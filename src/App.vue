<template>
  <div id="app">
    <Header />
    <AlertSite />
    <router-view />

    <FooterPage />
  </div>
</template>

<script>
import FooterPage from "./components/FooterPage";
import Header from "./components/Header";
import AlertSite from "./components/AlertSite";

export default {
  name: "App",
  components: {
    Header,
    AlertSite,
    FooterPage,
  },
};
</script>