<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="row">
            <div class="col-6">
              <h5>Company</h5>
              <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Aproach</a></li>
                <li><a href="#">Sustainability</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>
            <!-- /.col-6 -->
            <div class="col-6">
              <h5>Company</h5>
              <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Aproach</a></li>
                <li><a href="#">Sustainability</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>
            <!-- /.col-6 -->
            <div class="col-6">
              <h5>Company</h5>
              <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Aproach</a></li>
                <li><a href="#">Sustainability</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>
            <!-- /.col-6 -->
            <div class="col-6">
              <h5>Company</h5>
              <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Aproach</a></li>
                <li><a href="#">Sustainability</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">News</a></li>
              </ul>
            </div>
            <!-- /.col-6 -->
          </div>
        </div>
        <!-- /.col-md-6 -->

        <div class="col-md-6 footer-images">
          <div class="row">
            <div class="col-6">
              <img src="../assets/img/footer_img1.jpg" alt="">
            </div>
            <div class="col-6">
              <img src="../assets/img/footer_img1.jpg" alt="">
            </div>
            <div class="col-6">
              <img src="../assets/img/footer_img1.jpg" alt="">
            </div>
            <div class="col-6">
              <img src="../assets/img/footer_img1.jpg" alt="">
            </div>
          </div>
        </div>
        <!-- /.col-md-6 -->
      </div>
    </div>
  </footer>



</template>

<script>
  export default {
    name: 'Footer'
  }
</script>

<style scoped>
  .footer{
    background: url(../assets/img/world_map.png) center no-repeat;
    background-size: cover;
    padding: 100px 0;
    font-family: 'Poppins', sans-serif;
  }
  .footer h5{
    font-size: 25px;
    color: #4b2d7f;
    font-weight: 700;
  }
  .footer ul{
    list-style: none;
    padding-left: 10px;
  }
  .footer ul li a{
    font-size: 15px;
    font-weight: 600;
    color: #171717;
  }
  .footer-images img{
    margin-bottom: 20px;
    border-radius: 15px;
  }
  .copyright{
    background-color: #f6f6f6;
    padding: 50px 0;
    font-family: 'Poppins', sans-serif;
  }
  .copyright a,
  .copyright span{
    color: #171717;
    font-size: 18px;
    font-weight: 600;
    position: relative;
  }
  .copyright a:hover{
    text-decoration: underline;
  }
  .copyright li a::after,
  .copyright li span::after{
    content: '\00B7';
    position: absolute;
    right: -3px;
  }
  .copyright li:last-child a::after,
  .copyright li:last-child span::after{
    content: '';
  }
</style>
