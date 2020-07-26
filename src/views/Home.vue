<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Bible msg="Welcome to Bible App" />
  </div>
</template>

<script>
// @ is an alias to /src
// import Chapter from "@/components/Chapter.vue";
// import Book from "@/components/Book.vue";
import Bible from "@/components/Bible.vue";

export default {
  name: "Home",
  components: {
    // Chapter,
    // Book,
    Bible
  }
};
</script>
