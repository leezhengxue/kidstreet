<template>
  <div style="background-color:black">
    <div class="header">
      <div class="header-container">
        <img class="header-logo" src="../assets/logo.png" />
        <h1 class="header-font">
          KID STREET DANCE ACEDEMY
          </h1>
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
        <div class="image-container">
          <h1 class="title-font" >
            Types Of <br/> Hip-Hop Dance
          </h1>
          <img class="images" src="../assets/logo.png" />
        </div>
        <div class="content-container">
          <h2 class="content-title-font">
            Urban Choreography
          </h2>
          <text class="content-font">
            Kpop and Mixture of all dance
          </text>
          <h2 class="content-title-font">
            Break Dancing
          </h2>
          <text class="content-font">
            Toprock, Footwork, Power Moves and Freezes
          </text>
          <h2 class="content-title-font">
            Locking
          </h2>
          <text class="content-font">
            Funky, Happy and Body Movement
          </text>
          <h2 class="content-title-font">
            Popping
          </h2>
          <text class="content-font">
            Robotic, Waving and Body Control
          </text>
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
.header-container{
  display:flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
}
.header-logo{
  margin-left: 80px;
  margin-right: 80px;
  height: 100px;
  width:100px;
}

.header-font{
  color: rgb(245, 168, 172);
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:20px;
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
  height: 100%;

  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin:5%;
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
  height: 100%;
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
.image-container{
  display:flex;
  flex-direction: column;
  margin-left:5rem;
  margin-right:5rem;
  align-items: center;
}
</style>
