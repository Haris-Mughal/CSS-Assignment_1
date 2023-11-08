# CSS-Assignment_1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./styles/style.css">
</head>
<body>
    <header>
<nav id="navbox">
    <a href="" class="navitems">Home</a>
    <a href="" class="navitems">Lectures</a>
    <a href="" class="navitems">Assignments</a>
    <a href="" class="navitems">First Project</a>
    <a href="" class="navitems">Labs</a>
    <a href="" class="navitems">Docs</a>
</nav>
    </header>

  <main>
            <h1 class="heading"></div>Assignment 1: Static Web: HTML/CSS</h1>
        <p class="heading"><small>Due Sunday, January 9:11:50pm PST</small></p>
        
        
  <h1>Setup</h1>
        <p>Accept the Github Classroom <span style="color: brown;">assignment</span> and clone this repo that contain stencil code for Assignment 2</p>
              <h1>Introduction</h1>
              <p>This is a multi-part assignment with the objective of making you comfortable working with HTML and CSS. By the end of this assignment, you will have styled some rectangular blocks and created a simple version of Twitter's home page.</p>
              <p>If this assignment seems overwhelming to you, please come see a TA at TA hours to talk through some strategies for tackling it. We expect this assignment to be a time-consuming assignment as we cover a lot of fundamental techiniques. But with a good strategy, it can be finished in a reasonable amount of time.</p>
              <p>Note: Only CSS and HTML will be used for this assignment. If you want to use JavaScript (or libraries such as jQuery) then feel free to, but we will only be grading correctness on your CSS and HTML.</p>
              <p>If you can, <strong>start Earlier</strong></p>

  <h1>Part One</h1>

   <h2>Specifications</h2>

   <p>Now that you understand some of the basics of HTML and CSS, let's take a look at how to align HTML elements. There are multiple ways to align HTML elements, but in this part, we recommend using flexboxes as they are widely used in modern web development (for example BootstrapV4 is built on top of flexboxes).</p>
              <p>Refer to this great webpage on how to use Fireboxes <span style="color:brown">CSS Firebox Guide.</span></p>
               <p>Also feel free to use online resources such as Stack Overflow, MDN, W3, and Google for reference.</p>
            <p>When you open this provider HTML file <code><span style="color: hotpink;">part1/index.html</span></code>, it should look like this.</p>
    <section id="block">

        
   <h5>Assignment 1</h5>
            <h5>Provided Examples</h5>

   <h5>Row 1</h5>
            <div id="row1">
                <div class="box1-1"></div>
                <div class="box2-1"></div>
            </div><br>
            
   <h5>Row 2</h5>
            <div id="row2">
                <div class="box1-2"></div>
                <div class="box2-2"></div>
            </div><br>
            
   <h5>Student TODOs</h5>
            <h5>Row 3</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

  <h5>Row 4</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

   <h5>Row 5</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

  <h5>Row 6</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

 <h5>Row 7</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

 <h5>Row 8</h5>
            <div>
                <div class="same-boxes"></div>
            </div>

  <h5>Row 9</h5>
            <div>
                <div class="same-boxes"></div>
            </div>
        </section><br />
        <br /><hr />
            
  <p>As you can see there are 9 rectangles. the styling and makeupof the first two rectangles are already built for you. Your task is to apply stylings and add div elements inside of the next 7 green rectangular blocks to createa webpage that looks like this:</p>
            
   <section id="block">
            <h5>Assignment 1</h5>
            <h5>Provided Examples</h5>

  <h5>Row 1</h5>
            <div id="row1">
                <div class="box1-1"></div>
                <div class="box2-1"></div>
            </div><br>
            
  <h5>Row 2</h5>
            <div id="row2">
                <div class="box1-2"></div>
                <div class="box2-2"></div>
            </div><br>

   <h5>Student TODOs</h5>
            <h5>Row 3</h5>
            <div id="row3">
                <div class="box1-3"></div>
                <div class="box2-3"></div>
                <div class="box3-3"></div>
            </div>

   <h5>Row 4</h5>
            <div id="row4">
                <div class="box1-4"></div>
                <div class="box2-4"></div>
            </div>

  <h5>Row 5</h5>
            <div id="row5">
                <div class="box1-5">
                    <div class="box2-5"></div>
                </div>    
            </div>

  <h5>Row 6</h5>
            <div id="row6">
                <div class="box1-6">
                    <div class="box2-6"></div>
                </div>    
            </div>

   =<h5>Row 7</h5>
            <div id="row7">
                <div class="box1-7"></div>
                <div class="box2-7">
                    <div class="box3-7"></div>
                </div>    
            </div>

  <h5>Row 8</h5>
            <div id="row8">
                <div class="box1-8"></div>
                    <div class="box2-8"></div>
                    <div class="box3-8"></div>
                    <div class="box4-8"></div>
                    <div class="box5-8"></div>
                    <div class="box6-8"></div>
                    <div class="box7-8"></div>
                    <div class="box8-8"></div>
                    <div class="box9-8"></div>
            </div>

   <h5>Row 9</h5>
            <div id="row9">
                <div class="box1-9"></div>
                <div class="box2-9"></div>
                <div class="box3-9"></div>
                <div class="box4-9"></div>
                <div class="box5-9"></div>
                <div class="box6-9"></div>
                <div class="box7-9"></div>
                <div class="box8-9"></div>
                <div class="box9-9"></div>
            </div>

 </section>

  <p>Note that these rectangular blocks should be responsive. Here is what they look like when the window is thinner:</p>
    
  <section id="blockL">
                <h5>Assignment 1</h5>
                <h5>Provided Examples</h5>
    <h5>Row 1</h5>
                <div id="row1">
                    <div class="box1-1"></div>
                    <div class="box2-1"></div>
                </div><br>
                
  <h5>Row 2</h5>
                <div id="row2C">
                    <div class="box1-2C"></div>
                    <div class="box2-2C"></div>
                </div><br>
    
  <h5>Student TODOs</h5>
                <h5>Row 3</h5>
                <div id="row3C">
                    <div class="box1-3C"></div>
                    <div class="box2-3C"></div>
                    <div class="box3-3C"></div>
                </div>
    
  <h5>Row 4</h5>
                <div id="row4C">
                    <div class="box1-4C"></div>
                    <div class="box2-4C"></div>
                </div>
    
  <h5>Row 5</h5>
                <div id="row5C">
                    <div class="box1-5C">
                        <div class="box2-5C"></div>
                    </div>    
                </div>
    
 <h5>Row 6</h5>
                <div id="row6C">
                    <div class="box1-6C">
                        <div class="box2-6C"></div>
                    </div>    
                </div>
    
