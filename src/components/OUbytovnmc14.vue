<template>
  <div class="container-center-horizontal">
    <form class="o-ubytovani-u40mc14u41 screen" name="form8" action="form8" method="post">
      <div class="page-5">
        <div class="section-49">
          <router-link to="/homepage-3"
            ><img class="upraveno_logo-1-1-36" :src="upraveno_Logo111" alt="upraveno_logo (1) 1"
          /></router-link>
          <p class="penzion-v-srdci-esk-kanady-10 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</p>
          <div class="component-1-22">
            <div class="button-container-35">
              <navigace46 />
              <navigace47 />
              <navigace48 />
              <navigace49 />
              <navigace50 />
            </div>
          </div>
          <img
            class="vector-200-15"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="page-item-2">
          <container22 :title="container22Props.title" :description="container22Props.description" />
          <div class="image-container-35"><img class="image-1-7" :src="image1" alt="image 1" /></div>
          <img
            class="vector-200-16"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="page-item-2">
          <div class="image-container-36">
            <image-container :src="imageContainerProps.src" :className="imageContainerProps.className" />
          </div>
          <div class="container-46">
            <div class="container-47">
              <div class="title-71 heading-2">{{ title1 }}</div>
            </div>
            <div class="list-34">
              <div class="row-17">
                <div class="card-11">
                  <div class="image-container-37">
                    <div class="image-19">
                      <div class="overlap-group-5">
                        <div class="title-72 valign-text-middle roboto-normal-black-12px">{{ title2 }}</div>
                        <tag :className="tagProps.className" />
                        <img class="s-obrazem-1-3" :src="sObrazem1" alt="S obrazem 1" />
                      </div>
                    </div>
                  </div>
                  <div class="text-content-11">
                    <component1-variant6
                      :potvrditRezervaci="component1Variant6Props.potvrditRezervaci"
                      :className="component1Variant6Props.className"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
          <img
            class="vector-200-17"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="contents-9">
          <div class="container-48">
            <div class="container-49">
              <div class="title-73 heading-1">{{ title3 }}</div>
              <p class="description-28 subtext">{{ description }}</p>
            </div>
            <div class="image-container-38">
              <div class="image-19"></div>
            </div>
          </div>
          <div class="list-35">
            <div class="row-18">
              <div class="article-7">
                <image-container4 :frameProps="imageContainer4Props.frameProps" />
                <frame4273189068 :title="frame4273189068Props.title" :subtitle="frame4273189068Props.subtitle" />
              </div>
              <x-article3 :frame427318906Props="xArticle31Props.frame427318906Props" />
              <x-article3 :frame427318906Props="xArticle32Props.frame427318906Props" />
            </div>
          </div>
          <img
            class="vector-200-18"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200.svg"
            alt="Vector 200"
          />
        </div>
        <div class="section-50">
          <img class="upraveno_logo-1-1-37" :src="upraveno_Logo112" alt="upraveno_logo (1) 1" /><container8 />
          <img
            class="vector-200-19"
            src="https://cdn.animaapp.com/projects/673b2aed8a1b7d25aab8cf0f/releases/673b2d66ac84e614e11f02a0/img/vector-200-2.svg"
            alt="Vector 200"
          />
          <div class="component-1-23">
            <div class="button-container-36">
              <component156 />
              <component157 />
              <component158 />
              <component159 />
              <component160 />
            </div>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
