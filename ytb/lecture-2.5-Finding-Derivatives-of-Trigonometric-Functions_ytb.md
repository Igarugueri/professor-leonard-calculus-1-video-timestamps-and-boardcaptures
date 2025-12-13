----------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．５　Fｉｎｄｉｎｇ　Dｅｒｉｖａｔｉｖｅｓ　Oｆ　Tｒｉｇｏｎｏｍｅｔｒｉｃ　Fｕｎｃｔｉｏｎｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ　ａｎｄ　ｍｏｔｉｖａｔｉｏｎ

● [0:08]. Introduction to trigonometric functions and their importance in later calculus courses.
● [0:53]. Presentation of two fundamental concepts necessary for the demonstration:
     ◉ Trigonometric identity:  lim ₕ→₀ sin(h) / h = 1.
     ◉ Trigonometric identity:  lim ₕ→₀ (1 - cos(h))  / h  = 0.

    

Ｄｅｍｏｎｓｔｒａｔｉｏｎ　ｏｆ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ｔｈｅ　ｓｉｎｅ　ｆｕｎｃｔｉｏｎ

● [2:07]. Objective: find the derivative of 𝑓(𝒙) = sin(𝒙), denoted as 𝑓'(𝒙). = sin(𝒙), denoted as 𝑓'(𝒙)_1.png) = sin(𝒙), denoted as 𝑓'(𝒙)_2.png)
     ◉ Reminder of the concept of derivative as a limit:
          ○ 𝑓'(𝒙) = lim ₕ→₀  (𝑓(𝒙 + h) - 𝑓(𝒙)) / h 
    
● [2:55]. Application of the limit concept to the sine function:
     ◉ 𝑓(𝒙) = sin(𝒙).
     ◉ 𝑓(𝒙 + h) = sin(𝒙 + h).
     ◉ Restriction: the expression 𝒙 + h inside the sine function cannot 
         be separated without using trigonometric identities.
        
● [3:32]. First step of the demonstration:
     ◉ 𝑓'(𝒙) = lim ₕ→₀  (sin(𝒙 + h) - sin(𝒙)) / h 
    
● [5:00]. Use of the angle sum trigonometric identity for sine:
     ◉ sin(𝒙 + h) = sin(𝒙) ⋅ cos(h) + cos(𝒙) ⋅ sin(h)
     ◉ 𝑓'(𝒙) = lim ₕ→₀  (sin(𝒙) ⋅ cos(h) + cos(𝒙) ⋅ sin(h) - sin(𝒙)) / h 

● [5:55]. Reorder the expresion
     ◉ 𝑓'(𝒙) = lim ₕ→₀  (sin(𝒙) ⋅ cos(h) - sin(𝒙) + cos(𝒙) ⋅ sin(h) ) / h 

● [6:40]. Separation of the expression into two fractions with denominator h.
     ◉ 𝑓'(𝒙) = lim ₕ→₀  ((sin(𝒙) ⋅ cos(h)  - sin(𝒙)) / h) + ((cos(𝒙) ⋅ sin(h)) / h) ]
     
● [7:15]. Factoring out sin(𝒙) in the first term and limₕ→₀ the second term.
     ◉ 𝑓'(𝒙) = lim ₕ→₀  (sin(𝒙) ⋅ ((cos(h)  - 1)) / h) + (cos(𝒙) ⋅ (sin(h) / h)) 
          ○ Algebraic manipulation to obtain the known trigonometric limits:
               ■ lim ₕ→₀  sin(h) / h = 1 
               ■ lim ₕ→₀  (1 - cos(h)) / h = 0 
                    ▣ Factoring '-1' from the first term (we reverse 'cos(h)  - 1'):
                         ▢ 𝑓'(𝒙) = lim ₕ→₀  - sin(𝒙) ⋅ ((1 - cos(h))) / h) + (cos(𝒙) ⋅ (sin(h) / h)) 
                         
● [9:35]. Application of the limits and simplification to obtain the derivative of sine:
     ◉ 𝑓'(𝒙) = lim ₕ→₀  - (sin(𝒙) ⋅ (0) / h) + (cos(𝒙) ⋅ (1)) 
     ◉ 𝑓'(𝒙) = 0 + cos(𝒙)
     ◉ 𝑓'(𝒙) = cos(𝒙) or 𝒅/𝒅𝒙 [sin(𝒙)]  = cos(𝒙)
    
● [11:15]. Interpretation: the derivative of the sine function is the cosine function, meaning 
                 that the slope of the sine curve at any point is equal to the value of the cosine at that point.

                 

Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　ｏｔｈｅｒ　ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｆｕｎｃｔｉｏｎｓ

