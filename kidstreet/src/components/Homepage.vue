<template>
  <div style="background-color:#181818">
    <div class="header">
      <div class="header-container">
        <div class="image-container">
          <a href="#home"
            ><img class="header-logo" src="../assets/kidstreet-logo.png"
          /></a>
        </div>
        <div class="nav-bar">
          <ul>
            <li><a href="#about-us">ABOUT US</a></li>
            <li><a href="#achievement">ACHIEVEMENT</a></li>
            <li><a href="#team">TEAM</a></li>
            <li><a href="#partner">PARTNER</a></li>
            <li><a href="#review">REVIEW</a></li>
            <li><a href="#contact-us">CONTACT US</a></li>
          </ul>
        </div>
      </div>

      <div class="concept-design">
        <div class="left-border-line">
          <text class="left-border-text">KID STREET DANCE ACADEMY</text>
        </div>
        <div class="right-border-line">
          <text class="right-border-text">WE DANCE TO EDUCATE</text>
          <div class="progress-scroll-bar">
            <div id="circle">
              <span id="circle-value"> </span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="content">
      <div class="hero-container" id="home">
        <h1 class="hero-font">
          HIP - HOP <br />
          DANCE <br />
          CLASS 2021 <br />
        </h1>
        <img class="images_1" src="../assets/hero_image.png" />
      </div>

      <div class="main-container">
        <div class="content-container padding-top" id="about-us">
          <h1
            class="title-font mobile-title-font"
            style="margin:20px 0 20px 0;"
          >
            About Us
          </h1>
          <h2 class="sub-title-font mobile-sub-title-font">
            Background
          </h2>
          <text class="content-font content-font-width mobile-content-font">
            Founded in 2019, KID STREET; A professional dance company that
            focuses on Academy, Performances and Entertainment in dance. KID
            STREET was fouunded by both dancers, Ker Qian and Kah Meng aspiring
            to influence the dance industry in Malaysia
          </text>
          <div class="mobile-images-display">
            <img class="images_2" src="../assets/about_us_1.png" />
          </div>
          <h2 class="sub-title-font mobile-sub-title-font">
            Business Activity
          </h2>
          <text class="content-font content-font-width mobile-content-font">
            KID STREET has bee actively in collaborate with schools and dance
            academy since. We are looking to expand our platform for the year
            2021. We focuses on helping students in their academy by providing
            knowledgable dance and art class.
          </text>
          <div class="mobile-images-display">
            <img class="images_2" src="../assets/about_us_2.png" />
          </div>
        </div>
        <div class="image-container mobile-images-hide">
          <img class="images_2" src="../assets/about_us_1.png" />
          <img class="images_2" src="../assets/about_us_2.png" />
        </div>
      </div>

      <div class="main-container padding-top-bottom">
        <div class="image-container mobile-images-hide">
          <img class="images_3" src="../assets/what_is_hiphop.jpg" />
        </div>
        <div class="content-container">
          <h1 class="title-font mobile-title-font">What is <br />Hip-Hop?</h1>
          <div class="mobile-images-display">
            <img class="images_3" src="../assets/what_is_hiphop.jpg" />
          </div>
          <h2 class="sub-title-font">
            A Brief History
          </h2>
          <text class="content-font content-font-width mobile-content-font">
            Hip-hop now is a highly sought-after and dominant style of dance. It
            is among the most common styles of dance for music vidoes, concerts,
            and dance competitions.
          </text>
        </div>
      </div>

      <div class="main-container">
        <div class="image-container padding-right-50">
          <h1 class="title-font mobile-title-font">
            Why <br />
            Dancing?
          </h1>
          <img class="images_4" src="../assets/why_dance.png" />
        </div>
        <div class="content-container padding-top">
          <h2 class="sub-title-font">
            EDUCATION BENEFITS
          </h2>
          <text class="content-font-small rm-margin-bottom">
            1. Memorzation Skills<br />
            2. Presentation Skills<br />
            3. Improve focus Level
          </text>
          <h2 class="sub-title-font">
            HEALTH BENEFITS
          </h2>
          <text class="content-font-small rm-margin-bottom">
            1. Release Emotional Stress<br />
            2. Self-Confidence<br />
            3. Physical Health
          </text>
          <h2 class="sub-title-font">
            SOCIAL BENEFITS
          </h2>
          <text class="content-font-small rm-margin-bottom">
            1. Communication Level<br />
            2. Self Expression<br />
            3. Teamwork
          </text>
        </div>
      </div>

      <div class="main-container">
        <div class="image-container">
          <h1 class="title-font mobile-title-font">
            Types Of <br />
            Hip-Hop Dance
          </h1>
          <!-- <img class="images_5" src="../assets/logo.png" /> -->

          <video class="videos" width="600" controls>
            <source src="../assets/dance-video.mp4" type="video/mp4" />
          </video>
        </div>
        <div class="content-container padding-top">
          <div class="image-content">
            <div class="circle"><div class="circle-number">01</div></div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin special-font-color">
                Urban Choreography
              </h2>
              <text class="content-font-small">
                Kpop and Mixture of all dance
              </text>
            </div>
          </div>

          <div class="image-content">
            <div class="circle"><div class="circle-number">02</div></div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin special-font-color">
                Break Dancing
              </h2>
              <text class="content-font-small">
                Toprock, Footwork, Power Moves and Freezes
              </text>
            </div>
          </div>
          <div class="image-content">
            <div class="circle"><div class="circle-number">03</div></div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin special-font-color">
                Locking
              </h2>
              <text class="content-font-small">
                Funky, Happy and Body Movement
              </text>
            </div>
          </div>
          <div class="image-content">
            <div class="circle"><div class="circle-number">04</div></div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin special-font-color">
                Popping
              </h2>
              <text class="content-font-small">
                Robotic, Waving and Body Control
              </text>
            </div>
          </div>
        </div>
      </div>

      <div class="main-container">
        <div class="content-container content-container-wrapper">
          <h1 class="title-font mobile-title-font">
            Why Choose Us?
          </h1>
          <div class="mobile-images-display">
            <img class="images_6" src="../assets/why_choose_us.png" />
          </div>
          <h2 class="sub-title-font-rm-margin">
            OUR WORK EXPERIENCE
          </h2>
          <text class="content-font-small rm-margin-bottom">
            Our team has more than 10 years teaching experience.
          </text>
          <h2 class="sub-title-font-rm-margin">
            OUR WORK QUALITY
          </h2>
          <text class="content-font-small rm-margin-bottom">
            Our student has successful annually achiece tittles.
          </text>
          <h2 class="sub-title-font-rm-margin">
            OUR WORK COMMITMENT
          </h2>
          <text class="content-font-small rm-margin-bottom">
            Our teacher sacrifices personal time to cultivate our student.
          </text>
          <h2 class="sub-title-font-rm-margin">
            COST EFFECTIVE
          </h2>
          <text class="content-font-small rm-margin-bottom">
            Robotic, Waving and Body Control
          </text>
        </div>
        <div class="image-container mobile-images-hide">
          <img class="images_6" src="../assets/why_choose_us.png" />
        </div>
      </div>

      <div class="main-container" id="achievement">
        <div>
          <h1 class="title-font mobile-title-font">
            Our <br />
            Achievement
          </h1>
        </div>
        <div class="content-container padding-top">
          <div class="image-content image-content-margin">
            <div class="image-container">
              <img class="images_7" src="../assets/achievement_1.jpg" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                JOM MENARI
              </h2>
              <text class="content-font">
                CHAMPION 2019
              </text>
            </div>
          </div>
          <div class="image-content image-content-margin">
            <div class="image-container">
              <img class="images_8" src="../assets/achievement_2.png" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                MY TOWN FESTIVAL
              </h2>
              <text class="content-font">
                CHAMPION 2019
              </text>
            </div>
          </div>
          <div class="image-content image-content-margin">
            <div class="image-container">
              <img class="images_9" src="../assets/achievement_3.png" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                ASTRO BATTLE GROUND
              </h2>
              <text class="content-font">
                CHAMPION 2016
              </text>
            </div>
          </div>
        </div>
      </div>

      <div class="main-container" id="team">
        <div
          class="content-container padding-top content-padding-right-50 mobile-order-2"
        >
          <div class="image-content image-content-margin">
            <div class="image-container">
              <img class="images_10" src="../assets/teacher-ker-qian.png" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                TEACHER KER QIAN
              </h2>
              <text class="content-font-small">
                Academy Founder
              </text>
            </div>
          </div>
          <div class="image-content image-content-margin">
            <div class="image-container">
              <img class="images_11" src="../assets/teacher-xf.png" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                TEACHER XF
              </h2>
              <text class="content-font-small">
                Senior Dance Instructor
              </text>
            </div>
          </div>
          <!-- <div class="image-content">
            <div class="image-container">
              <img class="images_12" src="../assets/logo.png" />
            </div>
            <div class="content-container">
              <h2 class="sub-title-font-rm-margin">
                TEACHER MC
              </h2>
              <text class="content-font-small">
                Senior Dance Advisor
              </text>
            </div>
          </div> -->
        </div>
        <div>
          <h1
            class="title-font long-container mobile-order-1 mobile-title-font"
          >
            The Acedemy Team
          </h1>
        </div>
      </div>

      <div class="main-container" id="partner">
        <div class="main-container-column padding-top" style="margin:0">
          <div>
            <h1 class="title-font mobile-title-font">
              Our School Partner
            </h1>
          </div>
          <div class="main-container" style="justify-content: space-between;">
            <div class="image-content">
              <div class="image-container rm-image-container-margin">
                <img class="images-school-1" src="../assets/hanzkidz.png" />
                <h2 class="sub-title-font rm-margin" style="color:white">
                  HANZKIDZ
                </h2>
              </div>
              <div class="image-container rm-image-container-margin">
                <img
                  class="images-school-2"
                  src="../assets/sjkc-tai-thung.png"
                />
                <h2 class="sub-title-font rm-margin" style="color:white">
                  SJK(C) TAI THUNG
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="main-container">
        <div class="main-container-column">
          <h1 class="title-font mobile-title-font padding-right-400">
            Types of Collaborations
          </h1>
          <div class="main-container main-container-rm-margin">
            <div class="content-container">
              <h2 class="sub-title-font">
                Option 1
              </h2>
              <text class="content-font">
                - 20% commision for school.<br />
                - All student must participare to dance class. <br />
                - Complimentary performace to all school event. <br />
                - Train students to achieve competitions tittles.<br />
              </text>
              <h2 class="sub-title-font">
                Option 2
              </h2>
              <text class="content-font">
                - 10% commision for school.<br />
                - All class activity for student to participate.<br />
                - Complimentary performace to all school event.<br />
                - Train students to achieve competitions tittles.<br />
              </text>
            </div>
            <div class="image-container">
              <img class="images_13" src="../assets/collaboration.png" />
            </div>
          </div>
        </div>
      </div>

      <div class="main-container" id="review">
        <div class="main-container-column padding-top" style="margin:0">
          <div>
            <h1 class="title-font mobile-title-font">
              Parents Review
            </h1>
          </div>
          <div class="main-container" style="justify-content: space-between;">
            <div class="image-content">
              <div class="image-container rm-image-container-margin">
                <img class="images" src="../assets/logo.png" />
                <h2
                  class="content-font rm-margin"
                  style="color:white; text-align:left"
                >
                  - KEITH MOK'S PARENTS
                </h2>
              </div>
              <div class="image-container rm-image-container-margin">
                <img class="images" src="../assets/logo.png" />
                <h2
                  class="content-font rm-margin"
                  style="color:white; text-align:left;"
                >
                  - SHEELA LEE'S PARENTS
                </h2>
              </div>
              <div class="image-container rm-image-container-margin">
                <img class="images" src="../assets/logo.png" />
                <h2
                  class="content-font rm-margin"
                  style="color:white; text-align:left;"
                >
                  - XIN LYNN'S PARENTS
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="main-container">
        <div
          class="main-container-column padding-top padding-bottom"
          id="review"
          style="margin:0;"
        >
          <h1 class="title-font mobile-title-font">
            Parents Review
          </h1>
          <div class="main-container" style="justify-content: space-between;">
            <div class="image-content">
              <div
                class="image-container rm-image-container-margin review-container"
              >
                <img class="images" src="../assets/logo.png" />
                <h2 class="content-font rm-margin" style="color:white">
                  - KEITH MOK'S PARENTS
                </h2>
              </div>
              <div
                class="image-container rm-image-container-margin review-container"
              >
                <img class="images" src="../assets/logo.png" />
                <h2 class="content-font rm-margin" style="color:white">
                  - SHEELA LEE'S PARENTS
                </h2>
              </div>
              <div
                class="image-container rm-image-container-margin review-container"
              >
                <img class="images" src="../assets/logo.png" />
                <h2 class="content-font rm-margin" style="color:white">
                  - XIN LYNN'S PARENTS
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div> -->

      <div class="main-container" id="contact-us">
        <div class="image-container padding-right-50 mobile-images-hide">
          <img class="images_14" src="../assets/thank_you.png" />
        </div>
        <div class="content-container">
          <h1 class="title-font mobile-title-font" style="color:#d848bd">
            CONTACT US
          </h1>
          <div class="mobile-images-display">
            <img class="images_14" src="../assets/thank_you.png" />
          </div>
          <text class="content-font">
            Tel: <br />
            016-3377808 (Kah Meng)<br />
            016-9647770 (Ker Qian)<br /><br />
            Email:<br />
            kidstreet@gmail.com
          </text>
        </div>
      </div>
      <div style="height:150px;"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Homepage",
  setup() {
    let scrollPercentage = () => {
      let scrollProgress = document.getElementById("circle");
      let progressValue = document.getElementById("circle-value");
      let pos = document.documentElement.scrollTop;
      let calcHeight =
        document.documentElement.scrollHeight -
        document.documentElement.clientHeight;
      let scrollValue = Math.round((pos * 100) / calcHeight);

      /* console.log(scrollValue); */

      scrollProgress.style.background = `conic-gradient(#FFFFFF ${scrollValue}%, #575757 ${scrollValue}%)`;
      progressValue.textContent = `${scrollValue}%`;
    };

    window.onscroll = scrollPercentage;
    window.onload = scrollPercentage;

    // var skills = document.getElementsByClassName('red')[0];
    // var skills1 = document.getElementsByClassName('blue')[0];
    // var skills2 = document.getElementsByClassName('yellow')[0];
    // var skills3 = document.getElementsByClassName('orange')[0];

    // var aboutus = document.getElementById('about-us');
    // var achievement = document.getElementById('achievement');
    // var team = document.getElementById('team');
    // var partner = document.getElementById('partner');
    // var review = document.getElementById('review');
    // var contactus = document.getElementById('contact-us');

    //     window.onscroll = function() {
    //   // Get boundries of your div (top, bottom, left, right)
    //   var position = aboutus.getBoundingClientRect();
    //   var position2 = achievement.getBoundingClientRect();
    //   var position3 = team.getBoundingClientRect();
    //   var position4 = partner.getBoundingClientRect();
    //   var position5 = review.getBoundingClientRect();
    //   var position6 = contactus.getBoundingClientRect();

    // console.log(position, position2, position3, position4, position5, position6)
    //   // Check your divs position and add/remove your desired class
    //    if (position1.top) {
    //     skills.style.color = "red";

    //      skills1.style.color = "white";
    //       skills2.style.color = "white";
    //        skills3.style.color = "white";
    //   }
    //   if (position1.top < -200) {
    //     skills.style.color = "white";
    //      skills1.style.color = "blue";
    //       skills2.style.color = "white";
    //        skills3.style.color = "white";

    // 	}
    //   if (position1.top < -500) {
    //     skills.style.color = "white";
    //      skills1.style.color = "white";
    //       skills2.style.color = "yellow";
    //        skills3.style.color = "white";
    // 	}
    //   if (position1.top < -800) {
    //      skills.style.color = "white";
    //      skills1.style.color = "white";
    //       skills2.style.color = "white";
    //        skills3.style.color = "orange";
    // 	}

    // }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  position: fixed;
  width: 100%;
}
.header-container {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  padding-left: 80px;
  background-color: #131313;
}
.header-logo {
  height: 110px;
  margin: 5px;
}

