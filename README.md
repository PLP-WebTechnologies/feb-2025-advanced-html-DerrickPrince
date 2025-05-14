<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h2>Roman Numeral List</h2>
    <ol type="I">
        <li>First point</li>
        <li>Second point</li>
        <li>Third point</li>
        <li>Fourth point</li>
        <li>Fifth point</li>
    </ol>

    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1563356/pexels-photo-1563356.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="a road in the winter">

    <h2>Contact List</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Alice Wonderland</td>
                <td>12 Rabbit Hole, Wonderland</td>
                <td>555-0100</td>
                <td>alice.w@wonder.land</td>
            </tr>
            <tr>
                <td>Bob The Builder</td>
                <td>Construction Site A, Bobsville</td>
                <td>555-0101</td>
                <td>bob.builder@canwefixit.com</td>
            </tr>
            <tr>
                <td>Charlie Chaplin</td>
                <td>Silent Film Studio, Hollywood</td>
                <td>555-0110</td>
                <td>charlie.c@silent.screen</td>
            </tr>
            <tr>
                <td>Dorothy Gale</td>
                <td>Yellow Brick Road, Emerald City</td>
                <td>555-0111</td>
                <td>dorothy.g@oz.gov</td>
            </tr>
            <tr>
                <td>Eve Harrington</td>
                <td>Backstage Door #3, Theatre District</td>
                <td>555-1000</td>
                <td>eve.h@stage.strut</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <div>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required placeholder="Your Full Name">
        </div>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required placeholder="Your Email">
        </div>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required placeholder="Your Password" minlength="8">
        </div>
        <div>
            <label for="birthdate">Date of Birth:</label>
            <input type="date" id="birthdate" name="birthdate">
        </div>
        <div>
            <label for="occupation">Occupation:</label>
            <select id="occupation" name="occupation">
                <option value="">Select your occupation</option>
                <option value="student">Student</option>
                <option value="engineer">Engineer</option>
                <option value="designer">Designer</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div>
            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
        </div>
        <div>
            <p>Interests:</p>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="design" name="interests" value="design">
            <label for="design">Design</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
        </div>
        <button type="submit">Register</button>
    </form>

    <h2>Beach Video</h2>
    <video controls width="320" height="240">
        <source src="beach.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>
</body>

</html>git add registration_form.html
