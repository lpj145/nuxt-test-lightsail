<script>
export default {
  name: 'search'
}
</script>

<template>
  <div class="w-full h-screen">
    <div class="flex justify-center pt-12 h-screen">
      <div class="w-5/6 lg:w-1/3">
        <div class="text-center">
          <SearchLogo height="124" width="124" class="fill-current text-green-600 mx-auto mb-12" />
        </div>
        <div class="text-center mb-3">
          <h3 class="text-2xl">Teste de desempenho no lighthouse, <br> nuxt <small class="text-red-500">&#10084;</small> netlify.</h3>
        </div>
        <label>
          <input
            type="search"
            autofocus
            placeholder="Pesquisar por algum termo"
            class="px-3 py-2 border-2 w-full focus:border-blue-500 focus:outline-none"
          >
        </label>
        <div class="text-center mt-5">
          <button class="px-4 py-2 border bg-blue-700 text-white focus:outline-none rounded">
            Pesquisar por termo
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
