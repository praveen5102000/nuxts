<template class="home">
    <div class="mains">
      <div class="contents col-12">
          
        <div class="boxx1 container col-lg-4 col-md-12 col-sm-12 bordered"> 
          <div class="front">
              <div class="fronti">
              <i class="fa-solid fa-pen"></i><p>Personal</p></div></div>
        
              
          
       
      </div>
      <div class="boxx2 container col-lg-8 col-md-12 col-sm-12 bordered">
          
              <div class="end">
                  <div class="ln1">
                      <div class="lname"><span>Welcome</span><h3>VENKATACHALAM,Share a bit about yourself</h3></div><div class="lname2"><i class="fa-solid fa-question"></i><i class="fa-solid fa-ellipsis-vertical"></i></div>
                  </div>
                  <div class="lnns">
                  <div class="ln2">
                      <div class="lnn2"><h6>Please select your gender</h6></div>
                      <div class="lnn22">
                          <a>Male</a>
                          
                          <a style="color: white;background-color: rgb(111, 40, 177);border: none;">Female</a>
                          <a>Transgender</a>
                          
                          
                      </div>
                      
                  </div>
                  <div class="ln2">
                      <div class="lnn2"><h6>Select your maritial status</h6></div>
                      <div class="lnn22">
                          <a>Single</a>
                          
                          <a>Married</a>
                         
                          
                          
                      </div>
                      
                  </div></div>
                
                  <button class="con">Continue</button>
              </div>
          </div>
      
      </div>
  </div>
      
      
    
  </template>
  
 
  
  <style>
  .contents {
      background-color: #e9e9e2;
      width: 100%;
      height: 86vh;
      display: flex;
  }
  .boxx1.container.col-4.bordered {
      width: 24%;
      display: flex;
      align-items: center;
  }
  .front {
      width: 100%;
      height: 80vh;
      background: white;
  }
  .boxx2.container.col-8.bordered {
      width: 74%;
      display: flex;
      align-items: center;
  }
  .end {
      background: white;
      width: 99%;
      height: 80vh;
  }
  .mains {
      background-color:  white;
      margin-top: 4em;
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
      font-size: 10px;
  }
  
  .conlr.d-flex.col-12 {
      border-top: 1px solid gainsboro;
      padding-top: 1em;
      padding-bottom: 1em;
      margin: 0 1em;
      width: 97%;
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
      margin-bottom: 3em;
  }
  .lnns {
    margin-top: 5em;
    margin-left: 3em;
    margin-bottom: 7em;
}
  .two h4 {
      margin-bottom: 16px;
  }
  i.fa-solid.fa-pen {
    color: white;
    background: none;
    font-size: 11px;
    background-color: #125ba3;
    width: 6%;
    height: 100%;
    margin-left: 20px;
}
.fronti {
    display: flex;
    background-color: #dee7fb;
    margin: 27px 37px;
    gap: 15px;
    padding-top: 18px;
    border-radius: 6px;
    position: relative;
    top: 4%;
}
  .fronti p{
      color: #125ba3;
  }
  .ln1 {
      display: flex;
      margin-top: 10px;
      border-bottom: 3px solid #e8e8ff;
      width: 95%;
      margin-left: 1em;
      padding-bottom: 1em;
  }
  .lname {
      display: flex;
      width: 96%;
  }
  .lname span {
      font-size: 22px;
      margin-right: 1em;
  }
  i.fa-solid.fa-ellipsis-vertical {
      color: #7f7a7a;
      background: none;
  }
  .lnn22 a, .ln222 a {
      border: 1px solid gainsboro;
      border-radius: 20px;
      margin: 10px;
      font-weight: 500;
      padding: 5px;
      font-size: 14px;
  }
  .ln222 {
      margin-top: 1.5em;
  }
  .lnn22 {
      margin-top: 2em;
  }
  .ln2 {
      margin-left: 1em;
      margin-top: 17px;
      border-bottom: 1px solid gainsboro;
      padding-bottom: 20px;
      width: 57%;
  }
  .con {
      width: 26%;
      border: none;
      border-radius: 40px;
      margin-bottom: 0em;
      margin-left: 8em;
      margin-top: 1em;
      background: rgb(34, 34, 102);
      color: white;
      font-size: 20px;
      padding: 8px;
  }
  @media (max-width: 768px){
    .contents {
    display: block;
    padding: 10px;
    height: 124vh;
}
.front {
    width: 99%;
    height: 10vh;
    background: white;
}
.ln2{
    width: 100%;
    line-height: 2.5;
}
.end{
    height: 105vh;
}
.mains{
    margin-top: 0;
}

}
/* @media (max-width: 425px){
    .ln2 {
    width: 92%;
    line-height: 2.5;
}
.lnn22 {
    margin-top: 1em;
    line-height: 2.5;
}
} */
  </style>
  