---
layout: post
title:  "udn Digital"
date:   2015-09-30 18:11:02
categories: portfolio
featured: true
featured_image: "../assets/img/portfolio/cabin.png"
tags: design
---
<p class="summery">udn Digital is a subsidiary company of United Daily News, which is one of the most influential news corporations in Taiwan. My team developed systems for the corporation with ASP.NET MVC framework.
</p>
<ul class="task-list">
  <li id="NewsSmith">
    <strong>NewsSmith</strong></br>
    <ul class="task-info">
      <li>Duration: Sep 2014 - Aug 2015</li>
      <li>Backend: ASP.NET MVC, C#, SQL, SignalR, Entity Framework</li>
      <li>Frontend: knockout.js, Bootstrap</li>
    </ul>
    <p class="article-section">
      NewsSmith is brand-new news editing system for United Daily News.
      Compare to the previous system which is too complicated to use, NewsSmith is praised for its better UI design and utility.
    </p>
    <p class="article-section">
      In this project, I participated in the dicussion of UI design, and I tesed the system when it came out updated codes or new versions. 
      I found many bugs that were not easy to diagnose, and my team members appreciated what i did a lot. On the other hand, I wrote a tutorial webpage for the system, which made me more familiar with MVC structure.
    </p>
    <p>
      <img src="../assets/img/portfolio/udn/newsSmith01.png">
      <img src="../assets/img/portfolio/udn/newsSmith02.png">
    </p>
  </li>
  <li id="UCD">
    <strong>UCD Searching Engine</strong></br>
    <ul class="task-info">
      <li>Duration: Sep 2015 - Mar 2016</li>
      <li>Backend: ASP.NET MVC, C#, Elastic Search, SignalR</li>
      <li>Frontend: Angular.js, TypeScript, Bootstrap</li>
      <li>Test: Selenium, Specflow</li>
    </ul>
    <p class="article-section">    
      UCD is a news images/text searching engine for United Daily News.
      Compare to the previous system which is awkward to use, the new version of UCD we developed is praised for its better UI design and speed.
    </p>
    <p class="article-section">    
      In this project, I participate in designing and building the UI, and I wrote automatic test system with selenium and specflow. Because of my automatic test system, we didn't have to test manually whenever new code version comes out, which saved a lot of time and made the project process more efficiently.
    </p>
  </li>
  <li id="PMG">
    <strong>Production Management System</strong></br>
    <ul class="task-info">
      <li>Duration: Mar 2016 - Oct 2016</li>
      <li>Backend: ASP.NET MVC, C#, Entity Framework, SignalR</li>
      <li>Frontend: knockout.js, Bootstrap</li>
      <li>Test: Selenium, Specflow</li>
    </ul>
    <p class="article-section">
      Production Management System is a system for printing department of United Daily News. The previous version of system was of bad design, both in UI and code structure. We redesigned the UI as well as the code structure, and the result was a big win. The new system is praised for its better UI design, and better stability. 
    </p>
    <p class="article-section">
      In this project, I was responsible for all the front-end part, including the UI prototyping and programming. I learned a lots of front-end techniques from this project, and I really appreciate my team for giving me such an oppotunity.
    </p>
  </li>
</ul>

<style>
  .summery{
    margin-left: 2rem;
    font-size: 18px;
    margin-bottom: 2rem;
  }

  .task-list > li{
    margin-bottom: 3rem;
  }

  .task-list > li > strong{
    font-size: 20px;
  }  

  .task-info{
    list-style: none;
    padding: 0.5rem 1rem;
    margin: 0.5rem 0 1rem 0;
    color: lightslategray;
    border: 1px solid rgba(119,136,153, 0.6);
    border-radius: 5px;
    background: rgba(119,136,153, 0.05);
  }

 .article-section{
   margin: 1rem 0;
 }

  img{
    box-shadow: 0 0 5px #cccccc;
    margin-bottom: 1rem;
  }
</style>