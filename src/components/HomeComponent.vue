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
                A <span class="greenText">UX Designer</span> From
                <span class="purpleText">New Delhi</span>
              </p>
            </div>
            <div class="text">
              <p>
                I'm a dynamic product designer who has worked upon various B2C, B2B products & Design System.
              </p>
            </div>
            <div class="button">
              <div class="dizme_tm_button">
                <a href="https://drive.google.com/file/d/1XfOdzXb9w9SAHwJ6ct34Hs83ZLCO942b/view?usp=sharing" target="_blank"><span>Download CV</span></a>
              </div>
              <div class="social">
                <ul>
                  <li>
                    <a href="https://www.instagram.com/my_designwand/" target="_blank"><i class="icon-instagram-3"></i></a>
                  </li>
                  <li>
                    <a href="https://www.linkedin.com/in/urvashi-jain-8a448b145/" target="_blank"><i class="icon-linkedin-1"></i></a>
                  </li>
                  <li>
                    <a href="https://www.behance.net/urvashijaif9aa" target="_blank"><i class="icon-behance"></i></a>
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
              <span class="skills photoshop anim_moveBottom" v-html="notion"></span>
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
import { ai, figma, mouse, mouseDark, notion } from "../svg";
export default {
  name: "HomeComponent",
  data() {
    return { ai, notion, figma, mouse, mouseDark };
  },
  props: {
    dark: { type: Boolean },
  },
};
</script>
