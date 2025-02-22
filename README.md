<html>
.content {
    max-width: 900px;  /* Adjust as needed */
    margin: 0 auto;
    padding: 20px;
}

.image-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;  /* Ensures wrapping on small screens */
    width: 100%;
}

.image-container img {
    height: 300px;
    flex: 1;
    object-fit: cover;
    margin-right: 10px;
    max-width: 100%; /* Ensures images don't overflow */
}

.image-container img:last-child {
    margin-right: 0;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
    .image-container {
        flex-direction: column;  /* Stack images vertically */
        align-items: center;     /* Center images */
    }

    .image-container img {
        width: 100%;  /* Make images full-width */
        height: auto; /* Adjust height dynamically */
        margin-bottom: 10px;
    }

    .content {
        padding: 10px;  /* Reduce padding for smaller screens */
    }
}
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nicc Forster-Benson</title>
    <style>
         body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .navbar {
            background-color: #white;
            overflow: hidden;
            display: flex;
            padding: 10px;
        }
        .navbar a {
            color: #575757;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
            font-size: 20px; /* Increased font size */
        }
        .navbar a:hover {
            background-color: #f0f3f4;
        }
        .content {
            padding: 20px;
        }
        hr {
            border: none;
            height: 3px;
            background-color: black;
            margin: 5px 0;
        }
        .image-container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            width: 100%;
        }
        .image-container img {
            height: 200px;
            flex: 1;
            object-fit: cover;
            margin-right: 10px;
        }
        .image-container img:last-child {
            margin-right: 0;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#about">About Me</a>
        <a href="#research">Research</a>
        <a href="#teaching">Teaching</a>
        <a href="https://nfb77.github.io/Files/NFB_CV25.pdf" target="_blank">CV</a> &nbsp;&nbsp;&nbsp;&nbsp; 
    </div>
        <hr style="border: none; height: 1px; background-color: gainsboro; margin-bottom: 0px 0;">

    <div class="content">
<div style="display: flex; align-items: flex-start;">
    <img src="art4.1.jpg" alt="Artwork" style="height: 300px; flex: 1; object-fit: cover; margin-right: 10px;">
    <img src="nashville_map.jpg" alt="Nashville Map" style="height: 300px; flex: 1; object-fit: cover; margin-right: 10px;">
    <img src="art1.jpg" alt="Artwork" style="height: 300px; flex: 1; object-fit: cover; margin-right: 0;">
</div>
        </div>
        <hr style="border: none; height: 1px; background-color: gainsboro; margin-bottom: 0px 0;">

        <h1 id="about">Nicholas (Nicc) Forster-Benson</h1>
        <p><strong>PhD Student, Sociology & Social Policy, Harvard University</strong>
        <p><strong>Research Interests:</strong> Knowledge production and policy, political economy, financialization and inequality, mixed methods
        <h2>About Me</h2>
        <p>Nicc will receive his BA in Economics and Quantitative Social Science from Vanderbilt University in May of 2025. With experience working for the Tennessee Department of Treasury, the U.S. Federal Reserve Board of Governors, and running for political office in Tennessee, Nicc aims to continue exploring the relations between state agents, knowledge production, and governance in graduate school.
        </p>
<p>Currently, he is interested in examining how the logics of financialization and globalization shape inequality, permeating housing, infrastructure, and public space. Exploring the socio-political dynamics of contemporary urban governance, Nicc looks to investigate the evolving relationships between cities, markets, and policy.
</p>

<p>
Raised and educated in Nashville, Tennessee, Nicc has also lived in Boston, Chicago, Milan, and Uppsala, Sweden. In his spare time, he is a pick-up basketball enthusiast and part-time 3-point specialist.</p>

        <h2 id="research">Research</h2>
        
                <a href="https://scholar.google.com/citations?user=kRAT0zUAAAAJ&hl=en" target="_blank">Google Scholar</a> &nbsp;&nbsp;&nbsp;&nbsp; 
        <a href="https://github.com/nfb77" target="_blank">GitHub</a> &nbsp;&nbsp;&nbsp;&nbsp; 
        <hr style="border: none; height: 1px; background-color: gainsboro; margin-bottom: 0px 0;">
        
        <p>In his honors thesis, Nicc applied causal inference methods from econometrics, taking advantage of a quasi-experimental policy design to estimate the effect of upzoning on housing affordability in Nashville. Nicc’s findings demonstrated the regressive effects of upzoning on housing affordability, relating upzoning policies to the peripheralization of black communities in Nashville. Analyzing upzoning as a process of spatial financialization, his thesis draws upon the social production of space as a framework to understand post-Fordist modes of accumulation in Nashville.
</p>
<p>
Nicc has worked under the mentorship of both Dr. Richard Lloyd (VU sociology) and Karim Nchare (VU economics) navigating the complexities of formal economic modeling in relation to the socially-temporally contingent nature of economic phenomenon. In another strand of research, Nicc has applied insights into the social construction of political economy to topics of international development and legacies of colonialism in Africa, analyzing trade relationships between Portugal and its former African colonies from 1960-2022. Using gravity model Poisson pseudo-maximum-likelihood estimates of bilateral trade flows, Nicc’s research provided <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4874987" target="_blank">quantitative evidence for the persistence of colonial commodity dependence</a> and natural resource exploitation. His work combined empirical methodology with world-systems theory aiming to enhance our understanding of Africa’s unequal exchange in the new global division of labor, emphasizing the socio-political construction of modern economic inequalities.</p>

<h2 id="teaching">Teaching</h2>
<ul>
    <li>
        <strong>Teaching Assistant, ECON 1500 Economic Statistics, Fall 2024</strong><br>
        Vanderbilt University, Department of Economics,  <a href="https://nfb77.github.io/Files/EconStatFall24.pdf" target="_blank">Syllabus</a> <br>
        Led weekly office hours and assisting in evaluation regarding understandings of set-theory, probability, random variables, and regression analysis.    </li>
    <li>
        <strong>Teaching Assistant, SOC 3202 Cultural Production and Institutions, Fall 2023 </strong><br>
        Vanderbilt University, Department of Sociology,   <a href="https://nfb77.github.io/Files/SOC3203Fall.pdf" target="_blank">Syllabus</a> <br>
        Assisted in grading and instruction regarding the development of a sociological approach to the production of culture. Examining the production of authenticity within the milieu of various art fields, from the production of drill music to 15th century Italian painting.
    </li>
    <li>
        <strong>Teaching Assistant, SOC 3233 Contemporary American Society, Fall 2022, Fall 2023</strong><br>
         Vanderbilt University, Department of Sociology,  <a href="https://nfb77.github.io/Files/SOC3233Fall23.pdf" target="_blank">Syllabus</a> <br>
       Was responsible for key creation and essay evaluation regarding methods regarding critical analysis of shifts in the political, economic, and social structure of the United States; changes in political economy, geography, and social class stratification.

    </li>
</ul>
        <h2 id="contact">Contact</h2>
        <p>📧 <a href="mailto:nicholas.o.forster-benson@vanderbilt.edu">nicholas.o.forster-benson@vanderbilt.edu</a></p>
        <hr style="border: none; height: 1px; background-color: gainsboro; margin-bottom: 0px 0;">

<div style="display: flex; align-items: flex-start;">
    <img src="r_park2.png" alt="Resivoir" style="height: 245px; flex: 1; object-fit: cover; margin-right: 10px;">
    <img src="art6.jpg" alt="Artwork"  style="height: 245px; flex: 1; object-fit: cover; margin-right: 0;">

