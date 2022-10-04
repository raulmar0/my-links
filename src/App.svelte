<script>
import LinkGallery from './lib/LinkGallery.svelte'
import { AppConfig } from './utils/AppConfig.js';
import "./app.css"
import SkullNft from './assets/skullnft.webp'
</script>

<div class="contenedor">
  <main class="max-w-xs">
    <div class="shadoww w-8/12 mx-auto my-5">
      <img class="" src={SkullNft} alt={AppConfig.profile.alt}>
      <h1 class="bg-white font-bold text-center p-2">{AppConfig.profile.title}</h1>
    </div>
    <LinkGallery />
  </main>
  <!-- <svg xmlns='http://www.w3.org/2000/svg'  width='250' height='30' viewBox='0 0 1000 120'><rect fill='#000000' width='1000' height='120'/><g  fill='none' stroke='#222' stroke-width='10' stroke-opacity='1'><path d='M-500 75c0 0 125-30 250-30S0 75 0 75s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/><path d='M-500 45c0 0 125-30 250-30S0 45 0 45s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/><path d='M-500 105c0 0 125-30 250-30S0 105 0 105s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/><path d='M-500 15c0 0 125-30 250-30S0 15 0 15s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/><path d='M-500-15c0 0 125-30 250-30S0-15 0-15s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/><path d='M-500 135c0 0 125-30 250-30S0 135 0 135s125 30 250 30s250-30 250-30s125-30 250-30s250 30 250 30s125 30 250 30s250-30 250-30'/></g></svg> -->
</div>

<style>
  .shadoww {
    box-shadow: 1px 1px 10px #000;
  }
</style>
