<template>
  <v-container class="container">
    <v-column>
      <v-card class="card">
        <img src>
        <v-card-title>
          Work1
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
      <v-card class="card">
        <v-card-title>
          Work1
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
      <v-card class="card">
        <v-card-title>
          Work1
        </v-card-title>
        <v-card-content>
          説明
        </v-card-content>
      </v-card>
    </v-column>
  </v-container>
</template>

<script>
export default {
  data: () => ({
  }),
};
</script>

<style>
.container {
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo {
  width: 100vw;
}
.card {
  width: 80vw;
  margin: 100px;
  border-radius: 30px;
}
</style>