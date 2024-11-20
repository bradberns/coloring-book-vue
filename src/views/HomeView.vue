<script setup lang="ts">

</script>

<template>
  <main class=" w-full mt-4">
    <h2 class="text-center text-2xl mb-2">Samples from Original Coloring Book</h2>
    <div class="mx-1">
      <div class="gridSet">
        <div class="gridCell">
          <img class="" height="200" width="156"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052999/21_dyqpff.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052998/20_kpxvd9.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052581/18_u1svcx.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732052580/17_i7khkp.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
              src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732049349/16_tugsdj.png"/>
        </div>
      </div>

      <h2 class=" text-center my-2 text-2xl">Samples from Coloing Book #2</h2>

      <div class="gridSet">
        <div class="gridCell">
          <img class="" height="200" width="156"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140150/piclumen-1732056625315_mo2x6a.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140147/piclumen-1732056134661_yh9miv.png"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140144/piclumen-1732055381249_zxa02k.png"/>
        </div>
        <div class="gridCell">
          <img class=""
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140142/piclumen-1732055116114_luiuq9.png"
            height="200" width="156"/>
        </div>
        <div class="gridCell">
          <img class="" height="200" width="156"
            src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732140139/piclumen-1732054301607_kdqu7y.png"/>
        </div>
      </div>
    </div>
  </main>
</template>
<style scoped>
  .gridSet{
    @apply grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5
  }

  .gridCell{
    @apply py-2 bg-gray-300 flex items-center justify-center
  }
</style>
