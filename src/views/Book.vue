<template>
  <!--Album photo-->

  <div class="slider-scroll">
    <img alt="ju et sam" id="slide-scroll1" src="" />
    <img alt="sam 1" id="slide-scroll2" src="" />
    <img alt="sam 2" id="slide-scroll3" src="" />
    <img alt="sam 3" id="slide-scroll4" src="" />
    <img alt="sam 4" id="slide-scroll5" src="" />
    <img alt="sam 5" id="slide-scroll6" src="" />
    <img alt="sam 5" id="slide-scroll7" src="" />
    <img alt="sam 5" id="slide-scroll8" src="" />
    <img alt="sam 5" id="slide-scroll9" src="" />
    <img alt="sam 5" id="slide-scroll10" src="" />
  </div>
  <ul class="ancre">
    <li>
      <a href="#slide-scroll1">1</a>
    </li>
    <li>
      <a href="#slide-scroll2">2</a>
    </li>
    <li>
      <a href="#slide-scroll3">3</a>
    </li>
    <li>
      <a href="#slide-scroll4">4</a>
    </li>
    <li>
      <a href="#slide-scroll5">5</a>
    </li>
    <li>
      <a href="#slide-scroll6">6</a>
    </li>
    <li>
      <a href="#slide-scroll7">7</a>
    </li>
    <li>
      <a href="#slide-scroll8">8</a>
    </li>
    <li>
      <a href="#slide-scroll9">9</a>
    </li>
    <li>
      <a href="#slide-scroll10">10</a>
    </li>
  </ul>
</template>

<style scoped>
/*Album enfants*/
.albumEnfants {
  text-align: center;
  font-family: "Ramaraja", serif;
}

.slider-scroll {
  width: 650px;
  border: 5px solid black;
  max-width: 100%;
  max-height: 500px;
  margin: 2rem auto;
  display: flex;
  overflow-x: hidden;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
  -webkit-overflow-scrolling: touch;
}
.slider-scroll img {
  scroll-snap-align: center;
  min-width: 100%;
  border-radius: 5px;
}
.ancre {
  margin: 1rem auto;
  display: flex;
  justify-content: center;
}
.ancre li {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 30px;
  height: 30px;
  background: #404040;
  border-radius: 50%;
}
.ancre li a {
  color: white;
}
.ancre li:not(:last-child) {
  margin-right: 30px;
}
.ancre li a:hover {
  opacity: 0.5;
}
/*Album chiens*/
.Chiens {
  text-align: center;
  font-family: "Ramaraja", serif;
}
.slider-scroll2 {
  width: 650px;
  border: 5px solid black;
  max-width: 100%;
  max-height: 500px;
  margin: 2rem auto;
  display: flex;
  overflow-x: hidden;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
  -webkit-overflow-scrolling: touch;
}
.slider-scroll2 img {
  scroll-snap-align: center;
  min-width: 100%;
  border-radius: 5px;
}
.ancre2 {
  margin: 1rem auto;
  display: flex;
  justify-content: center;
}
.ancre2 li {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 30px;
  height: 30px;
  background: #404040;
  border-radius: 50%;
}
.ancre2 li a {
  color: white;
}
.ancre2 li:not(:last-child) {
  margin-right: 30px;
}
.ancre2 li a:hover {
  opacity: 0.5;
}
/*Album auto moto*/
.AutoMoto {
  text-align: center;
  font-family: "Ramaraja", serif;
}
.slider-scroll3 {
  width: 650px;
  border: 5px solid black;
  max-width: 100%;
  max-height: 500px;
  margin: 2rem auto;
  display: flex;
  overflow-x: hidden;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
  -webkit-overflow-scrolling: touch;
}
.slider-scroll3 img {
  scroll-snap-align: center;
  min-width: 100%;
  border-radius: 5px;
}
.ancre3 {
  margin: 1rem auto;
  display: flex;
  justify-content: center;
}
.ancre3 li {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 30px;
  height: 30px;
  background: #404040;
  border-radius: 50%;
}
.ancre3 li a {
  color: white;
}
.ancre3 li:not(:last-child) {
  margin-right: 30px;
}
.ancre3 li a:hover {
  opacity: 0.5;
}
</style>
