<template>
  <div id="not-found">
    <div>
      <img src="static/images/not-found.png" alt=""
           style="width: 600px;">
      <div style="text-align: center">
        <h1>没有找到该页面...</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NotFound"
}
</script>

<style scoped>
#not-found {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
