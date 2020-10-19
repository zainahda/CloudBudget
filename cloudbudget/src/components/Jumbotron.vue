<template>
    <!-- jumbotron -->
    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">CloudBudget</h1>
        <p class="lead">Cloud budget management for everyone. Only <br> €69.95 a Month After a 7 Day Trial of <br> Up to €4.99</p>
        <a href="" class="btn btn-primary tombol">Sign Up</a>
      </div>
    </div>
   
   <!-- jumbotron end --> 
</template>

<script>
export default {
    name:'Jumbotron'
}
</script>

<style scoped>
/*jumbotron */
.jumbotron {
  background-image:url(../assets/1.png);
  background-size: cover;
  height: 782px;
  text-align: center;
  position: relative;
}

.jumbotron .container{
  z-index: 1;
  position: relative;
}

.jumbotron::after {
  content:"";
  display: block;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(90deg, rgba(213, 32, 71, 0.8) 0%, rgba(238, 61, 27, 0.8) 100%);
  position: absolute;
  bottom: 0;
}

.jumbotron .display-4{
  text-transform: uppercase;
  color: #ffffff;
  font-size: 50px;
  margin-top: 257px;
  font-weight: 700;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
}

.jumbotron .lead {
  color: #ffffff;
  font-size: 24px;
  margin-top: 39px;
  font-weight: 500;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
}

.jumbotron .btn {
  margin-top: 39px;
  background-color:white;
  color:#ED4C5C;

}
/* desktop version */
@media (min-width: 992px) {
    
    .jumbotron {
      margin-top: -125px;
    }

    .jumbotron .display-4 {
      font-size: 72px;
    }
}

</style>