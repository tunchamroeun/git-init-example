<script setup lang="ts">
const toast = useToast()

function showToast() {
  const eventDate = new Date(Date.now() + Math.random() * 31536000000)
  const formattedDate = eventDate.toLocaleDateString('en-US', {
    month: 'short',
    day: 'numeric',
    year: 'numeric'
  })

  toast.add({
    title: 'Event added to calendar',
    description: `This event is scheduled for ${formattedDate}.`,
    icon: 'i-lucide-calendar-days'
  })
}
</script>

<template>
  <ul class="flex flex-col w-6xl gap-2 p-8">
    <li>
      <UButton
        to="/samnang"
      >
        Samnang
      </UButton>
    </li>
    <li>
      <UButton to="/ravy">
        Ravy
      </UButton>
    </li>
    <UButton to="/ravy">
      Ravy
    </UButton>
    <li>
      <UButton
        to="/chamroeun"
      >
        Cham Roeun
      </UButton>
    </li>
    <li>
      <UButton @click="showToast()">
        Show toast
      </UButton>
    </li>
  </ul>
</template>
