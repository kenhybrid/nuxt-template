<template>
  <div class="cover">
    <section class="height" style="background-color: red">

    </section>
    <section class="height" style="background-color: yellow"></section>
    <section class="height" style="background-color: green"></section>
    <section class="height" style="background-color: blue"></section>
  </div>
</template>

<script>
export default {}
</script>
<style>

section {
  height: 100vh;
  scroll-snap-align: start;
  overflow-x: hidden;

}
.cover {
  /* margin: -8px; */
  overflow-x: hidden;
  scroll-snap-type: y mandatory;
  overflow-y: scroll;
  height: 100vh;
  width: 100vw;
}
.white{
  background-color: #fff;
  height:44vh;
  max-width: 100%;
  margin: 3vh;
  border-radius: 10px;
}
</style>
