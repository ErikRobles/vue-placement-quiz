<template>
  <div id="app">
    <HeaderSection />
    <QuestionSection />
  </div>
</template>
<script>
import HeaderSection from "/components/HeaderSection";
import QuestionSection from "/components/QuestionSection";
export default {
  name: "App",
  components: {
    HeaderSection,
    QuestionSection
  }
};
</script>