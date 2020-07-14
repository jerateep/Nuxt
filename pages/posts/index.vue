<template>
  <b-container fluid>
    <Logo/>
    <h1>Posts</h1>
    <Header/>
    <b-row class="py-2">
      <PostContant/>
      <PostContant/>
      <PostContant/>
    </b-row>
  </b-container>
</template>

<script>
import Logo from '@/components/Logo'
import Header from '@/components/posts/Header'
import PostContant from '@/components/posts/PostContant'
export default {
  layout:"coreLayout",
  components:{
    Header
    , Logo
    , PostContant
  }
}
</script>

<style>

</style>