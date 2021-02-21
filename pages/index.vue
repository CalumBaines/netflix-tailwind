<template>
  <div>
    <Header />
    <Hero />
    <section
      class="absolute bottom-0 w-full bg-gradient-to-t from-black to-transparent"
    >
      <div class="px-16">
        <h2 class="text-2xl font-bold text-white">Popular on Netflix</h2>
      </div>
      <div class="w-full px-16 py-4 flex overflow-x-auto">
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail.jpg"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-2.webp"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-3.webp"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-4.jpg"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-5.webp"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-6.webp"
          alt="Parks rec"
        />
        <img
          class="w-1/6 pr-1 rounded"
          src="~/assets/images/thumbnail-7.jpg"
          alt="Parks rec"
        />
      </div>
    </section>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Hero from '../components/Hero.vue'
export default {
  components: { Header, Hero },
}
</script>
