<template>
  <div>
    <b-carousel id="Slider" controls indicators>
      <div v-for="item in items">
        <b-carousel-slide
          :caption=item.caption
          :text=item.text
          :img-src=item.image>
        </b-carousel-slide>
      </div>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data(){
    return {
      items:[
        {caption:"A",image:require("@/assets/images/pic1.jpg"),text:"test 1"}
        ,{caption:"B",image:"https://picsum.photos/1024/480/?image=38",text:"test 2"}
        ,{caption:"C",image:"https://picsum.photos/1024/480/?image=32",text:"test 3"}
        ,{caption:"D",image:"https://picsum.photos/1024/480/?image=33",text:"test 4"}
        ]
    }
  }
}
</script>

<style>

</style>