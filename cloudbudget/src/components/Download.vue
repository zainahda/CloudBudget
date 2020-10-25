<template>
  <div class="container2">
    <div class="row">
      <div class="col-lg-6">
        <h2 class="text-left">Stay focused on saving money</h2>
        <p class="text-justify">
          It is important to stay focused on saving money in any way you can. We
          help you monitor your spending habits so you can easily spot and cut
          any unnecessary expenses. Simply join today to get started!
        </p>
        <div class="links">
          <ul class="mb-4">
            <li>
              <a href><i class="fab fa-google-play"></i></a>
            </li>
            <li>
              <a href><i class="fab fa-app-store"></i></a>
            </li>
            <li>
              <a href><i class="fab fa-windows"></i></a>
            </li>
          </ul>
        </div>
      </div>
      <div
        id="carouselExampleControls"
        class="col-lg-6"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/Video_bg.svg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/Video_bg(1).svg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/Video_bg(2).svg" class="d-block w-100" alt="..." />
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleControls"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleControls"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Download",
};
</script>

<style>
.container2 {
  background-color: #ed4c5c;
}

.text-left {
  padding-top: 122px;
  padding-left: 27px;
  padding-right: 10px;
  color: #ffffff;
}
.text-justify {
  padding-left: 27px;
  padding-right: 10px;
  color: #ffffff;
}
.links {
  padding-top: 0px;
  padding-bottom: 100px;
  padding-left: 20px;
}
.links ul {
  list-style: none;
  padding: 0;
  justify-content: center;
}

.links ul li {
  float: left;
}

.links ul li a {
  padding: 10px;
  text-decoration: none;
  color: #ffffff;
  transition: 0.6s;
}
.links ul li a:hover {
  color: #0f0474;
}
.col-lg-6{
  margin-top: 50px;
}
.row{
  margin-left: 10px;
}
</style>
