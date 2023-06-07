<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>freeCodeCamp Survey Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1 id = "title">freeCodeCamp Survey Form</h1>
    <p id="description">This is a brief description of my page.</p>
      <form id = "survey-form"> 
        <fieldset>

<label for="name" id="name-label">Name:
  <input type="text" id="name" name="name" placeholder="Enter your name" required/> </label>

<label for="email" id="email-label"> 
  Email: <input type="email" id="email" name="email" placeholder="Enter your Email" required/></label>

<label for="number" id="number-label">
  Enter Your Number <input type="number" id="number" name="number" min= "0" max = "10" placeholder="Number" required /></label>

  <label for="Options">How did you hear about us?
          <select id="dropdown" name="Options">
            <option value="">(select current role)</option>
            <option value="1">Student</option>
            <option value="2">Full Time Job</option>
            <option value="3">Full Time Learner</option>
            <option value="4">Prefer not to say</option>
            <option value="5">Other</option>
          </select>
        </label>


<label> Would you recommend freeCodeCamp to a friend?
  </label>

      <p>
        <label for="Definitely"><input value ="Definitely" type="radio" name="freeCodeCamp" class="inline" /> Definitely </label>
        <label for="Maybe"><input value="Maybe" type="radio" name="freeCodeCamp" class="inline" /> Maybe</label>
        <label for="Not sure"><input value="Not sure" type="radio" name="freeCodeCamp" class="inline" /> Not sure</label>
</P>
         </form>

         <form>
  <p>Would you recommend freeCodeCamp to a friend?</p>
  <input type="radio" id="red" name="color" value="red">
  <label for="red">Red</label><br>
  <input type="radio" id="blue" name="color" value="blue">
  <label for="blue">Blue</label><br>
  <input type="radio" id="green" name="color" value="green">
  <label for="green">Green</label><br>
</form>
<form>
  <p>What would you like to see improved? (Check all that apply)</p>
  <label for="Survey Form">
          <input id="Survey Form" type="checkbox" value = "checkbox" class="inline" /> Front-end Projects
        </label>
<label for="Survey Form">
          <input id="Survey Form" type="checkbox" value = "checkbox"  class="inline" /> Back-end Projects
        </label>
<p></p>
<label for="Survey Form">Any comments or suggestions?
          <textarea id="C&S" name="C&S" rows="4" cols="30" placeholder="Enter your comments here..."></textarea>
        </label>

<label for="Survey Form">
        <input type="submit" id = "submit"value="Submit" /> </label>
  </html>
