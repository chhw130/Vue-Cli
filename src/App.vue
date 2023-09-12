<template>
  <img alt="Vue logo" src="./assets/logo.png" />
</template>

<script>
const app = {
  data() {
    return {
      friends: [
        {
          id: "manuel",
          name: "manuel Lorez",
          phone: "123-1234-1234",
          email: "manuel@naver.com",
        },
      ],
    };
  },
};
app();
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
