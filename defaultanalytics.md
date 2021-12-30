---
title: DefaultAnalytics
layout: page
---

<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 35%;
  padding: 15px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>

<div class="row">
  <div class="column">
    <img src="/assets/images/cri-logo.png" alt="CRI Logo" style="width:100%">
  </div>
  <div class="column">
    <img src="/assets/images/Yield-Book-logo.png" alt="Yield Book Logo" style="width:100%">
  </div>
</div>

<p>
This product was created with collaboration with the Credit Research Initiative (<a href="https://nuscri.org/en/">CRI</a>), which is part of the National University of Singapore (NUS).
We used their database contatining daily Probability of Default (PD) data for all listed companies and mapped it to the bonds issues by those corporates.
This allowed us to distribute their data in our system and build additional analytics on top.
</p>

<p>
The analytics we developed used binomial option pricing method, with the option being the default event, hence creating default adjusted cashflows.
These cashflows were the base for the analytics. The notable analytics were Default Adjusted Spread and Default Adjusted Yield.
</p>

<p>
The main concept behind these analytics was to remove the default risk from the spread and the yield, hence providing users a more comprehensive understanding of the risks in their investments.
</p>

<p>
Some resources:  
</p>
<ul class="attachements">
<li> the link to the Go-To-Market webinar can be found <a href="https://www.brighttalk.com/webcast/9819/509722">here</a>.</li>
<li> the presentation slides can be found <a href="https://www.brighttalk.com/resource/core/366030/yield-book---introducing-default-adjusted-analytics-for-corporate-bonds_795494.pdf">here</a>.</li>
<li> the factsheet about the product can be found <a href="https://www.brighttalk.com/resource/core/366328/yield-book-credit-default-adjusted-analytics_795626.pdf">here</a>.</li>
</ul>