● [12:50].**Presentation of the derivatives of the six main trigonometric functions:**
    1. 𝒅/𝒅𝒙 [sin(𝒙)]  = cos(𝒙).
    2. 𝒅/𝒅𝒙 [cos(𝒙)] = -sin(𝒙).
    3. 𝒅/𝒅𝒙 [tan(𝒙)]  = sec²(𝒙).
    4. 𝒅/𝒅𝒙 [sec(𝒙)] = sec(𝒙)tan(𝒙).
    5. 𝒅/𝒅𝒙 [csc(𝒙)] = -csc(𝒙)cot(𝒙).
    6. 𝒅/𝒅𝒙 [cot(𝒙)] = -csc²(𝒙).
    
● [13:41]. The derivatives of tangent, secant, cosecant, and cotangent can be obtained using 
                 the quotient rule and the derivatives of sine and cosine.
                 
● [16:17]. Observation on the relationships between the derivatives of trigonometric functions,
                 which can help in memorizing them.
                 


Ｅｘａｍｐｌｅｓ　ｏｆ　ａｐｐｌｙｉｎｇ　ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｄｅｒｉｖａｔｉｖｅｓ

● [19:08]. 🧩 Example – 1: Find the derivative of 𝐲 = 𝒙 ⋅ sin(𝒙).
     ◉ Identification of the need to use the product rule.
     ◉ Application of the product rule:
          ○ 𝒅/𝒅𝒙 [𝒙 ⋅ sin(𝒙)] = (𝒅/𝒅𝒙 [𝒙] ⋅ sin(𝒙)) + (𝒙 ⋅ 𝒅/𝒅𝒙 [sin(𝒙)]).
     ◉ Simplification to obtain the derivative:
          ○ 𝒅/𝒅𝒙 [𝒙 ⋅ sin(𝒙)] = sin(𝒙) + 𝒙 ⋅ cos(𝒙).
     ◉ Interpretation: the obtained expression represents the slope function for 
        the curve 𝐲 = 𝒙 ⋅ sin(𝒙).

● [21:35]. 🧩 Example – 2: Find the equation of the tangent line to the curve 𝐲 = 𝒙 ⋅ sin(𝒙) at the point 𝒙 = π/2.
     ◉ Requirements for the equation of a line: a point and the slope.
     ◉ Obtaining the slope (m) at 𝒙 = π/2:
          ○ m = sin(𝒙) + 𝒙 ⋅ cos(𝒙).
               ■ m = sin(π/2) + (π/2) ⋅ cos(π/2) = 1.
     ◉ Obtaining the point (π/2, 𝐲) by substituting 𝒙 = π/2 into the original equation:
          ○ 𝐲 = (π/2) ⋅ sin(π/2) = π/2.
     ◉ Use of the point-slope formula 𝐲 - 𝐲₁ = m(𝒙 - 𝒙₁) to obtain the equation of the tangent line.
          ○ 𝐲 - π/2 = 1(𝒙 - π/2) → 𝐲 = 𝒙
          
● [26:20]. 🧩 Example – 3: Find the derivative of 𝐲 = sin(𝒙) / (1 + cos(𝒙)).
     ◉ Identification of the need to use the quotient rule.
     ◉ Application of the quotient rule:
          ○ 𝒅/𝒅𝒙 [sin(𝒙) / (1 + cos(𝒙))] = {(𝒅/𝒅𝒙 [sin(𝒙)] ⋅ (1 + cos(𝒙))) - (sin(𝒙) ⋅ 𝒅/𝒅𝒙 [1 + cos(𝒙)])} / (1 + cos(𝒙))².
     ◉ Calculation of individual derivatives and simplification.
          ○ 𝒅/𝒅𝒙 [sin(𝒙) / (1 + cos(𝒙))] = { cos(𝒙)⋅ (1 + cos(𝒙))) - (sin(𝒙) ⋅ - sin(𝒙))} / (1 + cos(𝒙))² =
              = (cos(𝒙) + cos²(𝒙) + sin²(𝒙)) / (1 + cos(𝒙))²
                                 ︸︸︸ 1 ︸︸︸
     ◉ [31:42]. Use of the trigonometric identity cos²(𝒙) + sin²(𝒙) = 1 to simplify the expression.
          ○ 𝒅/𝒅𝒙 [sin(𝒙) / (1 + cos(𝒙))] = (cos(𝒙) + 1) / (1 + cos(𝒙))²
     ◉ Additional simplification to obtain the derivative:
          ○ 𝒅/𝒅𝒙 [sin(𝒙) / (1 + cos(𝒙))] = 1 / (1 + cos(𝒙)).

