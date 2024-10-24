# JY-portfolio
# Python script to create a portfolio page in HTML

html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Park Jooyeon - Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 20px; background-color: #f4f4f4; }
        .container { max-width: 800px; margin: auto; background: #fff; padding: 20px; border-radius: 8px; }
        h1, h2 { color: #333; }
        h1 { font-size: 2em; }
        h2 { font-size: 1.5em; margin-top: 20px; }
        p, ul { color: #555; }
        ul { list-style-type: none; padding: 0; }
        li { margin-bottom: 10px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Park Jooyeon</h1>
        <p>Email: jooyeon.park@u.nus.edu | Phone: +65 8044 3091 | <a href="https://www.linkedin.com">LinkedIn</a></p>
        
        <h2>Education</h2>
        <ul>
            <li><strong>National University of Singapore (NUS)</strong> - Bachelor of Business Administration, Honors (Aug 2020 – May 2025)</li>
            <li>Current CAP: 4.54/5.0, Specialization in Marketing and Business Economics, Minor in Chinese Language, Dean’s List AY2023/2024</li>
            <li><strong>Beijing World Youth Academy (BWYA)</strong> - International Baccalaureate Diploma Programme (Aug 2016 – May 2020)</li>
            <li>Scored 44/45, Scholarship Award 2019, Student Council Secretary 2019</li>
        </ul>

        <h2>Experience</h2>
        <ul>
            <li><strong>Edelman</strong> - Communications Consulting Intern (Jan 2024 – Jun 2024)</li>
            <li>Performed media monitoring and optimized social media strategies, increasing followers and engagement by 34% and 47% respectively.</li>
            <li><strong>Trinity Event Pte. Ltd.</strong> - Project Management & Strategy Intern (Nov 2022 – Feb 2023)</li>
            <li>Facilitated communication for a luxury brand’s marketing team and VIPs during an expo in Seoul.</li>
            <li><strong>Sinomune Pharmaceutical Co. Ltd</strong> - Product Strategy & Marketing Intern (Apr 2022 – Jun 2022)</li>
            <li>Executed a marketing campaign, achieving outreach of 1.3 million individuals and a clickthrough rate of 12.7%.</li>
            <li><strong>China CITIC Bank</strong> - Private Banking Sales Intern (Jul 2019 – Aug 2019)</li>
            <li>Boosted customer turnout rate by 23% through communication enhancements.</li>
        </ul>

        <h2>Achievements & Activities</h2>
        <ul>
            <li><strong>NUS Dayspring</strong> - Tutor and Befriender (Sep 2023 – Present)</li>
            <li><strong>Future Business Leaders of America</strong> - 2nd place in national round (Dec 2018 – May 2020)</li>
            <li><strong>Walkathon</strong> - Organizer and Leader (Aug 2017 – Nov 2018)</li>
            <li>Led 60 volunteers, raising 4500 RMB for a rural school in Shaanxi, China.</li>
        </ul>

        <h2>Skills</h2>
        <ul>
            <li>Languages: Korean (Native), English (Native), Mandarin (Conversant)</li>
            <li>Technical Skills: Power BI, Python, R, SPSS, Tableau, MS Office, Figma</li>
        </ul>

        <h2>Interests</h2>
        <ul>
            <li>Data Analysis and Visualization, AI, Econometrics</li>
            <li>Sustainable fashion and beauty, Children rights</li>
        </ul>
    </div>
</body>
</html>
"""

# Save the HTML content to a file
with open("portfolio.html", "w") as file:
    file.write(html_content)

print("Portfolio page created successfully. Upload 'portfolio.html' to your GitHub repository.")

