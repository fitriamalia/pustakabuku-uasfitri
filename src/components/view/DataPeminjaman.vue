<template>
  <div class="container ms-5">
    <div class="child">
      <router-link to="/readallpeminjamanmaster" class="btn btn-success ms-2"><h2>Data Peminjaman</h2></router-link>
    </div>
  </div>

</template>

<script>
export default {
  name: "DataPeminjaman"
}
</script>

<style scoped>
.container{
  margin: 25px;
  width: 1050px;
}
.child{
  width: 500px;
  height: 50px;
  /* Center horizontally*/
  margin: 0 auto;
}
</style>