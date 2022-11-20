<template>
  <div class="home">
    <NavbarView />
    <HeaderView />
    <SliderView />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavbarView from "@/views/NavbarView.vue";
import HeaderView from "@/views/HeaderView.vue";
import SliderView from "@/views/SliderView.vue"; // @ is an alias to /src
import ReadView from "@/views/ReadView.vue"; // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    NavbarView,
    HeaderView,
    SliderView,
    ReadView
  },
});
</script>
