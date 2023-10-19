<template>
  <div class="about-area about-2 fix">
    <div class="container-full">
      <div class="row">
        <!--
        <div class="col-md-5 col-sm-4 col-xs-12">
          <div class="about-image">
           
            <div class="video-content ">
              <a href="https://www.youtube.com/watch?v=O33uuBh6nXA" class="video-play vid-zone">
                <i class="fa fa-play"></i>
              </a>
            </div>
            
          </div>
        </div>
        -->
        <div class="">
          <div class="support-all about-content">
            <div class="section-headline right-headline white-headline">
              <div style="display: flex; align-items: center; justify-content: center">
              <h3>About Us</h3>
              </div>
              <p>Systemz Matrix is a niche research and consultancy firm from Pakistan,
                dedicated to provide the comprehensive services in the fields of health,
                education and environment.  At Systemz Matrix, we have a team of 
                qualified consultants with rich relevant experience which enables 
                us to provide the required expertise in the best possible manner. 
                Our strategic support helps the partnering organizations to improve 
                their existing systems accordingly to their laid down preset goal.
              </p>
            </div>
            <!--
            <div class="about-company">
              <div class="single-about">
                <span class="about-text">Collegiality </span>
                <span class="about-text">Discipline </span>
                <span class="about-text">Live chat upport</span>
              </div>
              <div class="single-about">
                <span class="about-text">Integrity </span>
                <span class="about-text">Commitment</span>
                <span class="about-text">Marketing expert policy</span>
              </div>
            </div>
          -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "About",
      mounted() {
        $('.video-play').magnificPopup({
          type: 'iframe'
        });
      }
    }
</script>

<style scoped>

</style>
