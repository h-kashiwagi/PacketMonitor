<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <packet_operator msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import packet_operator from '@/components/packet_operator.vue'; // @ is an alias to /src

@Options({
  components: {
    packet_operator,
  },
})
export default class HomeView extends Vue {}
</script>
