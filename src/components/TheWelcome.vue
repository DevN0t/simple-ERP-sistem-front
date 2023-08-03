<template>

  <div class="main">
    <div v-for="(user, index) in data" :key="user.id">
      {{ index }} - {{ user.cliente_name }}
    </div>
  <button @click="getMessage">Exibir Lista Clientes</button>
  </div>
</template>

<script>
import axios from "axios";
export default {
  data(){
    return{
      data: "",
      headers:{
      'Content-Type': 'application/json',
      'Authorization':'Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJhdXRoLWFwaSIsInN1YiI6IkpPQU8iLCJleHAiOjE2OTA5NjQxMDZ9.rk2NpkpDcW7X4mkGxpPVzc0LZD3xP7wkQbqTakWKqiY'
        
    }
    }
  },
  methods:{
    async getMessage(){
      await axios
    .get('http://localhost:8080/client/visualize')
    .then(res => this.data = res.data)
    }
  }
  
 

}
</script>

<style scoped>
  .main{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f3f3f3; 
    color: rgb(55, 55, 55);
    font-size: 3rem;
    height: 100%;
    border-top-left-radius: 40px;
    border-bottom-left-radius: 40px;
  }
</style>

