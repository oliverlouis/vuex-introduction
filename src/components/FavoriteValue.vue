<template>
  <div>
    <h2>{{ counter }}</h2>
    <p>we do more...</p>
  </div>
</template>

<script>
export default {
  computed: {
    counter() {
      return this.$store.getters.normalizedCounter;
    }
  }
};
</script>