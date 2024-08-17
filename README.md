<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #e0e0e0;
        }

        .form-wrapper {
            background-color: rgb(100, 229, 240);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        label {
            font-size: 14px;
            font-weight: bold;
        }

        input[type="text"] {
            padding: 10px;
            border: 1px solid #5722d3;
            border-radius: 5px;
        }

        button {
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            background-color: #b91450;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="form-wrapper">
        <form action="#" method="post">
            <label for="input-field">Name:</label>
            <input type="text" id="input-field" name="input-field" required>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>


