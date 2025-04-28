# csci406-project-2--trebuchet-problem-solved
**TO GET THIS SOLUTION VISIT:** [CSCI406 Project 2- Trebuchet Problem Solved](https://www.ankitcodinghub.com/product/csci406-algorithms-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117021&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI406 Project 2- Trebuchet Problem Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Dynamic Programming Project (100 pts) Trebuchet Problem

1 Problem Description

1.1 Introduction

The trebuchet problem discussed in class and on the supplemental handout is briefly defined as follows: Given t targets at 1-meter intervals and p pumpkins to be thrown via trebuchet, what is the worst-case minimum number of throws necessary to determine the maximum distance a pumpkin can be thrown without shattering on impact?

.

1.2 Recurrence Relation

Recall from the handout that the recurrence relation for the trebuchet problem is:



Base Cases: T(p,1) = 1

T(1,t) = t

2 Deliverables

Please submit all of the items requested below in a single PDF file on Canvas.

1. [20] Write a recursive algorithm to solve the problem for p = 3, t = 16. Don’t use any shortcuts (i.e. there should be a for-loop from 1 to t). Including the initial call, how many calls are made to the function? Include your code in the report.

2. [10] Run the code from the previous algorithm on a few combinations of p and t to characterize the growth in runtime as p and/or t increase. Provide a table or plot of your results and discuss.

1

3. [20] Implement a dynamic programming algorithm (that uses a table to avoid recomputation) to compute the minimum throws necessary. Include code in your report.

4. [10] Run the code from the previous algorithm on a few combinations of p and t to characterize the growth in runtime as p and/or t increase. Provide a table or plot of your results and discuss.

5. [10] Implement a traceback step that identifies which targets are attempted and what the result is (shattered or survived). Recall that the algorithm should be finding the outcome for the worst-case. Include code in your report. For consistency with our solutions, if there are multiple targets that can be attempted which result in the same outcome for the minimum number of throws, choose the target that is closer. Additionally, if at that target, the minimum number of throws is the same regardless of if the pumpkin shatters or survives, opt for it to shatter.

6. [20] Demonstrate that your code works correctly by showing its results on the following instance: p = 5, t = 100.

Output Format

The output consists of two lines:

• The first line prints minimum number of throws necessary to find the maximum distance.

• The second line prints the targets attempted in the order in which they were attempted. If the pumpkin shatters at a target, make the target number negative.

For the example p = 2, t = 4, the output could look like:

3

1 3 4

While there is only one correct solution of 3 necessary throws, there are multiple ways to get there. Use the guidelines in Deliverable #5 in deciding which targets to attempt.

7. Verification: you don’t need to turn in this part, just do the Canvas quiz.

[10] Demonstrate that your code works for larger values of p and t by correctly showing the results for the input on the Canvas quiz.

2
