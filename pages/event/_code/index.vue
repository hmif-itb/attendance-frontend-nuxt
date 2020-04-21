<template>
  <client-only>
    <div>
      <v-app-bar
        color="transparent"
        elevation="0"
        style="border-bottom: 0.5px solid #efefef !important;"
      >
        <v-container class="py-0 px-0" align="center" fill-height>
          <v-layout>
            <v-container fill-height class="pa-0">
              <nuxt-link to="/">
                <v-img :src="require('~/assets/logo-tech.png')" width="35" style="margin-right: 15px" />
              </nuxt-link>
              <div style="line-height: 16px !important;">
                <div>
                  <div class="font-weight-bold" style="font-size: 16px;">Musyawarah Kerja</div>
                  <small class="grey--text">Kode #{{ $route.params.code }}</small>
                </div>
              </div>
            </v-container>
            <v-spacer />
            <div class="pa-0 fill-height d-flex" style="align-items: center">
              <v-btn outlined class="text-none letter-spacing-normal font-weight-bold mr-3" color="red" elevation="0">
                Exit
              </v-btn>
              <v-btn class="text-none letter-spacing-normal font-weight-bold white--text" color="#FF9800" elevation="0">
                Present
              </v-btn>
            </div>
          </v-layout>
        </v-container>
      </v-app-bar>
    </div>
  </client-only>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>

</style>
