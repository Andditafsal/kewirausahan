<template>
  <div>
    <navbar />
    <hero />
    <render />
    <produk />
    <foot />
  </div>
</template>

<script>
import navbar from "../components/home/header.vue";
import hero from "../components/home/hero.vue";
import render from "../components/home/reader.vue";
import produk from "../components/home/produktampilan.vue";
import foot from "../components/home/footer.vue";
export default {
  data() {
    return {
      page_name: "index",
    };
  },
  components: {
    navbar,
    hero,
    render,
    produk,
    foot,
  },
};
</script>
