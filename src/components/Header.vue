<template>
  <div
    fluid
    :style="'background:url('+headerImage+'); background-size: contain; background-repeat: no-repeat; background-position: center;'"
  ></div>
</template>

<script>
import headerImage from "../assets/images/headerImage.jpg";

export default {
  name: "Header",
  data: () => {
    return {
      headerImage: headerImage,

      data: () => ({
        drawer: false
      })
    };
  }
};
</script>

<style scoped>
div {
  height: 600px;
  text-align: right;
}
@media (max-width: 600px) {
  div {
    height: 350px;
  }
}
</style>

