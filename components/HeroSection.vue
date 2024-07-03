<template>
  <!-- Link -->
  
    <title>Portofolio Zidan</title>
    <link rel="stylesheet" href="/responsipemrogramanweb/assets/main.css" />
    <link
      rel="stylesheet"
      href="https://unpkg.com/boxicons@latest/css/boxicons.min.css"
    />
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
 
  <!-- Header Section -->
  <header class="header">
      <nav class="nav bd_grid">
        <div>
          <a href="#" class="nav_logo">#ZiyaaPookie</a>
        </div>

        <div class="nav_menu" id="nav_menu">
          <ul class="nav_list">
            <li class="nav_items">
              <a href="#home" class="nav_link active">Home</a>
            </li>
            <li class="nav_items">
              <a href="#about" class="nav_link active">About</a>
            </li>
            <li class="nav_items">
              <a href="#skills" class="nav_link active">Skills</a>
            </li>
            
          </ul>
        </div>

        
      </nav>
    </header>
   
      
 
      <main class="main">
      <!-- HOME SECTION -->
      <section class="home bd_grid" id="home">
        <div class="home_data" oke="fade-down">
          <h1 class="home_title">
            Hay Teman Teman <br />Saya<span class="home_title-color"> Zidan Dhiya</span
            ><br />Fullstack Developer &#128513;
          </h1>
          <a class="button">Amikom University</a>
        </div>

        <div class="home_social">
          <a href="#" class="home_social-icon" oke="fade-down"
            ><i class="bx bxl-facebook-circle"></i
          ></a>
          <a
            href="#"
            class="home_social-icon"
            oke="fade-down"
            oke-delay="250"
            ><i class="bx bxl-instagram"></i
          ></a>
          <a
            href="#"
            class="home_social-icon"
            oke="fade-down"
            oke-delay="300"
            ><i class="bx bxl-twitter"></i
          ></a>
          <a
            href="#"
            class="home_social-icon"
            oke="fade-down"
            oke-delay="350"
            ><i class="bx bxl-github"></i
          ></a>
        </div>

        <div class="home_img">
          <img src="https://i.ibb.co.com/LR5T5fk/523-5237005-developing-full-stack-developer-png-transparent-png-removebg-preview.png" alt="">
        </div>
      </section>

      <!-- ABOUT SECTION -->
      <section class="about section" id="about">
        <h2 class="section-title" oke="fade-down">About</h2>

        <div class="about_container bd_grid">
          <div class="about_image">
            <img src="https://cdn.dribbble.com/users/2317423/screenshots/19792320/media/0ba6a3cf8bd68580017a54aef2e7caa5.jpg?resize=400x0" alt="">
          </div>

          <div>
            <h2
              class="about_subtitle"
              oke="fade-down"
              oke-delay="350"
            >
              Saya Zidan Dhiya &#128075;
            </h2>
            <p class="about_text" oke="fade-down" oke-delay="450">
              Sebagai mahasiswa Amikom, keseharianku diwarnai dengan padatnya kegiatan perkuliahan dan tugas. Namun, di sela-sela kesibukan itu, aku selalu menyempatkan diri untuk menyalurkan hobi yang paling aku sukai, yaitu memancing.
            </p>
          </div>
        </div>
      </section>

      <!-- SKILLS SECTION -->
      <section class="skills section" id="skills">
        <h2 class="section-title" oke="fade-down">Skills</h2>

        <div class="skills_container bd_grid">
          <div>
            <h2
              class="skills_subtitle"
              oke="fade-down"
              oke-delay="250"
            >
              Skill &#128020;
            </h2>
            <p class="skills_text" oke="fade-down" oke-delay="350">
              "Setiap hari adalah kesempatan baru untuk menjadi versi terbaik dari dirimu sendiri." - Brian Tracy
            </p>
            <!-- SKILLS HTML -->
            <div class="skills_data" oke="fade-right">
              <div class="skills_name">
                <i class="bx bxl-html5 skill_icon"></i>
                <span class="skill_name">Html5</span>
              </div>

              <div><span class="skill_percentage">95%</span></div>

              <div class="skill_bar skill_html"></div>
            </div>

            <!-- SKILLS css -->
            <div class="skills_data" oke="fade-right" oke-delay="250">
              <div class="skills_name">
                <i class="bx bxl-css3 skill_icon"></i>
                <span class="skill_name">CSS3</span>
              </div>

              <div><span class="skill_percentage">85%</span></div>

              <div class="skill_bar skill_css"></div>
            </div>

            <!-- SKILLS JS -->
            <div class="skills_data" oke="fade-right" oke-delay="250">
              <div class="skills_name">
                <i class="bx bxl-javascript skill_icon"></i>
                <span class="skill_name">JS</span>
              </div>

              <div><span class="skill_percentage">75%</span></div>

              <div class="skill_bar skill_js"></div>
            </div>

            <!-- SKILLS UI/UX -->
            <div class="skills_data" oke="fade-right" oke-delay="250">
              <div class="skills_name">
                <i class="bx bxs-paint skill_icon"></i>
                <span class="skill_name">UI / UX</span>
              </div>

              <div><span class="skill_percentage">85%</span></div>

              <div class="skill_bar skill_ui"></div>
            </div>
          </div>

          <img src="https://i.ibb.co.com/nbqDv80/8e231e0aa5c7acb23e299ae2f4889fbe-removebg-preview.png" alt="">
        </div>
      </section>

    

      <!-- Footer Section -->
      <footer class="footer">
        <p class="footer_title" oke="fade-down">@ZiyaaPookie</p>

       
       

        <p oke="fade-down" oke-delay="650">
          &#169; 2024 copyright all right reserved
        </p>
      </footer>
    </main>

</template>

<script>

export default {
  name: 'HeroSection',
  head: {
    script: [
      { src: '~/assets/main.js' }
    ]
  },
  head: {
    script: [
      {
        src: 'https://unpkg.com/aos@2.3.1/dist/aos.js',
        callback: () => {
          AOS.init({
            duration: 1200,
            once: false,
          })
        }
      }
    ]
  },
  
}
</script>
<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;
  background: #f5f5f5;
}
</style>
