<template>
    <div id="app">
        <v-form ref="form" v-model="valid" lazy-validation>
            <v-text-field v-model="name" :counter="10" :rules="nameRules" label="Name" required></v-text-field>
            <v-text-field v-model="alamat" :counter="100" :rules="alamatRules" label="Alamat" required></v-text-field>
            <v-text-field v-model="no" :counter="15" :rules="noRules" label="No Telp" required></v-text-field>
            <v-text-field textarea v-model="desc" :counter="2000" :rules="descRules" label="Deskripsi" required></v-text-field>

            <v-btn :disabled="!valid" color="success" @click="validate">Kirim</v-btn>
        </v-form>
    </div>
</template>