<template>
  <div class="container-center-horizontal">
    <div class="okoli-u40mc14u41 screen">
      <div class="section-51">
        <router-link to="/homepage-3"
          ><img class="upraveno_logo-1-1-38" :src="upraveno_Logo111" alt="upraveno_logo (1) 1"
        /></router-link>
        <p class="penzion-v-srdci-esk-kanady-11 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</p>
        <div class="component-1-24">
          <div class="button-container-37">
            <component1101 :oUbytovn="component1101Props.oUbytovn" />
            <component1102 :okol="component1102Props.okol" />
            <component1103 :fotogalerie="component1103Props.fotogalerie" />
            <component1104 :rezervace="component1104Props.rezervace" />
            <component1105 :kontakt="component1105Props.kontakt" />
          </div>
        </div>
        <img
          class="vector-200-20"
          src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
          alt="Vector 200"
        />
      </div>
      <div class="overlap-group-6">
        <div class="section-52">
          <container22 :title="container22Props.title" :description="container22Props.description" />
          <div class="image-container-41">
            <img class="okoli-10-1-3" :src="okoli101" alt="Okoli 10 1" />
            <div class="image-21"></div>
          </div>
          <img
            class="vector-200-21"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="list-37">
          <div class="container-52">
            <div class="title-78 heading-1">{{ title1 }}</div>
          </div>
          <div class="list-36">
            <div class="row-19">
              <div class="item-13">
                <frame2 />
                <div class="frame-427318906-18">
                  <div class="title-79 roboto-bold-black-20px">{{ title2 }}</div>
                  <div class="subtitle-25 roboto-normal-black-16px-2">{{ subtitle1 }}</div>
                </div>
              </div>
              <div class="item-13">
                <frame3 />
                <frame42731890622 :title="frame427318906221Props.title" :subtitle="frame427318906221Props.subtitle" />
              </div>
              <div class="item-13">
                <frame4 />
                <frame42731890622 :title="frame427318906222Props.title" :subtitle="frame427318906222Props.subtitle" />
              </div>
            </div>
          </div>
          <div class="list-36">
            <div class="row-20">
              <div class="card-12">
                <div class="image-container-40">
                  <div class="image-21">
                    <div class="title-77 valign-text-middle roboto-normal-black-12px">{{ title3 }}</div>
                    <tag2 />
                  </div>
                </div>
                <div class="text-content-12">
                  <div class="subtitle-26 roboto-medium-black-20px">{{ subtitle2 }}</div>
                  <p class="title-80 roboto-normal-black-16px">
                    <span class="roboto-normal-black-16px">{{ spanText1 }}</span
                    ><span class="span1-2 roboto-normal-black-16px">{{ spanText2 }}</span
                    ><span class="roboto-normal-black-16px">{{ spanText3 }}</span>
                  </p>
                </div>
              </div>
              <div class="card-12">
                <div class="image-container-40">
                  <div class="image-21">
                    <div class="title-77 valign-text-middle roboto-normal-black-12px">{{ title4 }}</div>
                    <tag3 />
                  </div>
                </div>
                <text-content4 :subtitle="textContent41Props.subtitle" :title="textContent41Props.title" />
              </div>
              <div class="card-13">
                <div class="image-container-40">
                  <div class="image-21">
                    <div class="title-77 valign-text-middle roboto-normal-black-12px">{{ title5 }}</div>
                    <tag4 />
                  </div>
                </div>
                <text-content4 :subtitle="textContent42Props.subtitle" :title="textContent42Props.title" />
              </div>
            </div>
          </div>
          <img
            class="vector-200-22"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
      </div>
      <div class="section-53">
        <img class="upraveno_logo-1-1-39" :src="upraveno_Logo112" alt="upraveno_logo (1) 1" /><container8 />
        <img class="vector-200-23" :src="vector2004" alt="Vector 200" />
        <div class="component-1-25">
          <div class="button-container-38">
            <component1106 :oUbytovn="component1106Props.oUbytovn" />
            <component1107 :okol="component1107Props.okol" />
            <component1108 :fotogalerie="component1108Props.fotogalerie" />
            <component1109 :rezervace="component1109Props.rezervace" />
            <component1110 :kontakt="component1110Props.kontakt" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Component1101 from "./Component1101";
