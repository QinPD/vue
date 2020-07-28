<template>
  <div class="app-container">
    <div>123123</div>
    <el-row>
      <el-col :span="24">
        <div>{{tittle}}</div>
      </el-col>
    </el-row>
  </div>
</template>

<script>

export default {
  name: 'Test',
  data() {
    return {
      tittle: 'title'
    }
  },
  created() {

  },
  methods: {

  }
}
</script>

