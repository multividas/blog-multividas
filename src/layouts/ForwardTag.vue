<template>
  <g-link class="g-link fw-bold text-primary mx-2" :to="path">
    <LeftSvg :x="16"></LeftSvg>
    <span class="ms-2">{{ text }}</span>
  </g-link>
</template>

<script>
import LeftSvg from "~/svgs/LeftSvg.vue"

export default {
  props: {
    path: {
      type: String,
      requied: true
    },
    text: {
      type: String,
      required: true
    }
  },
  components: {
    LeftSvg
  }
};
</script>

<style>
.g-link:hover {
  text-decoration: underline !important;
}
</style>
