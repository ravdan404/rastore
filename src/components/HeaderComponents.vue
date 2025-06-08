<template>
  <div class="flex items-center justify-between px-4 py-4 md:px-10 shadow-md bg-white dark:bg-gray-800">
    <h1 class="flex dark:text-white text-gray-900 text-2xl font-bold">RA. <span class="text-gray-400">S</span></h1>
    <form action="">
      <input
        type="text"
        placeholder="Search..."
        class="flex w-auto md:w-xl mx-2 bg-gray-100 dark:text-white dark:bg-gray-700 rounded-md px-4 py-2 focus:outline-none focus:ring-0"
      />
    </form>
    <ul class="md:flex hidden space-x-4 dark:text-white text-gray-900">
      <li>
        <button class="flex flex-col items-center cursor-pointer hover:text-blue-600">
          <InboxIcon class="size-6 "/>
          <span class="font-light text-sm">Inbox</span>
        </button>
      </li>
      <li>
        <router-link to="/users/123213" class="flex flex-col items-center hover:text-blue-600">
          <UserIcon class="size-6 "/>
          <span class="font-light text-sm">Users</span>
        </router-link>
      </li>
    </ul>
    <button class="flex md:hidden"><Bars3Icon class="size-6"/></button>
  </div>
</template>

<script>
import { InboxIcon, UserIcon, Bars3Icon } from '@heroicons/vue/24/outline'

export default {
  name: 'HeaderComponents',
  components: {
    InboxIcon, UserIcon, Bars3Icon
  }
}
</script>

<style></style>
