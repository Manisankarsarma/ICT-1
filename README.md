# ICT-1
<html>
    
    <head>
        <title>Login</title>
        
        <script>
            
            function checkforblank()
            {
                var errormessage = "";
                
                if(document.getElementById('fname').value == "")
                {
                    errormessage += "Enter your first name\n";
                    document.getElementById('fname').style.borderColor="red";
                   return false;
                }                
            }
        </script>
    </head>
    
    <body>
        
        <form method="post" action="#" onsubmit="checkforblank">
        <fieldset>
            <legend>Login</legend>
            <label for="FirstName">First Name:</label>
            <input type="text" id="fname">
            <br><br>
            <label for="LastName">Last name:</label>
            <input type="text" id="lname">
            <br>
            
            <input type="submit" value="Send">
        </fieldset>
        </form>
    </body>
</html>