.nav-bar {
  flex: 1;
  text-align: right;
  margin-right: 100px;
}
.nav-bar ul li {
  list-style: none;
  display: inline-block;
  padding: 8px 20px;
  position: relative;
}
.nav-bar ul li a {
  color: white;
  font-family: "Roboto", sans-serif;
  text-decoration: none;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 19px;
}

.concept-design {
  display: none;
  /* display: flex; */
  flex-direction: row;
  justify-content: space-between;
  margin: 50px 150px 0 150px;
}
.left-border-line {
  height: calc(100vh - 100px);
  width: 2px;
  background-color: rgb(255, 255, 255);
  margin-top: 150px;
}
.left-border-text {
  color: white;
  font-family: "Roboto", sans-serif;
  position: absolute;
  left: 100px;
  bottom: 250px;
  font-weight: 100;
  font-size: 20px;
  writing-mode: vertical-rl;
  transform: rotate(180deg);
  /* text-orientation: mixed; */
}
.right-border-line {
  height: calc(100vh - 500px);
  width: 2px;
  background-color: rgb(250, 250, 250);
}
.right-border-text {
  color: #f6921e;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  font-size: 20px;
  writing-mode: vertical-rl;
  /* text-orientation: mixed; */
  margin-left: 15px;
}

.progress-scroll-bar {
  margin-top: 400px;
  position: absolute;
  right: 150px;
  bottom: 350px;
}
#circle {
  height: 90px;
  width: 90px;
  border-radius: 50%;
  background-color: #000000;
  position: fixed;
  display: grid;
  place-items: center;
  box-shadow: 0 0 30px #d848bd;
}

