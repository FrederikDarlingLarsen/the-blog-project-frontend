<template>
  
  <div class="blogPostPage">
    <h1>This is a page for an individual blog post</h1>

    <h2>Title here</h2>

    <p>text here</p>

    <span>likes here</span>

    <CommentSection />
  </div>
</template>

<script>
import CommentSection from "./CommentSection.vue";

export default {
  name: "BlogPostPage",
  components: {
    CommentSection,
  },
};
</script>

<style scoped></style>
