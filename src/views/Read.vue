<template>
  <p>
    <span :key="verse.id" v-for="verse in kjv">{{ verse.verse_text }}</span>
  </p>
</template>

<script>
import kjv from "@/json/kjv.json";
export default {
  name: "Read",
  data() {
    return {
      kjv: kjv
    };
  },
  mounted() {
    this.kjv.forEach(verse => console.log(verse));
  }
};
</script>
