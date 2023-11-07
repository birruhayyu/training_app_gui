<!-- eslint-disable vue/multi-word-component-names -->
// eslint-disable-next-line vue/multi-word-component-names
<template>
  <v-container>
  <v-text-field
      label="Email"
      :rules="rules"
      hide-details="auto"
    ></v-text-field>
    <v-text-field label="Password"></v-text-field>
  <v-btn>Submit</v-btn>
  </v-container>
</template>
<script setup>
</script>
<style>
</style>
