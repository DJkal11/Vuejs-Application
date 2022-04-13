<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String,
  },
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<template>
  <div class="hello">
    <div class="Section-1">
      <div class="info-1">
        <h1 class="title-1">YOUR HIRING REIMAGINED</h1>
        <p class="content-1">
          One-stop hiring platform for every purpose-driven organization
        </p>
      </div>
      <b-button variant="danger">Get Started for Free</b-button>
    </div>
    <div class="Section-2">
      <div class="overlap-1">
        <div class="overlap-1-item">
          <h4 class="overlap-title">Save up to</h4>
          <h1 class="percentage">70%</h1>
          <p>hiring time & cost with integrated sourcing- screening solution</p>
        </div>
        <div class="overlap-1-item">
          <h4 class="overlap-title">Reduce</h4>
          <h1 class="percentage">68%</h1>
          <p>
            amount of interview time with our candidate video screening tool
          </p>
        </div>
        <div class="overlap-1-item">
          <h4 class="overlap-title">Candidates</h4>
          <h1 class="percentage">95%</h1>
          <p>said to have positive experience during the hiring process</p>
        </div>
        <div class="overlap-1-item">
          <h4 class="overlap-title">Experience</h4>
          <h1 class="percentage">90</h1>
          <p>better recruiter- hiring manager collaboration</p>
        </div>
      </div>
      <div class="overlap-2"></div>
      <div class="organizations">
        <h1 class="organization-title">Organizations that innovate with us</h1>
        <div class="organization-group">
          <fa class="organization-item" :icon="['fab', 'angrycreative']" />
          <fa class="organization-item" :icon="['fab', 'bity']" />
          <fa class="organization-item" :icon="['fab', 'uncharted']" />
          <fa class="organization-item" :icon="['fab', 'digg']" />
          <fa class="organization-item" :icon="['fab', 'cc-stripe']" />
        </div>
      </div>
    </div>
    <div class="Section-3">
      <h1 class="section-3-title">Why partner with Devcurate?</h1>
      <div>
        <div class="section-3-group">
          <div class="Section-3-image-1"></div>
          <div class="section-3-content">
            <button class="section-3-heading">EFFICIENCY</button>
            <h1>Fast track your hiring with candidate video screening</h1>
            <p>
              Reduce time-to-hire by skipping the time-consuming 1-on-1
              interview scheduling challenge and meet the right candidate faster
              with our one-way candidate video screening. What's more, enjoy our
              integrated job posting features so that you can manage essential
              hiring activities from the start — all in one place.
            </p>
          </div>
        </div>
        <div class="section-3-group">
          <div class="section-3-content">
            <button class="section-3-heading">EXPERIENCE</button>
            <h1>Improve everyone's experience</h1>
            <p>
              Our easy-to-use platform automates highly repeated hiring
              processes, allowing your hiring team to intuitively streamline
              what need to be done while boosting collaboration among hiring
              stakeholders, and enabling positive experience for your candidates
              throughout their application journey.
            </p>
          </div>
          <div class="Section-3-image-2"></div>
        </div>
        <div class="section-3-group">
          <div class="Section-3-image-3"></div>
          <div class="section-3-content">
            <button class="section-3-heading">EXPOSURE</button>
            <h1>Maximize your brand value to attract the right candidates</h1>
            <p>
              Gone are the days where “candidates come to you.” Communicate your
              impact and brand values with our branded job posting and a
              dedicated Employer Page. A strong employer brand not only helps
              you to attract more of the right talent, but essentially improve
              engagement and retention.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="Section-4">
      <h1 class="section-4-title">Benefit from these features</h1>
      <div class="feature-group">
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">
            <fa :icon="['fas', 'user-check']" />
          </div>
          <div class="feature-content">
            <h2>Easy Screening</h2>
            <p>
              Gain quick insight on job applicants with video screening tool
            </p>
          </div>
        </div>
      </div>
      <div class="div-btn">
        <button class="Section-4-btn">Start your free account now</button>
      </div>
    </div>
    <div class="Section-5">
      <h1>What leading recruiters say about us</h1>
      <b-carousel>
        <div class="section-5-card">
          <div class="section-5-icon"><fa :icon="['fas', 'user-check']" /></div>
          <div class="section-5-content">
            <h3>
              The user-friendly interface is what makes Devcurate platform
              different from others. It was super easy to assign the time-based
              interview questions, and we got amazing feedback from our
              candidates. We re very happy and would recommend to others.
            </h3>
            <h5><b>Naina Bedi</b></h5>
            <h5>Manager - Special Initiatives</h5>
          </div>
        </div>
        <div class="section-5-card">
          <div class="section-5-icon"><fa :icon="['fas', 'user-check']" /></div>
          <div class="section-5-content">
            <h3>
              Devcurate helps us save time and tackle interview scheduling
              challenges between hiring managers and candidates especially in
              the hybrid working environment. I believe this is a new way of
              candidate selection.
            </h3>
            <h5><b>Rangsri Kowiwattanakan</b></h5>
            <h5>Head of HRBP Operations & Support Center</h5>
          </div>
        </div>
      </b-carousel>
    </div>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Section-1 {
  background-image: url("../assets/Teamwork.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 34em;
  text-align: center;
  color: white;
}

.info-1 {
  padding-top: 7em;
}

.title-1 {
  font-size: 4.2em;
  padding-left: 7em;
  padding-right: 7em;
  margin-bottom: 0;
}

.content-1 {
  font-size: 1.5em;
}

.GetStartedbtn {
  background-color: rgb(252, 210, 0);
  width: 15em;
  padding: 0.7em;
  border: 0;
  border-radius: 50px;
  font-size: 1.5em;
}

.Section-2 {
  height: 32em;
  position: relative;
}

.overlap-1 {
  position: absolute;
  background-color: white;
  width: 80em;
  height: 15em;
  margin-top: -3em;
  margin-left: 5em;
  margin-right: 5em;
  border-radius: 20px;
  z-index: 2;
  box-shadow: 0px 10px 15px -3px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

.overlap-2 {
  position: absolute;
  background: rgb(255, 255, 255);
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 1) 10%,
    rgba(41, 215, 212, 1) 100%
  );
  width: 84em;
  height: 12em;
  margin-top: -1.7em;
  margin-left: 3em;
  margin-right: 3em;
  border: solid black;
  border-radius: 10px;
  z-index: 1;
}

