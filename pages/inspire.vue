<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: 'https://imgur.com/i2O98d3.jpg',
        },
        {
          src: 'https://imgur.com/xYfgSnq.jpg',
        },
        {
          src: 'https://imgur.com/YrXCSMG.jpg',
        },
        {
          src: 'https://imgur.com/Cke7e5B.jpg',
        },
      ],
    }
  },
}
</script>
<style></style>
