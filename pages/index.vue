<template>
  <section>
    <svg
      id="curve"
      viewBox="0 0 512 636"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      xml:space="preserve"
      xmlns:serif="http://www.serif.com/"
    >
      <g transform="matrix(1,0,0,1,-2521,-3277)">
        <g transform="matrix(1,0,0,1,-773.326,3277.85)">
          <g transform="matrix(1,0,0,1,884.365,-228)">
            <path
              d="M2415.4,228C2415.4,228 2390.49,290.391 2448.98,306.16C2507.46,321.93 2520.04,321.659 2534.64,373.31C2549.23,424.96 2505.1,423.11 2534.64,484.121C2564.18,545.133 2621.83,505.984 2666.05,571.148C2690.47,607.14 2686.69,668.301 2749.61,679.45C2822.72,692.403 2817.44,728.841 2814.11,760.058C2803.32,861.11 2882.7,835.81 2909.64,862.159C2936.57,888.508 2909.64,228 2909.64,228L2415.4,228Z"
            />
          </g>
        </g>
      </g>
    </svg>
    <div class="title">Title</div>
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
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 100px;
  color: #2E495E;
  letter-spacing: 1px;
  font-size: 6em;
}
.green {
  color: #00C48D;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #2E495E;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.section {
  position: relative;
  margin: 0;
  padding: 0;
  background: #8d8d8d;
  width: 100%;
  height: 100%;
}
#curve {
  width: 100%;
  height: 50%;
  fill: rgb(247, 239, 219);
}
</style>
