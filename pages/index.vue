<template>
  <v-container fluid class="fill-height">
    <div class="container">
      <div class="display-1 font-weight-black color-hmif-yellow">Hi, there!</div>
      <div class="mt-2">Silakan masukkan kode acara untuk melanjutkan. <b>Semangat ngabsennya!</b></div>
      <div class="mt-3">
        <v-text-field
          label="Kode Acara"
          single-line
          outlined
        ></v-text-field>
      </div>
      <v-btn class="text-none font-weight-bold letter-spacing-normal white--text" block color="#FF9800" elevation="0">Lanjut</v-btn>
      <div class="mt-3">
        <small>
          <a class="text-decoration-none" href="https://attendance.hmif.tech/admin">Belum punya acara? Buat</a>
        </small>
      </div>
      <div class="mt-6">
        <small>
          Copyright &copy; HMIF ITB 2020
        </small>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style scoped lang="scss">
  .container {
    max-width: 450px;
    margin: 0 auto;
  }
</style>
