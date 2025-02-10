---
title: 'Talks'
heroHeading: 'Talks'
heroSubHeading: ''
heroBackground: '/images/headway-F2KRf_QfCqw-unsplash.jpeg'
tags:
  - "talks"
---

Your can find most of our past talks, and much more, on our <a class="button button-inline" href="https://www.youtube.com/channel/UCUfOPtnJ3RlT7aOWODNvCmQ">Youtube Channel</a>

Themes of the talks:
* &#128202; Big data
* &#128187; Machine Learning
* &#127878; Physics discovery
* &#127758; Modeling
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide/dist/css/splide.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide-extension-video/dist/css/splide-extension-video.min.css">
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide/dist/js/splide.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide-extension-video/dist/js/splide-extension-video.min.js"></script>


<style>
  #video-carousel {
  margin-left: auto;
  margin-right: auto;
  max-width: 1000px; /* Adjust based on your video sizes or preference */

}
.video-wrapper {
  position: relative;
  width: 100%;
  padding-top: 56.25%; /* 16:9 Aspect Ratio */
}

.splide__video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

p {
  word-wrap: break-word; /* Ensures long words can break and wrap onto the next line */
  overflow-wrap: break-word; /* Similar to word-wrap, but with better support */
  white-space: normal; /* Ensures whitespace is handled normally, allowing wrapping */
}


</style>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    var splide = new Splide('#video-carousel', {
      type       : 'loop',
      perPage    : 1,
      rewind     : true,
      width      : '800px', // Adjust as needed
      gap        : '1rem',
      pagination : false,
      autoplay   : false, // Set true if you want autoplay
      pauseOnHover: true,
    });

    splide.mount(window.splide.Extensions);
  });
</script>


<div id="video-carousel" class="splide">
  <div class="splide__track">
    <ul class="splide__list">
      <li class="splide__slide">
        <div class="video-wrapper">
          <iframe class="splide__video" src="https://www.youtube.com/embed/oiIiWwm7iNM?si=SbFdl4Ovoe-9UJc-"></iframe>
        </div>
        <p align="center">
          <strong>Laure Zanna</strong><br>
          <em>Accelerating Discovery in Climate Physics with Machine Learning</em><br>
          Simons foundation Presidential Lecture - February 2024 &#128187; &#127878;
        </p>
      </li>
      <li class="splide__slide">
        <div class="video-wrapper">
          <iframe class="splide__video"  src="https://www.youtube.com/embed/PbcFWN5dtJc?si=Vb8WLHSDMhEIFyfn"></iframe>></iframe>
        </div>
        <p align="center">
          <strong>Paul O'Gorman</strong><br>
          <em>MIT's BC3 and Climate and Weather Extremes</em><br>
          ICCS Cross VESRI Journal  - February 2024 &#128187; &#127878;
        </p>
      </li>
      <li class="splide__slide">
        <div class="video-wrapper">
          <iframe class="splide__video" src="https://www.youtube.com/embed/EfGNoRIzq4M?si=xeZUktdxbfTTl5-B"></iframe>
        </div>
        <p align="center">
          <strong>Will Chapman</strong><br>
          <em>Advancing Weather and Climate Prediction with Data Driven Methods</em><br>
          Paul G. Allen School - February 2024
        </p>
      </li>
      <li class="splide__slide">
        <div class="video-wrapper">
          <iframe class="splide__video" src="https://www.youtube.com/embed/1esiBpicss4?si=-ZnmyagFdZnxr6u6"></iframe>
        </div>
        <p align="center">
          <strong>Laure Zanna</strong><br>
          <em>A New Generation of Global Climate Models Augmented by AI</em><br>
          Distinguished Seminar Series in Computational Science and Engineering - October 2023 &#128187; &#127878;
        </p>
      </li>
    </ul>
  </div>
</div>




<h1 style="font-family: Helvetica, serif; text-align: center;">Recent talks</h1>
<hr style="width: 100%; margin-top: 20px; border-color: #333;">

