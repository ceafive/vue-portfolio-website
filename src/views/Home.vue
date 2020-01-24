<template>
  <div class="bg-devdarkblue mx-24 my-12 shadow-2xl">
    <TheNavbar />
    <div class="flex flex-wrap xl:py-20">
      <div class="w-1/2 text-white leading-none p-20">
        <h1 class="text-6xl">Full Stack Web Developer</h1>
        <p class="font-thin text-gray-400 py-6">
          My name is
          <span class="text-4xl text-devblue2">CASTRO AGBO</span> and I am a web
          developer. My stack experience includes the MERN (MongoDB, ExpressJs,
          ReactJs and NodeJs). I also use CMS like WordPress and I am well
          versed in front-end libraries like Bootstrap 4, TailWind CSS and
          Semantic UI...
        </p>

        <router-link to="/portfolio">
          <button class="button-devred text-2xl py-2 px-8">Portfolio</button>
        </router-link>
      </div>
      <div class="w-1/2">
        <img
          class="shadow-2xl"
          src="@/assets/images/new.png"
          alt="right-side-image"
        />
      </div>
    </div>
    <div class="text-white text-center my-2 font-thin">
      Coded with
      <span class="text-red-700 text-xl">&hearts;</span> by &copy; Castro Agbo.
      2019
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import TheNavbar from "@/components/TheNavbar";
export default {
  name: "home",
  components: {
    TheNavbar
  },
  beforeCreate: function() {
    document.body.className = "bg-devblue2";
  }
};
</script>
