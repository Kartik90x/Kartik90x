<!DOCTYPE html>

<html>
<head>
  <title>Contact</title>
</head>
<style>
  
   *{
     padding:0;
    margin:0;
    box-sizing:border-box;
  }
  body{
    font-family:outfit;
    background:linear-gradient(#ffdad5,#fff7f9);
  }
 .contact-container{
   height:100vh;
   display:flex;
   align-items:center;
 }
 .contact-left-title hr{
   border:none;
   width:120px;
   height:5px;
   background-color:#a363aa;
   border-redius:10px;
   margin-buttom:20px;
 }
 .contact-inputs{
  width:400px;
  height:50px;
  font-weight:500;
  border-radius: 50px;
  padding: 15px;
 }
.contact-left textarea{
  height:140px;
  padding-top:15px;
  border-redius:5px;
}

.contact-left button{
  align:items:center;
  border-radius: 50px;
  padding: 10px;
  color:red;
  background-color:#aff994f,#fa6d86;
}

</style>

<body>
       <div class="contact-container">
    <form action="https://api.web3forms.com/submit" method="POST"
      class="contact-left">
      <div class="contact-left-title">
        <h2>Get in touch</h2>
        <hr>
        
      </div>
      
    <input type="hidden" name="access_key" value="b6015aaa-2055-4a65-806d-3213190bf37c">
 
      <form>
       <input  type="text" name="Name" placeholder="Your Name" class="contact-inputs" required>
      <input type="email" name="email" placeholder="Your Email" class="contact-inputs" required>
      <input type="Mob." name="Mob." placeholder="Your Mob.no" class="contact-inputs" required>
      <textarea name="Message" placeholder="Your Message" class="contact-inputs" required></textarea>
      <button type="submit">submit </button>
      </form>
      <div class="contact-right">
        <img src="https://i.ibb.co/QNv1Lr4/right-img.png">
      </div>
     

</body>
</html>

