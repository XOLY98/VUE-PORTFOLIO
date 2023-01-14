<template>
  <div class="abouttext">
  <div>
  <h2 class="me">ABOUT ME</h2>
                <p class="para">My name is Xolelwa Manqina,<br> I am a web developer based in Cape Town and<br> I am very passionate and dedicated to my work.<br>I have acquired
                 the skills necessary to build great and<br> premium websites. </p>
                 <ul>
                  <li>NAME: XOLELWA MANQINA</li>
                  <li>AGE: 24 YEARS OLD</li>
                  <li><i class="fa-sharp fa-solid fa-house"></i>  ADDRESS: 1028 NOMTHANDAZO STR,<br> NEWCROSS ROADS, NYANGA, 7750</li>
                  <li><i class="fa-sharp fa-solid fa-phone"></i>  PHONE: 084 0750 691</li>
                  <li><i class="fa-sharp fa-solid fa-envelope"></i>  EMAIL: manqinaxolelwa98@gmail.com</li>
                 </ul>
                 </div>
                 <div class="img">
                 <img src="https://i.postimg.cc/s2KNvgNz/DSC-3618-removebg-preview.png" width="350" height="480">
   </div>       
  </div>
</template>

<script>
export default {
    
}
</script>
<style scoped>
.abouttext{
    display:flex;
    text-align:center;
    margin:0px;
    justify-content:center;
}
.para{
    font-size:1.5rem;
    color:white;
}
.me{
    font-style:bold;
    color:#A865C9;
    text-decoration: underline double #A865C9;
    text-underline-position: under;
    margin-top:100px;
}
ul{
    list-style: none;

}
ul li{
    color:pink;
}
@media screen and (min-width: 300px) and (max-width:719px){
    .para{
        font-size:0.5rem;
        
    }
    .img{
       scale:0.5;
    }
    .ul{
        font-size:0.5rem;
    }
}


    
</style>