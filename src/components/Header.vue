<script setup lang="ts">

</script>
<template>
  <header class="text-center mt-4">
    <div class="m-2 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
      <div id="img" class="mx-auto w-full p-2 bg-gray-200 md:bg-gray-50">
        <img alt="Brad BernsXXX" class="mx-auto p-1 rounded-xl"
          src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732139973/brad_berns-2_pywfds.png" width="300" height="300" />
          <h1 class="text-3xl">
            Welcome to Brad's Beauties
          </h1>
        </div>
      <div id="intro" class="mx-auto">
        <div class=" text-left">
          <p class="mt-2 indent-1.5">
            Here you'll find AI created sketches of pretty women, perfect for coloring.
             Each zip file has over 20 images and each image is 1148 px (height) and 896 px (width).
             Feel free to download the complete zip files, or one of the samples below.
          </p>
           <ul id="zip_files" class="text-blue-500 mt-2 text-sm">
            <li class="">
              <a class=" hover:underline p-1" href="https://www.dropbox.com/scl/fi/ngfsxizqnqo5ttpinwv91/coloringbook.zip?rlkey=i1s4u539vdzstatbpht1ldj7e&st=u16xtq3y&dl=0">
              ColoringBook.zip | The Original
            </a>
            </li>
            <li class="my-2">
              <a class=" hover:underline p-1" href="https://www.dropbox.com/scl/fi/2re8a7o4xz96gqgsi02fr/coloringbook-2.zip?rlkey=xbg1sa6d3xrryh0vhke1rhdb6&st=ikxq8c0j&dl=0">
              ColoringBook-2.zip | nurses, cowgirls, girls with glasses
            </a>
            </li>
            <li class="my-2">
              <a class=" hover:underline p-1" href="https://www.dropbox.com/scl/fi/7wabxlucfcqd10qf3zs0h/coloringbook-3.zip?rlkey=p0dgyxv4rs9w6siifcgfxrilg&st=wk39z7nq&dl=0">
              ColoringBook-3.zip | various anime girls
            </a>
            </li>
          </ul>
        </div>
      </div>
      <div id="vid" class="mx-auto w-full p-2 bg-gray-200 md:bg-gray-50">
        <video  controls loop="true"
          class=" mt-1 p-2 bg-transparent lg:w-3/4 w-full rounded-lg mx-auto">
          <source
            src="https://res.cloudinary.com/dxbedpcbe/video/upload/v1732569610/angle-vid_pvhpva.webm"
            type="video/webm"
          />
          Your browser does not support the video.
        </video>
      </div>
    </div>
  </header>
</template>
