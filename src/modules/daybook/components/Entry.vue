<template>
  <div class="entry-conitainer mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: {id: 10} })">
      <div class="entry-title d-lfex">
          <span class="text-success fs-5 fw-bold">15</span>
          <span class="mx-1 fs-5">Julio</span>
          <span class="mx-2 fw-light">2022, jueves</span>
      </div>
      <div class="entry-description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias veniam eaque commodi facilis blanditiis? Placeat iure excepturi ipsa obcaecati eveniet ipsum, unde totam itaque, corrupti accusamus possimus dolore reiciendis? Nemo!
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scope>
.entry-conitainer{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover {
        background-color: lighten($color: gray, $amount: 45);
        transition: 0.2s all ease-in;
    }
.entry-description{
    font-size: 12px;
}
}

</style>