# my-demo
My first project attempt.
DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Student Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: whitesmoke;
            border:red;
            border-radius: 8px;
        }<!
        .container {
            width: 400px;
            margin: 40px auto;
            background-color:whitesmoke;
            padding: 20px ;
            border: gray;
            border-radius: 5px;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-top: 10px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        select,
        textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #aaa;
            border-radius: 4px;
        }
            textarea { height: 80px;
            resize: vertical;
        }

        .options {
            margin-top: 5px;
        }

        .options input {
            margin-right: 5px;
        }

        button {
            margin-top: 20px;
            width: 100%;
            padding: 10px;
            background-color: lightslategray;
            color: white;
            border-radius: 4px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Student Registration Form</h2>

        <form>
            <label for="name">Full Name</label>
            <input type="text" id="name" placeholder="Enter your name">

            <label for="email">Email Address</label>
            <input type="email" id="email" placeholder="Enter your email">
            <label for="course">Course</label>
            <select id="course" name="course">
                <option value="">Select course</option>
                <option>BCA</option>
                <option>BSc</option>
                <option>BTech</option>
                <option>MCA</option>
            </select>
            <label>Gender</label>
            <div class="options">
                <input type="radio"> Male
                <input type="radio" > Female
                <input type="radio" > Other
            </div>
            <label>Interests</label>
            <div class="options">
                <input type="checkbox"> Sports
                <input type="checkbox"> Music
                <input type="checkbox"> Coding
            </div>
            <label for="comments">Comments</label>
            <textarea id="comments" placeholder="Enter your comments"></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>

</body>
</html>
