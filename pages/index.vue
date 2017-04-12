<template>
  <section class="container">
    <img src="https://www.netlify.com/img/global/meta-image.jpg" />
    <h1 class="title">
      Netlify Assesment
    </h1>
    <nuxt-link class="button" to="/about">
      Hello!
    </nuxt-link>
    
    
  </head>
<body>

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span> 
      </button>
      <a class="navbar-brand" href="#">Logo</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#services">SERVICES</a></li>
        <li><a href="#portfolio">PORTFOLIO</a></li>
        <li><a href="#pricing">PRICING</a></li>
        <li><a href="#contact">CONTACT</a></li>
      </ul>
    </div>
  </div>
</nav>

<style>
.jumbotron { 
    background-color: #f4511e; /* Orange */
    color: #ffffff;
}
</style>

<style>
.bg-grey {
    background-color: #f6f6f6;
}
</style>
<style>
.jumbotron {
    background-color: #f4511e;
    color: #fff;
    padding: 100px 25px;
}
.container-fluid {
    padding: 60px 50px;
}
</style>

<style>
.logo {
    font-size: 200px;
}
@media screen and (max-width: 768px) {
    .col-sm-4 {
        text-align: center;
        margin: 25px 0;
    }
}
</style>

<div class="container-fluid">
  <div class="row">
    <div class="col-sm-8">
      <h2>About Company Page</h2>
      <h4>Lorem ipsum..</h4> 
      <p>Lorem ipsum..</p>
      <button class="btn btn-default btn-lg">Get in Touch</button>
    </div>
    <div class="col-sm-4">
      <span class="glyphicon glyphicon-signal logo"></span>
    </div>
  </div>
</div>

<div class="container-fluid bg-grey">
  <div class="row">
    <div class="col-sm-4">
      <span class="glyphicon glyphicon-globe logo"></span> 
    </div>
    <div class="col-sm-8">
      <h2>Our Values</h2>
      <h4><strong>MISSION:</strong> Our mission lorem ipsum..</h4> 
      <p><strong>VISION:</strong> Our vision Lorem ipsum..</p>
    </div>
  </div>
</div>



</body>
</html>
</section>
</template>
    
 
<style scoped>
.title
{
  margin: 50px 0;
}
</style>




