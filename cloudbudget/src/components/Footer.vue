<template>
  <!-- footer -->
    <div class="container">
        <div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-4">
            <div class="col">
                <h3 id="address" class="text-body">Address</h3>
                <h4 id="address1">Pipang Ltd,Griva Digeni,<br>81-83 Jacovides Tower, 1st Floor<br>1090 Picosia USA</h4>            </div>
            <div class="col">
                <h3 id="services" class="text-body">Services</h3>
                <ul id="services2" class="nav-menu">
                    <li><a href>Overview</a></li>
                    <li><a href>Feature</a></li>
                    <li><a href>Technology</a></li>
                    <li><a href>Terms & Condition</a></li>
                    <li><a href>Privacy</a></li>
                </ul>
            </div>
            <div class="col">
                <h3 id="getin" class="text-body">Get In Touch</h3> 
                <h4 id="emailinfo"><a href>info@cloudbudget.com</a></h4>
                <h4 id="phone">+1 844-721-7120</h4>
                <div class="social-icons">
                    <ul class="mb-4">
                        <li><a href><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href><i class="fab fa-linkedin-in"></i></a></li>            
                        <li><a href><i class="fab fa-twitter"></i></a></li>           
                    </ul>
                </div>
            </div>
            <div class="col">
                <h3 id="support" class="text-body">We Support</h3>
                <img src="../assets/secure-p-1 1.svg" class=img-fluid>
            </div>
        </div>
        <div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-4">
            <div class="col">
                <h4 id="address2">Copyright 2018 CloudBudget</h4>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style scoped>

    .col{
        padding-top: 85px;
        padding-bottom: 0px;

    }
    .container{
        font-size:18px;
        max-width: inherit ;
        top: 3487px;
        background-color: #fafafa;
        padding: auto;
        margin: auto;
    }
    #address {
        font-style: normal;
        font-weight: bold;
        font-size: 18px;
        line-height: 22px;
        margin-left: 10px;
        padding-left: 10px;
       
    }
    #address1 {
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 150%;
        margin-left: 10px;
        padding-left: 10px;
    }
    #address2 {
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 14px;
        margin-left: 10px;
        padding-left: 10px;
    }
    #services {
        font-style: normal;
        font-weight: bold;
        font-size: 18px;
        line-height: 22px;
        color: #101010;
        margin-left: 10px;
        padding-left: 10px;
    }
    #services2 {
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 160%;
        list-style-type: none;
        color: #000000;
        padding: 0;
        margin-left: 10px;
        padding-left: 10px;
    }
    #services2 a:hover {
        text-transform: capitalize;
    }
    #getin {
        font-style: normal;
        font-weight: bold;
        font-size: 18px;
        line-height: 22px;
        text-align: left;
        color: #101010;
        margin-left: 10px;
        padding-left: 10px;
    }
    #emailinfo {
        font-family: Lato;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 14px;
        color: #101010;
        margin-left: 10px;
        padding-left: 10px;
    }
    #phone{
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 14px;
        color: #121212;
        margin-left: 10px;
        padding-left: 10px;
    }
    .social-icons {
        padding-top: 0px;
        margin-left: 10px;
        padding-left: 10px;
        
    }
    .social-icons ul {
	list-style: none;
	padding: 0;
	justify-content: center;
    }
    
    .social-icons ul li {
        float: left;
    }

    .social-icons ul li a {
	padding: 10px;
	text-decoration: none;
	color:  #121212;
	transition: 0.6s;
    }
    .social-icons ul li a:hover {
	color: #121212;
    }
    #support{
        font-style: normal;
        font-weight: bold;
        font-size: 18px;
        line-height: 22px;
        color: #101010;
        margin-left: 10px;
        padding-left: 10px;
    }
    .img-fluid{
        margin-left: 10px;
        padding-left: 10px;
    }

</style>