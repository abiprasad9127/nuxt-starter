
<template>   
<section class="container">
<div>
    <img src="https://www.netlify.com/img/global/meta-image.jpg" />
    <h1 class="title">
      Netlify Assesment
    </h1>
</div>

 <head>
  <title>Bootstrap Theme Company Page</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  </head>
  
<style>
.jumbotron { 
    background-color: #f4511e; /* Orange */
    color: #ffffff;
}

 img {
  width: 200px;
  height: 200px;
  opacity:0.5;
}

.navbar {
    margin-bottom: 0;
    background-color: #f4511e;
    z-index: 9999;
    border: 0;
    font-size: 12px !important;
    line-height: 1.42857143 !important;
    letter-spacing: 4px;
    border-radius: 0;
}

.navbar li a, .navbar .navbar-brand {
    color: #fff !important;
}

.navbar-nav li a:hover, .navbar-nav li.active a {
    color: #f4511e !important;
    background-color: #fff !important;
}

.navbar-default .navbar-toggle {
    border-color: transparent;
    color: #fff !important;
}

.fluid1 {
    background-color: #f6f6f6;
    color: #000000;
}

.carousel-control.right, .carousel-control.left {
    background-image: none;
    color: #f4511e;
}

.carousel-indicators li {
    border-color: #f4511e;
}

.carousel-indicators li.active {
    background-color: #f4511e;
}

.item h4 {
    font-size: 15px;
    line-height: 1.375em;
    font-weight: 400;
    font-style: italic;
    margin: 40px 0;
}

.item span {
    font-style: normal;
}
</style>

<style scoped>
.title
{
  margin: 70px 0;
}
</style>

<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="10">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container1">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#q1">Question1</a></li>
        <li><a href="#q2">Question2</a></li>
        <li><a href="#q3">Question3</a></li>
        <li><a href="#q4">Question4</a></li>
        <li><a href="#q5">Question5</a></li>
        <li><a href="#q6">Question6</a></li>
        <li><a href="#q7">Question7</a></li>
        <li><a href="#q8">Question8</a></li>
        <li><a href="#q9">Question9</a></li>
        <li><a href="#q10">Question10</a></li>
      </ul>
    </div>
  </div>
</nav>

<div id="q1"></div>
<div class="fluid1">
  <h3>Question 1</h3>
  <h4>"Rank your 5 favorite, and least favorite, activities from this list: https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6"<br></h4> 
</div>

<div class="jumbotron">
  <h3>Answer 1</h3> 
  <p>5 things I would love to do:</p>
 *Dig through server logs to troubleshoot a customer's website behavior.
 *Analyze thousands of support tickets to spot trends to improve our product
 *Work with the development team to help design a new feature based on feedback from customers
 *Work with people to figure out if Netlify's service can solve a particular workflow or integration challenge they have
 *Work with prospective customers to explain our service and the pricing model</p> 

<p>Not as much:</p>
  *Write and maintain documentation for our software and blog posts for our website.
   *Create video tutorials to help teach users a specific feature or use case
   *Respond to Netlify fans on Twitter
   *Deliver a talk to many people you don't know at a conference or meetup
   *Submit bug reports and potentially bug fixes to closed and open source projects that Netlify maintains on GitHub</p>
</div>

<div class="fluid1" id="q2">
  <h3>Question 2</h3>
  <h4>"What is your favorite thing about providing technical support?"<br></h4> 
</div>

<div class="jumbotron">
  <h3>Answer 2</h3> 
  <p>There is always a huge learning curve with technical support because it helps me understand the real time issues of the product and keeps me updated about all the new features and its issues. That way it helps me understand and analayse better about the product as a whole.</p>
</div>

<div class="fluid1" id="q3">
  <h3>Question 3<br></h3> 
  <h4>What did you think of our service during the time you used it?  Be honest!  “it sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)<br></h4>
</div>

<div class="jumbotron">
  <h3>Answer 3</h3> 
  <p>We specialize in blablabla</p> 
</div>

<div class="fluid1" id="q4">
  <h3>Question 4</h3> 
  <h4>Tell about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it.<br></h4>
</div>

<div class="jumbotron">
  <h3>Answer 4</h3> 
  <p>It was great using the staticgen I was asked to refer. I started with using jekyll, but later I wasn't very comfortable with it because of it was all in Ruby and I decided to go ahead with nuxt ( hence, the extended period). I am new to web designing and github. And I must admit, it was a lot of fun seeing my continuious progression getting deployed on Netlify. I was also guided by w3schools to through the development of the web page.</p> 
</div>

<div class="fluid1" id="q5">
  <h3>Question 5</h3>
  <h4>Could you give us a suggestion to improve this test or the job posting?</h4> 
