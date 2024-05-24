# Registration-Form
Create a user registration form with the following fields: username, email, password, birthdate, address, and phone number. It should also have a submit and cancel button. Make sure each field has the appropriate input type.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .registration-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .registration-form h2 {
            margin-bottom: 20px;
        }
        .registration-form .form-group {
            margin-bottom: 15px;
        }
        .registration-form .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .registration-form .form-group input {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .registration-form .form-actions {
            display: flex;
            justify-content: space-between;
        }
        .registration-form .form-actions button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .registration-form .form-actions .submit-btn {
            background-color: #28a745;
            color: #fff;
        }
        .registration-form .form-actions .cancel-btn {
            background-color: #dc3545;
            color: #fff;
        }
    </style>
</head>
<body>

<div class="registration-form">
    <h2>Register</h2>
    <form action="#" method="POST">
        <div class="form-group">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
        </div>
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </div>
        <div class="form-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
        </div>
        <div class="form-group">
            <label for="birthdate">Birthdate:</label>
            <input type="date" id="birthdate" name="birthdate" required>
        </div>
        <div class="form-group">
            <label for="address">Address:</label>
            <input type="text" id="address" name="address" required>
        </div>
        <div class="form-group">
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>
        </div>
        <div class="form-actions">
            <button type="submit" class="submit-btn">Submit</button>
            <button type="button" class="cancel-btn" onclick="window.location.href='index.html'">Cancel</button>
        </div>
    </form>
</div>

</body>
</html>
