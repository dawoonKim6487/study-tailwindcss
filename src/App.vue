<template>
  <HelloTailWindCss />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloTailWindCss from "./components/HelloTailWindCss.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloTailWindCss,
  },
});
</script>
