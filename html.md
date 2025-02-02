<html>
 <head>
  <title>
   Portfolio
  </title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
            background-color: #f5a623;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background-color: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin: 10px;
            padding: 20px;
            width: 300px;
            box-sizing: border-box;
        }
        .card img {
            border-radius: 50%;
            width: 50px;
            height: 50px;
        }
        .card h2, .card h3, .card h4 {
            margin: 10px 0;
        }
        .card p {
            margin: 10px 0;
            line-height: 1.6;
        }
        .card .skills, .card .testimonials, .card .clients, .card .blog, .card .resume, .card .contact {
            margin-top: 20px;
        }
        .card .skills .skill {
            display: flex;
            justify-content: space-between;
            margin: 5px 0;
        }
        .card .skills .skill .bar {
            background-color: #333;
            border-radius: 5px;
            height: 10px;
            width: 70%;
            position: relative;
        }
        .card .skills .skill .bar span {
            background-color: #f5a623;
            border-radius: 5px;
            display: block;
            height: 100%;
            width: 70%;
        }
        .card .testimonials .testimonial, .card .clients .client, .card .blog .post, .card .resume .item, .card .contact .info {
            margin: 10px 0;
        }
        .card .testimonials .testimonial img, .card .clients .client img, .card .blog .post img {
            border-radius: 50%;
            width: 40px;
            height: 40px;
        }
        .card .contact iframe {
            border: 0;
            width: 100%;
            height: 200px;
            border-radius: 10px;
        }
        .card .contact .info {
            display: flex;
            align-items: center;
        }
        .card .contact .info i {
            margin-right: 10px;
        }
        .card .contact .info p {
            margin: 0;
        }
  </style>
 </head>
 <body>
  <div class="container">
   <div class="card">
    <img alt="Profile picture" height="50" src="https://storage.googleapis.com/a1aa/image/9rWmhwwJiwJ5J5GV8VjdiELa7l676mzE0TdihJX4Pwq3e90JA.jpg" width="50"/>
    <h2>
     Richard Hanrick
    </h2>
    <h4>
     Web Developer
    </h4>
    <p>
     Email: richard@example.com
    </p>
    <p>
     Phone: (123) 456-7890
    </p>
    <p>
     Birthday: June 23, 1982
    </p>
    <p>
     Location: Sacramento, California, USA
    </p>
   </div>
   <div class="card">
    <h2>
     About Me
    </h2>
    <p>
     I'm Creative Director and UI/UX Designer from Sydney, Australia, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.
    </p>
    <p>
     My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I created web design for many famous brand companies.
    </p>
   </div>
   <div class="card skills">
    <h2>
     Skills
    </h2>
    <div class="skill">
     <span>
      Web Design
     </span>
     <div class="bar">
      <span style="width: 70%;">
      </span>
     </div>
    </div>
    <div class="skill">
     <span>
      Graphic Design
     </span>
     <div class="bar">
      <span style="width: 90%;">
      </span>
     </div>
    </div>
    <div class="skill">
     <span>
      Branding
     </span>
     <div class="bar">
      <span style="width: 80%;">
      </span>
     </div>
    </div>
    <div class="skill">
     <span>
      WordPress
     </span>
     <div class="bar">
      <span style="width: 75%;">
      </span>
     </div>
    </div>
   </div>
   <div class="card testimonials">
    <h2>
     Testimonials
    </h2>
    <div class="testimonial">
     <img alt="Testimonial picture" height="40" src="https://storage.googleapis.com/a1aa/image/C2VC5qcNcTp3E9Mlf6xhRhsrz7Lfz7soT7pe4Csg3p3etvnOB.jpg" width="40"/>
     <p>
      Daniel Lewis
     </p>
     <p>
      Richard was hired to create a corporate identity. We were very pleased with the work done. He has a lot of experience and is very concerned about the needs of client. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent sit amet erat eget metus blandit condimentum in vel mauris. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
     </p>
    </div>
   </div>
   <div class="card clients">
    <h2>
     Clients
    </h2>
    <div class="client">
     <img alt="Client logo" height="50" src="https://storage.googleapis.com/a1aa/image/f1O60q0eM8g5VUq0Gkyg0TjbAayd5eiWZ3nLT4hywws423TnA.jpg" width="100"/>
    </div>
    <div class="client">
     <img alt="Client logo" height="50" src="https://storage.googleapis.com/a1aa/image/f1O60q0eM8g5VUq0Gkyg0TjbAayd5eiWZ3nLT4hywws423TnA.jpg" width="100"/>
    </div>
   </div>
   <div class="card blog">
    <h2>
     Blog
    </h2>
    <div class="post">
     <img alt="Blog post image" height="40" src="https://storage.googleapis.com/a1aa/image/6gdn9jYpel0EOi1yRQdHqfC1hiC0mZUnXuqjQNkUcDAb77pTA.jpg" width="40"/>
     <h3>
      Design Conference 2022
     </h3>
     <p>
      Design - Feb 23, 2022
     </p>
     <p>
      Vivamus et quam scelerisque, vulputate velit vitae, ultrices dui.
     </p>
    </div>
    <div class="post">
     <img alt="Blog post image" height="40" src="https://storage.googleapis.com/a1aa/image/6gdn9jYpel0EOi1yRQdHqfC1hiC0mZUnXuqjQNkUcDAb77pTA.jpg" width="40"/>
     <h3>
      Design Conference 2022
     </h3>
     <p>
      Design - Feb 23, 2022
     </p>
     <p>
      Vivamus et quam scelerisque, vulputate velit vitae, ultrices dui.
     </p>
    </div>
   </div>
   <div class="card resume">
    <h2>
     Resume
    </h2>
    <div class="item">
     <h3>
      Education
     </h3>
     <p>
      University School of the Arts
     </p>
     <p>
      2006 - 2010
     </p>
     <p>
      New York Academy of Art
     </p>
     <p>
      2008 - 2007
     </p>
    </div>
    <div class="item">
     <h3>
      Experience
     </h3>
     <p>
      Web Designer
     </p>
     <p>
      2010 - 2018
     </p>
    </div>
   </div>
   <div class="card contact">
    <h2>
     Contact
    </h2>
    <div class="info">
     <i class="fas fa-map-marker-alt">
     </i>
     <p>
      Sacramento, California, USA
     </p>
    </div>
    <div class="info">
     <i class="fas fa-phone">
     </i>
     <p>
      (123) 456-7890
     </p>
    </div>
    <div class="info">
     <i class="fas fa-envelope">
     </i>
     <p>
      richard@example.com
     </p>
    </div>
    <iframe allowfullscreen="" loading="lazy" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.835434509374!2d144.9537353153167!3d-37.81627917975195!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642af0f11fd81%3A0xf577d1f9c1b1e0e!2sVictoria%20State%20Library!5e0!3m2!1sen!2sau!4v1611814511234!5m2!1sen!2sau">
    </iframe>
   </div>
  </div>
 </body>
</html>
