# yamin103
<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org">
<head>
    <title>Java Contact Form</title>
    <style>
        body { font-family: sans-serif; background: #eef2f3; padding: 50px; text-align: center; }
        .container { background: white; padding: 30px; border-radius: 10px; display: inline-block; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        input, textarea { width: 90%; padding: 10px; margin: 10px 0; border: 1px solid #ddd; }
        button { background: #007bff; color: white; border: none; padding: 10px 20px; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Contact the Java Backend</h1>
        <form action="/submit" method="POST">
            <input type="text" name="name" placeholder="Name" required> <br>
            <textarea name="message" placeholder="Message" required></textarea> <br>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
