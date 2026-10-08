<script>
export default {
  data() {
    return {
      name: "Alvin",
      age: 22,
      job: "Frontend Developer"
    }
  },

  methods: {
    showMessage() {
      alert("Hello! I am Alvin.")
    }
  }
}
</script>

<template>
  <div>
    <h1>My Profile</h1>

    <p>Name: {{ name }}</p>
    <p>Age: {{ age }}</p>
    <p>Job: {{ job }}</p>

    <button @click="showMessage">
      Say Hello
    </button>
  </div>
</template>

<style>
div {
  text-align: center;
  margin-top: 50px;
}

button {
  padding: 10px 20px;
}
</style>