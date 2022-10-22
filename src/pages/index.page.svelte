<script lang="ts">
  import ssrLogo from '../assets/vite-plugin-ssr.svg'
  import svelteLogo from '../assets/svelte.svg'
  import tailwindLogo from '../assets/tailwindcss-mark.svg'
  import Counter from '../lib/Counter.svelte'
  import Layout from './__layout.svelte'
</script>

<Layout>
  <div class="flex flex-col justify-center w-full h-full m-0 absolute text-center dark:bg-gray-800 dark:text-gray-50">
    <div class="flex place-content-center">
      <a href="https://vitejs.dev">
        <img src="/vite.svg" class="h-12 m-6 hover:drop-shadow-[0_0_2em_#646cffaa]" alt="Vite Logo" />
      </a>
      <a href="https://vite-plugin-ssr.com">
        <img src={ssrLogo} class="h-12 m-6 hover:drop-shadow-[0_0_2em_#4400d6aa]" alt="Vite Plugin SSR Logo" />
      </a>
      <a href="https://svelte.dev">
        <img src={svelteLogo} class="h-12 m-6 hover:drop-shadow-[0_0_2em_#ff3e00aa]" alt="Svelte Logo" />
      </a>
      <a href="https://tailwindcss.com">
        <img src="{tailwindLogo}" class="h-12 m-6 tailwind hover:drop-shadow-[0_0_2em_#38bdf8]" alt="Tailwind CSS Logo" />
      </a>
    </div>
    <p class="text-5xl">Vite + SSR + Svelte + Tailwind</p>

    <div class="p-8">
      <Counter />
    </div>

    <p>
      Check out <a class="text-blue-400 hover:text-blue-600" href="https://github.com/sveltejs/kit#readme">SvelteKit</a>,
      the official Svelte app framework powered by Vite!
    </p>

    <p class="text-gray-500">
      Click on the Vite, vite-plugin-ssr, Svelte and Tailwind logos to learn more
    </p>
  </div>
</Layout>