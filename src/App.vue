<template>
  <div class="flex w-full min-h-screen font-sans bg-gray-100">
    <SideBar />
    <main>
      
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