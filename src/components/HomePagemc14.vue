<template>
  <div class="container-center-horizontal">
    <div class="home-page-u40mc14u41 screen">
      <div class="section-43">
        <img class="upraveno_logo-1-1-34" :src="upraveno_Logo111" alt="upraveno_logo (1) 1" />
        <p class="penzion-v-srdci-esk-kanady-9 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</p>
        <div class="component-1-20">
          <div class="button-container-33">
            <navigace16 />
            <navigace17 />
            <navigace18 />
            <navigace19 />
            <navigace20 />
          </div>
        </div>
        <img
          class="vector-200-13"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200-1.svg"
          alt="Vector 200"
        />
      </div>
      <div class="section-44">
        <h1 class="vtejte-u-ns-na-penzionu-3 valign-text-middle heading-1">{{ vtejteUNsNaPenzionu }}</h1>
        <p class="lorem-ipsum-dolor-si-5 subtext">{{ loremIpsumDolorSi1 }}</p>
        <router-link to="/rezervace-3">
          <div class="button-156">
            <div class="rezervovat-3 heading-2">{{ rezervovat }}</div>
          </div></router-link
        ><router-link to="/kontakt-2">
          <div class="button-155">
            <div class="kontakt-40 heading-2">{{ kontakt }}</div>
          </div></router-link
        ><img-container :className="imgContainerProps.className" />
      </div>
      <div class="section-45">
        <div class="o-penzionu-mikmtor-3 valign-text-middle heading-1">{{ oPenzionuMikmtor }}</div>
        <div class="section-46">
          <list3 :spolecnePrsotory021="list31Props.spolecnePrsotory021" :title="list31Props.title" />
          <list3 :spolecnePrsotory021="list32Props.spolecnePrsotory021" :title="list32Props.title" />
          <list3 :spolecnePrsotory021="list33Props.spolecnePrsotory021" :title="list33Props.title" />
          <div class="icon-buttons-3">
            <router-link to="/o-ubytovani-3">
              <div class="button-155">
                <div class="vce-informac-3 subtext">{{ vceInformac1 }}</div>
              </div></router-link
            >
          </div>
        </div>
      </div>
      <div class="section-47">
        <p class="zitky-a-aktivity-v-okol-3 heading-1">{{ zitkyAAktivityVOkol }}</p>
        <p class="lorem-ipsum-dolor-si-5 subtext">{{ loremIpsumDolorSi2 }}</p>
        <router-link to="/okoli-2">
          <div class="button-155">
            <div class="vce-informac-3 subtext">{{ vceInformac2 }}</div>
          </div></router-link
        >
      </div>
      <div class="section-48">
        <img class="upraveno_logo-1-1-35" :src="upraveno_Logo112" alt="upraveno_logo (1) 1" /><container8 />
        <img
          class="vector-200-14"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200-2.svg"
          alt="Vector 200"
        />
        <div class="component-1-21">
          <div class="button-container-34">
            <component121 />
            <component122 />
            <component123 />
            <component124 />
            <component125 />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navigace16 from "./Navigace16";
