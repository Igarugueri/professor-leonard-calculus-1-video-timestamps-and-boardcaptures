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
     ◉ [8:32](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=512). Calculating the slope of the secant line (Δ𝒚 / Δ𝒙) using points P and Q. 📷[Image](../img/Calculus 1 Lecture 1.5/[8-32]-01.png)
          ○  Δ𝒙 = 𝒙₀ + h - 𝒙₀ = h and   Δ𝒚 = 𝒇(𝒙₀ + h)  - 𝒇(𝒙₀)
               ■ m =  (𝒇(𝒙₀ + h)  - 𝒇(𝒙₀))  /  h
     ◉ [14:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=840). Introducing the concept of a limit to bring Q closer to (infinitely smaller) P: this is (h → 0). 📷[Image](../img/Calculus 1 Lecture 1.5/[14-00]-01.png)
          ○ Transition from the slope of the secant (m) to the slope of the tangent (m_tan)
              using the limit: 
               ■ m_tan = limₕ→₀ (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  /  h
     ◉ [17:30](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1050). Explanation of why we cannot simply set h = 0 (undefined).

● [18:33](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1113). 🧩 Example 1 – Finding the equation of the tangent line to: 𝒚 = x² at (1, 1) 📷[Image-1](../img/Calculus 1 Lecture 1.5/[18-33]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 1.5/[18-33]-02.png)
     ◉ [19:42](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1182). Steps to find the equation of the tangent line.
          ○ Identification of 𝒇(𝒙) = 𝒙² and x₀ = 1.
          ○ Calculating 𝒇(𝒙₀ + h) = 𝒇(1 + h) = (1 + h)².
          ○ Calculating 𝒇(𝒙₀) = 𝒇(1) = 1.
          ○ Take the limit m_tan = limₕ→₀  (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  /  h 
               ■ m_tan = limₕ→₀  ((1 + h)²- 1)  /  h  
                             = limₕ→₀ (1 + h + 2h² - 1) / h = ilimₕ→₀ 2 + h = 0
          ○ Hence, the slope of the tangent line is 2.
          ○ [28:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1700).  Using the point-slope form to find the equation of the tangent line at (1,1).
               ■  𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁).
               ■ The equation of the tangent line is 𝒚 = 2x - 1.
                    
● [30:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=1855). 🧩 Example 2 – Finding the equation of the tangent line to 𝒚 = 3/x at (3, 1) 📷[Image-1](../img/Calculus 1 Lecture 1.5/[30-55]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 1.5/[30-55]-02.png)
     ◉ Steps to restating the goal and using the formula for the slope of the tangent.
          ○ Identification of 𝒇(𝒙) = 3/x and x₀ = 3.
          ○ Calculating 𝒇(𝒙₀ + h) = 𝒇(3 + h) = 3/(3 + h).
          ○ Calculating 𝒇(𝒙₀) = 𝒇(3) = 1.
          ○ Take the limit m_tan = limₕ→₀  (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  /  h 
               ■ m_tan = limₕ→₀  (3/(3 + h) - 1)  /  h 
                             = limₕ→₀  (- h /( 3+ h ))/ h  = limₕ→₀  -1 / (3 + h) = -1/3
          ○ Hence, the slope of the tangent line is -1/3.
          ○ [41:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=2480). Using the point-slope form to find the equation of the tangent line at (1,1).
               ■  𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁).
               ■ The equation of the tangent line is 𝒚 = -1/3x + 2.                  

● [44:57](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=2697). 🧩 Example 3 –  Finding the slope of tangent lines to 𝒚 = √x at any point 📷[Image-1](../img/Calculus 1 Lecture 1.5/[44-57]-01.png)  📷[Image-2](../img/Calculus 1 Lecture 1.5/[44-57]-01.png)
     ◉ Objective: derive a general formula for the slope of the tangent to 𝒚 = √x at any point x.
          ○ Identification of 𝒇(𝒙) = √x.
          ○ Calculating 𝒇(x + h) = √(x + h).
          ○ Take the limit m_tan = limₕ→₀  (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  /  h 
               ■ m_tan = limₕ→₀  (√(x + h) - √x)  /  h  
                             = limₕ→₀  (x + h) - x)  /  (h∙(√(x + h) + √x)) multiplicate by de conjugat (√(x + h) + √x) / (√(x + h) + √x)
                             = limₕ→₀  1 / (√(x + h) + √x) = 1/(2√x)
          ○ Hence, the slope of the tangent line 𝐚𝐭 𝐚𝐧𝐲 𝐩𝐨𝐢𝐧𝐭 is  1/(2√x)
          ○ [55:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3300). Obtaining the general formula for the slope of the tangent: m = 1/(2√x).
               ■ Explanation that this formula allows computing the slope at any point on the curve.
          ○ [57:35](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3455). Sharp point:
               ■ At a sharp point on a curve, 𝘁͟𝗵͟𝗲͟ ͟𝘀͟𝗹͟𝗼͟𝗽͟𝗲͟𝘀͟ ͟𝗳͟𝗿͟𝗼͟𝗺͟ ͟𝘁͟𝗵͟𝗲͟ ͟𝗹͟𝗲͟𝗳͟𝘁͟ ͟𝗮͟𝗻͟𝗱͟ ͟𝗿͟𝗶͟𝗴͟𝗵͟𝘁͟ ͟𝘀͟𝗶͟𝗱͟𝗲͟𝘀͟ ͟𝗮͟𝗿͟𝗲͟ ͟𝗱͟𝗶͟𝗳͟𝗳͟𝗲͟𝗿͟𝗲͟𝗻͟𝘁͟. This discrepancy 
                  causes the limit defining the tangent slope (m_tan) to fail, as it does not exist uniquely. Consequently,
                  an infinite number of tangent lines with varying slopes can be drawn through that sharp point.




Ａｐｐｌｉｃａｔｉｏｎｓ   of   Ａｖｅｒａｇｅ   ａｎｄ   ｉｎｓｔａｎｔａｎｅｏｕｓ   ｖｅｌｏｃｉｔｙ

● [58:54](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3534). Introduction to applications.
     ◉ 𝗔̳𝘃̳𝗲̳𝗿̳𝗮̳𝗴̳𝗲̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ (V_ave) corresponds to the slope of the secant line between two points, calculated as:
                                      m_secant = (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h
     ◉ 𝗜̳𝗻̳𝘀̳𝘁̳𝗮̳𝗻̳𝘁̳𝗮̳𝗻̳𝗲̳𝗼̳𝘂̳𝘀̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ (V_inst)  matches the slope of the tangent line at a single point, given by:
                                               m_tan = limₕ→₀ (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h
               
𝗔̳𝘃̳𝗲̳𝗿̳𝗮̳𝗴̳𝗲̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳
● [59:03](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3543). Distance traveled over elapsed time.
     ◉ V_ave = displacement / time = (𝒇(t₀ + h) - 𝒇(t₀)) / h  
           
● [1:01:26](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3686). Relationship between the average velocity formula and the slope formula.
     ◉ Both formulas represent the slope between two points.
     ◉ Average velocity is the slope of the secant line on a position vs. time graph.
           
● [1:02:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3740). 🧩  Example: Finding average velocity of s(t) = 1 + 3t - 2t² over the interval [1,3] 📷[Image](../img/Calculus 1 Lecture 1.5/[1-02-20]-01.png)
     ◉ [1:03:35](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=3815). Identification of t₀ = 1 and h = 2.
     ◉ Calculating s(t₀ + h) = s(3) = -8.
     ◉ Calculating s(t₀) = s(1) = 2.
     ◉ Computing the average velocity: (s(3) - s(1)) / 2 = (-8 - 2) / 2 = -5.
           
● [1:08:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4135). Introduction to the difference between velocity and speed.
     ◉ Average Velocity:
          ○ Type: Vector
          ○ Includes: Direction and magnitude
          ○ Use:Indicates the overall change in position over time,
             providing information about both the rate of displacement and the direction.
     ◉ Speed:
          ○ Type: Scalar
          ○ Includes: Only magnitude
          ○ Use: Measures the total distance traveled over a period of time without regard to direction.
                      
𝗜̳𝗻̳𝘀̳𝘁̳𝗮̳𝗻̳𝘁̳𝗮̳𝗻̳𝗲̳𝗼̳𝘂̳𝘀̳ ̳𝘃̳𝗲̳𝗹̳𝗼̳𝗰̳𝗶̳𝘁̳𝘆̳ 📷[Image](../img/Calculus 1 Lecture 1.5/[1-10-02]-01.png)
● [1:10:02](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4202). Velocity at a specific instant in time.
     ◉ [1:11:25](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4285). 𝙃𝙤𝙬 𝙢𝙪𝙘𝙝 𝙩𝙞𝙢𝙚 𝙚𝙡𝙖𝙥𝙨𝙚𝙨 𝙞𝙣 𝙖𝙣 𝙞𝙣𝙨𝙩𝙖𝙣𝙩?
           
● [1:12:55](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4375). Instantaneous velocity is found by letting h approach zero in the average velocity formula.
     ◉ [1:13:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4403). This involves using a limit.
          ○ How we make average velocity instant?
               ■ limₕ→₀  (𝒇(t₀ + h) - 𝒇(t₀))/ h; h = time
                      
● [1:14:20](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4460). Relationship between instantaneous velocity and the slope of a curve at a point.
     ◉ Both represent the instantaneous rate of change.
           
● [1:15:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=4523). 🧩 Example: Finding instantaneous velocity of s(t) = 500 - 16t² after 5 seconds.  📷[Image-1](../img/Calculus 1 Lecture 1.5/[1-15-23]-02.png)  📷[Image-2](../img/Calculus 1 Lecture 1.5/[1-15-23]-01.png)
     ◉ limₕ→₀  (s(t₀ + h) - s(t₀))/ h 
     ◉ Identification of t₀ = 5.
     ◉ Calculating s(t₀ + h) = s(5 + h) = 500 - 16(5 + h)².
     ◉ Calculating s(t₀) = s(5) = 100.
     ◉ [1:27:00](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5220). Substituting into the instantaneous velocity formula and simplifying.
          ○ Take the limit 
                 limₕ→₀  (s(t₀ + h) - s(t₀))/ h = V_inst = limₕ→₀ (500 - 16(25 + 10h + h²) - 100)  / h  
          ○ Simplify the expression:
                 V_inst = limₕ→₀ (500 - 400 - 160h - 16h² - 100) / h
                 V_inst = limₕ→₀ (-160h - 16h²) / h
          ○ Cancel the common factor of h:
                 V_inst = limₕ→₀ -160 - 16h
          ○ Evaluate the limit as h approaches 0:
                 V_inst = -160 ft/sec
     ◉ [1:32:37](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5550). Computing the instantaneous velocity in general (for any time t so  ̵t̵₀̵ ̵=̵ ̵5̵)  and obtaining the formula: v(t) = -32t. 📷[Image-3](../img/Calculus 1 Lecture 1.5/[1-15-23]-03.png)
          ○ Set up the formula for instantaneous velocity:
               V_inst = limₕ→₀ s(T + h) - s(T) / h 
          ○ Substitute the given position functions:
               s(T + h) = 500 - 16(T + h)²
               s(T) = 500 - 16T²
          ○ Substitute the expressions:
               V_inst = limₕ→₀  (500 - 16(T² + 2Th + h²) - (500 - 16T²)) / h 
          ○ Expand and simplify:
              V_inst = limₕ→₀  (500 - 16T² - 32Th - 16h² - 500 + 16T²) / h 
          ○ Cancel common terms:
              V_inst = limₕ→₀  (-32Th - 16h²) / h 
          ○ Factor out the common term (h):
              V_inst = limₕ→₀ -32T - 16h 
          ○ Evaluate the limit as h approaches 0:
              V_inst = -32T
          ○ Substitute T = 5 seconds:
              V_inst = -32(5)
              V_inst = -160 ft/sec
     ◉ [1:38:29](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5909). Explanation of the difference between velocity and speed.
          ○ Speed is the absolute value of velocity.
                     



Ａｖｅｒａｇｅ   ａｎｄ   Ｉｎｓｔａｎｔａｎｅｏｕｓ   ｒａｔｅ   ｏｆ   ｃｈａｎｇｅ

● [1:39:23](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5963). Connection between slope and rate of change.
     ◉ The slope is a rate of change.
         
● [1:39:59](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=5999). The average rate of change is the slope of the secant line between two points.

● [1:41:58](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6118). The instantaneous rate of change is the slope of the curve at one point.

● [1:43:10](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6190). Rate of change:
     ◉ Average rate of change:          r_av = (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h
     ◉ instantaneous rate of change: r_inst =  limₕ→₀  (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  / h 
           
● [1:46:37](https://www.youtube.com/watch?v=PqQ5v94_NGM&t=6397). 🧩 Example: Finding the average and instantaneous rate of change of a curve  𝒇(𝒙) = 3𝒙² - 4, r_ave:[2,5] and  r_inst:-2
     ◉ Average rate of change: r_av = (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h
          ○ 𝒇(𝒙₀) = 𝒇(2) 
          ○ 𝒇(𝒙₀ + h) = 𝒇(2 + (5-2) ) = 𝒇(5) 
          ○ r_av = (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h = (𝒇(5) - 𝒇(2)) / 3 = 63 / 3 = 21
     ◉ instantaneous rate of change: r_inst =  limₕ→₀  (𝒇(𝒙₀ + h) - 𝒇(𝒙₀))  / h 
          ○  𝒇(𝒙₀) = 3𝒙₀² - 4 
          ○ 𝒇(𝒙₀ + h) = 𝒇(3(𝒙₀ + h)² - 4) = 3𝒙₀² + 6𝒙₀h + h² - 4
          ○ r_inst = limₕ→₀  ((3𝒙₀² + 6𝒙₀h + h² - 4) - (3𝒙₀² - 4)) / h  = limₕ→₀  ( 6𝒙₀h + h² ) / h  =
                       = limₕ→₀  6𝒙₀ + h  = 6𝒙₀
          ○ r_inst_𝒙₀:-2 = -12