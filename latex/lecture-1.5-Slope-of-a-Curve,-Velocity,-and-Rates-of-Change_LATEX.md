---------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　１．５　Sｌｏｐｅ　Oｆ　ａ　Cｕｒｖｅ，　Vｅｌｏｃｉｔｙ，　ａｎｄ　Rａｔｅｓ　Oｆ　Cｈａｎｇｅ**---------------------------------




Ｔａｎｇｅｎｔ   ｌｉｎｅ   ａｎｄ   ｒａｔｅ   ｏｆ   ｃｈａｎｇｅ

● [0:50](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=50). Introduction.
     ◉ Main objective of calculus: 
          ○ Find the slope of the tangent line to a curve at a point.
               ■ Equivalent statement: Find the slope of a curve at a point.
     ◉ Using limits to find the slope of the tangent line to a curve at a point.
     ◉ Importance of understanding the mathematical concept, not just the formulas.


● [3:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=200). Creating the formula for the slope of a curve from the slope of a secant line (that conect two points).
     ◉ [4:03](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=243). Definitions:  📷[Image](../img/Calculus 1 Lecture 1.5/[4-03]-01.png)
          ○ A curve
          ○ P: a poin to find the slope of a curve at a point P.
          ○ Q: a point to stablish the secant line from P to Q. 
          ○ 𝒙₀: 𝒙 coordinate of P and 𝒙₀ + h 𝒙 coordinate of Q
          ○ h: distance from P to Q
          ○ The idea is take Q really relly really close to P that is the idea of limit.
     ◉ [6:44](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=404). Calculating the 𝒚-values of the points: 𝒇(𝒙₀) and 𝒇(𝒙₀ + h). [📷Image](../img/Calculus 1 Lecture 1.5/[6-44]-01.png)
     ◉ [7:24](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=444). Reminder of the goal: finding the slope of the curve at point P.
     ◉ [8:32](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=512). Calculating the slope of the secant line ($\Delta \mathit{y} / \Delta \mathit{x}$) using points P and Q. 📷[Image](../img/Calculus 1 Lecture 1.5/[8-32]-01.png)
     $\rule{0pt}{}$
          ○  $\Delta \mathit{x}=x_0+h-x_0=h$ and $\Delta \mathit{y}=f(x_0+h)-f(x_0)$
          $\rule{0pt}{}$
               ■ $m=\displaystyle \dfrac{f(x_0+h)-f(x_0)}{h}$
               $\rule{0pt}{}$
     ◉ [14:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=840). Introducing the concept of a limit to bring Q closer to (infinitely smaller) P: this is (h → 0). 📷[Image](../img/Calculus 1 Lecture 1.5/[14-00]-01.png)
          ○ Transition from the slope of the secant (m) to the slope of the tangent ($m_{\text{tan}}$)
              using the limit: 
              $\rule{0pt}{}$
               ■ $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$
               $\rule{0pt}{}$
     ◉ [17:30](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1050). Explanation of why we cannot simply set h = 0 (undefined).


● [18:33](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1113). 🧩 Example 1 – Finding the equation of the tangent line to: 𝒚 = x² at (1, 1) 📷[Image-1](../img/Calculus 1 Lecture 1.5/[18-33]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 1.5/[18-33]-02.png)
     ◉ [19:42](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1182). Steps to find the equation of the tangent line.
          ○ Identification of 𝒇(𝒙) = 𝒙² and x₀ = 1.
          ○ Calculating 𝒇(𝒙₀ + h) = 𝒇(1 + h) = $(1+h)^{2}$.
          ○ Calculating 𝒇(𝒙₀) = 𝒇(1) = $1$.
          $\rule{0pt}{}$
          ○ Take the limit $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$
          $\rule{0pt}{}$
               ■ $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{(1+h)^{2}-1}{h}=\displaystyle \lim_{h\to 0}\dfrac{1+h+2h^{2}-1}{h}                             =\displaystyle \lim_{h\to 0}(2+h)=0$
               $\rule{0pt}{}$
          ○ Hence, the slope of the tangent line is $2$.
          ○ [28:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1700).  Using the point-slope form to find the equation of the tangent line at (1,1).
               ■  $\mathit{y}-y_1=m(x-x_1)$.
               ■ The equation of the tangent line is $\mathit{y}=2x-1$.

                    
