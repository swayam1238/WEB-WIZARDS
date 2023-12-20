![kempannasir](https://github.com/swayam1238/WEB-WIZARDS/assets/122473017/2aa556b4-e93b-4b6d-9f22-9edde725a21d)
![joytimam](https://github.com/swayam1238/WEB-WIZARDS/assets/122473017/1e969b1c-3341-485d-aa8c-cef4f848dd6b)
*{
    padding: 0;
    margin: 0;
    text-decoration: none;
    list-style: none;
}
body{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    margin:0px;
    background-color:lavender;
}

nav{
    height: 60px;
    width: 100%;
    background-color: #34495e;
}
label.logo{
    font-size: 35px;
    font-weight:lighter;
    color: white;
    padding: 0 100px;
    line-height: 60px;
}
nav ul{
    float: right;
    margin-right: 40px;
}
nav li{
    display: inline-block;
    margin: 0 8px;
    line-height: 60px;
}
nav a {
    color: white;
    font-size: 18px;
    text-transform: capitalize;
    border: 1px solid transparent;
    padding: 7px 10px;
    border-radius: 3px;
}
a.active,a:hover{
    border: 1px solid white;
    transform: .5s;
}
nav #icon{
    color: white;
    font-size: 30px;
    line-height: 80px;
    float: right;
    margin-right: 40px;
    cursor: pointer;
    
}
@media (min-width:900) and (max-width:1200){
    label #icon{
        display: block;
    }
}
@media(max-width: 2000px){
    label.logo{
        font-size:32px;
        padding-left:80px;        
    }
    label#icon{
        display: none;
    }
nav ul{
    margin-right: 20px;
}
nav a {
    font-size: 17px;
} 
.logo img{
    height: 170px;
    width: 550px;
    padding: 30px 35px 30px 85px;
    line-height: 200px;
}

.rg img{
    height: 200px;
    width: 600px;
    line-height: 200px;
    padding: 10px 85px 10px 85px;
}




} 
@media screen and (min-width:900px) and (max-width:1263px)  {
     i .fa-solid fa-bars{
        display: inline-block;
    }
    nav a {
        display: none;
    }
    
}
@media(max-width:900px){
    nav #icon{
        display: block;
    }
    nav ul{
        position: fixed;
        width: 100%;
        height: 100vh;
        background:#2f3640 ;
        top: 80px;
        left: -100%;
        text-align: center;
        transition:all .5s ;

    }
    nav li{
        display: block;
        margin: 50px 0;
        line-height: 30px;
    }
    nav a {
        font-size: 20px;
    }
    a.active,a:hover{
        border: none;
        color: #3498db;
    }
    nav ul.show{
        left: 0;

    }
    .logo img{
        height: 100px;
        width: 330px;
        padding: 20px 40px 20px 40px;
    }
    .rg img{
        height: 115px;
        width: 300px;
        padding: 10px 40px 10px 40px;

    }
}

header{
    display: flex;
    border:border-box;
}

@media (max-width:477px){
    
    .logo img{
        height: 50px;
        width: 150px;
        padding: 10px 20px 10px 20px;
    }
    .rg img{
       display: none;

    }

}
@media (max-width:750px){
    
    .logo img{
        height: 75px;
        width: 235px;
        padding: 10px 20px 10px 20px;
    }
    .rg img{
        height: 95px;
        width: 285px;
        padding: 5px 18px 5px 18px;

    }

}

.joy,.teachers{
    margin: 50px 50px 50px 50px;
    text-align: center;

}

.joy h4,.joy p{
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    text-align: center;
    color: #334258;
    word-spacing: 3px;
}

.teachers,.teachers2{
    display: flex;
    justify-content: space-around;
   
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    text-align: center;
    color: #334258;
    word-spacing: 3px;

}

.teachers2{
    padding-left:220px ;
    padding-right: 220px;
}





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>teachers</title>
    <link rel="stylesheet" href="teaching.css">
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
            <a href="https://bit-bangalore.edu.in/" target="_blank"><img src="logo.png" alt=""></a>
        </div>
        <div class="rg">
            <img src="Screenshot_2023-12-07_205303-removebg.png" alt="">
        </div>
    </header>
    <nav>
        <label class="logo"> <i>Web Wizards</i> </label>
        <ul>
            <li><a href="home1.html" target="_blank">home</a></li>
            <li><a href="events.html" target="_blank"> events</a></li>
            <li><a href="student.html" target="_blank">achievers</a></li>
            <li><a href="achievements.html" target="_blank">achievements</a></li>
            <li><a class="active" href="teaching.html" target="_blank">teaching faculty</a></li>
            <li><a href="feedback.html" target="_blank">Placements</a></li>
            <li><a href="developers.html" target="_blank">developers</a></li>
            
        </ul>
        <label id="icon">
            <i class="fa-solid fa-bars"></i>
        </label>
    </nav>

    <div class="teach">
        <div class="joy">
            <a href="https://sites.google.com/site/dgjyothibitcse/about-me" target="_blank"><img src="joytimam.png" width="275px" height="275px" alt=""></a>
            <h4>Dr.JYOTHI D.G</h4>
            <p>Professor & HOD of AIML</p>
        </div>
    </div>
    <div class="teachers">
        <div class="shobhamam">
            <a href="https://sites.google.com/site/shobhabitcse/home" target="_blank"><img src="shobhamam.png" width="275px" height="275px" alt=""></a>
            <h4>
                Prof. SHOBHA Y
            </h4>
            <P>
                Associate Professor
            </P>
        </div>

        <div class="kempannasir">
            <a href="https://sites.google.com/d/1JTHR6u7-bz93x4E_Z-QoyPfmTO6L5juB/p/1wQfDQ89_WM7IJNVZXpkXz6L-9cUNBP0g/edit"><img src="kempannasir.png" width="275px" height="275px" alt=""></a>
            <h4>
                Dr. KEMPANNA M
            </h4>
            <p>Associate Professor</p>
        </div>


        <div class="shruthibhamam">
            <a href="https://sites.google.com/bit-bangalore.edu.in/shruthiba-a/home" target="_blank"> <img src="shruthibamam.png" width="275px" height="275px" alt=""></a>
            <h4>
                Prof. SHRUTHIBA A
            </h4>
            <p>
                Assistant Professor
            </p>
        </div>


        <div class="sahanamam">
            <a href="https://sites.google.com/view/sahanam" target="_blank"> <img src="sahanamam.png" width="275px" height="275px" alt=""></a>
            <h4>
                Prof. SAHANA M
            </h4>
            <P>
                Assistant Professor
            </P>
        </div>
    </div>

    <div class="teachers2">
        <div class="manjunathsir">
            <a href="https://sites.google.com/bit-bangalore.edu.in/manjunathapb/home" target="_blank"> <img src="manjunathsir.png" width="275px" height="275px" alt=""></a>
            <h4>
                Prof. MANJUNATHA P B
            </h4>
            <P>
                Assistant Professor
            </P>
        </div>
        <div class="vibhamam">
            <a href="https://bit-bangalore.edu.in/"><img src="noone.png" width="275px" height="275px" alt=""></a>
            <h4>
                Dr. Vibha Lakshmikanth
            </h4>
            <p>
                Professor (Faculty)
            </p>
        </div>
        <div class="sanjaysir">
            <a href="https://bit-bangalore.edu.in/"><img src="noone.png" width="275px" height="275px" alt=""></a>
            <h4>
                Sanjay Kumar
            </h4>
            <p>
                Assistant Professor (Faculty)
            </p>
        </div>
    </div>
    <br><br>
   
   

    
    
</body>
</html>
