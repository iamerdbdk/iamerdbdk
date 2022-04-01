<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Auto Typing Effect</title>  
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
    <img src="erdal.jpeg">
        <h1>I'm  <span class="auto-type"></span></h1>
        <div class="container2">
        <h2>I'm <span class="auto-type2"></span></h2>
        <p>Hi there 👋 my name is Erdal Budak. I'm a Junior Software Developer 👨‍💻</p>
        <p>I'm a software engineering bootcamp student who lives in the Connecticut.</p>
        <p>I'm learning how to code. I love making and designing webpages with HTML and CSS (and possible JavaScript in the future).</p>
        <h4>| Full Stack | JavaScript | React.js | Ruby on Rails | HTML | CSS |</h4>
        
        <div class="photo">
            
                
                
                <img src="https://img.icons8.com/color/48/000000/javascript--v1.png"/>
                
            
        </div>
        <div class="photo2">
            <img src="https://img.icons8.com/color/48/000000/html-5--v1.png">
        </div>

        <div class="photo3">
            <img src="https://img.icons8.com/color/48/000000/css3.png">
        </div>
        <h4>Contact With Me</h4>
        <div class="contact">
            <img src="https://img.icons8.com/external-justicon-flat-justicon/64/000000/external-linkedin-social-media-justicon-flat-justicon.png"/>
        </div>
        </div>
    </div>
    </div>
    
    
    
    <script src="https://platform.linkedin.com/badges/js/profile.js" async defer type="text/javascript"></script>
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>


    <script>
        var typed = new Typed(".auto-type", {
            strings: [ "Developer", "Dad", "Hard Worker!"],
            typeSpeed: 150,
            backSpeed: 150,
            loop: true

        })

        var typed = new Typed(".auto-type2", {
            strings: [ "Coding", "Eating", "Enjoying"],
            typeSpeed: 150,
            backSpeed: 150,
            loop: true

        })
    </script>   

</body>
</html>
