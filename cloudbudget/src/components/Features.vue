<template>
<div class="container">
  <h1>Features</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3">
      <div class="col mb-4">
        <div class="card border-0">
          <img src="../assets/Bg1.png" class="card-img-top" alt="bg1">
          <div class="card-body">
            <h5 class="card-title">Supports All Currencies and Cards</h5>
            <p class="card-text">We support all popular currencies and is fully customizable to add</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>
      
      <div class="col mb-4">
        <div class="card border-0">
          <img src="../assets/Bg2.png" class="card-img-top" alt="bg2">
          <div class="card-body">
            <h5 class="card-title">Manage your expenses on the go</h5>
            <p class="card-text">You can access your account from anywhere in the world on any device</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>

      <div class="col mb-4">
        <div class="card border-0">
          <img src="../assets/Bg3.png" class="card-img-top" alt="bg3">
          <div class="card-body">
            <h5 class="card-title">Cloud Budget Management Software</h5>
            <p class="card-text">Our software is made so you can access and manage your budget</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>
      
    </div>
</div>
</template>

<script>
export default {
    name:'Features'
}
</script>

<style scoped>
h1 {
    margin-left: -300px;
    margin-top: 63px;
    width: 1110px;
    height: 55px;
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 43px;
    text-align: center;
  }

.row {
  margin-top: 63px;
}

.card-body {
  background-color: #ffffff;
  width: 293px;
  height: 198px;
  box-shadow: 0px 5px 30px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  margin-left: 100px;
  margin-top: -200px;
}

.card-title {
  margin-top: 10px;
  margin-left: 15px;
  width: 230px;
  height: 40px;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
}

.card-text {
  margin-top: 20px;
  margin-left: 15px;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 150%;
  text-align: center;
}

.btn {
  width: 253px;
  height: 18px;
  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 12px;
  line-height: 150%;
  text-align: center;
  color: #ED4C5C;
}

/* desktop version */
@media (min-width: 992px) {
  .card-body {
  margin-left: 30px;
  margin-top: -100px;
}

h1 {
    margin-left: 10px;
  }
}

</style>