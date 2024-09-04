<template>
  <div class="dizme_tm_header">
    <div class="container">
      <div class="inner">
        <div class="logo">
          <a href="/"
            ><img :src="`img/logo/logo.svg`" alt="Urvashi Jain"
          /></a>
        </div>
        <div class="menu">
          <ul class="anchor_nav">
            <!-- <li class="current"><a href="#home">Home</a></li> -->
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#mentorship">Mentorship</a></li>
            <!-- <li><a href="#hobbies">Hobbies</a></li> -->
            <li><a href="#certifications">Certification</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
            <li class="download_cv">
              <a href="https://drive.google.com/file/d/1XfOdzXb9w9SAHwJ6ct34Hs83ZLCO942b/view?usp=sharing" target="_blank" download><span>Download CV</span></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderVue",
  props: {
    dark: { type: Boolean },
  },
};
</script>
