<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E2 Computer Lab Exercises</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fffbea;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header, nav {
            text-align: center;
            padding: 10px;
            background-color: #fffbcc;
        }
        header h1, header h2 {
            margin: 5px 0;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #007acc;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .center {
            text-align: center;
        }
        .button {
            margin: 10px 0;
            padding: 10px 15px;
            background-color: #f4d35e;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .button:hover {
            background-color: #f4c145;
        }
        .form-control {
            margin: 10px 0;
            display: block;
        }
        .form-control label {
            display: block;
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <!-- Main Page -->
    <header>
        <h1>E2 COMPUTER</h1>
        <h2>LAB EXERCISES</h2>
        <p><strong>Name:</strong> Ella, Cristine Mae</p>
        <p><strong>Year and Section:</strong> 2 - India</p>
        <audio controls>
            <source src="audio/sample.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </header>
    <nav>
        <a href="autobiography.html">The Autobiography</a>
        <a href="article.html">The Article</a>
        <a href="blog.html">The Blog</a>
        <a href="form.html">The Form</a>
    </nav>
    <!-- Autobiography Page -->
    <div class="container">
        <h2 class="center">AUTOBIOGRAPHY</h2>
        <img src="images/autobiography.jpg" alt="Cristine Mae Ella" style="display: block; margin: 0 auto; width: 200px; border-radius: 10px;">
        <p>
            Cristine Mae Gubaya Ella was born on February 24, 2004, lives in San Pascual Bacon District Sorsogon City...
            <!-- Content Continues -->
        </p>
    </div>
    <!-- Article Page -->
    <div class="container">
        <h2 class="center">ARTICLE</h2>
        <iframe width="560" height="315" src="https://youtube.com/embed/Uk1pq8sb-eo" 
            title="YouTube video player" frameborder="0" allowfullscreen style="display: block; margin: 0 auto;"></iframe>
        <p>
            # Definition and Types<br>
            Plagiarism involves passing off someone else's work...
            <!-- Content Continues -->
        </p>
    </div>
    <!-- Blog Page -->
    <div class="container">
        <h2 class="center">BLOG</h2>
        <iframe width="560" height="315" src="https://youtube.com/embed/n8mbzU0X2nQ" 
            title="YouTube video player" frameborder="0" allowfullscreen style="display: block; margin: 0 auto;"></iframe>
        <p>
            # Understanding Cyber Threats: Viruses, Malware, Spam, and Antiviruses<br>
            In today's digital age...
            <!-- Content Continues -->
        </p>
    </div>
    <!-- Form Page -->
    <div class="container">
        <h2 class="center">Form</h2>
        <form>
            <div class="form-control">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
            </div>
            <div class="form-control">
                <label>Year Level:</label>
                <input type="radio" id="1st" name="year" value="1st">
                <label for="1st">1st</label>
                <input type="radio" id="2nd" name="year" value="2nd">
                <label for="2nd">2nd</label>
            </div>
            <div class="form-control">
                <label for="subjects">Favorite Subject:</label>
                <select id="subjects" name="subjects">
                    <option>Mathematics</option>
                    <option>English</option>
                    <option>Science</option>
                    <option>History</option>
                </select>
            </div>
            <div class="form-control">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password">
            </div>
            <div class="form-control">
                <label>Interests:</label>
                <input type="checkbox" id="movies" name="interest" value="Movies">
                <label for="movies">Movies</label>
                <input type="checkbox" id="sports" name="interest" value="Sports">
                <label for="sports">Sports</label>
            </div>
            <button type="submit" class="button">Submit</button>
        </form>
    </div>
</body>
</html>
