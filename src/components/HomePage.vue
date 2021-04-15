<template>
  <div>
    <div
      v-if="image"
      id="background"
      :style="{ 'background-image': 'url(' + image + ')' }"
    >
      <b-nav>
        <b-nav-item id="menu1">Menu Item</b-nav-item>
        <b-nav-item id="menu2"> Menu Item</b-nav-item>
        <b-nav-item id="menu3">Menu Item </b-nav-item>
        <b-nav-item id="menu4"> LOGO</b-nav-item>
        <b-nav-item id="menu5">Login</b-nav-item>
        <b-nav-item id="menu6">Register</b-nav-item>
      </b-nav>
      <div>
        <div class="mb-0"><b-icon icon="facebook" id="facebook"></b-icon></div>
        <div class="mb-0">
          <b-icon icon="instagram" id="instagram"></b-icon>
        </div>
        <div class="mb-0">
          <b-icon icon="youtube" id="youtube"></b-icon>
        </div>
        <div class="mb-0">
          <b-icon icon="power" id="power"></b-icon>
        </div>
        <p id="p1">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        </p>
        <p
          style="
            position: absolute;
            width: 376px;
            height: 30px;
            left: 142px;
            top: 584px;

            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            font-size: 30px;
            line-height: 100%;
            /* identical to box height, or 30px */

            letter-spacing: 0.01em;

            color: #ffffff;
          "
        >
          Lorem ipsum dolor sit amet,
        </p>

        <div class="s131">
          <form>
            <div
              class="row"
              style="
                position: absolute;
                width: 922px;
                height: 108px;
                left: 142px;
                top: 707px;

                background: #f6f5ff;
                border-radius: 0px 22px 22px 22px;
              "
            >
              <b-col cols="8">
                <p
                  style="
                    position: absolute;
                    width: 84px;
                    height: 14px;
                    left: 100px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 120%;
                    /* or 14px */

                    letter-spacing: 0.04em;
                    text-transform: uppercase;

                    color: #938bd5;
                  "
                >
                  Lorem Ipsum
                </p>

                <div class="mb-0">
                  <b-icon icon="search" id="search"></b-icon>
                </div>
                <div class="mb-0" id="searchBox">Search here ...</div>
              </b-col>
              <b-col style="background: #d9d6f1">
                <p
                  style="
                    position: absolute;
                    width: 84px;
                    height: 14px;
                    left: 20px;
                    font-family: Roboto;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 12px;
                    line-height: 120%;
                    /* or 14px */

                    letter-spacing: 0.04em;
                    text-transform: uppercase;

                    color: #938bd5;
                  "
                >
                  Lorem Ipsum
                </p>

                <div class="mb-0" id="category">Category</div>
                <div class="mb-0">
                  <b-icon
                    icon="chevron-compact-down"
                    id="categoryIcon"
                  ></b-icon>
                </div>
              </b-col>
              <b-col
                style="background: #fc6868; border-radius: 0px 22px 22px 0px"
              >
                <p id="redSearch">Search</p>
              </b-col>
            </div>
          </form>
        </div>
      </div>
      <div>
        <p
          style="
            position: absolute;
            width: 161px;
            height: 17px;
            left: 639px;
            top: 1021px;
            font-family: Roboto;
            font-style: normal;
            font-weight: normal;
            font-size: 14px;
            line-height: 120%;
            text-transform: uppercase;
            color: #938bd5;
          "
        >
          Lorem ipsum dolor
        </p>
        <p id="p2">Lorem ipsum dolor sit amet</p>
        <div style="background: #ffffff">
          <b-row
            style="margin-top: 1173px; margin-left: 139px; margin-right: 239px"
          >
            <b-card-group deck style="height: 264px">
              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>
            </b-card-group>
          </b-row>
          <b-row
            style="margin-left: 139px; margin-top: 25px; margin-right: 239px"
          >
            <b-card-group deck style="height: 264px">
              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>

              <b-card
                no-body
                style="max-width: 20rem"
                :img-src="card"
                img-alt="Image"
                img-top
              >
                <b-row style="margin-top: 1px">
                  <b-col style="height: 2px"><p>Name Here</p></b-col>
                  <b-col>
                    <b-icon icon="heart" style="color: #e381f3"></b-icon
                  ></b-col>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <div class="mb-0">
                    <b-icon
                      icon="geo-alt"
                      style="color: #9892c0; vertical-align: 2px"
                    ></b-icon>
                  </div>
                  <div class="mb-0" id="location" style="">Location</div>
                </b-row>
                <b-row style="margin-left: 5px; margin-top: 0px">
                  <b-button pill id="tag1">tag1</b-button>
                  <b-button pill id="tag">tag</b-button>
                  <b-button pill id="tag2">tag1</b-button>
                </b-row>
                <b-row style="margin-left: 5px">
                  <div class="mb-0" id="buttonLink">Buton Link</div>
                  <div class="mb-0" id="buttonIcon">
                    <b-icon
                      icon="chevron-compact-right"
                      style="color: #39317c; vertical-align: 2px"
                    ></b-icon>
                  </div>
                </b-row>
              </b-card>
            </b-card-group>
          </b-row>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vuetify from "vuetify";
