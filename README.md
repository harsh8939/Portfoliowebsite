# Portfoliowebsite
Here it is my Created an online shopping website with Java as the backend language. Implemented user authentication, product listing, and shopping cart functionalities. Utilized React.js for the frontend to enhance the user experience.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <Meta http-equiv="X-UA-Comptible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PORFOLIO WEBSITE</title>
    <link href="css/style.css" rel="stylesheet" />

</head>
<body>
    <header class="header">
        <img src="data:image/jpeg;base64,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" alt="OUR MAIN LOGO" class="logo" />
        <nav class="navbar">
            <ul class="navbar-list">
                <li><a href="#" class="navbar-link home-link">Home</a></li>
                <li><a href="#" class="navbar-link home-link">Home</a></li>
                <li><a class="navbar-link service-link" href="#">Services</a></li>
                <li><a class="navbar-link portfolio-link" href="#">Portfolio</a></li>
                <li>
                    <a class="navbar-link contact-link" href="#">contact</a>
                </li>
            </ul>
        </nav>
    </header>
         <!-- ======================================== 
          Our Main Hero Section Start  
    ========================================  -->
    <main>
        <section class="section-hero section">
          <div  class="container grid  grid-two-column">
        <div class="section-hero-data">
          <p class="hero-top-data"> this is me</p>
          <h1 class="hero-heading">FRONTEND DEVELOPER </h1>
          <p class="hero-para">
            I'm HARSH KORI. I am hTML & CSS AND OTHER JAVASCRIPT ALSO.
            CORE JAVA -🌟||&||🌟-DSA
            ||competitive programming
           
          </p>
        </div>
       <!-- hero section right side  -->
       <div class="section-hero-image">
        <picture>
          <source srcset="images/hero.webp" type="image/webp" />
          <source srcset="images/hero-min.jpg" type="image/jpg" />
          <img
                src="file:///C:/Users/ADMIN/Downloads/WhatsApp%20Image%202023-08-03%20at%207.03.51%20AM.jpeg"
            alt="this is me HARSH KORI"
            class="hero-img"
          />
        </picture>
      </div>
    </div>
  </section>
</main>
<!-- ======================================== 
      Our Bio-Data Section Start  
========================================  -->

<section class="section-biodata section">
  <div class="container grid grid-two-column">
    <div class="bio-image">
      <img src="file:///C:/Users/ADMIN/Downloads/WhatsApp%20Image%202023-08-03%20at%207.03.51%20AM.jpeg" alt="my bio data image" />
    </div>
    <!-- bio right side data  -->
    <div class="bio-data">
      <h2 class="common-heading">my bio-data</h2>
      <p>
        Highly motivated and skilled Computer Science graduate with a passion
        for frontend development programming. Equipped with a strong
        foundation in Core Java, Data Structures and Algorithms, and
        PostgreSQL, I am seeking an opportunity to leverage my skills and
        contribute to innovative projects in a dynamic and collaborative
        environment.
      </p>
      <br />
      <p>
        Awarded "Best Computer ScienceProject" for the Frontend development
        project during college's annual tech fest.
      </p>
      <div class="bio-data-stats">
        <div class="bio-stats">
          <h3>Design</h3>
          <div class="bio-progress-bar">
            <span>80%</span>
          </div>
        </div>
        <div class="bio-stats">
          <h3>HTML</h3>
          <div class="bio-progress-bar bio-progress-2">
            <span>99%</span>
          </div>
        </div>
        <div class="bio-stats">
          <h3>CSS</h3>
          <div class="bio-progress-bar bio-progress-3">
            <span>90%</span>
          </div>
        </div>
        <div class="bio-stats">
          <h3>JavaScript</h3>
          <div class="bio-progress-bar bio-progress-4">
            <span>85%</span>
          </div>
        </div>
        <div class="bio-stats">
          <h3>MERN</h3>
          <div class="bio-progress-bar bio-progress-5">
            <span>70%</span>
          </div>
        </div>
      </div>
      <div class="bio-data-btn">
        <a href="#" class="btn">Download CV</a>
      </div>
    </div>
  </div>
</section>

<!-- ======================================== 
      Our portfolio Section Start  
