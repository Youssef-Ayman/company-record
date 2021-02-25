<template>
  <CompanyRecord msg="Company Record" />
</template>

<script>
import CompanyRecord from "./components/company-record.vue";

export default {
  name: "App",
  components: {
    CompanyRecord,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
