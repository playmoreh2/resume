<template>
  <v-footer
    height="100"
    class="align-center justify-center column fill-height"
  >
    <social-media large />
  </v-footer>
</template>

<script>
export default {
  components: {
    SocialMedia: () => import('@/components/SocialMedia')
  }
}
</script>
