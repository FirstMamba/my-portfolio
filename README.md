<!DOCTYPE html>
<html>

<head>
    <title>A Branch of Hunter's CS160 Portfolio</title>
    <meta charset="utf-8" />
    <link href="screen.css" media="screen" rel="stylesheet" type="text/css" />

</head>

<body style="background-color:rgb(7, 68, 26);">

    <h1 style="color: rgb(156, 156, 156);">Python homework</h1>
    
    <p style="font-weight: bold; font-size: 32px; color:rgb(156, 156, 156);">This is python practice.</p>

    <img style="border-style: solid;border-width: 5px;border-color:rgb(0, 0, 0)" src="snake1.jpg" alt="Python" height="568"
        width="1000">

    

<style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
    }

    .header {
        text-align: center;
        padding: 32px;
    }

    .row {
        display: -ms-flexbox;
        /* IE 10 */
        display: flex;
        -ms-flex-wrap: wrap;
        /* IE 10 */
        flex-wrap: wrap;
        padding: 0 4px;
    }

    /* Create two equal columns that sits next to each other */
    .column {
        -ms-flex: 50%;
        /* IE 10 */
        flex: 50%;
        padding: 0 4px;
    }

    .column img {
        margin-top: 8px;
        vertical-align: middle;
    }

    /* Style the buttons */
    .btn {
        border: none;
        outline: none;
        padding: 10px 16px;
        background-color: #f1f1f1;
        cursor: pointer;
        font-size: 18px;
    }

    .btn:hover {
        background-color: #ddd;
    }

    .btn.active {
        background-color: #666;
        color: white;
    }
</style>

<body>

    <!-- Header -->
    <div class="header" id="myHeader">
        <h1>Image Grid</h1>
        <p>Click on the buttons to change the grid view.</p>
        <button class="btn" onclick="one()">1</button>
        <button class="btn active" onclick="two()">2</button>
    </div>

    <!-- Photo Grid -->
    <div class="row">
        <div class="column">
            <img src="completion badges copy.png" style="width:100%">
            <img src="Basic Python and console interaction copy.png" style="width:100%">
            <img src="conditionals completion copy.png" style="width:100%">
            <img src="tracy the turtle completion copy.png" style="width:100%">
            
        </div>
        <div class="column">
        </div>
        
    </div>

    <script>
        // Get the elements with class="column"
        var elements = document.getElementsByClassName("column");

        // Declare a loop variable
        var i;

        // Full-width images
        function one() {
            for (i = 0; i < elements.length; i++) {
                elements[i].style.msFlex = "100%";  // IE10
                elements[i].style.flex = "100%";
            }
        }

        // Two images side by side
        function two() {
            for (i = 0; i < elements.length; i++) {
                elements[i].style.msFlex = "50%";  // IE10
                elements[i].style.flex = "50%";
            }
        }

        

        // Add active class to the current button (highlight it)
        var header = document.getElementById("myHeader");
        var btns = header.getElementsByClassName("btn");
        for (var i = 0; i < btns.length; i++) {
            btns[i].addEventListener("click", function () {
                var current = document.getElementsByClassName("active");
                current[0].className = current[0].className.replace(" active", "");
                this.className += " active";
            });
        }
    </script>

    <textarea style="padding-left:10px; padding-right:10px; float: center; text-align: center; border-style: solid; border-color: rgb(136, 134, 134); background-color:rgb(7, 68, 26); color: rgb(156, 156, 156); font-weight: bold; font-size: 20px;"
        rows="10" cols="90">
    
    
        Programs on python I came up with
            tracy the turtle draws circles and squares 
        https://codehs.com/share/UnxogCR1UI3qKVkL6NKt
        
    </textarea>

    <p>
        <ul style="background-color: rgb(136, 134, 134)">
            <li><a href="https://codehs.com/share/Y2I6U3Wb28hJyTM24yy5">Python Rock, Paper, Scissor program</a></li>
            <li><a href="https://codehs.com/share/wyDTpphfsGs6LJpNRAJs">Python Mastermind program</a></li>
        </ul>
    </p>

    <ul style="float: right; width: 49%; padding: 50px; height: 300px; border-style: solid;border-width: 7px;border-color:rgb(136, 134, 134); background-color: black;">
    
        
        <li><a href="https://github.com">Github homepage</a></li>
        <li><a href="https://repl.it/">Repl.it homepage</a></li>
        <li><a href="https://github.com/login">Github login page</a></li>
        <li><a href="https://codehs.com/go/672D5">Python login page</a></li>
        <li><a href="https://stackoverflow.com/">stackoverflow.com</a></li>
        <li><a href="https://www.w3schools.com/">w3schools homepage</a></li>
        <li><a href="http://appinventor.mit.edu/explore/#">App inventor website</a></li>
        <li><a href="https://code.visualstudio.com/docs/languages/html">Visual Studio Code help</a></li>
        <li><a href="https://unity3d.com/learn/tutorials/topics/user-interface-ui/building-framework">Unity gamebuilding
                building-framework</a></li>

    </ul>

    <ul style="float: left; width: 49%; padding: 50px; height: 300px; border-style: solid;border-width: 7px;border-color:rgb(136, 134, 134); background-color: black;">
        <li><a href="../Questions for HW/images/index.html">images</a></li>
        <li><a href="../index.html">Top Level</a></li>
        <li><a href="../Scratch/index.html">Scratch HW</a></li>
        <li><a href="p5/index.html">P5 homework</a></li>
        <li><a href="../Digital_Photography 265/Week 1/index.html">Week 1 photos</a></li>
        <li><a href="../Digital_Photography 265/Week 2/index.html">Week 2 photos</a></li>
        <li><a href="../Questions for HW/index.html">Questions for HW</a></li>
        <li><a href="../Digital_Photography 265/index.html">Digital_Photography</a></li>

        
        
        

    </ul>





</body>

</html>
