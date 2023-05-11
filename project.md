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
            width: 95%;
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
        Keeping cities clean and safe is one of the most important and essential factors for the well-being of both residents and visitors.  Studies have shown that cleanliness of a city plays a critical role in maintaining the <a href="https://www.epowertrucks.co.uk/news/how-dirty-streets-are-affecting-the-environment-and-property-values-in-your-area/" target="_blank">public health</a> [1], promoting tourism and creating a safe and comfortable environment for everyone. On the other hand, when a city is dirty and filled with trash and waste, it negatively impacts the quality of life for all parties involved.
        San Francisco is a city that has faced significant challenges regarding the cleanliness of its streets. They are often littered with loose garbage, bulky items, needles and even human faeces, which is both repulsive and unhealthy. Major news outlets in San Francisco, such as <a href="https://abc7news.com/sf-tourism-san-francisco-streets-international-travelers-conventions-in/12227886/" target="_blank"> ABC News</a> [2] and the <a href="https://www.sfchronicle.com/opinion/letterstotheeditor/article/sf-streets-are-not-safer-or-cleaner-17596059.php" target="_blank"> San Francisco Chronicle</a> [3], reported multiple stories around 2018 that highlighted this crucial problem. This has also given rise to Mayor London Breed to incorporate the <a href="https://londonformayor.com/policies/clean-streets-clean-city-2/" target="_blank"> "Clean Streets"-agenda into her main campaign</a> [4].
        Given the significant issue of dirtiness in San Francisco and its ongoing discussion and seriousness, this report aims at contributiong to the understanding of the problem by analysing the government of San Francisco’s dataset (<a href="https://data.sfgov.org/City-Infrastructure/311-Cases/vw6y-z8j6" target="_blank">3-1-1 Cases</a>) of cases associated with Street Cleaning requests in the city.
        <br>
        In this way, we hypothesize that our report sheds light on especially two main issues: 
        <ol type='1'>
            <li>
                Given the stories reported in 2018, are the dirty streets still a prevalent issue today in San Francisco? And if so what are some of the main reasons for and contributors to this?
            </li>
            <li>
                News articles often focuses their attention to specific areas of the city. This project, however, also aims at elucidating if the problem is present throughout the city. In this way, we can answer if there are any specific areas that are more affected by the problem than others. And if so, what are the main reasons for this?
            </li>
        </ol>
    </p>
    <h2>Our Dataset</h2>
    <p>
        The dataset used for this project is the 311 Cases dataset made publicly available by the city's 311 Customer Service Center. The dataset contains non-emergency requests for service made by residents and visitors to the 311 Customer Service Center via  <a href="https://sf311.org/" target="_blank">phone calls, online submissions</a> [5] or mobile apps. The request types cover a wide range of issues, such as street and sidewalk cleaning, graffiti, abandoned vehicles and noise complaints. The dataset contains detailed information about each request, such as the date and time it was made, the location, the nature of the problem, and the status of the problem. The dataset is regularly updated to include the newest requests made, however we do not consider request made after the 30th of April. 
        <br>
        <br>
        The full dataset contains over 6 million requests made from 2008 to 2023, but since we focus on the Street and Sidewalk cleaning requests the actual dataset of interest contains approximately 2 million requests. Due to the significant size of the dataset, we only include requests with a latitude and longitude position within the boundaries of San Francisco. Moreover, we made sure that request types are not duplicated, but instead sum up similar types to get a more accurate representation of the severeness of the type. This means that for example, we accumulate the request types "Human or Animal Waste" and "Human Waste" to get a more accurate representation of the number of requests regarding human waste. Lastly, we direct focus towards the 10 most frequent request types, which are hence also the types we deem most relevant for our analysis. We will refer to these as the main request types, and we will not consider tendencies in the other request types.
        <br>
        <br>
        For a more hands-on inspection of the creation of this report, we have composed all findings in an explainer notebook, that can be found <a href="https://github.com/GustavHansen99/SocialDataFinalProject/blob/master/coding/project_notebook.ipynb" target="_blank">here</a>.
    </p>
    <h2>First point</h2>
    <p>
        Text here 
    </p>
    <div>
        <h3>Figure 1: San Francisco Street & Sidewalk Cleaning Requests</h3>
        <iframe src="/SocialDataFinalProject/assets/images/BarChart.html" width="100%" height="625" style="border:none;" class='center'></iframe>
    </div>
    <p>
        Text here 
    </p>
    <div>
        <h3>Figure 2: Examples of Requested Cleaning</h3>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/site_content/slideshow.html"
            width="1050"
            height="600"
            >
    </div>
    <p>
        Text here 
    </p>
    <h2>Second point</h2>
    <p>
        Text here 
    </p>
    <div>
        <h3>Figure 3: Trends in San Francisco Street Cleaning Requests by Category (2008-2023)</h3>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/timeSeriesPlot.html"
            width="1025"
            height="600"
            >
    </div>
    <p>
        Text here 
    </p>
    <div>
        <h3>Figure 4: A Yearly District-Level Perspective on Street Cleaning Requests</h3>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/SF_mapYearlyV2.html"
            width="1050"
            height="725"
            >
    </div>
    <p>
        Text here 
    </p>
    <h2>Mission, South of Market and Tenderloin - A Trifecta of trouble</h2>
    <p>
        Text here... <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry" target="_blank">link here to San Francisco Historical data from 2003-2018</a> <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783" target="_blank">link here to San Francisco data from 2018-present</a>
        <br>
        <br>
        Text here <a href="https://www.cbsnews.com/sanfrancisco/news/surging-crime-dirty-streets-local-residents-say-san-franciscos-mission-district-is-in-crisis/" target="_blank"> MISSION DISTRICT - SUPER NICE REFERENCE </a> [X]
    </p>
    <p>
        Text here
    </p>
    <div>
        <h3>Figure 5: A Yearly District-Level Perspective on Crimes in San Francisco</h3>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/SF_CrimemapYearlyV2.html"
            width="1050"
            height="725"
            >
    </div>
    <h2>Concluding Thoughts</h2>
    <p>
        Text here
        <br>
        <br>
        Text here  
    </p>
    <a id="references" style="color:inherit; text-decoration: none !important;"><h2>References</h2></a>
    <ol type="1">
        <li>
            <a href="https://www.epowertrucks.co.uk/news/how-dirty-streets-are-affecting-the-environment-and-property-values-in-your-area/" target="_blank"> How Dirty Streets Are Affecting The Environment And Property Values In Your Area </a>
        </li>
        <li>
            <a href="https://abc7news.com/sf-tourism-san-francisco-streets-international-travelers-conventions-in/12227886/" target="_blank"> ABC News article: SF's 'dirty streets' hurting international tourism as conventions struggle to come back </a>
        </li>
        <li>
            <a href="https://www.sfchronicle.com/opinion/letterstotheeditor/article/sf-streets-are-not-safer-or-cleaner-17596059.php" target="_blank"> SF Chronicle: Letters: Why Mayor Breed’s efforts aren’t making S.F. streets safer or cleaner </a>
        </li>
        <li>
            <a href="https://londonformayor.com/policies/clean-streets-clean-city-2/" target="_blank"> Mayor Breed: Clean Streets, Clean City </a>
        </li>
        <li>
            <a href="https://sf311.org/" target="_blank"> SF 311 </a>
        </li>
    </ol>
    <footer>
        <p>
            Click the link below to get a walkthrough of our data processing.
            <br>
            <a href="https://github.com/GustavHansen99/SocialDataFinalProject/blob/master/coding/project_notebook.ipynb" target="_blank">Github Repository</a>
        </p>
    </footer>