<template>
  <div>
    <h1>Login app</h1>
    <input type="text" v-model="nameValue">
    My name is {{ nameValue }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Hello Vue!",
      nameValue: ""
    };
  },
};
</script>
