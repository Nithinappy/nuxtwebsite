<template>
  <div>
    <Slider />
  </div>
</template>

<script>
import Slider from "~/components/slider.vue";
export default {
  name: "IndexPage",
  head() {
    return {
      title: "Panda App - Latest Latest Panda Info",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Get all the latest Latest Pandas",
        },
      ],
    };
  },
  components: {
    Slider,
  },
};
</script>
