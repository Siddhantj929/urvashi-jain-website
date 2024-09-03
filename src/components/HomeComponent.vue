<template>
  <div class="dizme_tm_section" id="home">
    <div class="dizme_tm_hero">
      <div
        class="background"
        :data-img-url="`/img/slider/${dark ? 2 : 1}.jpg`"
      ></div>
      <div class="container">
        <div class="content">
          <div class="details">
            <!-- <div class="hello">
              <h3 class="orangeText">Hello, I'm Urvashi Jain</h3>
            </div> -->
            <div class="name">
              <h3>Hi, I'm Urvashi Jain</h3>
            </div>
            <div class="job">
              <p>
                A <span class="greenText">Creative Designer</span> From
                <span class="purpleText">New Delhi</span>
              </p>
            </div>
            <div class="text">
              <p>
                I'm a self-taught UX designer with an engineering background, blending technical skills with a keen eye for design.
              </p>
            </div>
            <div class="button">
              <div class="dizme_tm_button">
                <a class="anchor" href="#about"><span>About Me</span></a>
              </div>
              <div class="social">
                <ul>
                  <li>
                    <a href="#"><i class="icon-facebook-1"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="icon-twitter-1"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="icon-linkedin-1"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="icon-behance"></i></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="avatar">
            <div class="image">
              <img src="/img/slider/avatar.png" alt="" />
              <span
                class="skills illustrator anim_moveBottom"
                v-html="ai"
              ></span>
              <span class="skills photoshop anim_moveBottom" v-html="ps"></span>
              <span class="skills figma anim_moveBottom" v-html="figma"></span>
            </div>
          </div>
        </div>
      </div>
      <div class="dizme_tm_down">
        <a class="anchor" href="#process" v-html="dark ? mouseDark : mouse">
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { ai, figma, mouse, mouseDark, ps } from "../svg";
export default {
  name: "HomeComponent",
  data() {
    return { ai, ps, figma, mouse, mouseDark };
  },
  props: {
    dark: { type: Boolean },
  },
};
</script>
