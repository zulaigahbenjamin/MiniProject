<template lang="">
    <div>
        
  
              <!-- contact form -->

      <main id="main-Section">

<div id="contact" class="row">
  <div class="col  first">
    <div class="card left">
      <div class="hide hijab">
        <img src="https://i.postimg.cc/mZHF14HT/contact.png" loading="lazy" class="pfp" />
      </div>

      <div class="text-center pb-3 add-pad bot">
        <h4><strong style="color:#BC9C22;" >𝑩𝒆𝒍𝒍𝒂 𝑽𝒊𝒔𝒂𝒈𝒆</strong></h4>
        <em>Contact Details:</em> <br />
        <br />
        Number: 021 362 010 <br />
        Email: 𝑩𝒆𝒍𝒍𝒂 𝑽𝒊𝒔𝒂𝒈𝒆@gmail.com<br />
        <br />
        <p>We at 𝑩𝒆𝒍𝒍𝒂 𝑽𝒊𝒔𝒂𝒈𝒆 store care about our customer's <br> feedback as we strive to serve nothing but the
          best.</p>

      </div>
    </div>
  </div>

  <div class="col-md-8 p-2">
    <!-- Logo image -->
    <div class="logo">
      <img class="logo-contact" src="https://i.postimg.cc/HsbqzZy5/Bv-1.png">
    </div>

    <div class="card border-2 mt-5 second" id="contact-box">

      <form action="https://formspree.io/f/xknayqyj" method="POST">

        <h2 class="card p-3 heading-text pink-bg border-2 text-center" style="border: none;">Contact Me!</h2>
        <div class="input-ting">
          <label class="form-label heading-text">Name:</label>
          <input type="text" name="Name" class="form-control light-bg border-2" placeholder="Please enter your name"
            required />
        </div>

        <div class="input-ting">
          <label class="form-label heading-text">Email:</label>
          <input type="email" name="Email" class="form-control light-bg border-2"
            placeholder="Please Enter your email" required />
        </div>

        <div class="input-ting">
          <label class="form-label heading-text">Enter message:</label>
          <textarea name="Message" class="form-control light-bg border-2" rows="5"
            placeholder="We would like to hear from you"></textarea>
        </div>
        <div class="bttn">
        <button type="submit" class="btn submit-btn submitting">Submit</button>
      </div>
      </form>
    </div>
  </div>
</div>
<!-- contact form done -->
</main>


    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&family=Roboto:ital,wght@0,400;0,500;0,700;1,500&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;
  font-family: "Poppins", sans-serif;
}

h1 {
  font-size: 50px;
  line-height: 64px;
  color: black;
  font-weight: 500;
}
h2 {
  font-size: 46px;
  line-height: 54px;
  color: black;
  font-weight: 400;
}
h4 {
  font-size: 20px;
  color: black;
}
h6 {
  font-size: 16px;
  font-weight: 700;
}

p {
  font-size: 16px;
  margin: 15px 0 20px 0;
  color: black;
}
.section-p1 {
  padding: 40px 80px;
}
.section-m1 {
  margin: 40px 0;
}
body {
  width: 100%;
}



  @media screen and (max-width: 300px) {

  
 

  html,
  body {
    overflow-x: hidden;
  }

  }

#hero button {
  letter-spacing: 3px;
  font-size: 17px;
  border-radius: 8px;
  transition: all 0.2s ease-in-out;
  box-shadow: 4px 4px 10px #ccc5b9, -4px -4px 10px#FFFCF2;
  cursor: pointer;
  margin-left: 30rem;
  margin-top: 50rem;
}

#hero button:hover {
  box-shadow: -4px -4px 10px #ccc5b9, 4px 4px 10px#FFFCF2;
}

/* feature button */
.feature-btn {
  text-decoration: none;
  margin-top: 50px !important;
 
}

/* category */

