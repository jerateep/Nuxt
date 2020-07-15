<template>
  <div>
    <h1>Admin Page.</h1>
    <PostList/>
  </div>
</template>

<script>
import PostList from '@/components/posts/PostList'
export default {
  layout:"coreLayout",
  components:{
    PostList
  }
}
</script>

<style>

</style>