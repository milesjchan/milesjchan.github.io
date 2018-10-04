---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div class="row">
  <div class="col-sm">
  <!-- Carousel -->
    <div id="carouselindex" class="carousel slide mb-3" data-ride="carousel">
    <!-- indicators -->
      <ol class="carousel-indicators">
        <li data-target="#carouselindex" data-slide-to="0" class="active"></li>
        <li data-target="#carouselindex" data-slide-to="1"></li>
        <li data-target="#carouselindex" data-slide-to="2"></li>
        </ol>
        <!-- slideshow -->
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-100" src="{{site.url}}/assets/carousel/holding_plane.jpg" alt="First slide">
          <!-- <div class="carousel-caption d-none d-md-block">
            <h5>Flying Model Airplanes</h5>
            <p>Most things are better with friends.</p>
            </div> -->
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="{{site.url}}/assets/carousel/plane.jpg" alt="Second slide">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="{{site.url}}/assets/carousel/climbing_halfdome.jpg" alt="Third slide">
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselindex" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselindex" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>

  <div class="col-sm">
    <h3>Welcome!</h3>
    <p class="text-justify">I'm Miles, an undergraduate mechanical engineering student at Georgia Tech and aspiring researcher in fluid mechanics. My desire to understand the physics describing natural and man-made systems has always defined my professional aspirations. I enjoy volunteering at the Invention Studio campus makerspace, and working on research, class, and personal projects.</p>
    <p>Please check out my work, displayed right here on this website!</p>
  </div>
</div>
