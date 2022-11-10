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
  <div class="grid grid-cols-3 bg-fuchsia-700 gap-3">
    <div class=" flex-col">
      <h1 class="text-blue-700 m-2 p-2">dynamic trading</h1>
      <h1 class="bg-slate-400 text-6xl m-2 p-2">start trading in few step</h1>
      <button class="bg-cyan-500 border-2 border-cyan-500 hover:bg-gray-400  text-white py-2 px-4 rounded-full w-36 ">
          start trading
      </button>

    </div>
    <div class="grid grid-cols-2 grid-rows-2 gap-3 col-span-2">
      <div class="bg-white border-2 flex justify-center"><span class="rounded-full w-20"> <img src="../images/imgacuille.PNG" alt="img"></span> <div> <h1 class="text-xl">create account</h1> <p>sign up with your email and mobil in just 5 minute</p></div></div>
      <div class="bg-white border-2 flex justify-center"><span class="rounded-full w-20"> <img src="../images/bank.PNG" alt="img"></span> <div> <h1 class="text-xl">verify your bank</h1> <p>verify your bank account in easy</p></div></div>
      <div class="bg-white border-2 flex justify-center"><span class="rounded-full w-20"> <img src="../images/wallet.PNG" alt="img"></span> <div> <h1 class="text-xl">add funf in wallet</h1> <p>quickly add money to your investement wallet</p></div></div>
      <div class="bg-white border-2 flex justify-center"><span class="rounded-full w-20"> <img src="../images/trade.PNG" alt="img"></span> <div> <h1 class="text-xl">start trading instatly</h1> <p>buy and sell variety of top coin at the best price</p></div></div>
    </div>

  </div>
</template>
  
<script>
  export default {
    name: 'IndexPage'
  }
</script>