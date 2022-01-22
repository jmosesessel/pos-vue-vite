<template>
  <div class="flex w-full min-h-screen font-sans bg-gray-100">
    <SideBar />
    <main class="flex flex-col flex-1">
      <header>
        <h1 class="text-x3"></h1>
      </header>
    </main>
    <aside class="flex flex-col gap-y6 pt-6 pr-6 w-96">
      <RightSideBar />
    </aside>
  </div>
</template>
  
<script setup>
import SideBar from './components/SideBar.vue'
import RightSideBar from './components/RightSideBar.vue';
</script>