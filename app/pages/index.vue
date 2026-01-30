<script setup lang="ts">
const toast = useToast()

function show_message() {
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
  <ul class="flex flex-col w-6xl gap-2 p-5 bg-amber-300">
    <li>
      <UButton to="/samnang">
        Samnang Mol
      </UButton>
    </li>
    <li>
      <UButton to="/ravy">
        Ravy Mot
      </UButton>
    </li>
    <li>
      <UButton to="/chamroeun">
        Cham Roeun
      </UButton>
    </li>
    <li>
      <UButton @click="show_message()">
        Show toast
      </UButton>
    </li>
  </ul>
</template>
