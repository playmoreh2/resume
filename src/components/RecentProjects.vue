<template>
  <section
    id="recent-projects"
    class="hide-overflow"
  >
    <v-layout
      xs12
      row
      wrap>
      <v-flex
        xs12
        md6
        lg6
        accent
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-2
          style="transform: rotate(180deg) translateX(25%)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          우리카드
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2019.11 ~ 2020.06
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills6"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <img src="../assets/main_woori.png" style="width:100%;">
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
      <v-flex
        xs12
        md6
        lg6
        primary
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateX(25%)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          BNK 경남은행
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2019.06 ~ 2019.10
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills5"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <img src="../assets/main_bnk.png" style="width:100%;">
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout
      xs12
      row
      wrap>
      <v-flex
        xs12
        md6
        lg6
        primary
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateX(0)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          KDB 산업은행
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2018.05 ~ 2019.03
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <v-img
                :src="require(`@/assets/main_kdb.png`)"
                max-height="300"
              />
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
      <v-flex
        xs12
        md6
        lg6
        accent
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-2
          style="transform: rotate(180deg) translateX(25%)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          HRD-Net
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2016.11 ~ 2017.03
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills2"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <v-img
                :src="require(`@/assets/main_hrdnet.png`)"
                max-height="300"
              />
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout
      xs12
      row
      wrap>
      <v-flex
        xs12
        md6
        lg6
        white
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-2
          style="transform: rotate(180deg) translateX(25%)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          SM 엔터네인먼트
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2016.01 ~ 2016.04
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills3"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <v-img
                :src="require(`@/assets/main_fanbook.png`)"
                max-height="300"
              />
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
      <v-flex
        xs12
        md6
        lg6
        primary
        text-xs-center
        pa-5
        white--text
        class="hide-overflow"
      >
        <base-bubble-2
          style="transform: rotate(360deg) translateX(30%)"
        />
        <base-heading
          class="display-1 info--text font-weight-bold"
        >
          KB국민은행<br><span class="title">(스타뱅킹웹앱)</span>
        </base-heading>

        <base-subheading
          class="title info--text"
        >
          2016.07 ~ 2016.11
        </base-subheading>

        <base-subheading
          class="body-1 info--text"
        >
          Skills
        </base-subheading>

        <v-alert
          outlined
          color="info"
        >
          <v-layout
            v-for="(skill, i) in skills4"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              text-sm-left
              v-text="skill.name"
            />
            <v-flex
              xs6
              text-xs-right
              v-text="`${skill.value}%`"
            />
            <v-progress-linear
              :value="skill.value"
              color="info"
              height="8"
            />
          </v-layout>
        </v-alert>

        <v-card
          color="secondary"
        >
          <v-container
            grid-list-md
            pa-2
          >
            <v-layout wrap>
              <img src="../assets/main_kb.png" style="width:100%;">
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  data: () => ({
    skills: [
      {
        name: 'Web Publishing',
        value: 30
      },
      {
        name: 'Javascript(Jquery)',
        value: 0
      }
    ],
    skills2: [
      {
        name: 'Web Publishing',
        value: 70
      },
      {
        name: 'Javascript(Jquery)',
        value: 50
      }
    ],
    skills3: [
      {
        name: 'Web Publishing',
        value: 100
      },
      {
        name: 'Javascript(Jquery)',
        value: 100
      }
    ],
    skills4: [
      {
        name: 'Web Publishing',
        value: 50
      },
      {
        name: 'Javascript(Jquery)',
        value: 30
      }
    ],
    skills5: [
      {
        name: 'Web Publishing',
        value: 40
      },
      {
        name: 'Javascript(Jquery)',
        value: 30
      }
    ],
    skills6: [
      {
        name: 'Web Publishing',
        value: 30
      },
      {
        name: 'Javascript(Jquery)',
        value: 0
      }
    ]
  })
}
</script>
