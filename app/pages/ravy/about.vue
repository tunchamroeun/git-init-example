<template>
  <div class="p-8">
    <h1 class="text-2xl font-bold">
      Email: muthravy@gmail.com <br>
      Tel: 0987654321
      Hello, My name is: Ravy
      <UButton
        to="https://t.me/yourusername"
        target="_blank"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          viewBox="0 0 24 24"
        >
          <path
            fill="currentColor"
            d="M21.05 2.39L2.9 9.62c-1.24.5-1.23 1.2-.23 1.51l4.6 1.44 1.77 5.4c.22.61.11.85.77.85.51 0 .73-.24 1.01-.51l2.21-2.15 4.6 3.4c.85.47 1.46.23 1.67-.79l3.03-14.28c.31-1.25-.48-1.82-1.28-1.45z"
          />
        </svg>
        Telegram
      </UButton>

      <UButton
        to="https://facebook.com"
        target="_blank"
      >
        <template #leading>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="20"
            height="20"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              fill-rule="evenodd"
              d="M5 1a4 4 0 0 0-4 4v14a4 4 0 0 0 4 4h14a4 4 0 0 0 4-4V5a4 4 0 0 0-4-4zm4.682 6.273A3.273 3.273 0 0 1 12.954 4h2.91c.2 0 .363.163.363.364v2.909c0 .2-.163.363-.363.363h-1.455a1.09 1.09 0 0 0-1.09 1.091v1.091h2.545a.364.364 0 0 1 .352.452l-.727 2.91a.36.36 0 0 1-.353.274h-1.818v6.182a.364.364 0 0 1-.364.364h-2.909a.364.364 0 0 1-.363-.364v-6.181H7.864a.364.364 0 0 1-.364-.364v-2.91c0-.2.163-.363.364-.363h1.818z"
              clip-rule="evenodd"
            />
          </svg>
        </template>

        My Facebook
      </UButton>
    </h1> <br>
    <HomeButton />
  </div>
</template>

<script setup>
</script>
