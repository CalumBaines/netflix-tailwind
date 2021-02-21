<template>
  <section>
    <div
      class="absolute inset-0 -z-10 h-screen w-full bg-cover bg-right bg-hero-image"
    ></div>
    <div class="px-16 grid grid-cols-5 gap-4 mt-32">
      <div class="col-span-2">
        <img
          class="w-full mb-6"
          src="~/assets/images/parks-rec-logo.webp"
          alt="Parks rec"
        />
        <h1 class="text-white text-2xl mb-8">
          An uber-ambitious public worker lights a fire under her apathetic
          colleagues. Hilarity is inevitable.
        </h1>
        <div class="flex">
          <button
            class="mr-3 flex items-center text-black bg-white py-2 pl-6 pr-8 rounded text-xl font-bold"
          >
            <i class="mr-3 fas fa-play"></i>
            Play
          </button>
          <button
            class="flex items-center text-white bg-white bg-opacity-25 py-2 pl-6 pr-8 rounded text-xl font-bold"
          >
            <i class="mr-3 fas fa-info-circle"></i>
            More Info
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style></style>