import Component1102 from "./Component1102";
import Component1103 from "./Component1103";
import Component1104 from "./Component1104";
import Component1105 from "./Component1105";
import Container22 from "./Container22";
import Frame2 from "./Frame2";
import Frame3 from "./Frame3";
import Frame42731890622 from "./Frame42731890622";
import Frame4 from "./Frame4";
import Tag2 from "./Tag2";
import Tag3 from "./Tag3";
import TextContent4 from "./TextContent4";
import Tag4 from "./Tag4";
import Container8 from "./Container8";
import Component1106 from "./Component1106";
import Component1107 from "./Component1107";
import Component1108 from "./Component1108";
import Component1109 from "./Component1109";
import Component1110 from "./Component1110";
export default {
  name: "Okolmc14",
  components: {
    Component1101,
    Component1102,
    Component1103,
    Component1104,
    Component1105,
    Container22,
    Frame2,
    Frame3,
    Frame42731890622,
    Frame4,
    Tag2,
    Tag3,
    TextContent4,
    Tag4,
    Container8,
    Component1106,
    Component1107,
    Component1108,
    Component1109,
    Component1110,
  },
  props: [
    "upraveno_Logo111",
    "penzionVSrdciEskKanady",
    "okoli101",
    "title1",
    "title2",
    "subtitle1",
    "title3",
    "subtitle2",
    "spanText1",
    "spanText2",
    "spanText3",
    "title4",
    "title5",
    "upraveno_Logo112",
    "vector2004",
    "component1101Props",
    "component1102Props",
    "component1103Props",
    "component1104Props",
    "component1105Props",
    "container22Props",
    "frame427318906221Props",
    "frame427318906222Props",
    "textContent41Props",
    "textContent42Props",
    "component1106Props",
    "component1107Props",
    "component1108Props",
    "component1109Props",
    "component1110Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.okoli-u40mc14u41
  align-items: flex-start
  background-color: $white
  display: flex
  flex-direction: column
  height: 1995px
  overflow: hidden
  width: 1512px

.section-51
  align-items: center
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1512px

.upraveno_logo-1-1-38
  cursor: pointer
  height: 109px
  margin-bottom: -36.50px
  margin-left: -114.00px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-11
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.component-1-24
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -114.00px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 473px

.button-container-37
  align-items: flex-end
  display: flex
  gap: 21px
  height: 44px
  left: 20px
  min-width: 433px
  position: relative
  top: 20px

.vector-200-20
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 156px
  width: 1512px

.overlap-group-6
  height: 1528px
  position: relative
  width: 1512px

.section-52
  align-items: center
  display: flex
  gap: 60px
  justify-content: center
  left: 0
  overflow: hidden
  padding: 60px 170px
  position: absolute
  top: 0
  width: 1512px

.image-container-41
  align-items: flex-start
  display: flex
  flex: 1
  flex-grow: 1
  height: 400px
  overflow: hidden
  position: relative

.okoli-10-1-3
  height: 400px
  object-fit: cover
  position: relative
  width: 556px

.image-21
  align-self: stretch
  background-color: $iron
  flex: 1
  flex-grow: 1
  position: relative

.vector-200-21
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 520px
  width: 1512px

.list-37
  align-items: center
  display: flex
  flex-direction: column
  gap: 60px
  justify-content: center
  left: 0
  overflow: hidden
  padding: 60px 170px
  position: absolute
  top: 444px
  width: 1512px

.container-52
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 24px
  position: relative
  width: 100%

.title-78
  color: $black
  font-weight: 400
  line-height: 100px
  margin-top: -1.00px
  position: relative
  text-align: center
  width: 520px

.list-36
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 40px
  justify-content: center
  position: relative
  width: 100%

.row-19,
.row-20
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.item-13
  align-items: center
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 20px
  justify-content: center
  padding: 12px 0px
  position: relative

.frame-427318906-18
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 8px
  position: relative
  width: 100%

.title-79
  align-self: stretch
  letter-spacing: 0
  line-height: 28px
  margin-top: -1.00px
  position: relative
  text-align: center

.subtitle-25
  align-self: stretch
  letter-spacing: 0
  line-height: 24px
  position: relative
  text-align: center

.card-12
  align-items: center
  border: 1px solid
  border-color: $black-2
  border-radius: 6px
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  overflow: hidden
  position: relative

.image-container-40
  align-items: flex-start
  align-self: stretch
  display: flex
  height: 340px
  position: relative
  width: 100%

.title-77
  height: 16px
  left: 16px
  letter-spacing: 0
  line-height: 16px
  position: absolute
  text-align: center
  top: 161px
  white-space: nowrap
  width: 332px

.text-content-12
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 4px
  padding: 12px
  position: relative
  width: 100%

.subtitle-26
  align-self: stretch
  letter-spacing: 0
  line-height: 28px
  margin-top: -1.00px
  position: relative

.title-80
  align-self: stretch
  letter-spacing: 0
  line-height: 24px
  position: relative

.span1-2
  text-decoration: underline

.card-13
  align-items: center
  border: 1px solid
  border-color: $black-2
  border-radius: 6px
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  height: 540px
  overflow: hidden
  position: relative

.vector-200-22
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 1084px
  width: 1512px

.section-53
  align-items: center
  display: flex
  gap: 60px
  height: 313px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1504px

.upraveno_logo-1-1-39
  height: 109px
  object-fit: cover
  position: relative
  width: 153px

.vector-200-23
  height: 1px
  left: -3498px
  object-fit: cover
  position: absolute
  top: 241px
  width: 1504px

.component-1-25
  border-radius: 5px
  height: 308px
  margin-bottom: -57.50px
  margin-top: -57.50px
  overflow: hidden
  position: relative
  width: 260px

.button-container-38
  align-items: flex-start
  display: flex
  flex-direction: column
  left: 20px
  min-height: 220px
  position: relative
  top: 20px
  width: 80px
</style>
