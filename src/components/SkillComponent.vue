<template>
  <div class="dizme_tm_section" id="hobbies">
    <div class="dizme_tm_skills">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div
              class="dizme_tm_main_title wow fadeInUp"
              data-wow-duration="1s"
              data-align="left"
            >
              <span>Hobbies</span>
              <h3>Embracing personal time</h3>
              <p>
                Outside of work, I find great joy in pursuing creative hobbies like calligraphy and sketching. Calligraphy allows me to explore the beauty of typography and the art of lettering. Sketching, on the other hand, provides me with a sense of freedom to capture ideas, emotions, and scenes from daily life or imagination on paper.
              </p>
            </div>
          </div>
          <div class="right">
            <img :src="`/img/hobby/hobby-final.png`" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SkillComponent",
  components: {},
  props: {
    dark: { type: Boolean },
  },
};
</script>
