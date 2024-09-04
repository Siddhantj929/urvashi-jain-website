<template>
  <div class="dizme_tm_section" id="testimonials">
    <div class="dizme_tm_testimonials">
      <div class="dizme_tm_main_title" data-align="center">
        <span>Recommendations</span>
        <h3>What my colleagues say</h3>
        <p>
          I give my best in my work while staying eager for feedback.
        </p>
      </div>
      <div class="list_wrapper">
        <div class="total">
          <div class="in">
            <swiper
              :pagination="{ clickable: true, el: '.owl-dots' }"
              :modules="modules"
              class="owl-carousel owl-theme"
            >
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    I am delighted to recommend Urvashi for her outstanding work as a design system designer. She played a key role in building and releasing Mindtickle’s first design system, showcasing her exceptional skills and dedication. Urvashi’s keen eye for design, deep understanding of user experience principles, and meticulous attention to detail have been vital. She excels in collaboration and seamlessly working with cross-functional teams. Always eager to learn and grow, Urvashi stays updated with the latest design trends and technologies. Her expertise, teamwork, and continuous learning mindset make her an invaluable asset to any team.
                  </p>
                </div>
                <div class="short">
                  <div class="image">
                    <div
                      class="main"
                      data-img-url="/img/testimonials/1.jpeg"
                    ></div>
                  </div>
                  <div class="detail">
                    <h3>Ron Severdia</h3>
                    <span>VP of Design at Mindickle</span>
                  </div>
                </div>
              </swiper-slide>
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    Urvashi started working with me as an associate product designer for the SplashLearn growth team. The role included redesigning the user flows basis new product requirements, being part of user research calls and designing the experience. She is also a diligent organizer who ensures that her work is updated and accessible, which helped me understand what went well and what did not. She asks the right questions, I’m sure she will hone her skills in design further to come up with exemplary solutions to those questions. I am confident that Urvashi will achieve great things in her career.
                  </p>
                </div>
                <div class="short">
                  <div class="image">
                    <div
                      class="main"
                      data-img-url="/img/testimonials/2.jpeg"
                    ></div>
                  </div>
                  <div class="detail">
                    <h3>Nikita Singh</h3>
                    <span>Design Head at SplashLearn</span>
                  </div>
                </div>
              </swiper-slide>
              <swiper-slide>
                <div class="icon" v-html="testimonialIcon"></div>
                <div class="text">
                  <p>
                    Urvashi & I worked together on multiple projects and she always brought curiosity to the table.
                    Her approach to design is methodical and user-centric. She always backs her prototypes with research, logic, and usability testing.
                    As a dedicated designer to the tutoring squad at SplashLearn, she was able to deliver under constraints in a fast-paced environment.
                  </p>
                </div>
                <div class="short">
                  <div class="image">
                    <div
                      class="main"
                      data-img-url="/img/testimonials/3.jpeg"
                    ></div>
                  </div>
                  <div class="detail">
                    <h3>Neil Verma</h3>
                    <span>PM at SplashLearn</span>
                  </div>
                </div>
              </swiper-slide>
            </swiper>
            <div class="owl-dots"></div>
          </div>
          <div class="left_details">
            <span class="circle green animPulse"></span>
            <span class="circle yellow animPulse"></span>
            <span class="circle border animPulse"></span>
          </div>
          <div class="right_details">
            <span class="circle yellow animPulse"></span>
            <span class="circle purple animPulse"></span>
            <span class="circle border animPulse"></span>
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/testimonials/1.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
import { testimonialIcon } from "@/svg";
import { Pagination } from "swiper";
import { Swiper, SwiperSlide } from "vue-awesome-swiper";
export default {
  name: "TestimonialsComponent",
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return {
      testimonialIcon,
    };
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
};
</script>
