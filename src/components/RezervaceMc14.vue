<template>
  <div class="container-center-horizontal">
    <form class="rezervace-mc14 screen" name="form7" action="form7" method="post">
      <div class="section-39">
        <router-link to="/homepage-3"
          ><img class="upraveno_logo-1-1-31" :src="upraveno_Logo11" alt="upraveno_logo (1) 1"
        /></router-link>
        <h1 class="penzion-v-srdci-esk-kanady-7 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</h1>
        <div class="component-1-17">
          <div class="button-container-30">
            <component186 :oUbytovn="component186Props.oUbytovn" />
            <component187 :okol="component187Props.okol" />
            <component188 :fotogalerie="component188Props.fotogalerie" />
            <component189 :rezervace="component189Props.rezervace" />
            <component190 :kontakt="component190Props.kontakt" />
          </div>
        </div>
        <img
          class="vector-200-7"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
          alt="Vector 200"
        />
      </div>
      <div class="section-40">
        <input-date-picker5 />
        <input-date-picker4 :textFieldProps="inputDatePicker4Props.textFieldProps" />
        <div class="image-container-33">
          <text-field22 />
          <text-field13 :activeIndicator="textField13Props.activeIndicator" />
          <text-field14 :activeIndicator="textField14Props.activeIndicator" />
          <text-field15 :activeIndicator="textField15Props.activeIndicator" />
          <text-field16
            :activeIndicator="textField16Props.activeIndicator"
            :iconButton22Props="textField16Props.iconButton22Props"
            :supportingText3Props="textField16Props.supportingText3Props"
          />
          <text-field17 :activeIndicator="textField17Props.activeIndicator" />
          <text-field18 :activeIndicator="textField18Props.activeIndicator" />
          <text-field19 :activeIndicator="textField19Props.activeIndicator" />
          <text-field11
            :activeIndicator="textField11Props.activeIndicator"
            :className="textField11Props.className"
            :inputTextContainer9Props="textField11Props.inputTextContainer9Props"
            :iconButton22Props="textField11Props.iconButton22Props"
          />
        </div>
        <img
          class="vector-200-8"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
          alt="Vector 200"
        />
        <component1-variant6
          :potvrditRezervaci="component1Variant6Props.potvrditRezervaci"
          :className="component1Variant6Props.className"
        />
      </div>
    </form>
  </div>
</template>

<script>
import Component186 from "./Component186";
import Component187 from "./Component187";
import Component188 from "./Component188";
import Component189 from "./Component189";
import Component190 from "./Component190";
import InputDatePicker5 from "./InputDatePicker5";
import InputDatePicker4 from "./InputDatePicker4";
import TextField22 from "./TextField22";
import TextField13 from "./TextField13";
import TextField14 from "./TextField14";
import TextField15 from "./TextField15";
import TextField16 from "./TextField16";
import TextField17 from "./TextField17";
import TextField18 from "./TextField18";
import TextField19 from "./TextField19";
import TextField11 from "./TextField11";
import Component1Variant6 from "./Component1Variant6";
export default {
  name: "RezervaceMc14",
  components: {
    Component186,
    Component187,
    Component188,
    Component189,
    Component190,
    InputDatePicker5,
    InputDatePicker4,
    TextField22,
    TextField13,
    TextField14,
    TextField15,
    TextField16,
    TextField17,
    TextField18,
    TextField19,
    TextField11,
    Component1Variant6,
  },
  props: [
    "upraveno_Logo11",
    "penzionVSrdciEskKanady",
    "component186Props",
    "component187Props",
    "component188Props",
    "component189Props",
    "component190Props",
    "inputDatePicker4Props",
    "textField13Props",
    "textField14Props",
    "textField15Props",
    "textField16Props",
    "textField17Props",
    "textField18Props",
    "textField19Props",
    "textField11Props",
    "component1Variant6Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.rezervace-mc14
  align-items: flex-start
  background-color: $white
  display: flex
  flex-direction: column
  gap: 2px
  height: 1450px
  width: 1512px

.section-39
  align-items: center
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.upraveno_logo-1-1-31
  cursor: pointer
  height: 109px
  margin-bottom: -36.50px
  margin-left: -114.00px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-7
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.component-1-17
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -114.00px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 473px

.button-container-30
  align-items: flex-end
  display: flex
  gap: 21px
  height: 44px
  left: 20px
  min-width: 433px
  position: relative
  top: 20px

.vector-200-7
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 156px
  width: 1512px

.section-40
  align-items: flex-start
  display: flex
  flex-wrap: wrap
  gap: 8px 85px
  height: 1292px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.image-container-33
  align-items: flex-start
  display: flex
  flex-wrap: wrap
  gap: 53px 120px
  height: 937px
  justify-content: center
  padding: 30px 0px
  position: relative
  width: 1038px

.vector-200-8
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 1292px
  width: 1512px
</style>
