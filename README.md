# CRM-systems
#1.CRM.html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
 font-family: Arial, Helvetica, sans-serif;
 background-color: black;
}
* {
 box-sizing: border-box;
}
/* Add padding to containers */
.container {
 padding: 16px;
 background-color: white;
}
/* Full-width input fields */
input[type=text], input[type=password] {
 width: 100%;
 padding: 15px;
 margin: 5px 0 22px 0;
 display: inline-block;
 border: none;
 background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
 background-color: #ddd;
 outline: none;
}
/* Overwrite default styles of hr */
hr {
 border: 1px solid #f1f1f1;
 margin-bottom: 25px;
}
/* Set a style for the submit button */
.registerbtn {
 background-color: #04AA6D;
 color: white;
 padding: 16px 20px;
 margin: 8px 0;
 border: none;
 cursor: pointer;
 width: 100%;
 opacity: 0.9;
}
.registerbtn:hover {
 opacity: 1;
}
/* Add a blue text color to links */
a {
 color: dodgerblue;
}
/* Set a grey background color and center the text of the "sign in" section */
.signin {
 background-color: #f1f1f1;
 text-align: center;
}
</style>
</head>
<body>
<form action="/action_page.php">
 <div class="container">
 <h1>Register</h1>
 <p>Please fill in this form to create an account.</p>
 <hr>
 <label for="email"><b>Email</b></label>
 <input type="text" placeholder="Enter Email" name="email" id="email" required>
 <label for="psw"><b>Password</b></label>
 <input type="password" placeholder="Enter Password" name="psw" id="psw" required>
 <label for="psw-repeat"><b>Repeat Password</b></label>
 <input type="password" placeholder="Repeat Password" name="psw-repeat" id="psw-repeat" 
required>
 <hr>
 <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>
 <input type="submit" value="Register" onClick="myFunction()"/>
 <script>
 function myFunction() {
 window.location.href="pipelinepage.html";

 
 }
 </script>
 </div>
 
 <div class="container signin">
 <p>Already have an account? <a href="login.html"> Sign in</a>.</p>
 </div>
</form>
</body>
</html>
2.LOGIN.html:
<html>
<style>
body {
 font-family: Arial, Helvetica, sans-serif;
 background-color: skyblue;
}
* {
 box-sizing: border-box;
}
/* Add padding to containers */
.container {
 padding: 16px;
 background-color: white;
}
/* Full-width input fields */
input[type=email], input[type=password] {
 width: 100%;
 padding: 15px;
 margin: 5px 0 22px 0;
 display: inline-block;
 border: none;
 background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
 background-color: #ddd;
 outline: none;

}
/* Overwrite default styles of hr */
hr {
 border: 1px solid #f1f1f1;
 margin-bottom: 25px;
}
/* Set a style for the submit button */
.registerbtn {
 background-color: #04AA6D;
 color: white;
 padding: 16px 20px;
 margin: 8px 0;
 border: none;
 cursor: pointer;
 width: 100%;
 opacity: 0.9;
}
.registerbtn:hover {
 opacity: 1;
}
/* Add a blue text color to links */
a {
 color: dodgerblue;
}
/* Set a grey background color and center the text of the "sign in" section */
.signin {
 background-color: #f1f1f1;
 text-align: center;
}
</style>
 Email:
<input type="email" id="email" name=""><br><br>
Password:
<input type="password" id="password" name=""><br><br>
<input type="submit" onClick="myFunction()"/>
 <script>
 function myFunction() {
 window.location.href="pipelinepage.html" 
 }
 </script>
</form>
</body>
 
22
</html>
3.STARTUP.html:
<html>
<style>
body{
background-color:gray;}
h1{
color:pink;
}
h2{
color:gold;
}
p{
color:white;
}
</style>
<body>
<h1 align="center"> WELCOME TO CRM SYSTEM FOR STARTUP </h1>
<h1 style="color:violet;"> Steps for pipe drive</h1>
<h2>1. Set up your pipeline stages</h2><br><br>
<p>Your pipeline is a visual representation of your sales process. It’s totally
customizable to fit how you work. Name the stages based on the steps you take deals through to 
close, or choose a template. Now you’re ready to fill it with deals.<p>
<br><br>
<img src="C:\Users\Harshitha\Downloads\pipedrive_workflow.jpg"><br><br>
<h2>2. Focus on sales actions</h2><br><br>
<p>
Instead of thinking about the finish line – the sale – focus on the actions that get you there. A sales 
activity is anything that moves your deals toward closing. It can be a phone call, lunch, meeting, 
email or anything in between. Schedule plenty of activities and let Pipedrive remind you what to do 
next.
</p><br><br>
<h2>3. Track progress towards goals</h2><br><br>
<p>As you do activities and drive deals forward, Pipedrive monitors your performance like a coach. 
It calculates your average conversion rate so you know how many new leads to get and activities to 
complete to meet your targets. Real time reports show if you’re on track, giving you time to adjust 
course if needed.
</p><br><br>
<img src="C:\Users\Harshitha\Downloads\biggest-sales-challenge.jpg"><br><br>
<h2>4. Optimize and grow</h2><br><br>
<p>Pipedrive’s easy analytics get your sales process down to a science. No more shutting your eyes 
and hoping for the best. Automations do admin tasks for you, while integrations with your favorite 
tools save you time. All that’s left is to refine your winning formula and set even bigger goals.
</p><br><br>
<img src="C:\Users\Harshitha\Downloads\pipeline (1).png" <body><html>