● [30:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1855). 🧩 Example 2 – Finding the equation of the tangent line to 𝒚 = 3/x at (3, 1) 📷[Image-1](../img/Calculus 1 Lecture 1.5/[30-55]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 1.5/[30-55]-02.png)
     ◉ Steps to restating the goal and using the formula for the slope of the tangent.
          ○ Identification of 𝒇(𝒙) = $3/x$ and $x_0=3$.
          $\rule{0pt}{}$
          ○ Calculating 𝒇(𝒙₀ + h) = 𝒇(3 + h) = $\dfrac{3}{3+h}$.
          $\rule{0pt}{}$
          ○ Calculating 𝒇(𝒙₀) = 𝒇(3) = $1$.
          $\rule{0pt}{}$
          ○ Take the limit $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$
          $\rule{0pt}{}$
               ■ $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{\dfrac{3}{3+h}-1}{h}=\displaystyle \lim_{h\to 0}\dfrac{-\,h/(3+h)}{h}                             =\displaystyle \lim_{h\to 0}\left(-\dfrac{1}{3+h}\right)=-\dfrac{1}{3}$
               $\rule{0pt}{}$
          ○ Hence, the slope of the tangent line is $-1/3$.
          ○ [41:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=2480). Using the point-slope form to find the equation of the tangent line at (1,1).
               ■  $\mathit{y}-y_1=m(x-x_1)$.
               ■ The equation of the tangent line is $\mathit{y}=-\dfrac{1}{3}x+2$.                  


● [44:57](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=2697). 🧩 Example 3 –  Finding the slope of tangent lines to 𝒚 = √x at any point 📷[Image](../img/Calculus 1 Lecture 1.5/[44-57]-01.png)  
     ◉ Objective: derive a general formula for the slope of the tangent to 𝒚 = √x at any point x.
          ○ Identification of 𝒇(𝒙) = $\sqrt{x}$.
          $\rule{0pt}{}$
          ○ Calculating 𝒇(x + h) = $\sqrt{x+h}$.
          $\rule{0pt}{}$
          ○ Take the limit $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$
          $\rule{0pt}{}$
               ■ $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{\sqrt{x+h}-\sqrt{x}}{h}$
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{h\to 0}\dfrac{(x+h)-x}{h\cdot\big(\sqrt{x+h}+\sqrt{x}\big)}$       multiplicate by de conjugat $\dfrac{\sqrt{x+h}+\sqrt{x}}{\sqrt{x+h}+\sqrt{x}}$
                             $\rule{0pt}{}$
               ■ $\displaystyle \lim_{h\to 0}\dfrac{1}{\sqrt{x+h}+\sqrt{x}}=\dfrac{1}{2\sqrt{x}}$
          ○ Hence, the slope of the tangent line 𝐚𝐭 𝐚𝐧𝐲 𝐩𝐨𝐢𝐧𝐭 is  $\dfrac{1}{2\sqrt{x}}$
          ○ [55:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3300). Obtaining the general formula for the slope of the tangent: $m=\dfrac{1}{2\sqrt{x}}$.
               ■ Explanation that this formula allows computing the slope at any point on the curve.
          ○ [57:35](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3455). Sharp point:
               ■ At a sharp point on a curve, 𝘁͟𝗵͟𝗲͟ ͟𝘀͟𝗹͟𝗼͟𝗽͟𝗲͟𝘀͟ ͟𝗳͟𝗿͟𝗼͟𝗺͟ ͟𝘁͟𝗵͟𝗲͟ ͟𝗹͟𝗲͟𝗳͟𝘁͟ ͟𝗮͟𝗻͟𝗱͟ ͟𝗿͟𝗶͟𝗴͟𝗵͟𝘁͟ ͟𝘀͟𝗶͟𝗱͟𝗲͟𝘀͟ ͟𝗮͟𝗿͟𝗲͟ ͟𝗱͟𝗶͟𝗳͟𝗳͟𝗲͟𝗿͟𝗲͟𝗻͟𝘁͟. This discrepancy 
                  causes the limit defining the tangent slope ($m_{\text{tan}}$) to fail, as it does not exist uniquely. Consequently,
                  an infinite number of tangent lines with varying slopes can be drawn through that sharp point.





Ａｐｐｌｉｃａｔｉｏｎｓ   of   Ａｖｅｒａｇｅ   ａｎｄ   ｉｎｓｔａｎｔａｎｅｏｕｓ   ｖｅｌｏｃｉｔｙ

