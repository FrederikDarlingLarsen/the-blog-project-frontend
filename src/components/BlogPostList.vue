<template>
   <div class="postList">
    <ul class="theList" v-for="post in blogPosts" :key="post.id">
        <BlogPostItem :blogPost=post />
    </ul>
   </div>
</template>


<script>
import BlogPostItem from './BlogPostItem.vue';

export default {
    name: 'BlogPostList',
    components: {
        BlogPostItem
    },
    props:['blogPosts']
}
</script>

<style scoped>

.theList{
    align-items: center;
    text-align: center;
}

</style>


