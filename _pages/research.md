---
layout: single
title: "Research & Publications"
permalink: /research/
author_profile: true
---

<!-- For proper citations, refer [INSPIRE-HEP](https://inspirehep.net/authors/1613452?ui-citation-summary=true)
<br>
<br> -->

<!-- Pie Chart Start -->

<br>

<head>
  <title>Publications Pie Chart</title>
  <script src="https://canvasjs.com/assets/script/canvasjs.min.js"></script>
</head>
<body>
  <div id="chartContainer1" style="height: 300px; width: 100%;"></div>

<script>
var chart1 = new CanvasJS.Chart("chartContainer1", {
		theme: "dark1",
		title: {
			text: "Publications"
		},		
    animationEnabled: true,
    animationDuration: 2000,
		data: [
		{       
			type: "pie",
			showInLegend: "true",
      indexLabelFontSize: 14,
      indexLabelFontWeight: "bold",
      indexLabel: "{label}: {y}",
			toolTipContent: "<b>{label}</b>: #percent %",
			legendText: "{label}",
			dataPoints: [
				{  y: 16, label: "Peer-Reviewed" },
        {  y: 1,  label: "Conference papers" },
				{  y: 1,  label: "Preprints"}
			]
		}
		]
	});
	chart1.render();
  </script>

<!-- Pie Chart End -->

<BR>
<br>
<BR>
<br>

<!-- Research Areas -->


<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

figure {
  margin: 0;
  text-align: center;
}

figure img {
  width: 100%;
  height: auto;
  display: block;
}

.figcaption {
  text-align: center;
}

.fig-caption {
  text-align: center;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

.column img {
  margin-top: 12px;
  vertical-align: middle;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

</style>

<body>

<!-- <div class="header">  <h1> Research Areas </h1> </div> -->

<h1> Research Areas </h1>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <figure>
    <a href="/research/black-holes">
        <img src="/images/bh1.gif" >
    </a>
    <figcaption style="font-size: 16px; text-align: center;"><b>Black holes in Modified gravitational theories</b></figcaption>
    </figure>
    <!-- -->
    <figure>
    <a href="/research/astrophysics">
        <img src="/images/bh2.gif" >
    </a>
    <figcaption style="font-size: 16px; text-align: center;"><b>&nbsp;&nbsp;&nbsp;&nbsp;Astrophysical supermassive black holes</b></figcaption>
    </figure>
  </div>
  <!-- -->
  <div class="column">
    <figure>
    <a href="/research/BW-models">
        <img src="/images/braneworld.gif"  >
    </a>
    <figcaption style="font-size: 16px; text-align: center;"><b>Braneworld models and extra dimensional solutions</b></figcaption>
    </figure>
    <!-- -->
    <figure>
    <a href="/research/cosmology">
        <img src="/images/cosmo.gif"  >
    </a>
    <figcaption style="font-size: 16px; text-align: center;"><b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cosmology</b></figcaption>
    </figure>
  </div>
</div>

</body>

<!----------------->

<BR>
<br>
<BR>
<br>

<!-- Publication List Start -->

<h1 style="font-size=50px;"> Complete Publication List </h1>

<!---------------->

{% include_relative publications/paper-17-2603.17607.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-16-2510.09547.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-15-2505.02368.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-14-2504.01669.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-13-2412.19773.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-12-2402.12459.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-11-2312.17198.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-10-2310.11919.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-9-2309.00873.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-8-2303.09116.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-7-2107.05656.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-6-2105.06915.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-5-2012.09199.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-4-2010.00025.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-3-2001.07226.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-2-1904.00216.md %}

<BR>
<br>

<!---------------->

{% include_relative publications/paper-1-1807.06880.md %}


<!-- Publication List End -->

<BR>
<BR>

<!-- Conference papers List Start -->

<h1 style="font-size=50px;"> Conference Papers </h1>

{% include_relative publications/conf-paper-1-2025.md %}

<BR>
<br>

<!------------------>

<!-- Conference papers List End -->