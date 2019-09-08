<template>
  <v-container class="container">
    <div class="d-flex flex-column">
      <v-card class="card">
        <v-card-title>
          Work1
        </v-card-title>
      </v-card>
      <div class="d-flex flex-row">
        <v-card class="card">
          <v-card-title>
            Work2
          </v-card-title>
        </v-card>
        <v-card class="card">
          <v-card-title>
            Work3
          </v-card-title>
        </v-card>
      </div>
    </div>
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
  /* width: 80vw; */
  margin: 5px;
  border-radius: 30px;
  height: 100%;
}
</style>