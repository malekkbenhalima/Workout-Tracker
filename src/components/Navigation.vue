<template>
  <header>
    <header class="bg-at-light-green text-white">
      <nav class="container py-5 px-4 flex flex-col gap-4 items-center sm:flex-row">
        <router-link class="cursor-pointer" :to="{ name: 'Home' }">
          <div class="flex items-center gap-x-4">
            <img class="w-14" src="../assets/images/dumbbell-light.png" alt="">
            <h1 class="text-lg">Workout Tracker</h1>
          </div>
        </router-link>
        <ul class="flex flex-1 justify-end gap-x-10">
          <router-link class="cursor-pointer" :to="{ name: 'Home' }">Home</router-link>
          <router-link class="cursor-pointer" :to="{ name: 'Login' }">Create</router-link>
          <router-link class="cursor-pointer" :to="{ name: 'Login' }">Login</router-link>
          <li class="cursor-pointer">Logout</li>
        </ul>
      </nav>
    </header>
  </header>
</template>

<script>
export default {
  setup() {
    // Get user from store

    // Setup ref to router

    // Logout function

    return {};
  },
};
</script>
