<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Webpage</title>
    <style>
        /* CSS styles for layout, colors, fonts, and spacing */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007acc;
            color: white;
            padding: 20px;
            text-align: center;
        }

        main {
            padding: 40px;
        }

        h1, h2 {
            color: #007acc;
        }

        p {
            line-height: 1.6;
            margin-bottom: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px 0;
        }

        a {
            color: #007acc;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .button-container {
            margin-top: 30px;
        }

        button {
            background-color: #28a745;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #218838;
        }

        footer {
            background-color: #eee;
            text-align: center;
            padding: 20px;
            font-size: 14px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Webpage</h1>
        <p>Explore the beauty of simple web development</p>
    </header>

    <main>
        <h2>About This Page</h2>
        <p>This webpage is built using HTML for content, CSS for styling, and JavaScript for interactivity. It's a simple example showing how the three core web technologies work together.</p>

        <!-- Updated image with actual content -->
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1050&q=80" alt="A scenic mountain landscape with clouds and sunrise">

        <p>Want to learn more? Visit <a href="https://developer.mozilla.org/en-US/" target="_blank">MDN Web Docs</a> for tutorials and references.</p>

        <div class="button-container">
            <button onclick="showAlert()">Click Me!</button>
        </div>
    </main>

    <footer>
        &copy; 2025 My Awesome Webpage. All rights reserved.
    </footer>

    <script>
        // JavaScript function to show alert
        function showAlert() {
            alert("You clicked the button! 🎉");
        }
    </script>

</body>
</html>