#circle-value {
  display: block;
  height: calc(100% - 5px);
  width: calc(100% - 5px);
  background-color: #ffffff;
  border-radius: 50%;
  display: grid;
  place-items: center;
  font-weight: 500;
  font-family: "Roboto", sans-serif;
  font-size: 15px;
  color: white;
  background-color: #3a3a3a;
}

.header-font {
  color: #f6921e;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 20px;
  padding-left: 50px;
}

.content {
  display: block;
  height: 100%;
}

.images_1 {
  height: 750px;
  box-shadow: 20px 20px 0 0, 20px 20px 0 2px rgb(148, 148, 148);
}
.images_2 {
  height: 250px;
  box-shadow: 20px 20px 0 0, 20px 20px 0 2px rgb(148, 148, 148);
  margin-top: 150px;
}
.images_3 {
  height: 500px;
  box-shadow: 20px 20px 0 0, 20px 20px 0 2px rgb(148, 148, 148);
}
.images_4 {
  height: 370px;
  box-shadow: 40px 60px 0 0, 40px 60px 0 2px rgb(148, 148, 148);
}
.padding-right-50 {
  padding-right: 50px;
}
.images_6 {
  margin-top: 120px;
  height: 450px;
  box-shadow: 40px 60px 0 0, 40px 60px 0 2px rgb(148, 148, 148);
}
.images_7 {
  height: 220px;
  box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
}
.images_8 {
  height: 200px;
  box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
}
.images_9 {
  height: 200px;
  box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
}
.images_10 {
  height: 223px;
  border: 5px solid transparent;
  border-color: white;
}
.images_11 {
  height: 225px;
  border: 5px solid transparent;
  border-color: white;
}
.images_13 {
  height: 500px;
  box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
}
.images_14 {
  height: 300px;
  box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
}
.images-school-1 {
  height: 260px;
  border-radius: 20px;
}
.images-school-2 {
  height: 260px;
  border-radius: 20px;
}
.hero-container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin: 5%;
  margin-top: 0;
  padding-top: 140px;
}
.hero-font {
  color: #d848bd;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 5rem;
  text-align: left;
}

