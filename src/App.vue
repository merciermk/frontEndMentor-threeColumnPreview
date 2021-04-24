<template>
  <div>
    <div id="treeColumns">
      
        <column-left></column-left>
        <column-center ></column-center>
        <column-right ></column-right>
  
    </div>
    <myFooter></myFooter>
  </div>
</template>

<script>
import columnLeft from "./components/columnLeft.vue";
import columnCenter from "./components/columnCenter.vue";
import columnRight from "./components/columnRight.vue";
import myFooter from "./components/myfooter";

export default {
  data() {
    return {};
  },
  components: {
    myFooter,
    columnLeft,
    columnCenter,
    columnRight,
  },
};
</script>

