
<!DOCTYPE html>
<html>
<head>
<title>My page</title>
<style>
table, th, td {border: 1px solid black;border-collapse: collapse;}
th, td {padding: 5px;}
th {color:#DDAB03}
</style>
</head>
<body style="background-color:#0E6F02;">
<h1><center style="color:#FF8F00">Examples for HTML</center></h1>
<p><center>(This page built with HTML only)</center></p>
<h2>let's start the journey together</h2>
<p style="font-size:150%;">What do we need to build a page with HTML?</p>
<ul>
<li style="color:#DC6B08;">Notepad</li>
<li style="color:#DC6B08;">Any browser software </li>
</ul>
<p style="font-size:150%;">how de we view our source on the browser?</p>
<ol>
<li style="color:#DC6B08;">Write the HTML code on a notepad</li>
<li style="color:#DC6B08;">Save your text file like this:<span style="color:#DDD603;"> example.html</span></li>
<li style="color:#DC6B08;">Open the exmample.html file</li>
</ol>
<table style="width:50%">
<tr>
<th>Firstname</th>
<th>Lastname</th> 
<th>Age</th>
</tr>
<tr>
<td>Mohamed</td>
<td>Zaki</td>
<td>40</td>
</tr>
<tr>
<td>Alaa</td>
<td>Omar</td>
<td>68</td>
</tr>
<tr>
<td>Ali</td>
<td>Kamel</td>
<td>34</td>
</tr>
</table>
<hr>
<p style="font-size:150%;">Let's build a form using HTML</p>
<p>(Here you are Contacting with support)</p>
<form action="/action_page.php">
<fieldset>
<legend>Contact:</legend>
<label for="name"> Name:</label>
<input type="text" id="name" name="user_name"><br><br>
<label for="mail">Email:</label>
<input type="email" id="mail" name="user_email"><br><br>
<label>Departments:</label><br>
<input type="radio" name="Departments" value="Account_Administration"/>Account Administration<br/>
<input type="radio" name="Departments" value="Payments"/>Payments<br/>
<input type="radio" name="Departments" value="Refunds"/>Refunds<br/>
<input type="radio" name="Departments" value="Report_bugs"/>Report bugs<br/><br>
<label for="img">Select image:</label>
<input type="file" id="img" name="img" accept="image/*"><br/><br/>
<label for="msg">Message:</label><br>
<textarea id="msg" name="user_message"></textarea><br/><br/>
<label>Subscription:</label>
<select name="subscription">
<option value="option1">Basic</option>
<option value="option2"> premium</option>
</select>
<p><input type="submit" value="Send">
<input type="reset" value="Reset"></p>
</fieldset>
</form>
</body>
</html>
