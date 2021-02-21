<template>
  <div>
    <Header />
    <Hero />
    <popular-list />
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Hero from '../components/Hero.vue'
import PopularList from '../components/PopularList.vue'
export default {
  components: { Header, Hero, PopularList },
}
</script>
