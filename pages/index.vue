<template>
  <div class="container">
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/waterfall.jpg"
      alt="waterfall"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/forest.jpg"
      alt="forest"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/hills.jpg"
      alt="hills"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/forest-hill.jpg"
      alt="forest-hill"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/island.jpg"
      alt="island"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/beach.jpg"
      alt="beach"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
    <nuxt-picture
      sizes="sm:200px md:400px lg:800px"
      src="/images/lake.jpg"
      alt="lake"
      loading="lazy"
      width="1024"
      height="800"
      quality="75"
    />
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  max-width: 1180px;
}

.container img {
  display: block;
  height: auto;
  max-width: 100%;
  object-fit: contain;
  margin-top: 4rem;
}
</style>
