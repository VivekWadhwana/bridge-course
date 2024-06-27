<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html>
    <html>
    
    <head>
        <style>
            * {
        margin: 0;
        padding: 0;
    }
    
    .navbar {
        display: flex;
        align-items: center;
        justify-content: center;
        position: sticky;
        top: 0;
        padding: 15px;
        cursor: pointer;
    }
    
    .background {
        background: black;
        background-blend-mode: darken;
        background-size: cover;
    }
    
    .nav-list {
        width: 70%;
        display: flex;
        align-items: center;
        gap: 20px;
        list-style: none;
    }
    
    .logo {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .logo img {
        width: 180px;
        border-radius: 50px;
    }
    
    .nav-list li {
        list-style: none;
        padding: 26px 30px;
        padding: 10px;
    }
    
    .nav-list li a {
        text-decoration: none;
        color: white;
    }
    
    .nav-list li a:hover {
        color: grey;
    }
    
    .rightnav {
        width: 30%;
        text-align: right;
    }
    
    #search {
        padding: 5px;
        font-size: 17px;
        border: 2px solid grey;
        border-radius: 9px;
    }
    
    .firstsection {
        background-color: rgb(128, 26, 0);
        height: 400px;
    }
    
    .secondsection {
        background-color: blue;
        height: 400px;
    }
    
    .box-main {
        display: flex;
        justify-content: center;
        align-items: center;
        color: black;
        max-width: 80%;
        margin: auto;
        height: 100%;
    }
    
    .firsthalf {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    
    .secondhalf {
        width: 30%;
    }
    
    .secondhalf img {
        width: 70%;
        border: 4px solid white;
        border-radius: 150px;
        display: block;
        margin: auto;
    }
    
    .text-big {
        font-family: 'Piazzolla', serif;
        font-weight: bold;
        font-size: 35px;
    }
    
    .text-small {
        font-size: 18px;
    }
    
    .btn {
        padding: 8px 20px;
        margin: 7px 0;
        border: 2px solid white;
        border-radius: 8px;
        background: none;
        color: white;
        cursor: pointer;
    }
    
    .btn-sm {
        padding: 6px 10px;
        vertical-align: middle;
    }
    
    .section {
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        max-width: 90%;
        margin: auto;
    }
    
    .section-Left {
        flex-direction: row-reverse;
    }
    
    .paras {
        padding: 0px 65px;
    }
    
    .thumbnail img {
        width: 250px;
        border: 2px solid black;
        border-radius: 26px;
        margin-top: 19px;
    }
    
    .center {
        text-align: center;
    }
    
    .text-footer {
        text-align: center;
        padding: 30px 0;
        font-family: 'Ubuntu', sans-serif;
        display: flex;
        justify-content: center;
        color: rgb(255, 255, 255);
        background-color: black;
    }
    
    footer {
        text-align: center;
        padding: 15px;
    }
    
    
    .rightnav {
        width: 100%;
        text-align: right;
        margin-top: 10px;
    }
    
    #search {
        box-sizing: border-box;
        width: 70%;
        padding: 8px;
        font-size: 17px;
        border: 2px solid grey;
        border-radius: 9px;
    }
    
    .btn-sm {
        padding: 8px 20px;
        margin: 7px 5px;
    }
    
    img {
        max-width: 100%;
        height: auto;
    }
        </style>
        
    </head>
    
    <body>
        <nav class="navbar background">
            <ul class="nav-list">
                <li><a href="">HTML</a></li>
                <li><a href="#web">CProgramming</a></li>
            </ul>
            <div class="rightnav">
                <input type="text" 
                       name="search" 
                       id="search">
                <button class="btn btn-sm">Search</button>
            </div>
        </nav>
    
        <section class="firstsection">
            <div class="box-main">
                <div class="firstHalf">
                    <h1 class="text-big" 
                        id="web">HTML
                      </h1>
                    <p class="text-small">
                        HTML stands for HyperText Markup Language.
                        It is used to design web pages using a markup
                        language. HTML is the combination of Hypertext
                        and Markup language. Hypertext defines the
                        link between the web pages. A markup language
                        is used to define the text document within tag
                        which defines the structure of web pages.
                        HTML is a markup language that is used by the
                        browser to manipulate text, images, and other
                        content to display it in the required format.
                    </p>
    
    
                </div>
            </div>
        </section>
    
        <section class="secondsection">
            <div class="box-main">
                <div class="firstHalf">
                    <h1 class="text-big" 
                        id="program">
                        C Programming
                    </h1>
                    <p class="text-small">
                        C is a procedural programming language. It
                        was initially developed by Dennis Ritchie
                        as a system programming language to write
                        operating system. The main features of C
                        language include low-level access to memory,
                        simple set of keywords, and clean style,
                        these features make C language suitable for
                        system programming like operating system or
                        compiler development.
                    </p>
                </div>
            </div>
        </section>

    
        <footer class="background">
            <p class="text-footer">
                Copyright ©-All rights are reserved
            </p>
        </footer>
    </body>
    
    </html>
</body>
</html>
