-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．７　Oｐｔｉｍｉｚａｔｉｏｎ；　Mａｘ /  Mｉｎ　Aｐｐｌｉｃａｔｉｏｎ　Pｒｏｂｌｅｍｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01]. Introduction 
     ◉ This lecture focuses on how to maximize and/or minimize continuous functions.
     ◉ Two scenarios are explored:
          ○ Closed Intervals.
          ○ Open Intervals.
     ◉ We analyze the existence of absolute maxima and minima in continuous functions and their real-life applications.

● [0:50]. Real-Life Applications
     ◉ Minimizing Costs and Maximizing Profits: In business, it is crucial to find the lowest cost and the highest profit.
          ○ Calculus allows for precise calculations of production and costs to optimize these aspects.
     ◉ Design Optimization: Calculus can be used to design products that maximize attributes such as volume, given certain constraints.



Ｅｘｔｒｅｍｅ　ｖａｌｕｅ　ｔｈｅｏｒｅｍ

● [2:15]. Extreme Value Theorem.
     ◉ Closed Intervals:
          ○ If a function is continuous on a **closed interval [𝓪,𝓫]**, then it **must attain** both an absolute maximum and an absolute minimum on that interval.
          ○ These extrema may occur:
               ■ At the endpoints (𝒙 = 𝓪 or 𝒙 = 𝓫), or
               ■ At critical points within (a, b) where the derivative is zero or undefined.
     ◉ Open Intervals:
          ○ If a function is continuous on an **open interval (𝓪,𝓫)**, it **might not attain** absolute extrema.
          ○ This is because there are no endpoints to "trap" the function’s values, and the function might increase or decrease without bound near the edges.


    

 Ｍａｘｉｍｉｚｉｎｇ　Eｘａｍｐｌｅｓ

● [3:51]. Maximizing the Area of a Rectangle 
     ◉ Problem: Maximize the area of a rectangular region fenced with 100 feet of fencing.
     ◉ Identify the Restriction: The total length of fencing (100 ft) corresponds to the rectangle’s perimeter.
     ◉ Draw a Diagram: Sketch a rectangle and label its sides as 𝒙 and 𝑦.
     ◉ Formulate:
          ○ Area: 𝒜 = 𝒙·𝑦
     ◉ Constraint:
          ○ Perimeter: 2𝒙 + 2𝑦 = 100
          ○ **Solve the restriction for one variable**:
               ■ 𝑦 = 50 − 𝒙
          ○ **Substitute into the Area Formula:** Substitute 𝑦 into the area expression:
               ■ 𝒜 = 𝒙(50 − 𝒙)
     ◉ Find Critical Points: Take the derivative of 𝒜 with respect to 𝒙, set it to zero, and solve for 𝒙.
          ○ d𝒜/d𝒙 = 50 − 2𝒙 = 0
          ○ 𝒙 = 25
     ◉ Determine Endpoints: The possible minimum and maximum values for 𝒙 are 0 and 50.
          ○ [18:08]. ᴛʜᴇ ᴩᴏɪɴᴛ: By the Extreme Value Theorem, the maximum must occur at one of the following:
               ■ 𝒙 = 0, 𝒙 = 25, or 𝒙 = 50 — all within the interval 𝒙 ∈ [0, 50]
     ◉ Evaluate the Function at Critical Points and Endpoints:
          ○ 𝒜(0) = 0
          ○ 𝒜(25) = 625
          ○ 𝒜(50) = 0
     ◉ Conclusion: The maximum area is 625 square feet when 𝒙 = 25 ft and 𝑦 = 25 ft, forming a square.

● [21:41]. Maximizing the Volume of a Box 
     ◉ Problem: An open box is constructed from a 16×30-inch piece of cardboard by cutting squares of side 𝒙 from each corner and folding up the flaps.
     ◉ Draw a Diagram: Sketch the cardboard with the cut-out squares and the resulting box.
     ◉ Identify the Restriction: The maximum cut size is 8 inches (half the length of the shorter side).
     ◉ Formulate Equations:
          ○ Volume: 𝒱 = 𝒙(30 − 2𝒙)(16 − 2𝒙)
          ○ Restriction: 0 ≤ 𝒙 ≤ 8
     ◉ Simplify the Volume Formula: Expand and combine like terms as needed.
     ◉ Find Critical Points: Take the derivative of 𝒱 with respect to 𝒙, set it to zero, and solve.
          ○ d𝒱/d𝒙 = 12𝒙² − 188𝒙 + 480 = 0
          ○ By factoring or quadratic formula: 𝒙 = 12 or 𝒙 = 10/3
     ◉ Discard Invalid Solutions: 𝒙 = 12 is invalid because it exceeds the restriction.
     ◉ Evaluate the Function at Critical Points and Endpoints:
          ○ 𝒱(0) = 0
          ○ 𝒱(10/3) = … (calculate the volume)
          ○ 𝒱(8) = 0
     ◉ Conclusion: The maximum volume is achieved with a 10/3-inch cut.

  

  Ｍｉｎｉｍｉｚｉｎｇ　Eｘａｍｐｌｅｓ

