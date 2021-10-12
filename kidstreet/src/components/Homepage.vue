<template>
  <div style="background-color:black">
    <div class="header">
      <div class="header-container">
        <div class="image-container">
          <img class="header-logo" src="../assets/kidstreet-logo.png" />
        </div>
        <h1 class="header-font">
        KID STREET DANCE ACADEMY
        </h1>
      </div>

      <div class="concept-design">
        <div class="left-border-line"></div>
        <div class="right-border-line">
          <text class="right-border-text">WE DANCE TO EDUCATE</text>
          <div class="progress-scroll-bar"></div>
        </div>
      </div>
    
    </div>
    <div class="content">
      <div class="hero-container">
        <h1 class="hero-font">
          HIP - HOP <br/>
          DANCE <br/>
          CLASS 2021 <br/>
        </h1>
        <img class="images" src="../assets/logo.png" />
      </div>

      <div class="main-container">
        <div class="content-container">
          <h1 class="title-font">
            About Us
          </h1>
          <h2 class="sub-title-font">
            Background
          </h2>
          <text class="content-font">
            Founded in 2019, KID STREET; A professional dance 
            company that focuses on Academy, Performances and 
            Entertainment in dance. KID STREET was fouunded by both
            dancers, Ker Qian and Kah Meng aspiring to influence the
            dance industry in Malaysia 
          </text>
           <h2 class="sub-title-font">
            Business Activity
          </h2>
          <text class="content-font">
            KID STREET has bee actively in collaborate with schools
            and dance academy since. We are looking to expand our 
            platform for the year 2021. We focuses on helping 
            students in their academy by providing knowledgable 
            dance and art class.
          </text>
        </div>
        <div class="image-container">
          <img class="images" src="../assets/logo.png" />
          <img class="images" src="../assets/logo.png" />
        </div>
      </div>

      <div class="main-container">
        <div class="image-container">
          <img class="images" src="../assets/logo.png" />
        </div>
        <div class="content-container">
          <h1 class="title-font">
            What is <br/>Hip-Hop?
          </h1>
          <h2 class="sub-title-font">
            A Brief History
          </h2>
          <text class="content-font">
            Hip-hop now is a highly sought-after and 
            dominant style of dance. It is among the most
            common styles of dance for music vidoes, concerts,
            and dance competitions.
          </text>
        </div>
      </div>

     <div class="main-container">
        <div class="image-container">
          <h1 class="title-font">
            Why <br/>Dancing?
          </h1>
          <img class="images" src="../assets/logo.png" />
        </div>
        <div class="content-container">
          <h2 class="sub-title-font">
            EDUCATION BENEFITS
          </h2>
          <text class="content-font">
            1. Memorzation Skills<br/>
            2. Presentation Skills<br/>
            3. Improve focus Level
          </text>
          <h2 class="sub-title-font">
            HEALTH BENEFITS
          </h2>
          <text class="content-font">
            1. Release Emotional Stress<br/>
            2. Self-Confidence<br/>
            3. Physical Health
          </text>
          <h2 class="sub-title-font">
            SOCIAL BENEFITS
          </h2>
          <text class="content-font">
            1. Communication Level<br/>
            2. Self Expression<br/>
            3. Teamwork
          </text>
        </div>
      </div>
    
      <div class="main-container">
        <div class="image-container long-container"> 
          <h1 class="title-font" >
            Types Of Hip-Hop Dance
          </h1>
          <img class="images" src="../assets/logo.png" />
        </div>
        <div class="content-container">
          <h2 class="sub-title-font-small">
            Urban Choreography
          </h2>
          <text class="content-font-small">
            Kpop and Mixture of all dance
          </text>
          <h2 class="sub-title-font-small">
            Break Dancing
          </h2>
          <text class="content-font-small">
            Toprock, Footwork, Power Moves and Freezes
          </text>
          <h2 class="sub-title-font-small">
            Locking
          </h2>
          <text class="content-font-small">
            Funky, Happy and Body Movement
          </text>
          <h2 class="sub-title-font-small">
            Popping
          </h2>
          <text class="content-font-small">
            Robotic, Waving and Body Control
          </text>
        </div>
      </div>
      

      <div class="main-container">
        <div class="content-container">
          <h1 class="title-font" >
            Why Choose Us?
          </h1>
          <h2 class="sub-title-font-small">
            OUR WORK EXPERIENCE
          </h2>
          <text class="content-font-small">
            Our team has more than 10 years teaching experience.
          </text>
          <h2 class="sub-title-font-small">
            OUR WORK QUALITY
          </h2>
          <text class="content-font-small">
            Our student has successful annually achiece tittles.
          </text>
          <h2 class="sub-title-font-small">
            OUR WORK COMMITMENT
          </h2>
          <text class="content-font-small">
            Our teacher sacrifices personal time to cultivate our student.
          </text>
          <h2 class="sub-title-font-small">
            COST EFFECTIVE
          </h2>
          <text class="content-font-small">
            Robotic, Waving and Body Control
          </text>
        </div>
        <div class="image-container"> 
          <img class="images" src="../assets/logo.png" />
        </div>
      </div>


      <div style="height:150px;">
      </div>
    
    </div>
  </div>
</template>

<script>
export default {
  name: 'Homepage',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  position:fixed;
  width: 100%;
}
.header-container{
  display:flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  padding-left:80px;
  background-color:rgb(0, 0, 0);
}
.header-logo{
  height: 150px;
}
.concept-design{
  display:none;
  /* display:flex; */
  flex-direction: row;
  justify-content: space-between;
  margin: 100px 200px 0 200px;
}
.left-border-line{
  height: calc(100vh - 300px);
  width: 3px;
  background-color: rgb(255, 255, 255);
}
.right-border-line{
  height: calc(100vh - 300px);
  width: 3px;
  background-color: rgb(250, 250, 250);
}
.right-border-text{
  color: rgb(245, 168, 172);
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  font-size:20px;
  writing-mode: vertical-rl;
  /* text-orientation: mixed; */
}
.progress-scroll-bar{
  height: 100px;
  width: 100px;
  background-color: #555;
  border-radius: 50%;
  margin-top: 300px;
}

.header-font{
  color: rgb(245, 168, 172);
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:20px;
  padding-left:50px;
}

.content{
  display:block;
  height:100%;
}
.images{
  height: 100px;
  width:100px;
}

.hero-container{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin:5%;
  margin-top:0 ;
  padding-top:10%;
}
.hero-font{
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:5rem;
  text-align: left;
}

.main-container{
  margin:5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.content-container{
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}
.title-font{
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:5rem;
  text-align: left;
}
.sub-title-font{
  color: rgb(245, 168, 172);
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 2rem;
}
.sub-title-font-small{
   color: rgb(245, 168, 172);
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 2rem;
  margin:0;
}
.content-font{
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  line-height: 3rem;
  font-size:18px;
  width: 45rem;
  text-align: justify;
}
.content-font-small {
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  line-height: 3rem;
  font-size:18px;
  width: 45rem;
  margin-bottom:30px;
}
.image-container{
  display:flex;
  flex-direction: column;
  margin-left:5rem;
  margin-right:5rem;
  align-items: center;
}
.long-container{
  width:400px;
}
@media (max-width: 1024px) {
  .header-font{
    display:none;
}
  .header-container{
   flex-direction: column;
   padding: 0;
 }
  .hero-container{
   flex-direction: column;
 }
  .content-container{
  display: block;
 }
  .main-container{
   flex-direction: column;
 }
  .title-font{
   font-size:60px;
 }
  .long-container{
  width:300px;
}
  .concept-design{
  display:none;
}
}
</style>
