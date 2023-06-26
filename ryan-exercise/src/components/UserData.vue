<template>
  <div class="main" id="Userinfo"></div>
</template>

<script>
async function UserData() {
  const data = await fetch(
    "https://rayhaank.github.io/JSON-Server/server.json"
  );
  const jsonData = await data.json();
  console.log(jsonData);
  let peopleData = jsonData.people;
  const display = document.querySelector("#Userinfo");

  peopleData.forEach((data) => {
    display.innerHTML += `
    <div class="container-fluid p-2">
        <div class="card" style="background-color: cadetblue">
          <div class="card-body">
            <h3 class="card-title">${data.firstName} ${data.lastName}</h3>
            <p class="card-text">${data.age}</p>
            </div>
          </div>
        </div>
      `;
  });
}
UserData();
</script>

<style scoped>
    .main {
        background-color: brown;
    }
</style>
