* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f7f6;
    padding-top: 80px; 
}


header {
    background-color: #004a99; 
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 15px 0;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 20px;
    margin: 0 10px;
    border-radius: 5px;
    transition: background 0.3s ease;
    
}

nav a:hover {
    background-color: #003366;
    color: #ffcc00; 
}


h1 {
    text-align: center;
    color: #004a99;
    margin: 40px 0 20px;
    font-size: 2.5rem;
}

p {
    max-width: 800px;
    margin: 0 auto 30px;
    padding: 0 20px;
    text-align: center;
    font-size: 1.1rem;
}

h2 {
    text-align: center;
    margin-top: 50px;
    color: #444;
}


.btn-container {
    text-align: center;
    margin-top: 20px;
    padding-bottom: 50px;
}

a[href^="https://www.gov.uk"] {
    display: inline-block;
    background-color: #008250; 
    color: white;
    padding: 15px 25px;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 3px;
    border-bottom: 3px solid #005a37;
    transition: transform 0.2s;
    
}

a[href^="https://www.gov.uk"]:hover {
    background-color: #005a37;
    transform: translateY(-2px);
}
