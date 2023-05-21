<template>
  <div class="menuMobil">
    <v-layout>
      <v-app-bar :elevation="0" style="position: static">
        <v-btn density="default" icon="mdi-menu"></v-btn>
        <span class="menuTitle">Управление компани...</span>
        <v-btn density="default" icon="mdi-bell"></v-btn>
        <v-btn density="default" icon="mdi-cart"></v-btn>
      </v-app-bar>
    </v-layout>
  </div>
</template>

<script>
export default {
  name: 'MenuMobil',
}
</script>

<style>

.menuMobil {
  height: 51px;
  display: flex;

}

.menuTitle {
  font-family: Roboto, normal, serif;
  font-size: 17px;
  font-weight: 700;
  line-height: 24px;
  letter-spacing: 0;
  text-align: left;
  color: #3C3F41;
  font-style: normal;
}


</style>