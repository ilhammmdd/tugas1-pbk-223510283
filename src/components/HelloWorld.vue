<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      hey there, I'm Ilham, I'm an informatics engineering student at  <a href="https://uir.ac.id/" target="_blank" rel="noopener">UIR</a>. I'm enthusiastic about technology, especially in the field of data science
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 25px;
  position: relative;
  top: -10px;
  color: rgb(55, 55, 55);
}

h3 {
  font-size: 1.2rem;
  color: black;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
