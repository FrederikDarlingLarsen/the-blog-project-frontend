<template>
<li class="item">
    <h3>{{blogPost.title}}</h3>

    <p>{{blogPost.text}}</p>

    <p>Likes: {{blogPost.likes}}</p>

    <a href="">read more</a>
</li>

</template>

<script>
export default{
    name:'BlogPostItem',
    props:['blogPost']
}
</script>

<style scoped>

.item{
    background-color: gainsboro;
    width: 30%;
    list-style: none;
}


</style>