import Navigace17 from "./Navigace17";
import Navigace18 from "./Navigace18";
import Navigace19 from "./Navigace19";
import Navigace20 from "./Navigace20";
import ImgContainer from "./ImgContainer";
import List3 from "./List3";
import Container8 from "./Container8";
import Component121 from "./Component121";
import Component122 from "./Component122";
import Component123 from "./Component123";
import Component124 from "./Component124";
import Component125 from "./Component125";
export default {
  name: "HomePagemc14",
  components: {
    Navigace16,
    Navigace17,
    Navigace18,
    Navigace19,
    Navigace20,
    ImgContainer,
    List3,
    Container8,
    Component121,
    Component122,
    Component123,
    Component124,
    Component125,
  },
  props: [
    "upraveno_Logo111",
    "penzionVSrdciEskKanady",
    "vtejteUNsNaPenzionu",
    "loremIpsumDolorSi1",
    "rezervovat",
    "kontakt",
    "oPenzionuMikmtor",
    "vceInformac1",
    "zitkyAAktivityVOkol",
    "loremIpsumDolorSi2",
    "vceInformac2",
    "upraveno_Logo112",
    "imgContainerProps",
    "list31Props",
    "list32Props",
    "list33Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.home-page-u40mc14u41
  align-items: flex-start
  background-color: $white
  display: flex
  flex-direction: column
  height: 2569px
  overflow: hidden
  width: 1504px

.section-43
  align-items: center
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.upraveno_logo-1-1-34
  height: 109px
  margin-bottom: -36.50px
  margin-left: -155.50px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-9
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.component-1-20
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -155.50px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 556px

.button-container-33
  align-items: flex-end
  display: flex
  height: 44px
  left: 20px
  min-width: 434px
  position: relative
  top: 20px

.vector-200-13
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 156px
  width: 1504px

.section-44
  align-content: space-between
  align-items: flex-start
  display: flex
  flex-wrap: wrap
  height: 784px
  justify-content: center
  padding: 60px 170px
  position: relative
  width: 1512px

.vtejte-u-ns-na-penzionu-3,
.o-penzionu-mikmtor-3,
.zitky-a-aktivity-v-okol-3
  color: $black
  font-weight: 400
  line-height: 100px
  margin-top: -1.00px
  position: relative
  text-align: center
  white-space: nowrap
  width: fit-content

.lorem-ipsum-dolor-si-5
  color: $gray
  font-weight: 600
  height: 120px
  line-height: 44px
  position: relative
  text-align: center
  width: 1151px

.button-156
  align-items: center
  background-color: $white
  border: 1px solid
  border-color: $fun-green
  border-radius: 10px
  cursor: pointer
  display: inline-flex
  flex: 0 0 auto
  gap: 10px
  justify-content: center
  overflow: hidden
  padding: 10px 25px
  position: relative

.rezervovat-3
  color: $fun-green
  font-weight: 400
  line-height: 44px
  margin-top: -1.00px
  position: relative
  white-space: nowrap
  width: fit-content

.button-155
  align-items: center
  background-color: $fun-green
  border-radius: 10px
  cursor: pointer
  display: inline-flex
  flex: 0 0 auto
  gap: 10px
  justify-content: center
  overflow: hidden
  padding: 10px 25px
  position: relative

.kontakt-40
  color: $surf
  font-weight: 400
  line-height: 44px
  margin-top: -1.00px
  position: relative
  text-align: center
  width: 172px

.section-45
  align-content: space-between
  align-items: flex-start
  display: flex
  flex-wrap: wrap
  height: 870px
  justify-content: center
  margin-left: 4px
  padding: 60px 170px
  position: relative
  width: 1504px

.section-46
  align-items: center
  display: flex
  flex-wrap: wrap
  gap: 67px 67px
  height: 714px
  justify-content: center
  margin-bottom: -64.00px
  margin-left: -174.00px
  margin-right: -174.00px
  padding: 60px 170px
  position: relative
  width: 1512px

.icon-buttons-3
  align-items: center
  display: flex
  gap: 8px
  justify-content: center
  margin-bottom: -46.50px
  margin-left: -44.00px
  margin-right: -44.00px
  position: relative
  width: 1260px

.vce-informac-3
  color: $surf
  font-weight: 600
  line-height: 44px
  margin-top: -1.00px
  position: relative
  white-space: nowrap
  width: fit-content

.section-47
  align-content: space-between
  align-items: flex-start
  display: flex
  flex-wrap: wrap
  height: 442px
  justify-content: center
  padding: 60px 170px
  position: relative
  width: 1504px

.section-48
  align-items: center
  display: flex
  gap: 60px
  height: 313px
  justify-content: center
  margin-top: 4px
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1504px

.upraveno_logo-1-1-35
  height: 109px
  object-fit: cover
  position: relative
  width: 153px

.vector-200-14
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 312px
  width: 1504px

.component-1-21
  border-radius: 5px
  height: 308px
  margin-bottom: -57.50px
  margin-top: -57.50px
  overflow: hidden
  position: relative
  width: 260px

.button-container-34
  align-items: flex-start
  display: flex
  flex-direction: column
  left: 20px
  min-height: 220px
  position: relative
  top: 20px
  width: 80px
</style>
