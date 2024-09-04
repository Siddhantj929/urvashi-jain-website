<template>
  <div class="dizme_tm_section" id="certifications">
    <div class="dizme_tm_services">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <span>Certifications</span>
          <h3>What I do to stay updated</h3>
          <p>
            I have completed 10+ courses on the IDF & IBM platform.
          </p>
        </div>
        <div class="service_list">
          <ul>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
            >
              <div class="list_inner tilt-effect" 
              style="background-image: url('/img/certificate/1.jpg'); background-size: cover; min-height: 390px;"
              >
              </div>
            </li>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
            >
              <div class="list_inner tilt-effect" 
              style="background-image: url('/img/certificate/2.jpg'); background-size: cover; min-height: 390px;"
              >
              </div>
            </li>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
            >
              <div class="list_inner tilt-effect" 
              style="background-image: url('/img/certificate/3.jpg'); background-size: cover; min-height: 390px;"
              >
              </div>
            </li>
            <li
              class="wow fadeInLeft"
              data-wow-duration="1s"
            >
              <div class="list_inner tilt-effect" 
              style="background-image: url('/img/certificate/4.jpg'); background-size: cover; min-height: 390px;"
              >
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/img/brushes/service/5.png" alt="" />
      </div>
      <div class="brush_2 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/service/6.png" alt="" />
      </div>
    </div>
  </div>
  <div :class="active == 1 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/1.jpg"
            style="background-image: url('img/service/1.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Creative Design</h3>
          <span class="price">Starts from <span>$99</span></span>
        </div>
        <div class="descriptions">
          <p>
            Dizme is a leading web design agency with an award-winning design
            team that creates innovative, effective websites that capture your
            brand, improve your conversion rates, and maximize your revenue to
            help grow your business and achieve your goals.
          </p>
          <p>
            In today’s digital world, your website is the first interaction
            consumers have with your business. That's why almost 95 percent of a
            user’s first impression relates to web design. It’s also why web
            design services can have an immense impact on your company’s bottom
            line.
          </p>
          <p>
            That’s why more companies are not only reevaluating their website’s
            design but also partnering with Kura, the web design agency that’s
            driven more than $2.4 billion in revenue for its clients. With over
            50 web design awards under our belt, we're confident we can design a
            custom website that drives sales for your unique business.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 2 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/2.jpg"
            style="background-image: url('img/service/2.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Graphic Design</h3>
          <span class="price">Starts from <span>$199</span></span>
        </div>
        <div class="descriptions">
          <p>
            Dizme is a leading web design agency with an award-winning design
            team that creates innovative, effective websites that capture your
            brand, improve your conversion rates, and maximize your revenue to
            help grow your business and achieve your goals.
          </p>
          <p>
            In today’s digital world, your website is the first interaction
            consumers have with your business. That's why almost 95 percent of a
            user’s first impression relates to web design. It’s also why web
            design services can have an immense impact on your company’s bottom
            line.
          </p>
          <p>
            That’s why more companies are not only reevaluating their website’s
            design but also partnering with Kura, the web design agency that’s
            driven more than $2.4 billion in revenue for its clients. With over
            50 web design awards under our belt, we're confident we can design a
            custom website that drives sales for your unique business.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 3 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/3.jpg"
            style="background-image: url('img/service/3.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>UI/UX Design</h3>
          <span class="price">Starts from <span>$299</span></span>
        </div>
        <div class="descriptions">
          <p>
            Dizme is a leading web design agency with an award-winning design
            team that creates innovative, effective websites that capture your
            brand, improve your conversion rates, and maximize your revenue to
            help grow your business and achieve your goals.
          </p>
          <p>
            In today’s digital world, your website is the first interaction
            consumers have with your business. That's why almost 95 percent of a
            user’s first impression relates to web design. It’s also why web
            design services can have an immense impact on your company’s bottom
            line.
          </p>
          <p>
            That’s why more companies are not only reevaluating their website’s
            design but also partnering with Kura, the web design agency that’s
            driven more than $2.4 billion in revenue for its clients. With over
            50 web design awards under our belt, we're confident we can design a
            custom website that drives sales for your unique business.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
  <div :class="active == 4 ? '' : 'service_hidden_details'">
    <ModalBox :close="close">
      <div class="service_popup_informations">
        <div class="image">
          <img src="img/thumbs/4-2.jpg" alt="" />
          <div
            class="main"
            data-img-url="img/service/4.jpg"
            style="background-image: url('img/service/4.jpg')"
          ></div>
        </div>
        <div class="main_title">
          <h3>Web Design</h3>
          <span class="price">Starts from <span>$399</span></span>
        </div>
        <div class="descriptions">
          <p>
            Dizme is a leading web design agency with an award-winning design
            team that creates innovative, effective websites that capture your
            brand, improve your conversion rates, and maximize your revenue to
            help grow your business and achieve your goals.
          </p>
          <p>
            In today’s digital world, your website is the first interaction
            consumers have with your business. That's why almost 95 percent of a
            user’s first impression relates to web design. It’s also why web
            design services can have an immense impact on your company’s bottom
            line.
          </p>
          <p>
            That’s why more companies are not only reevaluating their website’s
            design but also partnering with Kura, the web design agency that’s
            driven more than $2.4 billion in revenue for its clients. With over
            50 web design awards under our belt, we're confident we can design a
            custom website that drives sales for your unique business.
          </p>
        </div>
      </div>
    </ModalBox>
  </div>
</template>

<script>
import ModalBox from "./popup/ModalBox.vue";
export default {
  name: "ServiceCompoent",
  data() {
    return {
      active: 0,
    };
  },
  mounted() {
    let VanillaTilt = require("vanilla-tilt");
    VanillaTilt.init(document.querySelectorAll(".tilt-effect"), {
      maxTilt: 6,
      easing: "cubic-bezier(.03,.98,.52,.99)",
      speed: 500,
      transition: true,
    });
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
  components: { ModalBox },
  props: {
    dark: { type: Boolean },
  },
};
</script>
