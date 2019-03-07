<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <title>Jamie Scott | Web Developer</title>
        <style> 
            .bg {
                background-image: url("images/desk2.jpeg");
                height: 100%;
                min-height: 1000px;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
            }
        </style>
    </head>
    <body>
        <div class="bg">
    <!-------- NAV -------->
            <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <a class="navbar-brand text-info" href="#">Jamie Scott</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavDropdown">
                    <ul class="navbar-nav">
                        <li class="nav-item active">
                            <a class="nav-link" href="#intro">Introduction<span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#skills">Skills</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Portfolio</a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="https://github.com/jrs-scott" target="_blank">View My GitHub</a>
                            </div>
                        </li>
                        <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Projects</a>
                                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                    <a class="dropdown-item text-warning" href="#projects">Coming soon!</a>
                                </div>
                            </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>                    
                    </ul>
                </div>
            </nav>  
    <!-------- END NAV -------->

    <!-------- INTRODUCTION -------->    
            <div class="container justify-content-md-center mt-5">
                <div class="card text-center">
                    <div class="card-body">
                    <h1 class="card-title">Let's get acquainted</h1>
                    <p class="card-text">Pleased to meet you! My name is Jamie and I am currently studying software development at the Tech Academy. I was introduced to technology from a young age thanks to those around me, and my intrigue grew through the years. Upon taking my first HTML and CSS class, I was hooked. This site will grow over the next few months as I complete more projects and further my skill set. Now time to stop chattin’ and get coding!</p>
                    <a href="https://github.com/jrs-scott" target="_blank" class="btn btn-info">Visit my GitHub</a>
                    </div>
                </div>
            </div>
    <!-------- END INTRODUCTION -------->   

        </div> <!-- This ends the image/background -->

    <!-------- SKILLS --------> 
        <h1 id="skills" class="text-center">Proficiencies</h1>
        <div class="row justify-content-md-center mx-2">
            <div class="card bg-light m-2" style="max-width: 18rem;">
                <h5 class="card-header text-info text-center">HTML & CSS</h5>
                <div class="card-body">
                    <img src="images/html-css.jpg" class="card-img" height="150" alt="">
                    <p class="card-text">The foundations to any website, HTML works in tandem with CSS to create the beautiful web pages you see every day. My first loves, strongest skills.</p>
                </div>
            </div>

            <div class="card bg-light m-2" style="max-width: 18rem;">
                <h5 class="card-header text-info text-center">Version Control</h5>
                <div class="card-body">
                    <img src="images/github.png" class="card-img" height="150" alt="">
                    <p class="card-text">Projects of any size can benefit from using version control systems. I use Git with GitHub to keep files organized and tracked. Fixing pesky errors and managing branches comes with the territory.</p>
                </div>
            </div>

            <div class="card bg-light m-2" style="max-width: 18rem;">
                <h5 class="card-header text-info text-center">Visual Studio</h5>
                <div class="card-body">
                    <img src="images/visual-studio.png" class="card-img" height="150" alt="">
                    <p class="card-text">Writing neat code is imperative, which is precisely what I use Visual Studio Code for. Debug, use source control, and collaborate with team members.</p>
                </div>
            </div>  

            <div class="card bg-light m-2" style="max-width: 18rem;">
                    <h5 class="card-header text-info text-center">Adobe Photoshop</h5>
                    <div class="card-body">
                        <img src="images/photoshop.jpg" class="card-img" height="150" alt="">
                        <p class="card-text">The Adobe suite comes in handy for curating web development. My background in photography lead me to use Photoshop predominantly, but I have also dabbled in their other programs.</p>
                    </div>
                </div>

            <div class="card bg-light m-2" style="max-width: 18rem;">
                <h5 class="card-header text-info text-center">Microsoft Excel</h5>
                <div class="card-body">
                    <img src="images/excel.png" class="card-img" height="150" alt="">
                    <p class="card-text">Microsoft continues to make essential programs for businesses, including Excel. Previous record keeping jobs provided me with intermediate skill level.</p>
                </div>
            </div>

            <div class="card bg-light m-2" style="max-width: 18rem;">
                <h5 class="card-header text-info text-center">Teamwork</h5>
                <div class="card-body">
                    <img src="images/teamwork.png" class="card-img" height="150" alt="">
                    <p class="card-text">Though teamwork is required in every office, it is not a given skill. I have a strong background working with others and enjoy doing so. Communication is key, and I use it liberally. </p>
                </div>
            </div>
        </div> 
    <!-------- END SKILLS --------> 

    <!-------- PROJECTS --------> 
        <h1 id="projects" class="text-center m-4">Recent Projects</h1>
        <div class="alert alert-warning mx-auto" role="alert" style="width: 95%">
            <h5 class="text-center">This section is coming soon! The current projects I am working on will be updated here when they are ready for their debut.</h5>
        </div>
    <!-------- END PROJECTS --------> 

    <!-------- CONTACT --------> 
        <h1 id="contact" class="text-center m-4">Connect with Me</h1>
        <div class="text-info text-center">
            <ul class="mx-auto list-group list-group-horizontal mb-5" style="width: 25%">
                <li class="list-group-item"><a href="https://www.linkedin.com/in/jamie-scott-06200454/" target="_blank" class="text-info">LinkedIn profile</a></li>
                <li class="list-group-item"><a href="https://github.com/jrs-scott" target="_blank" class="text-info">GitHub portfolio</a></li>                    
                <li class="list-group-item"><a href="mailto:scott.jamierae@gmail.com" target="_blank" class="text-info">Send an email</a></li>
            </ul>    
        </div>
    <!-------- END CONTACT --------> 


        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </body>
</html>
