<template>
  <div class="commentSection">
    <h3>this is the comment section</h3>

    <textarea name="" id="" cols="30" rows="10">write a comment here</textarea>

    <button>post comment</button>

    <CommentList />
  </div>
</template>

<script>
import CommentList from "./CommentList.vue";

export default {
  name: "CommentSection",
  components: {
    CommentList,
  },
};
</script>

<style scoped></style>
