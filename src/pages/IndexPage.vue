<template>
  <q-page class="column items-center justify-evenly page q-pa-xl">
    <div class="title">
      We make creative media that
      <div style="">
        adds value
      </div>
    </div>
    <div class="row q-pa-xl justify-center" style="gap: 40px">
      <div class="row col-3 no-wrap card">
        <div class="col-5 column">
          <q-img src="~assets/1-1.png" class="col-6"></q-img>
          <q-img src="~assets/1-2.png" class="col-6"></q-img>
        </div>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Photography</div>
          <ul class="card--list full-width">
            <li>Drone Photography</li>
            <li>Interiors</li>
            <li>Exteriors / Architectural</li>
          </ul>
          <div class="card--paragraph">
            Every photograph we produce finds the beauty in your property while serving as a profitable asset.
          </div>
        </div>
      </div>
      <div class="row col-3 no-wrap card">
        <q-img src="~assets/2.png" class="col-5"></q-img>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Virtual Staging</div>
          <div class="card--paragraph q-mt-md">
            Our staging will help you sell the potential of your space.
            <br>
            We can work off of our own photography or photos you provide.
          </div>
        </div>
      </div>
      <div class="row col-3 no-wrap card">
        <q-img src="~assets/3.png" class="col-5"></q-img>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Renderings</div>
          <ul class="card--list full-width">
            <li>Interiors</li>
            <li>Exteriors</li>
          </ul>
          <div class="card--paragraph">
            Renderings are the gold standard in pre-construction marketing.
          </div>
        </div>
      </div>
      <div class="row col-3 no-wrap card">
        <q-img src="~assets/4.png" class="col-5"></q-img>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Photography</div>
          <ul class="card--list full-width">
            <li>Matterport</li>
            <li>Video Walkthroughs</li>
          </ul>
          <div class="card--paragraph">
            Give your audience the ability to explore your property without requiring in-person travel.
          </div>
        </div>
      </div>
      <div class="row col-3 no-wrap card">
        <q-img src="~assets/5.png" class="col-5"></q-img>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Floor Plans</div>
          <ul class="card--list full-width">
            <li>On-site Measure</li>
            <li>2D Floor Plans</li>
            <li>3D Floor Plans</li>
          </ul>
          <div class="card--paragraph">
            We produce laser-precise floor plans faster than any other service.
          </div>
        </div>
      </div>
      <div class="row col-3 no-wrap card">
        <q-img src="~assets/6.png" class="col-5"></q-img>
        <div class="column items-center q-pa-md q-pt-lg">
          <div class="card--title">Video</div>
          <ul class="card--list full-width">
            <li>Drone Cinematogprahy</li>
            <li>Interiors</li>
            <li>Exteriors / Architectural</li>
          </ul>
          <div class="card--paragraph">
            Video content has higher engagement and will help your property stand out online.
          </div>
        </div>
      </div>
    </div>
    <q-btn class="button" flat color="white">
      <template #default>
        <div class="button--text">
          GET STARTED
        </div>
      </template>
    </q-btn>
  </q-page>
</template>

<script setup lang="ts">

</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');

.card {
  border-radius: 8px;
  background-color: white;
  max-width: 437.5px;
  overflow: hidden;
  height: 335px;

  &--img {
    width: 183.5px;
  }

  &--title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 32px;
    color: #353844;
  }

  &--paragraph {
    font-family: 'Nunito Sans';
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 24px;
    color: #353844;
  }

  &--list {
    list-style: none;
    margin-left: 0;
    padding: 0.5em 0 0 1em;
    margin: 12px 2em;
    font-family: 'Nunito Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 15px;
    line-height: 26px;

    & li::before {
      content: "\2022";
      color: #D2AD81;
      font-weight: bold;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }
  }
}

.page {
  background-color: #E5E5E5;
}

.title {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 56px;
  line-height: 55px;
  color: #1B264F;
  text-align: center;

  >div {
    color: #506BCA;
  }
}

.button {
  background: #1B264F;
  border-radius: 12px;
  width: 315px;
  height: 60px;

  &--text {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 17px;
  }
}
</style>