## *2024*
<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/4jRVAK2yEj4');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/4jRVAK2yEj4/1.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em>Harnessing AI to confront environmental challenges </em><br>
   AI for Climate and Nature Spring Convening - Bezos Earth Fund - October  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/NknILybndKo');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/NknILybndKo/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Julia Simpson</strong><br>
    <em>Improving Parameterizations of Heat + Momentum Air-Sea Fluxes </em><br>
   LEAP Research Updates - September  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/KEmvuuyzglQ?t=5');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/KEmvuuyzglQ/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em> (Keynote) AI-augmented climate Simulators and Emulators</em><br>
   OMDP/COMMODORE Workshop - September  &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/iwK74hhwWIQ');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/iwK74hhwWIQ/2.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Marika Holland</strong><br>
    <em> The influence of historical forcing uncertainty on simulated Arctic change.</em><br>
   IARPC Collaborations - August  &#128202; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/_1iEl_nOk7A');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/_1iEl_nOk7A/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna, Sara Shamekh, Pierre Gentine</strong><br>
    <em>Navigating the Academic Search Process </em><br>
   LEAP Professional Development Series
  </p>
</div>


<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/embed/PbcFWN5dtJc?si=Vb8WLHSDMhEIFyfn');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/PbcFWN5dtJc/1.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Paul O'Gorman</strong><br>
    <em>AMIT's BC3 and Climate and Weather Extremes</em><br>
    ICCS Cross VESRI Journal  - February  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/embed/EfGNoRIzq4M?si=xeZUktdxbfTTl5-B');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/EfGNoRIzq4M/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Will Chapman</strong><br>
    <em>Advancing Weather and Climate Prediction with Data Driven Methods</em><br>
   Paul G. Allen School - February  &#128187; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/embed/oiIiWwm7iNM?si=SbFdl4Ovoe-9UJc-');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/oiIiWwm7iNM/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Accelerating Discovery in Climate Physics with Machine Learning</em><br>
   Simons foundation Presidential Lecture - February  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/gna8I-GMTKk');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/gna8I-GMTKk/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em>AI in Climate Science: From Emulation to New Discoveries </em><br>
   Simons foundation Presidential Lecture - February  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://youtu.be/JiCTG0CwkKg');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/JiCTG0CwkKg/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em>Machine learning across scales to improve climate models: from emulation to discoveries </em><br>
   Mathematics of Climate - February  &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=FEmuUlVvTuw');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/FEmuUlVvTuw/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Aakash Sane</strong><br>
    <em>Parameterizing Vertical Mixing Coefficients in the Ocean Surface Boundary Layer Using Neural Networks</em><br>
   CESM OMWG - February  &#128187; &#127878;
  </p>
</div>


## *2023*

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=AIgTy033-A4');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/AIgTy033-A4/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Paul O'Gorman</strong><br>
    <em>Improving climate models using machine learning</em><br>
    MIT Generative AI Week - November  &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/embed/1esiBpicss4?si=-ZnmyagFdZnxr6u6');">
        <a href="#" class="fill-div">
        <img src="http://img.youtube.com/vi/1esiBpicss4/maxresdefault.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>A New Generation of Global Climate Models Augmented by AI</em><br>
   Distinguished Seminar Series in Computational Science and Engineering - October 2023  &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=6lqkFuLI0ms');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/6lqkFuLI0ms/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Ocean and Atmosphere Dynamics</em><br>
   Climatematch academy - July  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=GVaFjoiB4I4&t=10519s');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/GVaFjoiB4I4/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pavel Perezhogin</strong><br>
    <em>Machine-Learned parameterizations of mesoscale eddies in MOM6 ocean model: convolutional neural network and symbolic regression</em><br>
   28th Annual CESM Workshop - June  &#128187; &#127758;
  </p>
</div>



