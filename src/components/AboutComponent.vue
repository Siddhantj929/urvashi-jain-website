<template>
  <div class="dizme_tm_section" id="mentorship">
    <div class="dizme_tm_about">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div class="image">
              <img :src="`/img/skills/skills.png`" alt="" />
              <div class="numbers year">
                <div class="wrapper">
                  <h3>
                    <VueJsCounter end="40"></VueJsCounter>
                  </h3>
                  <span class="name">Aspiring <br />Designers</span>
                </div>
              </div>
              <div class="numbers project">
                <div class="wrapper">
                  <h3 style="display: flex">
                    <VueJsCounter as="span" end="3"></VueJsCounter>
                  </h3>
                  <span class="name">Total<br />Workshops</span>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <div class="title wow fadeInUp" data-wow-duration="1s">
              <span>Mentorship</span>
              <h3>Live & online workshops</h3>
            </div>
            <div class="text wow fadeInUp" data-wow-duration="1s">
              <p>
                I have had the opportunity to lead several workshops, each designed to empower and inspire aspiring designers. Through these workshops, I have positively impacted the lives and careers of over 40 budding designers, guiding them through key design principles, best practices, and industry insights.
              </p>
            </div>
            <!-- <div class="dizme_tm_button wow fadeInUp" data-wow-duration="1s">
              <a class="anchor" href="#contact"><span>Hire Me</span></a>
            </div> -->
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/img/brushes/about/1.png" alt="" />
      </div>
      <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/about/2.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
import VueJsCounter from "vue-js-counter";
export default {
  name: "AboutComponent",
  components: { VueJsCounter },
  props: {
    dark: { type: Boolean },
  },
};
</script>
