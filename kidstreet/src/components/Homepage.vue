<template>
  <div>
    <div class="header background">
      <img class="header-logo" src="../assets/logo.png" />
      <h1 class="header-font">
        KID STREET DANCE ACEDEMY
        </h1>
    </div>
    <div class="content background">
      <div class="hero-container">
        <h1 class="hero-font">
          HIP - HOP <br/>
          DANCE <br/>
          CLASS 2021 <br/>
        </h1>
        <img class="images" src="../assets/logo.png" />
      </div>
      <div class="about-us-container">
        <div class="content-container">
          <h1 class="title-font">
            About Us
          </h1>
          <text class="content-font">
            Founded in 2019, KID STREET; A professional dance 
            company that focuses on Academy, Performances and 
            Entertainment in dance. KID STREET was fouunded by both
            dancers, Ker Qian and Kah Meng aspiring to influence the
            dance industry in Malaysia 
          </text>
        </div>
        <div class="image-container">
          <img class="images" src="../assets/logo.png" />
          <img class="images" src="../assets/logo.png" />
        </div>
      </div>
      <div class="what-is-hiphop">
        <div class="content-container">
          <h1 class="title-font">
            About Us
          </h1>
          <text class="content-font">
            Founded in 2019, KID STREET; A professional dance 
            company that focuses on Academy, Performances and 
            Entertainment in dance. KID STREET was fouunded by both
            dancers, Ker Qian and Kah Meng aspiring to influence the
            dance industry in Malaysia 
          </text>
        </div>
        <div class="image-container">
          <img class="images" src="../assets/logo.png" />
          <img class="images" src="../assets/logo.png" />
        </div>
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
  height:10rem;
  width:100%;
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
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:20px;
}

.background{
  background-color: black;
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
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.hero-font{
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size:5rem;
  text-align: left;
}

.about-us-container{
  height: 100%;
  width: 100%;
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
}
.content-font{
  color: white;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  line-height: 3rem;
  font-size:20px;
  width:45rem;
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
