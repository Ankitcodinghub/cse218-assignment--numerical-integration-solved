# cse218-assignment--numerical-integration-solved
**TO GET THIS SOLUTION VISIT:** [CSE218 Assignment -Numerical Integration Solved](https://www.ankitcodinghub.com/product/cse218-assignment-numerical-integration-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96872&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE218 Assignment -Numerical Integration Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<h1></h1>
<h2>Assignment</h2>
In this assignment, you will implement the following numerical integration methods:

<ol>
<li>Trapezoidal rule</li>
<li>Simpson’s 1/3 rule</li>
<li>Simpson’s 3/8 rule</li>
</ol>
<h2>Input file specifications</h2>
The input file will start with N, an integer, indicating how many data points are there. Next follows 2*N floating point numbers. The first floating point number indicates value of x, the second indicates f(x). x and f(x) both can be negative. A sample input file is:

10

0 0

1.5 6.2

…

…

11.8 20

&nbsp;

Therefore, from input, you know x’s and f(x)’s. You have to determine the following integral using numerical integration methods stated before.

The x’s in the input file will be sorted from minimum to maximum.

&nbsp;

<h2>Output requirements</h2>
You can write the output in file or in console. First, you should output the following:

Trapezoidal rule: x intervals

1/3 rule: y intervals

3/8 rule: z intervals

&nbsp;

Here, x denotes the number of intervals that were integrated using Trapeziodal rule and so on. (You should readily see why x, y and z should sum to N-1.)

&nbsp;

Next, you should print the value of the integral.

&nbsp;

<h2>Plotting</h2>
Your program should also generate a graph where the data points are shown. The intervals should be annotated properly to show in which of the three methods you integrated that interval. (There should be x intervals annotated with Trapezoid, y intervals with 1/3 rule and z intervals with 3/8 rule).

&nbsp;

<h2>Instructions</h2>
There are N-1 intervals. Your program should first decide consecutive equally spaced intervals. Say you have 5 consecutive intervals that are of the same width. Next, you have to determine which interval will be integrated using which methods. In this case, you can integrate all five using Trapezoidal rule. However, that will produce a large error and you will not score high marks. You can also integrate these five intervals using two 1/3 and one trapezoid. This will surely have less error than the previous, but the most accurate would be to use one 3/8 and one 1/3 rule. You have to figure out an algorithmic way to determine which interval(s) will be integrated with which rule(s).

&nbsp;

Note that your program should pick Simpson’s rule over the Trapezoidal whenever possible, since that will result in more accurate approximation of the integral. You must use multiple application of these rules whenever necessary.

&nbsp;

<h2>Plagiarism and surfing the Internet</h2>
Be cautious when copying someone’s code, even if it is not your batch-mate. Plagiarism means taking credit for something without doing it yourself, which includes copying Internet code as well. If you copy something from the Internet and or from someone else, you will be convicted of copying and <strong><em>will be penalized a negative 100% marks.</em></strong> Usually these copy checks are made at the end of the term. If you are feeling happy that you escaped copy-check is Assignments 2 and 3, don’t fool yourself. Copy check will be made and you will get caught.

&nbsp;
