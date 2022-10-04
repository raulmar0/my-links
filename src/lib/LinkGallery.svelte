<script>
  import { AppConfig } from '../utils/AppConfig.js';
</script>

<div class="flex flex-col">
  {#each AppConfig.links as link}
    <button class="m-2">
      <a href={link.url} target="_blank" class="w-full relative inline-block group focus:outline-none focus:ring">
        <span class="shadoww absolute inset-0 transition-transform translate-x-1.5 translate-y-1.5 bg-gradient-to-r from-violet-500 to-fuchsia-500 group-hover:translate-y-0 group-hover:translate-x-0"></span>
    
        <span class="shadoww w-full relative inline-block px-8 py-3 text-sm font-bold tracking-widest text-white uppercase border-2 border-current group-active:text-opacity-75">
          {link.title}
        </span>
      </a>
    </button>
  {/each}
</div>

<style>
  .shadoww {
    box-shadow: 1px 1px 10px #000;
  }
</style>

