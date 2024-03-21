
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Registration Form</title>
<style>
    label {
        display: block;
        margin-bottom: 5px;
    }
    input[type="text"], input[type="date"], select {
        width: 100%;
        padding: 8px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
    }
    input[type="radio"] {
        margin-right: 5px;
    }
    button {
        padding: 10px 20px;
        border: none;
        border-radius: 4px;
        background-color: #4CAF50;
        color: white;
        cursor: pointer;
    }
    button.cancel {
        background-color: #f44336;
    }
</style>
</head>
<body>

<h2>Student Registration Form</h2>

<form action="#" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>

    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="male" required>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female" required>
    <label for="female">Female</label>
    <input type="radio" id="other" name="gender" value="other" required>
    <label for="other">Other</label>

    <label for="address">Address:</label>
    <input type="text" id="address" name="address" required>

    <label for="telephone">Telephone:</label>
    <input type="tel" id="telephone" name="telephone" required>

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" required>

    <label for="course">Course:</label>
    <select id="course" name="course" required>
        <option value="">Select a course</option>
        <option value="Computer Science">Computer Science</option>
        <option value="Engineering">Engineering</option>
        <option value="Business">Business</option>
        <option value="Arts">Arts</option>
    </select>

    <button type="submit">Register</button>
    <button type="button" class="cancel">Cancel</button>
</form>

</body>
</html>
