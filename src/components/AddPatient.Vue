
    <template>
      <nav class="navbar fixed-top navbar-light bg-light" id="topnav">
          <a class="navbar-brand"  id="head">EZ MEDS</a>
          <button type="button" class="btn btn-default btn-sm" onclick="document.location='logout.php'" id="log">
            <span  aria-hidden="true"></span> Logout
          </button>
        </nav>
      
     
        
      <form  class="d-flex justify-content-center" id="add-patient">
        
        
          <div class="login-box" class="d-flex justify-content-center">
            <h5 style="text-align: center">Add Patient</h5>
          
          <div class="col-md-10 login" >
            <label  >First Name&nbsp;&nbsp;&nbsp;</label>
            <input type="text" id="a" >
          </div>
          <div class="col-md-10  login" >
            <label >Last Name&nbsp;&nbsp;&nbsp;</label>
            <input type="text" id="a"  >
          </div>
          <div class="col-md-10 login" >
            <label >Email&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</label>
            <input type="email" id="a" >
          </div>
          <div class="col-md-10 login">
            <label >Phone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</label>
            <input type="tel" id="a" >
          </div>

          <div  class="col-md-10 login">
            <button  class="btn btn-vue ">Cancel  </button>
             <button  class="btn btn-primary  ">Save</button>
          </div>
          
        
        </div>
      </form>
    </template>

    <script>
      
      export default{
       
    </script>

    <style>
      .btn-vue
{
    background:#A9A9A9;
    color:#fff;
    font-weight: bold;

}
.btn-vue:hover
{
  background-color:blue ;
  color: #fff;
  
}


  
  #add-patient
  {
    
    width: 50%;
    margin-left: 400px !important;
    margin: auto 0;
    align-content: center !important;
    text-align: center;
  }
    

  

.login-box{
  max-width: 700px; 
  float: none;
  margin: 100px auto;

  top: 50%;
  left: 50%;
}


.login{
  background:#DCDCDC;
  padding: 30px;
  display: inline-block !important;
  text-align: center;
  width:75%;
  
}


#a
{
  text-align: center;
  border-radius: 5px;
  border-width: 1px;
}
#topnav
{
    background-color: #44474B !important;
}
#log
{
    background-color: white;
    padding-top:0px;
    padding-bottom:0px;
    padding-right:15px;
    padding-left:15px;
    font-weight: 550;
}
#log:hover
{
    background-color:#007FFF;
    color: white;
    font-weight:2em ;
    padding-top:2px;
    padding-bottom:2px;
    padding-right:20px;
    padding-left:20px;
    
    
}
#head
{
    color: white;
    font-weight: 700;
}



    </style>