<template>
<div class="container">
    <h1>Technology</h1>
        <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4">
        <div class="col mb-4">
            <div class="card border-0">
                <img src="../assets/Frame 3.png" class="card-img-top" alt="icon1">
                <div class="card-body">
                    <h4>01</h4>
                    <h5 class="card-title">Cloud Storage</h5>
                    <p class="card-text">We support all popular currencies and is fully customizable to add</p>
                </div>
            </div>
        </div>
        
        <div class="col mb-4">
            <div class="card border-0">
                <img src="../assets/Frame 4.png" class="card-img-top" alt="icon2">
                <div class="card-body">
                    <h4>02</h4>
                    <h5 class="card-title">Secure</h5>
                    <p class="card-text">You can access your account from anywhere in the world on any device</p>
                </div>
            </div>
        </div>

        <div class="col mb-4">
            <div class="card border-0">
                <img src="../assets/Frame 6.png" class="card-img-top" alt="icon3">
                <div class="card-body">
                    <h4>03</h4>
                    <h5 class="card-title">PDF Download</h5>
                    <p class="card-text">Our software is made so you can access and manage your budget</p>
                </div>
            </div>
        </div>

        <div class="col mb-4">
            <div class="card5 border-0">
                <img src="../assets/Frame 5.png" class="card-img-top" alt="icon4">
                <div class="card-body">
                    <h4>04</h4>
                    <h5 class="card-title">CSV Download</h5>
                    <p class="card-text">Our software is made so you can access and manage your budget</p>
                </div>
            </div>
        </div>

    </div>
</div>
</template>

<script>
export default {
    name:'Technology'
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

img {
    z-index: 1;
    margin-top: 100px;
    margin-left: 225px;
    width: 70px;
    height: 70px;
}
.card-title {
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 22px;
    text-align: center;
}

.card5 {
    margin-top: 20px;
}

.card5 img {
    margin-left: 25px;
    width: 47px;
    height: 54px;
}

h4 {
    margin-top:-130px;
    margin-left: 175px;
    width: 117px;
    height: 120px;
    font-style: normal;
    font-weight: bold;
    font-size: 100px;
    line-height: 120px;
    color: rgba(16, 16, 16, 0.08);
}
    
h5 {
    margin-top: 19px;
}

p {
    position: absolute;
    width: 191px;
    height: 51px;
    margin-left: 140px;
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 14px;
    text-align: center;
}

/* desktop version */
@media (min-width: 992px) {
h1 {
    margin-left: 50px;
}
.card5 img {
    margin-left: 15px;
}
img {
    margin-left: 100px;
}
h4 {
    margin-left: 50px;
}
p {
    margin-left: 15px;
}
}



/* tablet version
@media (min-width: 768px) {
h1 {
    margin-left: -150px;
}
.card5 img {
    margin-left: -50px;
}
} */
</style>