<h5>Row 7</h5>
                <div id="row7C">
                    <div class="box1-7C"></div>
                    <div class="box2-7C">
                        <div class="box3-7C"></div>
                    </div>    
                </div>
    
<h5>Row 8</h5>
                <div id="row9">
                    <div class="box1-9"></div>
                        <div class="box2-9"></div>
                        <div class="box3-9"></div>
                        <div class="box4-9"></div>
                        <div class="box5-9"></div>             
                        <div class="box6-9"></div>
                        <div class="box7-9"></div>
                        <div class="box8-9"></div>
                        <div class="box9-9"></div>
                </div>
                <!-- small wali row8 small wali row9 dono same thi iss liye same name de diyaa -->
                <h5>Row 9</h5>
                <div id="row9">
                    <div class="box1-9"></div>
                    <div class="box2-9"></div>
                    <div class="box3-9"></div>
                    <div class="box4-9"></div>
                    <div class="box5-9"></div>
                    <div class="box6-9"></div>
                    <div class="box7-9"></div>
                    <div class="box8-9"></div>
                    <div class="box9-9"></div>
                </div>
            </section>

<p>We will describe how each row will behave dynamically and provide some hints for a possible approach:</p>
    <ol>
        <li>For the third row, the red and blue end rectangles should remain the same width, and the green space should shrink.</li><br />
        <i>Possible Approach: Have a div with a red background and a div with a blue background, both with fixed width. Use an appropriate value for <span style="color: brown;">Justify Content.</span></i><br /><br />
        <li>For the fourth row, the blue end rectangle should remain the same width, and the red rectangle should shrink.</li><br />
        <i>Possible Approach: Have a div with a red background and a div with a blue background. Have a fixed width on the blue div, Use <span style="color: brown;">Flex Grow.</span></i><br /><br />
        <li>For the fifth row, the red square should remain the same size, but always remain in the center of the green rectangle.</li><br />
        <i>Hint: Think about how to keep a div fixed size and how to align something in the absolute center of the parent element.</i><br /><br />
        <li>For the sixth row, the blue rectangle should remain the same size, while the red rectangles should shrink. The blue rectangle should remain in the center of the row.</li><br />
        <i>Hint: Use two red divs.</i><br /><br />
        <li>For the seventh row, the red rectangle should remain the same width.</li><br />
        <i>Hint: Nest divs and use <code><span style="color: hotpink;">background-color: transparent.</span></code></i><br /><br />
        <li>For the eighth row, the orange rectangles should remain the same size while the green space between them shrinks.</li><br />

