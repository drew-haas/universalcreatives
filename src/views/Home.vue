<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/uc-logo-v1.png">
    <!-- <p>I'm baby brooklyn paleo pork belly, chicharrones live-edge mumblecore vegan man bun. Williamsburg actually hoodie sriracha. Portland mumblecore affogato 8-bit, vaporware poutine helvetica brunch narwhal vinyl shoreditch kale chips. Gluten-free beard jianbing butcher meditation four dollar toast. Sartorial put a bird on it bushwick lomo celiac polaroid. Pop-up lyft kitsch banjo cronut tousled YOLO iPhone cliche.</p> -->
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {}
}
</script>

<style lang="scss">
.home {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #fff;

  &.dark-mode {
    filter: invert(100%);
  }

  img {
    max-width: 200px;
    transform: translateX(-17px);
  }

  p {
    max-width: 350px;
    text-align: justify;
    margin-top: 50px;
    font-weight: bold;
    line-height: 1.7;
  }
}
</style>