● [33:40]. 🧩 Example – 4: Calculation of higher-order derivatives for the function sin(𝒙).
     ◉ Calculation of the second, third, and fourth derivatives of sin(𝒙).
          ○ First derivative: 𝒅𝑦/𝒅𝑥 = cos(𝑥)
          ○ Second derivative: 𝒅²𝑦/𝒅𝑥² = −sin(𝑥)
          ○ Third derivative: 𝒅³𝑦/𝒅𝑥³ = −cos(𝑥)
          ○ Fourth derivative: 𝒅⁴𝑦/𝒅𝑥⁴ = sin(𝑥)
     ◉ Observation on the cyclical nature of the derivatives of the sine function.
     ◉ [35:15]. Variable sustitution
          ○ Evaluate the second derivative at 𝑥 = π/2:
          ■ d²𝑦/d𝑥² |_𝑥=π/2 = −sin(𝑥) |_𝑥=π/2 = −sin(π/2) = −1
     ◉ [35:45]. Graphical Relationship between sin(𝑥) and Its Derivatives
          ○ The function 𝑦 = sin(𝑥) exhibits periodic behavior. To understand the relationship between sin(𝑥) and its derivatives, 
              we can analyze both the graph of sin(𝑥) and the slopes (derivatives) at various points.
          ○ If we draw the tangent lines to the graph of sin(𝑥) at several key points, and then plot the **value of the slope** at each of those points, 
             we obtain the graph of cos(𝑥), since the derivative of sin(𝑥) is cos(𝑥).
          ○ This process can be repeated:
               ■ The derivative of cos(𝑥) is −sin(𝑥).
               ■ The derivative of −sin(𝑥) is −cos(𝑥).
               ■ The derivative of −cos(𝑥) is sin(𝑥).
          ○ **Observation:** After four derivatives, the function returns to its original form (sin(𝑥)), confirming the periodicity and oscillatory nature of sine and cosine functions.
          ○ **Key idea:** The slope of the curve at each point on sin(𝑥) directly corresponds to the value of cos(𝑥) at that same 𝑥.
             If you plot all these slopes, you reconstruct the cos(𝑥) curve.
          ○This explains why the graphs of sin(𝑥), cos(𝑥), −sin(𝑥), and −cos(𝑥) are all phase-shifted versions of each other, and why they oscillate back and forth, 
            always returning to the original position after four derivatives

          
● [39:45]. 🧩 Example – 5 (verbal problem): Modeling the motion of a spring with a mass.
     ◉ Description of the problem: a spring with a mass is stretched 3 cm from its 
         resting position and released, oscillating without friction.
     ◉ Modeling the position of the spring with a cosine function: 
          ○ Is the reflection of the 'normal' cosine so it is negative.
          ○ 𝐲(𝒕) = -3⋅cos(𝒕).
     ◉ Objective: find the velocity function of the spring.
     ◉ Relationship between velocity and position: velocity is the derivative of position.
          ○ **Observation:** The velocity is 0 whera the **slope is parallel to the x-axis**
     ◉ Calculation of the derivative of the position function:
          ○ 𝐲'(𝒕) = 3 ⋅ sin(𝒕).
     ◉ Possible additional questions about the problem:
          ○ Find the points where the velocity is zero.
          ○ Find the equation of the tangent line at a specific point.

        

Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｈａｉｎ　ｒｕｌe

● [45:58]. Introduction to the chain rule.
     ◉ Presentation of examples of derivatives that can be calculated _without the chain rule_:
          ○ 𝒅/𝒅𝒙 [3𝒙² ⋅ 4]
          ○ 𝒅/𝒅𝒙 [(3𝒙² ⋅ 4)²]; you can apply the product rule or expand, then differentiate.
          ○ 𝒅/𝒅𝒙 [(3𝒙² ⋅ 4)³]; still doable, but becomes tedious.
     ◉ Presentation of examples of derivatives that are difficult to calculate _without the chain rule_:
          ○ 𝒅/𝒅𝒙 [(3𝒙² ⋅ 4)¹⁰⁰]
     ◉ **Description of the utility of the chain rule:**
          ○ The chain rule provides a systematic and efficient method for finding the derivative of composite functions, especially when 
              direct expansion or repeated use of the product rule becomes impractical. It is essential for handling functions of the form 𝒇(𝗀(𝒙)), 
              where one function is nested inside another.
               ■ The chain rule is a fundamental technique for differentiating composite functions. It allows us to find the derivative of a 
                  function inside another function by differentiating the outer function (leaving the inner   unchanged) and multiplying by the derivative
                  of the inner function. This method is essential when direct expansion is impractical or impossible, and it is widely used in real-world 
                  problems where functions are nested—such as in physics, engineering, and economics.
                ■ In symbols: 𝒅/𝒅𝒙 [𝒇(𝗀(𝒙))] = 𝒇′(𝓰(𝒙)) ⋅ 𝓰′(𝒙)