.overlap-1-item {
  text-align: center;
  padding: 1em;
}
.percentage {
  font-size: 4em;
  margin: 0;
}

.overlap-title {
  margin-bottom: 0;
}

.organizations {
  position: absolute;
  margin-top: 14em;
  background-color: rgb(255, 255, 255);
  width: 100%;
}

.organization-title {
  margin-left: 3em;
  font-size: 2.5em;
}

.organization-group {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  padding: 3em;
}

.organization-item {
  font-size: 7em;
}

.Section-3 {
  background-color: rgb(237, 237, 237);
  height: fit-content;
}

.section-3-heading {
  background-color: rgb(6, 5, 6);
  color: white;
  border-radius: 10px;
  width: 12em;
  font-size: 1em;
  padding: 0.5em;
}

.section-3-title {
  margin-left: 3em;
  font-size: 2.5em;
  padding-top: 1em;
}

.Section-3-image-1 {
  background-image: url("../assets/efficiency.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 30em;
  height: 20em;
  border-radius: 20px;
  margin-right: 3em;
}

.Section-3-image-2 {
  background-image: url("../assets/experience.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 30em;
  height: 20em;
  border-radius: 20px;
  margin-right: 3em;
}

.Section-3-image-3 {
  background-image: url("../assets/exposure.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 30em;
  height: 20em;
  border-radius: 20px;
  margin-right: 3em;
}

.section-3-group {
  padding: 2em;
  margin-left: 10em;
  margin-right: 10em;
  display: grid;
  grid-template-columns: auto auto;
  gap: 0em;
}

.section-3-content {
  font-size: 1em;
  padding-left: 0em;
  padding-right: 5em;
}

.Section-4 {
  background: rgb(0, 255, 250);
  background: radial-gradient(
    circle,
    rgba(0, 255, 250, 1) 0%,
    rgba(0, 58, 89, 1) 100%
  );
  color: white;
}

.section-4-title {
  padding: 2.5em;
  padding-left: 4em;
  padding-bottom: 1em;
}

.feature-group {
  display: grid;
  grid-template-columns: auto auto auto;
  gap: 2em;
  padding: 8em;
  padding-top: 0;
  padding-bottom: 4em;
}

.feature-card {
  display: grid;
  grid-template-columns: auto auto;
  gap: 1em;
  background-color: white;
  color: black;
  padding: 2em;
  padding-top: 2.5em;
  padding-bottom: 2.5em;
  border-radius: 20px;
}

.feature-icon {
  font-size: 3em;
  margin-top: 1em;
}

.feature-content {
  border-left: solid black;
  font-size: 1em;
  padding-right: 3em;
  padding-left: 1em;
}

.div-btn {
  width: 100vw;
  text-align: center;
  padding-bottom: 4em;
}

.Section-4-btn {
  background-color: rgb(252, 210, 0);
  width: 15em;
  padding: 0.7em;
  border: 0;
  border-radius: 50px;
  font-size: 1.5em;
  margin: 0;
}

.Section-5 {
  padding: 2em;
  height: fit-content;
}

.section-5-card {
  padding: 2em;
  border: solid rgb(207, 207, 207);
  display: grid;
  grid-template-columns: auto auto;
}

.section-5-icon {
  font-size: 2em;
  margin-top: 1em;
}

.section-5-content {
  padding: 1em;
}

@media screen and (min-width: 1200px) {
}
</style>
