<template>
    <div class="flex   justify-between my-5">
        <div class="">
            <img src="../images/img.PNG" alt="image" class="max-w-7xl">
        </div>
        <div class="flex flex-col">
            <h1 class="text-blue-700 font-semibold mt-5">Dynamic Trading</h1>
            <img class="w-24 " src="../images/round.png" />
            <h1 class="text-5xl text-blue-600 font-bold">trading and investe solution build in modern platforme.</h1>
            <div class="my-7">
                <div> <span class="text-cyan-600">&#10003;</span> <span class="font-bold">fundamental researche</span><p class="inline"> lorem ipsum has been industry's stadard dummy text  since 1500s </p>
                </div>
                <div><span class="text-cyan-600">&#10003;</span> <span class="font-bold">trading idea and report</span><p class="inline"> lorem ipsum has been industry's stadard dummy text  since 1500s </p>
                </div>
                <div>
                    <span class="text-cyan-600">&#10003;</span> <span class="font-bold">trading idea and report</span><p class="inline"> lorem ipsum has been industry's stadard dummy text  since 1500s </p>
                </div>
            </div>
        </div>


    </div>
    <div class="flex justify-between my-5">
       
        <div class="flex flex-col">
            <h1 class="text-blue-700 font-semibold">Dynamic Trading</h1>
            <img class="w-24" src="../images/round.png" />
            <h1 class="text-5xl text-blue-600 font-bold my-4">stard trading and get more benifit.</h1>
            <p>lorem ipsum  is simply dummy text of the printing and typesetting industry</p>
            <button class="bg-cyan-500 border-2 border-cyan-500 hover:bg-gray-400  text-white py-2 px-4 rounded-full w-36 my-5">
                Start Trading
            </button>
        </div>
        <div>
            <img src="../images/img2.PNG" alt="img">
        </div>
    </div>
    <div class="flex justify-items-stretch my-5">
        <div>
            <img src="../images/image3.PNG" alt="image" class="mx-10">
        </div>

        <div class="flex flex-col">
            <h1 class="text-blue-700 font-semibold">Dynamic Trading</h1>
            <img class="w-24" src="../images/round.png" />
            <h1 class="text-5xl text-blue-600 font-bold my-4">why chose dynamic!</h1>
            <p>lorem ipsum has been industry's stadard dummy text  since 1500s  when an unkown printer took a galley of type and scambed iy to make a type spicemen book</p>
            <div class="grid grid-cols-2 grid-rows-3 mt-5">
                <div> <span class="text-white bg-blue-600 rounded-full w-36 my-2">&#10003;</span> <p class="inline font-bold">safty come first </p>
                </div>
                <div> <span class="text-white bg-blue-600 rounded-full w-3.5  my-2">&#10003;</span><p class="inline font-bold"> fast transaction </p>
                </div>
                <div> <span class="text-white bg-blue-600 rounded-full w-36  my-2">&#10003;</span> <p class="inline font-bold">bonus and refferal </p>
                </div>
                <div> <span class="text-white bg-blue-600 rounded-full w-36  my-2">&#10003;</span> <p class="inline font-bold">easy  deposit and withraw </p>
                </div>
                <div> <span class="text-white bg-blue-600 rounded-full w-36 my-2">&#10003;</span> <p class="inline font-bold">low charge </p>
                </div>
                <div> <span class="text-white bg-blue-600 rounded-full w-36 my-2">&#10003;</span> <p class="inline font-bold">24/7 support </p>
                </div>

            </div>
        </div>

    </div>

    <div class="flex justify-between ">
        <div class="flex flex-col">
            <h1 class="text-blue-700 font-semibold">Dynamic Trading</h1>
            <img class="w-24" src="../images/round.png" />
            <h1 class="text-5xl text-blue-600 font-bold my-4">refer and earn big rewards</h1>
            <p>lorem ipsum is simply dummy text of the printing and typesetting industry</p>
            <button class="bg-cyan-500 border-2 border-cyan-500 hover:bg-gray-400  text-white py-2 px-4 rounded-full w-36 my-5">
                rafer now 
            </button>

        </div>

        <div>
            <img src="../images/img4.PNG" alt="img">
        </div>

    </div>

    <div class="flex justify-evenly">
        <div class="flex flex-col">
           
            <h1 class="font-bold text-5xl inline">4 M+</h1>
            <h2>user register</h2>

        </div>
        <h1 class="text-5xl">|</h1>
        <div class="flex flex-col">
            <div>
                <span class="font-bold text-5xl">&#8377;</span>
                     
                <h1 class="font-bold text-5xl inline">200 M+</h1>
            </div>
            <h2>crypto investe</h2>
        </div>
        <h1 class="text-5xl">|</h1>
        <div class="flex flex-col">
           
            <div>
                <span class="font-bold text-5xl">&#8377;</span>
                <h1 class="font-bold text-5xl inline">500 M+</h1>
            </div>
            <h2>crypto purchase</h2>
        </div>

    </div>

    <div class="flex  justify-center ">
        <div class="flex-col">
            <div class=" justify-self-auto">
                <h1 class="text-blue-700 font-semibold mt-5">Dynamic Trading</h1>
                <img class="w-24 " src="../images/round.png" />
            </div>
        </div>
 
    </div>

    <div class="flex  justify-center ">
        <div class="flex-col">
            <h1 class="text-blue-900 font-bold text-5xl m-5">see our serticified user says about dynamic!</h1>
            <p>lorem ipsum has been industry's stadard dummy text  since 1500s  when an unkown printer took a galley of type and scambed iy to make a type spicemen book</p>
        </div>

    </div>
    

    <Splide :options="{ rewind: true }" aria-label="My Favorite Images">
        <SplideSlide>
            <div class="grid grid-cols-2 gap-2 ">
                <Commentaire class=" border rounded-lg" title="buying crypto was never so easy 1" :t=paragraphe :auteur=Auteur :ville=Ville></Commentaire>
                <Commentaire class="border rounded-lg" title="buying crypto was never so easy 2" :t=paragraphe :auteur=Auteur :ville=Ville></Commentaire>
                

            </div>
            
        </SplideSlide>
        <SplideSlide>
            <div class="grid grid-cols-2 gap-2  ">
                <Commentaire class="border rounded-lg" title="buying crypto was never so easy 3" :t=paragraphe :auteur=Auteur :ville=Ville></Commentaire>
                <Commentaire class="border rounded-lg" title="buying crypto was never so easy 4" :t=paragraphe :auteur=Auteur :ville=Ville></Commentaire>

            </div>
        </SplideSlide>
    </Splide>

    <div class="flex  justify-center m-6 ">
        <div class="flex-col">
            <div class=" justify-self-auto">
                <h1 class="text-blue-700 font-semibold mt-5">Dynamic Trading</h1>
                <img class="w-24 " src="../images/round.png" />
            </div>
        </div>
 
    </div>

    <div class="flex  justify-center ">
        <div class=" flex flex-col">
            <h1 class="text-blue-900 font-bold text-5xl m-5">get more benefit with subscription</h1>
            <div class="flex justify-center">
                <span class="mx-2"> Mothly</span>
                <label class="inline-flex relative  cursor-pointer">
                    <input type="checkbox" value="ok" class="sr-only peer">
                
                    <div class="w-11 h-6 bg-gray-200 peer-focus:outline-none peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 rounded-full peer dark:bg-gray-700 peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"></div>
                
                </label>
                <span class="mx-2"> Yearly</span>

            </div>
        </div>
   
      

    </div>
</template>

<script>
import { Splide, SplideSlide } from '@splidejs/vue-splide';
import '@splidejs/vue-splide/css';
import Commentaire from "./Commentaire.vue"

export default defineComponent( {
  components: {
    Splide,
    SplideSlide,
    Commentaire
  },
  data(){
    return{
        paragraphe:"lorem ipsum has been industry's stadard dummy text  since 1500s  when an unkown printer took a galley of type and scambed iy to make a type spicemen boo",
        Auteur:"hocine",
        Ville:"new york ,usa",

    }
  },
} );
</script>

<style scoped>

</style>