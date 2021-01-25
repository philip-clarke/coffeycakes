<template>
  <section>
    <h1 class="red">Hello World</h1>

    <div class="row">
      <div class="item"></div>
      <div class="item"></div>
      <div class="item"></div>
      <div class="item"></div>
      <div class="item"></div>
      
    </div>
  </section>
</template>

<script>
export default {
  layout: "gallery",
};
</script>

<style>
.item {
  width: 200px;
  height: 300px;
  background-color: aqua;
  background-image: url("https://via.placeholder.com/200x300");
  margin: 10px 10px;
  border: 1px solid red;
  flex-shrink: 0;
}

.row {
  display: flex;
  overflow-x: auto;
}
</style>