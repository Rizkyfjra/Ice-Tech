<template>
  <v-layout>
    <v-flex text-xs-center><br><br><br><br><br><br><br><br><br>
      <div class="text-xs-center" id="home">
        <parallax :fixed="false">  
        <img v-parallax="0.6" src="/Picture4.png" height="200px" alt="Vuetify.js" class="mb-5" />
        </parallax>
      </div><br>

      <v-layout mt-5 pt-5 >
        <v-flex>  
          <v-card>
            <v-img src="/laptop.jpg" class="white--text" height="300px" width="100%" >
              <v-container fill-height fluid>
                <v-flex>
                  <span class="headline"><center><h2>Tempat Pembuatan Website untuk Perusahaan atau Komersil</h2></center></span><br>
                  <span><center><p>IceTech Adalah tempat yang tepat untuk anda memulai bisnis, dengan harga yang murah IceTech menawarkan berbagai kemudahan untuk para<br> pelanggan
        dengan mengutamakan keinginan pelanggan dalam membuat web</p></center></span>
                </v-flex>
              </v-container>
            </v-img>
          </v-card>
        </v-flex>
      </v-layout>
      <!-- <v-card> -->
      <br>
        <br>
          <br>
            <br>
              <br>
                <br>
                  <br>
                    <br>
                      <br>
                        <br>
                          <br>
                            <br>
                              <br>
                                <br>
        <div style="position:relative;" class="layanan" id="layanan">
          <parallax :fixed="true">  
            <v-img v-parallax="0.2" src="/layanan.jpg" width="100%" >
        <center><h2 v-parallax="0.1" >LAYANAN KAMI</h2></center><br><br>
        <center><v-img v-parallax="0.1" src="/coding.png" height="20%" width="20%"></v-img></center><br><br>
        <h4 v-parallax="0.1"><center>Website Appication</center></h4>
            </v-img>
          </parallax>
        </div>
      <br>
        <br>
          <br>
            <br>
              <br>
                <br>
                  <br>
                    <br>
                      <br>
                        <br>
                          <br>
      <center><h2  v-parallax="0.2">PENGERJAAN DI ICETECH
        <img id="pengerjaan" src="/how2.png" height="500px" width="100%" alt="home" class="mb-5"> 
      </h2>
      </center>
      
      <br>
        <br>
          <br>
            <br>
              <br>
                <br>
                  <br>
                    <br>
                      <br>
          <v-layout>
            <v-flex xs12 sm6 offsite-sm3>
              <v-card>
                <v-img class="white--text" height="200px" src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                    <v-flex xs12 align-end flexbox>
                      <span class="headline">Top 10 Theme Ice Tech</span>
                    </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
                <v-card-title>
                  <div>
                    <span class="grey--text">Nomor 10</span><br>
                    <span>INI CEK DULU</span><br>
                    <span>CEK DULU CUYYYY</span>
                  </div>
                </v-card-title>
                <v-card-action>
                  <v-btn flat color="blue">Share</v-btn>
                  <v-btn flat color="blue">Explore</v-btn>
                </v-card-action>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 offsite-sm3>
              <v-card>
                <v-img class="white--text" height="200px" src="https://static.independent.co.uk/s3fs-public/thumbnails/image/2017/09/12/11/naturo-monkey-selfie.jpg?w968h681">
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                    <v-flex xs12 align-end flexbox>
                      <span class="headline">Top 10 Theme Ice Tech</span>
                    </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
                <v-card-title>
                  <div>
                    <span class="grey--text">Nomor 10</span><br>
                    <span>INI CEK DULU</span><br>
                    <span>CEK DULU CUYYYY</span>
                  </div>
                </v-card-title>
                <v-card-action>
                  <v-btn flat color="blue">Share</v-btn>
                  <v-btn flat color="blue">Explore</v-btn>
                </v-card-action>
              </v-card>
            </v-flex>
          </v-layout><br>
      <!-- </v-card> -->
      <br>
        <br>
          <br>
            <br>
              <br>
                <br>
                  <br>
                    <br>
                      <br>
      <div id="tim">
        <center><h1>TIM KAMI</h1></center>
        <!-- <div class="team" center>
        <v-img class="mx-auto rounded-circle" src="/user.png" ></v-img>
        <v-img class="mx-auto rounded-circle" src="/user.png" ></v-img>
        <v-img class="mx-auto rounded-circle" src="/user.png" ></v-img>
        </div> -->
      
        <div class="row">
          <div class="kolom">
            <div class="card">
              <v-img src="/man3.png" alt="ceo" style="width: 98%"></v-img>
              <div class="container">
                <center><h2>RIZKY FAJAR A</h2></center><br>
                <center><p class="bawah">Frontend Developer</p></center>
              </div>
            </div>
          </div>

          <div class="kolom">
            <div class="card">
              <v-img src="/businessman.png" alt="ceo" style="width: 98%"></v-img>
              <div class="container">
                <center><h2>DICKY NURSALIM</h2></center><br>
                <center><p class="bawah">Backend Developer</p></center>
              </div>
            </div>
          </div>
          <div class="kolom">
            <div class="card">
              <v-img src="/man.png" alt="ceo" style="width: 98%"></v-img>
              <div class="container">
                <center><h2>M KAMIL M</h2></center><br>
                <center><p class="bawah">System Analyst</p></center>
              </div>
            </div>
          </div>

          <div class="kolom">
            <div class="card">
              <v-img src="/man2.png" alt="ceo" style="width: 98%"></v-img>
              <div class="container">
                <center><h2>RADEN ANDRA Y</h2></center><br>
                <center><p class="bawah">Design</p></center>
              </div>
            </div>
          </div>
      </div>
    </div>
    
    <center> 
      <br>
        <br>
          <br>
            <br>
              <br>
                <br>
                  <br>
                    <br>
                      <br>
                        <br>
                          <br>
                            <br>
                            <div id="mulai">
        <h2>AYO MULAI</h2><br><br></div>
        <!-- <v-btn block color="success" to="/input" >Mulai</v-btn> -->
    <v-layout v-parallax="0.5" row justify-center>
      
      <v-dialog v-model="dialog" persistent max-width="600px">
        <template v-slot:activator="{ on }">
          <v-btn  block color="primary" dark v-on="on">Mulai</v-btn>
        </template>
        <v-card>
          <v-card-title>
            <span class="headline">Input Data</span>
          </v-card-title>
          <v-card-text>
            <v-container grid-list-md>
              <v-layout wrap>
                <v-flex xs12>
                  <v-text-field label="Nama*" required></v-text-field>
                </v-flex>
                <v-flex xs12>
                  <v-text-field label="Email*" required></v-text-field>
                </v-flex>
                <v-flex xs12>
                  <v-text-field label="No Telp*" required></v-text-field>
                </v-flex>
                <v-flex xs12>
                  <v-text-field textarea label="Deskripsi*" type="text" required></v-text-field>
                </v-flex>
              </v-layout>
            </v-container>
            <small>*Harus Diisi</small>
          </v-card-text>
          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn color="blue darken-1" flat @click="dialog = false">Close</v-btn>
            <v-btn color="blue darken-1" flat @click="dialog = false">Save</v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </v-layout>
  </center>
    </v-flex>
  </v-layout>
</template>

<script>
import Vue from 'vue'
import VueParallaxJs from 'vue-parallax-js'
Vue.use(VueParallaxJs)

export default {
  data () {
    return {
      dialog: false,
      VueParallaxJs
    }
  }
}
</script>
<style>
.layanan{
  color: white;
}
.team{
  height: 30%;
  width: 30%;
}
*, *:before, *:after {
  box-sizing: inherit;
}
.kolom{
  float:left;
  width:20%;
  margin-bottom: 16px;
  margin-left: 50px;
  padding: 0 8px;
  
}
@media screen and (max-width: 650px){
  .kolom{
    width:100%;
    display: block;
  }
}
.card{
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}
.container{
  padding: 0 16px;
}
.container::after, .row::after{
  content:"";
  clear: both;
  display: table;
}
.bawah{
  color: grey;
}
.template{
  scroll-behavior: smooth;
}
</style>  