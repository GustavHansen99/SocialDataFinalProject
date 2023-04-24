---
layout: page
title: Who are we?
permalink: who_are_we/
---

<h1 align="center" class="page-heading">{{ page.title }}</h1>

<html>
<head>
	<title>The authors</title>
	<style>
		.column {
			float: left;
			width: 33.33%;
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
		}
        .border-right {
            border-right: 1px solid black;
        }
		.clearfix::after {
			content: "";
			clear: both;
			display: table;
		}
	</style>
</head>
<body>
	<div class="column border-right">
        <h3>Name1</h3>
        <img src="/SocialDataFinalProject/site_content/giphy.gif" alt="dog1" width="200">
        <br>
        <p>Bla bla bla</p>
	</div>
	<div class="column border-right">
        <h3 align="center">Name2</h3>
        <img src="/SocialDataFinalProject/site_content/giphy (1).gif" alt="dog2" width="200">
        <br>
        <p align="center">Bla bla bla</p>
	</div>
	<div class="column">
        <h3 align="center">Name3</h3>
        <img src="/SocialDataFinalProject/site_content/giphy (2).gif" alt="dog3" width="200">
        <br>
        <p align="center">Bla bla bla</p>
	</div>
	<div class="clearfix"></div>
</body>
</html>