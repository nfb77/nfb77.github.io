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
    * {
      font-family: 'Garamond','EB Garamond',  serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    
    body {
      color: #333;
      background-color: #f9f9f9;
    }

    .wrapper {
  background-color: #f9f9f9;
  margin: 50px auto;              /* space so rounded edges show */
  padding: 30px 20px 20px;
  border: 1px solid #ddd;         /* subtle border */
  border-radius: 14px;            /* rounded corners */
``}
    
   .top-bar {
      background-color: #2b416e;
      position: absolute;
      color: white;
      padding: 10px 0 15px 130px;
      text-align: left;
      font-size: 18px;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
      display: flex;
      flex-wrap: wrap; }
   
    /* Colors   Grey #1e1e1e(HU web) #1f1f1f #5e676e  #0d2340 light grey #4f4f4f  dark blue #2b416e(HU web) #0d2340 #840a0a crimson  #a51c30(HU web) #ffce56    */  
      .navbar {
      background-color: #1e1e1e;
      position: absolute;
      justify-content: center; 
      padding: 10px 0 10px 0;
      top: 47px;
      left: 0;
      width: 100%;
      z-index: 1000;
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
  font-size: 18px;
  transition: background 0.2s;
}

.navbar a:hover {
  background-color:  #4f4f4f;
  border-radius: 4px;
}

    h1, h2 {
      scroll-margin-top: 20px; /* or whatever height your navbar is + some padding */
      margin-bottom: 60px;
      color: #2c3e50;
    }

    p, li {
      margin-bottom: 16px;
      font-size: 16px;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: #0077cc;
    }

    a:hover {
      text-decoration: underline;
    }

    hr {
      border: none;
      height: 2px;
      background-color: #ddd;
      margin: 40px 0;
    }
    .spacer {
      margin-top: 60px;
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
  background-image: url("nashville_map.jpg");
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

  <div class="top-bar" id="home"> <a href="https://sociology.fas.harvard.edu/people/nicholas-forster-benson" class="plain-link" >Nicholas Forster-Benson</a> </div>


  <div class="navbar">
    <div class="nav-links">
      <a href="#about">About Me</a>
      <a href="https://nfb77.github.io/Files/CV_NFB.pdf" target="_blank">CV</a>
      <a href="#research">Research</a>
      <a href="#teaching">Teaching</a>
    </div>
  </div>

<div class="sliding-background"></div>

<div class="content">
  
    <div class="fixed-background">
    </div>
    
    <div class="wrapper">

    <h2 id="about">About Me</h2>

    <div class="bio-section">
    <div class="bio-photo-wrapper">   
    <div class="photo-caption">
        <img src="IMG_3706k.jpg" alt="Niccccccc" style="width: 70%; height: auto; border-radius: 4px;" /> 
      <p><strong>PhD Student</strong>, <a href="https://gsas.harvard.edu/program/social-policy" class="plain-link" target="_blank">Sociology & Social Policy, Harvard University</a> <br>
    <strong>Research Interests</strong>: Political economy, markets and inequality, financialization, quantatitive methods </p>
    </div>
  </div>

  <div class="bio-text">
        <p>I am an doctoral student in <a href="https://www.hks.harvard.edu/educational-programs/doctoral-programs/phd-social-policy" target="_blank">Sociology & Social Policy</a> at Harvard University and an affiliate of the <a href="https://caps.gov.harvard.edu/" target="_blank">Center for American Political Studies</a> and the <a href="https://www.iq.harvard.edu/" target="_blank">Institute for Quantitative Social Science</a>. Broadly, my research investigates how various market structures and interventions affect economic inequalities at both the local and global scale.</p>

        <p>Currently, my research focuses on U.S. housing markets, examining the intersection of local politics, financialization, liquidity, and inequality. Another strand of my work focuses on underdevelopment, utilizing nation-level heterogeneity in trade flows and macro-economic indicators to better understand post-colonial commodity dependence and natural resource exploitation in the global south.</p>

        
          <p>I hold a BA in <a href="https://as.vanderbilt.edu/economics/major-minor/"  target="_blank">Economics</a> and <a href="https://nfb77.github.io/Files/requirements-individually-designed-interdisciplinary-major.pdf" target="_blank">Quantitative Social Science</a> (<a href="https://as.vanderbilt.edu/internal/policies/individually-designed-interdisciplinary-major.php" class="plain-link" target="_blank">interdisciplinary</a>) from <a href="https://www.vanderbilt.edu/" class="plain-link" target="_blank">Vanderbilt University</a>. I am a lifelong Tennessean, but I have also lived briefly lived in Uppsala, Chicago, Milan, and Boston. In my spare time, I am a pick-up basketball enthusiest.</p>   
          
  </div>
</div>

<div class="spacer"></div>

    <h2 id="research">Research</h2>
    <p>
      <a href="https://github.com/nfb77" target="_blank">GitHub</a> &nbsp;&nbsp; 
    </p>

    <p>Broadly, my research investigates how various market structures and interventions effect economic inequalities at both the local and global scale. I have worked under the mentorship of both <a href="https://sites.google.com/view/karimnchare/accueil" target="_blank">Dr. Karim Nchare</a> (<a href="https://as.vanderbilt.edu/economics/" class="plain-link" target="_blank">VU Economics</a>) and <a href="https://scholar.google.com/citations?user=0uUc8-cAAAAJ&hl=en" target="_blank">Dr. Richard Lloyd</a> (<a href="https://as.vanderbilt.edu/sociology/" class="plain-link" target="_blank">VU Sociology</a>) researching housing inequality in Nashville and post-colonial trade patterns in west Africa.</p>
    
    <p>In an article with Karim Nchare in the Journal of Housing Economics, we explored the connection between upzoning, displacement, and housing affordability in Nashville. Taking advantage of quasi-experimental policy design, we estimate heterogeneous market segment <a href="https://www.sciencedirect.com/science/article/pii/S1051137725000634" target="_blank">effects of upzoning on housing prices in Nashville</a>, showing decreases in affordability concentrated bottom quartile of sales simultaneously with potential price mitigation concentrated in the top fourth of the housing price distribution.</p>
    
    <p> In another strand of research, I analyzed trade relationships between Portugal and its former African colonies from 1960–2022, providing <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4874987" target="_blank">quantitative evidence for the persistence of colonial commodity dependence</a> and natural resource exploitation.</p>

<div class="spacer"></div>


    <h2 id="teaching">Teaching</h2>
    <ul>
      <li><strong>ECON 1500 Economic Statistics, Teaching Assistant, Fall 2024</strong><br>
        Vanderbilt University, Department of Economics — <a href="https://nfb77.github.io/Files/ECON1500Fall24.pdf" target="_blank">Syllabus</a><br>
        Set theory, probability, random variables, inference and regression analysis.
      </li>
      <li><strong>SOC 3233 Contemporary American Society, Teaching Assistant, Fall 2022, Fall 2023</strong><br>
        Vanderbilt University, Department of Sociology — <a href="https://nfb77.github.io/Files/SOC3233Fall23.pdf" target="_blank">Syllabus</a><br>
         Changes in political economy, geography, and social class stratification in the United States (1940s-present).
      </li>
      <li><strong>SOC 3202 Cultural Production and Institutions, Teaching Assistant, Fall 2023</strong><br>
        Vanderbilt University, Department of Sociology — <a href="https://nfb77.github.io/Files/SOC3203Fall23.pdf" target="_blank">Syllabus</a><br>
        Examining the production of art and authenticity within various art fields, from the production of drill music to 15th-century Italian painting.

      </li>
    </ul>

<div class="spacer"></div>

    <h2 id="contact">Contact</h2>
    <p>✉️ <a href="mailto:nforsterbenson@fas.harvard.edu">nforsterbenson@fas.harvard.edu</a></p>
    <p>⟟ <a href="https://www.google.com/maps/dir//808-818+Argyle+Ave,+Nashville,+TN+37203/@36.1364026,-86.7800109,214m/data=!3m1!1e3!4m9!4m8!1m0!1m5!1m1!1s0x8864667ef84ee215:0xecc27dbc7936315d!2m2!1d-86.7793274!2d36.1364026!3e0?entry=ttu&g_ep=EgoyMDI1MDYyOS4wIKXMDSoASAFQAw%3D%3D"  target="_blank">Reservoir Park Courts, 1801 8th Ave South, Nashville, TN 37203</a></p>

      <img src="r_park1.png" alt="Reservoir Park" style="width: 48%;height: auto;border-radius: 4px;"/>
  
  </div>
</div>


</body>
</html>
