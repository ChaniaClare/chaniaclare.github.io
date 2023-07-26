<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chania Clare</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: "Arial", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #2c3e50; /* Dark Blue */
            color: #fff;
            padding: 2rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }

        /* Social Media Links */
        .social-links {
            margin-top: 1rem;
        }

        .social-links a {
            display: inline-block;
            margin-right: 1rem;
            color: #fff;
            font-size: 1.5rem;
            text-decoration: none;
        }

        .social-links a:hover {
            color: #3498db; /* Light Blue */
        }

        nav {
            background-color: #3498db; /* Light Blue */
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }

        /* ... (Responsive Design and Smooth Transitions styles remain the same) ... */

       @media screen and (max-width: 768px) {
            header {
                padding: 1rem;
            }

            header h1 {
                font-size: 2rem;
            }

            header p {
                font-size: 1rem;
            }

            .profile-pic {
                width: 150px;
                height: 150px;
            }
        }

        /* Smooth Transitions */
        body {
            transition: background-color 0.3s ease;
        }

        header {
            transition: background-color 0.3s ease, padding 0.3s ease;
        }

        .social-links a {
            transition: color 0.3s ease;
        }

        nav {
            transition: background-color 0.3s ease;
        }

        /* Hover Effect */
        .social-links a:hover {
            color: #3498db; /* Light Blue */
        }
        /* ... (Additional styles can be added as needed) ... */
    </style>
</head>
<body>
    <header>
        <img class="profile-pic" src="Chania Clare - Photo.jpg" alt="Chania Clare">
        <h1>Chania Clare</h1>
        <p>PhD Student | Computational Systems and Synthetic Biology</p>
        <!-- Social Media Links -->
        <div class="social-links">
            <a href="https://www.linkedin.com/in/chania-clare/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/ChaniaClare" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://twitter.com/ChaniaNClare" target="_blank"><i class="fab fa-twitter"></i></a>
    </header>

    <!-- Main Content Section -->
    <section>
        <h2>About Me</h2>
        <p>
            Your brief and engaging introduction. Share your passion for your field of study and what drives you as a grad student.
        </p>

        <h2>Education and Research</h2>
        <p>
            Provide details about your educational journey, current program, and institution. Highlight your research areas, projects, and publications.
        </p>

        <h2>Projects Showcase</h2>
        <p>
            Showcase your research projects, academic works, and personal projects with descriptions, images, and links.
        </p>

        <h2>Skills and Expertise</h2>
        <ul>
            <li>Technical Skill 1</li>
            <li>Technical Skill 2</li>
            <!-- Add more skills as needed -->
        </ul>

        <h2>Publications and Research Output</h2>
        <ul>
            <li>Publication 1</li>
            <li>Publication 2</li>
            <!-- Add more publications as needed -->
        </ul>

        <!-- Add more sections and content as needed -->

        <!-- Latest Twitter Posts Widget -->
        <div class="twitter-widget">
            <!-- Tweets will be dynamically added here -->
        </div>

        <!-- Latest LinkedIn Posts Widget -->
        <div class="linkedin-widget">
            <!-- Posts will be dynamically added here -->
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>

    <!-- JavaScript for fetching and displaying Twitter posts -->
    <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    <script>
        window.addEventListener("load", function() {
            // Replace "your-twitter-username" with your actual Twitter username
            twttr.widgets.createTimeline(
                {
                    sourceType: "profile",
                    screenName: "ChaniaNClare"
                },
                document.querySelector(".twitter-widget")
            );
        });
    </script>

  
   
</body>
</html>
