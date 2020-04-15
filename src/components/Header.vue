<template>
  <div>
    <b-nav tabs>
      <b-nav-item>Fancy</b-nav-item>
      <b-nav-item>Counter : {{ numCorrect }}/ {{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"],
};
</script>

<style scoped></style>
