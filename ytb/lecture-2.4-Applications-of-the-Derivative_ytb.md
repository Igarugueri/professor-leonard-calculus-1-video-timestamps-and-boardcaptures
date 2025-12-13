-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．４　Aｐｐｌｉｃａｔｉｏｎｓ　Oｆ　Tｈｅ　Dｅｒｉｖａｔｉｖｅ**---------------------------------




I ｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ａｐｐｌｉｃａｔｉｏｎｓ　ｏｆ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ

● [00:01]. Introduction to Applications of the Derivative


Ａｐｐｌｉｃａｔｉｏｎｓ　ｉｎ　ｓａｌｅｓ　（ｄｖｄ　ｅｘａｍｐｌｅ）

● [00:29]. 🧩 Applications in Sales (DVD Example).png)
     ◉ [01:30]. Sales Model 𝑺(𝒕) over time 𝒕 (in years)
          ○ 𝑺(𝒕) =  7𝒕 / (𝒕² + 1)
          ○ Time 𝒕 must be greater than or equal to zero (𝒕 ≥ 0) since you cannot go back in time
          ○ Interpretation of initial sales (at 𝒕=0): at the start, no DVDs have been sold
     ◉ [02:45]. Objectives of the Sales Model Analysis
           ➀ Find the rate of change of sales
           ➁ Find when sales will reach their peak
           ➂ Find how quickly sales increase right when the movie is released (at 𝒕=0)
     ◉ [04:40]. ➀ Calculating the Rate of Change (the derivative 𝑺'(𝒕) or 𝒅𝑺/𝒅𝒕)
          ○ The rate of change is the slope
          ○ Notation of the derivative with respect to 𝒕: 𝒅/𝒅𝒕
          ○ Using the Quotient Rule to derive 𝑺(𝒕)
          ○ 𝑺'(𝒕) = [(𝒕² + 1)·d/d𝒕[7𝒕] − 7𝒕·d/d𝒕[𝒕² + 1]] / (𝒕² + 1)²
          ○ = [7(𝒕² + 1) − 7𝒕·2𝒕] / (𝒕² + 1)²
          ○ = [7𝒕² + 7 − 14𝒕²] / (𝒕² + 1)²  = (7 − 7𝒕²) / (𝒕² + 1)²
          ○ Formula for the rate of change 𝑺'(𝒕) = (7 - 7𝒕²) / (𝒕² + 1)²
          ○ **Interpretation: it tells how fast sales are increasing or decreasing at any moment 𝒕**
     ◉ [09:10]. ➁  Finding when sales reach their peak
          ○  At a peak (maximum point), the slope (rate of change) is zero, since the function changes from increasing to decreasing
          ○ Set the derivative to zero to find where the slope is horizontal: 𝑺'(𝒕) = 0
          ○ For a rational function to be zero, the numerator must be zero (the denominator cannot be zero or the function is undefined)
          ○ Set 𝑺'(𝒕) = 0:
               ■ (7 − 7𝒕²) / (𝒕² + 1)² = 0
               ■ 7 − 7𝒕² = 0    →    7 = 7𝒕²    →    𝒕² = 1
               ■ Solutions: 𝒕 = +1, −1
          ○ Validating the time: since the domain is 𝒕 ≥ 0, 𝒕 = -1 is not valid; thus, 𝒕 = 1 is valid
          ○ **Conclusion: Sales reach their peak exactly one year later (at 𝒕=1)**
     ◉ [13:50]. ➂ Finding the initial rate of increase of sales (at 𝒕=0)
          ○ The movie release moment is 𝒕=0
          ○ Evaluate the rate of change function (derivative 𝑺'(𝒕)) at 𝒕=0: 𝑺'(0)
          ○ 𝑺'(0) = (7 − 7(0)²) / (0² + 1)² = 7 / 1 = 7
          ○ **Interpretation: Sales initially increase at a rate of 7 (units, likely millions of DVDs/year) at launch**
           


Ａｐｐｌｉｃａｔｉｏｎｓ　ｉｎ　ｐｈｙｓｉｃｓ　（ｋｉｎｅｍａｔｉｃｓ）

● [17:00]. Applications in Physics (Kinematics).png)
     ◉ Relationship between Position 𝑺(𝒕), Velocity 𝓥(𝒕), Acceleration 𝓐(𝒕), and Jerk
          ○ Velocity 𝓥(𝒕) is the first derivative of Position 𝑺(𝒕) with respect to time 𝒕: 𝓥(𝒕) = 𝑺'(𝒕)
               ■ Velocity is how your position is changing with respect to time
          ○ Acceleration 𝓐(𝒕) is the derivative of Velocity 𝓥(𝒕), i.e., the second derivative of Position: 𝓐(𝒕) = 𝓥'(𝒕) = 𝑺''(𝒕)
               ■ Acceleration is how your velocity is changing with respect to time
          ○ Jerk is the derivative of Acceleration 𝓐(𝒕), i.e., the third derivative of Position: Jerk(𝒕) = 𝓐'(𝒕) = 𝓥''(𝒕) = 𝑺'''(𝒕)
               ■ Jerk describes how acceleration is changing with respect to time
     ◉ [21:52]. 🧩 Example –: 𝑺(𝒕) =  2𝒕³ - 15𝒕² + 24𝒕) Finding Acceleration and Jerk from a Position function (in 𝒕 seconds).
          ○ Find the Velocity function (first derivative): 𝑺'(𝒕) = 6𝒕² − 30𝒕 + 24
               ■ Find the Acceleration function (second derivative: 𝑺''(𝒕) = 12𝒕 − 30
          ○ Find the Jerk function (third derivative: 𝑺'''(𝒕) = 12     
          ○ Identify the calculated functions as Velocity, Acceleration, and Jerk
     ◉ [24:47]. Calculating Acceleration at a specific moment (e.g., 𝒕=3 seconds)
          ○ Evaluate Acceleration 𝓐(𝒕) at 𝒕=3: 𝓐(3)
          ○ 𝓐(3) = 6 (units, e.g., ft/s²)
     ◉ [25:41]. Find when Acceleration is zero
          ○ Set the Acceleration function to zero: 𝓐(𝒕) = 0
          ○ Solve 12𝒕 - 30 = 0 for 𝒕
          ○  𝒕 = 2.5 seconds
          ○ Interpretation: At 𝒕=2.5 s, acceleration is momentarily zero, indicating a change in how velocity is changing
            


Ａｐｐｌｉｃａｔｉｏｎｓ　ｉｎ　ｐｒｏｊｅｃｔｉｌｅｓ　（ｆｉｒｅｗｏｒｋｓ　ｅｘａｍｐｌｅ）

● [27:40]. Applications in Projectiles (Fireworks Example) 
     ◉ 🧩 Example –: 𝑺(𝒕) = -16𝒕² + 256𝒕 Model for height (Position 𝑺(𝒕)) of a firework at time 𝒕
          ○ **Initial height interpretation: since there is no constant term, the initial height is zero (it starts from the ground)**
          ○ [28:50]. Objective: Find the maximum height
               ■ The maximum height occurs where the Velocity 𝓥(𝒕) is zero
               ■ Velocity 𝓥(𝒕) is the first derivative of the height function 𝑺(𝒕): 𝓥(𝒕) = 𝑺'(𝒕)
                    ▣ 𝓥(𝒕) = 𝑺'(𝒕) = -16𝒕 + 256
               ■ Set Velocity to zero: 𝓥(𝒕) = 0 and solve for 𝒕
                    ▣ 𝓥(𝒕) = -16𝒕 + 256 = 0
                    ▣ Result: 𝒕 = 8 seconds
               ■ **Interpretation: The firework reaches its maximum height at 8 seconds, the optimal time for it to explode and be visible**

          

Ａｐｐｌｉｃａｔｉｏｎｓ　ｉｎ　ｂｕｓｉｎｅｓｓ　ａｎｄ　ｅｃｏｎｏｍｉｃｓ　（ｍａｒｇｉｎａｌ　ｃｏｓｔ）

● [32:10]. Applications in Business and Economics (Marginal Cost)
     ◉ Definition of Marginal Cost
          ○ Marginal cost refers to the additional cost incurred by producing one more unit of a good or service.
               ■ Economic Decision-Making: Businesses use marginal cost analysis to decide whether producing an additional unit will be profitable. 
                  If revenue from selling one more unit exceeds its marginal cost, it is beneficial to produce that unit.
                    ▣ Before deciding to significantly increase production, companies analyze whether the extra revenue they will receive from selling more outweighs the increasingly higher marginal cost.
                           If the selling price is greater than the marginal cost, it’s worth producing more. If not, it’s better to stop there.
                    ▣ **Production decisions are made based on the current level of output (“Should I produce one more unit or not?”).**
                           That’s why marginal cost is useful for deciding whether it’s worth increasing production — and for that, you need to know how much the next unit at your current level will cost.
          ○ It is the rate of change of the total production cost
          ○ Marginal Cost is the first derivative of the total cost function 𝑪(𝒙), where 𝒙 is the number of items produced: Marginal Cost = 𝑪'(𝒙)
               ■ **Just as velocity is the rate at which position changes with respect to time, marginal cost is the rate at which total cost changes with respect to quantity.**
                    In essence, 𝑪′(1) ≈ 𝑪(2) − 𝑪(1) captures the idea of how cost increases when producing one more unit from the current level — it’s not about the cost of the first unit itself,
                    but the _additional_ cost at the margin.
     ◉ [32:59]. 🧩 Example –: 𝑪(𝒙) = -0,2𝒙² + 200𝒙 + 9000, of a Total Cost function 𝑪(𝒙).png) 
          ○ Interpretation of initial cost (at 𝒙=0): it is the cost when nothing is produced
               ■ Initial cost (overhead) is 𝑪(0) = 9.000$
     ◉ [36:00]. Calculating the Marginal Cost function (the derivative 𝑪'(𝒙))
          ○ 𝑪'(𝒙) = - 0,4𝒙 + 200
               ■ Calculate Marginal Cost for the 100th item: 𝑪'(100)
                    ▣ Result: 𝑪'(100) = $160 (estimated cost to produce item 101)
               ■ Calculate Marginal Cost for the 101st item: 𝑪'(101)
                    ▣ Result: 𝑪'(101) = $159.60 (estimated cost to produce item 102)
               ■ Calculate Marginal Cost for the 150th item: 𝑪'(150)
                    ▣ Result: 𝑪'(150) = $140 (estimated cost to produce item 151)
               ■ Interpretation: Marginal Cost decreases as more items are produced (the slope of the cost function is negative in this range),
                  meaning it costs less to produce extra items as production increases
    