● [58:54](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3534). Introduction to applications.
     ◉ 𝗔̳𝘃̳𝗲̳𝗿̳𝗮̳𝗴̳𝗲̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ ($V_{\text{ave}}$) corresponds to the slope of the secant line between two points, calculated as:
     $\rule{0pt}{}$
          ○ $m_{\text{secant}}=\displaystyle \dfrac{f(x_0+h)-f(x_0)}{h}$
                                      $\rule{0pt}{}$
     ◉ 𝗜̳𝗻̳𝘀̳𝘁̳𝗮̳𝗻̳𝘁̳𝗮̳𝗻̳𝗲̳𝗼̳𝘂̳𝘀̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ ($V_{\text{inst}}$)  matches the slope of the tangent line at a single point, given by:
     $\rule{0pt}{}$
          ○ $m_{\text{tan}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$

               
● [59:03](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3543). 𝗔̳𝘃̳𝗲̳𝗿̳𝗮̳𝗴̳𝗲̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳
     ◉ Distance traveled over elapsed time.
$\rule{0pt}{}$
          ○ $V_{\text{ave}}=$ displacement / time $=\displaystyle \dfrac{f(t_0+h)-f(t_0)}{h}$  
     ◉[1:01:26](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3686). Relationship between the average velocity formula and the slope formula.
          ○ Both formulas represent the slope between two points.
          ○ Average velocity is the slope of the secant line on a position vs. time graph.           
     ◉[1:02:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3740). 🧩  Example: Finding average velocity of $s(t)=1+3t-2t^{2}$ over the interval [1,3] 📷[Image](../img/Calculus 1 Lecture 1.5/[1-02-20]-01.png)
          ○ Identification of $t_0=1$ and $h=2$.
          ○ Calculating $s(t_0+h)=s(3)=-8$.
          ○ Calculating $s(t_0)=s(1)=2$.
     $\rule{0pt}{}$
          ○ Computing the average velocity: $\displaystyle \dfrac{s(3)-s(1)}{2}=\dfrac{-8-2}{2}=-5$.           
     ◉[1:08:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4135). Introduction to the difference between velocity and speed.
          ○ Average Velocity:
               ■ Type: Vector
               ■ Includes: Direction and magnitude
               ■ Use:Indicates the overall change in position over time, providing information about both the rate of displacement and the   direction.
          ○ Speed:
               ■ Type: Scalar
               ■ Includes: Only magnitude
               ■ Use: Measures the total distance traveled over a period of time without regard to direction.

                      
● [1:10:02](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4202). 𝗜̳𝗻̳𝘀̳𝘁̳𝗮̳𝗻̳𝘁̳𝗮̳𝗻̳𝗲̳𝗼̳𝘂̳𝘀̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ 📷[Image](../img/Calculus 1 Lecture 1.5/[1-10-02]-01.png)
     ◉ Velocity at a specific instant in time.
          ○ [1:11:25](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4285). 𝙃𝙤𝙬 𝙢𝙪𝙘𝙝 𝙩𝙞𝙢𝙚 𝙚𝙡𝙖𝙥𝙨𝙚𝙨 𝙞𝙣 𝙖𝙣 𝙞𝙣𝙨𝙩𝙖𝙣𝙩?           
     ◉[1:12:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4375). Instantaneous velocity is found by letting h approach zero in the average velocity formula.
          ○ [1:13:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4403). This involves using a limit.
               ■ How we make average velocity instant?
          $\rule{0pt}{}$
                     ▣ $\displaystyle \lim_{h\to 0}\dfrac{f(t_0+h)-f(t_0)}{h}$; $h=$ time                      
     ◉[1:14:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4460). Relationship between instantaneous velocity and the slope of a curve at a point.
          ○ Both represent the instantaneous rate of change.           
     ◉[1:15:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4523). 🧩 Example: Finding instantaneous velocity of $s(t)=500-16t^{2}$ after 5 seconds.  📷[Image-1](../img/Calculus 1 Lecture 1.5/[1-15-23]-02.png)  📷[Image-2](../img/Calculus 1 Lecture 1.5/[1-15-23]-01.png)
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{h\to 0}\dfrac{s(t_0+h)-s(t_0)}{h}$
     $\rule{0pt}{}$
          ○ Identification of $t_0=5$.
          ○ Calculating $s(t_0+h)=s(5+h)=500-16(5+h)^{2}$.
          ○ Calculating $s(t_0)=s(5)=100$.
          ○ [1:27:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5220). Substituting into the instantaneous velocity formula and simplifying.
               ■ Take the limit 
          $\rule{0pt}{}$
                    ▣ $\displaystyle \lim_{h\to 0}\dfrac{s(t_0+h)-s(t_0)}{h}=V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{500-16(25+10h+h^{2})-100}{h}$
                 $\rule{0pt}{}$
               ■ Simplify the expression:
          $\rule{0pt}{}$
                    ▣ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{500-400-160h-16h^{2}-100}{h}$
                 $\rule{0pt}{}$
                    ▣ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{-160h-16h^{2}}{h}$
                 $\rule{0pt}{}$
               ■ Cancel the common factor of $h$:
          $\rule{0pt}{}$
                    ▣ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\big(-160-16h\big)$
                 $\rule{0pt}{}$
               ■ Evaluate the limit as $h$ approaches $0$:
          $\rule{0pt}{}$
                    ▣ $V_{\text{inst}}=-160\ \text{ft/sec}$                 $\rule{0pt}{}$
     ◉ [1:32:37](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5550). Computing the instantaneous velocity in general (for any time $t$ so  ̵t̵₀̵ ̵=̵ ̵5̵)  and obtaining the formula: $v(t)=-32t$. 📷[Image-3](../img/Calculus 1 Lecture 1.5/[1-15-23]-03.png)
          ○ Set up the formula for instantaneous velocity:
          $\rule{0pt}{}$
               ■ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{s(T+h)-s(T)}{h}$
               $\rule{0pt}{}$
          ○ Substitute the given position functions:
          $\rule{0pt}{}$
               ■ $s(T+h)=500-16(T+h)^{2}$
               ■ $s(T)=500-16T^{2}$
               $\rule{0pt}{}$
          ○ Substitute the expressions:
          $\rule{0pt}{}$
               ■ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{500-16(T^{2}+2Th+h^{2})-(500-16T^{2})}{h}$
               $\rule{0pt}{}$
          ○ Expand and simplify:
          $\rule{0pt}{}$
               ■ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{500-16T^{2}-32Th-16h^{2}-500+16T^{2}}{h}$
              $\rule{0pt}{}$
          ○ Cancel common terms:
          $\rule{0pt}{}$
               ■ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{-32Th-16h^{2}}{h}$
              $\rule{0pt}{}$
          ○ Factor out the common term $(h)$:
          $\rule{0pt}{}$
               ■ $V_{\text{inst}}=\displaystyle \lim_{h\to 0}\big(-32T-16h\big)$
              $\rule{0pt}{}$
          ○ Evaluate the limit as $h$ approaches $0$:
               ■ $V_{\text{inst}}=-32T$
          ○ Substitute $T=5$ seconds:
               ■ $V_{\text{inst}}=-32(5)$
               ■ $V_{\text{inst}}=-160\ \text{ft/sec}$
     ◉ [1:38:29](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5909). Explanation of the difference between velocity and speed.
          ○ Speed is the absolute value of velocity.
                     




Ａｖｅｒａｇｅ   ａｎｄ   Ｉｎｓｔａｎｔａｎｅｏｕｓ   ｒａｔｅ   ｏｆ   ｃｈａｎｇｅ

●[1:39:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5963). Connection between slope and rate of change.
     ◉ The slope is a rate of change.

         
●[1:39:59](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5999). The average rate of change is the slope of the secant line between two points.


●[1:41:58](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6118). The instantaneous rate of change is the slope of the curve at one point.


●[1:43:10](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6190). Rate of change:
     ◉ Average rate of change: 
     $\rule{0pt}{}$
          ○ $r_{\text{av}}=\displaystyle \dfrac{f(x_0+h)-f(x_0)}{h}$
     $\rule{0pt}{}$
     ◉ instantaneous rate of change:
     $\rule{0pt}{}$
          ○ $r_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$ 

           
●[1:46:37](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6397). 🧩 Example: Finding the average and instantaneous rate of change of a curve  𝒇(𝒙) = 3𝒙² - 4, r_ave:[2,5] and  r_inst:-2
$\rule{0pt}{}$
     ◉ Average rate of change: $r_{\text{av}}=\displaystyle \dfrac{f(x_0+h)-f(x_0)}{h}$
     $\rule{0pt}{}$
          ○ $f(x_0)=f(2)$ 
          $\rule{0pt}{}$
          ○ $f(x_0+h)=f\big(2+(5-2)\big)=f(5)$ 
          $\rule{0pt}{}$
          ○ $r_{\text{av}}=\displaystyle \dfrac{f(x_0+h)-f(x_0)}{h}=\dfrac{f(5)-f(2)}{3}=\dfrac{63}{3}=21$
          $\rule{0pt}{}$
          $\rule{0pt}{}$
     ◉ instantaneous rate of change: $r_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{f(x_0+h)-f(x_0)}{h}$ 
     $\rule{0pt}{}$
          ○ $f(x_0)=3x_0^{2}-4$ 
          $\rule{0pt}{}$
          ○ $f(x_0+h)=f\big(3(x_0+h)^{2}-4\big)=3x_0^{2}+6x_0h+h^{2}-4$
          $\rule{0pt}{}$
          ○ $r_{\text{inst}}=\displaystyle \lim_{h\to 0}\dfrac{\big(3x_0^{2}+6x_0h+h^{2}-4\big)-\big(3x_0^{2}-4\big)}{h}=\displaystyle \lim_{h\to 0}\dfrac{6x_0h+h^{2}}{h}                       =\displaystyle \lim_{h\to 0}\big(6x_0+h\big)=6x_0$
          $\rule{0pt}{}$
          ○ $r_{\text{inst}\_\!x_0:-2}=-12$
