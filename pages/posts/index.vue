<template>
  <b-container fluid = "md">
    <Logo/>
    <h1>Posts</h1>
    <Header/>
    <PostList/>
  </b-container>
</template>

<script>
import Logo from '@/components/Logo'
import Header from '@/components/posts/Header'
import PostList from '@/components/posts/PostList'
export default {
  layout:"coreLayout",
  components:{
    Header
    , Logo
    , PostList
  }
}
</script>

<style>

</style>