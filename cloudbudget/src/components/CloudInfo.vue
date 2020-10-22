<template>
    <!-- info -->
      <div class="container">
      <div class="row overview">

        <div class="col overview-info">
          <h4> Easy to Use Cloud Budget<br> Management Software</h4>
          <p>Our software is made so you can access and manage your budget and expenses online at any time from any device. It provides detailed income and expense reports with graphs so you can easilly see your spending patterns and budget at a glance. Read below to find out more.</p>
          <a href="" class="btn">Learn More</a>
        </div>

        <div class="col overview-img">
          <img src="../assets/Video_bg.png" alt="meetings"></div>
           <button class="btn">
               <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-play-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path d="M11.596 8.697l-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z"/>
</svg>
           </button>
        </div>
    </div>
      <!-- info end -->
</template>

<script>
export default {
    name: 'CloudInfo'
}
</script>

<style scoped>
/* overview */

.overview-info h4{
  margin-top: 140px;
  font-size: 36px;
  font-weight: 600;
  text-align: center;
}

.overview-info p{
  width: 445px;
  margin-top: 24px;
  font-size: 14px;
  font-weight: 400;
  text-align:justify;
}

.overview-info a{
  margin-left: -100px;
  font-size: 14px;
  font-weight: 400;
  color: #ED4C5C;
}

.overview-img img{
  justify-content: center;
  border-radius: 15px;
  margin-top: 94px;
  border-color: #C4C4C4, 100%;
}
 
button {

  position: absolute;
  width: 66px;
  height: 66px;
  margin-top: 650px; 
  margin-left: 250px;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #ED4C5C;
  color: white;
  font-size: 18px;
  padding: 20px;
  border: none;
  cursor: pointer;
  border-radius: 50%;
}

button svg {
   font-size: 18px; 
}


.overview-btn {
  justify-content: center;
  align-content: center;
  margin-top: 217px;
  margin-left: 702px;
}

.overview-btn a {
  color: #FFFFFF;
  background-color: #ED4C5C;
  border-radius: 50%;
  width: 66px;
  height: 66px;
}



/* desktop version */
@media (min-width: 992px) {

.overview-info h4{
    text-align: left;
}

.overview-info a{
  margin-left: -465px;
}

button {
  position: absolute;
  margin-top: 241px; 
  margin-left: 630px;
}
}



</style>