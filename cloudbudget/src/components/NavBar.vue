<template>
    <!-- nav bar -->
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-cloud-fill" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" d="M4.406 3.342A5.53 5.53 0 0 1 8 2c2.69 0 4.923 2 5.166 4.579C14.758 6.804 16 8.137 16 9.773 16 11.569 14.502 13 12.687 13H3.781C1.708 13 0 11.366 0 9.318c0-1.763 1.266-3.223 2.942-3.593.143-.863.698-1.723 1.464-2.383z"/>
        </svg>
      <a class="navbar-brand" href="#">cloudbudget</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ml-auto mr-auto">
          <a class="nav-link active" href="#">Overview <span class="sr-only">(current)</span></a>
          <a class="nav-link" href="#">Features</a>
          <a class="nav-link" href="#">Technology</a>
          <a class="nav-link" href="#">Contact</a>
          <a class="nav-link" href="#">Sign Up</a>
          <a class="btn btn-primary tombol" href="#">Login</a>
        </div>
      </div>
    </div>
    </nav>
    <!-- navbar end -->
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style scoped>
    /* navbar */
.navbar{
  position: relative;
  z-index: 1;
}

.navbar-brand {
    font-family:Lato;
    font-size: 20px;
    text-transform: uppercase;
    font-weight: 700;
}

.navbar-nav .btn{
  background-color:#ED4C5C;
  color:white;
  border-color: white;
  width: 100px;
  height: 40px;
}

/* desktop version */
@media (min-width: 992px) {

  .navbar {
    margin-top: 58px;
  }

  .navbar-brand, .nav-link{
    color: #ffffff !important;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
  }

  svg {
    color:#FFFFFF;
    margin-right: 10px;
  }

    .nav-link {
        text-transform: uppercase;
        margin-right: 25px;
    }

    .nav-link:hover::after {
        content:"";
        display: block;
        border: 3px solid #FFFFFF;
        width: 50%;
        margin: auto;
        padding-bottom: 5px;  
        margin-bottom: -11px; 
    }
}
</style>
    