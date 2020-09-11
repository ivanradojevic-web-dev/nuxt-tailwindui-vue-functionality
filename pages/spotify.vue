<template>
<div class="flex flex-col h-screen text-sm text-gray-400">

<div class="bg-blue-500 flex overflow-hidden">

  <div class=" bg-gray-900 w-48 flex-none  flex flex-col justify-between font-semibold">

    <ul class="py-6">
      <li class="border-l-4 border-green-600">
        <nuxt-link to="/" class="flex items-center mx-4 mt-4 hover:text-white">
          <span><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg></span>
          <span class="ml-2">Home</span>
        </nuxt-link>  
      </li> 
      <li class="">
        <a href="#" class="flex items-center mx-4 mt-4 hover:text-white">
          <span><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7v8a2 2 0 002 2h6M8 7V5a2 2 0 012-2h4.586a1 1 0 01.707.293l4.414 4.414a1 1 0 01.293.707V15a2 2 0 01-2 2h-2M8 7H6a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2v-2"></path></svg></span>
          <span class="ml-2">Browse</span>
        </a>  
      </li> 
      <li class="">
        <a href="#" class="flex items-center mx-4 mt-4 hover:text-white">
          <span><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 5c7.18 0 13 5.82 13 13M6 11a7 7 0 017 7m-6 0a1 1 0 11-2 0 1 1 0 012 0z"></path></svg></span>
          <span class="ml-2">Radio</span>
        </a>  
      </li> 
    </ul>

    <div class="sidebar overflow-y-auto px-4 mt-2"> 
      <h3 class="uppercase tracking-widest text-gray-500 text-xs font-normal mb-2">Your LIbrary</h3> 
      <ul class="leading-loose">
       <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Liked Song</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
      </ul>

      <h3 class="uppercase tracking-widest text-gray-500 text-xs font-normal mt-5 mb-2">Playlists</h3> 
      <ul class="leading-loose">
       <li class="truncate"><a href="#" class="hover:text-white">Dance</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">90`s</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">R&B</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">House</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Hip Hop</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Rock</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Live</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Acoustic</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Techno</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Pop</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Ambient</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">World Music</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Country</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Electro</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Piano</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Top 10</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Hits</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Soundtrack</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Solo</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Chill Out</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Downtempo</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">Leftfield</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">DnB</a></li>
       <li class="truncate"><a href="#" class="hover:text-white">80`s</a></li>
      </ul>

    </div>

    <button class="border-t border-gray-800 h-16 px-4 py-2 flex items-center hover:text-white focus:outline-none">
      <span><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg></span>
          <span class="ml-2">New Playlist</span>
    </button>

  </div>





  <div class="sidebar-content bg-gray-800 flex-1 flex flex-col">

      <div class=" flex justify-between  ">

        <div>levo</div>
        <div>desno</div>

      </div>

      <div class="overflow-y-auto ">
        
        <div class="container mx-auto">

          <h2 class="mt-24 text-5xl font-semibold text-white">Home</h2>

            <div class="mt-12" >
          
        <h3 class="font-semibold text-xl border-b border-gray-800 pb-2">Recently Played</h3>

                 <div class="flex  mt-4 space-x-8  ">   


                 <div class="w-1/5 px-4"  >
<div><img src="R-1306664-1318369920.jpeg.jpg" alt="album cover" ></div>
<div class="flex flex-col ml-2">

     <div class="flex">
    <p class="hover:text-white text-gray-500 mt-2">Vangelis</p>
    </div> 

       <div class="flex items-center">
         <h4 class="hover:text-white">Love Theme</h4>
      </div>
    
    

   </div>
                </div>  



                 <div class="w-1/5 px-4"  >
<div><img src="R-1306664-1318369920.jpeg.jpg" alt="album cover" ></div>
<div class="flex flex-col ml-2">

     <div class="flex">
    <p class="hover:text-white text-gray-500 mt-2">Vangelis</p>
    </div> 

       <div class="flex items-center">
         <h4 class="hover:text-white">Love Theme</h4>
      </div>
    
    

   </div>
                </div>  



                 <div class="w-1/5 px4">aa</div>
                 <div class="w-1/5 px4">aa</div>
                 <div class="w-1/5 px4">aa</div>
                 
                 

                  </div>


            </div>





        </div>

      </div>

  </div>










</div>
 



<div class="bg-gray-700 flex-none h-20 px-5 flex items-center justify-between overflow-hidden">


  <div class="flex items-center flex-none ">
    <a href="#"><img src="R-1306664-1318369920.jpeg.jpg" alt="album cover" class="w-12 h-12"></a>

    <div class="flex flex-col ml-2">

       <div class="flex items-center">
         <h4 class="hover:text-white">Love Theme</h4>
          <svg class="w-4 h-4 ml-1 hover:text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path  stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
      </div>
    
    <div class="flex">
    <p class="hover:text-white text-gray-500">Vangelis</p>
    </div> 

   </div>
 </div>

  <div class="flex flex-col items-center flex-1">

    <div class="flex items-center space-x-4">
        
       <button><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12.066 11.2a1 1 0 000 1.6l5.334 4A1 1 0 0019 16V8a1 1 0 00-1.6-.8l-5.333 4zM4.066 11.2a1 1 0 000 1.6l5.334 4A1 1 0 0011 16V8a1 1 0 00-1.6-.8l-5.334 4z"></path></svg></button> 
       <button><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg></button> 
       <button><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.933 12.8a1 1 0 000-1.6L6.6 7.2A1 1 0 005 8v8a1 1 0 001.6.8l5.333-4zM19.933 12.8a1 1 0 000-1.6l-5.333-4A1 1 0 0013 8v8a1 1 0 001.6.8l5.333-4z"></path></svg></button> 
       
    </div>

  
    <div class="flex items-center">
      <div>1:20</div>
      <div class="bg-gray-500 rounded-lg w-64 h-1 ml-3"></div>
      <div class="ml-3">- 4:00</div>
    </div>

  </div> 

  <div class="flex items-center">
      <button><svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z"></path></svg></button>

      <div class="bg-gray-500 rounded-lg w-16 h-1 ml-3"></div>

  </div>



</div>


</div>

</template>


<script>



</script>



<style>



</style>
