<template>
  <div>
    <a
      class="ma-2"
      :large="large"
      style="text-decoration: none;"
      href="mailto:playmoreh2@gmail.com"
    >
      <v-icon
        dark
        color="primary"
        v-text="'mdi-email'"
      />
    </a>
    <a
      class="ma-2"
      :large="large"
      style="text-decoration: none;"
      href="tel:010-8840-1074"
    >
      <v-icon
        dark
        color="primary"
        v-text="'mdi-phone'"
      />
    </a>
  </div>
</template>

<script>
export default {
  props: {
    large: {
      type: Boolean,
      default: false
    }
  }
}
</script>
