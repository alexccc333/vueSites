<template>
  <header class="main-header">
    <nav class="navbar navbar-expand-lg">
      <a class="navbar-brand" href="#">
        <!--<img src="./assets/img/logo.png" alt=""> BlueRex-->
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <i class="fas fa-bars"></i>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="blog.html">Blog</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Features</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Product</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Reviews</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Faq</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </nav>

    <div class="main-header-text">
      <h3>We are best and creative agency</h3>
      <h4>We turn creative ideas into your business</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit doloribus non nam, velit nemo enim!</p>
      <div class="main-header-buttons">
        <button type="button" class="btn btn-pink rounded-pill">Our story</button>
        <button type="button" class="btn btn-violet rounded-pill">Read more</button>
      </div>
    </div>
    <!-- /.main-header-text -->
  </header>
</template>

<script>
  export default {
    name: 'header',
  }
</script>

<style scoped>
  body{
    font-family: 'Montserrat', sans-serif;
    min-width: 320px;
    color: #1d1d1d;
  }
  img{
    max-width: 100%;
    height: auto;
  }
  section{
    padding: 100px 0;
  }
  h3{
    font-style: italic;
    font-size: 42px;
    font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
  }
  h4{
    font-weight: 600;
    font-size: 44px;
    margin-bottom: 20px;
  }
  .scrollToTop{
    position: fixed;
    bottom: 60px;
    right: 50px;
    border-radius: 4px;
    display: none;
    font-size: 32px;
    height: 50px;
    width: 50px;
    z-index: 1001;
    color: #fff;
    transition: all .5s;
    background-color: #da1757;
    border: 0;
    cursor: pointer;
  }
  .scrollToTop:hover{
    background-color: #fff;
    text-decoration: none;
    outline: none;
    color: #da1757;
    border: 1px solid #da1757;
  }




  /* =============================header============================== */
  .main-header{
    background: url(../assets/img/main1.jpg) center no-repeat;
    background-size: cover;
    height: 100vh;
    min-height: 700px;
    position: relative;
  }
  .main-header .navbar-toggler{
    color: #fff;
  }
  .main-header .navbar-brand,
  .main-header ul li a{
    color: #fff;
    font-weight: 600;
  }
  .main-header .navbar-brand{
    font-size: 41px;
  }
  .main-header ul li a{
    font-size: 17px;
  }
  .main-header ul li a::after{
    content: '';
    display: block;
    width: 100%;
    background-color: #fff;
    height: 1px;
    transform: scale(0);
    transition: all .3s;
  }
  .main-header ul li a:hover::after{
    transform: scale(1);
  }
  .main-header-text{
    position: absolute;
    top: 25%;
    left: 5%;
    max-width: 600px;
    color: #fff;
    padding: 20px;
  }
  .main-header-buttons{
    padding-left: 30px;
  }
  .btn{
    font-size: 15px;
    font-weight: 600;
    color: #fff;
    text-transform: uppercase;
  }
  .main-header-buttons .btn{
    height: 60px;
    padding-left: 40px;
    padding-right: 40px;
    margin-right: 20px;
    margin-top: 30px;
    opacity: .8;
    box-shadow: 0 4px 16px rgba(0,0,0,.35);
    transition: all .5s;
  }
  .main-header-buttons .btn:hover{
    color: #fff;
    opacity: 1;
  }
  .btn-pink{
    background-color: #f42267;
  }
  .btn-violet{
    background-color: #69328e;
  }
</style>
