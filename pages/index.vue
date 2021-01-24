<template>
  <section class="hero">
    <svg
      class="curve"
      xmlns="http://www.w3.org/2000/svg"
      width="100"
      height="100"
      viewBox="0 0 256 318"
    >
      <path
        d="M2.7 0.4c0 0-12.5 31.2 16.8 39.1 29.2 7.9 35.5 7.8 42.8 33.6 7.3 25.8-14.8 24.9 0 55.4 14.8 30.5 43.6 10.9 65.7 43.5 12.2 18 10.3 48.6 41.8 54.2 36.6 6.5 33.9 24.7 32.2 40.3 -5.4 50.5 34.3 37.9 47.8 51.1 13.5 13.2 0-317.1 0-317.1l-247.1 0Z"
        class="b"
      />
    </svg>

    <div class="square"></div>
    <div class="title">Title1</div>
    <div class="subtitle">Subtitle</div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";
import IconLink from "~/components/IconLink.vue";

export default {
  components: {
    Logo,
    IconLink,
  },
};
</script>

<style scoped>


.title {
  display: absolute;
  top: 120px;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-weight: 400;
  font-size: 100px;
  color: #2E495E;
  letter-spacing: 1px;
  font-size: 6em;
}

.subtitle {
  top: 240px;
  font-weight: 300;
  font-size: 3em;
  color: #2E495E;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

body {
  position: relative;
  margin: 0;
  padding: 0;
  background-color: #8d8d8d;
  width: 100%;
  height: 100%;
}
.curve {
  width: 25%;
  height: 25%;
  float: right;
  fill: rgb(191 191 61);
}
</style>
