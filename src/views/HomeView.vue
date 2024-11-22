<script setup lang="ts">

</script>

<template>
  <main class=" w-full mt-4">
    <h2 class="text-center text-2xl mb-2">Samples from Original Coloring Book</h2>
    <div class="mx-1">
      <div class="gridSet">
        <div class="gridCell">
          <img class="" height="442" width="345"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732216061/9_ilqf4z.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="442" width="345"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052999/21_dyqpff.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="442" width="345"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052998/20_kpxvd9.png"/>
        </div>
      </div>

      <h2 class=" text-center my-2 text-2xl">Samples from Coloing Book #2</h2>
      <p class="mb-2 text-center italic text-xs">
        nurses, cowgirls, girls with glasses
      </p>
      <div class="gridSet">
        <div class="gridCell">
          <img class="" height="442" width="345"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732215974/piclumen-1732056806448_qym4sm.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="442" width="345"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140150/piclumen-1732056625315_mo2x6a.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="442" width="345"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140147/piclumen-1732056134661_yh9miv.png"/>
        </div>
      </div>

      <h2 class=" text-center my-2 text-2xl">Samples from Coloing Book #3</h2>
      <p class="mb-2 text-center italic text-xs">
        various anime girls
      </p>

      <div class="gridSet">
        <div class="gridCell">
          <img class=""
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732232325/anime_13_tkhny2.png"
            height="442" width="345"/>
        </div>
        <div class="gridCell">
          <img class=""
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732232328/anime_19_dmapvb.png"
            height="442" width="345"/>
        </div>
        <div class="gridCell">
          <img class=""
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732232322/anime_1_faadvb.png"
            height="442" width="345"/>
        </div>
      </div>

    </div>
  </main>
</template>
<style scoped>
  .gridSet{
    @apply grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3
  }

  .gridCell{
    @apply py-2 bg-gray-100 flex items-center justify-center
  }
</style>
