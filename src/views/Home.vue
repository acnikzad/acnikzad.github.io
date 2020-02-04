<template>
  <div class="home">
    <head>
      <link rel="stylesheet" href="https://cdn.rawgit.com/konpa/devicon/df6431e323547add1b4cf45992913f15286456d3/devicon.min.css">
    </head>
    <body>
    <!-- Header -->
      <section class="banner style1 fullscreen onload-image-fade-in">
        <div class="content">
          <h1>Aria Nikzad</h1>
          <h4 style="color:red;">Full Stack Developer</h4><h4>Business Manager</h4><h4>Entrepreneur</h4>
        </div>
        <div class="image">
          <img src="https://i.imgur.com/GlVmbR9.jpg" alt="Alternate text"  width="300"/>
        </div>
      </section>

      <!-- Statement -->
      <section class="spotlight style1 orient-right onload-image-fade-in">
        <div class="content">
          <h4>"Working hard for something we don’t care about is called stress;<br>working hard for something we love is called passion."</h4>
          <i style="color:red;">- Simon Sinek</i>
        </div>
        <div class="image">
          <img src="https://i.imgur.com/QqbzOqV.jpg" alt="Alternate text"  width="300"/>
        </div>
      </section>

      <section class="spotlight style1 fullscreen onscroll-image-fade-in">
        <div class="content">
          <h2>Welcome!</h2>
          <h5>Thank you for taking the time to learn about my professional and personal life. The bulk of my career has primarily consisted of business management and entrepreneurship. Most recently, I have fulfilled a longtime goal of mine to learn fullstack development.</h5>
          <h5>Outside of the professional world, you can find me mountain biking, hiking, camping, or at a newly discovered brewery with my dog.</h5>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
        </div>
        <div class="image" onscroll-fade-in>
          <img src="https://i.imgur.com/bviAolZ.jpg" alt="Alternate text" width="700"/>
        </div>
      </section>
      <br>
      <center>
        <h2>Education</h2>
      </center>
      <div class="items style1 big (optional modifiers)">
        <section>
          <center>
            <a href="https://www.sfsu.edu/" class="image">
              <img src="https://d3n8a8pro7vhmx.cloudfront.net/intentionalendowments/pages/526/attachments/original/1528992324/SFState_Logo_H_rgb_2in.png?1528992324" alt="Alternate text" height="100"/>
            </a>
            <p>Business Marketing</p>
          </center>
        </section>
        <section>

            <ul>
              <li>Marketing Research</li>
              <li>Marketing Management</li>
              <li>International Marketing Strategy</li>
              <li>Digital Marketing</li>
              <li>Business Communications</li>
              <li>Micro and Macro Economics</li>
              <li>Business Finance</li>
              <li>Marketing Theory</li>
              <li>Retail Management</li>
              <li>Retail Management</li>
              <li>Operations Management</li>
              <li>Business Calculus</li>
            </ul>

        </section>
        <section>
          <center>
            <a href="https://anyonecanlearntocode.com/" class="image">
              <img src="https://acltc-blog-pics.s3.amazonaws.com/uploads/blog_pic/blog_pic/24/ActualizeFinalwhiteBgLogo.png" alt="Alternate text" height="100"/>
            </a>
            <p>Software Development</p>
          </center>
        </section>
        <section>
          <ul>
            <li>Ruby on Rails</li>
            <li>Javascript</li>
            <li>GitHub</li>
            <li>RESTful APIs</li>
            <li>PostgreSQL</li>
            <li>CSS</li>
            <li>Vue.js</li>
            <li>HTML</li>
            <li>Object Oriented Programming</li>
          </ul>
        </section>
      </div>

      <section class="banner style1 halfscreen onload-content-fade-down onscroll-image-fade-in orient-left">
        <div class="content">
          <h2>BlockHound</h2>
          <hr style="color:red;">
          <h4>Inspired by the neighborhood app NextDoor, I wanted to build an app that helps track your dogs movements. Everyday NextDoor is riddled with posts about losts dogs with vague descriptions and locations. I have created an app that can track your dogs movements, alerts you if your dog escapes, and can notify nearby neighbors with your dogs description and real-time location.
          </h4>
          <div class="dev-icons">
            <center>
              <i id="prog-icon" class="devicon-ruby-plain colored"></i>
              <i id="prog-icon" class="devicon-rails-plain"></i>
              <i id="prog-icon" class="devicon-git-plain"></i>
              <i id="prog-icon" class="devicon-vuejs-plain"></i>
              <i id="prog-icon" class="devicon-html5-plain"></i>
              <i id="prog-icon" class="devicon-css3-plain"></i>
              <i id="prog-icon" class="devicon-javascript-plain"></i>
              <i id="prog-icon" class="devicon-bootstrap-plain"></i>
            </center>
          </div>
          <br>
          <a href="https://acnikzad.herokuapp.com/blockhound" class="button">Learn More</a>

          <br>
        </div>
        <div class="image">
          <img src="https://i.imgur.com/1zdoZSV.png" alt="Alternate text" />
        </div>
      </section>
      <section class="banner style1 onload-content-fade-down orient-right">
        <div class="content">
          <h2>Corsega Eyewear</h2>
          <hr style="color:red;">
          <h4>Following my entrepreneurial spirit, I wanted to build a company. I would constantly break or lose expensive sunglasses. I believed stylish, quality sunglasses with polarized lenses should be affordable. So in 2014, after a year of research and development, I launched my own sunglasses company: Corsega Eyewear. 
          </h4>
          <center>
            <i class="devicon-photoshop-plain"></i>
            <i class="devicon-illustrator-plain"></i>
            <i class="devicon-google-plain"></i>
          </center>
          <h3 style="color:red;">#CorsegaEyewear</h3>
          <a href="https://acnikzad.herokuapp.com/corsega" class="button">Learn More</a>
        </div>
        <div class="image">
          <img src="https://i.imgur.com/suE8nPM.jpg" alt="Alternate text" />
        </div>
      </section>
      <!-- gallery -->
      <section class="wrapper style1 align-center">
        <div class="gallery style1 onscroll-fade-in lightbox large">
          <div class="inner" style="overflow: hidden;">
            <article>
              <a href="(full image URL)" class="image">
                <img src="https://i.imgur.com/H9gGPSz.jpg" alt="Alternate text" />
              </a>
              <div class="caption">
                Raindrops
              </div>
            </article>
            <article>
              <a href="(full image URL)" class="image">
                <img src="https://i.imgur.com/jh9QPmt.jpg" alt="Alternate text" />
              </a>
              <div class="caption">
                Jungles
              </div>
            </article>
            <article>
              <a href="(full image URL)" class="image">
                <img src="https://i.imgur.com/LlAlhkA.jpg" alt="Alternate text" />
              </a>
              <div class="caption">
                Atlantics
              </div>
            </article>
            <article>
              <a href="(full image URL)" class="image">
                <img src="https://i.imgur.com/bSgn2It.jpg" alt="Alternate text" />
              </a>
              <div class="caption">
                Skyclads
              </div>
            </article>
          </div>
        </div>
      </section>
  <!-- Items -->

    </body>
  </div>
</template>

<style>
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    HelloWorld
  }
};
</script>
