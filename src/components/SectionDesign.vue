<template>
  <section class="section-design">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <h3>We are best and creative agency</h3>
          <h4>We turn creative ideas into your business</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam ipsam, quas, illo laborum molestias nihil dolore nobis quis, quam reiciendis asperiores. Accusamus consequatur ipsum asperiores dolore perferendis, tempore ducimus blanditiis.</p>
          <div class="row">
            <div class="col-md-6 mb-3">
              <span><i class="far fa-comments"></i></span>
              <h2>Graphic Design</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, amet totam modi optio, a quae.</p>
              <p><a href="#" class="btn btn-pink btn-shadow">Read more</a></p>
            </div>
            <!-- /.col-md-6 -->
            <div class="col-md-6 mb-3">
              <span><i class="fas fa-bullhorn"></i></span>
              <h2>Graphic Design</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, amet totam modi optio, a quae.</p>
              <p><a href="#" class="btn btn-pink btn-shadow">Read more</a></p>
            </div>
            <!-- /.col-md-6 -->
          </div>
          <!-- /.row -->
        </div>
        <!-- /.col-lg-6 -->
        <div class="col-lg-6">
          <div class="embed-responsive embed-responsive-16by9 mt-5">
            <iframe id="videoPlayer" class="embed-responsive-item" src="https://www.youtube.com/embed/--4WpisLl9k?enablejsapi=1&amp;html5=1&amp;rel=0&amp;&amp;showinfo=0" allowfullscreen></iframe>
            <div id="videoPlayBtn"></div>
          </div>
        </div>
        <!-- /.col-lg-6 -->
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'SectionDesign'
  }
</script>

<style scoped>
  .section-design h3,
  .section-design h4{
    color: #484848;
  }
  .section-design h3{
    font-size: 33px;
  }
  .section-design span i{
    font-size: 60px;
    background: linear-gradient(45deg, rgba(255,0,32,.7) 0%,rgba(68,26,130,.8) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    padding-left: 15px;
  }
  .section-design h2{
    font-size: 25px;
    font-weight: 600;
    color: #484848;
    margin: 10px 0;
  }
  .section-design p{
    font-size: 14px;
  }
  .embed-responsive{
    position: relative;
    border-radius: 10px;
  }
  #videoPlayBtn{
    width: 100%;
    height: 100%;
    z-index: 1000;
    position: absolute;
    top: 0;
    cursor: pointer;
    background: url(../assets/img/play.png) center no-repeat;
  }
</style>