<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=Tya7d0tfpb0&t=1743s');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/Tya7d0tfpb0/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Fabrizio Falasca</strong><br>
    <em>Exploting the nonstationarity of coastal sea level probability distributions</em><br>
   NOAA-CVP Webinar Series 2023 - April  &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=X3EQg1_-xXU');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/X3EQg1_-xXU/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pavel Perezhogin</strong><br>
    <em>Generative data-driven approaches for stochastic subgrid parameterizations in an idealized ocean model </em><br>
    NEMO working group on Machine-Learning - April &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=SRDb7X30DYc');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/SRDb7X30DYc/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Transforming Climate Modeling with AI: hype or Reality?</em><br>
    UN AI for Good - March &#128187; &#127758;
  </p>
</div>



## *2022*

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=bKtuRjxWNYE');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/bKtuRjxWNYE/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Janni Yuval</strong><br>
    <em>Neural-network parameterization of subgrid momentum transport learned from a high-resolution simulation </em><br>
    23rd AMS Conference on Atmospheric and Oceanic Fluid Dynamics - June &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=U7RY218Vp0E');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/U7RY218Vp0E/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Aakash Sane</strong><br>
    <em>Parameterizing Vertical Turbulent Mixing Coefficients In The Ocean Surface Boundary Layer Using Neural Networks </em><br> February &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=fcMyaTDp2C0');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/fcMyaTDp2C0/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Lorenzo Zampieri</strong><br>
    <em>On the design strategy of subgrid parameterizations in modern sea ice models</em><br>
    Arctic Model Parameterization Development - December 22nd &#128187; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=hcuahoLpDog');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/hcuahoLpDog/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Ryan Abernathey</strong><br>
    <em>Climate Science and AI in Big Tech</em><br>
    Climate Change AI Webinar Series - December 15th  &#128202; &#128187; <br>
    <em>NOTE</em>: You can find all the talks and posters our members gave at the AGU Fall meeting in our December 2022 <a href="https://mailchi.mp/169d6f0c61f9/m2lines-december-newsletter-agu-special">newsletter</a>.
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em>Physics to Machine Learning and Machine Learning Back to Physics</em><br>
    Columbia Center of AI Technology - December 7th &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
    <div onclick="window.open('https://www.youtube.com/watch?v=beO9Zcpa570');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/beO9Zcpa570/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong> and Steven Brunton<br>
    <em>Machine learning in fluid dynamics and climate physics</em><br>
    Nature Reviews Physics + Alan Turing Institute - October 5th &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=3y00LhyACV4');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/3y00LhyACV4/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Machine Learning for Ocean and Climate Modeling: advances, challenges and outlook</em><br>
    LEAP Seminar - September 22nd &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>AI for Climate Physics</em><br>
    Hammers and Nails - August 4th &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Plenary talk</em><br>
    SIAM conference on Mathematics for Planet Earth - July 13th &#128187; &#127878; &#127758; <br>
    <em>NOTE</em>: More info at this <a href="https://www.siam.org/conferences/cm/conference/mpe22?_ga=2.193046573.1207615065.1657569935-11076920.1657569935">website</a>.
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=q_gGIL-Kvgs&list=PLfdKzSc-V-WAYHR8sPfddkCbnwnfuBb1A&t=11550s');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/q_gGIL-Kvgs/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Joint plenary talk with Galen McKinley on M²LInES and LEAP</em><br>
    2022 CESM Workshop - June 13th &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=qRSXSkjvFcE');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/qRSXSkjvFcE/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Machine Learning for Mesoscale Closures in Ocean Models</em><br>
    NCAR Mesoscale & Microscale Meteorology Laboratory - June 2nd &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em>Can Artificial Intelligence Help Us Better Project Climate Change?</em><br>
    The Artificial Intelligence for Good Group - May 4th &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden;margin-right: 10px;">
      <div onclick="window.open('https://iclr.cc/virtual/2022/workshop/4550');">
        <a href="#" class="fill-div">
        <img src="/images/talks/AR_22.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Andrew Ross</strong><br>
    Panel discussion on the future of model interpretability at the ICLR workshop on AI for Earth and Space Science - April 29th <br>
    <em>NOTE</em>: You can find the panel on the top main video at 7:49:25 <a href="https://iclr.cc/virtual/2022/workshop/4550"> here </a>.
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden;margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=ydiCxUliaG0');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/ydiCxUliaG0/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Online implementation of Machine Learning Eddy Parameterizations in a Hierarchy of Ocean Models</em><br>
    Ocean Sciences Meeting - March 4th &#128187; &#127878; &#127758;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=M3ypY9vPRpQ');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/M3ypY9vPRpQ/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Mitch Bushuk</strong><br>
    <em>Mechanisms of Regional Arctic Sea Ice Predictability in Dynamical Seasonal Forecast Systems</em><br>
    Ocean Sciences Meeting - March 3rd &#127878;
  </p>
