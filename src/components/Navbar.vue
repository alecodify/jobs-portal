<script setup>
    import logo from '@/assets/images/logo.png';
</script>

<template>
    <nav class="bg-primary border-b border-secondary">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="flex h-20 items-center justify-between">
          
          <div class="flex flex-1 items-center justify-center md:items-stretch md:justify-start">
              <img class="h-10 w-auto" :src="logo" alt="Vue Jobs" />
              <span class="hidden select-none md:block text-white text-2xl font-bold ml-2">Jobs Portal</span>
          </div>

          <div class="md:ml-auto">
              <div class="flex space-x-4">
                  <a href="" class="text-white bg-secondary hover:bg-highlight transition-all duration-200 rounded-md px-4 py-2 text-sm font-medium">Home</a>
                  <a href="" class="text-white hover:bg-secondary hover:text-primary transition-all duration-200 rounded-md px-4 py-2 text-sm font-medium">Jobs</a>
                  <a href="" class="text-white hover:bg-secondary hover:text-primary transition-all duration-200 rounded-md px-4 py-2 text-sm font-medium">Add Job</a>
              </div>
          </div>
       </div>
    </div>
  </nav>
</template>
