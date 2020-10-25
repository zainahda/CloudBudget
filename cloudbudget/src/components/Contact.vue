<template>
  <div class="container1">
    <div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-2">
      <div class="col-lg-6">
        <h2 id="contact">Contact</h2>
        <p id="text1">
          Questions or concerns? Just fill out the form below and our support
          team will get back to you within 24 hours
        </p>
      </div>

      <div class="col-lg-6">
        <form id="form">
          <div class="form-row">
            <div class="form-group col-md-6">
              <input type="firstname" class="form-control" placeholder="First Name">
            </div>
            <div class="form-group col-md-6">
             <input type="lastname" class="form-control" placeholder="Last Name">
            </div>
          </div>
          <div class="form-group">
            <input
              type="text"
              class="form-control"
              placeholder="Phone Number"
            />
          </div>
          <div class="form-group">
            <select id="inputservice" class="form-control">
                <option selected>Select Service</option>
                <option>...</option>
              </select>
          </div>
          <button type="submit" class="btn btn-danger">Submit Now</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style>
.container1 {
  padding-top: 10px;
  margin-top: 50px;
  background: #ffffff;
  margin-left: 15px;
  padding-left: 15px;
  margin-bottom: 100px;
}
#contact {
  font-weight: 600;
  font-size: 36px;
  line-height: 43px;
  color: #000000;
}
#text1 {
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 140%;
  text-align: justify;
  color: #000000;
  padding-right: 10px;
}
#form{
  padding-right: 10px;
}
</style>
