<template>
  <section class="section-progress text-center">
    <div class="container">
      <div class="row">
        <div class="col-md-4 progress-item">
          <div><i class="fas fa-bullhorn"></i></div>
          <div class="num">500+</div>
          <h4><span>Successfully</span> completed projects</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore aspernatur quas voluptatibus sed dolor optio architecto, praesentium ullam dolorum alias soluta deserunt quod quidem quaerat officiis ipsa quae, magnam esse?</p>
        </div>
        <!-- /.col-md-4 progress-item -->
        <div class="col-md-4 progress-item">
          <div><i class="fas fa-bullhorn"></i></div>
          <div class="num">254+</div>
          <h4><span>Highly</span> specialised employees</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore aspernatur quas voluptatibus sed dolor optio architecto, praesentium ullam dolorum alias soluta deserunt quod quidem quaerat officiis ipsa quae, magnam esse?</p>
        </div>
        <!-- /.col-md-4 progress-item -->
        <div class="col-md-4 progress-item">
          <div><i class="fas fa-bullhorn"></i></div>
          <div class="num">45+</div>
          <h4><span>Awards</span> around the world</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore aspernatur quas voluptatibus sed dolor optio architecto, praesentium ullam dolorum alias soluta deserunt quod quidem quaerat officiis ipsa quae, magnam esse?</p>
        </div>
        <!-- /.col-md-4 progress-item -->
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'SectionProgress'
  }
</script>

<style>
  .section-progress{
    background-color: #4b2d7f;
    color: #fff;
    font-size: 15px;
    padding: 0;
  }
  .section-progress i{
    font-size: 70px;
  }
  .section-progress .num{
    font-size: 50px;
    font-weight: 600;
    margin: 30px 0 20px;
  }
  .section-progress h4{
    font-size: 30px;
    height: 72px;
    overflow: hidden;
  }
  .section-progress .progress-item{
    padding-top: 80px;
    padding-bottom: 80px;
    transition: all .5s;
  }
  .section-progress .progress-item:hover{
    background-color: #40286a;
  }

</style>
