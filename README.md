# index.html# 
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section>
            <h2>About This Page</h2>
            <p>This is a simple HTML page created using Python.</p>
        </section>
    </main>
    
    <footer>
        <p>Contact me at <a href="mailto:example@example.com">example@example.com</a></p>
    </footer>
</body>
</html>
"""

# Write the HTML content to a file
with open("index.html", "w") as file:
    file.write(html_content)

print("index.html file has been created successfully.")
