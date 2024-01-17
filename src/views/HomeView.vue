<script>

</script>

<template>
  <div class="music">
    <div class="play-song">
      <img src="../assets/pochette_a.jpg" alt="pochette album">
      <p>music a</p>
      <button>+</button>
      <button>▶️</button>
    </div>
    <div class="play-song">
      <img src="../assets/pochette_b.jpg" alt="pochette album">
      <p>music b</p>
      <button>+</button>
      <button>▶️</button>
    </div>
    <div class="play-song">
      <img src="../assets/pochette_c.jpg" alt="pochette album">
      <p>music c</p>
      <button>+</button>
      <button>▶️</button>
    </div>
  </div>
</template>

<style scoped>
  .music{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 15px;
  }
  .play-song{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
  }
  img{
    width: 100px;
    height: 100px;
  }
</style>
