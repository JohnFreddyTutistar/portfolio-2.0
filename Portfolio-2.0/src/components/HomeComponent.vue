<template>
  <div class="father-container">
    <div class="container">
      <div class="container father-logo">
        <div class="logo-section">
          <div class="info-container">
            <h1 class="myname">&lt;John F. Tutistar/&gt;</h1>
            <h5 class="myinfo">
              Welcome to my portfolio, here you will find some of my projects
              and relevant information in case you want to work with me
            </h5>
          </div>
          <div class="logo-container">
            <img
              src="../assets/principal2.jpg"
              alt=""
              width="300"
              class="img-logo"
            />
            <img
              src="../assets/principal.jpg"
              alt=""
              width="300"
              class="img-logo"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="img-section" id="img-section">
      <img src="../assets/img8.png" alt="" class="img-big" />
    </div>
    <div class="about-me-container" id="about">
      <div class="about-me">
        <h3 class="presentation">Hi! I'm John. pleasure to meet you.</h3>
        <p class="parrafo">
          I was born in the city of Pasto, Colombia on February 3, 1994, I am
          currently 28 years old, since I was very young I have been very
          curious about technology and its operation, that is why I studied
          Systems Engineering, I like front-end development, but Lately I'm very
          interested in server-side (back-end) programming. Number one fan of
          learning and the interaction of new technologies. "Never Stop
          Learning".
        </p>
      </div>
      <img src="../assets/door2.png" alt="" width="500" />
    </div>
    <div class="container">
      <div class="container-box">
        <div class="skills border-right">
          <div class="img-logo">
            <img src="../assets/iphone.png" alt="" width="60" />
          </div>
          <b>Mobile Developer</b>
          <div class="espec-box">
            <p>
              I have designed and programmed some applications for android
              devices, prioritizing functionality, stability and usability.
            </p>
          </div>
          <div class="title-skills">
            <b class="title2">Languajes & tools i've learned and uses</b>
          </div>
          <div>
            <p>Java, XML, JavaScript</p>
          </div>
        </div>
        <div class="skills">
          <div class="img-logo">
            <img src="../assets/responsive.png" alt="" width="60" />
          </div>
          <b>Frontend Developer</b>
          <div class="espec-box">
            <p>
              I have designed and programmed some applications for android
              devices, prioritizing functionality, stability and usability.
            </p>
          </div>
          <div class="title-skills">
            <b class="title2">Languajes & tools i've learned and uses</b>
          </div>
          <div>
            <p>HTML, CSS3, JavaScript, VueJS, Angular</p>
          </div>
        </div>
        <div class="skills border-left">
          <div class="img-logo">
            <img src="../assets/database.png" alt="" width="60" />
          </div>
          <b>Backend Developer</b>
          <div class="espec-box">
            <p>
              I have designed and programmed some applications for android
              devices, prioritizing functionality, stability and usability.
            </p>
          </div>
          <div class="title-skills">
            <b class="title2">Languajes & tools i've learned and uses</b>
          </div>
          <div>
            <p>JavaScript, NodeJs, Json, MySQL, PostgreSQL</p>
          </div>
        </div>
      </div>
      <div class="title3-container">
        <div class="title3">
          <h3 class="title-about">Learn more about me</h3>
        </div>
      </div>
      <div class="more-about-me">
        <div class="section-about me">
          Check some of the projects I've done.
          <div class="btn-link">
            <router-link to="/projects" class="btn btn-outline-primary"
              >Check more</router-link
            >
            <!-- <a target="_blank" href="https://github.com/JohnFreddyTutistar" class="btn btn-outline-primary">Check more</a> -->
          </div>
        </div>
        <div class="section-about">
          Or you can download my resume 
          <div class="btn-link">
            <a
              target="_blank"
              href="https://drive.google.com/drive/folders/1JplM5ZK_kDu-2y5D4G3ZiIeMy3rur9Lu?usp=sharing"
              class="btn btn-outline-primary"
              >Get my resume</a
            >
          </div>
        </div>
      </div>
      |
    </div>

    <!-- Footer section -->

    <footer>
      <div class="img-lap">
        <img src="../assets/laptop3.png" alt="" width="200" />
      </div>
      <div class="text">Software Developer</div>
      <div class="wrapper container">
        <ul>
          <li class="instagram">
            <a href="https://www.instagram.com/john_capm/" target="_blank"
              ><i class="fa fa-instagram fa-2x" arial-hidden="true"></i
            ></a>
          </li>
          <li class="github">
            <a href="https://github.com/JohnFreddyTutistar/" target="_blank"
              ><i class="fa fa-github fa-2x" arial-hidden="true"></i
            ></a>
          </li>
          <li class="linkedin">
            <a
              href="https://www.linkedin.com/in/john-freddy-tutistar-99a85b1b3/"
              target="_blank"
              ><i class="fa fa-linkedin fa-2x" arial-hidden="true"></i
            ></a>
          </li>
          <li class="whatsapp">
            <a href="https://wa.me/573105124961" target="_blank"
              ><i class="fa fa-whatsapp fa-2x" arial-hidden="true"></i
            ></a>
          </li>
          
        </ul>
      </div>

      <span
        >Developed By <a href="#">John Tutistar</a> |
        <span class="far fa-copyright"></span> 2022 All rights recerved</span
      >
      <div>Made with <img src="../assets/vue.png" alt="" width="15" /></div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HomeComponent",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Arimo:ital@1&family=Koulen&family=Raleway:wght@100&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Arimo:ital@1&family=Concert+One&family=Kavoon&family=Koulen&family=Raleway:wght@100&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Fredoka+One&family=Montserrat:wght@100&family=Rajdhani:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Fredoka+One&family=Kanit:wght@600&family=Montserrat:wght@100&family=Rajdhani:wght@300&display=swap");

