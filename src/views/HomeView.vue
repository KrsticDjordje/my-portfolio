<template>
  <div>
    <div id="colorlib-page">
      <div id="colorlib-about">
        <div class="container">
          <div class="row text-center">
            <h2 class="bold">About</h2>
          </div>
          <div class="row">
            <div class="col-md-5 animate-box">
              <div class="owl-carousel3">
                <div class="item">
                  <img
                    class="img-responsive about-img"
                    src="data:image/jpeg;base64,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"
                    alt=""
                  />
                </div>
                <div class="item">
                  <img
                    class="img-responsive about-img"
                    src="images/about-2.jpg"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col-md-6 col-md-push-1 animate-box">
              <div class="about-desc">
                <div class="owl-carousel3">
                  <div class="item">
                    <h2><span>Djordje</span><span>Krstic</span></h2>
                  </div>
                  <div class="item">
                    <h2><span>I'm</span><span>A Frontend Developer</span></h2>
                  </div>
                </div>
                <div class="desc">
                  <div class="rotate">
                    <h2 class="heading">About</h2>
                  </div>
                  <p>
                    A small river named Duden
                    <a href="#">flows by their place</a> and supplies it with
                    the necessary regelialia. It is a paradisematic country, in
                    which roasted parts of sentences fly into your mouth. Even
                    the all-powerful Pointing has no control about the blind
                    texts it is an almost unorthographic life.
                  </p>
                  <p class="colorlib-social-icons">
                    <a href="#"><i class="icon-facebook4"></i></a>
                    <a href="#"><i class="icon-twitter3"></i></a>
                    <a href="#"><i class="icon-googleplus"></i></a>
                    <a href="#"><i class="icon-dribbble2"></i></a>
                  </p>
                  <p>
                    <a href="#" class="btn btn-primary btn-outline"
                      >Contact Me!</a
                    >
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="colorlib-services">
        <div class="container">
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
                        <h3>1 - Graphic Design</h3>
                        <ul>
                          <li>UI Design</li>
                          <li>Website &amp; Digital Design</li>
                          <li>Brading &amp; Visual Identity</li>
                          <li>Print Design</li>
                        </ul>
                      </div>
                      <div class="services animate-box">
                        <h3>3 - Front End Development</h3>
                        <ul>
                          <li>HTML / CSS</li>
                          <li>JS &amp; Jquery Startup</li>
                          <li>WordPress</li>
                          <li>Jomla</li>
                        </ul>
                      </div>
                    </div>
                    <div class="col-md-6">
                      <div class="services animate-box">
                        <h3>2 - Illustration</h3>
                        <ul>
                          <li>Editorial</li>
                          <li>Narrative</li>
                          <li>Motion Graphics</li>
                          <li>Animation</li>
                          <li>Visual Effects</li>
                        </ul>
                      </div>
                      <div class="services animate-box">
                        <h3>4 - Web Marketing</h3>
                        <ul>
                          <li>Sales Marketing</li>
                          <li>Invoice</li>
                          <li>eCommerce</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="one-forth services-img"
                  style="background-image: url(images/services-img-1.jpg)"
                ></div>
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
            <div class="col-md-12">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
                  class="work-img"
                  style="background-image: url(images/work-1.jpg)"
                >
                  <div class="display-t">
                    <div class="work-name">
                      <h2>Pursuing Best</h2>
                    </div>
                  </div>
                </a>
                <div class="col-md-4 col-md-offset-4">
                  <div class="desc">
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
            <div class="col-md-12">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
                  class="work-img"
                  style="background-image: url(images/work-2.jpg)"
                >
                  <div class="display-t">
                    <div class="work-name">
                      <h2>Coordinates</h2>
                    </div>
                  </div>
                </a>
                <div class="col-md-4 col-md-offset-4">
                  <div class="desc">
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
            <div class="col-md-12">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
                  class="work-img"
                  style="background-image: url(images/work-3.jpg)"
                >
                  <div class="display-t">
                    <div class="work-name">
                      <h2>Cristall</h2>
                    </div>
                  </div>
                </a>
                <div class="col-md-4 col-md-offset-4">
                  <div class="desc">
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
            <div class="col-md-12">
              <div class="work-entry animate-box">
                <a
                  href="work.html"
                  class="work-img"
                  style="background-image: url(images/work-4.jpg)"
                >
                  <div class="display-t">
                    <div class="work-name">
                      <h2>Black</h2>
                    </div>
                  </div>
                </a>
                <div class="col-md-4 col-md-offset-4">
                  <div class="desc">
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
    <hello-world />
  </div>
</template>

<script>
import HelloWorld from "../components/HelloWorld";

export default {
  name: "HomeView",

  components: {
    HelloWorld,
  },
};
</script>
