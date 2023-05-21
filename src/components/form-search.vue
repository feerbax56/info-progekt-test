<template>
  <div class="formSearch">
    <v-text-field
        v-model="search"
    ></v-text-field>
  </div>
</template>

<script>
export default {
  name: 'FormSearch',
  data() {
    return {
      search: 'Быстрый поиск',
    }
  }
}
</script>

<style>
.formSearch {
  width: 338px;
  height: 37px;
  margin: 0 auto;
}
</style>