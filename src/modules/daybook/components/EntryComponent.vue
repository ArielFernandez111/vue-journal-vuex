<template>
  <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: {  id: 10 } })"
  >
      <div class="entry-title d-flex">
          <span class="text-success fs-5 fw-bold">16</span>
          <span class="mx-1 fs-5">Marzo</span>
          <span class="mx-2 fw-light">2022, Miercoles</span>
      </div>
      <div class="entry-description">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatum sapiente ducimus nostrum debitis molestias neque totam nesciunt enim architecto harum praesentium non voluptates tenetur ut eaque quis nulla dicta, iste culpa dolor, cum modi. Autem laborum nihil est odio, quisquam soluta atque temporibus qui enim ipsam omnis dignissimos voluptate maxime.
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scope>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description{
        font-size: 12px;
    }
}
</style>