# TASK
 Week 2 side hustle task
<!DOCTYPE html>
<html>
    <head>SIMPLE FORM</head>
    <style>
       
        body {
            background-color: rgb(165, 184, 146);
            background-image: url(ff411dbc1e4883125a61db9aba4660ec_screen.jpg);
            background-repeat: no-repeat;
            background-size: 100%;
            overflow: hidden;
            color: white;
            text-align: center;
            margin: 0%;
        }

        h1 {
            background-color: black;
            color: rgb(4, 27, 128);
            text-align: center;
            margin: 0%;
            padding: 20px;
            
        }
        p {
            margin: 0%;
        }
        button {
            color: white;
            background-color: black;
            font-size: 12px;
            padding: 6px;
            border-radius: 16px;
            border-color: azure;
            border: 1;
            width: 75px;
            justify-content: center;

        }
        button:hover {
            background-color: gray;
        }
        input {
            border-color: blue;
            border-radius: 16px;
            
        }
        select {
            border-color: blue;
            border-radius: 16px;
            font-size: 12px;
            justify-content: center;
            width: 75px;
        }
        fieldset {
            background-color: rgb(31, 141, 175);
            background-image: url(backgroundsTiktok\ backgrounds\ -\ Made\ with\ PosterMyWall.png);
        }

    </style>
    <Body>
        <h1>TASK</h1>
        <form onsubmit="myFunction()">
            <fieldset style>
                
                <label for="Fullname">Fullname</label>
                <br>
                <input type="text" name="Fullname" id="Fullname">
                <br>
                <label for="Email">Email</label>
                <br>
                <input type="Email" name="Email" id="Email" required>
                <br>
                <label for="Phone number">Phone number</label>
                <br>
                <input type="Phone number" name="Phone number" id="Phone number">
                <br>
                <p>Gender</p>
                <select id="Gender">
                    <option value="Male">Male</option>
                    <option value="Female">Female</option>
                  

                </select>
               
                <br>
                <label for="Password">Password</label>
                
                <input type="text" name="Password" id="Password">
                <button class="Submit">Submit</button>
                

            </fieldset>
        </form>
        <script>
            function myFunction() {
                alert ("Submitted")
            }
        </script>
    </Body>
</html>
