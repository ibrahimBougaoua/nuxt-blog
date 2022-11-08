<template>
  <div>
    <p class="bg-orange-600 text-white text-xl text-center p-10">This page will be displayed at the /index route.</p>
  </div>
  <div class="flex  justify-center items-stretch h-96 bg-zinc-600">
    <div class="flex-col justify-between ">
      <h1 class="text-blue-700 m-2 p-2">dynamic trading</h1>
      <h1 class="bg-slate-400 text-6xl m-2 p-2">start trading in crypto instant</h1>
      <p class="bg-emerald-300 m-2 p-2">join world biggest and trusted exchangetrade bicoin</p>
      <div class="flex">
        <button class="bg-cyan-500 border-2 border-cyan-500 hover:bg-gray-400  text-white py-2 px-4 rounded-full w-36 ">
          start
        </button>
        <button class="bg-white border-2 hover:bg-gray-400 border-cyan-500 text-gray-800 font-bold py-2 px-4 rounded-full w-36">
          dowload
        </button>
      </div>

      <div class="pt-10 ">
        <h1 class="text-xl text-blue-900">featured companies</h1>
        <div class="flex space-x-10">
          <p>bibox</p>
          <p>monero</p>
          <p>bitcoindumy</p>
          <p>okex</p>
        </div>
      </div>
      
    </div>
    <div class="flex flex-grow">
      <img src="../images/header-img.png" alt="image">
    </div>
  </div>
</template>
  
<script>
  export default {
    name: 'IndexPage'
  }
</script>