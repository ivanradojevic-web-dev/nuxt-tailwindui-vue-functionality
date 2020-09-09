<template>
<div class="flex flex-col h-screen text-sm text-gray-400">
<div class="bg-blue-500 flex-1 flex overflow-y-hidden">

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

  <div class="sidebar-content bg-gray-800 flex-1 overflow-y-auto">Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.
The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.</div>
</div> 

<div class="bg-gray-700 flex-none h-20 px-5 flex items-center justify-between">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div> 

</div>
</template>



<style>



</style>
