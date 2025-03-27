# my-personal-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gen Weseman</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #d8c292;
            color: #3e2723;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #3e2723;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #f8e1b4;
            border-bottom: 2px solid #3e2723;
        }
        nav a {
            padding: 14px 20px;
            display: block;
            color: #3e2723;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #d8c292;
        }
        .container {
            padding: 20px;
        }
        h1, h2, h3 {
            font-family: 'Goudy Old Style', serif;
        }
        .about, .portfolio, .contact {
            margin: 20px 0;
            padding: 20px;
            background-color: #ffffff;
            border: 2px solid #3e2723;
            border-radius: 8px;
        }
        footer {
            background-color: #d8c292;
            color: #3e2723;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Genevieve Weseman</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Gen Weseman is a data analyst with a decade of experience leveraging statistical methods and data visualization tools (R, Power BI, GIS, Excel) to extract actionable insights. Skilled in identifying trends and translating complex data into strategic recommendations for public health and policy initiatives. She is passionate about educating individuals on emerging public health matters and advocates for tick-borne disease awareness and policy in her free time. She earned her MPH in Epidemiology & Biosecurity at St Louis University in 2014. Before she arrived at the St. Charles County Department of Public Health, Ms. Weseman served as the public health emergency preparedness program coordinator for the Missouri Department of Health and Senior Services and as an emergency planner and surveillance specialist for the Lincoln County Health Department.</p>
        </section>
        <section id="portfolio" class="portfolio">
            <h2>Portfolio</h2>
            <p>Here you can showcase your work, projects, and contributions. You can include images, links, and descriptions of your work here.</p>
        </section>
        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out to me at:</p>
            <p>Email: GenWeseman@gmail.com</p>
            <p>Phone: (636) 866-1078</p>
            
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Genevieve Weseman</p>
    </footer>
</body>
</html>
