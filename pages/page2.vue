<template class="home">
  
    <div class="contents">
      <div class="box container"> 
        <div class="row">
          <div class="head d-flex">
        <div class="head-para"><h3>Lets's get started</h3></div>
        <div class="head-icon"><i class="fa-solid fa-question"></i></div></div>
        <div class="conlr col-lg-12 col-md-12 col-sm-12">
          <div class="left col-lg-6 col-md-12 col-sm-12">
            <div class="one">
            <h4>Verify your number</h4>
            <p>Enter the 6-digit OTP received on 99****8595</p>
          </div>
          <div class="two">
            <div class="twoo">
                
            <h5>Enter OTP</h5>
            <div class="star">
            <i class="fa-solid fa-star"> </i>Try TOTP?</div>
            </div>
            <input type="text" value="+91">
            <div class="resend">
                <h4>Resend OTP(1:49s)</h4>
            </div>
          </div>
          <div class="three">
            <button><h6>Get OTP</h6></button>
          </div>
        </div>
          <div class="right col-lg-6 col-md-12 col-sm-12">
            <h4>Login with QR code</h4>
          </div>
        </div>
      </div></div></div>
    
  
</template>



<style>
.contents {
    background-color: #e9e9e2;
    width: 100%;
    height: 100vh;
}
.box.container {
    background-color: white;
    position: absolute;
    top: 25%;
    left: 7%;
    border-radius: 10px;
}

.head-para {
    width: 96%;
    text-align: center;
   
}
.head.d-flex {
    width: 100%;
    margin-top: 2em;
}
.fa-solid, .fas {
    background-color: #7f7a7a;
    color: white;
    padding: 7px;
    border-radius: 50%;
    font-size: 15px;
}

.conlr.d-flex.col-12 {
    border-top: 1px solid gainsboro;
    padding-top: 1em;
    padding-bottom: 1em;
    margin: 0 1em;
    width: 97%;
}
.left {
    padding-left: 2em;
}
.right {
    padding-left: 4em;
    border-left: 1px solid gainsboro;
}
.one p {
    width: 70%;
    margin-bottom: 20px;
}
input[type="text"] {
    border-top: none;
    border-left: none;
    border-right: none;
    width: 70%;
    border-bottom: 2px solid darkviolet;
    margin-bottom: 1em;
}
button {
    width: 70%;
    border: none;
    border-radius: 40px;
    margin-bottom: 2em;
}
button h6 {
    opacity: .4;
    font-weight: 700;
    padding: 11px;
}
.two h4 {
    margin-bottom: 16px;
}
.twoo {
    display: flex;
    justify-content: space-between;
    width: 70%;
    align-items: center;
    margin-bottom: 1em;
}
.star i {
    color: #7710a3;
    background: none;
}
.star {
    display: flex;
    gap: 0px;
    color: #7710a3;
    font-weight: 500;
}
.resend h4 {
    font-size: 18px;
    opacity: .4;
    text-align: end;
    width: 70%;
    font-weight: 600;
    margin-bottom: 2em;
}
.conlr{
  display: flex;
}
@media (max-width: 768px){
  .conlr{
  display: block;
}
.box.container{
  position: relative;
  left: 0;
  top: 12%;
}
.right {
    padding: 0 3em 3em 3em;
}
.head-para{
  margin-bottom: 1em;
}
.one p {
    width: 100%;
    margin-bottom: 20px;
}
.left {
  padding-left: 0;
    padding: 3em;
}
input[type="text"] {
  width: 100%;
}
button{
  width: 100%;
}
.twoo{
  width: 100%;
}
}
</style>
