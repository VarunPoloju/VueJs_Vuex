<template>
  <button @click="addOne">Add 2 change counter</button>
</template>

<script>
export default {
  methods: {
    addOne() {
      this.$store.dispatch('increment');
    },
  },
};
</script>
