<template>
  <div id="app">
    <header role="banner">
      <nav class="navbar navbar-expand-md navbar-dark bg-light">
        <div class="container">
          <a class="navbar-brand" href="index.html">Jo'rabek saloni</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample05" aria-controls="navbarsExample05" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse navbar-light" id="navbarsExample05">
            <ul class="navbar-nav ml-auto pl-lg-5 pl-0">
              <li class="nav-item">
                <router-link class="nav-link active reload" to="/">Bosh sahifa</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link active reload" to="/hairstyle">Xizmatlar</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link active reload" to="/about">Biz haqimizda</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link active reload" to="/gallery">Galareya</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link active reload" to="/sertificate">Sertifikatlar</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link active" to="/contact">Bog'lanish</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- END header -->

    <router-view/>

    <footer class="site-footer">
      <div class="container">
        <div class="row mb-4">
          <div class="col-md-3">
            <h3 class="mb-4">Ma'lumotlar</h3>
            <p class="mb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut, quod!</p>
            <ul class="list-unstyled ">
              <li class="d-flex"><span class="mr-3"><span class="icon ion-ios-location"></span></span><span class="">Al-Xorazmiy ko'cha, Urganch shahar, Xorazm viloyat, O'zbekiston </span></li>
              <li class="d-flex"><span class="mr-3"><span class="icon ion-ios-telephone"></span></span><span class="">+998 00 000 00 00</span></li>
              <li class="d-flex"><span class="mr-3"><span class="icon ion-email"></span></span><span class="">barber@gmail.com</span></li>
            </ul>
          </div>
          <div class="col-md-2">
            <h3 class="mb-4">Havola</h3>
            <ul class="list-unstyled ">
              <li><router-link to="/">Bosh sahifa</router-link></li>
              <li><router-link to="/hairstyle">Xizmatlar</router-link></li>
              <li><router-link to="/about">Biz haqimizda</router-link></li>
              <li><router-link to="/gallery">Galareya</router-link></li>
              <li><router-link to="/sertificate">Sertifikatlar</router-link></li>
              <li><router-link to="/contact">Bog'lanish</router-link></li>
            </ul>
          </div>
          <div class="col-md-2">
            <h3>Ulanishlar</h3>
            <p>
              <br>
              <a href="https://www.facebook.com/" class="p-3"><span class="fa fa-facebook">  Facebook</span></a>
              <br>
              <br>
              <a href="https://twitter.com/" class="p-3"><span class="fa fa-twitter">  Twitter</span></a>
              <br>
              <br>
              <a href="https://www.instagram.com/" class="p-3"><span class="fa fa-instagram">  Instagram</span></a>
              <br>
              <br>
              <a href="https://www.youtube.com/" class="p-3"><span class="fa fa-youtube">  YouTube</span></a>
              <br>
              <br>
              <a href="https://www.telegram.com/" class="p-3"><span class="fa fa-telegram">  Telegram</span></a>
            </p>
          </div>
          <div  class="col-md-5">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4282.817556374759!2d60.62925233249815!3d41.56942478378534!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x41dfcfacdd1a667f%3A0x492de1fcb31687f4!2sTATU%20UF%20Talabalar%20turar%20joyi!5e0!3m2!1sen!2s!4v1654582381500!5m2!1sen!2s"
                  width="600" height="350" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
        </div>
      </div>
      <hr>
    </footer>
    <!-- END footer -->
    <div id="loader" class="show fullscreen"><svg class="circular" width="48px" height="48px"><circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee"/><circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10" stroke="#f4b214"/></svg></div>
  </div>

</template>
<script src="https://www.google.com/recaptcha/api.js?onload=vueRecaptchaApiLoaded&render=explicit" async defer></script>
<script>
import './assets/js/jquery-3.2.1.min';
import './assets/js/jquery-migrate-3.0.0';
import './assets/js/popper.min';
import './assets/js/bootstrap.min';
import './assets/js/owl.carousel.min';
import './assets/js/jquery.waypoints.min';
import './assets/js/jquery.stellar.min';
import './assets/js/jquery.magnific-popup.min';
import './assets/js/magnific-popup-options';
import './assets/js/main';

export default {
  name: 'App'
}
</script>

<style>
@import "assets/fonts/ionicons/css/ionicons.min.css";
@import "assets/fonts/fontawesome/css/font-awesome.min.css";
@import "assets/fonts/flaticon/font/flaticon.css";

@import "assets/css/style.css";
@import "assets/css/bootstrap.css";
@import "assets/css/animate.css";
@import "assets/css/magnific-popup.css";
@import "assets/css/owl.carousel.min.css";

@import "sweetalert2/dist/sweetalert2.min.css";
</style>
