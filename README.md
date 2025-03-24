<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <ol type="i">
        <h3>An ordered list with roman numerals</h3>
        <!-- this is the Ordered list with (i) romans numbes -->
        <li>Mangos</li>
        <li>Banana</li>
        <li>Apple</li>
        <li>Lemon</li>
        <li>Grapes</li>
    </ol>
    <h3>An external image from pexels.com</h3>
    <img src="https://images.pexels.com/photos/3397939/pexels-photo-3397939.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="This is a puppy" width="20%" height="20%">
    <table>
        <h3>Table of contacts </h3>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Girbert Masengeli</td>
            <td>2569234</td>
            <td>0113434984</td>
            <td>masengeli@gmailcom</td>
        </tr>
        <tr>
            <td>tutus</td>
            <td>256000</td>
            <td>049479230</td>
            <td>titius@gmailcom</td>
        </tr>
        <tr>
            <td>David njenga</td>
            <td>20500</td>
            <td>0113456050</td>
            <td>david@gmailcom</td>
        </tr>
        <tr>
            <td>joseph joroge</td>
            <td>206003</td>
            <td>076056346</td>
            <td>njoroge@gmailcom</td>
        </tr>
        <tr>
            <td>Zuma Jacob</td>
            <td>23567934</td>
            <td>01124323</td>
            <td>zuuma@gmail.com</td>
        </tr>
    </table>
    <h3>A registration form</h3>
    <form action=""post><br><br>
        <label for="name"></label>Enter user name
        <input type="text" placeholder="Enter your name"><br>
        <label for="email"></label>Enter Email
        <input type="email" placeholder="enter your email"><br>
        <label for="date"></label>Date
        <input type="date" placeholder="enter today's date"><br>
        <label for="countries">Countrie of origin</label>
        <select name="counties" id="counties">
            <option value="counties">countries</option>
            <option value="kenya">Kenya</option>
            <option value="Tz">Tanzania</option>
            <option value="UG">Uganda</option>
            <option value="Rwanda">Rwanda</option>
        </select><br>
        <label for="options">how interactive is Html</label>
        <input type="radio" name="option" id="option1" value="Option 1">
        <label for="option1">10%</label>
        <input type="radio" name="option" id="option2" value="Option 2">
        <label for="option2">50%</label>
        <input type="radio" name="option" id="option3" value="Option 3">
        <label for="option3">100%</label><br>
        <input type="checkbox"> Male
        <input type="checkbox"> Female <br>
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
    </form>
</html>
