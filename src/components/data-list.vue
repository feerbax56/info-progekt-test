<template>
  <div class="dataList">
    <PaginationBlock/>
    header
    данные из json
    <PaginationBlock/>
  </div>
</template>

<script>
import PaginationBlock from "@/components/pagination-block.vue";

export default {
  name: 'DataList',
  components: {PaginationBlock}
}
</script>

<style>
.dataList{
  width: 370px;
  min-height: 200px;
}
</style>