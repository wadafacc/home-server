<template>
  <div class="sidebar-container">
    <img
      class="logo box"
      src="~/assets/smurfhat-light.png"
      alt=""
      @click="expand()"
    />

    <div class="side-nav box" id="menu">
      <img
        class="icon"
        id="stats"
        :src="require(`~/assets/icons/stats-light.png`)"
        alt=""
        @click="activateTab('stats')"
      />
      <img
        class="icon"
        id="container"
        src="~/assets/icons/container-light.png"
        alt=""
        @click="activateTab('container')"
      />
      <img
        class="icon"
        id="drive"
        src="~/assets/icons/drives-light.png"
        alt=""
        @click="activateTab('drive')"
      />
    </div>
  </div>
</template>

<style scoped src="~/styles/sidebar.css">
</style>

<script>
export default {
  methods: {
    expand() {
      const nav = document.getElementById("menu");
      console.log(nav.style.height);
      if (nav.style.height != "30%") {
        nav.style.height = "30%";
      } else {
        nav.style.height = "0%";
      }
    },
    activateTab(i) {
      console.log(i);
    },
  },
};
</script>