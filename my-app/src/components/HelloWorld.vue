<template>
  <div class="hello">
    <div class="Section-1">
      <div class="info-1">
        <h1 class="title-1">YOUR HIRING REIMAGINED</h1>
        <p class="content-1">
          One-stop hiring platform for every purpose-driven organization
        </p>
      </div>
      <button class="GetStartedbtn">Get Started for Free</button>
    </div>
    <div class="Section-2">
      <div class="overlap-1">what</div>
      <div class="overlap-2"></div>
    </div>
    <div>
      <h1>who</h1>
    </div>
    <div>
      <h1>what</h1>
    </div>
    <div>
      <h1>why</h1>
    </div>
  </div>
</template>

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
  background-color: yellow;
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
  background-color: pink;
  width: 80em;
  height: 15em;
  margin-top: -3em;
  margin-left: 5em;
  margin-right: 5em;
  border-radius: 20px;
  z-index: 2;
}

.overlap-2 {
  position: absolute;
  background-color: aquamarine;
  width: 84em;
  height: 12em;
  margin-top: -1.7em;
  margin-left: 3em;
  margin-right: 3em;
  border-radius: 10px;
  z-index: 1;
}
</style>
