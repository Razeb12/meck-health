<template>
  <div>
    <h1 class="title">How to Report An Emergency</h1>
    <div class="container">
      <div class="item">
        <h5 class="desc_text">
          On tap <br />
          <q>Report Emergency</q>
        </h5>
        <img
          :src="require('../assets/phone mockphone-mock-1.png')"
          class="img"
          alt="image-1"
        />
      </div>
      <div class="item">
        <h5 class="desc_text">
          <q>Allow location access</q> <br />
          On 1st time use
        </h5>
        <img
          :src="require('../assets/phone mockphone-mock-2.png')"
          alt="image-2"
          class="img"
        />
      </div>
      <div class="item">
        <h5 class="desc_text_3">
          Double tap sends <br />
          toast notification
        </h5>
        <img
          :src="require('../assets/phone mockphone-mock-3.png')"
          alt="image-3"
          class="img"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Section",
};
</script>

<!-- limit CSS to this component only -->
<style scoped>
.title {
  text-align: center;
  font-weight: 700;
  font-size: 45px;
  margin-top: 62px;

  text-transform: uppercase;
}
.container {
  display: flex;
  width: 100%;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 65px;
}

.item + .item {
  margin-left: 2.5%;
}
.img {
  height: 745px;
  filter: drop-shadow(30px 10px 4px grey);
}

.desc_text {
  text-align: center;
  font-size: 25px;
  font-weight: 400;
}
.desc_text_3 {
  text-align: center;
  font-size: 25px;
  font-weight: 400;
}
@media only screen and (max-width: 760px) {
  .title {
    font-size: 40px;
  }
  .img {
    width: 100%;
  }
}
</style>
