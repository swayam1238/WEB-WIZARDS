<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
    <link rel="stylesheet" href="home1.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <script src="https://code.jquery.com/jquery-3.7.1.js" integrity="sha256-eKhayi8LEQwp4NKxN+CfCh+3qOVUtJn3QNZ0TciWLP4=" crossorigin="anonymous"></script>
    <script>
        $(document).ready(function(){
            $('#icon').click(function(){
                $('ul').toggleClass('show');
            });
        });
    </script>

</head>
<body>
    <header>
        <div class="logo">
            <a href="https://bit-bangalore.edu.in/"><img src="logo.png" alt=""></a>
        </div>
        <div class="rg">
            <img src="Screenshot_2023-12-07_205303-removebg.png" alt="">
        </div>
    </header>
    <nav>
        <label class="logo"> <i>Web Wizards</i> </label>
        <ul>
            <li><a class="active" href="home1.html" target="_blank">home</a></li>
            <li><a href="events.html" target="_blank">upcoming events</a></li>
            <li><a href="achievements.html" target="_blank">achievements</a></li>
            <li><a href="teaching.html" target="_blank">teaching faculty</a></li>
            <li><a href="feedback.html" target="_blank">feedback</a></li>
            <li><a href="developers.html" target="_blank">developers</a></li>
        </ul>
        <label id="icon">
            <i class="fa-solid fa-bars"></i>
        </label>
    </nav>
    <div class="ai">
        
    </div>
    
</body>
</html>
