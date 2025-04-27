# lab-2---classes-solved
**TO GET THIS SOLUTION VISIT:** [Lab 2 – Classes Solved](https://www.ankitcodinghub.com/product/lab-2-classes-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;10663&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Lab 2 – Classes Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<h1>Overview</h1>
The purpose of this assignment is give you some experience writing classes in C++, the various special functions they make use of (such as copy constructors, assignment operators, and destructors), as well as and introduction dynamically allocating memory within those classes.

<h1>Description</h1>
This program will represent a hypothetical car dealership, which consists of showrooms that contain the vehicles for sale. To that end, there are three classes you will be writing:

<ul>
<li>Vehicle</li>
<li>Showroom</li>
<li>Dealership</li>
</ul>
For this assignment, main.cpp will be provided for you, so you don’t have to worry about the structure of the program. Instead, you can focus solely on the structure of the classes and their interactions.

<h2>Vehicle</h2>
The Vehicle class is the basic container of this assignment. You will need to store the following data:

<ul>
<li>The make of the vehicle (such as Mazda, Toyota, etc)</li>
<li>The model of the vehicle (such as Mustang, Model S, F-150, etc)</li>
<li>The year</li>
<li>The price</li>
<li>How many miles does the vehicle have on it?</li>
</ul>
In addition to a constructor which takes in the necessary information, you will also need the following functions defined. You will also want to define a destructor, just to print out when that destructor is called (this is so you can get familiar with that concept).

&nbsp;

<h2>Showroom</h2>
The Showroom class is a bit more sophisticated. Its purpose is to store an array of Vehicle objects. Each Showroom that you create could have a different number of Vehicles, so you will have to use dynamic memory allocation in this case. Your Showroom should contain variables for the following:

<ul>
<li>The name of the Showroom</li>
<li>A pointer to the array of Vehicles, and because pointers don’t have any addition info on their own…</li>
<li>A maximum capacity of the array</li>
<li>A count of how many Vehicles you currently have</li>
</ul>
In addition, you should create the following functions (plus the special functions—a copy constructor, assignment operator, and destructor):

&nbsp;

<h2>Dealership</h2>
The Dealership class in some ways is very similar to the Showroom. It will store a dynamic array, this time of Showroom objects. It will also need a name and ways to keep track of how many Showrooms it can store, versus how many it is currently storing.

Based on the layout of main.cpp (and the test output), you will also need a way to print everything in its inventory (which consists of Showrooms which consist of Vehicles), but also a way to get the average price of each vehicle.

Be sure to define the big three as well.

<h1>Tips</h1>
A few tips about this assignment:

<ul>
<li>Remember the “Big Three” or the “Rule of Three” o If you define one of the three special functions (copy constructor, assignment operator, or destructor), you should define the other two</li>
<li>You can print out a tab character (the escape sequence ‘\t’ ) to help line up the output.</li>
<li>Don’t try to tackle everything all at once. Work on one class at a time. Can’t have a Showroom without a Vehicle…</li>
<li>You can customize the way numbers are displayed in C++ (particularly floating-point numbers).</li>
</ul>
The header file &lt;iomanip&gt; contains this functionality. Look into std::fixed and std::setprecision()

<ul>
<li>Refer back to the recommended chapters in your textbook as well as lecture videos for an explanation of the details of dynamic memory allocation o There are a lot of things to remember when memory allocation</li>
</ul>
