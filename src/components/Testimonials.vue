<template>
 <h1>Testimonials</h1>
   <div class="container-fluid ">
   <div class="row gap-5 mx-5 d-sm-flex justify-content-center">
<div class="card " v-for="item in testimonials"  :key="item" style="width:20rem ">
  <img :src="item.image" class="card-img-top rounded-circle" alt="">
  <div class="card-body">
    <h6 class="card-title">{{item.name}}</h6>
    <h6 class="company">{{item.company}}</h6>
    <p class="message">{{item.message}}</p>
  </div>
</div>
   </div>
</div>
   

    
  
        
    
</template>
<script>
export default {
    
    data() {
        return {
            testimonials:[{
                name:"KEREN BRUCE",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"Xolelwa is great team player, she is always eager to learn. She does not give up on any difficult tasks, her aim is to achieve the best results.",
                image:"https://i.postimg.cc/434z7Vqt/me.jpg"
            },
            {
                name:"THOKOZANI NQWILI",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"She exhibits exceptional unique creativity and determination. She has a diligate,effient work ethic and alway produces sophisicated projects to the best of her ability.",
                 image:"https://i.postimg.cc/mk7fJh4Z/my-Picture.jpg"
            },
            {
                name:"ZOE DANIELS",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"Xolelwa is a hard working lady with a big heart.She is organised,efficient and extremely competent with excellent rapport with people of all ages.Her communication skills are excellent no matter if you are talking about verbal or written. She would be a valueable asset to your company.",
                 image:"https://i.postimg.cc/LXvLMh03/IMG-20221103-161223.jpg"
            },
            {
                name:"NIKITA RAMAWOOTHAR",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"Xolelwa is go-getter, she is outspoken and outgoing,she make a great team player with great work ethics.",
                 image:"https://i.postimg.cc/j2cnHx12/56164181-2nikitaaa.jpg"
            },
            {
                name:"RYAN THOMAS",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"Xolelwa is a hard-working and strong individual that ensures that she understands something completely before implementing it. She has a great personality and has a great sense of humor. He ability to assess an issue and solve it, is really good and she strives to reach perfection in her work.",
                 image:"https://i.postimg.cc/7YdzPjMF/ryan-t.jpgO/"
            },
             {
                name:"CHRISANER MATTHY",
                company:"LIFE CHOICES CODING ACADEMY ",
                message:"Xolelwa is an extremely optimistic person. She has the ability uplift those around her and I feel one may be able to  approach her at any time for help. Therefore I believe she'll be an asset to any organization.",
                 image:"https://i.postimg.cc/Kc5Vg7Rv/IMG-20210925-WA0022.jpg"
            },
           
            ]
        }
    },
}
</script>
<style scoped>
h1{
    font-style:bold;
    color:#A865C9;
    text-decoration: underline double #A865C9;
    text-underline-position: under;
    text-align:center;
}

.card{

    height:90vh;
     box-shadow:5px 5px 5px pink;
     margin-top:80px;
     animation: 2s anim-card ease infinite;
     background-color:black
}
@keyframes anim-card {
  0% {

    transform: scale(1);
    opacity: 0;
    
  }
}
.card-title{
    color:pink;
}
.message{
    color:white;
    margin-top:50px;
}
.company{
    color:#A865C9;
}


    
</style>