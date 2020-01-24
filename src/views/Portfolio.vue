<template>
  <div class="bg-devdarkblue m-6 xl:mx-24 xl:my-12 shadow-2xl">
    <TheNavbar />
  </div>
</template>

<script>
// @ is an alias to /src

import TheNavbar from "@/components/TheNavbar";
export default {
  name: "home",
  components: {
    TheNavbar
  }
};
</script>
