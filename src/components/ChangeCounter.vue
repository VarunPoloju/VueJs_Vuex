<template>
  <button @click="addOne">Add 1 change counter</button>
</template>

<script>
export default {
  methods: {
    addOne() {
      this.$store.commit('increment');
    },
  },
};
</script>
