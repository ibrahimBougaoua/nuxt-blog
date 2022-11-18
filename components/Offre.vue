<template>
    
    <div>
        <slot class="space-y-2">
        
        </slot>
        <ul class="space-y-2">
            <li><span class="text-blue-600 w-36 mx-4">&#10003;</span><p class="inline">lorem ipsum is simply dummy text</p> </li>
            <li><span class="text-blue-600 w-36 mx-4">&#10003;</span><p class="inline">it is a long establish fact that a reder </p></li>
            <li><span class="text-blue-600 w-36 mx-4">&#10003;</span><p class="inline">the point of using Lorem Ipsum</p></li>
            <li><span class="text-blue-600 w-36 mx-4">&#10003;</span><p class="inline">it was popularized in 1960s with release</p></li>
            <li><span class="text-blue-600 w-36 mx-4">&#10003;</span><p class="inline">software like PageMaker including versions. </p></li>
        </ul>
        <button class="bg-white border-2 border-blue-500 hover:bg-gray-400  text-blue-500 py-2 px-4 rounded-full w-64 my-5">
                {{msgbtn}} 
        </button>

    </div>
</template>

<script>
export default ( {
  components: {
    
  },
  props:{ msgbtn:String,

},
 
  
} );

</script>