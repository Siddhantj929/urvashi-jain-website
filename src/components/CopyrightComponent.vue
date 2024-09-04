<template>
  <div class="dizme_tm_section">
    <div class="dizme_tm_copyright">
      <div class="container">
        <div class="inner" style="justify-content: center">
          <div class="center wow fadeInLeft" data-wow-duration="1s" >
            <p>
              Copryright
              &copy; {{ new Date().getFullYear() }}. Urvashi Jain. All Rights Reserved.
            </p>
          </div>
          <!-- <div class="right wow fadeInRight" data-wow-duration="1s">
            <ul>
              <li><a href="#">Terms &amp; Condition</a></li>
              <li><a href="#">Privacy Policy</a></li>
            </ul>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CopyrightComponent",
  components: {},
};
</script>
