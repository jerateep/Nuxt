<template>
  <strong> Welcome : {{$route.params.id}}</strong>
</template>

<script>
export default {
  validate(data){
    return /^\d+$/.test(data.params.id)
    //regular expression check id ต้องส่งเป็นตัวเลขเท่านั้น
  }
}
</script>

<style>

</style>