========================================  -->
<section class="section section-portfolio" id="portfolio-section">
  <div class="container">
    <h2 class="common-heading">Latest Works</h2>
    <p>
        Consistently maintained a top position in the Data Structures and Algorithms
        course throughout the academic tenureCreated an online shopping website with Java as the backend language.
        Implemented user authentication, product listing, and shopping cart
        functionalities.
        Utilized React.js for the frontend to enhance the user experience.
    </p>
  </div>

  <div class="p-btns">
    <div class="btn p-btn" data-btn-num="1">Website</div>
    <div class="btn p-btn" data-btn-num="2">Youtube</div>
    <div class="btn p-btn" data-btn-num="3">Design</div>
  </div>

  <div class="container grid grid-three-column portfolio-images">
    <div class="img-overlay p-btn--1">
      <img src="images/folio/1.jpg" alt="my works" />
      <div class="overlay">
        <a
          href="http://charcounter.thapaonlineclass.com/"
          target="_thapa"
          class="common-heading"
          >Project 1</a
        >
      </div>
    </div>

    <div class="img-overlay p-btn--3">
      <img src="images/folio/4.jpg" alt="my works" />
      <div class="overlay">
        <a
          href="http://charcounter.thapaonlineclass.com/"
          target="_thapa"
          class="common-heading"
          >Project 2
        </a>
      </div>
    </div>

    <div class="img-overlay p-btn--1">
      <img src="images/folio/3.jpg" alt="portfolio images " />
      <div class="overlay">
        <a href="" target="_blank" class="common-heading">Project 3</a>
      </div>
    </div>
    <div class="img-overlay p-btn--1 p-btn--2">
      <img src="images/folio/4.jpg" alt="portfolio images " />
      <div class="overlay">
        <a href="" target="_blank" class="common-heading">Project 4</a>
      </div>
    </div>
    <div class="img-overlay p-btn--2">
      <img src="images/folio/5.jpg" alt="portfolio images " />
      <div class="overlay">
        <a href="" target="_blank" class="common-heading">Project 5</a>
      </div>
    </div>
    <div class="img-overlay p-btn--1">
      <img src="images/folio/1.jpg" alt="portfolio images " />
      <div class="overlay">
        <a href="" target="_blank" class="common-heading">Project 6</a>
      </div>
    </div>
  </div>
</section>
<!-- ======================================== 
      Our work counter Section Start  
========================================  -->

<section class="section section-work-data">
  <div class="container grid grid-four-column">
    <div>
      <h2 class="counter-numbers" data-number="2000">0+</h2>
      <p>project completed</p>
    </div>
    <div>
      <h2 class="counter-numbers" data-number="6000">0+</h2>
      <p>Happy Clients</p>
    </div>
    <div>
      <h2 class="counter-numbers" data-number="5000">0+</h2>
      <p>cups of coffee</p>
    </div>
    <div>
      <h2 class="counter-numbers" data-number="3000">0+</h2>
      <p>real professionals</p>
    </div>
  </div>
</section>
<!-- ======================================== 
      Our Services  Section Start  
========================================  -->

<section class="section section-services">
  <div class="container">
    <h2 class="common-heading">Services Offers</h2>
    <p>
      The development of the Windows operating system, which hasrew the
company from a small startup to one of the largest and most successful
companies in the world.
    </p>
  </div>

  <!-- services offers card  -->
  <div class="container grid grid-three-column">
    <div class="service-box">
      <ion-icon name="desktop-sharp" class="service-icon"></ion-icon>
      <h3>Web Design</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>

    <div class="service-box">
      <ion-icon name="logo-react" class="service-icon"></ion-icon>
      <h3>web development</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>

    <div class="service-box">
      <!-- <ion-icon name="camera-sharp" class="service-icon"></ion-icon> -->
      <ion-icon name="camera-outline" class="service-icon"></ion-icon>
      <h3>photography</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>

    <div class="service-box">
      <ion-icon name="phone-portrait-sharp" class="service-icon"></ion-icon>
      <h3>Mobile Apps</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>

    <div class="service-box">
      <ion-icon name="globe-sharp" class="service-icon"></ion-icon>
      <h3>apps interface</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>

    <div class="service-box">
      <ion-icon name="images-sharp" class="service-icon"></ion-icon>
      <h3>graphic design</h3>
      <p>
        “It is not because things are difficult that we do not dare; it is
        because we do not dare that they are difficult.”
      </p>
    </div>
  </div>
</section>

<!-- ======================================== 
      Our Resume  Section Start  
========================================  -->

