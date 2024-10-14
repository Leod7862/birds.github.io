<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced Bird Characteristics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f0f8ff;
        }
        .content {
            display: none;
            margin-top: 10px;
        }
        button {
            margin-top: 10px;
            padding: 10px;
            border: none;
            background-color: #007bb3;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background-color: #005f8a;
        }
    </style>
</head>
<body>
    <h1>Advanced Bird Characteristics</h1>
    <button onclick="document.getElementById('characteristic1').style.display='block'">Show Characteristic 1</button>
    <div id="characteristic1" class="content">
        <h2>1. Avian Intelligence</h2>
        <p>Many bird species, like crows and parrots, are known for their remarkable intelligence. They use tools, solve complex problems, and even recognize themselves in mirrors.</p>
    </div>
    <button onclick="document.getElementById('characteristic2').style.display='block'">Show Characteristic 2</button>
    <div id="characteristic2" class="content">
        <h2>2. Specialized Vision</h2>
        <p>Birds possess some of the most advanced visual systems in the animal kingdom. Many have ultraviolet vision, enabling them to see patterns and details invisible to humans.</p>
    </div>
    <button onclick="document.getElementById('characteristic3').style.display='block'">Show Characteristic 3</button>
    <div id="characteristic3" class="content">
        <h2>3. Navigation Skills</h2>
        <p>Migratory birds have incredible navigation skills, often using the Earth's magnetic field, sun, and stars to travel thousands of miles with astonishing accuracy.</p>
    </div>
</body>
