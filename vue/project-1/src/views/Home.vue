<template>
  <div>
    <div class="wrapper">
      <PenguinCard />
      <div class="info-area">
        <small>Design: figma</small>
        <br />
        <small>Code Generator(vue): teleportHq.io</small>
      </div>
    </div>
    <div></div>
  </div>
</template>

<script>
  import PenguinCard from '@/components/PenguinCard.vue';

  export default {
    name: 'Home',
    metaInfo: {
      title: 'PenguinCard',
    },
    components: { PenguinCard },
  };
</script>

<style scoped>
  .wrapper {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .info-area {
    margin-top: 10px;
  }
</style>
