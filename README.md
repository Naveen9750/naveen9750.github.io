# naveen9750.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simple Aesthetic Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Segoe UI", Tahoma, sans-serif;
        }

        body {
            height: 100vh;
            background: linear-gradient(135deg, #c3ecf7, #f5d3f7);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .card {
            background: white;
            padding: 30px 40px;
            border-radius: 16px;
            width: 320px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        h1 {
            font-size: 24px;
            color: #333;
            margin-bottom: 10px;
        }

        p {
            font-size: 14px;
            color: #666;
            margin-bottom: 20px;
        }

        button {
            background: #6c63ff;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 25px;
            cursor: pointer;
            font-size: 14px;
            transition: background 0.3s ease;
        }

        button:hover {
            background: #554ee0;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>Hello ✨</h1>
        <p>This is a simple aesthetic HTML & CSS page.</p>
        <button>Get Started</button>
    </div>

</body>
</html>
