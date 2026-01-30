<template>
  <section class="w-full min-h-screen flex items-center justify-center bg-gray-100">
    <div class="max-w-3xl w-full bg-white rounded-2xl shadow-lg p-10 text-center">
      
      <h1 class="text-4xl font-bold text-gray-800 mb-4">
        Hello
      </h1>

      <p class="text-xl text-gray-600 mb-6">
        My name is <span class="font-semibold text-indigo-600">Samnang</span>
      </p>

      <p class="text-gray-500 mb-8">
        I am learning Nuxt, Vue, Git, and Vim.
      </p>

      <div class="flex justify-center gap-4">
        <NuxtLink
          to="/contact"
          class="px-6 py-3 bg-indigo-600 text-white rounded-xl hover:bg-indigo-700 transition"
        >
          Contact Me
        </NuxtLink>

        <button
          class="px-6 py-3 border border-indigo-600 text-indigo-600 rounded-xl hover:bg-indigo-50 transition"
        >
          Learn More
        </button>
      </div>

    </div>
  </section>
</template>
