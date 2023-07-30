# form
<!-- hosted link -->
https://ajit7568.github.io/form/
html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body oncontextmenu="return false;">
    <!-- The HTML form starts here -->
    <form>
        <!-- Personal Details Section -->
        <fieldset>
            <legend>Personal Details</legend>
            <!-- Firstname Input -->
            <label> Firstname </label>         
            <input type="text" name="firstname" size="15"/> <br> <br>

           <!-- Middlename Input -->
   <label> Middlename: </label>     
        <input type="text" name="middlename" size="15"/> <br> <br>

            <!-- Lastname Input -->
   <label> Lastname: </label>         
            <input type="text" name="lastname" size="15"/> <br> <br>

            <!-- Course Selection Dropdown -->
   <label> Course: </label>   
            <select>  
                <option value="Course">Course</option>  
                <option value="BCA">BCA</option>  
                <option value="BBA">BBA</option>  
                <option value="B.Tech">B.Tech</option>  
                <option value="MBA">MBA</option>  
                <option value="MCA">MCA</option>  
                <option value="M.Tech">M.Tech</option>  
            </select>  
            <br>  
            <br>

            <!-- Gender Selection -->
  <label>Gender:</label>
            <br>
            <input type="radio" name="gender"/> Male <br>
            <input type="radio" name="gender"/> Female <br>
            <input type="radio" name="gender"/> Other  
            <br>  
            <br>  

            <!-- Date of Birth Input -->
  <label>DOB</label>
            <input type="datetime-local" name="dob" id="">
            <br>

            <!-- Phone Input -->
  <label>Phone:</label>  
            <input type="text" name="country code" value="+91" size="2" disabled/>   
            <input type="tel" name="phone" maxlength="10" size="10"/> <br> <br>  

            <!-- Address Textarea -->
  <label>Address:</label>
            <br>  
            <textarea cols="80" rows="5" value="address"></textarea>  
            <br> <br>  

            <!-- Email Input -->
  <label>Email:</label> 
            <input type="email" id="email" name="email"/> <br>    
            <br> <br>  

            <!-- Password Input -->
  <label>Password:</label>
            <input type="Password" id="pass" name="pass"> <br>   
            <br> <br>  

            <!-- Retype Password Input -->
  <label>Re-type password:</label>  
            <input type="Password" id="repass" name="repass"> <br> <br>

            <!-- Agree to terms and conditions Checkbox -->
   <input type="checkbox" name="terms" id="">Agree to terms and conditions
            <br><br>

            <!-- File Input -->
   <label>Choose File</label>
            <input type="file" name="file" id="">
            <br><br>
            
            <!-- Color Input -->
   <label>Choose Color</label>
            <input type="color" name="color" id="">
            <br><br>

            <!-- Reset and Submit Buttons -->
   <input type="reset" value="Reset"/> 
            <input type="button" value="Submit"/>  
        </fieldset>
    </form>
</body>
</html>
<!-- The HTML form is created using the <form> tag. It contains various form elements such as input fields, dropdowns, radio buttons, checkboxes, and buttons.
Inside the <form> tag, we have used a <fieldset> tag to group related form elements together. The <legend> tag is used to specify the title of the fieldset.
The form includes input fields for capturing the user's personal details such as firstname, middlename, lastname, course, gender, date of birth, phone number, address, email, password, and retype password.
The disabled attribute is used in the country code input field to prevent user input.
The <textarea> tag is used to create a multiline text input field for the address.
The <input type="email"> tag is used to create an email input field that validates the user's email address.
The <input type="password"> tag is used to create a password input field that masks the input characters for security.
The <input type="checkbox"> tag is used to create a checkbox for the "Agree to terms and conditions" option.
The <input type="file"> tag is used to create a file input field for uploading files.
The <input type="color"> tag is -->
