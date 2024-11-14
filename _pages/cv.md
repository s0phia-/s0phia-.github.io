---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
---



<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
          @keyframes rainbow {
        0% { color: linear-gradient(to right, #ff0000, #ff4000); }
        8.33% { color: #ff4000; }
        16.67% { color: #ff8000; }
        25% { color: #ffbf00; }
        33.33% { color: #ffff00; }
        41.67% { color: #bfff00; }
        50% { color: #80ff00; }
        58.33% { color: #40ff00; }
        66.67% { color: #00ff00; }
        75% { color: #00ff40; }
        83.33% { color: #00ff80; }
        91.67% { color: #00ffbf; }
        100% { color: linear-gradient(to right, #00ffff, #ff0000); }
      }

      #rainbow-link {
        text-decoration: none;
        animation: rainbow 3s linear infinite;
      }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        h1 {
            margin-bottom: 0px; /* Reduced bottom margin to bring "PhD Candidate" up */
            padding-bottom: 5px; /* Reduced padding to decrease the space below the heading */
        }
        h2 {
            margin-top: 10px; /* Reduced top margin to bring "Education" closer to content above */
            border-top: 2px solid #2c3e50; /* Added border-top for the Education section */
            padding-top: 5px; /* Reduced padding to decrease space between text and border */
        }
        h3 {
            margin-top: 10px; /* Adjusted margin for h3 elements */
        }
        ul {
            padding-left: 20px;
        }
        .contact-info {
            margin-bottom: 10px; /* Reduced margin to bring symbols closer to the text */
            display: flex;
            justify-content: center; /* Centered the icons for better alignment */
        }
        .contact-info a {
            color: #3498db;
            text-decoration: none;
            font-size: 1.5em;
            margin: 0 10px; /* Reduced horizontal margin to decrease space around symbols */
        }
        .contact-info a:hover {
            color: #2980b9;
        }
        .date {
            font-style: italic;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

Please find a PDF version of my CV <a href="https://s0phia-.github.io/assets/pdf/CV.pdf" id="rainbow-link">here</a>.

<br><br><br>


    <h2>Education</h2>
    <h3>PhD in Reinforcement Learning </h3>
    <p><strong>University of Bath</strong> <span class="date">Sept 2021 - Present</span></p>
    <ul>
        <li>Researching reinforcement learning with graph based methods in the UKRI CDT for Accountable, Responsible, and Transparent AI, under the supervision of Prof Özgür Şimşek.</li>
        <li>My research deconstructs reinforcement learning policies, which are strategies that guide how an agent takes actions to achieve a goal. The policies are deconstructed into subtasks, for example a policy for making tea might be decomposed into the steps: boil water; place a teabag in a cup; pour water over the teabag. My research has two aims: the first is to deconstruct existing policies into subtasks to provide an explanation of how the overall policy will behave, and the second is to extract useful subtasks that might be transferred to new tasks.</li>
        <li>Achieved 75% in the integrated MRes year.</li>
        <li>Organise and host a popular reading group for the AI and ML department.</li>
    </ul>

    <h3>MSc Computer Science (Distinction, 75%)</h3>
    <p><strong>University of Edinburgh</strong> <span class="date">Sept 2017 - Sept 2018</span></p>
    <ul>
        <li>Studied modules relating to AI and theoretical computer science.</li>
        <li>Dissertation judged outstanding. Contributed novel research in the field of randomised algorithms on graphs. Available online <a href="https://project-archive.inf.ed.ac.uk/msc/20183073/msc_proj.pdf">here</a>.</li>
    </ul>

    <h3>MSc Mathematics (Merit, 67%)</h3>
    <p><strong>University of Leeds</strong> <span class="date">Sept 2015 - Sept 2016</span></p>
    <ul>
        <li>Studied courses in pure mathematics and statistics.</li>
    </ul>

    <h3>BSc Mathematics with Finance (First Class, 75%)</h3>
    <p><strong>University of Brighton</strong> <span class="date">Sept 2012 - July 2015</span></p>
    <ul>
        <li>Won the Deb Bose Prize for Best Mathematical Dissertation.</li>
        <li>Elected representative for students on my course.</li>
    </ul>
    
    <h2>Work Experience</h2>
    <h3>Senior Operations Research Scientist</h3>
    <p><strong>Wayfair, Berlin</strong> <span class="date">May 2019 - Aug 2021</span></p>
    <p>Selected projects:</p>
    <ul>
        <li>Created a forecasting system to estimate the optimal delivery fleet size, achieving over 90% accuracy. Development included interviewing stakeholders, feature engineering, and modelling on a small dataset.</li>
        <li>My team and I developed a novel algorithm using routing heuristics to find geographically optimal locations for delivery hubs.</li>
    </ul>

    <h3>Credit Risk Analyst</h3>
    <p><strong>Lloyds Banking Group, Leeds</strong> <span class="date">April - Sept 2017</span></p>
    <p>Developed models to predict the total loss the bank may incur due to customers defaulting on mortgage payments.</p>

    <h3>Explainable AI consultant</h3>
    <p><strong>Simply Rational, Berlin</strong> <span class="date">August 2023</span></p>
    <p>Consulted on an explainable credit risk prediction project.</p>

    <h2>Teaching Experience</h2>
    <h3>Tutoring</h3>
    <ul>
        <li>Mathematics for Computation (University of Bath)</li>
        <li>Cryptography (University of Bath)</li>
        <li>Discrete Mathematics and Mathematical Reasoning (University of Edinburgh)</li>
    </ul>

    <h3>Course co-leader</h3>
    <ul>
        <li>R Programming for Analytics (Wayfair)</li>
    </ul>

    <h3>Volunteer Instructor</h3>
    <ul>
        <li>Data Science with Python (Code Your Dreams)</li>
    </ul>

    <h3>MSc Supervision</h3>
    <ul>
        <li>Comparison of Handcrafted and Autonomously Learned Hierarchical Reinforcement Learning Agents in Tetris (University of Bath)</li>
        <li>Using Curriculum Learning Techniques with Deep Reinforcement Learning in Tetris (University of Bath)</li>
        <li>Reinforcement Learning for Tetris using Options (University of Bath)</li>
    </ul>

    <h2>Awards</h2>
    <ul>
        <li>Deb Bose Prize for Best Mathematical Dissertation (2015)</li>
    </ul>

    <h2>Skills</h2>
    <ul>
        <li><strong>Regular Use:</strong> Python, PyTorch, NumPy, Matplotlib, LaTeX</li>
        <li><strong>Past professional use:</strong> Python, R</li>
        <li><strong>University Modules:</strong> MATLAB, Java, ROS</li>
    </ul>
</body>
