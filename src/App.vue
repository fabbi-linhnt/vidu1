<template>
  <div id="app">
    <div class="container">
      <LeftContainer />
      <RightContainer />
    </div>
  </div>
</template>

<script>
import LeftContainer from "@/components/LeftContainer"
import RightContainer from "@/components/RightContainer"

export default {
  name: 'App',
  components: {
    LeftContainer,
    RightContainer,
  }
}
</script>

<style scoped>
#app {
  background-image: url("./assets/texture.png");
  padding: 150px 0;
  height: 100vh;
}
.container {
  width: 80%;
  height: 60vh;
  margin: auto;
  background: whitesmoke;
  padding: 100px 50px;
  display: flex;
  border-radius: 10px;
  box-shadow: 0 0 15px aqua;
}
</style>
