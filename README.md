# Survey Form
HTML/CSS
This is from freeCodecamp Responsive-Web-Design Certification.
*************************HTML*************************

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Survey Form</title>
  <link rel="stylesheet" href="styles.css"/>
  </head>
 

<body>
<h1 id="title">Survey Form</h1>
<p id="description">Thank you for signing up for this awesome task!</p>
<form method="post" action="https://register-demo.freecodecamp.org" id="survey-form" name="survey-form">


<fieldset>
<label for="name" id="name-label">Name <input id="name" name="name" type="text" placeholder="Enter your name" required/> </label>


<label for="email" id="email-label">Email <input id="email" name="email" type="email" placeholder="Enter your email"required /></label>


<label for="number" id="number-label">Age <input id="number" name="number" type="number" min="13" max="120" placeholder="Age" value="number-label" required />  </label>



<label for="dropdown" name="dropdown">Choose your occupation
  <select id="dropdown">
    <option value=""> Occupation</option>
  <option value="1"> Freelance </option>
  <option value="2"> Student </option>
  <option value="3"> Full Time Job </option>
  <option value="4"> Full Time Learner </option>
  <option value="5"> Prefer not to say </option>
  </select>
   </label>
</fieldset>
 

  <fieldset>
  <legend> Which pets do you like the most?</legend>
  <label for="dog"><input type="radio" name="account-type" id="dog" checked value="dog"> Dogs</label>
  <label for="cat"><input type="radio" name="account-type" id="cat" value="cat"> Cats</label>
  <label for="pet"><input type="radio" name="account-type" id="pet" value="pet"> I am the pet >:(</label>
</fieldset>

  <fieldset>
    <label>
    <legend> Did you enjoy this survey?
      <label for="enjoy_yes"><input type="checkbox" name="account-type" id="enjoy_yes" checked value="enjoy_yes"> Yes!</label>
      <label for="enjoy_yes2"><input type="checkbox" name="account-type" id="enjoy_yes2" value="enjoy_yes2"> Yes.....</label>
<label for="enjoy_yes3"><input type="checkbox" name="account-type" id="enjoy_yes3" value="enjoy_yes3"> Yes *sigh*</label>
      </label>
  </fieldset>

<label for="bio">Any recommendations for the survey?<textarea placeholder="BARF BARF or MEOW" rows="3" cols="30"></textarea/></label>

<input type="submit" value="Submit" id="submit">
 </form>
</body>
</html>


***********CSS*************



body {
  width: 100%;
  height:100vh;
  margin:0;
  background-color: green;
  color: #f5f6f7;
  font-family: tahoma;
  font-size: 16px;
}

label {
  display:block;
  margin: 0.5rem 0;
}

  h1, p {
    margin: 1em auto;
    text-align: center;
  }

form {
  width: 60vw;
  max-width:500px;
  min-width:300px;
  margin: 0 auto;
  padding-bottom: 2em;
}

input[type="submit"] {
  display:block;
  width: 70%;
  min-width: 300px;
  margin: 1em auto;
  height: 2em;
  font-size: 1.5rem;
  background-color: #3b3b4f;
  color: white;
  
}

