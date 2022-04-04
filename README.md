# semantic_html_refactor
Refactoring a marketing agency website to use semantic HTML

HTML https://github.com/Winner-AM1/semantic_html_refactor.git

_Summary_ 

I have refactored a website for "Horiseon Inc in this project." To make the website more accessible, I have added alt text. I understand that search engine optimisation is a vital part of the company, so I have even decided to add as much as semantic HTML elements as possible by removing the <div> in the previous code. To stop a higher likelihood of having bugs, I have reduced the repeated CSS in the CSS files and ensured that HTML changes are followed through in the CSS.

_Head and broken navigation bar Before_
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>

<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimizat
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Man
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>\
        </div>
    </div>
    <div class="hero"></div>
    <div class="content">

_



Head and fixed navigation bar after_ 
 *semantic HTML was added making it more search engine optimised)* 
<head>
   <meta charset="UTF-8" />
   <link rel="stylesheet" href="./assets/css/style.css">
   <title> Refactoring HTML and CSS code for Horiseon Inc. </title>
</head>
<body>
    <!--header with a navigation bar-->
  <header class="header">
     <h1>Hori<span class="seo">seo</span>n</h1>
    <nav class="navbar">
       <nav class="button">
       <a href="#search-engine-optimization">Search Engine Optimization<
       </nav>
       <nav class="button">
       <a href="#online-reputation-management">Online Reputation Managem
       </nav>
       <nav class="button">
       <a href="#social-media-marketing">Social Media Marketing</a>
       </nav>
    </nav>
  </header>  
     <!--background cover image-->
     <div class="hero" > </div>


_



Content (before)_
 <div class="content">
     <div class="search-engine-optimization">
         <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
         <h2>Search Engine Optimization</h2>
         <p>
             The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increas
         </p>
     </div>
     <div id="online-reputation-management" class="online-reputation-management">
         <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
         <h2>Online Reputation Management</h2>
         <p>
             The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management giv
         </p>
     </div>
     <div id="social-media-marketing" class="social-media-marketing">
         <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
         <h2>Social Media Marketing</h2>
         <p>
             Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets an
         </p>
     </div>
 </div>


_Content(After)_
<main>
  
  <!--
  <!--content that can be found via navigation bar -->
  <section class="content">
  <article id="search-engine-optimization" class="features">
  <img src="./assets/images/search-engine-optimization.jpg"  
  alt= " In a workspace, on the table there is: a macbook, a pen-holder, coffee and a notepad. Within the notepad is brainstorm of what are important qualities required for an SEO setup which are: content
  class="float-left" />
  <h2>Search Engine Optimization</h2>
  <p>
  The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase yo
  </p>
  </article>
  <article id="online-reputation-management" class="features">
  <img src="./assets/images/online-reputation-management.jpg" alt= "A person on their laptop analysing their online reputation via a graph" class="float-right" />
  <h2>Online Reputation Management</h2>
  <p>
  The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives y
  </p>
  </article>
  <article id="social-media-marketing" class="features">
  <img src="./assets/images/social-media-marketing.jpg" alt="A group of people, around a table, have elements that are important for social media marketing"class="float-left" />
  <h2>Social Media Marketing</h2>
  <p>
  Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and in
  </p>
  </article>
 </section>

 _Side bar (before)_
 </div>
 <div class="benefits">
     <div class="benefit-lead">
         <h3>Lead Generation</h3>
         <img src="./assets/images/lead-generation.png" />
         <p>
             Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
         </p>
     </div>
     <div class="benefit-brand">
         <h3>Brand Awareness</h3>
         <img src="./assets/images/brand-awareness.png" />
         <p>
             Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
         </p>
     </div>
     <div class="benefit-cost">
         <h3>Cost Management</h3>
         <img src="./assets/images/cost-management.png" />
         <p>
             As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
         </p>
     </div>

_Side bar(After)_
<aside class="benefits">
 <aside class="leadbrandcost">
 <h3>Lead Generation</h3>
 <img src="./assets/images/lead-generation.png" alt="a black watermark showing technical information being fed to make dollars" />
 <p>
 Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
 </p>
 </aside>
 <aside class="leadbrandcost">
 <h3>Brand Awareness</h3>
 <img src="./assets/images/brand-awareness.png" alt= "a black watermark which has a suited man's head replaced with a light bulb"/>
 <p>
 Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
 </p>
 </aside>
 <aside class="leadbrandcost">
 <h3>Cost Management</h3>
 <img src="./assets/images/cost-management.png" alt="A black watermark displays a clog with three dollars- two of which have white text on a black background, while the la
 <p>
  As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
 </p>
 </aside>
</aside>


In CSS, I removed the repetitive css as a results of unnecessary different selectors added to same elements.

css before ![ css before](/assets/images/CSS%20before.png "CSS before")

css after ![css after ](/assets/images/CSS%20after.png"CSS after")








