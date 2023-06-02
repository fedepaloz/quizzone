<template>
  <div id="app">
    <MainHeader></MainHeader>
    <QuizCard></QuizCard>
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import QuizCard from "./components/QuizCard.vue";
export default {
  name: "App",
  components: {
    MainHeader,
    QuizCard,
  },
};
</script>

<style></style>
