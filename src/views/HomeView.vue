<template>
   <NavBar/>
   <Hero/>
   <carousel/>
</template>

<script>
import NavBar from '@/components/Navbar-comp.vue'
import Hero from '@/components/Hero-comp.vue'
import carousel from '@/components/Carousel-comp.vue'
export default {
  name: "Nav",
  components: {NavBar,Hero, carousel}
}
</script>
