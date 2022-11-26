<template>
    <div class="w-9/12 m-32">
        <h1 class="font-bold text-xl"> {{title}}</h1>
        <p>{{t}}</p>
        <div class="m-2 flex">
            <span class="rounded-full w-10 inline "><img src="../images/personne.PNG" alt="img" class="inline"></span>
            <div class="inline">
                <h1 class="font-bold">{{auteur}}</h1>
                <h2 class="text-gray-600">{{ville}} </h2>
            </div>

        </div>
        
    </div> 
</template>

<script>
export default {
  name : 'default',
  data()
  {
    return{

    }
  },
  props:{
    title : String,
    t: String,
    auteur : String,
    ville : String,
  },
  
}

</script>