<section class="section section-resume">
  <div class="container grid grid-two-column">
    <!-- resume left side  -->
    <div class="resume-img">
      <img
        class="lazy-img"
        src="images/lazy1.jpg"
        data-src="images/biodata.jpg"
        alt="resume image"
        loading="lazy"
      />
    </div>

    <!-- resume right side  -->
    <div class="resume-data">
      <h2 class="common-heading">resume</h2>
      <p class="resume-para">My Work Experience</p>

      <div class="resume-data-subsection">
        <div class="resume-data-left">
          <h3>FRONTEND DEVELOPMENT PROGRAMMING</h3>
          <div class="grid grid-two-column">
            <p>
              <ion-icon name="business-outline"></ion-icon> HARSH KORI,
              Inc.
            </p>
            <p><ion-icon name="location-outline"></ion-icon> JABALPUR, India</p>
          </div>
        </div>

        <div class="resume-data-right">
          <p class="resume-data-button">fulltime</p>
          <p>
            <ion-icon name="calendar-outline"></ion-icon>
            <span>AUGUST 2021 - Present </span>
          </p>
        </div>
      </div>
      <!-- end  -->

      <div class="resume-data-subsection">
        <div class="resume-data-left">
          <h3>FOUNDATION IN CORE JAVA </h3>
          <div class="grid grid-two-column">
            <p>
              <ion-icon name="business-outline"></ion-icon> HARSH KORI,
              Inc.
            </p>
            <p><ion-icon name="location-outline"></ion-icon> JABALPUR, India</p>
          </div>
        </div>

        <div class="resume-data-right">
          <p class="resume-data-button">fulltime</p>
          <p>
            <ion-icon name="calendar-outline"></ion-icon>
            <span>AUGUST 2021 - Present </span>
          </p>
        </div>
      </div>
      <!-- end  -->

      <div class="resume-data-subsection">
        <div class="resume-data-left">
          <h3>DATA STRUCTURE AND ALGORITHMS </h3>
          <div class="grid grid-two-column">
            <p>
              <ion-icon name="business-outline"></ion-icon>HARSH KORI,
              Inc.
            </p>
            <p><ion-icon name="location-outline"></ion-icon> JABALPUR, India</p>
          </div>
        </div>

        <div class="resume-data-right">
          <p class="resume-data-button">fulltime</p>
          <p>
            <ion-icon name="calendar-outline"></ion-icon>
            <span>AUGUST 2021 - Present </span>
          </p>
        </div>
      </div>
      <!-- end  -->

      <div class="resume-data-subsection">
        <div class="resume-data-left">
          <h3>PostgreSQL </h3>
          <div class="grid grid-two-column">
            <p>
              <ion-icon name="business-outline"></ion-icon> HARSH KORI,
              Inc.
            </p>
            <p><ion-icon name="location-outline"></ion-icon> JABALPUR, India</p>
          </div>
        </div>

        <div class="resume-data-right">
          <p class="resume-data-button">fulltime</p>
          <p>
            <ion-icon name="calendar-outline"></ion-icon>
            <span>AUGUST 2021 - Present </span>
          </p>
        </div>
      </div>
      <!-- end  -->

      <div class="resume-data-bottom-subsection">
        <p class="resume-para">Education</p>
        <div class="resume-data-subsection margin-small">
          <div class="resume-data-left">
            <h3>INNOVATIVE PROJECTS IN DYNAMIC AND COLLABORATIVE ENVIRONMENT </h3>
            <div class="grid grid-two-column">
              <p>
                <ion-icon name="business-outline"></ion-icon>
                HARSH KORI, Inc.
              </p>
              <p>
                <ion-icon name="location-outline"></ion-icon> Jabalpur, India
              </p>
            </div>
          </div>

          <div class="resume-data-right">
            <p class="resume-data-button">Master</p>
            <p>
              <ion-icon name="calendar-outline"></ion-icon>
              <span>AUGUST 2021 - Present </span>
            </p>
          </div>
        </div>
        <!-- end -->
        <div class="resume-data-subsection margin-small">
          <div class="resume-data-left">
            <h3>COMPUTER SCIENCE ENGINEERING</h3>
            <div class="grid grid-two-column">
              <p>
                <ion-icon name="business-outline"></ion-icon>
                HARSH KORI, Inc.
              </p>
              <p>
                <ion-icon name="location-outline"></ion-icon> JABALPUR, India
              </p>
            </div>
          </div>

          <div class="resume-data-right">
            <p class="resume-data-button">BACHELOR OF TECHNOLOGY</p>
            <p>
              <ion-icon name="calendar-outline"></ion-icon>
              <span>AUGUST 2021- Present </span>
            </p>
          </div>
        </div>
        <!-- end -->
      </div>
    </div>
  </div>
