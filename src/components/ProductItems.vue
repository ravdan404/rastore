<template>
  <div
    class="w-full relative max-w-sm bg-white border border-gray-200 rounded-lg shadow-sm dark:bg-gray-800 dark:border-gray-700"
  >
    <a href="#">
      <img
        class="p-8 rounded-t-lg"
        src="https://d2j6dbq0eux0bg.cloudfront.net/images/66610504/2636945004.jpg"
        alt="product image"
      />
    </a>
    <div class="px-5 pb-5">
      <a href="#">
        <h5 class="text-xl font-semibold tracking-tight text-gray-900 dark:text-white mb-5">
          Apple Watch Series 7 GPS, Aluminium Case, Starlight Sport
        </h5>
      </a>
      <div class="flex items-center justify-between">
        <span class="text-3xl font-bold text-gray-900 dark:text-white">$599</span>
        <a
          href="#"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >Add to cart</a
        >
      </div>
    </div>
    <span>
      <div class="absolute top-5 left-0 text-sm rounded-r-md bg-red-400 px-2">-50%</div>
      <div class="absolute top-5 right-4 text-sm">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="size-6 text-gray-200 transform transition-transform hover:scale-120 duration-200 cursor-pointer"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z"
          />
        </svg>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
          fill="currentColor"
          class="hidden size-6 text-red-500 hover:text-red-700 transition-colors duration-200 cursor-pointer"
        >
          <path
            d="m11.645 20.91-.007-.003-.022-.012a15.247 15.247 0 0 1-.383-.218 25.18 25.18 0 0 1-4.244-3.17C4.688 15.36 2.25 12.174 2.25 8.25 2.25 5.322 4.714 3 7.688 3A5.5 5.5 0 0 1 12 5.052 5.5 5.5 0 0 1 16.313 3c2.973 0 5.437 2.322 5.437 5.25 0 3.925-2.438 7.111-4.739 9.256a25.175 25.175 0 0 1-4.244 3.17 15.247 15.247 0 0 1-.383.219l-.022.012-.007.004-.003.001a.752.752 0 0 1-.704 0l-.003-.001Z"
          />
        </svg>
      </div>
    </span>
  </div>
</template>

<script>
export default {
  name: 'ProductItems',
  components: {},
}
</script>

<style></style>