● [38:33]. Minimizing the Cost of a Pipeline
     ◉ Problem: A pipeline must carry oil from an offshore platform to a refinery on land.
          ○ The pipeline cost is $1 per km offshore and $0.50 per km on land.
          ○ The platform is 5 km from the coast, and the refinery is 8 km along the coast.
     ◉ Draw a Diagram: Sketch the coastline, the offshore platform, the refinery, and the potential pipeline route.
     ◉ Identify the Restriction: The refinery is fixed at 8 km along the coast.
     ◉ Choose a landing point 𝓟 = (x, 0) somewhere along the coast (0 ≤ x ≤ 8) where the total cost is minimized.         
          🗼 (0,5) offshore platform
            | 
            |
            |     Offshore segment (cost $1/km)
            |
            |
            |(0,0)  Landing point A at x km                                                                                            Refinery R
            ─────────────●─────────────────────────────────────────🛢️   (8, 0)
                       <-- x -->          𝓟                                                <--  |8 − x|  →
           <──────────────── Land segment (cost $0.50/km) ───────────────────>
     ◉ Formulate Equations:
          ○ Cost: 𝒞 = (√(𝒙² + 25)) + 0.5(8 − 𝒙)
             (Here, 𝒙 is the distance along the coast from the point directly opposite the platform to the pipeline’s landfall)
          ○ Restriction: 0 ≤ 𝒙 ≤ 8
     ◉ Simplify the Cost Equation: Distribute 0.5 in the expression.
     ◉ Find Critical Points: Take the derivative of 𝒞 with respect to 𝒙, set it to zero, and solve.
          ○ d𝒞/d𝒙 = (𝒙 / √(𝒙² + 25)) − 0.5 = 0
          ○ Solving yields 𝒙 = (5√3) / 3
     ◉ Evaluate the Function at Critical Points and Endpoints:
          ○ 𝒞(0) = 9
          ○ 𝒞((5√3)/3) ≈ 8.33
          ○ 𝒞(8) ≈ 9.43
     ◉ Conclusion: The minimum cost is about $8.33 when 𝒙 ≈ 2.9 km.

● [1:12:12]. Minimizing Material for a Can
     ◉ Problem: Design a cylindrical can that holds 1,000 cm³ of liquid using the least material.
     ◉ Draw a Diagram: Sketch a cylinder, labeling the radius r and height h.
     ◉ Identify the Restriction: The can’s volume is fixed at 1,000 cm³.
     ◉ Formulate Equations:
          ○ Surface Area: 𝒮 = 2πr² + 2πr·h
          ○ Restriction (Volume): πr²h = 1000
     ◉ Solve for One Variable: Solve the volume restriction for h.
          ○ h = 1000 / (πr²)
     ◉ Substitute into the Surface Area Formula:
          ○ 𝒮 = 2πr² + 2πr (1000 / (πr²))
          ○ Simplify: 𝒮 = 2πr² + 2000 / r
     ◉ Find Critical Points: Take the derivative of 𝒮 with respect to r, set it to zero, and solve.
          ○ d𝒮/dr = 4πr − (2000 / r²) = 0
          ○ Solving gives r = ∛(500/π) ≈ 5.42 cm
     ◉ Calculate the Height:
          ○ h ≈ 10.84 cm
     ◉ Verify It’s a Minimum:
          ○ Use the second derivative: d²𝒮/dr² = 4π + (4000 / r³)
          ○ Evaluating at r ≈ 5.42 cm yields a positive result, indicating a minimum.
     ◉ Conclusion: The can uses the least material when r ≈ 5.42 cm and h ≈ 10.84 cm.