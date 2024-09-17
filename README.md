# Registration-form-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project 2</title>
</head>
<body>
    <main>
        <h1><u>Registration Form</u></h1>
        <form action="/action.php">
            <input type="text" placeholder="Enter Username">
            <br>
            <br>
            <input type="text" placeholder="Enter Password">
            <br>

            <h4><u>Select Your Class</u></h4>
            <label for="101">
            <input type="radio" value="class XI" name="class" id="101">class XI
            </label>
            <br>

            <label for="102">
            <input type="radio" value="class XII" name="class" id="102">class XII
            </label>
            <br>

            <h4><u>Select Your Subject</u></h4>
            <label for="Math">
                <input type="checkbox" value="math" name="subject" id="101">Math
            </label>
            <br>

            <label for="Phy">
                <input type="checkbox" value="Phy" name="subject" id="102">Phy
            </label>
            <br>

            <label for="Chem">
                <input type="checkbox" value="Chem" name="subject" id="103">Chem
            </label>
            <br>

            <label for="Bio">
                <input type="checkbox" value="Bio" name="subject" id="104">Bio
            </label>
            <br>

            <label for="IT">
                <input type="checkbox" value="IT" name="subject" id="105">IT
            </label>
            <br>
            <h4><u>Select Your City</u></h4>
            <select name="city">
                <option value="Banglore">Banglore</option>
                <option value="Delhi">Delhi</option>
                <option value="Mumbai">Mumbai</option>
                <option value="Pune">Pune</option>

            </select>
            <br>
            <br>
            <h4><u>Give Your Valuable Feedback</u></h4>
            <textarea name="feedback" id="101" placeholder="Feedback">Feedback</textarea>
            <br>

            <input type="submit" value="submit">
        </form>

    
    
    </main>

    <footer></footer>
</body>

</html>
