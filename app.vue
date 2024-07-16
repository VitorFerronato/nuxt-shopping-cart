<template>
  <v-app id="inspire" :theme="useCartStore().getTheme">
    <Header />
    <v-main>
      <v-container>
        <NuxtPage />
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
import {useCartStore} from './stores/cart'
</script>