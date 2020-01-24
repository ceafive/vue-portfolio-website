<template>
  <div>
    <nav class="flex justify-between py-3 px-12">
      <div class="flex text-sm border border-devblue2">
        <router-link to="/">
          <span
            class="flex items-center text-devdarkblue bg-devblue2 text-sm text-xl h-full px-2"
            >ceafive_dev</span
          >
        </router-link>
      </div>
      <div class="flex items-center">
        <div class="flex flex-grow">
          <router-link to="/about">
            <div
              class="inline-block mr-4 text-lg text-devblue2 hover:text-white border-b-2 border-transparent hover:border-devblue2 cursor-pointer"
            >
              About
            </div>
          </router-link>
          <router-link to="/portfolio">
            <div
              class="inline-block mr-4 text-lg text-devblue2 hover:text-white border-b-2 border-transparent hover:border-devblue2 cursor-pointer"
            >
              Portfolio
            </div>
          </router-link>
        </div>
      </div>
    </nav>
    <hr class="border-devblue2" />
  </div>
</template>
