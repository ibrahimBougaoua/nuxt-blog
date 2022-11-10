<template>
  <div class="flex justify-between py-10">

    <div class="flex flex-col">
      <div class="flex flex-col space-y-4">
        <div>
          <h1 class="text-blue-700 font-semibold">Dynamic Trading</h1>
          <img class="w-24" src="../../images/round.png" />
          <h1 class="text-6xl text-blue-600 font-bold">Start Trading With Free Signals Right Now</h1>
        </div>
        <div>
          <p class="text-slate-500">Join World's Biggest And Trusted Exchange.Trade In Bicoin,Ethereum,</p>
          <p class="text-slate-500">Ripple And Many More Currencies.</p>
        </div>
      </div>

      <div class="flex space-x-3 mt-6">
        <button class="bg-blue-600 hover:bg-cyan-700  text-white py-2 px-4 rounded-full w-36">
          Start Trading
        </button>
        <button class="bg-white border-2 border-cyan-400 text-cyan-400 py-2 px-4 rounded-full w-36 hover:bg-cyan-400 hover:text-white">
          Dowload App
        </button>
      </div>

      <div class="mt-6">
        <h1 class="text-xl text-blue-900 font-semibold">Featured Companies</h1>
        <div class="flex space-x-5 mt-3">
          <NuxtLink to="https://www.bibox.com/" target="_blank">
            <img class="w-24" src="../../images/bibox.png" />
          </NuxtLink>
          <NuxtLink to="https://mymonero.com/" target="_blank">
            <img class="w-24" src="../../images/monero.png" />
          </NuxtLink>
          <NuxtLink to="https://bitcoin.org/" target="_blank">
            <img class="w-24" src="../../images/bitcoindumy.png" />
          </NuxtLink>
          <NuxtLink to="https://www.okx.com/" target="_blank">
            <img class="w-24" src="../../images/okex.png" />
          </NuxtLink>
        </div>
      </div>

    </div>

    <div>
      <img class="w-full h-full" src="../../images/header-img.png" alt="image">
    </div>
  </div>
</template>

<script>

export default {
  name : 'default',
}
</script>