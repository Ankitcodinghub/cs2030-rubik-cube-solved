# cs2030-rubik-cube-solved
**TO GET THIS SOLUTION VISIT:** [CS2030 Rubik Cube Solved](https://www.ankitcodinghub.com/product/cs2030-rubik-cube-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114513&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2030 Rubik Cube Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem Description

The Rubik’s cube is a three-dimensional combination puzzle that is considered the world’s best-selling toy.

The 3 × 3 rubik’s cube above can be flattened so that all six faces are shown.

Your task is to write a program that reads as input the cube faces, followed by the turns. It then manipulates the cube ny turning the faces clockwise (F/R/U/L/B/D), anti-clockwise (F’/R’/U’/L’/B’/D’) or half-turn (F2/R2/U2/L2/B2/D2). The final cube is then output. As an example, the input

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18

19 20 21 22 23 24 25 26 27

28 29 30 31 32 33 34 35 36

37 38 39 40 41 42 43 44 45

46 47 48 49 50 51 52 53 54

F

R’

U2

will give the output

……541518……

……510504……

……480201……

303336455352101137

131438262306293235

161739272412070809 ……343119……

……404120……

……434421……

……464728……

……495042……

……032225……

Take note of the following assumptions:

Input always begins with a set of 54 values specifying the face values of the 3 × 3 cube in order (top, left, front, right, down, back),

The numbers associated with the cube faces are positive (&gt; 0)

Input turns are valid

This task is divided into several levels. Read through all the levels to see how the different levels are related. You need to complete all levels.

As this lab focuses on the testability of classes and methods, you will need to follow the method signatures strictly and develop the classes and methods in a bottom-up fashion. To minimize state changes, each method should also return a new object.

For this lab, you need to only develop Face.java, Rubik.java and Main.java in the main directory.

Level 1

Since a cube comprises six faces, let’s begin by developing the Face class. The nine values associated with a cube face can be represented using a 3 × 3 array of integers. Each face can also be rotated right or left.

Develop the following methods for the Face class:

Face(int[][] grid): the constructor that takes in the 3 × 3 array of integers

Face rotateRight(): rotates a quarter revolution to the right and returns a new Face

Face rotateLeft(): rotates a quarter revolution to the left and returns a new Face Face rotateHalf(): rotates half a revolution returns a new Face int[][] getGrid(): returns the 3 × 3 integer grid associated with the Face object String toString(): returns a String representing the Face object

/open Face.java

new Face(new int[][]{{1,2,3},{4,5,6},{7,8,9}}).rotateRight()

/exit

can be redirected to jshell using

$ jshell -q &lt; rubik1.jsh jshell&gt; /open Face.java

jshell&gt; new Face(new int[][]{{1,2,3},{4,5,6},{7,8,9}}).rotateRight() $2 ==&gt; 070401

080502 090603 jshell&gt; /exit

Level 2

With the Face class ready, we can proceed to develop the Rubik class. In particular, we would like to orientate the cube to give a different output.

Develop the following methods of the Rubik class:

Rubik(int[][][] grid): the constructor that takes in a three-dimensional (6 × 3 × 3) integer array of six face values.

Rubik viewRight(): orientates the cube to view the right-side and returns a new Rubik object

Rubik viewLeft(): orientates the cube to view the left-side and returns a new Rubik object

Rubik viewUp(): orientates the cube to view the up-side and returns a new Rubik object

Rubik viewDown(): orientates the cube to view the down-side and returns a new Rubik object String toString(): returns a String representing the Rubik object

Test the methods by writing a suitable test class, or using jshell (compile your classes first). As an example, the following script

(say rubik2.jsh)

/open Face.java /open Rubik.java

int[][][] grid = new int[6][3][3] int d = 0; for (int k = 0; k &lt; 6; k++) for (int i = 0; i &lt; 3; i++)

for (int j = 0; j &lt; 3; j++) grid[k][i][j] = ++d; new Rubik(grid).viewRight()

/exit

can be redirected to jshell using

jshell&gt; /open Face.java jshell&gt; /open Rubik.java

jshell&gt; int[][][] grid = new int[6][3][3] jshell&gt; int d = 0;

jshell&gt; for (int k = 0; k &lt; 6; k++) …&gt; for (int i = 0; i &lt; 3; i++)

…&gt; for (int j = 0; j &lt; 3; j++) grid[k][i][j] = ++d; jshell&gt; new Rubik(grid).viewRight()

$6 ==&gt; ……070401……

……080502……

……090603……

192021282930545352

222324313233515049

252627343536484746 ……394245……

……384144……

……374043……

……181716……

……151413…… ……121110……

jshell&gt; /exit

Notice that the right face of the original cube is now facing the front with the corresponding changes to the other faces with respect to the new orientation of the cube.

Level 3

We are now ready to turn the faces. You might think that one needs to implement turns separately for each of the six faces.

However, in this case there is no need to. You need only implement front-face turns. Why? The hint is in the preceding level.

Develop the following additional methods of the Rubik class:

Rubik frontfaceRight(): turns the front face clockwise and returns the new Rubik object

Rubik frontfaceLeft(): turns the front face anti-clockwise and returns the new Rubik object

Rubik frontfaceHalf(): turns the front face half revolution and returns the new Rubik object

Rubik rightfaceRight(): turns the right face clockwise and returns the new Rubik object

Rubik rightfaceLeft(): turns the right face anti-clockwise and returns the new Rubik object

Rubik rightfaceHalf(): turns the right face half revolution and returns the new Rubik object

Rubik leftfaceRight(): turns the left face clockwise and returns the new Rubik object

Rubik leftfaceLeft(): turns the left face anti-clockwise and returns the new Rubik object

Rubik leftfaceHalf(): turns the left face half revolution and returns the new Rubik object

Rubik upfaceRight(): turns the up face clockwise and returns the new Rubik object

Rubik upfaceLeft(): turns the up face anti-clockwise and returns the new Rubik object

Rubik upfaceHalf(): turns the up face half revolution and returns the new Rubik object

Rubik downfaceRight(): turns the down face clockwise and returns the new Rubik object

Rubik downfaceLeft(): turns the down face anti-clockwise and returns the new Rubik object

Rubik downfaceHalf(): turns the down face half revolution and returns the new Rubik object

Rubik backfaceRight(): turns the back face clockwise and returns the new Rubik object

Rubik backfaceLeft(): turns the back face anti-clockwise and returns the new Rubik object

Rubik backfaceHalf(): turns the back face half revolution and returns the new Rubik object

Test the methods by writing a suitable test class, or using jshell (compile your classes first). As an example, the following script

(say rubik3.jsh)

/open Face.java /open Rubik.java

int[][][] grid = new int[6][3][3] int d = 0; for (int k = 0; k &lt; 6; k++) for (int i = 0; i &lt; 3; i++)

for (int j = 0; j &lt; 3; j++) grid[k][i][j] = ++d; new Rubik(grid).upfaceLeft()

/exit

can be redirected to jshell using

jshell&gt; /open Face.java jshell&gt; /open Rubik.java

jshell&gt; int[][][] grid = new int[6][3][3] jshell&gt; int d = 0;

jshell&gt; for (int k = 0; k &lt; 6; k++) …&gt; for (int i = 0; i &lt; 3; i++)

…&gt; for (int j = 0; j &lt; 3; j++) grid[k][i][j] = ++d; jshell&gt; new Rubik(grid).upfaceLeft()

$6 ==&gt; ……030609……

……020508……

……010407……

545352101112192021

131415222324313233

161718252627343536 ……373839……

……404142……

……434445……

……464748……

……495051…… ……302928……

jshell&gt; /exit

Level 4

Include the Main class that reads the Rubik’s cube as input, followed by the turns and output the final Rubik’s cube after all the turns have been made.

The following is a sample run of the program. User input is underlined.

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18

19 20 21 22 23 24 25 26 27

28 29 30 31 32 33 34 35 36

37 38 39 40 41 42 43 44 45

46 47 48 49 50 51 52 53 54

F

R’

U2

……541518……

……510504……

……480201……

303336455352101137

131438262306293235

161739272412070809 ……343119……

……404120……

……434421……

……464728……

……495042……

……032225……

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18

19 20 21 22 23 24 25 26 27

28 29 30 31 32 33 34 35 36

37 38 39 40 41 42 43 44 45

46 47 48 49 50 51 52 53 54

F R U L B D

F’ R’ U’ L’ B’ D’

F2 R2 U2 L2 B2 D2

……281118……

……220508……

……270648……

211539342936452037

401451332344473253

014207192603543143 ……123830……

……354124……

……104916……

……521346……

……175002……

……090425……

Check the format correctness of the output by typing the following Unix command

$ java Main &lt; test4.in | diff – test4.out
