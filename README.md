# index-2-.html
<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My website</title>
    <style>
        /* Add some basic styling to make the page look better */
        body {
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
        }
    </style>
</head>
<body>
    <!-- Ordered list -->
    <h2>Ordered List </h2>
    <ol type="I">
        <li>Object 1</li>
        <li>Object 2</li>
        <li>Object 3</li>
    </ol>

    <!-- External image from pexels.com -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/248797/pexels-photo-248797.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="External Image" width="500" height="300">

    <!-- Table of 5 contacts -->
    <h2>Contacts Table</h2>
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
                <td>John Doe</td>
                <td>123 Makuyu</td>
                <td>0134563578</td>
                <td>johndoe@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Mweni</td>
                <td>673 Kiharu</td>
                <td>0106745629</td>
                <td>janemwenik@gmail.com</td>
            </tr>
            <tr>
                <td>princess cate</td>
                <td>245 Umoja</td>
                <td>0100585264</td>
                <td>cateline2@gmail.com</td>
            </tr>
            <tr>
                <td>Alice Johnson</td>
                <td>321 Muhoroni</td>
                <td>0723456778</td>
                <td>alicejohnsoan@gmail.com</td>
            </tr>
            <tr>
                <td>Mike Brown</td>
                <td>901 Kangemi</td>
                <td>0700897643</td>
                <td>mikebrown@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required placeholder="Enter your password"><br><br>
        <label for="date">Date:</label>
        <input type="date" id="date" name="date" required><br><br>
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="">Select a country</option>
            <option value="Uganda">Uganda</option>
            <option value="Tanzania">Tanzania</option>
            <option value="Kenya">Kenya</option>
        </select><br><br>
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label><br><br>
        <label for="hobbies">Hobbies:</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="writing" name="hobbies" value="writing">
        <label for="writing">Writing</label>
        <input type="checkbox" id="coding" name="hobbies" value="coding">
        <label for="coding">Coding</label><br><br>
        <input type="submit" value="Submit">
    </form>

    <!-- Audio and video elements -->
    <h2>Audio and Video Elements</h2>
    <audio controls>
        <source src="audio.mp3" type="audio/mp3">
    </audio>
    <video controls>
        <source src="video.mp4" type="video/mp4"
    </video>
</body>
</html>
