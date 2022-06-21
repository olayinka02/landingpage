<template>

<div class="heroSection">

 <b-container fluid class="bv-example-row">
  <b-row>
    <b-col sm="6">
        <div class="Herolefttext">
          <h2 class="Herolefttextheading">Business activities at your <span class="fingertip">finger tips</span></h2>
           <img src="../assets/VectorOne.svg" fluid alt="Fluid image" />
           <p class="Herolefttextparagraph">
            Llorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem 
            cras habitasse donec arcu enim eu, justo, nunc nulla. Mauris turpis 
            ut est est quis sed praesent. Nulla integer risus dolor enim at nulla. 
            Nunc non egestas vitae quis turpis ut est est quis sed praesent. Nulla 
            integer risus dolor .
           </p>
            <b-button class="getstartedbutton">Get Started
              <img src="../assets/buttonarrow.svg" fluid alt="Fluid image" />   
            </b-button>
        </div>
    </b-col>
    <b-col sm="6">
        <div class="RightImagebody">
            <img src="../assets/RightImage.svg" class="img-fluid" alt="..." />
        </div>
    </b-col>
  </b-row>
</b-container><br/>

<b-container fluid class="bv-example-row Pointwrapbody ">
     <b-row>
        <img class="lineimage" src="../assets/Line.svg" fluid alt="Fluid image" />
        <b-col class="Pointbody">
        <b-row>
        <b-col sm="4">
            <b-row class="wrapeachelement">
                <b-col cols="2">
                    <img src="../assets/marks.svg" fluid alt="Fluid image" /> 
                </b-col>
                <b-col cols="10">
                    <div class="PointOnetext">
                       <h6>ed praesent. Nulla integer risus dolor enim at nulla. Nunc non egestas vitae </h6>
                    </div>
                </b-col>
            </b-row>
          
        </b-col>
         <b-col sm="4">
             <b-row class="wrapeachelement">
                <b-col cols="2">
                    <img src="../assets/marks.svg" fluid alt="Fluid image" /> 
                </b-col>
                <b-col cols="10" >
                    <div class="PointOnetext">
                       <h6>cras habitasse donec arcu enim eu, justo, nunc nulla. Mauris turpis ut est </h6>
                    </div>
                </b-col>
            </b-row>
        </b-col>
         <b-col sm="4">
             <b-row class="wrapeachelement">
                <b-col cols="2">
                    <img src="../assets/marks.svg" fluid alt="Fluid image" /> 
                </b-col>
                <b-col cols="10">
                    <div class="PointOnetext">
                       <h6>Lorem ipsum dolor sit amet, consectetur adipiscing dolor sit amet, consectetur </h6>
                    </div>
                </b-col>
            </b-row>
        </b-col>
        </b-row>
        </b-col>
         <img  class="lineimage" src="../assets/Line.svg" fluid alt="Fluid image" />
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

.heroSection{
    padding-left:0.5rem;
    padding-right:0.5rem;
    background: url(../assets/HeroSection.svg),#444A92;
    background-repeat:no-repeat;
    height:auto;
    padding-bottom:3rem;
}
.RightImagebody{
    margin-top:5rem;
}
.Herolefttext{
    margin-top:20%;
}
.Herolefttextheading{
width:95%;
font-family: 'Nunito';
font-style: bold;
font-weight: bolder;
font-size: 2.5rem;
line-height: 130%;
color: aliceblue;
letter-spacing: 0.085em;
/* or 91px */

letter-spacing: -0.01em;
text-transform: capitalize
}
.fingertip{
    color:  #58A0DF;
}
.Herolefttextparagraph{
    width:97%;
    margin-top:0.8rem;
    color: aliceblue;
    
}

.getstartedbutton{
    width:60%;
    height:2.6rem;
    background-color: #58A0DF;
    border: none;
    border-radius:0.2rem;
}

.getstartedbutto:hover{
    width:30%;
    background-color:#444A92 !important;
    border: none;
    border-radius:0.2rem;
}
.Pointwrapbody{
    margin-top: 3rem;
}
.PointOnetext{
    width:100%;
    color: aliceblue;
    
}
.PointOnetext h6{
    font-size: 0.8rem;
}
.Pointbody{
    margin-top:1.5rem;
    margin-bottom:0rem;
    margin-right: 1rem;
    margin-left: 1rem ;
}
.wrapeachelement{
    margin-bottom:1.5rem;
}
.lineimage{
    width:100%;
}

 




