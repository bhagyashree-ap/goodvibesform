#goodvibesform.html

<html>
<title>Good Vibes Form</title>
<body>
<style>

body{
text-align: center;
background-color: paleturquoise;
}
form
{ 
display: inline-block;
margin-left: auto;
margin-right:auto;
text-align:left;
}
</style>

<h1 style="color:dimgrey;height="400px" > Good Vibes Form </h1>

<h2 style="color:grey;">Tell us what is something good <br> that happened to you today?</h2>

<form>

<h2> Name: </label><input type="text" id="n" name="n" placeholder="Enter your name" style="height:35.5px;" size="30" required><br><br> 

Rate your happy experience:  <input type="number" id="num" name="num" min="1" max="10" placeholder="1-10" style="height:30px;"required> <br><br>

When did it happened? <br>
<input type="radio" name="when" value="morning" >Morning <br>
<input type="radio" name="when" value="afternoon">Afternoon <br>
<input type="radio" name="when" value="evening">Evening <br>

<br>Where did it happen? 
<select style="height:40px;">
<option> Select </option>
<option> At home </option>
<option> On street </option>
<option> At work </option>
<option> While Commuting </option>
<option> Other </option>
</select> 

<br><br>What emotion did you experience?<br>(Select Multiple)<br>
<input type="checkbox" id="whatemotion" name="whatemotion" value="Excited"> 
<label for="whatemotion1"> Excited </label><br>
<input type="checkbox" id="whatemotion2" name="whatemotion2" value="Happy"> 
<label for="whatemotion2"> Glad </label><br>
<input type="checkbox" id="whatemotion3" name="whatemotion3" value="Grateful"> 
<label for="whatemotion3"> Grateful </label><br>
<input type="checkbox" id="whatemotion4" name="whatemotion4" value="Inspired"> 
<label for="whatemotion4"> Inspired </label><br>
<input type="checkbox" id="whatemotion5" name="whatemotion5" value="Amused"> 
<label for="whatemotion5"> Amused </label><br>
<input type="checkbox" id="whatemotion6" name="whatemotion6" value="Lucky"> 
<label for="whatemotion6"> Lucky </label><br>

<br>Describe your experience: <br><textarea name="message" rows="5" cols="45">Describe your Experience </textarea><br><br>

<input type="Submit" alt="submit"> 
