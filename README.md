#Personal-Portofolio-Capstone-Project"
Link Capstone Project:
file:///C:/Users/admin/Downloads/Personal%20Portofolio.html

Input prompt IBM Granite Capstone Project:
Create a single-page static website for random personal porotofio (male or female person). 
Generate the code using combination HTML, CSS, and JavaScript with impressive User Interface (UI) and User Experience (UX). 
Ensure it is responsive for screens on mobile and desktop. The page should include name of person; contact of person 
like home address, email address, phone, and social media; birthdate of person with format day, month, and year; education history 
(elementary school, junior high school, senior high school, and university); hardskills; softskills; experience history 
(company name, start-end date work, and key activities); and portofolio projects like data analysis, digital marketing, and/or financial analysis.

Output Prompt IBM Granite Capstone Project:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jane Smith's Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        header {
            text-align: center;
            padding: 20px 0;
            background-color: #333;
            color: white;
        }
        h1 {
            margin: 0;
        }
        .profile-info, .education, .skills, .experience, .portfolio {
            margin-bottom: 30px;
        }
        .profile-info p, .education p, .skills p, .experience p, .portfolio p {
            margin: 5px 0;
        }
        .contact-info {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .contact-info p {
            margin: 0;
        }
        @media (max-width: 768px) {
            .contact-info {
                flex-direction: column;
            }
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jane Smith</h1>
    </header>
    <div class="container">
        <div class="profile-info">
            <h2>Personal Information</h2>
            <p><strong>Name:</strong> Jane Smith</p>
            <p><strong>Birthdate:</strong> 15 March, 1985</p>
            <p><strong>Contact:</strong></p>
            <div class="contact-info">
                <p><i class="fab fa-home"></i> 456 Oak Ave, Somecity, USA</p>
                <p><i class="far fa-envelope"></i> jane.smith@example.com</p>
                <p><i class="fas fa-phone"></i> +1 (234) 567-8901</p>
                <p><i class="fab fa-facebook-square"></i><a href="#">facebook.com/janesmith</a></p>
                <p><i class="fab fa-linkedin-in"></i><a href="#">linkedin.com/in/janesmith</a></p>
            </div>
        </div>
        <div class="education">
            <h2>Education</h2>
            <p><strong>Elementary School:</strong> Some Elementary School, Somecity, USA (1991-1996)</p>
            <p><strong>Junior High School:</strong> Some Junior High School, Somecity, USA (1996-2001)</p>
            <p><strong>Senior High School:</strong> Some Senior High School, Somecity, USA (2001-2005)</p>
            <p><strong>University:</strong> Some University, Somecity, USA (2005-2009) <i class="fas fa-graduation-cap"></i> Bachelor of Arts in Computer Science</p>
        </div>
        <div class="skills">
            <h2>Skills</h2>
            <h3>Hard Skills</h3>
            <ul>
                <li>Data Analysis (Python, R, SQL)</li>
                <li>Digital Marketing (SEO, SEM, Social Media)</li>
                <li>Financial Analysis (Excel, Tableau)</li>
                <li>Web Development (HTML, CSS, JavaScript, React)</li>
            </ul>
            <h3>Soft Skills</h3>
            <ul>
                <li>Problem Solving</li>
                <li>Communication</li>
                <li>Teamwork</li>
                <li>Time Management</li>
            </ul>
        </div>
        <div class="experience">
            <h2>Experience</h2>
            <p><strong>Senior Software Engineer</strong> at TechSolutions, Somecity, USA</p>
            <p>June 2015 - Present</p>
            <ul>
                <li>Led a team of developers in building scalable web applications</li>
                <li>Implemented data visualization tools using D3.js and Tableau</li>
                <li>Optimized application performance and reduced load times by 50%</li>
            </ul>
            <p><strong>Junior Data Analyst</strong> at DataInsights, Somecity, USA</p>
            <p>January 2013 - May 2015</p>
            <ul>
                <li>Analyzed large datasets to identify trends and patterns</li>
                <li>Created interactive dashboards using Tableau and PowerBI</li>
                <li>Collaborated with stakeholders to provide actionable insights</li>
            </ul>
        </div>
        <div class="portfolio">
            <h2>Portfolio</h2>
            <p><strong>Data Analysis Project:</strong> Customer Churn Prediction for XYZ Corp</p>
            <p>Utilized Python and its libraries (pandas, numpy, matplotlib, scikit-learn) to analyze customer data and predict churn. Improved prediction accuracy by 20%.</p>
            <p><strong>Digital Marketing Project:</strong> SEO Campaign for ABC Inc</p>
            <p>Optimized website content and structure, implemented keyword research, and managed backlink strategies. Increased organic traffic by 40% within nine months.</p>
            <p><strong>Financial Analysis Project:</strong> Stock Market Prediction Model</p>
            <p>Developed a predictive model using historical stock data and machine learning algorithms (LSTM, ARIMA). Achieved 90% accuracy in predicting stock price movements.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Jane Smith</p>
    </footer>
</body>
</html>

</htm
