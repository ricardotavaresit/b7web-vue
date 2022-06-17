<template>
  <div>{{ title }}</div>
</template>
 

 <script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  data() {
    return {
      title: "cenas",
    };
  },
});
</script>
 