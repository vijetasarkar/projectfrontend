<template>
  <nav class="navbar fixed-top navbar-light bg-light" id="topnav">
    <a class="navbar-brand" href="#" id="head">EZ MEDS</a>
    <button type="button" class="btn btn-default btn-sm"  id="log">
      <span  aria-hidden="true"></span> Logout
    </button>
  </nav>
  <p><br><br><br></p>

  
  
  
  <div><h3 class="text-center">Patients</h3></div>
  <p></p>
  
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
      
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
        <router-link to="/addpatient"><button type="button" class="btn btn-default btn-sm" href="#../components/AddPatient.vue" id="add">
					<span  aria-hidden="true"></span> +Add New Patient
        </button></router-link>
        <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</div>
        <div></div>
        <button type="button" class="btn btn-default btn-sm"  id="ExtoEx">
					<span  aria-hidden="true"></span> Export to Excel
				</button>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Filter by Patient Name      " aria-label="Search">
        
      </form>
    </div>
  </nav>
  <div class="container mt-4" id="app">
    <table class="table table-hover">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Name &#9660;</th>
          <th scope="col">Email</th>
          <th scope="col">Phone</th>
          <th scope="col">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
          <th scope="col">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Patient 1</td>
          <td>patient1@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>

        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Patient 2</td>
          <td>patient2@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Patient 3</td>
          <td>patient3@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        <tr>
          <th scope="row">4</th>
          <td>Patient 4</td>
          <td>patient4@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        <tr>
          <th scope="row">4</th>
          <td>Patient 4</td>
          <td>patient4@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        <tr>
          <th scope="row">5</th>
          <td>Patient 5</td>
          <td>patient5@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        <tr>
          <th scope="row">6</th>
          <td>Patient 6</td>
          <td>patient6@mail.com</td>
          <td>123-456-7890</td>
          <td><button type="button" class="btn btn-light" id="a">Edit Profile</button></td>
          <td><button type="button" class="btn btn-light" id="a">Prescription</button></td>
        </tr>
        
        
      </tbody>
    </table>

    
  </div>
  <div class="pagination" id="page">

    
    <a  class="active" href="#">1</a>
    <a  href="#">2</a>
    <a href="#">3</a>
    <a href="#">4</a>
    <a href="#">5</a>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
    
  </div>
  <router-view />
</template>
 


<style lang="scss">

</style>
