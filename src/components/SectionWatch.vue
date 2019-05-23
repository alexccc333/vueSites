<template>
  <section class="section-watch section-tabs">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 mb-5">
          <h3>Dream Big Inspire the World</h3>
          <h4>We turn creative ideas into your business</h4>

          <ul class="nav nav-pills" id="myTab" role="tablist">
            <li class="nav-item">
              <a class="nav-link active rounded-pill" id="webdesign-tab" data-toggle="tab" href="#webdesign" role="tab" aria-controls="webdesign" aria-selected="true">Webdesign</a>
            </li>
            <li class="nav-item">
              <a class="nav-link rounded-pill" id="mobileapp-tab" data-toggle="tab" href="#mobileapp" role="tab" aria-controls="mobileapp" aria-selected="false">Mobile app</a>
            </li>
            <li class="nav-item">
              <a class="nav-link rounded-pill" id="branding-tab" data-toggle="tab" href="#branding" role="tab" aria-controls="branding" aria-selected="false">Branding</a>
            </li>
          </ul>
          <div class="tab-content" id="myTabContent">
            <div class="tab-pane fade show active" id="webdesign" role="tabpanel" aria-labelledby="webdesign-tab">
              <p>Webdesign Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur obcaecati vero aliquid libero doloribus ad, unde tempora maiores, ullam, modi qui quidem minima debitis perferendis vitae cumque et quo impedit.</p>
              <p><a href="#" class="btn btn-pink btn-shadow">Read more</a></p>
            </div>
            <div class="tab-pane fade" id="mobileapp" role="tabpanel" aria-labelledby="mobileapp-tab">
              <p>Mobile app Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur obcaecati vero aliquid libero doloribus ad, unde tempora maiores, ullam, modi qui quidem minima debitis perferendis vitae cumque et quo impedit.</p>
              <p><a href="#" class="btn btn-pink btn-shadow">Read more</a></p>
            </div>
            <div class="tab-pane fade" id="branding" role="tabpanel" aria-labelledby="branding-tab">
              <p>Branding Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur obcaecati vero aliquid libero doloribus ad, unde tempora maiores, ullam, modi qui quidem minima debitis perferendis vitae cumque et quo impedit.</p>
              <p><a href="#" class="btn btn-pink btn-shadow">Read more</a></p>
            </div>
          </div>

        </div>
        <!-- /.col-md-6 -->

        <div class="col-lg-6 text-center">
          <img src="../assets/img/watch.png" alt="">
        </div>
        <!-- /.col-md-6 -->
      </div>
    </div>
  </section>
  <!-- /.section-watch -->
</template>

<script>
  export default {
    name: 'section-watch'
  }
</script>

<style>
  /* =============================.section-watch============================== */
  .section-watch{
    background: url(../assets/img/world_map.png) center no-repeat;
    background-size: cover;
  }
  .section-watch h3,
  .section-watch h4{
    color: #484848;
  }
  .section-tabs .nav-pills{
    margin-bottom: 20px;
  }
  .section-tabs .nav-pills .nav-link{
    font-size: 13px;
    font-weight: 600;
    text-transform: uppercase;
    padding: 14px 30px;
    color: #484848;
  }
  .section-tabs .nav-pills .nav-item .nav-link.active{
    background-color: #f42267;
    color: #fff;
    box-shadow: 0 4px 16px rgba(0,0,0,.35);
  }
  .btn-shadow{
    box-shadow: 0 10px 0 #ff5990;
    border-radius: 10px;
    padding: 10px 25px;
    transition: all .5s;
  }
  .btn-shadow:hover{
    box-shadow: 0 5px 0 #ff5990;
    color: #fff;
    background-color: #da1757;
  }

</style>