</div>

<div class="jumbotron">
  <h3>Answer 5</h3> 
  <p>I had a great time working on this assesment, and working on netlify. Everything was just done easily and it worked great with time! I can only just suggest to limit this assesment with time, because otherwise I found myself continuously trying to improve the web page and explore more static generators.</p> 
</div>

<div class="fluid1" id="q6">
  <h3>Question 6</h3>
  <h4>Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.</h4> 
</div>

<div class="jumbotron">
  <h3>Answer 6</h3> 
  <p>W3school helped me a lot through this assesment, because it gives a step by step guide for beginners in web designing (like me!). Through their guided documents and snippets I was not only able to understand and reproduce the framework for the web page but also customize it based on my liking.</p> 
</div>

<div class="fluid1" id="q7">
  <h3>Question 7</h3>
  <h4>Why do you think SSL/HTTPS is important?</h4> 
</div>

<div class="jumbotron">
  <h3>Answer 7</h3> 
  <p>SSL and HTTPS help secure the communication between the client and server through the internet from eavsdroppers. Communication through HTTPS and SSL is encrypted between the client and the server. </p> 
</div>

<div class="fluid1" id="q8">
  <h3>Question 8</h3>
  <h4>Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users</h4> 
</div>

<div class="jumbotron">
  <h3>Answer 8</h3> 
  <p>DNS records
  When a ping to a host fails, try pinging the host by IP address instead of the name. If it responds then the you will have to check the DNS server to make sure that a Host (A) record exists for the host. If the DNS serves does not have an appropriate Host(A) record it will be unable to resolve the host's name.</p>
</div>

<div class="fluid1" id="q9">
  <h3>Question 9</h3>
  <h2><strong>MISSION:</strong> Our mission lorem ipsum..</h2> 
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
</div>

<div class="jumbotron">
  <h3>Answer 9</h3> 
  <p>We specialize in blablabla</p> 
  <p>We specialize in blablabla</p> 
</div>

<div class="fluid1" id="q10">
  <h3>Question 10</h3>
  <h2><strong>MISSION:</strong> Our mission lorem ipsum..</h2> 
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
</div>

<div class="jumbotron">
  <h3>Answer 10</h3> 
  <p>We specialize in blablabla</p> 
  <p>We specialize in blablabla</p> 
</div>

<h2>What our customers say</h2>
  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
      <li data-target="#myCarousel" data-slide-to="4"></li>
      <li data-target="#myCarousel" data-slide-to="5"></li>
      <li data-target="#myCarousel" data-slide-to="6"></li>
      <li data-target="#myCarousel" data-slide-to="7"></li>
      <li data-target="#myCarousel" data-slide-to="8"></li> 
      <li data-target="#myCarousel" data-slide-to="9"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <h4>"Rank your 5 favorite, and least favorite, activities from this list: https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6"<br><span>x</span></h4>
      </div>
      <div class="item">
        <h4>"What is your favorite thing about providing technical support?"<br><span>There is always a huge learning curve with technical support because it helps me understand the real time issues of the product and keeps me updated about all the new features and its issues. That way it helps me understand and analayse better about the product as a whole. 
</span></h4>
      </div>
      <div class="item">
        <h4>"What did you think of our service during the time you used it?  Be honest!  “it sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)"<br><span>Chandler Bing, Actor, FriendsAlot</span></h4>
      </div>
      <div class="item">
        <h4>"Why do you think SSL/HTTPS is important?"<br><span>SSL and HTTPS help secure the communication between the client and server thrrough the internet from eavsdroppers. Communication through HTTPS and SSL is encrypted between the client and the server. </span></h4>
      </div>
       <div class="item">
        <h4>"Tell about how you made your site and why you chose the tools you did. Briefly explain a challenge you experienced in setting up this site and how you solved it."<br><span>It was great using the staticgen I was asked to refer. I started with using jekyll, but later I wasn't very comfortable with it because of it was all in Ruby and I decided to go ahead with nuxt ( hence, the extended period). I am new to web designing and github. And I must admit, it was a lot of fun seeing my continuious progression getting deployed on Netlify. I was also guided by w3schools to through the development of the web page.</span></h4>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<script>
$(document).ready(function(){
  // Add smooth scrolling to all links in navbar + footer link
  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {
      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
  
  $(window).scroll(function() {
    $(".slideanim").each(function(){
      var pos = $(this).offset().top;

      var winTop = $(window).scrollTop();
        if (pos < winTop + 600) {
          $(this).addClass("slide");
        }
    });
  });
})
</script>


</body>
</html>  
 </section>
 </template>
