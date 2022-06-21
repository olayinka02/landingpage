<template>
<div class="howitworkbody">

<h5 class="howitwork">How it works</h5>
<p class="howitworktext">orem ipsum dolor sit amet,  Lorem ipsum dolor sit amet, </p>

<b-container fluid class="howitworkbody">
  <b-row>
    <b-col  sm="12" md="12" lg="4" xl="4">
      <div class="howitworkbodycard">
       <div>
          <b-row>
            <b-col  sm="2" md="2" lg="2" xl="2">  <img  class="bulletimage" src="../assets/bulletpoint.svg" fluid alt="Fluid image" /></b-col>
            <b-col  sm="10" md="10" lg="10" xl="10"><h5 style="margin-top:0.5rem;font-weight:bold;font-size:1rem;">Lorem ipsum dolor sit amet,</h5> </b-col>
          </b-row>
        </div><br/>
        <p class="howitworkbodyparagraph">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
          Lorem cras habitasse donec arcu enim eu, justo, nunc nulla. 
          Mauris turpis ut est est quis sed praesent. Nulla integer risus 
          dolor enim at nulla. Nunc non egestas cras habitasse donec arcu 
          enim eu, justo, nunc nulla. Mauris turpis ut est est quis sed</p>
          <b class="Readmorebtn">Read More <img  class="ReadmoreArrow" src="../assets/ReadmoreArrow.svg" fluid alt="Fluid image" /></b>
      </div>
    </b-col>
    <b-col  sm="12" md="12" lg="4" xl="4">
       <div class="howitworkbodycard">
       <div>
          <b-row>
            <b-col  sm="2" md="2" lg="2" xl="2">  <img  class="bulletimage" src="../assets/bulletpoint.svg" fluid alt="Fluid image" /></b-col>
            <b-col  sm="10" md="10" lg="10" xl="10"><h5 style="margin-top:0.5rem;font-weight:bold;font-size:1rem;">Lorem ipsum dolor sit amet,</h5> </b-col>
          </b-row>
        </div><br/>
        <p class="howitworkbodyparagraph">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
          Lorem cras habitasse donec arcu enim eu, justo, nunc nulla. 
          Mauris turpis ut est est quis sed praesent. Nulla integer risus 
          dolor enim at nulla. Nunc non egestas cras habitasse donec arcu 
          enim eu, justo, nunc nulla. Mauris turpis ut est est quis sed</p>
          <b class="Readmorebtn">Read More <img  class="ReadmoreArrow" src="../assets/ReadmoreArrow.svg" fluid alt="Fluid image" /></b>
      </div>
    </b-col>
    <b-col sm="12" md="12" lg="4" xl="4">
       <div class="howitworkbodycard">
        <div>
          <b-row>
            <b-col  sm="2" md="2" lg="2" xl="2">  <img  class="bulletimage" src="../assets/bulletpoint.svg" fluid alt="Fluid image" /></b-col>
            <b-col  sm="10" md="10" lg="10" xl="10"><h5 style="margin-top:0.5rem;font-weight:bold;font-size:1rem;">Lorem ipsum dolor sit amet,</h5> </b-col>
          </b-row>
        </div><br/>
        <p class="howitworkbodyparagraph" >Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
          Lorem cras habitasse donec arcu enim eu, justo, nunc nulla. 
          Mauris turpis ut est est quis sed praesent. Nulla integer risus 
          dolor enim at nulla. Nunc non egestas cras habitasse donec arcu 
          enim eu, justo, nunc nulla. Mauris turpis ut est est quis sed</p>
          <b class="Readmorebtn">Read More <img  class="ReadmoreArrow" src="../assets/ReadmoreArrow.svg" fluid alt="Fluid image" /></b>
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

.howitworkbody{
  padding-top: 4.5rem;
  padding-bottom:4.5rem;
  padding-left:0.5rem;
  padding-right:0.5rem;

}
 

.howitwork{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#263238;
font-weight:bolder;
font-size:2.8rem;
}
.howitworktext{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#444A92;;
font-weight:bold;
font-size:0.9rem; 
margin-left:0.5rem;
margin-right:0.5rem;
}

.howitworkbodycard{
    background: url(../assets/HeroSection.svg);
    background-repeat:no-repeat;
    margin:0rem;
    padding:2rem;
    margin-bottom:2rem;
}
.howitworkbodycard h5{
  color: #444A92;
  font-weight: bold;
}

.Readmorebtn{
  color: #58A0DF;
}
.howitworkbodyparagraph{
  font-size:0.9rem;
}





@media (min-width: 576px) {
 
 }


@media (min-width: 768px) { 

 }


@media (min-width: 992px) { 

 .howitworkbody{
  padding-top: 4.5rem;
  padding-bottom:4.5rem;
  padding-left:1rem;
  padding-right:1rem;

}
 

.howitwork{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#263238;
font-weight:bolder;
font-size:2.8rem;
}
.howitworktext{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#444A92;;
font-weight:bold;
font-size:0.9rem; 
}

.howitworkbodycard{
    background: url(../assets/HeroSection.svg);
    background-repeat:no-repeat;
    margin:0rem;
    padding:2rem;
    margin-bottom:0rem;
}
.howitworkbodycard h5{
  color: #444A92;
  font-weight: bold;
  
}

.Readmorebtn{
  color: #58A0DF;
}

 
 }


@media (min-width: 1200px) { 
  .howitworkbody{
  padding-top: 4.5rem;
  padding-bottom:4.5rem;
  padding-left:3rem;
  padding-right:3rem;

}
 

.howitwork{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#263238;
font-weight:bolder;
font-size:2.8rem;
}
.howitworktext{
justify-content: center;
align-items: center;
text-align: center;
font-family: 'Nunito';
color:#444A92;;
font-weight:bold;
font-size:0.9rem; 
}

.howitworkbodycard{
    background: url(../assets/HeroSection.svg);
    background-repeat:no-repeat;
    margin:0rem;
    padding:2rem;
    margin-bottom:0rem;
}
.howitworkbodycard h5{
  color: #444A92;
  font-weight: bold;
  
}

.Readmorebtn{
  color: #58A0DF;
}

  
 }


@media (min-width: 1400px) { 

 }

</style>
