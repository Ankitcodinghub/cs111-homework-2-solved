# cs111-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CS111 Homework 2 Solved](https://www.ankitcodinghub.com/product/cs111-submit-your-paper-as-one-pdf-file-and-tell-gradescope-which-pages-each-problem-is-on-if-you-worked-with-a-partner-you-must-each-turn-in-your-own-homework-paper-and-report-the-name-and-pe/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115126&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS111 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Consider the permutation matrix

 0

P =  0

 0

1 1

0

0

0 0

0

1

0 0 

1 

0 .

0

1.1. Find a 4-permutation v = [ something ] such that A[v,:] == P @ A holds for every 4-by-4 matrix A. Test your answer by running a few lines of Python, and include the code and output from your testing in your LaTeX writeup.

1.2. For the same P, find a 4-permutation w = [ something ] such that A[:,w] == A @ P holds for every 4-by-4 matrix A. Turn in your testing for your answer.

2. The routine Lsolve() is in the file cs111/LU.py. It is called as y = Lsolve(L, b), where L must be unit lower triangular, that is, a square, lower triangular matrix whose diagonal is all ones. Modify Lsolve() to take an optional third keyword argument unit diag that defaults to True. If unit diag is False, your modified routine should not require (or assert) that the diagonal is all ones, but instead it should do the necessary arithmetic to get the right answer to Ly = b for any nonsingular lower triangular matrix L. Test your answer, both by itself and with LUsolve(), and include a screenshot of your testing along with your code as part of your LaTeX writeup.

3. Write Usolve(), analogous to Lsolve() in the file cs111/LU.py, to solve an upper triangular system Ux = y. You should again include an optional argument unit diag, as in problem (2), but this time its default should be False. Test your answer, both by itself and with LUsolve(), and include a screenshot of your testing along with your code as part of your LaTeX writeup. Hint: Loops can be run backward in Python, say from n − 1 down to 0, by writing

for i in reversed(range(n)):

4. Suppose that A is a nonsymmetric invertible matrix, b is a vector, and that you have called

L, U, p = cs111.LUfactor(A).

Now suppose you want to solve the system ATx = b (not Ax = b) for x. Show how to do this using only calls to Lsolve() and Usolve() (as modified in problems (2) and (3)).

1
