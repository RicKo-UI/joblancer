<template>
  <div class="home py-5">
    <div class="container mt-5">
      <!--Hero-->
      <div class="row mb-5">
        <div class="col-md-6 align-self-md-center align-self-sm-start">
          <h3 class="mb-4">Cari Pekerjaan Mudah Dimana Saja dan Kapan Saja</h3>
          <p class="mb-5">Menyediakan ratusan pekerjaan yang bisa di kerjakan kapan saja dan dimana saja, buruan daftar</p>
          <button class="btn btn-primary">Cari Pekerjaan</button>
        </div>
        <div class="col-md-6">
          <img src="../assets/hero.png" alt="" class="img-fluid">
        </div>
      </div>
      <!---->

      <!--Card Benefit-->
      <div class="row mt-5 pt-5">
        <div class="card pt-5 pb-4 text-center kartu">
          <div class="container mt-5">
            <div class="row">
              <div class="col-md-4 col-sm-12">
                <span><font-awesome-icon icon="fa-solid fa-user" class="iconhero"/></span>
                <p class="mt-3">500+ Pengguna Aktif</p>
              </div>
              <div class="col-md-4 col-sm-12">
                <span><font-awesome-icon icon="fa-solid fa-briefcase" class="iconhero"/></span>
                <p class="mt-3">200+ Pekerjaan</p>
              </div>
              <div class="col-md-4">
                <span><font-awesome-icon icon="fa-solid fa-sack-dollar" class="iconhero"/></span>
                <p class="mt-3">Penghasilan++</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!---->

      <!--About-->
      <div class="row mt-5 py-5">
        <div class="col-md-6 mt-3">
          <img src="../assets/about.png" alt="" class="img-fluid">
        </div>
        <div class="col-md-6 mt-5 align-self-md-center">
          <h3 class="mb-3">Website buat freelancer banget</h3>
          <p>Platform bagi freelancer untuk mencari pekerjaan apa saja, website terlengkap se-Indonesia</p>
          <ul class="list-group">
            <li class="list-group-item">
              <font-awesome-icon icon="fa-reguler fa-circle-check" class="me-2 about-icon"/>
              Tidak Ada Potongan Fee Admin
            </li>
            <li class="list-group-item">
              <font-awesome-icon icon="fa-reguler fa-circle-check" class="me-2 about-icon"/>
              Pembayaran Aman
            </li>
            <li class="list-group-item">
              <font-awesome-icon icon="fa-reguler fa-circle-check" class="me-2 about-icon"/>
              Rate Gaji Tinggi
            </li>
          </ul>
        </div>
      </div>
      <!---->

      <!--Feature-->
      <div class="row mt-5 py-5">
        <div class="col-md-12 mt-5 text-center">
          <h3 class="mb-3">Platform Freelancer Terbesar di Dunia</h3>
          <p class="mb-5">Berbagai macam pekerjaan tersedia di seluruh penjuru dunia</p>
          <img src="../assets/feature.png" alt="" class="img-fluid mt-5">
        </div>
      </div>
      <!---->

      <!--Testimonials-->
      <div class="row mt-5 py-5">
        <div class="col-md-12 mt-2 text-center">
          <h3 class="mb-3">Apa Kata Mereka?</h3>
          <p>Berikut ini adalah testimoni dari freelancer</p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <div class="card px-5 py-5 mb-sm-5">
            <div class="d-flex">
              <div class="flex-shrink-0">
                <img src="../assets/avatar-11.jpg" alt="..." class="testi-image">
              </div>
              <div class="flex-grow-1 ms-3">
                <h5 class="mb-3">Mantap Banget</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus, placeat.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="card px-5 py-5 mb-sm-5">
            <div class="d-flex">
              <div class="flex-shrink-0">
                <img src="../assets/avatar-8.jpg" alt="..." class="testi-image">
              </div>
              <div class="flex-grow-1 ms-3">
                <h5 class="mb-3">Platform Freelancer Terbaik Nih..</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus, placeat.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!---->
    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>

<style>
.card.kartu{
  border: none;
  box-shadow: 0 1px 2px rgba(53, 58, 75, 0.03), 
                0 2px 4px rgba(53, 58, 75, 0.03), 
                0 4px 8px rgba(53, 58, 75, 0.05), 
                0 8px 16px rgba(53, 58, 75, 0.03),
                0 16px 32px rgba(53, 58, 75, 0.05), 
                0 32px 64px rgba(53, 58, 75, 0.03);
}
.iconhero{
  width: 36px;
  height: 36px;
  color: #F53838;
  background-color: #FFECEC;
  padding: 12px 12px;
  border-radius: 50%;
}
.list-group-item{
  border: none;
}
.about-icon{
  color: #61c061;
}
.testi-image{
  width: 80px;
  height: 80px;
  border-radius: 50%;
}
.btn-primary{
  background-color: #F53838;
  border: none;
}
.btn-primary:hover{
  background-color: #cc2525;
}
</style>