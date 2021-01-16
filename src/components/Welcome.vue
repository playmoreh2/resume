<template>
  <section
    id="welcome"
    class="hide-overflow"
  >
    <v-layout>
      <v-flex
        hidden-sm-and-down
        md4
        align-center
        justify-center
        v-scroll-reveal.reset="{ origin: 'left', distance: '300px', easing: 'ease-in-out' }"
      >
        <v-layout
          align-center
          justify-center
          fill-height
        >
          <p
            class="display-2 font-weight-bold"
            v-scroll-reveal.reset="{ origin: 'right', distance: '300px', easing: 'ease-in-out', duration: 500 }"
          >
            친절한 개발자
          </p>
        </v-layout>
      </v-flex>

      <v-flex
        xs12
        md8
        align-content-space-between
        layout
        :pa-5="$vuetify.breakpoint.smAndDown"
        wrap
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs12
            m10
          >
<!--            <p-->
<!--              class="display-2 font-weight-bold"-->
<!--              v-scroll-reveal.reset="{ origin: 'right', distance: '300px', easing: 'ease-in-out', duration: 500 }"-->
<!--            >-->
<!--              친절한 개발자 이효훈-->
<!--            </p>-->
            <p
              class="mt-5 title"
              v-scroll-reveal.reset="{ origin: 'right', distance: '300px', easing: 'ease-in-out', duration: 700 }"
            >
              "원활한 소통과 친절한 마인드의 프론트엔드 개발자!!"<br><br>

              "최근 프론트엔드 개발자의 역할이 커지면서 스크립트의 중요성을 느낌"<br><br>

              "스터디 및 관련 자료를 찾아가며 꾸준히 스스로 학습"<br><br>

              "최근 SPA에 관심이 많아져 Vuejs를 학습하고 포트폴리오페이지 개발"<br><br>

              "맡은 업무는 끝까지 해내려는 강한 의지와 집중력"<br><br>

              "패스트캠퍼스 '프론트엔드 개발 올인원 패키지' 수강완료"<br><br>
            </p>
          </v-flex>
        </v-layout>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-flex>
    </v-layout>
  </section>
</template>
