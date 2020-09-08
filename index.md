<html>
<head>
    <title>Personal Website (?) </title>
    <link rel="stylesheet" type="text/css" href="CSS/CSS.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Bad+Script&family=Roboto:wght@300&display=swap"
        rel="stylesheet">
    <script>
        function starTime() {
            var today = new Date();
            var h = today.getHours();
            var m = today.getMinutes();
            var s = today.getSeconds();
            m = checkTime(m);
            s = checkTime(s);
            document.getElementById("clock").innerHTML = h + ":" + m + ":" + s;
            var t = setTimeout(starTime, 500);
        }
        function checkTime(i) {
            if (i < 10) { i = "0" + 1 }; // add zero in front of numbers <10
            return i;
        }
    </script>
</head>
<body onload="starTime()">
    <div class="main">
        <section>
            <nav>
                <a href="#" class="logo">M. FAIZ TRIPUTRA</a>
                <ul>
                    <li><a href="#" class="active">THIS</a></li>
                    <li><a href="#">IS</a></li>
                    <li><a href="#">JUST</a></li>
                    <li><a href="#">A</a></li>
                    <li><a href="#">TEXT</a></li>
                    <li><a href="#">MAYBE</a></li>
                    <li><a href="#">(?)</a></li>
                </ul>
                <div class="toggle"></div>
            </nav>
            <div class="text-container">
                <p>Hello,</p>
                <p>I&#8217;M M. Faiz Triputra</p>
                <p>A Human</p>
                <p>Maybe...</p>
            </div>
            <img alt="model" class="model" src="images/model.jpg">
        </section>
        <div class="about-container">
            <!--img-->
            <img src="images/about-img.png" />
            <!--about-me-text-->
            <div class="about-text">
                <p>About Me</p>
                <p>F*CKING ORDINARY HUMAN :)</p>
                <p>Well i didn't know what i need to introduce about, just chat me in 082189100482 then we talk.</p>
            </div>
        </div>
        <!--services-container---------------------------->
        <div class="services ">
            <!--text-->
            <div class="services-text ">
                <p>Seriously, I Can Do :)</p>
            </div>
            <div class="box-container">
                <!--1------------->
                <div class="box-1">
                    <span>1</span>
                    <p class="heading">MC</p>
                    <p class="details">Trust me i can do this can of job... </p>
                </div>
                <!--2------------->
                <div class="box-2">
                    <span>2</span>
                    <p class="heading">Python Fundamentals</p>
                    <p class="details">I can teach u Python Fundamentals !, also other prom lang (?).</p>
                </div>
                <!--3------------->
                <div class="box-3">
                    <span>3</span>
                    <p class="heading">Eat Your Food</p>
                    <p class="details">Is that even counted :/</p>
                </div>
            </div>
            <!--if you have any project in your mind contact me-->
            <div class="contact-me">
                <p>Btw, this page just for jokes, really wanna know me well? just see my linked in : </p>
                <a
                    href="https://www.linkedin.com/in/m-faiz-triputra-913156130">https://www.linkedin.com/in/m-faiz-triputra-913156130</a>
            </div>
            <div class="box">
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </div>
        </div>
</body>
</html>