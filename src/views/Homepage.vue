<template>
  <section>
    <div class="picture"></div>
    <h1>Thanks for attending our wedding.</h1>
    <p>Please click on the button below to donate.</p>
    <router-link to="/donate-page"><button>Donate</button></router-link>
    <img
      style="max-width: 200px; display: block; margin: 20px auto"
      alt="Vue logo"
      src="../assets/pstk.png"
    />
  </section>
</template>

<script>
export default {
  name: "Homepage",
  data() {
    return {};
  },
};
</script>

<style scoped>
.picture {
  width: 300px;
  height: 400px;
  border: 2px solid red;
  margin: 20px auto 50px;
}
h1 {
  font-size: 40px;
  color: tomato;
}
button {
  width: 200px;
  height: 50px;
  border-radius: 5px;
  background: teal;
  color: white;
  border: 0px;
}
button:hover {
  cursor: pointer;
  background-color: #8ebf42;
}
</style>