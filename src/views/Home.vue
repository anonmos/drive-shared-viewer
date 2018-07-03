<template>
  <div class="home">
     <button @click="handleAuth">Sign In</button>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import gapi from 'gapi';
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    // Some components here
  },
  methods: {
    handleAuth: () => {
      // Some code here
    },
  },
  mounted: () => {
    // Some code here
  },
})
export default class Home extends Vue {}
</script>
<style scoped lang="scss">
@import '../styles/home'
</style>
