<template>
  <div>
    <div class="w-hero_container">

      <div class="contain w-h-container">
        <p class="pm w-h-subheading" data-aos="fade-up" data-aos-duration="1000">case studies</p>
        <h1 data-aos="fade-up" data-aos-duration="1000" data-aos-delay="300">
          Some of my
          <br />Finest
          <span class="outlined">Work</span>
        </h1>
        <p
          class="pm w-subheading_2"
          data-aos="fade-up"
          data-aos-duration="900"
          data-aos-delay="600"
        >
          I pour my ❤️️ into every project. I do what i do because I love it and
          I am dedicated to creating meaningful work.
        </p>
      </div>
    </div>
    <!-- timeline 2019 -->
    <!-- <projecttimeline timeline="2019" /> -->

    <!-- project grid -->
    <div class="showcase-container-home">
      <div class="showcase-container-grid">
         <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/GoCorona">
            <thumbnail
              thumbnailName="Gocorona"
              thumbnailDescription="App Development competition"
              thumbnail="/raghav/gocorona2.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="800"
              data-aos-once="true"
              data-aos-anchor-placement="top-bottom"
            />
          </nuxt-link>
        </div>

        <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/Blockchain">
            <thumbnail
              thumbnailName="Blockchain Aadhar Voting"
              thumbnailDescription="Microsoft Code fundoo Competition"
              thumbnail="/raghav/voting2.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="1000"
              data-aos-once="true"
              data-aos-anchor-placement="top-bottom"
            />
          </nuxt-link>
        </div>

        <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/TravelGo">
            <thumbnail
              thumbnailName="Travel Go"
              thumbnailDescription="Chatbot as Internship in Valiance Solutions"
              thumbnail="/raghav/travelgo.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="100"
              data-aos-once="true"
              data-aos-anchor-placement="top-bottom"
            />
          </nuxt-link>
        </div>

        <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/SocialContour">
            <thumbnail
              thumbnailName="SocialContour"
              thumbnailDescription="Freelance"
              thumbnail="/raghav/socialcontour2.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="300"
              data-aos-once="true"
            />
          </nuxt-link>
        </div>

        <div class="p-thumbnail-ad">
          <nuxt-link to="/OpenSource">
            <thumbnail
              thumbnailName="OpenSource"
              thumbnailDescription="OpenSource"
              thumbnail="/raghav/open.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="300"
              data-aos-once="true"
            />
          </nuxt-link>
        </div>

        <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/automizeapps">
            <thumbnail
              thumbnailName="Automize Apps"
              thumbnailDescription="Internship"
              thumbnail="/raghav/automize2.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="100"
              data-aos-once="true"
            />
          </nuxt-link>
        </div>

         <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/goals101">
            <thumbnail
              thumbnailName="Change Management Tool"
              thumbnailDescription="Goals 101, Internship"
              thumbnail="/raghav/goals.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="300"
              data-aos-once="true"
            />
          </nuxt-link>
        </div>

         <div class="p-thumbnail-ad">
          <nuxt-link to="/projects/streerides">
            <thumbnail
              thumbnailName="Streerides"
              thumbnailDescription="Website Development"
              thumbnail="/raghav/streerides3.jpg"
              data-aos="zoom-out-up"
              data-aos-duration="400"
              data-aos-delay="300"
              data-aos-once="true"
            />
          </nuxt-link>
        </div>
      </div>
    </div>

    <!-- thumbnail end here -->
    <!-- some more projects links  -->

    <!-- my quote -->
    <hr class="section-divider p-section-divider" />


    <div class="p-project-footer">
      <div class="p-h-footer-container">
        <div class="p-f-p-container">
          <nuxt-link to="/blog">
            <div class="p-h-previous">
              <div class="overlay"></div>
              <span class="p-h-text">
                <h3>Go to Blog</h3>
              </span>
            </div>
          </nuxt-link>
        </div>
        <div class="p-home-icon">
          <nuxt-link to="/">
            <img src="~assets/projects/home-icon.svg" alt="home button svg icon" title="To home" />
          </nuxt-link>
        </div>

        <div class="p-f-n-container">
          <nuxt-link to="/about">
            <div class="p-h-next">
              <div class="overlay"></div>
              <span class="p-h-text">
                <h3>About Me</h3>
              </span>
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>

    
    <!-- See my Photography -->
    <div class="w-photography-container"></div>
    <div class="w-arts-container"></div>
  </div>
</template>

