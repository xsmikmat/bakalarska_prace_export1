<template>
  <div class="container-center-horizontal">
    <div class="kontakt-mc14 screen">
      <div class="section-36">
        <router-link to="/homepage-3"
          ><img class="upraveno_logo-1-1-29" :src="upraveno_Logo111" alt="upraveno_logo (1) 1"
        /></router-link>
        <p class="penzion-v-srdci-esk-kanady-6 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</p>
        <div class="component-1-15">
          <div class="button-container-28">
            <component176 :oUbytovn="component176Props.oUbytovn" />
            <component177 :okol="component177Props.okol" />
            <component178 :fotogalerie="component178Props.fotogalerie" />
            <component179 :rezervace="component179Props.rezervace" />
            <component180 :kontakt="component180Props.kontakt" />
          </div>
        </div>
        <img
          class="vector-200-2"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
          alt="Vector 200"
        />
      </div>
      <div class="list-27">
        <div class="container-38">
          <div class="title-59 roboto-bold-black-40px">{{ title1 }}</div>
        </div>
        <div class="list-28">
          <div class="row-15">
            <item7 :title="item71Props.title" :subtitle="item71Props.subtitle" :frameProps="item71Props.frameProps" />
            <item7 :title="item72Props.title" :subtitle="item72Props.subtitle" :frameProps="item72Props.frameProps" />
            <item7 :title="item73Props.title" :subtitle="item73Props.subtitle" :frameProps="item73Props.frameProps" />
          </div>
        </div>
        <img
          class="vector-200-3"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200-3.svg"
          alt="Vector 200"
        />
      </div>
      <div class="list-29">
        <div class="title-60 roboto-bold-black-40px">{{ title2 }}</div>
        <div class="container-39">
          <item22 :title="item221Props.title" :subtitle="item221Props.subtitle" />
          <item22 :title="item222Props.title" :subtitle="item222Props.subtitle" />
          <item22 :title="item223Props.title" :subtitle="item223Props.subtitle" />
        </div>
        <div class="list-30">
          <div class="row-16">
            <item22 :title="item224Props.title" :subtitle="item224Props.subtitle" />
            <item22 :title="item225Props.title" :subtitle="item225Props.subtitle" />
            <item22 :title="item226Props.title" :subtitle="item226Props.subtitle" />
          </div>
        </div>
        <img
          class="vector-200-4"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
          alt="Vector 200"
        />
      </div>
      <div class="section-container">
        <div class="section-37">
          <div class="map-container-3">
            <div class="image-17">
              <div class="overlap-group-4">
                <img
                  class="image-18"
                  src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/image.svg"
                  alt="image"
                />
                <div class="title-61 roboto-medium-black-16px">{{ title3 }}</div>
                <img
                  class="ic-location-2"
                  src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/ic-location.svg"
                  alt="ic-location"
                />
              </div>
            </div>
          </div>
          <img
            class="vector-200-5"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="section-38">
          <img class="upraveno_logo-1-1-30" :src="upraveno_Logo112" alt="upraveno_logo (1) 1" /><container8 />
          <img
            class="vector-200-6"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200-2.svg"
            alt="Vector 200"
          />
          <div class="component-1-16">
            <div class="button-container-29">
              <component181 :oUbytovn="component181Props.oUbytovn" />
              <component182 :okol="component182Props.okol" />
              <component183 :fotogalerie="component183Props.fotogalerie" />
              <component184 :rezervace="component184Props.rezervace" />
              <component185 :kontakt="component185Props.kontakt" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Component176 from "./Component176";
