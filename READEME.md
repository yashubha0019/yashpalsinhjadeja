<!DOCTYPE html>
<html lang="en">

<head>
    <meta name="description" content="Join the Nexora x OneDiplomas Internship Program for real-world experience in Web Development and Digital Marketing. Paid internship with certificate and mentorship.">

<meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Internship Program | Nexora x OneDiplomas</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: #121212;
            color: #f5f5f5;
            line-height: 1.6;
        }

        header {
            background-color: #1c1c1c;
            padding: 2rem 3rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #f5f5f5;
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
        }

        header h1 {
            font-size: 2.5rem;
            font-weight: 700;
        }

        nav a {
            color: #fff;
            margin-left: 2rem;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #007bff;
        }

        section {
            padding: 4rem 2rem;
            max-width: 1100px;
            margin: 0 auto;
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.7s ease;
        }

        section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        h2 {
            font-size: 2.5rem;
            color: #007bff;
            margin-bottom: 1rem;
            text-align: center;
        }

        .about,
        .internship-details,
        .testimonials,
        .contact,
        .apply {
            margin-bottom: 4rem;
        }

        .cta-button {
            display: inline-block;
            padding: 1rem 2rem;
            background-color: #28a745;
            color: white;
            font-weight: 600;
            border-radius: 6px;
            text-decoration: none;
            transition: background 0.3s ease;
            margin-top: 2rem;
        }

        .cta-button:hover {
            background-color: #218838;
        }

        form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.5rem 2rem;
            background-color: #2a2a2a;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        
        form div {
            display: flex;
            flex-direction: column;
        }
        
        form label {
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #ccc;
        }
        
        form input {
            padding: 1rem;
            border: 1px solid #444;
            border-radius: 6px;
            font-size: 1rem;
            background-color: #222;
            color: #fff;
            transition: border-color 0.3s ease;
        }
        
        form input:focus {
            border-color: #007bff;
            outline: none;
        }
        
        form button {
            grid-column: span 2;
            padding: 1rem;
            background-color: #007bff;
            color: white;
            font-weight: 600;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        
        form button:hover {
            background-color: #0056b3;
        }
        
        @media (max-width: 768px) {
            form {
                grid-template-columns: 1fr;
            }
        
            form button {
                grid-column: span 1;
            }
        }
        
        footer {
            background-color: #1c1c1c;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        footer .social-icons a {
            color: white;
            margin: 0 1rem;
            font-size: 2rem;
            transition: color 0.3s ease;
        }

        footer .social-icons a:hover {
            color: #007bff;
        }

        @media (max-width: 1024px) {
            header {
                padding: 1.5rem;
            }

            header h1 {
                font-size: 2rem;
            }

            nav a {
                margin-left: 1rem;
            }

            section {
                padding: 3rem 1rem;
            }

            .cta-button {
                width: 100%;
                padding: 1rem;
                font-size: 1.2rem;
            }

            form {
                padding: 1.5rem;
            }

            form input,
            form textarea {
                font-size: 0.95rem;
            }

            form button {
                padding: 1rem;
                font-size: 1rem;
            }
        }

        @media (max-width: 768px) {
            header {
                padding: 1rem;
            }

            header h1 {
                font-size: 1.5rem;
            }

            nav a {
                margin-left: 0.5rem;
            }

            .cta-button {
                width: 100%;
                padding: 1rem;
                font-size: 1rem;
            }

            form input,
            form textarea {
                font-size: 1rem;
            }

            form button {
                font-size: 1rem;
            }
        }
        .menu-toggle {
            display: none;
            font-size: 1.8rem;
            cursor: pointer;
            color: #fff;
        }
        
        @media (max-width: 768px) {
            nav#navbar {
                position: absolute;
                top: 70px;
                right: 20px;
                background-color: #1c1c1c;
                padding: 1rem;
                border-radius: 8px;
                display: none;
                flex-direction: column;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
            }
        
            nav#navbar a {
                margin: 0.8rem 0;
            }
        
            .menu-toggle {
                display: block;
            }
        
            nav#navbar.show {
                display: flex;
            }
        }
        
    </style>
</head>

