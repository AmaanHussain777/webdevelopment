<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Football Tournament.</title>
    <link rel="stylesheet" href="day2.css">
</head>

<body>
    <h1 align="center">Football Tournament</h1>
    <h2>Team List</h2>
    <ol>
        <li>Real Madrid juniors.fc</li>
        <li>Boca juniors fc</li>
        <li>Flow Global Football</li>
        <li>PSG football academy</li>
        <li>Manchester United academy</li>
    </ol>
    <p><b>Note:</b> Maximum 6 teams are allowed in the tournament <br>
        This tournament will be held in league format </p>
    <h2>Match schedule</h2>
    <table border="3">
        <tr>
            <th>Day</th>
            <th>Round</th>
            <th>Match timing</th>
        </tr>
        <tr>
            <td>1</td>
            <td>1,2 and 3</td>
            <td>5pm to 6pm</td>
        </tr>
        <tr>
            <td>2</td>
            <td>4,5 and 6</td>
            <td>5pm to 6pm</td>
        </tr>
        <tr>
            <td>Final Day</td>
            <td>7,8,9 and 10</td>
            <td>8pm to 10pm</td>
        </tr>
    </table>
<p style="color: red;"><b>Note:</b> Award ceremony will also be held on the final day.</p>
<table border="2">
    <tr>
    <th colspan="4">Previous year tournament top scorer</th>
    </tr>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Description</th>
        <th>Photo</th>
    </tr>
    <tr>
        <td>Amaan Hussain</td>
        <td>15yrs.</td>
        <td>,playmaker,topscorer</td>
        <td><img src="mc.jpeg.jpg" alt="PlayerImage" height="100"></td>
    </tr>
</table>
 <h3>Registration Form for teams</h3>
    <form>
        <label for="Name">Team Name:</label><input type="text" placeholder="enter team name" id="Name" required><br>
        <label for="contact">Contact No.</label><input type="tel" id="contact" required><br> 
        <label for="email">Email ID</label><input type="email" id="email" required><br>
        <input type="submit"><br>
        <input type="reset">
    </form>
    <p><b>Note:</b>You will receive a Team code after registration, keep that code safe.</p>
<script src="day2.js">java</script>
</body>
</html>