</div>

 <div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Ryan Abernathey</strong><br>
    <em>OpenOceanCloud: A New Approach to Ocean Data and Computing</em><br>
    Ocean Sciences Meeting - March 3rd &#128202;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=3SYWCtuzrKk');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/3SYWCtuzrKk/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Lorenzo Zampieri</strong><br>
    <em>A machine learning correction model for the warm bias over Arctic sea ice in atmospheric reanalyses</em><br>
    Ocean Sciences Meeting - March 1st &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=gTOzmE7_-mU');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/gTOzmE7_-mU/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Dhruv Balwada</strong><br>
    <em>Tracer Ventilation, Stirring, and Variability in the Antarctic Circumpolar Current</em><br>
    Ocean Sciences Meeting - March 1st &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=pCdiWFwICr0');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/pCdiWFwICr0/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Brandon Reichl</strong><br>
    <em>A potential energy analysis of ocean surface mixed layers</em><br>
    Ocean Sciences Meeting - February 28th
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden;margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=fIIAqrFOUSM');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/fIIAqrFOUSM/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Andrew Ross</strong><br>
    <em>Evaluating machine learning parameterizations of ocean subgrid forcing</em><br>
    Ocean Sciences Meeting - February 28th &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden;margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=OKZl9IjWSHA');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/OKZl9IjWSHA/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Dhruv Balwada</strong><br>
    <em>Direct observational estimate of the dual kinetic energy cascade and its seasonality at the surface ocean from surface drifters</em><br>
    Ocean Sciences Meeting - February 28th &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://vimeo.com/670782104');">
        <a href="#" class="fill-div">
        <img src="/images/talks/RA_22.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Ryan Abernathey</strong><br>
    <em>OpenOceanCloud - Transforming oceanography with a new approach to data and computing</em><br>
    Ocean Data Conference - February 15th &#128202;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=X3EQg1_-xXU');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/X3EQg1_-xXU/0.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Ryan Abernathey</strong><br>
    <em> Workshop AI for Earth Sciences</em><br>
    The National Academies Board on Atmospheric Sciences and Climate - February 10th &#128202; &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="">
        <a href="#" class="fill-div">
        <img src="/images/newlogo.png" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Pierre Gentine</strong><br>
    <em> Workshop AI for Earth Sciences</em><br>
    The National Academies Board on Atmospheric Sciences and Climate - February 7th &#128187; &#127878;
  </p>
</div>

<div style="display: flex; align-items: center;">
  <div style="width: 100px; height: 100px; overflow: hidden; margin-right: 10px;">
      <div onclick="window.open('https://www.youtube.com/watch?v=JB7LpUJlxc0');">
        <a href="#" class="fill-div">
        <img src="https://img.youtube.com/vi/JB7LpUJlxc0/1.jpg" alt="Video Preview">
        </a>
      </div>
  </div>
  <p>
    <strong>Laure Zanna</strong><br>
    <em>Data-driven turbulence closures for ocean and climate models: advances and challenges</em><br>
    UW Data-driven methods in science and engineering seminar - February 4th &#128187; &#127878;
  </p>
</div>
