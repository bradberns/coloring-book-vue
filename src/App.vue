<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Footer from './components/Footer.vue'
</script>

<template>
  <header class="text-center mt-4">
    <div class="m-2 grid grid-cols-1 lg:grid-cols-2">
      <div id="img" class="mx-auto">
        <img alt="Vue logo" class="text-center p-1 rounded-xl"
          src="https://res.cloudinary.com/dxbedpcbe/image/upload/v1732139973/brad_berns-2_pywfds.png" width="300" height="300" />
      </div>
      <div id="intro" class="mx-auto lg:mx-10">
        <div class=" pl-2 text-left">
          <h1 class="text-3xl">
            Welcome to Brad's Beauties
          </h1>
          <p class="mt-2 indent-1.5">
            Here you'll find AI created sketches of pretty women, perfect for coloring.
             Each zip file has over 20 images and each image is 1148 px (height) and 896 px (width).
             Feel free to download the complete zip files, or one of the samples below.
          </p>
          <!-- <p class="my-2 indent-1.5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud
            exercitation ullamco laboris nisi ut aliquip ex ea
            commodo consequat. Duis aute irure dolor in reprehenderit
            in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident,
            sunt in culpa qui officia deserunt mollit anim id est
            laborum.
          </p> -->
          <ul class="text-blue-500 mt-2 text-sm">
            <li>
              <a class=" hover:underline p-1" href="https://www.dropbox.com/scl/fi/ngfsxizqnqo5ttpinwv91/coloringbook.zip?rlkey=i1s4u539vdzstatbpht1ldj7e&st=u16xtq3y&dl=0">
              ColoringBook.zip | The Original
            </a>
            </li>
            <li class="my-2">
              <a class=" hover:underline p-1" href="https://www.dropbox.com/scl/fi/2re8a7o4xz96gqgsi02fr/coloringbook-2.zip?rlkey=xbg1sa6d3xrryh0vhke1rhdb6&st=ikxq8c0j&dl=0">
              ColoringBook-2.zip | nurses, cowgirls, girls with glasses
            </a>
            </li>
          </ul>
          <!-- <p >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud
            exercitation ullamco laboris nisi ut aliquip ex ea
            commodo consequat. Duis aute irure dolor in reprehenderit
            in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident,
            sunt in culpa qui officia deserunt mollit anim id est
            laborum.
          </p> -->
        </div>
      </div>
    </div>
  </header>

  <RouterView />
  <Footer/>
</template>

<style scoped>

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
