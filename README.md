<!DOCTYPE html>

<html>
<head>
    <title>My first website</title>
</head>
<body>

    <form action="action_page.php" method="POST">

        <div>
            <label for="fname">first name:</label>
            <input type="text" id="fname" name="fname" placeholder="Spongebob" required>
        </div>

        <br>

        <div>
            <label for="lname">last name:</label>
            <input type="text" id="lname" name="lname" placeholder="Squarepants" required>
        </div>

        <br>

        <div>
            <label for="pass">password:</label>
            <input type="password" id="pass" name="pass" maxlength="12" required>
        </div>

        <br>

        <div>
            <label for="email">email:</label>
            <input type="email" id="email" name="email" placeholder="SPants@gmail.com">
        </div>

        <br>

        <div>
            <label for="phone">phone #:</label>
            <input type="tel" id="phone" name="phone" placeholder="(123)-456-7890">
        </div>

        <br>

        <div>
            <label for="bdate">birthdate:</label>
            <input type="date" id="bdate" name="bdate">
        </div>
        
        <br>

        <div>
            <label for="quantity">quantity:</label>
            <input type="number" id="quantity" name="quantity" min="0" max="99" value="1">
        </div>
        
        <br>

        <div>
            <label for="title">title:</label>

            <label for="Mr.">Mr.</label>
            <input type="radio" id="Mr." name="title" value="Mr.">

            <label for="Mrs.">Mrs.</label>
            <input type="radio" id="Mrs." name="title" value="Mrs.">

            <label for="PhD.">PhD.</label>
            <input type="radio" id="PhD." name="title" value="PhD.">
        </div>
        
        <br>

        <div>
            <label for="payment">payment:</label>
            <select id="payment" name="payment">
                <option value="visa">visa</option>
                <option value="mastercard">mastercard</option>
                <option value="giftcard">giftcard</option>
            </select>
        </div>
        
        <br>

        <div>
            <label for="subscribe">subscribe:</label>
            <input type="checkbox" id="subscribe" name="subscribe" min="0" max="99" value="1">
        </div>
        
        <br>

        <div>
            <input type="reset">
        </div>

        <br>

        <div>
            <input type="submit">
        </div>

    </form>

</body>
</html>
