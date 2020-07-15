<template>
 <b-col>
  <b-card
    :title=title
    :img-src=img
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      {{content}}
    </b-card-text>

    <b-button href="#" variant="primary">อ่าน</b-button>
  </b-card>
</b-col>
</template>

<script>
export default {
    props:{
       id:{
        type:String,
        required:false
      },
      title:{
        type:String,
        required:true
      },
       content:{
        type:String,
        required:false
      },
       img:{
        type:String,
        required:false
      }
    }
}
</script>

<style>

</style>