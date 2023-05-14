<template>
  <div>
    <div id="colorlib-page">
      <div id="colorlib-about">
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
                      ><span>A Frontend Developer</span>
                    </h2>
                  </div>
                </div>
                <div class="desc">
                  <div class="rotate">
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
                    <a href="#"><i class="icon-facebook4"></i></a>
                    <a href="#"><i class="icon-twitter3"></i></a>
                    <a href="#"><i class="icon-googleplus"></i></a>
                    <a href="#"><i class="icon-dribbble2"></i></a>
                  </p>
                  <p>
                    <button href="#" class="btn btn-primary btn-outline">
                      Contact Me!
                    </button>
                    <a href="#" download>
                      <button href="#" class="btn btn-primary">
                        Download CV
                      </button>
                    </a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="colorlib-services">
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
                      <div class="rotate">
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
                      'url(' + require('@/assets/katib.jpg') + ')',
                  }"
                ></div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div id="colorlib-services">
        <div class="container" style="margin-top: 45px">
          <div class="row text-center">
            <h2 class="bold">Background</h2>
          </div>
          <div class="row">
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
                          <h3>- Frontend Developer - AppWorks</h3>
                        </div>
                        }}
                        <ul>
                          <li>HTML / CSS / SCSS</li>
                        </ul>

                        <div class="d-flex">
                          <span class="mr-3 dateExperience">2020 - 2020</span>
                          <h3>- Web Designer Intern - The Social Formula</h3>
                        </div>
                        <ul>
                          <li>HTML / CSS / SCSS</li>
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

      <div id="colorlib-work">
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
              <div class="rotate">
                <h2 class="heading">Portfolio</h2>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
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
                      Far far away, behind the word mountains, far from the
                      countries Vokalia and Consonantia, there live the blind
                      texts. Separated they live in Bookmarksgrove right at the
                      coast of the Semantics, a large language ocean.
                    </p>
                    <p class="read"><a href="#">View details</a></p>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
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
                      Far far away, behind the word mountains, far from the
                      countries Vokalia and Consonantia, there live the blind
                      texts. Separated they live in Bookmarksgrove right at the
                      coast of the Semantics, a large language ocean.
                    </p>
                    <p class="read"><a href="#">View Details</a></p>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
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
                      Far far away, behind the word mountains, far from the
                      countries Vokalia and Consonantia, there live the blind
                      texts. Separated they live in Bookmarksgrove right at the
                      coast of the Semantics, a large language ocean.
                    </p>
                    <p class="read"><a href="#">View details</a></p>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
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
                      Far far away, behind the word mountains, far from the
                      countries Vokalia and Consonantia, there live the blind
                      texts. Separated they live in Bookmarksgrove right at the
                      coast of the Semantics, a large language ocean.
                    </p>
                    <p class="read"><a href="#">View details</a></p>
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
};
</script>
