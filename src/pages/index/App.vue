<template>
  <div id="app">
    <b-notification :active.sync="isActive" aria-close-label="Close notification">
            Testing notification
    </b-notification>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      isActive: true,
    }
  }
}
</script>

<style>
</style>
