<template>
  <div>
    <h2>About</h2>
    <p>
      Aute excepteur officia amet officia Lorem ex. Reprehenderit qui
      exercitation irure velit duis. Proident quis commodo ullamco cupidatat
      Lorem sit laboris voluptate. Elit et eiusmod minim duis eiusmod amet culpa
      amet incididunt. Laboris magna officia cillum fugiat anim et do sit amet
      Lorem nostrud consectetur consectetur. Dolore nostrud eu amet cupidatat
      pariatur esse.
    </p>
    <p>
      Aute excepteur officia amet officia Lorem ex. Reprehenderit qui
      exercitation irure velit duis. Proident quis commodo ullamco cupidatat
      Lorem sit laboris voluptate. Elit et eiusmod minim duis eiusmod amet culpa
      amet incididunt. Laboris magna officia cillum fugiat anim et do sit amet
      Lorem nostrud consectetur consectetur. Dolore nostrud eu amet cupidatat
      pariatur esse.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
// const { data } = await useFetch("/api/ninja?name=mario", {
//   method: "post",
//   body: { age: 30 },
// });

// const { data } = await useFetch("/api/ninja");

const { data } = await useFetch("/api/currency/GBP");
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
