# cse4020-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [CSE4020 Lab 6 Solved](https://www.ankitcodinghub.com/product/cse4020-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91691&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4020 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

1. Write your own myLookAt() and myFrustum() functions (of the following form) that behaves exactly same as gluLookAt() and glFrustum().

A.

<ol start="2">
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Code skeleton</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
def myLookAt(eye, at, up): # eye, at, up are 1D numpy array of length 3

</div>
</div>
<div class="layoutArea">
<div class="column">
def myFrustum(left, right, bottom, top, near, far):

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
def render():

</div>
</div>
<div class="layoutArea">
<div class="column">
glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT)

</div>
</div>
<div class="layoutArea">
<div class="column">
glEnable(GL_DEPTH_TEST)

</div>
</div>
<div class="layoutArea">
<div class="column">
glPolygonMode( GL_FRONT_AND_BACK, GL_LINE )

</div>
</div>
<div class="layoutArea">
<div class="column">
glLoadIdentity()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>myFrustum(-1,1, -1,1, 1,10)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
myLookAt(np.array([5,3,5]), np.array([1,1,-1]), np.array([0,1,0]))

</div>
</div>
<div class="layoutArea">
<div class="column">
# Above two lines must behave exactly same as the below two lines

drawFrame()

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>#glFrustum(-1,1, -1,1, 1,10)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>#gluLookAt(5,3,5, 1,1,-1, 0,1,0)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
glColor3ub(255, 255, 255)

</div>
</div>
<div class="layoutArea">
<div class="column">
drawCubeArray()

</div>
</div>
<div class="layoutArea">
<div class="column">
def myFrustum(left, right, bottom, top, near, far):

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># implement here
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
def myLookAt(eye, at, up):

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># implement here
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
D.

E.

F.

</div>
<div class="column">
Find code for drawFrame(), drawCubeArray() from 6-Viewing &amp; Projection2 &amp; mesh slides.

DO NOT use gluLookAt() inside myLookAt() and glFrustum() inside myFrustum()!

Your program should render the following scene:

</div>
</div>
<div class="layoutArea">
<div class="column">
i.

G. Hint:

<ol>
<li>To implement myLookAt(), see lecture slide 5-reference-viewing. To implement myFrustum(), see lab slide 6-Viewing &amp; Projection2, mesh .</li>
<li>l2 norm of v : ||v|| = np.sqrt( np.dot(v, v) )</li>
<li>a x b (cross product) : np.cross(a, b)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>a 􏱃 b (inner product) : np.dot(a, b) or a@b</li>
<li>Use glMultMatrixf() to multiply your projection matrix and viewing matrix to the
current transformation matrix.
</li>
</ol>
H. Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)

2. Write down a Python program to draw following cube (􏰸􏱄􏱅􏱆) by using indexed squares representation and glDrawElements().

</div>
</div>
<div class="layoutArea">
<div class="column">
1.51.51.5

6

15015 .

C. Start from the code in 6-Viewing &amp; Projection2 &amp; mesh slides. Make sure camera

􏰆􏰚􏰂􏰓􏰠􏰐􏰕􏰚􏰃􏰓􏰘􏰂 􏰈􏰗􏰘􏰌􏰃􏰛􏰐􏰃􏰈 􏰧􏰣􏰜􏰢 􏰧􏰼􏰜􏰢 􏰧􏰡􏰜􏰢 􏰧􏰪􏰜 􏰪􏰘􏰌􏰝􏰫 􏰲􏱇􏰘􏰂􏰜􏰃 􏰂􏰖􏰖􏰊 􏰃􏰘 􏰛􏰚􏰌􏰖 􏰚􏰍􏰘􏰐􏰃 􏰓􏰂􏰓􏰃􏰓􏰚􏰕 􏰅􏰓􏰖􏰪 􏰚􏰂􏰔􏰕􏰖􏱁

<ol start="4">
<li>Set the window title to your student ID and the window size to (480,480).</li>
<li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
0 1.5 1.5

001.5

</div>
<div class="column">
01.jo 4

0

</div>
<div class="column">
71.5.150

3

</div>
</div>
<div class="layoutArea">
<div class="column">
A.

B. Length of each line is 1.5

</div>
</div>
<div class="layoutArea">
<div class="column">
I

</div>
<div class="column">
000

</div>
</div>
<div class="layoutArea">
<div class="column">
1.50

</div>
<div class="column">
0.

</div>
</div>
</div>
