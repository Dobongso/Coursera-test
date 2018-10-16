<!DOCTYPE html>
<html>
<head>

          <title>Assignment module 2</title>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1">
          <link rel="stylesheet" href="css/style.css">
<style>
/***** BASE STYLES *****/

* {
	box-sizing: border-box;
	    position: relative;
 }
h1 {
    position: relative;
    width: 100%;
    text-align: center;
	margin-bottom: 15px;
	font-family: Helvetica;
	font-size: 1.7em;
}

p {
	border: 1px solid black;
	backgroung-color: #A52A2A;
	width: 95%;
	height: 100%;
	margin-top: 10px;
	margin-right: auto;
    margin-left:  auto;
    margin-bottom: 10px;
    font-family: Helvetica;
    color: black;
}

 /* simple responsive framework. */
.row{
	width: 100%;
}
.section{
         position: relative;
         width: 95%;
         border: 1px solid black;
         background-color: #808080;
         margin: auto;
         margin-top: 2.5%;
         margin-bottom: 2.5%;
         paddimg-top: 0px;
 }
 .section-title{
          positiom: relative;
          width: 30%;
          height: 30px;
          border: 1px solid black;
          text-align: center;
      font-family: Helvetica;
      font-size: 1.25em;
           padding-top: 2px;
           margin-top: -1px;
           margin-right: -1px;
           margin-bottom: 2px;
 }        
 #Chicken{
        background-color: #ffc0cb;

 }
 #Beef{
      background-color: #A52A2A;
      color: white;
 }
#Sushi{
	background-color: #f2dea6;
}

 /***** large devices only *****/


@media(min-width: 992px)  {
	.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12{  
	   float: left;
 }
 .col-lg-1{
	width: 8.33%;
 }
 .col-lg-2{
	width:16.66%;
 }
 .col-lg-3{
	width: 25%;
 }
 .col-lg-4{
	width: 33%;
 }
 .col-lg-5{
	width: 41.66%;
 }
 .col-lg-6{
	width: 50%;
 }
 .col-lg-7{
	width: 58.33%;
 }
 .col-lg-8{
    width: 66.66%;
 }
 .col-lg-9{
	width: 74.99%;
 }
 .col-lg-10{
	width: 83.33%;
 }
 .col-lg-11{
	width: 91.66%;
 }
 .col-lg-12{
	width: 100%;
  }

}
/***** medium devices only *****/


@media(min-width: 768px) and (max-width: 991px)  {
	.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12{  
	float: left;
 }
 .col-md-1{
	width: 8.33%;
 }
 .col-md-2{
	width:16.66%;
 }
 .col-md-3{
	width: 25%;
 }
 .col-md-4{
	width: 33%;
 }
 .col-md-5{
	width: 41.66%;
 }
 .col-md-6{
	width: 50%;
 }
 .col-md-7{
	width: 58.33%;
 }
 .col-md-8{
    width: 66.66%;
 }
 .col-md-9{
	width: 74.99%;
 }
 .col-md-10{
	width: 83.33%;
 }
 .col-md-11{
	width: 91.66%;
 }
 .col-md-12{
	width: 100%;
 }
  .Sushi-negative-margin{
  	margin-left: 1.25%;
  	margin-right: 1.25%;
  	margin-top: 1.25%;
  	width: 97.5%
  }
 

 }
</style>
</head>
<body>
	<h1>OUR MENU</h1>

<div class="row">
	<div class="col-lg-4 col-md-6">
		<div class="section">
			<p class="section-title" id="Chicken">Chicken</p>
		<p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Utenim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquio ex ea commodo consequat. </p> 
	   </div>
	</div>

		<div class="col-lg-4 col-md-6">
		     <div class="section">
			<p class="section-title" id="Beef">Beef</p>
		<p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Utenim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquio ex ea commodo consequat. </p> 
	    </div>
	 </div>

		<div class="col-lg-4 col-md-6">
		     <div class="section">
			<p class="section-title" id="Sushi">Sushi</p>
		<p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Utenim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquio ex ea commodo consequat. </p>
		 </div>
		</div>
</div>
</body> 
</html>