</section>
<!-- ======================================== 
      Our Freelancing   Section Start  
========================================  -->

<section class="section section-freelancing">
  <div class="overlay"></div>
  <div class="container">
    <h2>I am <span>available</span> for freelancing</h2>
    <p>
      Utilized React.js to build a user-friendly
      FRONTEND interface for administrators
    </p>
    <a href="/contact.html" class="btn">HIRE ME</a>
  </div>
</section>

<!-- ======================================== 
      Our contact us   Section Start  
========================================  -->

<section class="section section-contact">
  <div class="container">
    <h2 class="common-heading">Contact Us</h2>
  </div>

  <div class="section-contact-main contact-container">
    <form action="https://formspree.io/f/xknyvwjo" method="POST">
      <div class="grid grid-two-column">
        <div>
          <label for="username"></label>
          <input
            type="text"
            name="username"
            placeholder="Username"
            id="username"
            required
            autocomplete="off"
          />
        </div>
        <div>
          <label for="email"></label>
          <input
            type="email"
            name="email"
            placeholder="demo@mail.com"
            id="email"
            autocomplete="off"
            required
          />
        </div>
      </div>

      <div>
        <label for="subject"></label>
        <input
          type="text"
          name="subject"
          placeholder="subject"
          id="subject"
          autocomplete="off"
          required
        />
      </div>
      <div>
        <label for="textarea"></label>
        <textarea
          name="textarea"
          id="textarea"
          cols="30"
          rows="10"
          autocomplete="off"
          placeholder="Write your message"
          required
        ></textarea>
      </div>

      <div>
        <input
          type="submit"
          name="submit"
          id="submit"
          class="btn"
          value="send message"
        />
      </div>
    </form>
  </div>
</section>

<!-- ======================================== 
      Our Footer   Section Start  
========================================  -->
<footer class="section-footer section">
  <div class="container grid grid-four-column">
    <div class="f-about">
      <h3>About</h3>
      <p>
        We have tested a number of registry fix and clean utilities and
        present our top 3 list on our site for your convenience. Hope you
        like it.
      </p>
    </div>
    <!-- end -->
    <div class="f-links">
      <h3>Links</h3>
      <ul>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">home</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">about</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">services</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">portfolio</a>
        </li>

        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">contact</a>
        </li>
      </ul>
    </div>
    <!-- end  -->
    <div class="f-services">
      <h3>Services</h3>
      <ul>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">web design</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">web development</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">Mern Project</a>
        </li>

        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">Online Classes</a>
        </li>
        <li>
          <span><ion-icon name="arrow-forward-outline"></ion-icon></span
          ><a href="#">Youtube Course</a>
        </li>
      </ul>
    </div>
    <!-- end  -->
    <div class="f-address">
      <h3>Have a Questions?</h3>
      <address>
        <div>
          <p>
            <span><ion-icon name="location-outline"></ion-icon></span>
            Jabalpur, India
          </p>
        </div>

        <div>
          <p>
            <span><ion-icon name="call-outline"></ion-icon></span>
            <a href="tel:+917987134836"> +91 9111380218 </a>
          </p>
        </div>

        <div>
          <p>
            <span><ion-icon name="mail-outline"></ion-icon></span>
            <a href="harshkori389@gmail.com">
              info@harshkori.com
            </a>
          </p>
        </div>
      </address>
    </div>
  </div>

  <div class="container">
    <div class="f-social-icons">
      <a href="https://instagram.com/harsh_kori27?igshid=MzRlODBiNWFlZA==" target="_blank">
        <ion-icon class="icons" name="logo-instagram"></ion-icon>
      </a>

      <a href="https://discord.gg/MdScmCsua6" target="_blank">
        <ion-icon class="icons" name="logo-discord"></ion-icon>
      </a>

      <a href="https://youtube.com/@trend_withbase?si=_C2a7dLkpziP0NkN" target="_blank">
        <ion-icon class="icons" name="logo-youtube"></ion-icon>
      </a>
    </div>

    <div class="f-credits">
      <p>
        Copyright ©2022 All rights reserved | This template is made with ❤
        by HARSH KORI.
      </p>
    </div>
  </div>
</footer>
