<template>
  <div id="app">
    <div class="row">
      <!-- Slider Berita -->
      <div class="col-lg-9">
        <div class="slider-content">
          <img src="/assets/image/logo (1).png" alt="Berita" class="slider-image" />
          </div>
        </div>

      <!-- Sambutan Kepala Sekolah -->

      <div class="sambutan">
        <h3>Sambutan Kepala Sekolah</h3>
        <div class="sambutan-content">
          <img src="/assets/image/skyyy.png" alt="Kepala Sekolah" class="kepsek-image" />
          <marquee direction="up" scrollamount="2" class="marquee-text">
            Assalamu'alaikum Wr, Wb<br /><br />
            Segala puji dan syukur kita panjatkan kehadirat Alloh SWT,
             semoga kita semua ada dalam lindungan-Nya dan atas perkenan-Nya pula kami
              dapat menghadirkan web site SMK Negeri 4 Tasikmalaya ini
          </marquee>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

.container {
  display: flex;
  gap: 20px;
  padding: 20px;
}

/* Slider */
.slider {
  flex: 3;
  position: relative;
  background-color: #fff;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
}

.slider-content {
  padding: 5px;
  text-align: center;
}

.slider-content h2 {
  font-size: 18px;
  background-color: rgba(0, 0, 0, 0.7);
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}

.slider-content p {
  margin: 10px 0;
  font-size: 14px;
  color: #0c0a0a;
}

.slider-image {
  width: 100%;
  height: auto;
  margin: 10px 0;
}

.slider-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.btn-berita {
  background-color: #070809;
  color: #fff;
  padding: 8px 15px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.btn-berita:hover {
  background-color: #0056b3;
}

.tanggal {
  font-size: 12px;
  color: #888;
}

.slider-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  border: none;
  border-radius: 50%;
  padding: 10px;
  cursor: pointer;
  font-size: 16px;
}

.slider-btn-left {
  left: 10px;
}

.slider-btn-right {
  right: 10px;
}

/* Sambutan Kepala Sekolah */
.sambutan {
  flex: 1;
  background-color: #fff;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
  text-align: center;
}

.sambutan h3 {
  background-color: #04821d;
  color: #fff;
  padding: 10px;
  margin: 0;
}

.sambutan-content {
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.kepsek-image {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.marquee-text {
  width: 100%;
  font-size: 14px;
  color: #555;
}
</style>