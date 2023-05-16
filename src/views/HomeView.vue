<template>
  <div>
    <div id="colorlib-page">
      <div id="colorlib-about" data-aos="fade-up" data-aos-duration="1000">
        <div class="container">
          <div class="row text-center">
            <h2 class="bold">About</h2>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div class="about-desc">
                <div class="owl-carousel3">
                  <div class="item">
                    <h2>
                      <span>I'm Đorđe Krstić</span
                      ><span style="color: #314559">Frontend Developer</span>
                    </h2>
                  </div>
                </div>
                <div class="desc">
                  <div
                    class="rotate"
                    data-aos="fade-right"
                    data-aos-duration="1000"
                  >
                    <h2 class="heading">About</h2>
                  </div>
                  <p>
                    After creating over 40+ websites using HTML, CSS, and
                    JavaScript, I started exploring and learning Vue.js, a new
                    technology that immediately caught my attention because of
                    its simplicity and flexibility. Soon, I began building web
                    applications using Vue.js along with Vuex and Vue Router,
                    creating elegant and intuitive user interfaces. <br />
                    <br />
                    Using Vue.js, I have developed a variety of projects,
                    including different web applications and websites. I
                    leveraged my knowledge of CSS and HTML to design beautiful
                    user interfaces using libraries like Tailwind, Bootstrap,
                    and Vuetify. Working with my team, I have contributed to
                    various projects, working on design, development, and
                    implementation.
                  </p>
                  <p class="colorlib-social-icons">
                    <a href="https://github.com/KrsticDjordje/" target="_blank">
                      <span class="mdi mdi-github icons"></span>
                    </a>
                    <a
                      href="https://rs.linkedin.com/in/djordjekrstic97"
                      target="_blank"
                    >
                      <span class="mdi mdi-linkedin icons"></span>
                    </a>
                  </p>
                  <p>
                    <a href="@/assets/MyResume _ Krstic Djordje.pdf" download>
                      <button class="btn btn-primary btn-outline">
                        Download CV
                      </button>
                    </a>
                    <a href="mailto:djordje.krstic97@gmail.com">
                      <button class="btn btn-primary">Contact me!</button>
                    </a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="colorlib-services" data-aos="fade-up" data-aos-duration="1000">
        <div class="container" ref="about">
          <div class="row text-center">
            <h2 class="bold">Services</h2>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div class="services-flex">
                <div class="one-third">
                  <div class="row">
                    <div
                      class="col-md-12 col-md-offset-0 animate-box intro-heading"
                    >
                      <span>My Services</span>
                      <h2>Here Are Some of My Skills</h2>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-12">
                      <div
                        class="rotate"
                        data-aos="fade-right"
                        data-aos-duration="1000"
                      >
                        <h2 class="heading">Services</h2>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="services animate-box">
                        <h3>1 - Frontend Development</h3>
                        <ul>
                          <li>HTML / CSS / SCSS</li>
                          <li>Bootstrap / Tailwind</li>
                          <li>JavaScript</li>
                          <li>VueJS</li>
                          <li>Axios</li>
                          <li>Vue Router / Vuex / Vuetify</li>
                        </ul>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="services animate-box">
                        <h3>2 - Designer Tools</h3>
                        <ul>
                          <li>Figma</li>
                          <li>Adobe Photoshop</li>
                          <li>Adobe Illustrator</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="one-forth services-img"
                  :style="{
                    backgroundImage:
                      'url(' + require('@/assets/laptop.jpg') + ')',
                  }"
                ></div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div id="colorlib-services" data-aos="fade-up" data-aos-duration="1000">
        <div class="container" style="margin-top: 45px">
          <div class="row text-center">
            <h2 class="bold bcg">Background</h2>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div
                class="rotate"
                data-aos="fade-right"
                data-aos-duration="1000"
              >
                <h2 class="heading">Background</h2>
              </div>
            </div>
            <div class="col-md-6">
              <div class="services-flex">
                <div class="education">
                  <div class="row">
                    <div
                      class="col-md-12 col-md-offset-0 animate-box intro-heading"
                    >
                      <h2>My Educations</h2>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-12">
                      <div class="services animate-box">
                        <div class="d-flex">
                          <span class="mr-3 dateExperience">2016 - 2021</span>
                          <h3>- Information Technology School - ITS</h3>
                        </div>
                        <ul>
                          <li>
                            Computer Multimedia Engineer for Information
                            Technology
                          </li>
                        </ul>
                        <div
                          class="d-flex"
                          style="
                            border-top: 1px solid #ebebeb;
                            padding-top: 20px;
                          "
                        >
                          <span class="mr-3 dateExperience"
                            >6 months (2022)</span
                          >
                          <h3>- Vue JS - Esenca Software</h3>
                        </div>
                        <div class="d-flex">
                          <span class="mr-3 dateExperience"
                            >4 months (2023)</span
                          >
                          <h3>- English Language - Tesla Academy</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="services-flex">
                <div class="education">
                  <div class="row">
                    <div
                      class="col-md-12 col-md-offset-0 animate-box intro-heading"
                    >
                      <h2>My Experience</h2>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-md-12">
                      <div class="services animate-box">
                        <div class="d-flex">
                          <span class="mr-3 dateExperience">2021 - Today</span>
                          <h3>- Frontend Developer</h3>
                        </div>
                        <ul>
                          <li>AppWorks, Belgrade</li>
                        </ul>

                        <div class="d-flex">
                          <span class="mr-3 dateExperience">2020 - 2020</span>
                          <h3>- Web Designer / Wordpress Intern</h3>
                        </div>
                        <ul>
                          <li>The Social Formula, Belgrade</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div id="colorlib-work" data-aos="fade-up" data-aos-duration="1000">
        <div class="container">
          <div class="row text-center">
            <h2 class="bold">Works</h2>
          </div>
          <div class="row">
            <div
              class="col-md-12 col-md-offset-0 text-center animate-box intro-heading"
            >
              <span>Portfolio</span>
              <h2>Done Projects</h2>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div
                class="rotate"
                data-aos="fade-right"
                data-aos-duration="1000"
              >
                <h2 class="heading">Portfolio</h2>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div
                class="work-entry animate-box"
                data-aos="fade-up"
                data-aos-duration="1000"
              >
                <a
                  href="#"
                  class="work-img"
                  :style="{
                    backgroundImage:
                      'url(' + require('@/assets/katib.jpg') + ')',
                  }"
                >
                  <div class="display-t"></div>
                </a>
                <div class="col-md-10">
                  <div class="desc">
                    <h3 class="title-services">Software</h3>
                    <p>
                      The "Katib" project is an innovative solution for
                      transcribing video into text. With its diverse
                      functionalities, it allows users to easily and efficiently
                      translate and follow video content that they can upload
                      and then translate the text into another language. One of
                      the main features of the project is the ability to perform
                      live transcription, where users can select their desired
                      TV channel and receive automatically translated text every
                      2 minutes. <br />
                      <br />
                      As part of the team that worked on the project, I had the
                      privilege to develop the entire frontend using Vue.js,
                      Vuex, Vue Router, and Vuetify. The integration of the
                      frontend with the backend was implemented through a Python
                      API using the Axios library. Through this communication,
                      we enabled efficient data exchange and ensured smooth
                      functioning of the application. Our API provided user
                      authentication through a login system. Based on the user's
                      subscription, we granted access to selected channels and
                      allowed them to utilize all the project's capabilities.
                      <br />
                      <br />
                      The "Katib" project brings revolutionary possibilities for
                      transcribing and translating video content, providing
                      users with practical solutions for tracking and
                      understanding diverse material. My role in this project as
                      a solo frontend developer allowed me to contribute to the
                      creation of an intuitive and efficient user interface. I
                      am proud to have been part of this project and look
                      forward to future achievements and successes that "Katib"
                      brings.
                    </p>
                    <p>
                      <a href="https://padme.mpanel.app/" target="_blank">
                        <span class="mdi mdi-web icons two"></span>
                      </a>
                      <a
                        href="https://github.com/KrsticDjordje/vue-software"
                        target="_blank"
                      >
                        <span class="mdi mdi-github icons two"></span>
                      </a>
                    </p>
                    <!-- <p class="read"><a href="#">View details</a></p> -->
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div
                class="work-entry animate-box"
                data-aos="fade-up"
                data-aos-duration="1000"
              >
                <a
                  href="#"
                  class="work-img"
                  :style="{
                    backgroundImage:
                      'url(' + require('@/assets/maul.jpg') + ')',
                  }"
                >
                  <div class="display-t"></div>
                </a>
                <div class="col-md-10">
                  <div class="desc">
                    <h3 class="title-services">E-commerce</h3>
                    <p>
                      The project I worked on was the development of an
                      e-commerce website for the renowned football club FK
                      Partizan. Using technologies such as Vue.js, Vue Router,
                      Bootstrap, Axios, and a bit of GSAP, I managed to create
                      an exceptionally functional and visually appealing
                      website.<br />
                      <br />
                      The main focus of the project was the implementation of a
                      complete shopping cart system. Through reactivity, I
                      enabled users to add products to their cart, perform
                      deletions, increase or decrease quantities, all with
                      instant refreshing of the total amount. This fluid
                      interaction between users and the shopping cart
                      functionality contributed to a pleasant shopping
                      experience on the website. <br />
                      <br />
                      One of the key features of the project was optimizing the
                      product search. I implemented a search mechanism that was
                      tailored to the most efficient way of working with the
                      database. The search is activated after the user enters
                      three letters, avoiding unnecessary backend requests. This
                      enabled fast and efficient product searching, enhancing
                      the overall user experience.<br />
                      <br />
                      Through collaboration and teamwork, I managed to create an
                      outstanding e-commerce website for FK Partizan. Building
                      the shopping cart system, optimizing the search, and
                      utilizing reactivity were just some of the aspects I
                      worked on to provide a seamless user experience.
                    </p>
                    <p>
                      <a href="https://padme.mpanel.app/" target="_blank">
                        <span class="mdi mdi-web icons two"></span>
                      </a>
                      <a
                        href="https://github.com/KrsticDjordje/e-commerce-vue"
                        target="_blank"
                      >
                        <span class="mdi mdi-github icons two"></span>
                      </a>
                    </p>
                    <!-- <p class="read"><a href="#">View Details</a></p> -->
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6" data-aos="fade-up" data-aos-duration="1000">
              <div class="work-entry animate-box">
                <a
                  href="#"
                  class="work-img"
                  :style="{
                    backgroundImage:
                      'url(' + require('@/assets/padme.jpg') + ')',
                  }"
                >
                  <div class="display-t"></div>
                </a>
                <div class="col-md-10">
                  <div class="desc">
                    <h3 class="title-services">Website</h3>
                    <p>
                      Additionally, the project I worked on involved creating a
                      website for FK Partizan, where the entire site was
                      connected to an admin panel. Within the project, we
                      developed functionalities such as the Match Center, Player
                      Center, displaying all played and upcoming matches, as
                      well as a club member overview. We also created a template
                      for reading articles. Furthermore, we implemented a video
                      playlist and reserved space for advertising banners on the
                      website. Additionally, we pulled posts from social media
                      platforms like Twitter and Instagram and displayed them on
                      the site. <br />
                      <br />
                      As the foundation of the project, we used Vue.js, Vuex,
                      Vue Router, and Bootstrap. Vue.js allowed us to develop a
                      dynamic user interface, while Vuex was responsible for
                      managing the application state. Vue Router enabled page
                      routing, while Bootstrap was crucial for fast and
                      responsive design. <br />
                      <br />
                      Integration with the admin panel enabled efficient content
                      management on the website, providing the FK Partizan
                      administrative team with control over displayed
                      information and the ability to update and add new content.
                      <br />
                      <br />
                      The project presented an exciting opportunity to create a
                      comprehensive website for FK Partizan. With careful
                      planning and implementation, we were able to provide an
                      intuitive user experience that meets the needs of both
                      fans and the administrative team. I'm proud to have been
                      part of this project.
                    </p>
                    <p>
                      <a href="https://padme.mpanel.app/" target="_blank">
                        <span class="mdi mdi-web icons two"></span>
                      </a>
                      <a
                        href="https://github.com/KrsticDjordje/vue-website"
                        target="_blank"
                      >
                        <span class="mdi mdi-github icons two"></span>
                      </a>
                    </p>
                    <!-- <p class="read"><a href="#">View details</a></p> -->
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6" data-aos="fade-up" data-aos-duration="1000">
              <div class="work-entry animate-box">
                <a
                  href="#"
                  class="work-img"
                  :style="{
                    backgroundImage:
                      'url(' + require('@/assets/nunb.jpg') + ')',
                  }"
                >
                  <div class="display-t"></div>
                </a>
                <div class="col-md-10">
                  <div class="desc">
                    <h3 class="title-services">PDF Reader</h3>
                    <p>
                      In this project, I used Vue.js and the pdf.express.js
                      library. I created a PDF reader designed for clients who
                      have e-books and e-publications on their websites. This
                      library supports various functionalities such as searching
                      within PDF documents, zooming in and out, adjusting
                      reading options, dark mode for comfortable reading in
                      different lighting conditions, and more.<br />
                      <br />
                      Integration with the backend was achieved through an API.
                      The backend sends a specially generated token for each PDF
                      on the website. Using the route, I decode that token and
                      based on the data obtained from the token, construct an
                      API call to retrieve the path to the PDF document as a
                      response. <br />
                      <br />
                      This PDF reader enables users to access e-books and
                      e-publications on the website in a simple and intuitive
                      manner. Through the implementation of Vue.js and the
                      pdf.express.js library, we created an interactive and
                      personalized reading experience.
                    </p>
                    <p>
                      <a
                        href="https://github.com/KrsticDjordje/vue-pdf-reader"
                        target="_blank"
                      >
                        <span class="mdi mdi-github icons two"></span>
                      </a>
                    </p>
                    <!-- <p class="read"><a href="#">View details</a></p> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
  mounted() {
    window.AOS.init();
  },
};
</script>