import Navigace46 from "./Navigace46";
import Navigace47 from "./Navigace47";
import Navigace48 from "./Navigace48";
import Navigace49 from "./Navigace49";
import Navigace50 from "./Navigace50";
import Container22 from "./Container22";
import ImageContainer from "./ImageContainer";
import Tag from "./Tag";
import Component1Variant6 from "./Component1Variant6";
import ImageContainer4 from "./ImageContainer4";
import Frame4273189068 from "./Frame4273189068";
import XArticle3 from "./XArticle3";
import Container8 from "./Container8";
import Component156 from "./Component156";
import Component157 from "./Component157";
import Component158 from "./Component158";
import Component159 from "./Component159";
import Component160 from "./Component160";
export default {
  name: "OUbytovnmc14",
  components: {
    Navigace46,
    Navigace47,
    Navigace48,
    Navigace49,
    Navigace50,
    Container22,
    ImageContainer,
    Tag,
    Component1Variant6,
    ImageContainer4,
    Frame4273189068,
    XArticle3,
    Container8,
    Component156,
    Component157,
    Component158,
    Component159,
    Component160,
  },
  props: [
    "upraveno_Logo111",
    "penzionVSrdciEskKanady",
    "image1",
    "title1",
    "title2",
    "sObrazem1",
    "title3",
    "description",
    "upraveno_Logo112",
    "container22Props",
    "imageContainerProps",
    "tagProps",
    "component1Variant6Props",
    "imageContainer4Props",
    "frame4273189068Props",
    "xArticle31Props",
    "xArticle32Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.o-ubytovani-u40mc14u41
  align-items: flex-start
  background-color: $white
  display: flex
  height: 2142px
  width: 1512px

.page-5
  align-items: flex-end
  background-color: $white
  display: flex
  flex-direction: column
  height: 2140px
  position: relative
  width: 1512px

.section-49
  align-items: center
  align-self: stretch
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 100%

.upraveno_logo-1-1-36
  cursor: pointer
  height: 109px
  margin-bottom: -36.50px
  margin-left: -114.00px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-10
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.component-1-22
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -114.00px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 473px

.button-container-35
  align-items: flex-end
  display: flex
  gap: 21px
  height: 44px
  left: 20px
  min-width: 433px
  position: relative
  top: 20px

.vector-200-15
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 156px
  width: 1512px

.page-item-2
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 60px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 100%

.image-container-35
  align-items: flex-start
  display: flex
  flex: 1
  flex-grow: 1
  height: 380px
  overflow: hidden
  padding: 30px 0px
  position: relative

.image-1-7
  height: 390px
  margin-bottom: -70.00px
  object-fit: cover
  position: relative
  width: 556px

.vector-200-16
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 500px
  width: 1512px

.image-container-36
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 1
  flex-grow: 1
  position: relative

.container-46
  align-items: center
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 44px
  justify-content: center
  position: relative

.container-47
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 24px
  position: relative
  width: 100%

.title-71
  align-self: stretch
  color: $black
  font-weight: 400
  line-height: 44px
  margin-top: -1.00px
  position: relative
  text-align: center

.list-34
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 40px
  justify-content: center
  position: relative
  width: 100%

.row-17
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.card-11
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

.image-container-37
  align-items: flex-start
  align-self: stretch
  display: flex
  height: 240px
  position: relative
  width: 100%

.image-19
  align-self: stretch
  background-color: $iron
  flex: 1
  flex-grow: 1
  position: relative

.overlap-group-5
  height: 240px
  position: relative
  width: 556px

.title-72
  height: 16px
  left: 16px
  letter-spacing: 0
  line-height: 16px
  position: absolute
  text-align: center
  top: 111px
  white-space: nowrap
  width: 524px

.s-obrazem-1-3
  height: 240px
  left: 0
  object-fit: cover
  position: absolute
  top: 0
  width: 556px

.text-content-11
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 4px
  justify-content: center
  padding: 18px 12px 12px
  position: relative
  width: 100%

.vector-200-17
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 518px
  width: 1512px

.contents-9
  align-items: center
  align-self: stretch
  display: flex
  flex-direction: column
  gap: 60px
  height: 655px
  justify-content: center
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 100%

.container-48
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 60px
  justify-content: center
  position: relative
  width: 100%

.container-49
  align-items: flex-start
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 24px
  position: relative

.title-73
  align-self: stretch
  color: $black
  font-weight: 400
  line-height: 100px
  margin-top: -1.00px
  position: relative

.description-28
  align-self: stretch
  color: $gray
  font-weight: 600
  line-height: 44px
  position: relative

.image-container-38
  align-items: flex-start
  display: flex
  height: 180px
  position: relative
  width: 180px

.list-35
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 40px
  justify-content: center
  padding: 20px 0px
  position: relative
  width: 100%

.row-18
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.article-7
  align-items: flex-start
  border: 1px solid
  border-color: $black-2
  border-radius: 6px
  display: flex
  flex: 1
  flex-grow: 1
  gap: 16px
  justify-content: center
  padding: 16px
  position: relative

.vector-200-18
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 654px
  width: 1512px

.section-50
  align-items: center
  display: flex
  gap: 60px
  height: 313px
  justify-content: center
  margin-bottom: -2.00px
  overflow: hidden
  padding: 60px 170px
  position: relative
  width: 1504px

.upraveno_logo-1-1-37
  height: 109px
  object-fit: cover
  position: relative
  width: 153px

.vector-200-19
  height: 1px
  left: 0
  object-fit: cover
  position: absolute
  top: 312px
  width: 1504px

.component-1-23
  border-radius: 5px
  height: 308px
  margin-bottom: -57.50px
  margin-top: -57.50px
  overflow: hidden
  position: relative
  width: 260px

.button-container-36
  align-items: flex-start
  display: flex
  flex-direction: column
  left: 20px
  min-height: 220px
  position: relative
  top: 20px
  width: 80px
</style>
