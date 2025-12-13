-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ０．１ Ｌｉｎｅｓ， Λｎｇｌｅ ｏｆ Ｉｎｃｌｉｎａｔｉｏｎ， ａｎｄ ｔｈｅ Ｄｉｓｔａｎｃｅ Ｆｏｒｍｕｌａ**------------------------------—




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=fYyARMqiaag&t=1). Introduction
     ◉ Review of Math 2 concepts and basic algebra needed for Calculus.
     ◉ Topics to cover:
          ○ Basic lines.
          ○ Families of curves.
          ○ Trigonometric functions.
          ○ Introduction to Calculus.



 Ｌｉｎｅｓ

● [0:34](https://www.youtube.com/watch?v=fYyARMqiaag&t=34). Lines [📷image](../img/Calculus 1 Lecture 0.1/[0-34]-01.png)
     ◉ What is special about a line?
          ○ You need at least two points to define a line.
          ○ Lines do not curve.
          ○ Lines do not end.
          ○ Lines have slope.
     ◉ [1:03](https://www.youtube.com/watch?v=fYyARMqiaag&t=63). What do we need to graph a line?
          ○ Two points or . . .
          ○ . . . One point and the slope
     ◉ [1:10](https://www.youtube.com/watch?v=fYyARMqiaag&t=70). **Slope of a Line**
          ○ The slope describes how a line rises or falls.
          ○ Deriving the slope formula:
               ■ Take two generic points on a line: $(𝒙_1,𝒚_1)$ and $(𝒙_2,𝒚_2)$.
               ■ Coordinates of a point $(𝒙,𝒚)$.
               ■ Distinguishing two points using subscripts.
               ■ Calculating the “run” (change in 𝒙): $𝒙_2-𝒙_1$.
               ■ Calculating the “rise” (change in 𝒚): $𝒚_2-𝒚_1$.
               ■ [3:30](https://www.youtube.com/watch?v=fYyARMqiaag&t=210). Defining the slope $(𝒎)$ as rise over run: 
               $\rule{0pt}{}$
                    ▣ $\boxed{\Large 𝒎=\dfrac{𝒚_2-𝒚_1}{𝒙_2-𝒙_1}}$
                    $\rule{0pt}{}$
                         ▢ The formula works for any pair of points on the line.
     ◉ [5:39](https://www.youtube.com/watch?v=fYyARMqiaag&t=339). **Equation of a Line from the Slope Formula**
           ○ Manipulating the slope formula to get the equation of a line.
           ○ Fix one point $(𝒙_1,𝒚_1)$ and let the other point be variable $(𝒙,𝒚)$.
           $\rule{0pt}{}$
           ○ Substituting into the slope formula: 
           $\rule{0pt}{}$
                ■ $\boxed{\Large 𝒎=\dfrac{𝒚-𝒚_1}{𝒙-𝒙_1}}$
           $\rule{0pt}{}$
           ○ The resulting equation allows solving for 𝒚 when a value for 𝒙 is provided.
           ○ Isolating $(𝒚-𝒚_1)$
           ○ [8:05](https://www.youtube.com/watch?v=fYyARMqiaag&t=485). **Point-Slope Form of a Line’s Equation**
           $\rule{0pt}{}$
                 ■ $\boxed{\Large 𝒚-𝒚_1=𝒎(𝒙-𝒙_1)}$
                 $\rule{0pt}{}$
                 ■ Called point-slope form because you need one point $(𝒙_1,𝒚_1)$ and the slope $(𝒎)$ to define it.
     ◉ [9:40](https://www.youtube.com/watch?v=fYyARMqiaag&t=580). 🧩 Example – Finding a Line’s Equation Given Two Points:  $(-2,-3)$ and $(8,2)$ [📷image](../img/Calculus 1 Lecture 0.1/[9-40]-01.png)
           ○ Necessary steps:
                ■ We need one point (we have two).
                ■ We need the slope (we must calculate it).
           ○ Calculating the slope using the two given points:
           $\rule{0pt}{}$
                 $𝒎=\dfrac{2-(-3)}{8-(-2)}=\dfrac{5}{10}= \dfrac{1}{2}$
                 $\rule{0pt}{}$
           ○ Using the point-slope form to find the equation:
           $\rule{0pt}{}$
                 $𝒚-(-3)=\dfrac{1}{2}(𝒙-(-2))$
                 $\rule{0pt}{}$
                 $𝒚+3=\dfrac{1}{2}(𝒙+2)$
                 $\rule{0pt}{}$
                 $𝒚+3=\dfrac{1}{2}𝒙+1$
                 $\rule{0pt}{}$
                 $𝒚=\dfrac{1}{2}𝒙-2$
                 $\rule{0pt}{}$
           ○ [15:10](https://www.youtube.com/watch?v=fYyARMqiaag&t=910). **Slope-Intercept Form of a Line’s Equation**
                ■ Transforming the point-slope form to slope-intercept form 
                $\rule{0pt}{}$
                     ▣ $\displaystyle \boxed{\Large 𝒚=𝒎𝒙+𝒃}$
                     $\rule{0pt}{}$
                ■ Identifying the slope $(𝒎)$ and the 𝒚-intercept $(𝒃)$.
                ■ 🧩 Example – Graphing using slope-intercept form.
                ■ Interpretation of positive or negative slope.
                ■ Two points define a unique line.
                     ▣ $𝒚=\dfrac{1}{2}𝒙-2$  
                     $\rule{0pt}{}$
                          ▢ $𝒃=-2$ point $(0,-2)$
                          $\rule{0pt}{}$
                          ▢ $𝒎=\dfrac{1}{2}$; from $(0,2)$ one unit up (rise) ⇡ and two units to the right ⇢ (run)
                          $\rule{0pt}{}$
                               ▲ $(-1,2)$ is the second  point
     ◉ [17:24](https://www.youtube.com/watch?v=fYyARMqiaag&t=1044). **Special Types of Lines** [📷image](../img/Calculus 1 Lecture 0.1/[17-24]-01.png)
          ○ [17:46](https://www.youtube.com/watch?v=fYyARMqiaag&t=1066). Horizontal lines: $𝒚=𝒄$ (where 𝒄 is a constant).
               ■ Intersects the 𝒚-axis at 𝒄.
               ■ Slope is zero.
          ○ [18:45](https://www.youtube.com/watch?v=fYyARMqiaag&t=1125). Vertical lines: $𝒙=𝒄$ (where 𝒄 is a constant).
               ■ Intersects the 𝒙-axis at 𝒄.
               ■ Slope is undefined.
     ◉ [19:50](https://www.youtube.com/watch?v=fYyARMqiaag&t=1190). **Standard Form of a Line’s Equation** [📷image](../img/Calculus 1 Lecture 0.1/[21-52]-01.png)
          ○ [21:52](https://www.youtube.com/watch?v=fYyARMqiaag&t=1312). 🧩 Example – Converting from standard form to slope-intercept form by isolating 𝒚: $4𝒙+2𝒚-3=0 \;\to\; 𝒚=𝒎𝒙+𝒃$
               ■ Start from the standard form:
                    ▣ $4𝒙+2𝒚-3=0$
               ■ Move the constant term to the other side:
                    ▣ $4𝒙+2𝒚=3$
               ■ Divide each term by $-2$ to isolate 𝒚:
               $\rule{0pt}{}$
                    ▣ $\dfrac{4𝒙-3}{-2}=-2𝒙+\dfrac{3}{2}=𝒚$
                    $\rule{0pt}{}$
               ■ Final slope–intercept form:
               $\rule{0pt}{}$
                    ▣ $𝒚=-2𝒙+\dfrac{3}{2}$
                         ▢ Here, slope $𝒎=-2$ and intercept $𝒃=\dfrac{3}{2}$
                         $\rule{0pt}{}$
          ○ [22:02](https://www.youtube.com/watch?v=fYyARMqiaag&t=1322). **Cover-Up Method for Graphing from Standard Form**
               ■ To find the 𝒙-intercept, cover the term with 𝒚.
               ■ To find the 𝒚-intercept, cover the term with 𝒙.
               ■ 🧩 Example –: $3𝒙+4𝒚=4$ ($𝒙$-intercept at $\dfrac{4}{3}$, $𝒚$-intercept at $1$).
          ○ [23:02](https://www.youtube.com/watch?v=fYyARMqiaag&t=1382). **Parallel Lines**
               ■ Have the same slope.
               ■ Stair analogy: both rise or fall at the same rate, never intersecting.
                    ▣ Algebraic condition for parallelism:
                         ▢ Two lines $𝑦=𝒎_1𝑥+𝒃_1$ and $𝑦=𝒎_2𝑥+𝒃_2$ are parallel iff $𝒎_1=𝒎_2$ but $𝒃_1\neq𝒃_2$.
                         ▢ Different intercepts $(𝒃_1,𝒃_2)$ shift the lines vertically without changing slope.
               ■ Geometric interpretation: equal slope ⇒ same inclination angle with respect to the 𝒙-axis.
         ○ [23:39](https://www.youtube.com/watch?v=fYyARMqiaag&t=1419). **Perpendicular Lines**
               ■ Intersect at a right angle (90°).
               ■ If one slope is positive, the other is negative.
               ■ Their slopes are negative reciprocals:
                    ▣ Algebraic condition for perpendicularity:
                    $\rule{0pt}{}$
                         ▢ $\displaystyle \boxed{\Large 𝒎_1\cdot𝒎_2=-1}$
                         $\rule{0pt}{}$
                              ▲ Example: if $𝒎_1=2$, then $𝒎_2=-\dfrac{1}{2}$
                              $\rule{0pt}{}$
                    ▣ Special case (vertical and horizontal lines):
                         ▢ A vertical line (undefined slope) and a horizontal line (slope $=0$) are perpendicular even though $𝒎_1\cdot𝒎_2\neq-1$ (since one slope is undefined).
                    ▣ Visual cue: perpendicular lines form a “T” or “L” shape where they intersect.
          ○ [25:24](https://www.youtube.com/watch?v=fYyARMqiaag&t=1524). 🧩 Example – Finding the Equation of a Line Parallel to $2𝒙+3𝒚=12$ passing through $(6,7)$ [📷image](../img/Calculus 1 Lecture 0.1/[25-24]-01.png)
               ■ Identify the slope of the given line (in slope-intercept form):
                   $2𝒙+3𝒚=12$
                   $\rule{0pt}{}$
                   $3𝒚=-2𝒙+12$ 
                   $\rule{0pt}{}$
                   $𝒚=-\dfrac{2}{3}𝒙+4$
               ■ The slope of the parallel line is the same: $𝒎=-\dfrac{2}{3}$
               $\rule{0pt}{}$
               ■ Use the point-slope form with the point $(6,7)$ and the parallel slope:
                   $𝒚-𝒚_1=𝒎(𝒙-𝒙_1)$  
                   $\rule{0pt}{}$
                   $𝒚-7=-\dfrac{2}{3}(𝒙-6)$  
                   $\rule{0pt}{}$
                   $𝒚-7=-\dfrac{2}{3}𝒙+4$  
                   $\rule{0pt}{}$
                   $𝒚=-\dfrac{2}{3}𝒙+11$
                   $\rule{0pt}{}$
          ○ [29:50](https://www.youtube.com/watch?v=fYyARMqiaag&t=1790). 🧩 Example – Finding the Equation of a Line Perpendicular to $2𝒙+3𝒚=12$ passing through $(6,7)$ [📷image](../img/Calculus 1 Lecture 0.1/[29-50]-01.png)
          $\rule{0pt}{}$
               ■ $𝒎=-\dfrac{2}{3} \;\to\; 𝒎=\dfrac{3}{2}$ (negative reciprocals)
               $\rule{0pt}{}$
               ■ Use the point-slope form:
                   $𝒚-𝒚_1=𝒎(𝒙-𝒙_1)$  
                   $\rule{0pt}{}$
                   $𝒚-7=\dfrac{3}{2}(𝒙-6)$  
                   $\rule{0pt}{}$
                   $𝒚-7=\dfrac{3}{2}𝒙-9$  
                   $\rule{0pt}{}$
                   $𝒚=\dfrac{3}{2}𝒙-2$




 Ａｎｇｌｅ ｏｆ Ｉｎｃｌｉｎａｔｉｏｎ

● [32:10](https://www.youtube.com/watch?v=fYyARMqiaag&t=1930). Angle of Inclination [📷image](../img/Calculus 1 Lecture 0.1/[32-10]-01.png)
     ◉ Definition: The angle a line forms with the positive 𝒙-axis.
     ◉ Relationship with change in 𝒙 $(\Delta 𝒙)$ and change in 𝒚 $(\Delta 𝒚)$.
     ◉ Using basic trigonometry on a right triangle formed by the line, $\Delta 𝒙$, and $\Delta 𝒚$.
     ◉ The tangent of the angle of inclination $(𝜃)$ equals the slope $(𝒎)$: 
     $\rule{0pt}{}$
          ○ $\displaystyle \boxed{\Large \tan(𝜃)=\dfrac{\Delta 𝒚}{\Delta 𝒙}=𝒎}$
          $\rule{0pt}{}$
     ◉ If the angle is known, the slope can be found; if the slope is known, the angle can be found.
     ◉ [35:50](https://www.youtube.com/watch?v=fYyARMqiaag&t=2150). 🧩 Example – Finding the Slope Given the Angle of Inclination:  $30^\circ$ or $\dfrac{\pi}{6}$ radians
          ○ Using the formula $𝒎=\tan(𝜃)$.
          $\rule{0pt}{}$
          ○ Calculating $\tan\!\big(\dfrac{\pi}{6}\big)=\dfrac{\sin(\pi/6)}{\cos(\pi/6)}=\dfrac{1/2}{\sqrt{3}/2}=\dfrac{1}{\sqrt{3}}=\dfrac{\sqrt{3}}{3}$
          $\rule{0pt}{}$
     ◉ [39:00](https://www.youtube.com/watch?v=fYyARMqiaag&t=2340). 🧩 Example – Finding the Angle of Inclination Given the Slope: $𝒎=-1$ 
          ○ Using $\tan(𝜃)=𝒎\;\to\;-1=\tan(𝜃)$
          ○ Applying the inverse tangent: $𝜃=\tan^{-1}(-1)$
          ○ Interpreting the inverse tangent: finding the angle whose tangent is $-1$.
          ○ Using the unit circle to find angles where sine and cosine have equal magnitudes but opposite signs:
               ■ $135^\circ$ → Second quadrant  
               ■ $315^\circ$ → Fourth quadrant
     ◉ Importance of practicing these trigonometric concepts.
     ◉ Trigonometry will be used extensively in Calculus.




Ｄｉｓｔａｎｃｅ Ｆｏｒｍｕｌａ

● [44:20](https://www.youtube.com/watch?v=fYyARMqiaag&t=2660). Distance Formula [📷image](../img/Calculus 1 Lecture 0.1/[44-20]-01.png) 
     ◉ Derived using two random points $(𝒙_1,𝒚_1)$ and $(𝒙_2,𝒚_2)$.
     ◉ Forming a right triangle with sides $|𝒙_2-𝒙_1|$ and $|𝒚_2-𝒚_1|$.
     ◉ Applying the Pythagorean Theorem: $𝒅^2=(𝒙_2-𝒙_1)^2+(𝒚_2-𝒚_1)^2$
     ◉ Solving for distance 𝒅: 
     $\rule{0pt}{}$
            ○ $\displaystyle \boxed{\Large 𝒅=\sqrt{(𝒙_2-𝒙_1)^2+(𝒚_2-𝒚_1)^2}}$
            $\rule{0pt}{}$
     ◉ We omit the negative root because distance cannot be negative.
