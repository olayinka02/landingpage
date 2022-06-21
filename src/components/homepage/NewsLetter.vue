<template>
<div>


 <b-container class="NewsletterBody">
   <b-row class="NewsletterBodySection" >
      <b-col  sm="12" md="6" lg="6" xl="6">
        <h4 class="Newslettertext">Subscribe to our Newsletter to know more about us</h4>
      </b-col>
      <b-col sm="12" md="6" lg="6" xl="6">
        <div>
         <b-form inline >
           <label class="sr-only" for="inline-form-input-name">Name</label>
            <b-form-input
               id="input-group-1"
              class="mb-2 mr-sm-2 mb-sm-0 inputplace "
              placeholder="Olayimika@gmail.com"
            ></b-form-input>
            <b-button class="signinbtn" variant="primary">Sign Up</b-button>
         </b-form>
        </div>
      </b-col>
   </b-row>
 </b-container>

  
</div>

</template>

<script>


  // export default {
  //   name: 'HelloWorld',
  //   props: {
  //     msg: String
  //   }
  // }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200;400&display=swap');


.NewsletterBody{
  padding-left:2rem;
  padding-right:2rem;
  margin-bottom:3rem;
  margin-top:-3rem;
}
.NewsletterBodySection{
   background: url(../assets/HeroSection.svg),#58A0DF;
   padding:2rem;
   border-radius:0.4rem;

}
.Newslettertext{
  color:aliceblue;
  font-size:1.4rem;
 font-family: 'Nunito';
}
.inputplace{
  width:100% !important;
}
.signinbtn{
  width:100%;
}


 

 




@media (min-width: 576px) {

 
 }


@media (min-width: 768px) { 
 .NewsletterBody{
  padding-left:3rem;
  padding-right:3rem;
  margin-bottom:3rem;
  margin-top:-3rem;
}
.NewsletterBodySection{
   background: url(../assets/HeroSection.svg),#58A0DF;
   padding:6rem;
   border-radius:0.4rem;

}
.Newslettertext{
  color:aliceblue;
  font-size:1.4rem;
 font-family: 'Nunito';
}
.inputplace{
  width:65% !important;
}
.signinbtn{
  width:30%;
}

 }


@media (min-width: 992px) { 
 .NewsletterBody{
  padding-left:3rem;
  padding-right:3rem;
  margin-bottom:3rem;
  margin-top:-3rem;
}
.NewsletterBodySection{
   background: url(../assets/HeroSection.svg),#58A0DF;
   padding:6rem;
   border-radius:0.4rem;

}
.Newslettertext{
  color:aliceblue;
  font-size:1.4rem;
 font-family: 'Nunito';
}


 
 }


@media (min-width: 1200px) { 

  
 }


@media (min-width: 1400px) { 
 
 
 }

</style>
