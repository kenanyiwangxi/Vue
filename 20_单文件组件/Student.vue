<template>
  <!--组件的结构-->
  <div>
    <h2>学校名称：{{ name }}</h2>
    <h2>学校地址：{{ age }}</h2>
  </div>
</template>

<script>
// 组件交互相关的代码(数据、方法等等)
export default {
  name:'Student',
  data() {
    return {
      name: '猪八戒',
      age: 20
    }
  }
}
</script>