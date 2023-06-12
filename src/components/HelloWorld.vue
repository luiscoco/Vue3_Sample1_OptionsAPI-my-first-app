<template>
  <div>
    <p>{{ message }}</p>
    <button @click="updateMessage">Update Message</button>
  </div>
</template>

<!-- Options API -->
<script>
export default {
  data() {
    return {
      message: "Hello, Vue!",
    };
  },
  methods: {
    updateMessage() {
      this.message = "Hello, Vue updated!";
    },
  },
};
</script>
