<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Exo:wght@400;500;700;900&display=swap");

.fontExo {
  font-family: "Exo", sans-serif;
}
.main_container {
  background: url("../../public/images/Group.png");
  opacity: 90%;
}

.image_container {
  background: url("../../public/images/player1.png");
}
</style>

<template>
  <div class="main_container mt-5 bg-cover bg-no-repeat">
    <div class="flex justify-around">
      <div class="mt-8">
        <h2 class="fontExo font-black mt-20 text-4xl w-[554px] h-[135px]">
          All The Ingredients of a Successful Sports Career Are Here
        </h2>
        <p class="fontExo text-3xl font-normal w-[554px]">
          You receive a clear blueprint and never have to second guess
          yourself. 
        </p>
      </div>
      <div class="flex">
        <img class="right h-3/4" src="~/public/images/player1.png" />
      </div>
    </div>
    <HomepageOptionsBox />
  </div>
</template>
