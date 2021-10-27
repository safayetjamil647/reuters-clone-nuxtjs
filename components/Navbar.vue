<template>
     <nav class=" container mx-auto flex items-center justify-between flex-wrap bg-white px-12">
      <div class="flex items-center flex-shrink-0 text-black mr-6">
        <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"/></svg>
        <span class="font-semibold text-xl tracking-tight">Reuters</span>
      </div>
      <div class="block lg:hidden">
        <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400">
          <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
        </button>
      </div>
      <div class="w-full block flex-grow lg:flex lg:items-center lg:justify-center lg:w-auto ">
        <div class="text-base lg:flex-grow lg:border-b-2 lg:border-l-2 lg:border-r-2 lg:shadow-md lg:rounded-b-xl px-4 py-4 mx-6">
          <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200  mr-4">
            Docs
          </a>
          <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200  mr-4">
            Examples
          </a>
          <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 ">
            Blog
          </a>
        </div>
        <div class="flex space-x-4">
          <div>
        <a href="#" class="inline-block text-base font-bold px-3 py-2 leading-none border rounded-md text-gray-400 hover:text-black border-gray-400 hover:border-black mt-4 lg:mt-0">Sign In</a>

          </div>
          <div>
          <a href="#" class="inline-block text-base font-bold px-3 py-2 leading-none border rounded-md text-white bg-black border-black hover:opacity-70  mt-4 lg:mt-0">Register</a>

          </div>
        </div>
      </div>
    </nav>
</template>
<script>
export default {
    name:"Navbar"
}
</script>