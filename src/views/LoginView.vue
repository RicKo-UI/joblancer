<template>
    <div class="login py-5">
      <div class="container mt-3">
        <div class="row">
            <div class="col-md-6">
                <img src="../assets/about.png" alt="" class="img-fluid">
            </div>
            <div class="col-md-6 align-self-center">
                <h3>Sign In</h3>
                <p class="mb-5">Silahkan masuk dengan akun yang sudah didaftarkan ya</p>
                <form>
                    <div class="mb-3">
                        <label for="exampleInputEmail1" class="form-label">Email address</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Masukan Email Terdaftar">
                    </div>
                    <div class="mb-5">
                        <label for="exampleInputPassword1" class="form-label">Password</label>
                        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Masukan Password Valid Kamu">
                    </div>
                    <div class="mb-3">
                        <router-link to="/" class="d-grid gap-2">
                            <button type="submit" class="btn btn-primary">Submit</button>
                        </router-link>
                        
                    </div>
                    <div class="mb-3 d-flex align-items-end">
                        Belum Punya Akun? 
                        <router-link to="/" class="link-signin ms-2">
                            Daftar
                        </router-link>
                    </div>
                    </form>
            </div>
        </div>
      </div>
    </div>
</template>
  
<script>
// @ is an alias to /src
  
  
export default {
    name: 'LoginView',
    components: {
      
    }
}
</script>
  
<style>
.link-signin{
    text-decoration: none;
}
</style>