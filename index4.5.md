File 1: index.html (Home Page)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | Campus Tech Club</title>
    <meta name="description" content="Welcome to the Campus Tech Club home page. Explore our events, workshops, and coding community.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; background-color: #f8f9fa; color: #333; }
        header { background: #1a365d; color: white; padding: 30px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; }
        nav { background: #2a4365; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover, nav a.active { color: #63b3ed; text-decoration: underline; }
        .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
        section { background: white; padding: 25px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: #1a365d; border-bottom: 2px solid #63b3ed; padding-bottom: 8px; }
        table { width: 100%; border-collapse: collapse; margin-top: 15px; }
        th, td { border: 1px solid #cbd5e0; padding: 10px; text-align: center; }
        th { background-color: #2a4365; color: white; }
        footer { background: #1a365d; color: white; text-align: center; padding: 15px; margin-top: 40px; }
    </style>
</head>
<body>

    <header>
        <h1>Campus Tech Club</h1>
        <p>Innovate, Code, and Build the Future Together</p>
    </header>

    <nav>
        <a href="index.html" class="active">Home</a>
        <a href="about.html">About</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <div class="container">
        <section>
            <h2>Welcome to the Club!</h2>
            <p>The Campus Tech Club is a community of passionate developers, designers, and tech enthusiasts. We host weekly coding workshops, hackathons, and guest speaker sessions to help students build real-world tech skills.</p>
        </section>

        <section>
            <h2>Upcoming Events Schedule</h2>
            <table>
                <caption>Semester Workshop & Event Schedule</caption>
                <thead>
                    <tr>
                        <th>Event Name</th>
                        <th>Date</th>
                        <th>Time</th>
                        <th>Location</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Intro to HTML & CSS</td>
                        <td>Nov 5, 2026</td>
                        <td>4:00 PM - 6:00 PM</td>
                        <td>Lab Room 302</td>
                    </tr>
                    <tr>
                        <td>JavaScript Hackathon</td>
                        <td>Nov 18, 2026</td>
                        <td>10:00 AM - 4:00 PM</td>
                        <td>Main Auditorium</td>
                    </tr>
                    <tr>
                        <td>Web Accessibility Workshop</td>
                        <td>Dec 2, 2026</td>
                        <td>3:00 PM - 5:00 PM</td>
                        <td>Library Hall B</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Campus Tech Club. All rights reserved.</p>
    </footer>

</body>
</html>
File 2: about.html (About Introduction & Members)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us | Campus Tech Club</title>
    <meta name="description" content="Learn more about the Campus Tech Club mission, history, and core leadership team.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; background-color: #f8f9fa; color: #333; }
        header { background: #1a365d; color: white; padding: 30px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; }
        nav { background: #2a4365; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover, nav a.active { color: #63b3ed; text-decoration: underline; }
        .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
        section { background: white; padding: 25px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: #1a365d; border-bottom: 2px solid #63b3ed; padding-bottom: 8px; }
        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }
        footer { background: #1a365d; color: white; text-align: center; padding: 15px; margin-top: 40px; }
    </style>
</head>
<body>

    <header>
        <h1>About Our Club</h1>
        <p>Get to know our mission and leadership team</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html" class="active">About</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <div class="container">
        <section>
            <h2>Our Mission</h2>
            <p>Founded in 2024, the Campus Tech Club bridges the gap between classroom theory and practical software development. We empower students of all majors to build projects, collaborate, and launch successful careers in tech.</p>
        </section>

        <section>
            <h2>Core Leadership Team</h2>
            <ul>
                <li><strong>President:</strong> Alex Morgan (Senior, Computer Science)</li>
                <li><strong>Vice President:</strong> Taylor Swift (Junior, Software Engineering)</li>
                <li><strong>Event Coordinator:</strong> Jordan Lee (Junior, Information Systems)</li>
                <li><strong>Faculty Advisor:</strong> Dr. Alan Turing (Department of Computer Science)</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Campus Tech Club. All rights reserved.</p>
    </footer>

</body>
</html>
File 3: registration.html (Student Registration Form)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration | Campus Tech Club</title>
    <meta name="description" content="Register to join the Campus Tech Club and participate in upcoming workshops and events.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; background-color: #f8f9fa; color: #333; }
        header { background: #1a365d; color: white; padding: 30px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; }
        nav { background: #2a4365; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover, nav a.active { color: #63b3ed; text-decoration: underline; }
        .container { max-width: 600px; margin: 30px auto; padding: 0 20px; }
        .form-box { background: white; padding: 30px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: #1a365d; text-align: center; margin-top: 0; }
        .form-group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; font-weight: bold; }
        input, select, textarea { width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; }
        button { width: 100%; background-color: #2b6cb0; color: white; padding: 12px; border: none; border-radius: 4px; font-size: 16px; font-weight: bold; cursor: pointer; margin-top: 10px; }
        button:hover { background-color: #2c5282; }
        footer { background: #1a365d; color: white; text-align: center; padding: 15px; margin-top: 40px; }
    </style>
</head>
<body>

    <header>
        <h1>Club Registration</h1>
        <p>Join our growing community today!</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="registration.html" class="active">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <div class="container">
        <div class="form-box">
            <h2>Membership Form</h2>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="fullname">Full Name:</label>
                    <input type="text" id="fullname" name="fullname" placeholder="John Doe" required>
                </div>
                <div class="form-group">
                    <label for="email">College Email:</label>
                    <input type="email" id="email" name="email" placeholder="student@college.edu" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required>
                </div>
                <div class="form-group">
                    <label for="year">Academic Year:</label>
                    <select id="year" name="year" required>
                        <option value="">-- Select Year --</option>
                        <option value="freshman">Freshman</option>
                        <option value="sophomore">Sophomore</option>
                        <option value="junior">Junior</option>
                        <option value="senior">Senior</option>
                    </select>
                </div>
                <button type="submit">Register Now</button>
            </form>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Campus Tech Club. All rights reserved.</p>
    </footer>

</body>
</html>
File 4: contact.html (Contact Details)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | Campus Tech Club</title>
    <meta name="description" content="Get in touch with the Campus Tech Club leadership team via email or visit us on campus.">
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; background-color: #f8f9fa; color: #333; }
        header { background: #1a365d; color: white; padding: 30px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; }
        nav { background: #2a4365; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover, nav a.active { color: #63b3ed; text-decoration: underline; }
        .container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
        section { background: white; padding: 25px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        h2 { color: #1a365d; border-bottom: 2px solid #63b3ed; padding-bottom: 8px; }
        p { margin: 10px 0; }
        a.email-link { color: #2b6cb0; text-decoration: none; font-weight: bold; }
        a.email-link:hover { text-decoration: underline; }
        footer { background: #1a365d; color: white; text-align: center; padding: 15px; margin-top: 40px; }
    </style>
</head>
<body>

    <header>
        <h1>Contact Us</h1>
        <p>We would love to hear from you!</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html" class="active">Contact</a>
    </nav>

    <div class="container">
        <section>
            <h2>Get in Touch</h2>
            <p>Have questions about our events, workshops, or club membership? Reach out to us using the details below:</p>
            <p><strong>Email:</strong> <a href="mailto:techclub@college.edu" class="email-link">techclub@college.edu</a></p>
            <p><strong>Location:</strong> Student Union Building, Room 404, Campus Grounds</p>
            <p><strong>Office Hours:</strong> Monday through Friday, 2:00 PM – 5:00 PM</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Campus Tech Club. All rights reserved.</p>
    </footer>

</body>
</html>
Requirements Checklist for Submission:
All Four Files Created: index.html, about.html, registration.html, and contact.html.

Consistent Navigation: Every page includes the same <nav> links (index.html, about.html, registration.html, contact.html).

Home Page: Features club intro, activities, and an events schedule table.

About Page: Contains club mission details and leadership team info.

Registration Page: Includes a fully functional student registration form.

Contact Page: Displays email, campus location, and office hours.

Metadata & Favicon: Includes UTF-8 encoding, viewport scaling, descriptive titles, meta descriptions, and a favicon link on every page.