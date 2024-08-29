<template>
  <el-row type="flex" class="navbar" justify="space-between">
    <el-col :span="6">
      <topbar></topbar>
    </el-col>
  </el-row>
</template>

<script>
import Topbar from "@/components/Topbar";

export default {
  name: "Navbar",
  components: {
    Topbar,
  },
  props: {
    isCollapse: {
      type: Boolean,
      default: false,
    },
  },
};
</script>
<style>
.navbar {
  background-color: rgba(43, 92, 238, 0.715);
  height: 100%;
  line-height: 60px;
  padding: 0 20px;
}
</style>
