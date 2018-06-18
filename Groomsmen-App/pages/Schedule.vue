<template>
  <div class="Schedule">
    <h1 class="header">
      Schedule
    </h1>
    <calendar />
  </div>
</template>

<script>
import Calendar from '~/components/Calendar.vue'

export default {
  components: {
    Calendar
  }
}
</script>