@media (min-width: 576px) {
 .heroSection{
    padding-left:0.5rem;
    padding-right:0.5rem;
    background: url(../assets/HeroSection.svg),#444A92;
    background-repeat:no-repeat;
    height:auto;
    padding-bottom:3rem;
}
.RightImagebody{
    margin-top:5rem;
}
.Herolefttext{
    margin-top:20%;
}
.Herolefttextheading{
width:95%;
font-family: 'Nunito';
font-style: bold;
font-weight: bolder;
font-size: 2.5rem;
line-height: 130%;
color: aliceblue;
letter-spacing: 0.085em;
/* or 91px */

letter-spacing: -0.01em;
text-transform: capitalize
}
.fingertip{
    color:  #58A0DF;
}
.Herolefttextparagraph{
    width:97%;
    margin-top:0.8rem;
    color: aliceblue;
    font-size:0.9rem;
}
.getstartedbutton{
    width:60%;
    height:2.6rem;
    background-color: #58A0DF;
    border: none;
    border-radius:0.2rem;
}

.getstartedbutto:hover{
    width:30%;
    background-color:#444A92 !important;
    border: none;
    border-radius:0.2rem;
}
.Pointwrapbody{
    margin-top: 3rem;
}
.PointOnetext{
    width:100%;
    color: aliceblue;
    
}
.PointOnetext h6{
    font-size: 0.8rem;
}
.Pointbody{
    margin-top:1.5rem;
    margin-bottom:0rem;
    margin-right: 0rem;
    margin-left: 0rem ;
}
.wrapeachelement{
    margin-bottom:1.5rem;
}

 

 }



@media (min-width: 768px) { 
 .heroSection{
    padding-left:1rem;
    padding-right:1rem;
}
.RightImagebody{
    margin-top:7rem;
}
.Pointwrapbody{
    margin-top: 3rem;
}
.PointOnetext{
    width:70%;
    color: aliceblue;
}
.Pointbody{
    margin-top:1rem;
    margin-bottom:1rem;
    margin-right: 0rem;
    margin-left: 0rem ;
}
.wrapeachelement{
    margin-bottom:0rem;
}

 



 }

@media (min-width: 992px) { 

 .heroSection{
    padding-left:3rem;
    padding-right:3rem;
    background: url(../assets/HeroSection.svg),#444A92;
    background-repeat:no-repeat;
    height:auto;
    padding-bottom:5rem;
}
.RightImagebody{
    margin-top:5rem;
}
.Herolefttext{
    margin-top:25%;
}
.Herolefttextheading{
width:35rem;
font-family: 'Nunito';
font-style: bold;
font-weight: bolder;
font-size: 2.5rem;
line-height: 130%;
color: aliceblue;
letter-spacing: 0.085em;
/* or 91px */

letter-spacing: -0.01em;
text-transform: capitalize
}
.fingertip{
    color:  #58A0DF;
}
.Herolefttextparagraph{
    width:90%;
    margin-top:0.8rem;
    color: aliceblue;
    font-size:0.9rem;
}
.getstartedbutton{
    width:30%;
    background-color: #58A0DF;
    border: none;
    border-radius:0.2rem;
}

.getstartedbutto:hover{
    width:30%;
    background-color:#444A92 !important;
    border: none;
    border-radius:0.2rem;
}

 


 }


@media (min-width: 1200px) { 
 .heroSection{
    padding-left:6rem;
    padding-right:6rem;
    background: url(../assets/HeroSection.svg),#444A92;
    background-repeat:no-repeat;
    height:auto;
    padding-bottom:5rem;
}
.RightImagebody{
    margin-top:5rem;
}
.Herolefttext{
    margin-top:35%;
}
.Herolefttextheading{
width:35rem;
font-family: 'Nunito';
font-style: bold;
font-weight: bolder;
font-size: 3rem;
line-height: 130%;
color: aliceblue;
letter-spacing: 0.085em;
/* or 91px */

letter-spacing: -0.01em;
text-transform: capitalize
}
.fingertip{
    color:  #58A0DF;
}
.Herolefttextparagraph{
    width:90%;
    margin-top:0.8rem;
    color: aliceblue;
    font-size:0.9rem;
}
.getstartedbutton{
    width:30%;
    background-color: #58A0DF;
    border: none;
    border-radius:0.2rem;
}

.getstartedbutto:hover{
    width:30%;
    background-color:#444A92 !important;
    border: none;
    border-radius:0.2rem;
}



 
 }
 @media (min-width: 1400px) { 
 

 
 }

</style>
