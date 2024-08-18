# Survey
<link rel="stylesheet" href="style.css">
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset = "utf-8">
    <h1 id="title"> Survey Feedback Form
    </h1>
  </head>
  <body>
    <p id="description">Thank you for taking the time to complete this form. Please follow the requests below</p>
    <form method = "post" id = "survey-form">
      <fieldset> 
      <label id= "name-label">Enter your Name: <input id="name" name = "name" type = "text" required placeholder = "Please enter your name"/></label><br>
      <label id= "email-label">Enter your Email: <input id="email" type = "email" name="email" required placeholder = "Please enter email address"/></label><br>
      <label id="number-label">Rate the work: <input id = "number" type="number" min = 0 max = 10 placeholder = "Please enter mobile or telephone number"><br>
      <label for = "Select">Please Select one of the following options: 
      <select id = "dropdown"><option value = "">(Select One)</option>
        <option value = 1>Ben is great</option>
        <option value = 2>Ben is not so great</option>
      </select>
      </label>
      <legend for= "Reuse">Would you use the Service Again?</legend>
      <label for= "yes">Yes<input id = "yes" type ="radio" name = "option-type" class= "inline" value = 1></label><br>
      <label for= "no">No<input id = "no" type ="radio" name = "option-type" class= "inline" value = 2></label><br>
      <textarea id="other" name = "bio" placeholder = "Please share your thoughts"></textarea><br>

<label for = "Contact">Please select your preferred contact method: </label><br>
<label for = "email"><input type = "checkbox" value = 1>email</label>
<label for = "phone"><input type = "checkbox" value = 2>phone</label>
<br>
<label for = "submit"><button id = "submit" value = "Submit">Submit</label>


     </fieldset>
    </form>
  </body>

