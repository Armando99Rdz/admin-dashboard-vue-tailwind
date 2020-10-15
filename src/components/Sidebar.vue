<template>
    <!-- give the sidebar z-50 class so its higher than the navbar if you want to see the logo -->
    <!-- you will need to add a little "X" button next to the logo in order to close it though -->
    <div class="w-1/2 md:w-1/3 lg:w-64 fixed md:top-0 md:left-0 h-screen lg:block bg-gray-25 border-r z-30" :class="sideBarOpen ? '' : 'hidden'" id="main-nav">

          <a href="/" class="w-full h-20 flex px-4 items-center mb-8">
            <svg class="w-8 h-8 ml-2 text-purple-light" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path></svg>
            <p class="font-semibold text-3xl text-gray-800 pl-4">LOGO</p>
          </a>

          <div class="mb-4 px-4 text-gray-800">
            <p class="pl-4 text-xs font-semibold mb-4 text-gray-600">MENU</p>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <svg class="w-6 h-6 mr-2 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
              <span class="text-gray-800 font-medium">Dashboard</span>
            </div>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <svg class="w-6 h-6 mr-2 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M9 17a2 2 0 11-4 0 2 2 0 014 0zM19 17a2 2 0 11-4 0 2 2 0 014 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16V6a1 1 0 00-1-1H4a1 1 0 00-1 1v10a1 1 0 001 1h1m8-1a1 1 0 01-1 1H9m4-1V8a1 1 0 011-1h2.586a1 1 0 01.707.293l3.414 3.414a1 1 0 01.293.707V16a1 1 0 01-1 1h-1m-6-1a1 1 0 001 1h1M5 17a2 2 0 104 0m-4 0a2 2 0 114 0m6 0a2 2 0 104 0m-4 0a2 2 0 114 0"></path></svg>
              <span class="text-gray-800 font-medium">Compras</span>
            </div>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <svg class="w-6 h-6 mr-2 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
              <span class="text-gray-800 font-medium">Ventas</span>
            </div>
            
          </div>
          <div class="mb-4 px-4 text-gray-800 mt-5">
            <p class="pl-4 text-xs font-semibold mb-4 text-gray-600">SEGURIDAD</p>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <svg class="w-6 h-6 mr-2 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 7a2 2 0 012 2m4 0a6 6 0 01-7.743 5.743L11 17H9v2H7v2H4a1 1 0 01-1-1v-2.586a1 1 0 01.293-.707l5.964-5.964A6 6 0 1121 9z"></path></svg>
              <span class="text-gray-800 font-medium">Accesos</span>
            </div>
          </div>

          <div class="mb-4 px-4 text-gray-800 mt-5">
            <p class="pl-4 text-xs font-semibold mb-4 text-gray-600">MONITOREO</p>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <svg class="w-6 h-6 mr-2 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 12l3-3 3 3 4-4M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z"></path></svg>
              <span class="text-gray-800 font-medium">Reportes</span>
            </div>
          </div>

          <div class="mb-4 px-4 text-gray-800 mt-5">
            <p class="pl-4 text-xs font-semibold mb-4 text-gray-600">TAREAS</p>
            <!-- task list-->
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <div class="h-2 w-2 mr-4 rounded-full bg-orange"></div>
              <span class="text-gray-800 font-medium">Hacer el inventari...</span>
            </div>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <div class="h-2 w-2 mr-4 rounded-full bg-green"></div>
              <span class="text-gray-800 font-medium">Verificar las ventas...</span>
            </div>
            <div class="w-full flex items-center text-gray-800 h-10 pl-4 hover:bg-gray-30 rounded-lg cursor-pointer duration-150">
              <div class="h-2 w-2 mr-4 rounded-full bg-purple"></div>
              <span class="text-gray-800 font-medium">Corte de caja</span>
            </div>
          </div>

        </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
    name: 'Sidebar',
    computed: {
        ...mapState(['sideBarOpen'])
    }
}
</script>