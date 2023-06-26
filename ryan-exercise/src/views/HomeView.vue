<template>
  <div class="main">
    <div class="title">
      <h1 class="display-4">Home</h1>
    </div>
    <!-- <div id="Userinfo">

    </div> -->
  </div>
</template>

<script>
  // export default {
  //   name: 'HomeView'
  // }
  // async function UserData(){
  //   const data = await fetch('https://rayhaank.github.io/JSON-Server/server.json')
  //   const jsonData = await data.json()
  //   console.log(jsonData);
  //   let peopleData = jsonData.people
  //   const display = document.querySelector("#Userinfo")

  //    peopleData.forEach(data => {
  //     display.innerHTML += `
  //     <div class="card">
  //       <div class="card-body">
  //         <h3 class="card-title">${data.firstName},${data.lastName}}</h3>
  //         <p class="card-text">${data.age}}</p>
  //         </div>
  //       </div>
  //     `
  //   })
  // }
  // UserData()
</script>

<style  scoped>
    .main{
      background-color: brown;
      /* height: 100vh; */
      width: 100%;
    }
    
    .title {
      padding: 1rem;
      color: black;
      font-size: 2rem ;
      text-decoration: underline;
    }
</style>