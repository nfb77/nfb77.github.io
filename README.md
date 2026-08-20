
<html lang="en">
<head>
  <link href="https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap" rel="stylesheet">
  <link rel="shortcut icon" type="image/png" href="favicon.ico?">
  <link rel="apple-touch-icon" sizes="180x180" href="/img/apple-touch-icon.png">
  <title>Nicholas Forster-Benson</title>
  
<script>
  document.title = "Nicholas Forster-Benson";
</script>
  
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta property="og:title" content="Nicholas Forster-Benson">

  <style>
    /* Reset & Base Styles */
    * {font-family: 'Garamond','EB Garamond',  serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    
    body {
      color: #333;
      background-color: #f9f9f9;
    }

    .wrapper {
  background-color: #e7d0a7;
  margin: 20px auto;              /* space so rounded edges show */
  padding: 30px 20px 20px;
  border: 1px solid black;         /* subtle border */
  border-radius: 14px;            /* rounded corners */
``}
    
   .top-bar {
      background-color: #e7d0a7;
      position: absolute;
      color: black;
      padding: 7px 0 8px 0px; 
      font-weight: 700; /*  green monster font,     font-family: 'Overpass', sans-serif; font-weight: 700;  text-transform: uppercase;     letter-spacing: 1px; */
      font-size: 19px;
      justify-content: center; 
      top: 0;
      left: 0;
      width: 100%;
      border-top: 1.5px solid black;
      z-index: 1001;
      display: flex;
      flex-wrap: wrap; }


   
    /* Colors    #2b416e(dark blue HU web) #1e1e1e(Grey HU web) #4d6f65 (fenway green) #3e6358 (fenway hover, dark) #1f1f1f #5e676e  #0d2340 #4f4f4f (light grey hover) #0d2340 #840a0a   #a51c30(crimsonHU web) #ffce56  #e7d0a7 (background cream) #f9f9f9 (textbox cream)*/  
      .navbar {
      background-color: #4d6f65;
      position: absolute;
      justify-content: center; 
      padding: 8px 0 8px 0;
      top: 41.5px;
      left: 0;
      width: 100%;
      z-index: 1000;
      border-top: 2px solid black;
      border-bottom: 1.5px solid black;
      display: flex;
      flex-wrap: wrap; 
    }
    
    
    .nav-links {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 25px;
}

.navbar a {
  color: white;
  padding: 8px 8px;
  text-decoration: none;
  font-size: 19px;
  transition: background 0.2s;
}

.navbar a:hover {
  background-color:  #3e6358;
  border-radius: 4px;
}

h1 {
  scroll-margin-top: 20px; /* or whatever height your navbar is + some padding */
  margin-bottom: 60px;
  color: #2c3e50;
  border-bottom: 1px solid #2c3e50;
}
    
.markdown-body h2 {
  scroll-margin-top: 20px; /* or whatever height your navbar is + some padding */
  margin-bottom: 30px;
  color: #2c3e50;
  border-bottom: 1px solid #2c3e50;
}
    

    p, li {
      margin-bottom: 16px;
      font-size: 16px;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: #4d6f65;    /* link color: #0077cc (light blue)   #4000ff (dark blue)*/
    }

    a:hover {
      text-decoration: underline;
    }

    hr {
      border: none;
      height: 5px;
      background-color: white;
    }
    
    .spacer {
      margin-top: 60px;
      }

        .spacerr {
      margin-top: 100px;
      }
    
        .bio-section {
      display: flex;
      align-items: flex-start;
      gap: 30px;
      max-width: 100%;
    }
    
    .bio-photo-wrapper {
      text-align: center;
      max-width: 40%;
    }
    
    .photo-caption {
      margin-top: 8px;
      font-size: 0.95em;
      color: #444;
    }
    
    .bio-text {
      flex: 1;
    }

.container {
  overflow: hidden;
}

.sliding-background {
  position: fixed;
  top: 0;
  left: 0;
  width: 200vw;
  height: 200vh;
  background-image: url("images/nashville_map.jpg");
  background-repeat: repeat;
  background-size: 800px auto; /* adjust scale here */
  z-index: -1;
  animation: diagonal-slide 80s linear infinite;
}

@keyframes diagonal-slide {
  0% {
    transform: translate(0, 0);
  }
  100% {
    transform: translate(-50vw, -50vh);
  }
}

.content {
  position: relative;
  z-index: 1;
}


    .contact-boxes {
  display: flex;
  justify-content: center;
  gap: 14px;
  margin-top: 14px;
  flex-wrap: wrap;
}

.contact-box {
  border: 1px solid #888;
  padding: 8px ;
  border-radius: 8px;
  text-decoration: none;
  color: black;
  font-size: 0.95em;
  display: inline-flex;
  align-items: center;
  transition: background-color 0.2s ease, border-color 0.2s ease;
}

.contact-box:hover {
  background-color: #4d6f65;
  color: white;
  border-color: white;
}

.contact-box .icon {
  font-size: 1.1em;
}
    
    /* Responsive mobile styles */
  @media (max-width: 768px) {
  .bio-section {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .bio-photo-wrapper {
    max-width: 80%;
    flex: 0 0 auto;
  }

  .bio-text {
    text-align: left;
    padding: 0px 0px 10px 0px;
  }
}
    
    .plain-link {
      color: inherit;           /* Uses the same text color as surrounding text */
      text-decoration: none;    */  Removes underline     */ Optional: adds pointer cursor      cursor: pointer;     */
    }

      .fixed-background {
      margin-top: 100px;
      margin-bottom: 30px;
      background-image: url('nashville_map.jpg');
      height: 55vh;
      background-attachment: fixed;
      background-size: 75%;
      background-position: top;
      background-repeat: no-repeat;
    }

    /* Fallback for mobile */
    @media (max-width: 768px) {
    .fixed-background {
    background-attachment: scroll;
    background-size: cover;
  }
}
        
  </style>
</head>



<body>
   <!-- Top Bar -->

  <div class="top-bar" id="home"> Nicholas Forster Benson   </div>

  <div class="navbar">
    <div class="nav-links">
      <a href="#research">Research</a>
      <a href="#teaching">Teaching</a>
      <a href="https://nfb77.github.io/Files/CV_NFB.pdf" target="_blank">CV</a>

    </div>
    </div>

<div class="sliding-background"></div>

<div class="content">
    


<div class="spacerr"></div>
<div class="spacerr"></div>
<div class="spacerr"></div>
<div class="spacerr"></div>

    <div class="wrapper">

    <h2 id="about">Bio</h2>

    <div class="bio-section">
    <div class="bio-photo-wrapper">   
    <div class="photo-caption">
        <img src="images/r_park1.png" alt="Nicccccccccccccc" style="width: 85%; height: auto; border-radius: 4px;" /> 
      <p><strong><a href="https://sociology.fas.harvard.edu/people/nicholas-forster-benson" class="plain-link" >PhD Student</a></strong>, <a href="https://gsas.harvard.edu/program/social-policy" class="plain-link" target="_blank">Sociology & Social Policy</a> <br>
    <strong>Research Interests</strong>: Political economy, markets and inequality, financialization, quantatitive methods </p>
    <div class="contact-boxes">
  <a href="https://github.com/nfb77" target="_blank" class="contact-box">
    <span class="icon"></span> GitHub
  </a>

  <a href="mailto:nforsterbenson@g.harvard.edu" class="contact-box">
    <span class="icon"></span> E-mail
  </a>
</div>
</div>
</div>


  <div class="bio-text">
        <p>I am a doctoral student in <a href="https://www.hks.harvard.edu/educational-programs/doctoral-programs/phd-social-policy" target="_blank">Sociology & Social Policy</a> and Malcolm H. Wiener Scholar in Poverty and Justice at Harvard University. Broadly, my research asks how material inequalities are produced, reproduced, or mitigated through various economic and political institutions. My current focus is U.S. housing markets, examining the intersection of local politics, financialization, and inequality. Currently, my research focuses on U.S. housing markets, examining the intersection of local politics, financialization, and inequality.</p>


        <!-- <p>Currently, my research focuses on U.S. housing markets, examining the intersection of local politics, financialization, and inequality. Another strand of my work focuses on underdevelopment, utilizing nation-level heterogeneity in trade flows and macro-economic indicators to better understand post-colonial commodity dependence and natural resource exploitation in the global south.</p> -->

          <p>I hold a BA in <a href="https://as.vanderbilt.edu/economics/major-minor/"  target="_blank">Economics</a> and <a href="https://nfb77.github.io/Files/requirements-individually-designed-interdisciplinary-major.pdf" target="_blank">Quantitative Social Science</a> (<a href="https://as.vanderbilt.edu/internal/policies/individually-designed-interdisciplinary-major.php" class="plain-link" target="_blank">interdisciplinary</a>) from <a href="https://www.vanderbilt.edu/" class="plain-link" target="_blank">Vanderbilt University</a>. I am a lifelong Tennessean, but I have also lived briefly lived in Uppsala, Chicago, Milan, and Boston. In my spare time, I am a <a href="https://en.wikipedia.org/wiki/Pick-up_basketball"  target="_blank">pick-up basketball</a> enthusiest.</p>   
          
  </div>
  </div>
  </div>
  
<div class="spacerr"></div>
<div class="spacerr"></div>


<div class="wrapper">

  <h2 id="research">Research</h2>

  <h3>Publications</h3>

  <p>
    <strong>N. Forster-Benson</strong> and K. Nchare. (2025).
    “<a href="https://doi.org/10.1016/j.jhe.2025.102104" target="_blank">Upzoning and Residential Transaction Price in Nashville.</a>”
    <em>Journal of Housing Economics</em>, 70: 102104.
  
  </p>

  <h3>Works in Progress</h3>

  <p>
   <strong>N. Forster-Benson</strong>.
    “<a href="https://nfb77.github.io/Files/CODRUS.pdf" target="_blank">Corporate Ownership Density and Rent in the United States: An Analysis from 2012-2022.</a>”
    Working paper. 
  </p>

<p>
    <strong>N. Forster-Benson</strong>. “Upzoning, Density, and the Financialization of Space in Nashville.” Under Review. 
</p>
  
<p>
    <strong>N. Forster-Benson</strong>. “Towards a Relational Understanding of Zoning Conflict.” In Preperation.
</p>

<p>
    <strong>N. Forster-Benson</strong> and K. Nchare.
    “<a href="https://doi.org/10.2139/ssrn.4874987" target="_blank">Trade Distortions and Colonial Legacy: Evidence from Portugal and Its Former Colonies.</a>”
    Revise &amp; Resubmit, <em>Journal of International Development</em>.
</p>

  <div class="spacer"></div>

</div>

 

  
<div class="spacerr"></div>
<div class="spacerr"></div>

    <div class="wrapper">
    
    <h2 id="teaching">Teaching</h2>
    <ul>
      <li><strong>Economic Statistics (ECON 1500), Teaching Assistant, Fall 2024</strong><br>
        Vanderbilt University, Department of Economics — <a href="https://nfb77.github.io/Files/ECON1500Fall24.pdf" target="_blank">Syllabus</a><br>
        Introduction to probability and inference.
      </li>
      <li><strong>Contemporary American Society (SOC 3233), Teaching Assistant, Fall 2022, Fall 2023</strong><br>
        Vanderbilt University, Department of Sociology — <a href="https://nfb77.github.io/Files/SOC3233Fall23.pdf" target="_blank">Syllabus</a><br>
         Changes in political economy, geography, and social class stratification in the United States (1940s-present).
      </li>
      <li><strong>Cultural Production and Institutions (SOC 3202), Teaching Assistant, Fall 2023</strong><br>
        Vanderbilt University, Department of Sociology — <a href="https://nfb77.github.io/Files/SOC3203Fall23.pdf" target="_blank">Syllabus</a><br>
        Examining the production of art and authenticity within various art fields, from the production of drill music to 15th-century Italian painting.

      </li>
    </ul>

<div class="spacer"></div>
  
  </div>
  
<div class="spacerr"></div>
<div class="spacerr"></div>



    <div class="wrapper">
    <h2 id="contact">Contact</h2>
    <p>✉ <a href="mailto:nforsterbenson@fas.harvard.edu">nforsterbenson@fas.harvard.edu</a></p>
    <p>⟟ <a href="https://www.google.com/maps/dir//808-818+Argyle+Ave,+Nashville,+TN+37203/@36.1364026,-86.7800109,214m/data=!3m1!1e3!4m9!4m8!1m0!1m5!1m1!1s0x8864667ef84ee215:0xecc27dbc7936315d!2m2!1d-86.7793274!2d36.1364026!3e0?entry=ttu&g_ep=EgoyMDI1MDYyOS4wIKXMDSoASAFQAw%3D%3D"  target="_blank">Reservoir Park Courts, 1801 8th Ave South, Nashville, TN 37203</a></p>

      <img src="images/r_park4.1.jpeg" alt="Reservoir Park" style="width: 48%;height: auto;border-radius: 4px;"/>

<div class="spacerr"></div>

  </div>
</div>
<div class="spacerr"></div>
<div class="spacerr"></div>


</body>
</html>
