<template>
  <section class="section sec2 about active" id="about">
    <div class="main-title">
      <h2>About <span>me</span><span class="bg-text">my stats</span></h2>
    </div>
    <div class="about-container">
      <div class="left-about">
        <h4>Information About me</h4>
        <p>
         Knowledgeable Software Developer adept at creating successful
         application that meet customer needs. Specializing in collaborating
         with customers to gather requirements, produce plans and improve designs for
         usability and functionality. <br/>
         <br/>
         Fully proficient in Vue JS a JavaScript framework,
         Django and Django Rest Framework and CSS for beautiful Layouts and designs.
        </p>
        <div class="btn-con">
          <a href="#" class="main-btn">
            <span class="btn-text">Download CV</span>
            <span class="btn-icon"><i class="fas fa-download"></i></span>
          </a>
        </div>
      </div>
      <div class="right-about">
        <div class="about-item">
          <div class="abt-text">
            <p class="large-text">30+</p>
            <p class="small-text">
              Projects <br />
              Completed
            </p>
          </div>
        </div>
        <div class="about-item">
          <div class="abt-text">
            <p class="large-text">5+</p>
            <p class="small-text">
              Years of <br />
              experience
            </p>
          </div>
        </div>
        <div class="about-item">
          <div class="abt-text">
            <p class="large-text">10+</p>
            <p class="small-text">
              Happy <br />
              Clients
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="about-stats">
      <h4 class="stat-title">My Skills</h4>
      <div class="progress-bars">
        <div class="progress-bar">
          <p class="prog-title">html5</p>
          <div class="progress-con">
            <p class="prog-text">80%</p>
            <div class="progress">
              <span class="html"></span>
            </div>
          </div>
        </div>
        <div class="progress-bar">
          <p class="prog-title">css3</p>
          <div class="progress-con">
            <p class="prog-text">95%</p>
            <div class="progress">
              <span class="css"></span>
            </div>
          </div>
        </div>
        <div class="progress-bar">
          <p class="prog-title">javascript</p>
          <div class="progress-con">
            <p class="prog-text">75%</p>
            <div class="progress">
              <span class="js"></span>
            </div>
          </div>
        </div>
        <div class="progress-bar">
          <p class="prog-title">VueJS</p>
          <div class="progress-con">
            <p class="prog-text">75%</p>
            <div class="progress">
              <span class="react"></span>
            </div>
          </div>
        </div>
        <div class="progress-bar">
          <p class="prog-title">NodeJS</p>
          <div class="progress-con">
            <p class="prog-text">87%</p>
            <div class="progress">
              <span class="node"></span>
            </div>
          </div>
        </div>
        <div class="progress-bar">
          <p class="prog-title">Python</p>
          <div class="progress-con">
            <p class="prog-text">70%</p>
            <div class="progress">
              <span class="python"></span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <h4 class="stat-title">My Timeline</h4>
    <div class="timeline">
      <div class="timeline-item">
        <div class="tl-icon">
          <i class="fas fa-briefcase"></i>
        </div>
        <p class="tl-duration">2021 - Present | Part-Time</p>
        <h5>Sound Engineer<span> - Parklands Baptist Church - EastGate</span></h5>
        <p>
         • Live Sound Monitoring <br>
         • Setup and Set down <br>
         • Stage Management
        </p>
      </div>
      <div class="timeline-item">
        <div class="tl-icon">
          <i class="fas fa-briefcase"></i>
        </div>
        <p class="tl-duration">2021 - present</p>
        <h5>Web Developer<span> - Freelance</span></h5>
        <p>
          • Indepenede Software Developer - Remote Work
        </p>
      </div>
      <div class="timeline-item">
        <div class="tl-icon">
          <i class="fas fa-briefcase"></i>
        </div>
        <p class="tl-duration">2019 - 2021</p>
        <h5>Software Engineer<span> -Mutall Data Mangers</span></h5>
        <p>
          •	Designed, developed and implemented software
          applications for website based on analyzed requirements and understanding of industry technical standards.
        </p>
      </div>
      <div class="timeline-item">
        <div class="tl-icon">
          <i class="fas fa-briefcase"></i>
        </div>
        <p class="tl-duration">2018 - 2019</p>
        <h5>Database Administrator<span> - Eureka Waters Compampay</span></h5>
        <p>
          •	Administered, supported and monitored databases
          by proactively resolving database issues and maintaining servers.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name:'About'
}
</script>


<style lang="scss">
.about-container .left-about p{
    padding-left: 0;
}
</style>