.main-container {
  margin: 5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.main-container-rm-margin {
  margin: 0;
}
.padding-top-bottom {
  padding: 70px 0 100px 0;
}
.padding-top {
  padding-top: 150px;
  padding-bottom: 100px;
}

.main-container-column {
  margin: 5%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.content-container {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}
.content-container-wrapper {
  width: 35rem;
}
.content-padding-right-50 {
  padding-right: 50px;
}

.title-font {
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 5rem;
  text-align: left;
}
.padding-right-400 {
  padding-right: 400px;
}

.sub-title-font {
  color: #d848bd;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 2rem;
  width: max-content;
}
.font-color-white {
  color: white;
}
.sub-title-font-rm-margin {
  color: #d848bd;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  font-size: 2rem;
  margin: 0;
}

.content-font {
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 3px;
  line-height: 2.5rem;
  font-size: 20px;
  text-align: justify;
}
.content-font-width {
  width: 600px;
}
.content-font-small {
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 2px;
  line-height: 3rem;
  font-size: 18px;
  margin-bottom: 50px;
}
.rm-margin-bottom {
  margin: 0;
}
.image-container {
  display: flex;
  flex-direction: column;
  margin-left: 2rem;
  margin-right: 2rem;
  align-items: center;
}
/* .image-wrapper::before {
  position: absolute;
  top: -5%;
  left: -15%;
  width: 100%;
  height: 100%;
  border: 4px solid #ffffff;
  content: "";
} */
.image-wrapper {
  display: inline-block;
  position: relative;
}
/* remove image-wrapper so that it wont overlap header */

.long-container {
  width: 400px;
}
.image-content {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
}
.image-content-margin {
  margin-top: 50px;
}
.special-font-color {
  color: white;
}
.circle {
  height: 60px;
  width: 60px;
  border-radius: 50%;
  background: linear-gradient(
    225deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(235, 0, 139, 1) 0%,
    rgba(239, 51, 101, 1) 51%,
    rgba(246, 146, 30, 1) 100%
  );
  margin-right: 20px;
  margin-top: 5px;
  place-items: center;
  display: grid;
}
.circle-number {
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: 100;
  letter-spacing: 5px;
  line-height: 3rem;
  font-size: 20px;
}
.review-container {
  width: 400px;
}
.mobile-images-display {
  display: none;
}

@media (max-width: 1440px) {
  .progress-scroll-bar {
    margin-top: 200px;
  }
  #circle {
    height: 75px;
    width: 75px;
  }
  .title-font {
    font-size: 3rem;
  }

  .content-font {
    font-size: 18px;
    letter-spacing: 2px;
    line-height: 2rem;
  }
  .content-font-width {
    width: 400px;
  }
  .content-font-small {
    font-size: 15px;
    line-height: 2rem;
  }
  .content-padding-right-50 {
    padding-right: 0px;
  }
  .sub-title-font {
    font-size: 26px;
  }
  .sub-title-font-rm-margin {
    font-size: 26px;
  }
  .content-container-wrapper {
    width: 28rem;
  }
  .images_1 {
    height: 650px;
    box-shadow: 20px 20px 0 0, 20px 20px 0 2px rgb(148, 148, 148);
  }
  .images_2 {
    height: 200px;
    box-shadow: 20px 20px 0 0, 20px 20px 0 2px rgb(148, 148, 148);
    margin-top: 100px;
  }
  .images_3 {
    height: 350px;
    box-shadow: 10px 10px 0 0, 10px 10px 0 1px rgb(148, 148, 148);
  }
  .images_4 {
    height: 300px;
    box-shadow: 30px 40px 0 0, 30px 40px 0 2px rgb(148, 148, 148);
  }
  .images_6 {
    margin-top: 120px;
    height: 350px;
    box-shadow: 40px 60px 0 0, 40px 60px 0 2px rgb(148, 148, 148);
  }
  .images_7 {
    height: 190px;
    box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
  }
  .images_8 {
    height: 170px;
    box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
  }
  .images_9 {
    height: 170px;
    box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
  }
  .images_10 {
    height: 178px;
  }
  .images_11 {
    height: 180px;
  }
  .images_13 {
    height: 350px;
    box-shadow: 15px 15px 0 0, 15px 15px 0 2px rgb(148, 148, 148);
  }
}

@media (max-width: 1024px) {
  .nav-bar {
    display: none;
  }
  .header-font {
    display: none;
  }
  .header-container {
    flex-direction: column;
    padding: 0;
  }
  .header-logo {
    height: 90px;
    margin: 5px;
  }
  .hero-container {
    flex-direction: column;
    padding-top: 80px;
    padding-bottom: 100px;
  }
  .hero-font {
    font-size: 3rem;
  }
  .content-container {
    display: block;
    width: 300px;
  }
  .main-container {
    flex-direction: column;
  }
  .title-font {
    font-size: 60px;
  }
  .sub-title-font {
    font-size: 20px;
    margin-top: 50px;
  }
  .long-container {
    width: 300px;
  }
  .image-content {
    flex-direction: column;
    align-items: center;
    width: 300px;
  }
  .content-container-wrapper {
    width: 18rem;
  }
  .mobile-content-font {
    letter-spacing: 1.5px;
    font-size: 14px;
  }
  .content-font-small {
    margin-bottom: 50px;
  }
  .mobile-title-font {
    font-size: 38px;
  }
  .sub-title-font-rm-margin {
    font-size: 24px;
    margin-top: 30px;
  }
  .rm-margin {
    margin: 0;
  }
  .rm-image-container-margin {
    margin: 0;
  }
  .padding-top {
    padding-top: 0;
  }
  .circle {
    display: none;
  }
  .image-content-margin {
    margin: 0;
  }
  .padding-right-400 {
    padding-right: 0;
  }
  .images {
    height: 100px;
    width: 100px;
  }
  .images_1 {
    height: 350px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_2 {
    height: 160px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
    margin-top: 20px;
  }
  .images_3 {
    height: 220px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_4 {
    height: 170px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .padding-right-50 {
    padding-right: 0px;
  }
  .images_6 {
    margin-top: 0;
    margin-bottom: 40px;
    height: 190px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_7 {
    height: 210px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_8 {
    height: 190px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_9 {
    height: 190px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .images_13 {
    height: 210px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
    margin-top: 30px;
  }
  .images_14 {
    height: 160px;
    border: 5px solid transparent;
    border-image: linear-gradient(45deg, rgb(235, 0, 139), rgb(246, 146, 30)) 1;
    box-shadow: none;
  }
  .review-container {
    width: auto;
  }
  .videos {
    width: 300px;
  }
  .mobile-images-display {
    display: block;
  }
  .mobile-images-hide {
    display: none;
  }
  .mobile-order-1 {
    order: 1;
  }
  .mobile-order-2 {
    order: 2;
  }
  .special-font-color {
    color: #f6921e;
  }
}
@media (max-width: 768px) {
  .concept-design {
    display: none;
  }
  .images-school-1 {
    height: 200px;
  }
  .images-school-2 {
    height: 200px;
  }
}
</style>
