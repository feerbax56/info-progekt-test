<template>
    <div class="app">
      <MenuMobil/>
      <TabItems/>
      <FormSearch/>
      <BtnBlock/>
      <DataList/>
    </div>
</template>

<script>
import MenuMobil from "@/components/menu-mobile.vue";
import TabItems from "@/components/tab-items.vue";
import FormSearch from "@/components/form-search.vue";
import BtnBlock from "@/components/btn-block.vue";
import DataList from "@/components/data-list.vue"

export default {
  components: { BtnBlock, FormSearch, TabItems, MenuMobil, DataList}

}
</script>

<style>
.app {
  max-width: 370px;
  height: 812px;
  background-color:#FFFFFF;
  margin: 20px auto;
  display: flex;
  flex-direction: column;
}
body{
  background-color: #f5f5f5;
}
</style>