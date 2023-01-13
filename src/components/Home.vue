<template>
<div>
  <div class='line'>
    <h2 class='pop-outin'>XOLELWA MANQINA</h2>
 </div>
 <div class="line">
    <p class='lineUp'>I am web developer <br>Backend,Frontend and<br>Freelancer!</p>
  </div>
 </div>
</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button{
    display: flex;
    margin:0 auto;
    align-items:center;
    justify-content: center;
    background-color:white;
}
.pop-outin {
  animation: 2s anim-popoutin ease infinite;
  color:white;
  font-size:4rem;
  margin-top:100px
  
}

@keyframes anim-popoutin {
  0% {
    color: #A865C9;
    transform: scale(0);
    opacity: 0;
    text-shadow: 0 0 0 rgba(0, 0, 0, 0);
  }
  25% {
    color: pink;
    transform: scale(2);
    opacity: 1;
    text-shadow: 3px 10px 5px rgba(0, 0, 0, 0.5);
  }
  50% {
    color: #A865C9;
    transform: scale(1);
    opacity: 1;
    text-shadow: 1px 0 0 rgba(0, 0, 0, 0);
  }
  100% {
    /* animate nothing to add pause at the end of animation */
    transform: scale(1);
    opacity: 1;
    text-shadow: 1px 0 0 rgba(0, 0, 0, 0);
  }
}
.lineUp {
  animation: 2s anim-lineUp ease-out infinite;
  color:pink;
  font-size:2rem;
  font-family:"Copperplate","Lucida Handwriting";
}
@keyframes anim-lineUp {
  0% {
    opacity: 0;
    transform: translateY(80%);
  }
  20% {
    opacity: 0;
  }
  50% {
    opacity: 1;
    transform: translateY(0%);
  }
  100% {
    opacity: 1;
    transform: translateY(0%);
  }
}

</style>
