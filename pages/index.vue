<template>
  <div class="container">
    <img class="image" src="/images/waterfall.jpg" alt="waterfall" />
    <img class="image" src="/images/forest.jpg" alt="forest" />
    <img class="image" src="/images/hills.jpg" alt="hills" />
    <img class="image" src="/images/forest-hill.jpg" alt="forest-hill" />
    <img class="image" src="/images/island.jpg" alt="island" />
    <img class="image" src="/images/beach.jpg" alt="beach" />
    <img class="image" src="/images/lake.jpg" alt="lake" />
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

.image {
  display: block;
  height: auto;
  max-width: 100%;
  object-fit: contain;
}

.image + .image {
  margin-top: 4rem;
}
</style>
