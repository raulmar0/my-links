<script>
import LinkGallery from './lib/LinkGallery.svelte'
import { AppConfig } from './utils/AppConfig.js';
import "./app.css"
import SkullNft from './assets/skullnft.webp'
</script>

<div class="contenedor">
  <main class="max-w-xs">
    <div class="shadow-2xl w-8/12 mx-auto my-5">
      <img class="" src={SkullNft} alt={AppConfig.profile.alt}>
      <h1 class="bg-white font-bold text-center p-2">{AppConfig.profile.title}</h1>
    </div>
    <LinkGallery />
  </main>
</div>

<style>

</style>