/*Logo section*/
.father-logo {
  margin: flex;
  align-items: center;
}
.logo-section {
  padding-top: 75px;
  height: 600px;
  /* align-items: center; */
}
.info-container {
  display: block;
  width: 800px;
  margin: auto;
}
.myname {
  text-align: center;
  font-family: "Concert One", cursive;
  font-size: 55px;
  color: #333;
}
.myinfo {
  text-align: center;
  margin-top: 30px;
}
.logo-container {
  display: flex;
}
.logo-container img {
  position: absolute;
  transition: opacity 0.1s ease-in-out;
  /* margin: auto; */
  /* left: 42%;  */
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.logo-container img.img-logo:hover {
  opacity: 0;
}
.img-big {
  opacity: 0.8;
  width: 100%;
}
.about-me-container {
  position: relative;
  background: radial-gradient(closest-side, #374b70, #293a5a, #161f30);
  color: #fff;
  height: 500px;
}
.parrafo {
  font-family: "Rajdhani", sans-serif;
  margin-top: 30px;
  font-size: 16px;
}
.about-me {
  text-align: center;
  width: 600px;
  height: 200px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.presentation {
  font-family: "Fredoka One", cursive;
}

/*section 3*/
.container-box {
  display: flex;
  margin: auto;
  margin-top: 40px;
  height: 335px;
  border-bottom: solid 1px rgb(235, 233, 233);
  box-shadow: 0px 10px 10px -6px rgb(218, 214, 214);
  border-radius: 5px;
}

.skills {
  margin: auto;
  text-align: center;
  /* border: solid 1px rgb(233, 231, 231); */
  border-radius: 5px;
  /* border-top-style: none;
        border-bottom-style: none; */
}
.img-logo {
  margin-bottom: 15px;
}
.espec-box {
  margin-top: 15px;
}
.title-skills {
  margin-bottom: 10px;
}
.title2 {
  font-size: 15px;
  color: #3b517a;
}
b {
  font-size: 20px;
}

/*section 4*/

.title3 {
  text-align: center;
  margin-top: 80px;
}
.more-about-me {
  display: flex;
}
.section-about {
  margin: auto;
  text-align: center;
  height: 200px;
  margin-top: 50px;
  margin-bottom: 50px;
  padding-top: 30px;
  font-size: 22px;
  width: 100%;
}
.btn-link {
  margin-top: 50px;
}
.me {
  border-right: solid 1px rgb(219, 218, 218);
}
.title-about {
  font-size: 50px;
  font-family: "Fredoka One", cursive;
  color: #3a4f75;
}

/*footer section*/
/*Social network*/
.wrapper {
  display: flex;
  margin-bottom: 35px;
}
.wrapper ul {
  list-style: none;
  margin: auto;
}
.wrapper ul li {
  width: 55px;
  height: 55px;
  line-height: 60px;
  margin: 0 30px;
  text-align: center;
  cursor: pointer;
  border-radius: 50%;
  border: 2px solid #d8e2dc;
  float: left;
  transition: all 0.5s ease;
}
.wrapper ul li .fa {
  color: #d8e2dc;
  transition: all 0.5s ease;
}
/*#bc2a8d*/
.wrapper ul li:hover.instagram {
  border: 3px solid #dd2a7b;
  box-shadow: 0 0 15px #dd2a7b;
  transition: all 0.5s ease;
}

.wrapper ul li:hover .fa-instagram {
  /* color: linear-gradient(to right, #515bd4, #8134af, #dd2a7b, #feda77, #f58529);
  text-shadow: linear-gradient(to right, #515bd4, #8134af, #dd2a7b, #feda77, #f58529); */
  color: #dd2a7b;
  text-shadow: #dd2a7b;
  transition: all 0.5s ease;
}

.wrapper ul li:hover.github {
  border: 3px solid #fff;
  box-shadow: 0 0 15px #fff;
  transition: all 0.5s ease;
}

.wrapper ul li:hover .fa-github {
  color: #fff;
  text-shadow: #fff;
  transition: all 0.5s ease;
}

.wrapper ul li:hover.linkedin {
  border: 3px solid #0077b5;
  box-shadow: 0 0 15px #0077b5;
  transition: all 0.5s ease;
}

.wrapper ul li:hover .fa-linkedin {
  color: #0077b5;
  text-shadow: #0077b5;
  transition: all 0.5s ease;
}

.wrapper ul li:hover.whatsapp {
  border: 3px solid #4dc247;
  box-shadow: 0 0 15px #4dc247;
  transition: all 0.5s ease;
}

.wrapper ul li:hover .fa-whatsapp {
  color: #4dc247;
  text-shadow: #4dc247;
  transition: all 0.5s ease;
}

@media screen and(max-width: 640px) {
  .wrapper {
    width: 350px;
  }
  .wrapper ul li {
    margin-top: 10px;
  }
  .wrapper ul li.linkedin {
    margin-left: 60px;
  }
}

footer {
  background: radial-gradient(closest-side, #374b70, #293a5a, #161f30);
  padding: 20px 23px;
  color: white;
  text-align: center;
  font-size: 20px;
}
footer span a {
  color: #5dade2;
}
.text {
  margin-bottom: 40px;
}
.img-lap {
  margin-top: 40px;
}
html {
  scroll-behavior: smooth;
}
</style>