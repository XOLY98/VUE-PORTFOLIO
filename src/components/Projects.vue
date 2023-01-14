<template>
<h1>Projects</h1>
<div class="proj">
<div class="row gap-5 mx-5 d-sm-flex justify-content-center">
<div class="card" v-for="item in projects" style="width: 18rem;" :key="item">
  <img :src="item.image" class="card-img-top" alt="">
  <div class="card-body">
    <h5 class="card-title">{{item.name}}</h5>
   <button> <a :href="item.github" class="btn btn-primary">Github</a></button>
   <button> <a :href="item.netlify" class="btn btn-primary">Netlify</a></button>
   </div>
  </div>
</div>
</div>
<div>
      <ul>
       <li>NAME: XOLELWA MANQINA</li>
       <li>AGE: 24 YEARS OLD</li>
       <li><i class="fa-sharp fa-solid fa-house"></i>  ADDRESS: 1028 NOMTHANDAZO STR,<br> NEWCROSS ROADS, NYANGA, 7750</li>
       <li><i class="fa-sharp fa-solid fa-phone"></i>  PHONE: 084 0750 691</li>
       <li><i class="fa-sharp fa-solid fa-envelope"></i>  EMAIL: manqinaxolelwa98@gmail.com</li>
      </ul>
      </div>
   
            
</template>
<script>
export default {
    data() {
        return {
           projects:[{
            name:"MY PORTFOLIO",
            image:"https://i.postimg.cc/fRMjkbf4/PORT.png",
            github:"https://github.com/XOLY98/MY-1st-PROJECT.git",
            netlify:"https://brilliant-ganache-74ce89.netlify.app"
            },
            {
            name:"CALCULATOR",
            image:"https://i.postimg.cc/R0rKrVpJ/CALCU.png",
            github:"https://github.com/XOLY98/CALCULATOR.git",
            netlify:"https://tubular-axolotl-055e4c.netlify.app"
            },
            {
            name:"MY FIRST JAVASCRIPT",
            image:"https://i.postimg.cc/6QwV2pVJ/JAVA.png",
            github:"https://github.com/XOLY98/END-MODULE-PROJECT-JAVASCRIPT-.git",
            netlify:"https://jocular-brioche-078da3.netlify.app"
            },
            {
            name:"FIRST ECOMMERCE",
            image:"https://i.postimg.cc/C5ZxLbzh/ECOM.png",
            github:"https://github.com/XOLY98/MANQINA.git",
            netlify:"https://velvety-gumption-13fefd.netlify.app"
            },
            {
            name:"FIRST HTML",
            image:"https://i.postimg.cc/8zT9DNFc/HTML-PIC.png",
            github:"https://github.com/XOLY98/MANQINA.git",
            netlify:"https://incandescent-nasturtium-5ba667.netlify.app"
            },
           ] 
        }
    },
}
</script>
<style scoped>
   .proj{
   margin-top:100px;
   }
   .card{
       background-image:linear-gradient(pink,#A865C9);
      animation: 2s anim-card ease-out infinite;
     }
   @keyframes anim-card {
      0% {
        opacity: 0;
        transform: translateY(50%);
      }
     
    } 
   
   
   .btn{
background-color:black;
color:white;
   }
   h1{
    font-style:bold;
    color:#A865C9;
    text-decoration: underline double #A865C9;
    text-underline-position: under;
    text-align:center;
   }
   ul{
      list-style: none;
      margin-top: 100px;
      margin-bottom:0;
  }
  ul li{
      color:white;
  }
  @media screen  and(min-width: 300px) and (max-width:719px){
   .card{
      width:1rem;
   }
   ul{
      font-size: 1rem;
   }
  }
</style>