<template>
<div class="wrapper">
    <nav id="sidebar" class="sidebar">
	<div class="sidebar-header">
            <p><img src="../assets/schoolLogo.png"/>Handmaid's International<i class="fa fa-caret-down" style="color:  #1B75BB; margin-left:5px;"></i></p>
	</div>
    <div class="blue-area">
        <ul>
            <li><img src="../assets/dashboardlogo.png"/>Dashboard</li>
            <div class="dropdown">
        <li><img src="../assets/students.png"/>Students<i class=" me fa fa-caret-down"></i></li>
            <div class="dropdown-content">
            <a href="#">A</a>
            <a href="#">B</a>
            <a href="#">C</a>
            </div>
             </div>
             <div class="dropdown">
             <li><img src="../assets/employees.png"/>Employees<i class="me2 fa fa-caret-down"></i></li>
            <div class="dropdown-content">
            <a href="#">1</a>
            <a href="#">2</a>
            <a href="#">3</a>
            </div>
             </div>
        
             <li><img src="../assets/parentsguardians.png"/>Guardians</li>
            
            
        
             <div class="dropdown">
             <li><img src="../assets/attendance.png"/>Attendance<i class="me1 fa fa-caret-down"></i></li>
            <div class="dropdown-content">
            <a href="#">A</a>
            <a href="#">B</a>
            <a href="#">C</a>
            </div>
             </div>

            <div class="dropdown">
             <li><img src="../assets/finance.png"/>Finance<i class=" me fa fa-caret-down"></i></li>
            <div class="dropdown-content">
            <a href="#"> 1</a>
            <a href="#"> 2</a>
            <a href="#"> 3</a>
            </div>
             </div>

            
            <li><img src="../assets/subjects.png"/>Subjects</li>
            <li><img src="../assets/batches.png"/>Batches</li>
            <li><img src="../assets/reportcards.png"/>Report Cards</li>
            <li><img src="../assets/sms.png"/>SMS</li>

            <div class="dropdown">
             <li><img src="../assets/events.png"/>Events<i class=" me1 fa fa-caret-down"></i></li>
            <div class="dropdown-content">
            <a href="#">Link A</a>
            <a href="#">Link B</a>
            <a href="#">Link C</a>
            </div>
             </div>
              
            <hr>
            <li>Settings</li>
        </ul>

        <div class="foot">
            <button class="btn"><img src="../assets/question.png">Help</button>
            <span class="terms">Terms. Privacy</span>
        </div>
    </div>    
	</nav>
</div>
</template>

<style>
.wrapper {
    display: flex;
    align-items: stretch;
    perspective: 1500px;
}
    .sidebar {
    min-width: 250px;
    max-width: 250px;
    background: #ffffff;
    color: #2C2C2C;
    font-size: 14px;
    font-weight: bold;
    line-height: 22px;
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.170509);
    position: fixed; /* Fixed Sidebar (stay in place on scroll) */
    z-index: 1; /* Stay on top */
    top: 0; /* Stay at the top */
    left: 0;
    }
    .sidebar-header {
        margin-top: 20px;
        margin-left: 20px;
}
    .blue-area {
        background: linear-gradient(136.25deg, #1B75BB 0%, #00ADEE 100%);
        padding:0px;
        margin:0px;
    }
    li img {
        margin-right: 10px;
    }
    ul{
        list-style: none;
        line-height: 4;
        color:#ffffff;
        padding: 0px;
        margin:0px;
        text-align: left;
        padding-left:30px;

    }
    li .fa {
        float: right;
        margin-right: 50px;
        line-height: 4;   
    }


    
    li:hover {
        color: #e29f9f;
    
    }
    hr{
        margin-left: -39px;
        width: 250px;
        background: #ffffff;
    } 
    .foot {
       margin-top: 40px;
       display: flex;
       margin-left: 30px;
       color: #ffffff;
    }
    .btn {
        width: 100px;
        height: 38px;
        border-radius: 20px;
        background: #ffffff;
        color: #1B75BB;
        margin-bottom: 10px;
    }
    button img {
        margin-right: 5px;
    }
    .terms {
        color: #ffffff;
        margin-left: 15px;
        margin-top: 6px;
        font-size: 14px;
    }

    
/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: block;
}

.me{

margin-left: 75px;

}
.me1{
   margin-left: 60px; 
}

.me2 {
    margin-left:50px;
}
/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
    width: 50px;
  min-height: 10px;
  background-color: #e29f9f;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  text-align: center;

  
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 0;
  text-decoration: none;
  display: block;
  flex:right;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #ddd;}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover li {background-color:#1B75BB #1B75BB;}
</style>