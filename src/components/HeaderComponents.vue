<template>
  <div class="flex items-center justify-between px-8 py-4">
    <h1 class="text-gray-900 text-2xl font-bold">RA. <span class="text-gray-400">S</span></h1>
    <form action="">
      <input
        type="text"
        placeholder="Search..."
        class="flex w-xl bg-gray-50 rounded-md px-4 py-2 focus:outline-none focus:ring-0"
      />
    </form>
    <ul class="flex space-x-4">
      <li>
        <router-link to="/">Home</router-link>
      </li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/upload">Upload</router-link></li>
      <li><router-link to="/user/1">User 1</router-link></li>
      <li><router-link to="/user/2">User 2</router-link></li>
    </ul>
  </div>
</template>

<script></script>

<style></style>