<script>
import Thumbnail from '~/components/thumbnail'
import Projecttimeline from '~/components/projects/projecttimeline'
import Pfootern from '~/components/projects/pfootern'
import Pfooterp from '~/components/projects/pfooterp'
export default {
  layout: 'projects',
  components: {
    Thumbnail,
    Projecttimeline,
    Pfooterp,
    Pfootern
  }
}
</script>

<style>
.p-footer-container {
  width: 100%;
  height: 60vh;
  background-color: white;
  padding: 0px 0px 0px 0px;
  position: relative;
}

.p-section-divider {
  padding: 60px 0px 30px 0px;
}

.p-footer-container img {
  height: 83%;
  position: absolute;
  right: 7%;
  bottom: 0px;
  z-index: 1;
}

.p-h-quote-contain {
  position: relative;
  margin: 63px 32.4% 0px calc(20% - 83px);
  top: 21%;
  padding: 28px 0px 0px 0px;
  z-index: 3;
}

@media screen and (max-width: 1200px) {
  .p-h-quote-contain {
    padding: 27px 92px 0px 0px;
  }
}
@media screen and (max-width: 800px) {
  .p-h-quote-contain {
    /* margin-left: 20%; */
    margin-right: 18.4%;
    margin-left: 10%;
  }
}

@media screen and (max-width: 500px) {
  .p-h-quote-contain {
    /* margin-left: 20%; */
    /* margin-right: 9%; */
    margin-right: 4%;
    margin-left: 7%;
  }
}

.p-quote-container p {
  color: black;
  font-size: 30px;
}

/* p footer links */

.p-h-footer-links {
  width: 100%;
  height: 30vh;
  background-color: black;
  position: relative;
}

.p-h-footer-links::before {
  content: '';
  height: 1px;
  top: 0px;
  position: absolute;
  width: 100%;
  background-color: var(--primary-color);
  transition: height 0.65s;
  transition-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
}
.p-h-footer-container:hover .p-h-footer-links:before {
  height: 100%;
}

.p-h-footer-links span {
  z-index: 10;
  position: relative;
  font-size: 1.4em;
  color: white;
}

.p-h-footer-container:hover .p-h-footer-links span {
  color: black;
}

/*  */

.p-project-footer {
  width: 100%;
  position: relative;
}
.p-home-icon img {
  position: absolute;
  z-index: 3;
  left: 50%;
  width: 76px;
  top: 39%;
  transform: translate(-50%, -50%);
  cursor: pointer;
  padding: 18px;
  transition: all 0.5s;
  transition-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
}
.p-home-icon img:hover {
  width: 85px;
  border: solid 1px white;
}

.p-h-footer-container {
  width: 100%;
  padding-top: 0;
  padding-bottom: 0;
  position: relative;
  height: 30vh;
  display: grid;
  grid-template-areas:
    'a b'
    'a b';
  background-color: var(--primary-color);
  transition: height 0.95s cubic-bezier(0.475, 0.425, 0, 0.995);
  position: relative;
}

.p-h-footer-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 40px;
  z-index: 2;
  background-color: var(--primary-color);
  display: block;
  will-change: transform;
  -webkit-transition: -webkit-transform 0.65s;
  transition: -webkit-transform 0.65s;
  transition: transform 0.65s;
  transition: transform 0.65s, -webkit-transform 0.65s;
  -webkit-transition-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
  transition-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
}

.p-h-footer-container:hover:before {
  -webkit-transform: translateY(-100%);
  transform: translateY(-100%);
}

.p-h-previous {
  /* cursor: url('/cursor-previous.png'), auto; */
  cursor: url('/cp.svg'), auto;
  position: relative;
}

.p-h-next {
  cursor: url('/cn.svg'), auto;
  position: relative;
}

.p-text > h3 {
  color: white;
}

.p-h-previous > img {
  width: 100%;
  object-fit: cover;
  height: 80vh;
}

.p-h-next > img {
  width: 100%;
  object-fit: cover;
  height: 80vh;
}

.overlay {
  background-color: black;
  opacity: 0.9;
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0%;
  left: 0%;
}

.p-h-text {
  position: absolute;
  width: 100%;
  align-items: center;
  top: 15%;
  color: white;
  text-align: center;
  transition: all 0.85s cubic-bezier(0.19, 1, 0.22, 1);
  padding: 30px 0px 0px 0px;
}

.p-h-previous:hover .p-h-text {
  letter-spacing: 3px;
}

.p-h-next:hover .p-h-text {
  letter-spacing: 3px;
}
</style>
