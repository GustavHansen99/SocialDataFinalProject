---
layout: page
title: 3-1-1 - Street Cleaning Requests in San Francisco
permalink: /project/
---

<html>
<head>
	<style>
        .page-title {
            color: white;
            font-size: 32px;
        }
        h3 {
            font-size: 14px;
            text-align: center
        }
		.column {
			float: left;
			width: 50%;
			padding: 10px;
			box-sizing: border-box;
            text-align: center;
		}
		.column img {
			display: block; /* make the image a block element */
			max-width: 100%; /* set the maximum width of the image to the width of its parent element */
			height: auto; /* allow the height of the image to adjust proportionally */
			margin: 0 auto; /* center the image horizontally */
		}
		.column p {
			width: 80%; /* set the width of the paragraph text to 80% of the column */
			margin: 0 auto; /* center the paragraph text horizontally */
            text-align: justify
		}
        .border-right {
            border-right: 1px solid black;
        }
		.clearfix::after {
			content: "";
			clear: both;
			display: table;
		}
        div {
            text-align: justify
        }
        .back-gif {
            position: absolute;
            left:0;
            width: 100%;
            height: auto;
            z-index:-1;
            transform: translateY(-80%);
        }
        footer {
        text-align: right;
        }
        .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 80%;
        }
	</style>
</head>

<body>
    <div class="city_life">
        <img src="/SocialDataFinalProject/site_content/SF.gif" class="back-gif" alt="Messy">
    </div>
    <h1 class="page-title">{{ page.title }}</h1>
    <p style="color:white">A deep dive into the defilement of San Francisco</p>
    <br><br>
    <h2>Introduction</h2>
    <div> 
    <p>
        Keeping cities clean and safe is one of the most important and essential factors for the well-being of both residents and visitors. The cleanliness of a city plays a critical role in maintaining the public health, promoting tourism and creating a safe and comfortable environment for everyone. On the other hand, when a city is dirty and filled with trash and waste, it negatively impacts the quality of life for all parties involved.
        San Francisco is a city that has faced significant challenges regarding the cleanliness of its streets. They are often littered with loose garbage, bulky items, needles and even human faeces, which is both repulsive and unhealthy. Major news outlets in San Francisco, such as the <a href="https://abc7news.com/sf-tourism-san-francisco-streets-international-travelers-conventions-in/12227886/" target="_blank"> ABC </a> [1] and the <a href="https://www.sfchronicle.com/opinion/letterstotheeditor/article/sf-streets-are-not-safer-or-cleaner-17596059.php" target="_blank"> San Francisco Chronicle </a> [2], reported multiple stories around 2018 that highlighted this crucial problem. This has also given rise to Mayor London Breed to incorporate the <a href="https://londonformayor.com/policies/clean-streets-clean-city-2/" target="_blank"> "Clean Streets" -agenda into her main campaign </a> [3].
        Given the significant issue of dirtiness in San Francisco and its ongoing discussion and seriousness, this report aims at contributiong to the understanding of the problem by analysing the government of San Francisco’s dataset (<a href="https://data.sfgov.org/City-Infrastructure/311-Cases/vw6y-z8j6" target="_blank"> 3-1-1 Cases </a>) of cases associated with Street Cleaning requests in the city.
        <br>
        In this way, we hypothesize that our report sheds light on especially two main questions: 
        <ol type='1'>
            <li>
                Given the stories reported in 2018, are the dirty streets still a prevalent issue today in San Francisco? And if so what are some of the main reasons for and contributors to this?
            </li>
            <li>
                Some news articles focused their attention to specific areas of the city. This project, however, also aims at elucidating if the problem is present throughout the city. In this way, we can answer if there are there any specific areas that are more affected by the problem than others? And if so, what are the main reasons for this? 
            </li>
        </ol>
        <br>
    </p>
    <h2>Our Dataset</h2>
    <p>
        Text here.... <a href="https://data.sfgov.org/City-Infrastructure/311-Cases/vw6y-z8j6" target="_blank">link here to San Francisco 3-1-1 data from 2008-present</a>... Link to our Github explainer notebook <a href="https://github.com/GustavHansen99/SocialDataFinalProject/blob/master/coding/project_notebook.ipynb" target="_blank">Github Repository</a>
    <br>
    <br>
    </p>
    <h2>Title of something interesting</h2>
    <p>
        Text here 
    </p>
    <div>
    <h4 style="text-align:center">Time Series</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/timeSeriesPlot.html"
            width="1100"
            height="600"
        >
    </div>
    <p>
        Text here 
    </p>
    <div>
        <h4 style="text-align:center">Examples of requested cleaning tickets</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/site_content/slideshow.html"
            width="1050"
            height="600"
            >
    </div>
    <h2>Another title of something cool</h2>
    <p>
        Text here 
    </p>
    <div>
        <h4 style="text-align:center">Map Yearly V2</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/SF_mapYearlyV2.html"
            width="1100"
            height="720"
            >
    </div>
    <p>
        Text here 
    </p>
    <h2>Mission, South of Market and Tenderloin - The Trifecta of trouble</h2>
    <p>
        Text here... <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry" target="_blank">link here to San Francisco Historical data from 2003-2018</a> <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783" target="_blank">link here to San Francisco data from 2018-present</a>
        <br>
        <br>
    </p>
    <p>
        Text here
    </p>
    <div>
        <h4 style="text-align:center">Map Yearly V2</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/SF_CrimemapYearlyV2.html"
            width="1100"
            height="720"
            >
    </div>
    <h2>Concluding Thoughts</h2>
    <p>
        Text here
        <br>
        <br>
        Text here  
    </p>
    <h3>References</h3>
    <ol type="1">
        <li>
            <a href="https://abc7news.com/sf-tourism-san-francisco-streets-international-travelers-conventions-in/12227886/" target="_blank"> ABC News article: SF's 'dirty streets' hurting international tourism as conventions struggle to come back </a>
        </li>
        <li>
            <a href="https://www.sfchronicle.com/opinion/letterstotheeditor/article/sf-streets-are-not-safer-or-cleaner-17596059.php" target="_blank"> SF Chronicle: Letters: Why Mayor Breed’s efforts aren’t making S.F. streets safer or cleaner </a>
        </li>
        <li><a href="https://londonformayor.com/policies/clean-streets-clean-city-2/" target="_blank"> Mayor Breed: Clean Streets, Clean City </a></li>
    </ol>
    <footer>
        <p>
            Click the link below to get a walkthrough of our data processing.
            <br>
            <a href="https://github.com/GustavHansen99/SocialDataFinalProject/blob/master/coding/project_notebook.ipynb" target="_blank">Github Repository</a>
        </p>
    </footer>
</body>