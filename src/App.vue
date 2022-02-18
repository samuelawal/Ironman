<template>
  <Header />
  <Summary />
</template>

<script>
import Header from "./components/Headers";
import Summary from "./components/Summary";
export default {
  name: "App",
  components: {
    Header,
    Summary,
  },
};
</script>

<style >
body {
  background-image: url("./assets/images/frame.png");
  background-repeat: no-repeat, repeat;
  background-size: cover;
}
</style>
