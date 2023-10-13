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
              <h3>About<span class="color">Us</span></h3>
              <p>Systemz Matrix is a niche research and consultancy firm of Pakistan which is 
                dedicated to provide comprehensive services in the sectors of health and 
                education. Our strategic support helps the partnering organizations to 
                improve the existing systems in accordance with their laid down preset goals. 
                Systemz Matrix team is comprised of qualified consultants having rich 
                relevant experience.This vast experience enables us  to have an intimate 
                understanding of the challenges our clients face and subsequently provide 
                expertise in the best possible manner.
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
