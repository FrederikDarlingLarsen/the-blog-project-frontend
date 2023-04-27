<template>
  <div class="home">
   
    <BlogPostList :blogPosts=dummyData />
  </div>
</template>

<script>
import BlogPostList from "../components/BlogPostList.vue";

export default {
  name: "HomePage",
  components: {
    BlogPostList,
  },
  data() {
    
    return {
      
      dummyData: [
        {
          id: 1,
          title: "My exercise routine",
          text: "This is my exercise routine right now...",
          likes: 42,
          comments: [
            {
              id: 1,
              username: "Xarunah",
              comment: "Nice! Maybe I should try this!",
              timestamp: "03:00:43 20 April 2023",
            },
          ],
        },
        {
          id: 2,
          title: "Look at what i just built!",
          text: "I have created this awesome new LEGO model, please check it out...",
          likes: 23,
          comments: [
            {
              id: 1,
              username: "Darling",
              comment: "That is truly an awsome model",
              timestamp: "07:30:53 25 April 2023",
            },
          ],
        },
        {
          id: 3,
          title: "A post about Dragon Ball Z",
          text: "Thi is a post about the greatest anime...",
          likes: 9001,
          comments: [
            {
              id: 1,
              username: "Bulma",
              comment: "I love DBZ too!",
              timestamp: "17:20:33 15 April 2023",
            },
          ],
        },
      ],
    };
  },
  
};


</script>

<style scoped></style>
