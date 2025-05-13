# csci-3070u--analysis-and-design-of-algorithms-assignment--3-solved
**TO GET THIS SOLUTION VISIT:** [CSCI 3070U -Analysis and Design of Algorithms Assignment- #3 Solved](https://www.ankitcodinghub.com/product/csci-3070u-analysis-and-design-of-algorithms-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;71311&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI 3070U&nbsp;-Analysis and Design of Algorithms  Assignment- #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

&nbsp;

<strong>Topic:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>Linear sorting, greedy algorithms

<strong>&nbsp;</strong>

<h1>Part 1</h1>
For this part of the assignment, you will implement a radix sort procedure for sorting numbers between 0 (inclusive) and 1,000,000 (exclusive) (i.e. 6-digit numbers).&nbsp; Your procedure will use a modified version the counting sort implementation that you developed in tutorial #5 in order to sort by each digit (modified to sort by digit, of course).

&nbsp;

You may find the following code (which determines the value of an arbitrary digit) useful:

&nbsp;

function getDigit(num, digit) {

working = num / 10<sup>digit-1</sup>;

return workingmod 10;

}

<h1>Part 2</h1>
Write a greedy algorithm to solve the fractional knapsack problem, as described below:

&nbsp;

Given a number of items with weight and value, select a percentage (0.0-1.0) for each item(s) to include in your knapsack such that the weight capacity (W) of the knapsack is not exceeded, and the total value (V, the sum of the value of all included items) is maximal.

&nbsp;

One way that you could implement this problem is to pass 2 arrays into your procedure:&nbsp; 1) weights, where weights[i] is the weight of element i, and 2) values, where values[i] is the value of element i.

<h1>Part 3</h1>
Write an implementation of Huffman coding, which is a greedy implementation of assigning prefix codes.&nbsp; This will require a program that does the following:

<ol>
<li>Read through a simple ASCII text file (passed as an argument), determining the frequency of each character in the file</li>
<li>Use these frequencies to calculate the optimal prefix codes for each character (Huffman)
<ul>
<li>Print a complete table of prefix codes for the characters in the document (print only characters with frequencies &gt; 0)</li>
</ul>
</li>
<li>Normally, you would then encode each character using its prefix code
<ul>
<li>However, actually implementing this requires some trick bit manipulation (which, for some languages, is difficult to do)</li>
<li>Instead, calculate the length of the entire document before and after using the prefix codes</li>
</ul>
</li>
</ol>
&nbsp;
