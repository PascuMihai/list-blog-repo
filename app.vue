<template>
  <div class="bg-gray-100 min-h-screen overflow-auto">
    <navbar />
    <main-container />
    <app-footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import AppFooter from './components/AppFooter.vue';
import MainContainer from './components/MainContainer.vue';

export default {
  name: 'HomeLayout',
  components: {
    Navbar,
    MainContainer,
    AppFooter,
  },
  data() {
    return {
      items: [],
    }
  },
}
</script>
