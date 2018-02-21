<template>
  <v-carousel delimiter-icon="stop">
    <v-carousel-item v-for="(item,i) in items" :src="item.src" :key="i"></v-carousel-item>
  </v-carousel>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://s3.amazonaws.com/vuetify-docs/static/doc-images/carousel/squirrel.jpg'
          },
          {
            src: 'https://s3.amazonaws.com/vuetify-docs/static/doc-images/carousel/sky.jpg'
          },
          {
            src: 'https://s3.amazonaws.com/vuetify-docs/static/doc-images/carousel/bird.jpg'
          },
          {
            src: 'https://s3.amazonaws.com/vuetify-docs/static/doc-images/carousel/planet.jpg'
          }
        ]
      }
    }
  }
</script>
