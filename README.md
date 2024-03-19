# Making-form
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Form</title>

    <style>

        *{background-color: hsl(180, 100%, 97%);

        border-radius: 6px;}

        button{

            background-color:hsl(180, 79%, 94%);

        }

        button:hover{

            background-color: aquamarine;

        }

        

    </style>

</head>

<body>

    <form>

       <h3>Fill Up The Form</h3>

       First Name:- <input type="text" placeholder="eg, abcd"> 

       Last Name:- <input type="text"placeholder="eg, xyz"><br><br>

       <div>Mail <input type="email" placeholder="eg, name123@gmail.com"></div><br>

       <div>Password:- <input type="password" placeholder="******"></div><br>

       <div>Gender:- 

        <input type="radio" name="gender">Male

        <input type="radio" name="gender">Female

        <input type="radio" name="gender">Other </div><br>

        <input type="checkbox">Above all details in knowledge is true.<br><br>

        <div>

            <button id="Submit">Submit</button>

            <button id="Reset">Reset</button>

            <button id="Submit">Back</button>

        </div>





    </form>

</body>

</html>
