<template>
  <div>
    <v-snackbar
      v-model="snackbar"
      :timeout="timeout"
      top
      multi-line
    >
      {{ text }}
      <v-btn
        color="pink"
        flat
        @click="snackbar = false"
      >
        Close
      </v-btn>
    </v-snackbar>
    <welcome />
    <recent-projects />
    <about-me />
  </div>
</template>

<script>
export default {
  data () {
    return {
      snackbar: true,
      timeout: 3000,
      text: '2021 플립커뮤니케이션즈에 지원하기위해 Vue + Vuetify를 이용해 개발하였습니다.'
    }
  },
  components: {
    AboutMe: () => import('@/components/AboutMe'),
    RecentProjects: () => import('@/components/RecentProjects'),
    Welcome: () => import('@/components/Welcome')
  }
}
</script>