<body>

    <header>
        <h1>Nexora x OneDiplomas</h1>
        <nav id="navbar">
          <a href="#about">About</a>
          <a href="#internship">Internship</a>
          <a href="#apply">Apply</a>
          <a href="#contact">Contact</a>
        </nav>
        <div class="menu-toggle" id="menu-toggle">
          <i class="fas fa-ellipsis-v"></i>
        </div>
      </header>
      

    <section id="about" class="about">
        <h2>About Our Collaboration</h2>
        <p>
            <strong>Nexora</strong> is a dynamic creative agency committed to accelerating business growth through modern digital solutions. We specialize in a wide range of services including Web Development, Graphic Design, Branding, and Digital Marketing. Our mission is to help businesses establish a powerful online presence, enhance their brand identity, and reach their target audience effectively.
        </p>
        <br />
        <p>
            <strong>OneDiplomas</strong> is an educational platform dedicated to supporting diploma students with valuable academic resources. We offer access to GTU exam papers, paper solutions, syllabus, and much more — all in one place. OneDiplomas is constantly evolving, with new features and platforms under development to further enhance learning and academic success for students.
        </p>
        <br />
        <p>
            Together, <strong>Nexora</strong> and <strong>OneDiplomas</strong> are proud to launch an internship program that not only offers real-world exposure in digital domains but also empowers students to develop practical skills aligned with industry standards.
        </p>
    </section>
    
    

    <section id="internship" class="internship-details">
        <h2>Internship Details</h2>
        <p>
          At Nexora, we are offering a professional and flexible internship program designed to help students gain real-world experience in the fields of <strong>Web development</strong>, and <strong>Digital Marketing</strong>.
        </p>
        <p>
          The internship duration ranges from a minimum of <strong>15 days</strong> to <strong>1 to 2 months</strong>, depending on your availability and learning goals. 
        </p>
        <p>
          <strong>All students</strong> are welcome to apply, regardless of their academic background or skill level. This is a <strong>paid internship</strong> that includes:
          <ul>
            <li>Official <strong>Joining Letter</strong></li>
            <li>Completion <strong>Certificate</strong></li>
            <li>Personalized <strong>Guidance & Mentorship</strong></li>
            <li>Best-in-class <strong>Practical Learning</strong></li>
          </ul>
        </p>
        <p>
          This is a great opportunity to enhance your skills, gain industry exposure, and build a strong professional foundation for your career.
        </p>
      </section>
      
    <section id="apply" class="apply">
        <h2>Apply for Internship</h2>
        <form action="https://formspree.io/f/xnnddnzb" method="POST">
            <div>
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" placeholder="Your full name" required>
            </div>
            <div>
                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" placeholder="Your email" required>
            </div>
            <div>
                <label for="mobile">Mobile Number</label>
                <input type="tel" id="mobile" name="mobile" placeholder="10-digit mobile number" pattern="[0-9]{10}" required>
            </div>
            <div>
                <label for="branch">Branch</label>
                <input type="text" id="branch" name="branch" placeholder="Your branch (e.g., Computer Engineering)" required>
            </div>
            <div>
                <label for="semester">Semester</label>
                <input type="text" id="semester" name="semester" placeholder="Your semester (e.g., 4th)" required>
            </div>
            <button type="submit"><i class="fas fa-paper-plane"></i> Submit Application</button>

        </form>
    </section>
    
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p><strong>Email:</strong> contact@onediplomas.site</p>
        <p><strong>Phone:</strong> +91-XXXXXXXXXX</p>
    </section>

    <footer>
        <div class="social-icons">
            <a href="https://www.linkedin.com/in/kishan-parmar-126030326" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.github.com" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://www.instagram.com/kishan_parmar_70?igsh=NDEzbWowc3c5aW01" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://www.facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://www.youtube.com" target="_blank"><i class="fab fa-youtube"></i></a>
        </div>
    </footer>

    <script>
        window.addEventListener("scroll", () => {
            document.querySelectorAll("section").forEach(section => {
                if (section.getBoundingClientRect().top < window.innerHeight - 150) {
                    section.classList.add("visible");
                }
            });
        });
    </script>
    <script>
        const sections = document.querySelectorAll('section');
        window.addEventListener('scroll', () => {
          sections.forEach(sec => {
            const top = window.scrollY;
            const offset = sec.offsetTop - 150;
            const height = sec.offsetHeight;
            if (top >= offset && top < offset + height) {
              sec.classList.add('visible');
            }
          });
        });
      </script>
      <script>
        // Hamburger Menu Toggle
        const toggleBtn = document.getElementById("menu-toggle");
        const navbar = document.getElementById("navbar");
    
        toggleBtn.addEventListener("click", () => {
            navbar.classList.toggle("show");
        });
    </script>
    
</body>

</html>
