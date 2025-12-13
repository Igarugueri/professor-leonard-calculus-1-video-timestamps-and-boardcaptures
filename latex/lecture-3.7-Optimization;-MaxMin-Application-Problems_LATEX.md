-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．７　Oｐｔｉｍｉｚａｔｉｏｎ；　Mａｘ /  Mｉｎ　Aｐｐｌｉｃａｔｉｏｎ　Pｒｏｂｌｅｍｓ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=SWZcq_biZLw&t=1). Introduction [📷image](../img/Calculus 1 Lecture 3.7/[0-01]-01.png) 
     ◉ This lecture focuses on how to maximize and/or minimize continuous functions.
     ◉ Two scenarios are explored:
          ○ Closed Intervals.
          ○ Open Intervals.
     ◉ We analyze the existence of absolute maxima and minima in continuous functions and their real-life applications.

● [0:50](https://www.youtube.com/watch?v=SWZcq_biZLw&t=50). Real-Life Applications
     ◉ Minimizing Costs and Maximizing Profits: In business, it is crucial to find the lowest cost and the highest profit.
          ○ Calculus allows for precise calculations of production and costs to optimize these aspects.
     ◉ Design Optimization: Calculus can be used to design products that maximize attributes such as volume, given certain constraints.




Ｅｘｔｒｅｍｅ　ｖａｌｕｅ　ｔｈｅｏｒｅｍ

● [2:15](https://www.youtube.com/watch?v=SWZcq_biZLw&t=135). Extreme Value Theorem.
     ◉ Closed Intervals:
          ○ If a function is continuous on a **closed interval $[\mathcal{a},\mathcal{b}]$**, then it **must attain** both an absolute maximum and an absolute minimum on that interval.
          ○ These extrema may occur:
               ■ At the endpoints ($x=\mathcal{a}$ or $x=\mathcal{b}$), or
               ■ At critical points within $(\mathcal{a}, \mathcal{b})$ where the derivative is zero or undefined.
     ◉ Open Intervals:
          ○ If a function is continuous on an **open interval $(\mathcal{a},\mathcal{b})$**, it **might not attain** absolute extrema.
          ○ This is because there are no endpoints to "trap" the function’s values, and the function might increase or decrease without bound near the edges.


    

 Ｍａｘｉｍｉｚｉｎｇ　Eｘａｍｐｌｅｓ

● [3:51](https://www.youtube.com/watch?v=SWZcq_biZLw&t=231). Maximizing the Area of a Rectangle [📷image](../img/Calculus 1 Lecture 3.7/[3-51]-01.png) 
     ◉ Problem: Maximize the area of a rectangular region fenced with 100 feet of fencing.
     ◉ Identify the Restriction: The total length of fencing (100 ft) corresponds to the rectangle’s perimeter.
     ◉ Draw a Diagram: Sketch a rectangle and label its sides as $𝒙$ and $𝑦$.
     ◉ Formulate:
          ○ Area: $A = 𝒙\cdot 𝑦$
     ◉ Constraint:
          ○ Perimeter: $2𝒙 + 2𝑦 = 100$
          ○ **Solve the restriction for one variable**:
               ■ $𝑦 = 50 − 𝒙$
          ○ **Substitute into the Area Formula:** Substitute $𝑦$ into the area expression:
               ■ $A = 𝒙(50 − 𝒙)$
     ◉ Find Critical Points: Take the derivative of $𝒜$ with respect to $𝒙$, set it to zero, and solve for $𝒙$
     $\rule{0pt}{}$
          ○ $\dfrac{dA}{d𝒙} = 50 − 2𝒙 = 0$
          $\rule{0pt}{}$
          ○ $𝒙 = 25$
     ◉ Determine Endpoints: The possible minimum and maximum values for $𝒙$ are $0$ and $50$.
          ○ [18:08](https://www.youtube.com/watch?v=SWZcq_biZLw&t=1088). ᴛʜᴇ ᴩᴏɪɴᴛ: By the Extreme Value Theorem, the maximum must occur at one of the following:
               ■ $𝒙 = 0,\; 𝒙 = 25,\; 𝒙 = 50$ — all within the interval $𝒙 \in [0, 50]$
     ◉ Evaluate the Function at Critical Points and Endpoints:
          ○ $A(0) = 0$
          ○ $A(25) = 625$
          ○ $A(50) = 0$
     ◉ Conclusion: The maximum area is $625\ \text{ft}^2$ when $𝒙 = 25$ ft and $𝑦 = 25$ ft, forming a square.

● [21:41](https://www.youtube.com/watch?v=SWZcq_biZLw&t=1301). Maximizing the Volume of a Box [📷image-1](../img/Calculus 1 Lecture 3.7/[21-41]-01.png) [📷image-2](../img/Calculus 1 Lecture 3.7/[21-41]-02.png) 
     ◉ Problem: An open box is constructed from a $16\times 30$-inch piece of cardboard by cutting squares of side $𝒙$ from each corner and folding up the flaps.
     ◉ Draw a Diagram: Sketch the cardboard with the cut-out squares and the resulting box.
     ◉ Identify the Restriction: The maximum cut size is $8$ inches (half the length of the shorter side).
     ◉ Formulate Equations:
     $\rule{0pt}{}$
          ○ Volume: $V = 𝒙(30 − 2𝒙)(16 − 2𝒙)$
          $\rule{0pt}{}$
          ○ Restriction: $0 \le 𝒙 \le 8$
          $\rule{0pt}{}$
     ◉ Simplify the Volume Formula: Expand and combine like terms as needed.
     ◉ Find Critical Points: Take the derivative of $V$ with respect to $𝒙$, set it to zero, and solve.
     $\rule{0pt}{}$
          ○ $\dfrac{dV}{d𝒙} = 12𝒙^2 − 188𝒙 + 480 = 0$
          $\rule{0pt}{}$
          ○ By factoring or quadratic formula: $𝒙 = 12$ or $𝒙 = \dfrac{10}{3}$
          $\rule{0pt}{}$
     ◉ Discard Invalid Solutions: $𝒙 = 12$ is invalid because it exceeds the restriction.
     ◉ Evaluate the Function at Critical Points and Endpoints:
     $\rule{0pt}{}$
          ○ $V(0) = 0$
          $\rule{0pt}{}$
          ○ $V\!\left(\dfrac{10}{3}\right) > 0$
          $\rule{0pt}{}$
          ○ $V(8) = 0$
     ◉ Conclusion: The maximum volume is achieved with a $10/3$-inch cut.

  


  Ｍｉｎｉｍｉｚｉｎｇ　Eｘａｍｐｌｅｓ

● [38:33](https://www.youtube.com/watch?v=SWZcq_biZLw&t=2313). Minimizing the Cost of a Pipeline [📷image-1](../img/Calculus 1 Lecture 3.7/[38-33]-01.png) [📷image-2](../img/Calculus 1 Lecture 3.7/[38-33]-02.png)
     ◉ Problem: A pipeline must carry oil from an offshore platform to a refinery on land.
          ○ The pipeline cost is $1 per km offshore and $0.50 per km on land.
          ○ The platform is $5$ km from the coast, and the refinery is $8$ km along the coast.
     ◉ Draw a Diagram: Sketch the coastline, the offshore platform, the refinery, and the potential pipeline route.
     ◉ Identify the Restriction: The refinery is fixed at $8$ km along the coast.
     ◉ Choose a landing point $𝓟=(x,0)$ somewhere along the coast ($0 \le x \le 8$) where the total cost is minimized.
     $\rule{0pt}{}$
          🗼 $(0,5)$ offshore platform
            | 
            |
            |     Offshore segment (cost \$1/km)
            |
            |
            |$(0,0)$  Landing point A at $x$ km                                                                                            Refinery R
            ─────────────●─────────────────────────────────────────🛢️   $(8, 0)$
                      <-- $x$ -->          $𝓟$                                                <--  $|8 − x|$  →
           <──────────────── Land segment (cost $0.50/km) ───────────────────>
           $\rule{0pt}{}$
     ◉ Formulate Equations:
     $\rule{0pt}{}$
          ○ Cost: $C = \sqrt{x^{2} + 25}\; +\; 0.5\,(8 − x)$
             (Here, $x$ is the distance along the coast from the point directly opposite the platform to the pipeline’s landfall)
          ○ Restriction: $0 \le x \le 8$
     ◉ Simplify the Cost Equation: Distribute $0.5$ in the expression.
     ◉ Find Critical Points: Take the derivative of $C$ with respect to $x$, set it to zero, and solve.
     $\rule{0pt}{}$
          ○ $\dfrac{dC}{dx} = \dfrac{x}{\sqrt{x^{2} + 25}} − 0.5 = 0$
          $\rule{0pt}{}$
          ○ Solving yields $x = \dfrac{5\sqrt{3}}{3}$
          $\rule{0pt}{}$
     ◉ Evaluate the Function at Critical Points and Endpoints:
     $\rule{0pt}{}$
          ○ $C(0) = 9$
          $\rule{0pt}{}$
          ○ $C\!\left(\dfrac{5\sqrt{3}}{3}\right) \approx 8.33$
          $\rule{0pt}{}$
          ○ $C(8) \approx 9.43$
          $\rule{0pt}{}$
     ◉ Conclusion: The minimum cost is about 8.33$ when x $\approx$ 2.9 km.


● [1:12:12](https://www.youtube.com/watch?v=SWZcq_biZLw&t=4332). Minimizing Material for a Can [📷image-1](../img/Calculus 1 Lecture 3.7/[1-12-12]-01.png) [📷image-2](../img/Calculus 1 Lecture 3.7/[1-12-12]-02.png) [📷image-3](../img/Calculus 1 Lecture 3.7/[1-12-12]-03.png)
     ◉ Problem: Design a cylindrical can that holds $1{,}000\ \text{cm}^3$ of liquid using the least material.
     ◉ Draw a Diagram: Sketch a cylinder, labeling the radius $r$ and height $h$.
     ◉ Identify the Restriction: The can’s volume is fixed at $1{,}000\ \text{cm}^3$.
     ◉ Formulate Equations:
          ○ Surface Area: $S = 2\pi r^{2} + 2\pi r\,h$
          ○ Restriction (Volume): $\pi r^{2}h = 1000$
     ◉ Solve for One Variable: Solve the volume restriction for $h$.
     $\rule{0pt}{}$
          ○ $h = \dfrac{1000}{\pi r^{2}}$
          $\rule{0pt}{}$
     ◉ Substitute into the Surface Area Formula:
     $\rule{0pt}{}$
          ○ $S = 2\pi r^{2} + 2\pi r \left(\dfrac{1000}{\pi r^{2}}\right)$
          $\rule{0pt}{}$
          ○ Simplify: $S = 2\pi r^{2} + \dfrac{2000}{r}$
          $\rule{0pt}{}$
     ◉ Find Critical Points: Take the derivative of $S$ with respect to $r$, set it to zero, and solve.
     $\rule{0pt}{}$
          ○ $\dfrac{dS}{dr} = 4\pi r − \dfrac{2000}{r^{2}} = 0$
          $\rule{0pt}{}$
          ○ Solving gives $r = \sqrt[3]{\dfrac{500}{\pi}} \approx 5.42\ \text{cm}$
          $\rule{0pt}{}$
     ◉ Calculate the Height:
          ○ $h \approx 10.84\ \text{cm}$
     ◉ Verify It’s a Minimum:
          ○ Use the second derivative: $\dfrac{d^{2}S}{dr^{2}} = 4\pi + \dfrac{4000}{r^{3}}$
          $\rule{0pt}{}$
          ○ Evaluating at $r \approx 5.42$ cm yields a positive result, indicating a minimum.
     ◉ Conclusion: The can uses the least material when $r \approx 5.42$ cm and $h \approx 10.84$ cm.
