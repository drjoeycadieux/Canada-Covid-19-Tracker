<template>
  <header class="bg-gray-800 text-white p-10 mb-0">
    <div class="text-center text-1xl md:text-5xl font-bold mb-3">
      <i class="fas fa-viruses"></i> <ButtonDashboard />
      Canada Covid-19 Tracker Platform
    </div>
    <h3 class="text-center text-xs text-white">
      Source:
      <a
        class="text-center border-b border-dotted text-blue-600 border-blue-600 hover:text-blue-800 hover:border-blue-800"
        href=""
        >Canada Deptartment of Health
      </a>
      Last updated 4/30/2021 12:00 p.m.
    </h3>
    <Banner />
  </header>
</template>

<script>
import Banner from "../components/Banner";

export default {
  name: "Header",
  components: {
    Banner,
  },
};
</script>