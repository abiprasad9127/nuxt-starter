
<template>   
<section class="container">
    <img src="https://www.netlify.com/img/global/meta-image.jpg" />
    <h1 class="title">
      Netlify Assesment
    </h1>

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
    font-size: 19px;
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

<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="30">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container1">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage">Logo</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#q1">QUESTION 1</a></li>
        <li><a href="#q2">QUESTION 2</a></li>
        <li><a href="#q3">QUESTION 3</a></li>
        <li><a href="#q4">QUESTION 4</a></li>
        <li><a href="#q5">QUESTION 5</a></li>
        <li><a href="#q6">QUESTION 6</a></li>
        <li><a href="#q7">QUESTION 7</a></li>
        <li><a href="#q8">QUESTION 8</a></li>
        <li><a href="#q9">QUESTION 9</a></li>
        <li><a href="#q10">QUESTION 10</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="fluid1" id="services">
  <h2>Our Values</h2>
  <h4><strong>MISSION:</strong> Our mission lorem ipsum..</h4> 
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
  <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
</div>

<div class="jumbotron" id="portfolio">
  <h1>Company</h1> 
  <p>We specialize in blablabla</p> 
  <p>We specialize in blablabla</p> 
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
