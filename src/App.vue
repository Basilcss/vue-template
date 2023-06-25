<template>
  <div>
    <FirstSection />
    <SecondSection />
    <ThirdSection />
  </div>
</template>

<script>
import FirstSection from "./components/FirstSection.vue"
import SecondSection from "./components/SecondSection.vue"
import ThirdSection from "./components/ThirdSection.vue"
export default {
  name: "App",
  components: {
    FirstSection,
    SecondSection,
    ThirdSection,
  },
}
</script>
