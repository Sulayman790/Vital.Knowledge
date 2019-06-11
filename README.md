<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Project: Blog</title>
        <style>
            
            body {
                font-family: "Baskerville Old Face", serif;
                font-size: 20px;
                line-height:1.5;
                
            }
            h1 {
                font-family: monospace;
                text-align: center;
                font-size: 3em;
                color: rgb(180, 175, 250);
                background-color: rgb(0, 0, 0);
            }
            
            @keyframes example {
                from {color: rgb(164, 184, 31);}
                to {color: black;}
            }
            
            h2 {
                font-family: monospace;
                text-align: center;
                font-size: 2em;
                animation-name: example;
                animation-duration: 6s;
                background-image: url("https://www.kasandbox.org/programming-images/seasonal/snowy-slope-with-trees.png");
            }
            
            ul {
                text-align: center;
                list-style-type: none;
                line-height: 2;
                font-size: 25px;
            }
            
            h3 {
                font-size:1.3em;
            }
            
            div.block {
                width: 350px;
                border: 6px solid black;
                padding: 17px;
                margin: 5px;
                text-align: justify;
                float: left;
                border-collapse: collapse;
                
            }
            img.block {
                display: auto;
                margin-left: 32%;
                margin-right: auto;
                width: 30%;
                
            }
            
            a{
                text-decoration: none;
                color: black;
                font-style: bolder;
            }
            
            a:hover {
                color: brown;
            }
            
            a.postlink {
                color: black;
                font-family: "Kristen ITC", serif;
                font-size: 22px;
                text-decoration: none;
                
            }
            a.postlink:hover {
                color: red;
            }
            
            a.readmore {
                color: gray;
                font-style: italic;
                opacity: 0.8;
            }
        </style>
    </head>
    <body>
        
        <h1>Soulman's news</h1>
        
        <h2>Try to put one pebble to build the sculpture of human evolution, if you can do more, put it a huge rock</h2>
        <ul>
            <a href="Projets.html" target="_blank" ><li> Projets</li></a>
            <a href="Books&website.html" target="_blank"><li> Books and usefell webs sites</li> </a>
            <a href="Inspiratepeople.html" target="_blank" ><li> Inspiring people of our century</li></a>
            <a href="Memes.html" target="_blank" ><li> Memes and fun things </li></a>
        </ul>
        <img src="https://www.kasandbox.org/programming-images/animals/cat.png" alt="cats look at you">
        
        <ul>
            <a class="postlink" href="#Why I created this blog">
            <li> Why I created this bloks 
            </a>
            <a class="postlink" href="#A simple question : Why read ?">
            <li> A simple question : Why read ?
            </a>
        </ul>
        
        <div class="block"><h3> Why I created this blog</h3>
        <img class="block" src="https://www.kasandbox.org/programming-images/avatars/questionmark.png" alt="interogation symbol">
        <p id="Why I created this blog">This blog has been created to share knowledge with you. At the age of 22 years, after having read the book "Replay" of Ken Grimwood, I have starting to search for huge quantity of knowledge. few time later, I discovered my ignorance of the word. Some of the mainly important things to know (read lot of books, how to learn well and fast, the importance of learning other languages etc..) were hide just in face of my nose. I was so angry that nobody told me that during my childhood. I promised myselft to: add value in this word and help people to have a better access at primordial knowledges <a class="readmore" href="Why I created this blog.html"> read more... </a></p>
            <h6>Posted the 31/05/2019</h6>
        </div>
        <div class="block"><h3> A simple question : Why read ? </h3>
        <p id="A simple question : Why read ?"> Maybe have you already heard a lot about this subject or maybe it's new for you. Consider that all successful people in intellectual field had or currently read a lot. And not random books, this kind of people choose their books in fonction of their goals. So why school still not teach us to love and choose correctly our books ? additionally, books give you more that only pure knowledge it <a class="readmore" href="A simple question: Why read.html"> read more... </a></p>
        <h6> Posted the 01/06/2019</h6>
            
        </div>   
    </body>
</html>
