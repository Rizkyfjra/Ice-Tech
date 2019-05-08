<template>
  <v-app white>
    <!-- <v-navigation-drawer
      :mini-variant.sync="miniVariant"
      :clipped="clipped"
      v-model="drawer"
      fixed
      app
    > -->
      <!-- <v-list>
        <v-list-tile
          router
          :to="item.to"
          :key="i"
          v-for="(item, i) in items"
          exact
        >
          <v-list-tile-action>
            <v-icon v-html="item.icon"></v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title v-text="item.title"></v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
      </v-list> -->
      <!-- </v-navigation-drawer> -->
    <v-toolbar class="navbar navbar-default navbar-fixed-top" color="blue"  height="60px" fixed app :clipped-left="clipped">
      <!-- <v-toolbar-side-icon @click="drawer = !drawer"></v-toolbar-side-icon> -->
      <img src="/ikon.png" height="40px">
      
      <v-toolbar-title class="title" v-text="title"></v-toolbar-title>

      <v-spacer></v-spacer>
      
      <v-navigation>
        <div class="nav">
          
        <a v-bind:href="'#home'" flat class="white--text mx-3">AWAL</a>
        <a v-bind:href="'#layanan'" flat class="white--text mx-3"> LAYANAN</a>
        <a v-bind:href="'#pengerjaan'" flat class="white--text mx-3"> PENGERJAAN</a>
        <a v-bind:href="'#tim'" flat class="white--text mx-3"> TIM</a>
        <a v-bind:href="'#mulai'" flat class="white--text mx-3"> MULAI</a>
        <a v-bind:href="'#mulai'" flat class="white--text ml-3"> TENTANG</a>
        <!-- <v-btn flat color="white" href="/inspire">Belanja</v-btn>
        <v-btn flat color="white" href="/input">Input</v-btn> -->
      </div>
      </v-navigation>
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-navigation
      temporary
      :right="right"
      v-model="rightDrawer"
      fixed
    >
    </v-navigation>

    <v-footer height="auto">
      <v-card class="flex" flat tile>
        <v-card-title class="blue">
          <div class="row">
            <div class="col-sm-4">Hubungi IceTech</div>
            <img type="image" src="/fb.png"  alt="www.facebook.com" height="30px">
            <img src="/ig.png" height="30px">
            <div class="col-sm-4">Metode Pembayaran</div><br>
            <img src="/BCA-512.png" height="40px"> <img src="/BNI.png" height="40px"> <img src="/mandiri.png" height="40px">
          </div>
          <v-spacer></v-spacer>
          <div class="row">
            <div class="col-sm-4">
      <img src="/panjang.jpg" height="80px"></div>
        <div class="col-sm-4">IceTech Adalah Penyedia Jasa Yang berfokus pada Website<br>
          kemudahan yang ditawarkan IceTech Membuat konsumen nyaman<br>
          untuk menggunakan Jasa Kami.
        </div>
            </div>
        </v-card-title>
        <v-card-actions class="blue darken-3 justify-center">
          &copy;2019 — <strong>IceTech</strong>
        </v-card-actions>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        clipped: false,
        drawer: true,
        fixed: false,
        items: [
          { icon: 'apps', title: 'Halaman Utama', to: '/' },
          { icon: 'bubble_chart', title: 'Inspire', to: '/inspire' },
          { icon: 'input', title: 'input', to: '/input' }
        ],
        miniVariant: false,
        right: true,
        rightDrawer: false,
        title: 'IceTech'
      }
    }
  }
</script>
<style>
.nav{
  scroll-behavior: smooth;
}
.col-sm-4{
  color: white;
}
.title{
  color:white;
}
.blue{
  color: white;
}
.nav{
  scroll-behavior: smooth;
  text-align: center;
}
a{
  text-decoration: none;
}
</style>