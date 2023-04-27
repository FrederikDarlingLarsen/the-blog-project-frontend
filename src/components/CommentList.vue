<template>
    <p>This is a list of comments</p>
  <ul>
    <div class="loop">
      <CommentItem />
    </div>
  </ul>
</template>

<script>
import CommentItem from './CommentItem.vue';

export default{
    name: 'CommentList',
    components: {
        CommentItem
    }
}
</script>

<style scoped></style>
