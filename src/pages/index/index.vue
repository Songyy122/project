<template>
  <div class="container">
    <div class="message">{{msg}}</div>
    <!-- <vue-qr :logoSrc="imageUrl" text="xxx" :size="200"></vue-qr> -->
  </div>
</template>

<script>
// import vueQr from 'vue-qr'
export default {
  name: 'qecode',
  data() {
    return {
      imageUrl: '',
      msg: 'hhh',
    };
  },
  // components: {
  //   vueQr
  // },
};
</script>

<style scoped>
.message {
  color: red;
  padding: 10px;
  text-align: center;
}
</style>