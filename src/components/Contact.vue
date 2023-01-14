<template>
<h2>Contact Me</h2> 
    <div class="forms">
  <form action="https://formspree.io/f/xqkjgobz" method="post">
    <label for="fname">First Name:</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name.." aria-describedby="nameHelp" required><br>
<pre></pre>
    <label for="lname">Last Name:</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name.." aria-describedby="lastnameHelp" required><br>
<pre></pre>
    <label for="email">Email:</label>
    <input type="text" id="email" name="email" placeholder="Your email address.." aria-describedby="emailHelp" required><br>
<pre></pre>  
    <label for="message">Message:</label>
    <input type="text" id="message" name="message" placeholder="Your message.." aria-describedby="messageHelp" required><br>
<pre></pre>
    <label for="country">Country:</label>
    <select id="country" name="country">
    <option value="south africa"> South Africa</option>
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select><br>
  <pre></pre>
    <button type="submit">Send</button>
  </form>
</div>
 <pre></pre>
   <ul>
     <li>NAME: XOLELWA MANQINA</li>
     <li>AGE: 24 YEARS OLD</li>
     <li><i class="fa-sharp fa-solid fa-house"></i>  ADDRESS: 1028 NOMTHANDAZO STR,<br> NEWCROSS ROADS, NYANGA, 7750</li>
     <li><i class="fa-sharp fa-solid fa-phone"></i>  PHONE: 084 0750 691</li>
     <li><i class="fa-sharp fa-solid fa-envelope"></i>  EMAIL: manqinaxolelwa98@gmail.com</li>
    </ul>
</template>
<script>
export default {
    
}
</script> 

<style scoped>
h2{
         font-style:bold;
    color:#A865C9;
    text-decoration: underline double #A865C9;
    text-underline-position: under;
    text-align:center;

}
select {
  width: 300px;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  background-color:white;
  color:black;
}

input  {
  width: 300px;
  background-color:white;
  color: black;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button{
    margin: 30px;
    width: 150px ;
    padding: 10px;
    background-color:#A865C9;
    color:black ;
}
button:hover{
    background-color:white; 
    border: none;
    color:black;
    box-shadow:5px 5px ;
    transition:0.3s ;
    font-size:20px ;
}


div  {
  
  height:550px;
  width:500px;
  margin-left:530px;
  margin-top:50px;
  box-shadow:3px 1px 3px 1px white
 

}
label{
    color:white;
}

ul {
    text-align:center;
    color:white;
    float:bottom;
    list-style:none;
    margin-top:100px
} 
  #message{
    width:300px;
    height:100px
}
@media screen  and(min-width: 300px) and (max-width:719px){
  div  {
  height:5%;
  width:2%;
  margin-left: 0 !important;
 
}
input{
  width: 2%;
}
}

    
</style>