import Component177 from "./Component177";
import Component178 from "./Component178";
import Component179 from "./Component179";
import Component180 from "./Component180";
import Item7 from "./Item7";
import Item22 from "./Item22";
import Container8 from "./Container8";
import Component181 from "./Component181";
import Component182 from "./Component182";
import Component183 from "./Component183";
import Component184 from "./Component184";
import Component185 from "./Component185";
export default {
  name: "KontaktMc14",
  components: {
    Component176,
    Component177,
    Component178,
    Component179,
    Component180,
    Item7,
    Item22,
    Container8,
    Component181,
    Component182,
    Component183,
    Component184,
    Component185,
  },
  props: [
    "upraveno_Logo111",
    "penzionVSrdciEskKanady",
    "title1",
    "title2",
    "title3",
    "upraveno_Logo112",
    "component176Props",
    "component177Props",
    "component178Props",
    "component179Props",
    "component180Props",
    "item71Props",
    "item72Props",
    "item73Props",
    "item221Props",
    "item222Props",
    "item223Props",
    "item224Props",
    "item225Props",
    "item226Props",
    "component181Props",
    "component182Props",
    "component183Props",
    "component184Props",
    "component185Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.kontakt-mc14
  align-items: flex-start
  background-color: $white
  display: flex
  flex-direction: column
  height: 1991px
  width: 1512px

.section-36
  align-items: center
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.upraveno_logo-1-1-29
  cursor: pointer
  height: 109px
  margin-bottom: -36.50px
  margin-left: -114.00px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-6
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.component-1-15
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -114.00px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 473px

.button-container-28
  align-items: flex-end
  display: flex
  gap: 21px
  height: 44px
  left: 20px
  min-width: 433px
  position: relative
  top: 20px

.vector-200-2
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 156px
  width: 1512px

.list-27
  align-items: center
  display: flex
  flex-direction: column
  gap: 60px
  justify-content: center
  margin-left: 3px
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1509px

.container-38
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 24px
  position: relative
  width: 100%

.title-59
  letter-spacing: 0
  line-height: 48px
  margin-top: -1.00px
  position: relative
  text-align: center
  width: 520px

.list-28
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 40px
  justify-content: center
  position: relative
  width: 100%

.row-15
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.vector-200-3
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 492px
  width: 1509px

.list-29
  align-items: center
  display: flex
  flex-wrap: wrap
  gap: 60px 60px
  height: 614px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.title-60
  letter-spacing: 0
  line-height: 48px
  margin-top: -50.00px
  position: relative
  text-align: center
  width: 1144px

.container-39
  align-items: flex-start
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 24px
  height: 484px
  margin-bottom: -49.00px
  position: relative

.list-30
  align-items: center
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 40px
  height: 326px
  justify-content: center
  position: relative

.row-16
  align-items: flex-start
  align-self: stretch
  display: flex
  flex-direction: column
  gap: 40px
  height: 477px
  margin-bottom: -75.50px
  margin-top: -75.50px
  position: relative
  width: 100%

.vector-200-4
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 614px
  width: 1512px

.section-container
  height: 729px
  position: relative
  width: 1512px

.section-37
  align-items: center
  display: flex
  flex-direction: column
  gap: 60px
  justify-content: center
  left: 0
  overflow: hidden
  padding: 60px 170px
  position: absolute
  top: 0
  width: 1512px

.map-container-3
  align-items: flex-start
  align-self: stretch
  display: flex
  height: 300px
  padding: 4px 0px
  position: relative
  width: 100%

.image-17
  align-self: stretch
  background-color: $black-3
  border-radius: 6px
  flex: 1
  flex-grow: 1
  position: relative

.overlap-group-4
  height: 300px
  left: 16px
  position: relative
  top: -4px
  width: 1140px

.image-18
  height: 300px
  left: 20px
  position: absolute
  top: 0
  width: 1100px

.title-61
  left: 0
  letter-spacing: 0
  line-height: 22px
  position: absolute
  text-align: center
  top: 157px
  width: 1140px

.ic-location-2
  height: 24px
  left: 558px
  position: absolute
  top: 126px
  width: 24px

.vector-200-5
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 420px
  width: 1512px

.section-38
  align-items: center
  display: flex
  gap: 60px
  height: 310px
  justify-content: center
  left: 0
  overflow: hidden
  padding: 60px 170px
  position: absolute
  top: 419px
  width: 1504px

.upraveno_logo-1-1-30
  height: 109px
  object-fit: cover
  position: relative
  width: 153px

.vector-200-6
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 310px
  width: 1504px

.component-1-16
  border-radius: 5px
  height: 308px
  margin-bottom: -59.00px
  margin-top: -59.00px
  overflow: hidden
  position: relative
  width: 260px

.button-container-29
  align-items: flex-start
  display: flex
  flex-direction: column
  left: 20px
  min-height: 220px
  position: relative
  top: 20px
  width: 80px
</style>
