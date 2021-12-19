<template>
  <v-footer dark padless>
    <v-card flat tile class="pink white--text text-center">
      <v-card-text>
        <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4 white--text"
            icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>
      <v-card-text class="white--text pt-0">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad animi aperiam, consectetur corporis, dicta doloremque dolorum explicabo harum laudantium numquam omnis porro repellat suscipit. Amet eum fuga id suscipit voluptatibus.
      </v-card-text>
      <v-divider></v-divider>
      <v-card-text class="white--text">
        {{ new Date().getFullYear()}} - Movie Project
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: [
      'mdi-facebook',
      'mdi-twitter',
      'mdi-linkedin',
      'mdi-instagram'
    ]
  })
}
</script>

<style>

</style>