.category-title {
  margin-top: 20px;
  margin-bottom: 10px;
}
.category-title h2 {
  text-align: center;
}
.category .category-box {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.category .category-box .box {
  margin: 30px 20px;
}
.category .category-box .box img {
  width: 600px;
  border-radius: 5px;
  height: 328px;
}

.category .category-box .box-content {
  position: absolute;
  z-index: 1;
  margin-left: 30px;
  margin-top: 100px;
}

.category .category-box .box-content h3 {
  color: #eb5e28;
  font-size: 30px;
  margin-top: 40px;
}

.category .category-box .box-content label {
  display: block;
  font-size: 27px;
  color: #eb5e28;
}
.category .category-box .box-content a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 25px;
  font-size: 14px;
  border-radius: 25px;
  background: #fffcf2;
  transition: all 0.19s ease-in;
  color: black;
}
.category .category-box .box-content a:hover {
  background: silver;
}
.category .category-box .box-content.b2 {
  margin: 15px;
  text-align: left;
  margin-top: 100px;
}

/* banner section */
.banner_section {
  overflow: hidden;
}

/* Image styling for contact page */

.pfp {
  width: 100%;
  border-style: solid;
  border-width: 5px;
  border-radius: 50%;
  border-color: white;
}
.bttn {
  width: 90% !important;
}
.logo {
  margin: 0;
  padding: 0;
}
.btn {
  display: flex;
  justify-content: center;
  align-items: center;
}

.input-ting {
  width: 90%;
}

.second {
  margin-bottom: 5rem;
  background-color: white!important;
  color: white !important;
}

form h2 {
  background-color: !important;
  color: white !important;
  border: white !important;
}

form {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border: white;
}
#contact-box {
  margin-top: -0.9rem !important;
}

.bot {
  padding-top: 1rem;
  background-color: pink;
  color: white;
}

.bot p {
  color: white;
}
/* landing page preview cards */
.cards {
  border: 2px solid black;
}
/* end */

.hijab img {
  width: 18rem;
  height: 12rem;
  border: white;
}
.card-text {
  margin-left: 20px;
}
.card-title {
  margin-left: 10px;
}
.btn-contact {
  box-shadow: 4px 4px 10px #ccc5b9, -4px -4px 10px#FFFCF2 !important;
  padding: 3px;
  background-color: #eb5e28 !important;
}

.submit-btn {
  width: 100% !important;
  position: relative;
  display: flex;
  margin-left: 0 !important;
}
.logo-contact {
  width: 55% !important;
  margin: 0 !important;
  padding: 0 !important;
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  border-radius: 1000px !important;
  border-radius: 50% 46% / 38% 40% !important;
  height: 290px !important;
  position: relative !important;
  top: 70px   !important;
  left: 25% !important;
}
#contact {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  width: 100%;
}

.hijab {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: white;
  padding-top: 2rem;
  padding-bottom: 1.4rem;
  border: white !important;
}

#contactPage {
  background-image: url("https://i.postimg.cc/pV9bHMnx/unsplash-ta-O2f-C7sx-DU.png");
  background-repeat: no-repeat;
  background-size: 100%;
  width: 100%;
}

#main-Section {
  display: flex;
  justify-content: center;
  align-items: center;
}

.submitting {
  background-color: #faaa94 !important;
  width: 100% !important;
  margin-top: 2rem !important;
  margin-bottom: 2rem !important;
  color: white !important;
}
.submitting:hover {
  box-shadow: 0 0 15px#FFFCF2 !important;
}








  
  h2 {
    font-size: 32px;
    margin-bottom: 1em;
  }
  
 
  
  


h2,
h3 {
  font-weight: 700;
}








/* end of footer */

/* about */
strong{
  color: black;
  font-family: 'Caveat', cursive;
font-family: 'Poppins', sans-serif;
}

span{
  color:pink ;
  font-family: 'Caveat', cursive;
font-family: 'Poppins', sans-serif;

}
/* about end */

    
</style>