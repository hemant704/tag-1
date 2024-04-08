<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Information Form</title>
    <style>
        body {
            font-family: Arial, sans-serif; #not useful
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin-bottom: 5px;
            color: #333;
        }
        input[type="text"], select {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4c4faf;
            background-color: #b96653;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Student Information Form</h1>
        <form action="#" method="post">
            <label for="name">User Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="roll">Enrollment Number:</label>
            <input type="text" id="roll" name="roll" required>
            
            <label for="course">Course:</label>
            <select id="course" name="course" required>
                <option value="">Select Course</option>
                <option value="Computer Science">Computer Science</option>
                <option value="Engineering">Engineering</option>
                <option value="Business">Business</option>
                <option value="Mathematics">Mathematics</option>
            </select>
            
            <label for="address">Sector:</label>
            <input type="text" id="address" name="address" required>

            <label for="address">Home</label>
            <input type="text" id="address" name="address" required>

            <label for="address">Email id</label>
            <input type="text" id="address" name="address" required>
            
            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>
