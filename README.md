<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAJNARAYAN - Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #1a1a1a, #333);
            color: white;
            text-align: center;
            padding: 3rem 2rem;
            position: relative;
            overflow: hidden;
        }
        
        header::after {
            content: '';
            position: absolute;
            bottom: -50px;
            left: 0;
            right: 0;
            height: 100px;
            background: #f5f5f5;
            transform: skewY(-2deg);
            z-index: 1;
        }
        
        section {
            padding: 2.5rem;
            max-width: 800px;
            margin: -30px auto 2rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            position: relative;
            z-index: 2;
        }
        
        img {
            display: block;
            margin: 0 auto 1.5rem;
            border-radius: 50%;
            width: 180px;
            height: 180px;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            color: white;
        }
        
        h2 {
            color: #1a1a1a;
            margin-bottom: 1.5rem;
            position: relative;
            display: inline-block;
        }
        
        h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background: #0073e6;
        }
        
        .tagline {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 1rem;
            color: #ddd;
        }
        
        .about, .skills, .contact {
            margin-bottom: 2.5rem;
        }
        
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-top: 1.5rem;
        }
        
        .skill {
            background: #f0f8ff;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: 500;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        
        .contact-info {
            font-size: 1.1rem;
            margin: 1.5rem 0;
        }
        
        .social {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 1.5rem;
        }
        
        .social a {
            color: #1a1a1a;
            text-decoration: none;
            font-size: 1.2rem;
            transition: all 0.3s ease;
            padding: 10px;
        }
        
        .social a:hover {
            color: #0073e6;
            transform: translateY(-3px);
        }
        
        .social-icon {
            width: 24px;
            height: 24px;
            vertical-align: middle;
            margin-right: 5px;
        }
        
        @media (max-width: 600px) {
            section {
                padding: 1.5rem;
                margin: -20px auto 1.5rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            img {
                width: 140px;
                height: 140px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>RAJNARAYAN</h1>
        <p class="tagline">Social Influencer | Video Editor | Content Creator</p>
    </header>
    
    <section>
        <img src="https://via.placeholder.com/150" alt="Rajnarayan's Profile Picture" id="profile-pic">
        
        <div class="about">
            <h2>About Me</h2>
            <p>I'm Rajnarayan, a passionate content creator and social influencer. With skills in video editing, photo editing, and storytelling, I aim to entertain, inspire, and connect with people through powerful content. My mission is to keep evolving creatively while staying true to my roots.</p>
        </div>
        
        <div class="skills">
            <h2>Skills</h2>
            <div class="skills-list">
                <div class="skill">✔️ Video Editing</div>
                <div class="skill">✔️ Photo Editing</div>
                <div class="skill">✔️ Content Creation</div>
                <div class="skill">✔️ Social Media Influencing</div>
                <div class="skill">✔️ Storytelling</div>
                <div class="skill">✔️ Digital Marketing</div>
            </div>
        </div>
        
        <div class="contact">
            <h2>Contact</h2>
            <div class="contact-info">
                Email: <a href="mailto:rajnarayan233232@gmail.com">rajnarayan233232@gmail.com</a>
            </div>
            
            <h2>Follow Me</h2>
            <div class="social">
                <a href="#" target="_blank">
                    <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/>
                    </svg>
                    YouTube
                </a>
                <a href="#" target="_blank">
                    <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"/>
                    </svg>
                    Facebook
                </a>
                <a href="#" target="_blank">
                    <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                    </svg>
                    Instagram
                </a>
            </div>
        </div>
    </section>
    
    <script>
        // Simple animation on page load
        document.addEventListener('DOMContentLoaded', function() {
            const elements = document.querySelectorAll('section, header h1, header p');
            elements.forEach((el, index) => {
                setTimeout(() => {
                    el.style.opacity = '1';
                    el.style.transform = 'translateY(0)';
                }, 100 * index);
            });
            
            // Set initial styles for animation
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.style.opacity = '0';
                section.style.transform = 'translateY(20px)';
                section.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            });
            
            const headers = document.querySelectorAll('header h1, header p');
            headers.forEach(header => {
                header.style.opacity = '0';
                header.style.transform = 'translateY(20px)';
                header.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            });
        });
    </script>
</body>
</html>
