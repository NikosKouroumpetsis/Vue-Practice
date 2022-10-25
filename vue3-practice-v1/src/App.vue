<template>
  <h1 v-if="isShowing">{{ title }}</h1>
  <h3 v-else-if="isShowing === null">This is v-else-if</h3>
  <h2 v-else>This is if else part</h2>
  <p>{{ para }}</p>
</template>

<script>
export default {
  data() {
    return {
      title: "This is title inside h1 tag",
      isShowing: null,
      para: "a example with props",
    };
  },
};
</script>

<style></style>
