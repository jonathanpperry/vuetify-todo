<template>
  <div class="home">
    <h1>Homepage</h1>
    <v-btn class="pink white--text">Click Me</v-btn>
    <v-btn flat color="pink">Click Me</v-btn>

    <v-btn depressed class="pink white--text">
      <v-icon left>home</v-icon>
      <span>Email me</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon left small>email</v-icon>
      <span>Email me</span>
    </v-btn>
  </div>
</template>

<script>
export default {};
</script>
