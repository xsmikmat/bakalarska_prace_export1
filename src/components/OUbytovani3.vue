<template>
  <div class="container-center-horizontal">
    <form class="o-ubytovani-3 screen" name="form6" action="form6" method="post">
      <div class="page-3">
        <div class="heeader-1">
          <router-link to="/homepage-3"
            ><img class="upraveno_logo-1-1-22" :src="upraveno_Logo111" alt="upraveno_logo (1) 1"
          /></router-link>
          <p class="penzion-v-srdci-esk-kanady-4 valign-text-middle heading-2">{{ penzionVSrdciEskKanady }}</p>
          <div class="navigace-9">
            <div class="button-container-21">
              <navigace46 />
              <navigace47 />
              <navigace48 />
              <navigace49 />
              <navigace50 />
            </div>
          </div>
        </div>
        <div class="page-item-1">
          <container4 :title="container4Props.title" :description="container4Props.description" />
          <image-container5 :src="imageContainer51Props.src" />
        </div>
        <div class="page-item-1">
          <image-container5 :src="imageContainer52Props.src" :className="imageContainer52Props.className" />
          <div class="container-28">
            <div class="container-29">
              <div class="title-37 heading-2">{{ title1 }}</div>
            </div>
            <div class="list-17">
              <div class="row-8">
                <div class="card-5">
                  <image-container5 :src="imageContainer53Props.src" :className="imageContainer53Props.className" />
                  <div class="text-content-5">
                    <component1-variant6
                      :potvrditRezervaci="component1Variant6Props.potvrditRezervaci"
                      :className="component1Variant6Props.className"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="contents-6">
          <div class="container-30">
            <div class="container-31">
              <div class="title-38 heading-1">{{ title2 }}</div>
              <p class="description-17 subtext">{{ description }}</p>
            </div>
            <image-container62 />
          </div>
          <div class="list-18">
            <div class="row-9">
              <div class="article-4">
                <image-container4 :frameProps="imageContainer4Props.frameProps" />
                <frame4273189062 :title="frame4273189062Props.title" :subtitle="frame4273189062Props.subtitle" />
              </div>
              <x-article2
                :frameProps="xArticle21Props.frameProps"
                :frame4273189062Props="xArticle21Props.frame4273189062Props"
              />
              <x-article2
                :frameProps="xArticle22Props.frameProps"
                :frame4273189062Props="xArticle22Props.frame4273189062Props"
              />
            </div>
          </div>
        </div>
        <footer class="footer-10">
          <img class="upraveno_logo-1-1-23" :src="upraveno_Logo112" alt="upraveno_logo (1) 1" /><container />
          <div class="component-1-11">
            <div class="button-container-22">
              <component156 />
              <component157 />
              <component158 />
              <component159 />
              <component160 />
            </div>
          </div>
        </footer>
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
import Container4 from "./Container4";
import ImageContainer5 from "./ImageContainer5";
import Component1Variant6 from "./Component1Variant6";
import ImageContainer62 from "./ImageContainer62";
import ImageContainer4 from "./ImageContainer4";
import Frame4273189062 from "./Frame4273189062";
import XArticle2 from "./XArticle2";
import Container from "./Container";
import Component156 from "./Component156";
import Component157 from "./Component157";
import Component158 from "./Component158";
import Component159 from "./Component159";
import Component160 from "./Component160";
export default {
  name: "OUbytovani3",
  components: {
    Navigace46,
    Navigace47,
    Navigace48,
    Navigace49,
    Navigace50,
    Container4,
    ImageContainer5,
    Component1Variant6,
    ImageContainer62,
    ImageContainer4,
    Frame4273189062,
    XArticle2,
    Container,
    Component156,
    Component157,
    Component158,
    Component159,
    Component160,
  },
  props: [
    "upraveno_Logo111",
    "penzionVSrdciEskKanady",
    "title1",
    "title2",
    "description",
    "upraveno_Logo112",
    "container4Props",
    "imageContainer51Props",
    "imageContainer52Props",
    "imageContainer53Props",
    "component1Variant6Props",
    "imageContainer4Props",
    "frame4273189062Props",
    "xArticle21Props",
    "xArticle22Props",
  ],
};
</script>

<style lang="sass">
@import '../../variables'

.o-ubytovani-3
  align-items: flex-start
  background-color: $white
  display: flex
  height: 1737px
  overflow: hidden
  width: 1512px

.page-3
  align-items: flex-end
  background-color: $white
  display: flex
  flex-direction: column
  position: relative
  width: 1512px

.heeader-1
  align-items: center
  align-self: stretch
  display: flex
  gap: 160px
  height: 156px
  justify-content: center
  padding: 60px 80px
  position: relative
  width: 100%

.upraveno_logo-1-1-22
  cursor: pointer
  height: 109px
  margin-bottom: -36.50px
  margin-left: -24.00px
  margin-top: -36.50px
  object-fit: cover
  position: relative
  width: 153px

.penzion-v-srdci-esk-kanady-4
  color: $black
  font-weight: 400
  height: 91px
  line-height: 44px
  margin-bottom: -26.50px
  margin-top: -28.50px
  position: relative
  text-align: center
  width: 454px

.navigace-9
  border-radius: 5px
  height: 84px
  margin-bottom: -24.00px
  margin-right: -24.00px
  margin-top: -24.00px
  overflow: hidden
  position: relative
  width: 473px

.button-container-21
  align-items: flex-end
  display: flex
  gap: 21px
  height: 44px
  left: 20px
  min-width: 433px
  position: relative
  top: 20px

.page-item-1
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 20px
  justify-content: center
  padding: 20px 80px
  position: relative
  width: 100%

.container-28
  align-items: center
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 44px
  justify-content: center
  position: relative

.container-29
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 24px
  position: relative
  width: 100%

.title-37
  align-self: stretch
  color: $black
  font-weight: 400
  line-height: 44px
  margin-top: -1.00px
  position: relative
  text-align: center

.list-17
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 40px
  justify-content: center
  position: relative
  width: 100%

.row-8
  align-items: flex-start
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.card-5
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

.text-content-5
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

.contents-6
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  flex-direction: column
  gap: 20px
  justify-content: center
  padding: 20px 80px
  position: relative
  width: 100%

.container-30
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 60px
  justify-content: center
  position: relative
  width: 100%

.container-31
  align-items: flex-start
  display: flex
  flex: 1
  flex-direction: column
  flex-grow: 1
  gap: 24px
  position: relative

.title-38
  align-self: stretch
  color: $black
  font-weight: 400
  line-height: 100px
  margin-top: -1.00px
  position: relative

.description-17
  align-self: stretch
  color: $gray
  font-weight: 600
  line-height: 44px
  position: relative

.list-18
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

.row-9
  align-items: center
  align-self: stretch
  display: flex
  flex: 0 0 auto
  gap: 40px
  position: relative
  width: 100%

.article-4
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

.footer-10
  align-items: center
  background-color: transparent
  display: flex
  gap: 60px
  height: 313px
  justify-content: center
  padding: 60px 170px
  position: relative
  width: 1504px

.upraveno_logo-1-1-23
  height: 109px
  object-fit: cover
  position: relative
  width: 153px

.component-1-11
  border-radius: 5px
  height: 308px
  margin-bottom: -57.50px
  margin-top: -57.50px
  overflow: hidden
  position: relative
  width: 260px

.button-container-22
  align-items: flex-start
  display: flex
  flex-direction: column
  left: 20px
  min-height: 220px
  position: relative
  top: 20px
  width: 80px
</style>
