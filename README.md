# comp90038-tutorial-week-12-solved
**TO GET THIS SOLUTION VISIT:** [COMP90038 Tutorial Week 12 Solved](https://www.ankitcodinghub.com/product/comp90038-algorithms-and-complexity-tutorial-week-12-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120063&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90038  Tutorial Week 12 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Plan

Sadly this is the last tutorial session; but at least there is still the exam to look forward to. You will find a list of examinable topics on the LMS, under “exam information” page. We will also make the front page of the exam paper available, for a sneak preview.

The exercises

79. Floyd’s algorithm sometimes works even if we allow negative weights in a dag.

For example, for the left graph above, it will produce these successive distance matrices:

What happens for the right graph above? What do D0, D1 and D2 look like? Explain why D2 ends up giving an incorrect result in this case (but not in the previous case).

80. We are given a sequence of “connection points” spaced out evenly along a straight line. There are n white, and n black points, in some (random) order.

The points are spaced out evenly, so that the distance between two adjacent points is 1.

The points need to be connected, so that each white point is connected to exactly one black point and vice versa. However, the total length of wire used must be kept as small as possible.

Consider the following (greedy) algorithm to solve the problem:

k ← 1

while there are still unconnected points do create all possible connections of length k

k ← k + 1

81. Recall the definition of the knapsack problem. Given a set of items S = {i1,i2,…in} with

• weights: w(i1),w(i2),…,w(in)

• values: v(i1),v(i2),…,v(in)

and a knapsack of capacity W, find the most valuable selection of items that will fit in the knapsack. That is, find a set I ⊆ S such that ∑i∈I w(i) ≤ W and so that ∑i∈I v(i) is maximised.

Define the benefit of an item i to be the rational number v(i)/w(i). Consider the following greedy approach to the problem:

Let A[1]…A[n] hold the items from S, in decreasing order of benefit

val ← 0

weight ← 0

k ← 1

while k ≤ n ∧ weight + w(A[k]) ≤ W do select A[k] val ← val + v(A[k]) weight ← weight + w(A[k])

k ← k + 1

That is, at each step, from the remaining items we simply pick the one that has the greatest benefit. Give a simple example to show that this greedy algorithm does not solve the knapsack problem.

82. Work through Prim’s algorithm for the graph below. Assume the algorithm starts by selecting node a. Which edges are selected for the minimum spanning tree, and in which order?

2

1

83. Use Dijkstra’s algorithm to find the shortest paths for node e in the previous question’s graph. That is, run the algorithm to determine the length of the shortest path from e to v, for all seven nodes v. Is the shortest path from e to b part of the graph’s minimum spanning tree?

a b d e g i l m n s ␣ 6 1 3 2 1 3 6 1 5 3 6

How many bits are required for the encoded string?
