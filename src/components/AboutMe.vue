<template>
  <section
    id="about"
    class="hide-overflow"
  >
    <v-layout white>
      <v-flex
        xs12
        md6
        pa-5
      >
        <base-bubble-1
          style="transform: translate(5%, -5%)"
        />
        <base-heading class="display-1 info--text font-weight-bold">
          '프론트엔드 개발자 이효훈을 소개합니다'
        </base-heading>

        <base-subheading class="info--text">
          "작은 업무라도 최선을 다하는 프론트개발자가 되는것이 목표입니다!"
        </base-subheading>

        <base-text class="mb-5">
          평소 웹개발에 대한 관심이 있었지만 전공 분야와 달라서 접근하기가 쉽지 않았습니다. 찾아보니 웹퍼블리셔가 접근하기 쉬워 시작하게 되었습니다.<br>
          퍼블리싱을 하면서 스크립트에 대한 로망이 생기게 되었고, 스터디 및 관련 서적, 인강등으로 틈틈히 학습하였습니다. 최근에는 Vuejs에 대한 관심이 많아져서 스터디에 참여하고 있던 중에 Vuejs 및 Vuetify를 이용해 간단한 포트폴리오를 만들어 보았습니다.<br>
          여러 프로젝트를 참여하면서 많은 사람들과 함께 일하면서 소통의 중요성을 느끼게 되었고, 업무능력 만큼 원활한 소통 능력도 키우기 위해 상대방의 말을 들어주는 자세와 항상 친절한 태도를 유지하려고 노력하고 있습니다.<br>
          저는 웹개발을 늦게 시작하여 경력에 비해 나이가 많은 편입니다. 나이가 일을 하는데 중요한 요소는 아니라고 생각하고 늦게 시작한 만큼 더 열심히 해서 앞으로 나아가고 싶은 마음이 큽니다. 제가 맡은 업무는 성실히 성공적으로 마무리 하기 위해 노력하고 있습니다.
        </base-text>
      </v-flex>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <v-img
          :src="require('@/assets/aboutme.png')"
          height="100%"
        />
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  data: () => ({
    skills: [
      {
        name: 'Web Design',
        value: 100
      },
      {
        name: 'Web Development',
        value: 75
      },
      {
        name: 'Web Support',
        value: 90
      }
    ]
  })
}
</script>
