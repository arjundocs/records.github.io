<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Android Developer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600&display=swap"
        rel="stylesheet">
    <style>
        body {
            /* font-family: 'Arial', sans-serif; */
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 30px 0;
        }

        h1 {
            margin: 10px 0;
        }

        p {
            margin: 0;
        }

        img {
            /* border-radius: 50%; */
            max-width: 100%;
            height: auto;
        }

        section {
            margin: 20px 0;
        }

        .project-card {
            background-color: #3d3939;
            border: 1px solid #000;
            border-radius: 5px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .project-card-main {
            background-color: #474040;
            border: 1px solid #000;
            border-radius: 5px;
            padding: 20px;
            margin: 20px 0;
            /* Adjusted margin for spacing */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 100%;
            /* Takes full width */
            box-sizing: border-box;
            display: block;
            /* Ensures each card is displayed on a new line */
        }



        .project-card img {
            max-width: 30px;
            height: 20px;
            border-radius: 1px;
        }

        a {
            margin-top: 20px;
            color: #fff;
            text-decoration: none;
            display: inline-block;
            padding: 8px 16px;
            border: 1px solid #fff;
            border-radius: 4px;
            transition: background-color 0.3s, color 0.3s;
            margin-right: 10px;
        }

        a:hover {
            background-color: #fff;
            color: #000;
        }

        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .skills {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: space-around;
            margin: 5px 0;
        }

        .skills li {
            text-align: center;
        }

        .social-media {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .building-projects {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: space-around;
            margin: 5px, 0;
        }

        .building-projects li {
            /* text-align: center; */
            margin: 10px;
        }

        .social-media {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .social-media li {
            margin: 0 10px;
        }

        h2 {
            text-align: center;
        }

        .skills-logo {
            height: 100px;
            width: 100px;
            display: flex;
            align-items: center;
        }

        form {
            margin-top: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 12px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background-color: #000;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }

        #blogs {
            margin: 20px 0;
        }

        .blog-item {
            display: flex;
            margin-bottom: 20px;
            background: #282727;
            padding: 20px;
            border-radius: 5px;
        }

        .blog-image {
            max-width: 200px;
            height: auto;
            border-radius: 5px;
            margin-right: 20px;
        }

        .blog-content {
            flex-grow: 1;
        }

        .blog-content h3 {
            margin-top: 0;
        }

        .read-more {
            display: inline-block;
            padding: 8px 16px;
            background-color: #000;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s, color 0.3s;
        }

        .read-more:hover {
            background-color: #555;
        }
    </style>
</head>

<body>

    <header>
        <div class="container">
            <!-- <img src="https://oliver-andersen.se/wp-content/uploads/2018/03/cropped-Profile-Picture-Round-Color.png"
                alt="Your Name" width="150"> -->
                <img src="pro_pic/profile-pic (4).png"
                alt="Your Name" width="150">
            <h3>Hello,How are You?</h3>

            <h1>Building that Create Impacts.</h1>
            <p>Consectetur adipisicing elit. Accusamus, error quaerat quidem iusto vel assumenda eveniet reprehenderit
                ipsa labore tempore id commodi! Odit earum, unde quam in eum itaque officia.</p>
            <a href="#" class="join-community">Join Community</a>
        </div>
    </header>

    <section id="skills">
        <div class="container">
            <h2>ME EXPERIENCES</h2>
            <!-- <ul class="skills">
                <li>Java</li>
                <li>Kotlin</li>
                <li>Android Studio</li>
                <li>UI/UX Design</li>
            </ul> -->
            <ul class="skills">
                <li><img src="https://img.icons8.com/?size=48&id=13679&format=png" alt=""></li>
                <li><img src="https://img.icons8.com/?size=48&id=ZoxjA0jZDdFZ&format=png" alt=""></li>
                <li><img src="https://img.icons8.com/?size=48&id=17836&format=png" alt=""></li>
                <li><img src="https://img.icons8.com/?size=48&id=7gdY5qNXaKC0&format=png" alt=""></li>
                <li><img src="https://img.icons8.com/?size=48&id=20909&format=png" alt=""></li>
            </ul>
        </div>
    </section>

    <section id="building-projects">
        <div class="container">
            <h2>BUILDING PROJECTS</h2>
            <ul class="building-projects">
                <li>
                    <div class="project-card-main">
                        <h3>Artscreen: AI Generated Wallapapers</h3>
                        <img src="https://help.figma.com/hc/article_attachments/18924884984727" alt="Project 1">
                        <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="#">Download</a>
                    </div>
                </li>
                <li>
                    <div class="project-card-main">
                        <h3>DailyJuarnal: Write juarney in you Locial Storage.</h3>
                        <img src="https://help.figma.com/hc/article_attachments/18924884984727" alt="Project 1">
                        <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="#">Download</a>
                    </div>
                </li>
            </ul>
            <ul class="building-projects">
                <li>
                    <div class="project-card-main">
                        <h3>Cemistory: Values & Play Cemistory Quizes.</h3>
                        <img src="https://help.figma.com/hc/article_attachments/18924884984727" alt="Project 1">
                        <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="#">Download</a>
                    </div>
                </li>
                <li>
                    <div class="project-card-main">
                        <h3>Vocablary: To Improve your vocablary</h3>
                        <img src="https://help.figma.com/hc/article_attachments/18924884984727" alt="Project 1">
                        <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="#">Download</a>
                    </div>
                </li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>SHOWCASE PROJECTS</h2>
            <!-- Building Projects -->
            <div class="project-card-main">
                <h3>Artscreen: AI Generated Wallapapers</h3>
                <img src="https://help.figma.com/hc/article_attachments/18924884984727" alt="Project 1">
                <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
            <div class="project-card-main">
                <h3>Project 2</h3>
                <img src="https://images.unsplash.com/opengraph/1x1.png?blend=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1575936123452-b67c3203c357%3Fblend%3D000000%26blend-alpha%3D10%26blend-mode%3Dnormal%26crop%3Dfaces%252Cedges%26h%3D630%26mark%3Dhttps%253A%252F%252Fimages.unsplash.com%252Fopengraph%252Fsearch-input.png%253Fh%253D84%2526txt%253Dimage%2526txt-align%253Dmiddle%25252Cleft%2526txt-clip%253Dellipsis%2526txt-color%253D000000%2526txt-pad%253D80%2526txt-size%253D40%2526txt-width%253D660%2526w%253D750%2526auto%253Dformat%2526fit%253Dcrop%2526q%253D60%26mark-align%3Dmiddle%252Ccenter%26mark-w%3D750%26w%3D1200%26auto%3Dformat%26fit%3Dcrop%26q%3D60%26ixid%3DM3wxMjA3fDB8MXxzZWFyY2h8Mnx8aW1hZ2V8ZW58MHx8fHwxNzAzMDAwNzQzfDA%26ixlib%3Drb-4.0.3&blend-w=1&h=630&mark=https%3A%2F%2Fimages.unsplash.com%2Fopengraph%2Flogo.png&mark-align=top%2Cleft&mark-pad=50&mark-w=64&w=1200&auto=format&fit=crop&q=60"
                    alt="Project 2">
                <p>Description of Project 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
            <div class="project-card-main">
                <h3>Project 3</h3>
                <img src="https://s3-alpha.figma.com/hub/file/4072859956/3393b8f4-01ec-450a-8e0d-c7125b2f57d1-cover.png"
                    alt="Project 3">
                <p>Description of Project 3. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>

            <!-- Dummy Projects
            <h2>Dummy Projects</h2>
            <div class="project-card">
                <h3>Dummy Project 1</h3>
                <img src="dummy1.jpg" alt="Dummy Project 1">
                <p>Description of Dummy Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
            <div class="project-card">
                <h3>Dummy Project 2</h3>
                <img src="dummy2.jpg" alt="Dummy Project 2">
                <p>Description of Dummy Project 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
            <div class="project-card">
                <h3>Dummy Project 3</h3>
                <img src="dummy3.jpg" alt="Dummy Project 3">
                <p>Description of Dummy Project 3. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
            <div class="project-card">
                <h3>Dummy Project 4</h3>
                <img src="dummy4.jpg" alt="Dummy Project 4">
                <p>Description of Dummy Project 4. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <a href="#">Download</a>
            </div>
        </div> -->
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Passionate Android Developer with a focus on creating user-friendly and innovative mobile applications.
                Skilled in Java and Kotlin. Excited to contribute to the world of mobile development.</p>
        </div>
    </section>





    <!-- Add this section after the #social-media section -->

    <section id="blogs">
        <div class="container">
            <h2>Latest Blogs</h2>

            <div class="blog-item">
                <img src="https://developermedia.com/wp-content/uploads/2019/09/what-should-a-tech-resource-hub-looks-like-1000px.jpg" alt="Blog 1" class="blog-image">
                <div class="blog-content">
                    <h3>Blog Title 1</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor tellus eu odio hendrerit
                        tristique. Sed aliquet neque vel ligula fermentum, in mattis quam malesuada.</p>
                    <a href="#" class="read-more">Read More</a>
                </div>
            </div>

            <div class="blog-item">
                <img src="https://blog.hartman-technology.com/wp-content/uploads/2019/03/050318_LRR_MEN_WomenTech.jpg" alt="Blog 2" class="blog-image">
                <div class="blog-content">
                    <h3>Blog Title 2</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor tellus eu odio hendrerit
                        tristique. Sed aliquet neque vel ligula fermentum, in mattis quam malesuada.</p>
                    <a href="#" class="read-more">Read More</a>
                </div>
            </div>

            <div class="blog-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTl-iINukESRzHqQlsnsN5y0zQmwdOkNUpHsx2QCSvRSgLlo_u-j13AlK-MMkr6PcvvA40&usqp=CAU" alt="Blog 3" class="blog-image">
                <div class="blog-content">
                    <h3>Blog Title 3</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor tellus eu odio hendrerit
                        tristique. Sed aliquet neque vel ligula fermentum, in mattis quam malesuada.</p>
                    <a href="#" class="read-more">Read More</a>
                </div>
            </div>

            <div class="blog-item">
                <img src="https://guardian.ng/wp-content/uploads/2016/01/WOMEN-IN-TECH.jpg" alt="Blog 4" class="blog-image">
                <div class="blog-content">
                    <h3>Blog Title 4</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor tellus eu odio hendrerit
                        tristique. Sed aliquet neque vel ligula fermentum, in mattis quam malesuada.</p>
                    <a href="#" class="read-more">Read More</a>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="mailto:artscreen@gmail.com" method="post" enctype="text/plain">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </div>
    </section>




    <section id="social-media">
        <div class="container">
            <h2>Follow Me on Social Media</h2>
            <ul class="social-media">
                <li><a href="#" target="_blank"><img src="https://img.icons8.com/?size=48&id=60469&format=png"
                            alt="Twitter"></a></li>
                <li><a href="#" target="_blank"><img src="https://img.icons8.com/?size=48&id=UrgbzHxXKotn&format=png"
                            alt="Instagram"></a></li>
                <li><a href="#" target="_blank"><img src="https://img.icons8.com/?size=48&id=yGcWL8copNNQ&format=png"
                            alt="Facebook"></a></li>
                <li><a href="#" target="_blank"><img src="https://img.icons8.com/?size=48&id=xuvGCOXi8Wyg&format=png"
                            alt="Linkedin"></a></li>
                <li><a href="#" target="_blank"><img src="https://img.icons8.com/?size=48&id=19318&format=png"
                            alt="Linkedin"></a></li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Your Name - Android Developer</p>
        </div>
    </footer>

    <script>
        // You can add JavaScript functionality here if needed
    </script>
</body>

</html>
