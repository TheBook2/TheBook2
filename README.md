/* General reset and body style */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #1a1a1a;
    line-height: 1.6;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #004080;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 2em;
}

/* Navigation Styles */
nav {
    background-color: #0066cc;
    display: flex;
    justify-content: center;
    gap: 15px;
    padding: 10px 0;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover, nav a:focus {
    color: #ffd700;
    text-decoration: underline;
    outline: 2px dashed #ffd700;
}

/* Main content layout */
.main-content {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
}

/* Section styling */
section {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Headings */
h2 {
    color: #003366;
    margin-bottom: 10px;
}

/* Paragraphs */
p {
    margin-bottom: 10px;
    font-size: 1rem;
}

/* Buttons */
button {
    background-color: #005bb5;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 6px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #004a99;
}

/* Footer */
footer {
    text-align: center;
    margin-top: 40px;
    font-size: 0.9rem;
    color: #666;
}

/* Images */
img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

/* Links */
a {
    color: #0055aa;
}

a:hover, a:focus {
    color: #ff5500;
    outline: 2px dashed #ff5500;
}