export default {
  vuetify: new Vuetify(),
  data() {
    return {
      image: require("../assets/background.jpg"),
      card: require("../assets/cards.jpg"),
    };
  },
};
</script>
<style scoped>
#menu1 {
  position: absolute;

  height: 16px;
  left: 141px;
  top: 38px;

  font-family: Roboto Condensed;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 120%;
  letter-spacing: 0.02em;
  text-transform: uppercase;
}
#menu2 {
  position: absolute;
  height: 16px;
  left: 256px;
  top: 38px;
  font-family: Roboto Condensed;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 120%;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  color: #ffffff;
}
#menu3 {
  position: absolute;

  height: 16px;
  left: 371px;
  top: 38px;

  font-family: Roboto Condensed;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 120%;
  /* identical to box height, or 16px */

  letter-spacing: 0.02em;
  text-transform: uppercase;
  color: #ffffff;
}
#menu4 {
  position: absolute;
  width: 97px;
  height: 37px;
  left: 671px;
  top: 33px;

  font-family: HelveticaNeueCyr;
  font-size: 31px;
  line-height: 120%;
  /* or 37px */

  letter-spacing: 0.07em;
  color: #ffffff;
}
#menu5 {
  position: absolute;
  width: 34px;
  height: 16px;
  left: 1050px;
  top: 36px;
  font-family: Roboto Condensed;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 120%;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  color: #ffffff;
}
#menu6 {
  position: absolute;
  width: 122px;
  height: 40px;
  left: 1121px;
  top: 23px;
  border: 2px solid #fc6868;
  box-sizing: border-box;
  border-radius: 100px;
  color: #ffffff;
}
a {
  color: #ffffff;
}
#tag1 {
  width: 69.71px;
  height: 28.75px;
  left: 156.43px;
  top: 1457.05px;
  background: #b1bdfa;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 13.9413px;
  line-height: 100%;
  color: #2243f1;
}
#tag {
  width: 43.57px;
  height: 28.75px;
  left: 240.07px;
  top: 1457.05px;
  background: #b1e4fa;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 100%;
  color: #0d94cf;
  margin-left: 3px;
}
#tag2 {
  width: 56.64px;
  height: 28.75px;
  left: 297.58px;
  top: 1457.05px;
  background: #b2fae5;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 13.9413px;
  line-height: 100%;
  color: #099068;
  margin-left: 3px;
}
#location {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 13.9413px;
  line-height: 100%;
  color: #9892c0;
}
#p1 {
  position: absolute;
  width: 986px;
  height: 128px;
  left: 142px;
  top: 421px;

  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 100%;
  color: #ffffff;
  background: transparent;
}
#p2 {
  position: absolute;
  width: 445px;
  height: 36px;
  left: 497px;
  top: 1065px;

  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 100%;
  /* identical to box height, or 36px */

  color: #1a1636;
}
#background {
  width: 1400px;
  height: 901px;
  background: linear-gradient(
    0deg,
    #5145b5 0%,
    #292357 0.01%,
    rgba(81, 69, 181, 0.16) 79.02%
  );
}
#buttonLink {
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 15.684px;
  line-height: 100%;
  letter-spacing: 0.01em;

  color: #39317c;
}
#facebook {
  position: absolute;
  width: 29.59px;
  height: 29.59px;
  left: calc(50% - 29.59px / 2 + 565.2px);
  top: 305px;
  background: #b6b0e3;
}
#instagram {
  position: absolute;
  width: 29.59px;
  height: 29.59px;
  left: calc(50% - 29.59px / 2 + 565.2px);
  top: 375px;
  background: #b6b0e3;
}
#youtube {
  position: absolute;
  width: 29.59px;
  height: 29.59px;
  left: calc(50% - 29.59px / 2 + 565.2px);
  top: 445px;
  background: #b6b0e3;
}
#power {
  position: absolute;
  width: 29.59px;
  height: 40px;
  left: calc(50% - 29.59px / 2 + 565.2px);
  top: 745px;
  background: #b6b0e3;
}
#search {
  position: absolute;
  width: 24px;
  height: 24px;
  top: 50px;
  left: 70px;
  background: transparent;
}
#searchBox {
  position: absolute;
  width: 124px;
  height: 20px;
  left: 95px;
  top: 55px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 0.01em;
  color: #292357;
}
#category {
  position: absolute;
  height: 20px;
  left: 23px;
  top: 55px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 0.01em;
  color: #292357;
}
#categoryIcon {
  position: absolute;
  width: 20px;
  height: 15px;
  top: 60px;
  left: 110px;
}
#redSearch {
  position: absolute;
  width: 62px;
  height: 20px;
  left: 45px;
  top: 45px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 100%;
  color: #ffffff;
}
</style>