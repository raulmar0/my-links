<script>
import LinkGallery from './lib/LinkGallery.svelte'
import { AppConfig } from './utils/AppConfig.js';
import "./app.css"
</script>

<main class="max-w-xs py-5 mx-auto">
  <div class="shadow-2xl w-8/12 mx-auto my-5">
    <img class="" src={AppConfig.profile.image} alt={AppConfig.profile.alt}>
    <h1 class="bg-white font-bold text-center p-2">{AppConfig.profile.title}</h1>
  </div>
  <LinkGallery />
</main>

<style>

</style>
