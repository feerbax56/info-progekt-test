<template>
  <div class="btnBlock">
    <v-btn rounded="xl" prepend-icon="mdi-filter-variant" append-icon="mdi-numeric-1-circle" size="small" >
      Фильтры
    </v-btn>
    <v-btn rounded="xl" color="primary" size="small">
      <v-icon icon="mdi-plus"/>
      Добавить
    </v-btn>
  </div>
</template>

<script>
export default {
  name: 'BtnBlock',
}
</script>

<style>
.btnBlock {
  display: flex;
  margin: 8px auto;

}
</style>