<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Statstik Data SMKN 4 Tasikmalaya
          </h5>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
            <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink>/ DataStatistik
          </p>
        </div>

        <div class="content">
      <h2>Statistik Data</h2>
      <div class="stats-grid">
        <div class="stat-item">
          <h3>Jumlah Siswa</h3>
          <p class="value">1116</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Rombel</h3>
          <p class="value">34</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Guru</h3>
          <p class="value">60</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Tenaga Administrasi</h3>
          <p class="value">10</p>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.statistik-data {
  font-family: Arial, sans-serif;
  margin: 20px;
}

.breadcrumb {
  font-size: 14px;
  color: gray;
  margin-bottom: 20px;
}

.content {
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1 {
  text-align: center;
  margin-bottom: 20px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
}

.stat-item {
  background-color: #bfebfe;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.stat-item h3 {
  margin-bottom: 10px;
}

.stat-item .value {
  font-size: 24px;
  font-weight: bold;
}
</style>
