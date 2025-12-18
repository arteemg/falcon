# falcon.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Site</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            background: white;
            padding: 60px 40px;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 600px;
            text-align: center;
            animation: fadeIn 0.8s ease-in;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #667eea;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.1em;
            color: #666;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px 40px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
        }

        .button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(102, 126, 234, 0.6);
        }

        .features {
            margin-top: 40px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .feature {
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .feature:hover {
            transform: scale(1.05);
        }

        .feature h3 {
            color: #667eea;
            margin-bottom: 10px;
        }

        .emoji {
            font-size: 2em;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Site</h1>
        <p>This is a simple, modern website hosted on GitHub Pages. Feel free to customize it to make it your own!</p>
        
        <a href="#" class="button" onclick="showMessage(); return false;">Click Me!</a>
        
        <div class="features">
            <div class="feature">
                <div class="emoji">🚀</div>
                <h3>Fast</h3>
                <p>Lightning quick load times</p>
            </div>
            <div class="feature">
                <div class="emoji">🎨</div>
                <h3>Beautiful</h3>
                <p>Clean, modern design</p>
            </div>
            <div class="feature">
                <div class="emoji">📱</div>
                <h3>Responsive</h3>
                <p>Works on all devices</p>
            </div>
        </div>
    </div>

    <script>
        function showMessage() {
            alert('Hello! 👋 You can customize this button to do anything you want.');
        }

        // Add a simple animation when the page loads
        document.addEventListener('DOMContentLoaded', function() {
            console.log('Welcome to your GitHub Pages site!');
        });
    </script>
</body>
</html>
