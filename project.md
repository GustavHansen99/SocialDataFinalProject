---
layout: page
title: 3-1-1 Cases in San Francisco
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
        Text here
        <br>
        <br>
        Text here
        <br>
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
    <h2>Yet another title of something cool</h2>
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
    <h2>Temporary viz storage</h2>
    <div>
        <h4 style="text-align:center">Map Yearly</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/assets/images/SF_mapYearly.html"
            width="1100"
            height="620"
            >
    </div>
    <div>
        <h4 style="text-align:center">Examples of requested cleaning tickets</h4>
        <embed 
            type="text/html" 
            src="/SocialDataFinalProject/site_content/slideshow.html"
            width="1050"
            height="600"
            >
    </div>
    <footer>
        <p>
            Click the link below to get a walkthrough of our data processing.
            <br>
            <a href="https://github.com/GustavHansen99/SocialDataFinalProject/blob/master/coding/project_notebook.ipynb" target="_blank">Github Repository</a>
        </p>
    </footer>
</body>