<li>For the ninth row, the green space between the orange rectangles should remain the same width while the orange rectangles narrow.</li><br />
    </ol>
        <p>The examples we provided with the first two rectangular blocks use flexboxes. You are not required to use flexboxes for the next 7 rows, but we recommend it as it will also be useful in part 2 of this assignment.</p>
        <p>You should only have to use the <code><span style="color: hotpink;">div</span></code> html element to complete this assignment. Also, <strong>none of the divs you create inside of the provided wrapper divs should have <code><span style="color: hotpink;">background-color: green;</span></code></strong> But it is valid to specify non-green background colors for any divs, including the wrapper.</p>
        <p>Try to style the boxes as closely to the solution image as possible don't worry about getting exact dimensions or rgb values. We care about what structure,CSS styles you used, and the dynamic behavior of the page. However just for reference,</p>
            
  <ul>
            <li>The color of the boxes we used are <code><span style="color: hotpink;">background-color:</span></code> <span style="background-color: red; color: white;">red</span> , <span style="background-color: blue; color: white ;">blue</span> , and <span style="background-color: orange;">orange</span></li>
            <li>Some width/height values we used are <code><span style="color: hotpink;">20px, 40px, 80px</span></code></li>
        </ul>
    
<p>You are not required to use Bootstrap in this part. You can use if you want, but we actually recommend writing plain CSS. Just for this part, inline CSS is acceptable, but you should generally avoid using inline CSS in the future.</p>
    
<h1>General Notes</h1>
    <p>As a reminder, it's a good idea to run your HTML and CSS syntax through validators You should also consider using an accessibility checker such as WAVE.</p>
    
<h1>Troubleshooting</h1>
    <p>There are hundreds of HTML and CSS tags, properties, and values, and we do not expect students to learn each one by heart. However, this assignment and the first lab are intended for you to intuitively understand the languages, and to be proficient at knowing how to tackle a design by the end of the semester.</p>
    <p>There are hundreds of HTML and CSS tags, properties, and values, and we do not expect students to learn each one by heart. However, this assignment and the first lab are intended for you to intuitively understand the languages, and to be proficient at knowing how to tackle a design by the end of the semester.</p>
    <p>If you're having problems, there are many guides on HTML and CSS online (CSSTricks and MDN are your friends), as well as on our resources page. As always, if you are stuck on a particular part, you can always talk to the friendly TAS or ask questions on course piazza (check your email for a signup link).</p>
    <p><b>As a general rule of thumb, do not expect TAs to be able to solve every web problem you have. Even the most adept web developer can struggle a lot with specific CSS rules to use.</b></p>
    </main>
    <footer id="footer">
<p class="footer1">&copy; 2022 | Muhammad Haris Ahsan.</p>
<a href="" class="footer2">www.harisahsan.com</a>
    </footer>
</body>
</html>
