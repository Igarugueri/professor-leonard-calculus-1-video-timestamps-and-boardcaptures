-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ４．５ Ｔｈｅ Ｆｕｎｄａｍｅｎｔａｌ Ｔｈｅｏｒｅｍ ｏｆ Ｃａｌｃｕｌｕｓ**---------------------------------





Ｔｈｅ　Ｆｕｎｄａｍｅｎｔａｌ　Ｔｈｅｏｒｅｍ　ｏｆ　Ｃａｌｃｕｌｕｓ（FTC）　　
　　　　　　　　　　　　　　　　 𝒫𝒜𝑅𝒯 Ⅱ

● [2:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=120). Introduction to the Fundamental Theorem of Calculus (FTC) [📷image](../img/Calculus 1 Lecture 4.5/[02-00]-01.png)
     ◉ Visualizing the area under the curve from 𝓪 to 𝓫
          ○ Subtracting areas: area up to 𝓫 minus area up to 𝓪
     ◉ Analogy with distance: 𝓫-𝓪
     ◉ The area as a function
          ○ Definite integrals as areas with specific limits
          ○ Definition of the definite integral as the difference of the antiderivative evaluated at the integration limits
               ■ The area from 𝓪 to 𝓫 is 𝓕(𝓫) - 𝓕(𝓪) (FTC 𝒫𝒜𝑅𝒯 Ⅱ )
          ○ The starting point of the integral does not matter, as long as it’s the same for both limits
          
● FTC, 𝒫𝒜𝑅𝒯 II — “Evaluation Theorem”
     ◉ Connects the definite integral to any antiderivative.
     ◉ Statement of FTC 𝒫𝒜𝑅𝒯 II:
        {
               I̲f̲       𝒇 𝘪𝘴 𝘤𝘰𝘯𝘵𝘪𝘯𝘶𝘰𝘶𝘴 𝘰𝘯 [𝓪, 𝓫] 𝘢𝘯𝘥 𝓕 𝘪𝘴 𝘢𝘯 𝘢𝘯𝘵𝘪𝘥𝘦𝘳𝘪𝘷𝘢𝘵𝘪𝘷𝘦 𝘰𝘧 𝒇 𝘰𝘯 [𝓪, 𝓫] (i.e., 𝓕′(𝒙) = 𝒇(𝒙)),
               t̲h̲e̲n̲  ∫[𝓪, 𝓫] 𝒇(𝒙) 𝒅𝒙 = 𝓕(𝓫) − 𝓕(𝓪).
         }
     ◉ Equivalent form (Net Change Theorem):
         ∫[𝓪, 𝓫] 𝓕′(𝒙) 𝒅𝒙 = 𝓕(𝓫) − 𝓕(𝓪).

     
● [10:45](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=645). Explanation of why +𝓒 is eliminated in definite integrals [📷image](../img/Calculus 1 Lecture 4.5/[10-45]-01.png)
     ◉ The constant cancels when subtracting antiderivatives, it belogs to the same function.
     ◉ The definite integral results in a single number representing area

● [11:49](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=709).  Examples of definite integrals
     ◉ [11:49](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=709). 🧩 Example – 1: ∫[1,5] 𝒙·𝒅𝒙 [📷image](../img/Calculus 1 Lecture 4.5/[11-49]-01.png) 
          ○ Antiderivative: 
               ■ 𝓕(𝒙) = 𝒙²/2
          ○ Evaluate at the bounds:  
               ■ 𝒙²/2 ∣ [1,5] = (5²)/2 − (1²)/2 = 25/2 − 1/2 = 24/2 = 12
     ◉ [14:02](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=842). 🧩 Example – 2: ∫[0,(π/2)] cos(𝒙)·𝒅𝑥 [📷image-1](../img/Calculus 1 Lecture 4.5/[14-02]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[14-02]-02.png)
          ○ Antiderivative:
               ■ 𝓕(𝒙) = sin(𝒙)
          ○ Evaluate at the bounds:  
               ■ sin(𝒙) ∣ [0,π/2]= sin(π/2) − sin(0) = 1 − 0 = 1
          ○ Visualizing the area under the cosine function
               ■ Relation to the circle’s area
               ■ Introduction to the idea of signed net area
     ◉ [18:30](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1110). 🧩 Example – 3: ∫[4,9] 𝒙²·√𝒙 · 𝒅𝒙 [📷image](../img/Calculus 1 Lecture 4.5/[18-30]-01.png)
          ○ Rewrite with exponents:
               ■ √𝒙 = 𝒙¹ᐟ²  ⇒  𝒙²·√𝒙 = 𝒙²·𝒙¹ᐟ² = 𝒙⁵ᐟ²
          ○ Antiderivative::
               ■  𝓕(𝒙) = ∫ 𝒙⁵ᐟ² · 𝒅𝒙 = 𝒙⁷ᐟ² ÷ (7/2)= (2/7)·𝒙⁷ᐟ²
          ○ Evaluate at bounds:
               ■ (2/7)·𝒙⁷ᐟ² ∣ [4,9]
               ■ (2/7)·9⁷ᐟ² − (2/7)·4⁷ᐟ²
          ○ Powers and roots:
               ■ 9⁷ᐟ² = (√9)⁷ = 3⁷ = 2187
               ■ 4⁷ᐟ² = (√4)⁷ = 2⁷ = 128
          ○ Final result:
             (2/7)·2187 − (2/7)·128) = 4118/7
     ◉ [22:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1370). 🧩 Example – 4: ∫[0,π/3] sec²(𝒙)·𝒅𝑥 [📷image](../img/Calculus 1 Lecture 4.5/[22-50]-01.png)
          ○ Antiderivative:
               ■  𝓕(𝒙) = ∫sec²(𝒙)·𝒅𝑥 = tan(𝒙)
          ○ Evaluate at bounds:
               ■  tan(𝒙) ∣ [0,π/3] = tan(π/3) − tan(0) = √3 − 0 = √3
     ◉ [25:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1540). 🧩 Example – 5: Definite integral with reversed limits ∫[0,4] 𝒙³ · 𝒅𝑥 [📷image](../img/Calculus 1 Lecture 4.5/[25-40]-01.png)
          ○ Apply 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.2: Reversing the limits of integration changes the sign of the integral.
               ■ ∫[𝓫,𝓪] 𝒇(𝒙)·𝒅𝒙 = −∫[𝓪,𝓫] 𝒇(𝒙)·𝒅𝒙
               ■ ∫[4,0] 𝒙³·𝒅𝒙 = (𝒙⁴/4)∣[4,0] = (0⁴/4 − 4⁴/4) = −64
               ■ −∫[0,4] 𝒙³·𝒅𝒙 = −[(𝒙⁴/4) ∣ [0,4]]  = −[(4⁴/4 − 0⁴/4)] = −[64] = −64
     ◉ [28:25](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1705). 🧩 Example – 6: ∫[1, -1] (1/𝒙²) ·𝒅𝑥 [📷image-1](../img/Calculus 1 Lecture 4.5/[28-25]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[28-25]-02.png) 
          ○ Rewrite the integrand with negative exponent:
               ■ 𝒙⁻² = 1/𝒙²
          ○ Apply the power rule:
               ■ ∫ 𝒙⁻² · 𝒅𝑥 = 𝒙⁻¹ / (−1) = −1/𝒙
          ○ Evaluate the definite integral:
               ■ [−1/𝒙]∣[0-1,1] = (−1/1) − (−1/−1) = −1 − 1 = −2 ❓
          ○ Analysis of the Result
               ■ This result suggests a **negative area**, which raises concerns because the function 𝒇(𝒙) = 1/𝒙² is **always positive** on its domain. According to:
                    ▣ 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.6: If the function is positive, the integral is positive (and vice versa).
                         ▢ If𝒇(𝒙) ≥ 0 for all 𝒙 ∈ [𝓪,𝓫] then ∫[𝓪,𝓫]𝒇(𝒙) · 𝒅𝑥  ≥ 0
                              ▲ If 𝒇(𝒙) is above the 𝒙-axis, the integral is positive
                         ▢ If𝒇(𝒙) ≤ 0 for all 𝒙 ∈ [𝓪,𝓫] then ∫[𝓪,𝓫]𝒇(𝒙) · 𝒅𝑥  ≤ 0
                              ▲ If 𝒇(𝒙) is below the 𝒙-axis, the integral is negative
               ■ So how can the integral be negative, if the function is positive? The issue lies in the **discontinuity** at 𝒙 = 0.
                    ▣ Discontinuity and Asymptote
                         ▢ The function 𝒇(𝒙) = 1/𝒙² is **undefined at 𝒙 = 0**, and has a **vertical asymptote** there.  
                              ▲ Therefore, the interval [−1, 1] includes a point of discontinuity.  
                         ▢ This means the integral is not proper and **must be treated as an improper integral**, using limits.
                              ▲ The function is unbounded and discontinuous at 𝒙 = 0, leading to an asymptote.
                         ▢ [33:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1980). Graphical interpretation showing how the asymptote affects the area.
                              ▲**Observation:** If, because of the asymptote, some of those rectangles blow up to infinity, then the area can’t be computed.
                         ▢ Domain issue: When an asymptote lies within or at the limit of integration, the integral 
                             may diverge or require special treatment (e.g., improper integrals).
                              ▲**Observation:** If the integrand has a vertical asymptote that makes some Riemann rectangles unbounded, the corresponding
                                   improper integral diverges; therefore, the area is not defined.
          ○ NOTE: 🛡️ Pre-check: Domain & Continuity of the Integrand
               ■ Before applying any property (like 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.6), **you must verify that the integrand 𝒇(𝒙) is continuous on the interval** [𝓪,𝓫].
                    ▣ If 𝒇(𝒙) is **not defined or not continuous** at any point in [𝓪,𝓫], the integral becomes **improper**.
                    ▣ For improper integrals, **standard properties of definite integrals do not necessarily apply**.
                    ▣  In particular, **you cannot directly say that a positive function implies a positive integral** unless the function is continuous throughout the interval.
               ■ **Think about it:**
                                                    **Checklist before integrating:**
                                                1. 📌 Is 𝒇(𝒙) defined at every point in [𝓪,𝓫]?
                                                2. 📌 Is 𝒇(𝒙) continuous on [𝓪,𝓫]?
                    ▣  If **yes**, proceed with Fundamental Theorem & integral properties.
                    ▣ If **no**, analyze the integral as **improper** (i.e., split it or use limits).
     ◉ [37:23](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2243). 🧩 Example – 7: Integrals with piecewise-defined functions [📷image](../img/Calculus 1 Lecture 4.5/[37-23]-01.png)
          ○ ∫[0,6] 𝒇(𝒙) ·𝒅𝑥,  𝒇(𝒙) =  {
                                                      𝒙³      , 𝒙 < 2  
                                                      5𝒙 - 1  , 𝒙 ≥ 2
                                                  }
          ○ Splitting the integral over intervals where the function is defined
               ■ Continuity is required to split the integral properly
          ○ Computing each integral separately:
           ■ ∫[0,2] 𝒙³·𝒅𝒙 = 𝒙⁴∕4 evaluated from 0 to 2 → 2⁴∕4 − 0 = 16∕4 = 4  
      ■ ∫[2,6] (5𝒙−1)·𝒅𝒙 =  
                        = ∫ 5𝒙·𝒅𝒙 = (5𝒙²)/2  
                        = ∫ (−1)·𝒅𝒙 = −𝒙  
                        = [5·6²∕2 − 6] − [5·2²∕2 − 2] = [90−6] − [10−2] = 84 − 8 = 76  
    ■ Total area: 4 + 76 = 80
          ○ **What happens at 𝒙 = 2?**
               ■ At 𝒙 = 2, the function is **discontinuous** (it jumps from one branch to another).  
               ■ Therefore, it is **not differentiable** at that point.  
               ■ **Result:**  There is **no single, continuous antiderivative** on the entire interval [0,6].
          ○ **Can we apply the FTC directly to ∫[0,6] 𝒇(𝒙)·𝒅𝒙?**
               ■ **No.**  
               ■ The **Fundamental Theorem of Calculus – Part II** (the evaluation part) requires that:
                   1. 𝒇(𝒙) is **continuous over** [𝓪,𝓫]  
                   2. There exists a function 𝓕 such that 𝓕′(𝒙) = 𝒇(𝒙)
               ■ In this case, these conditions **are not met** because:
                    ▣ 𝒇(𝒙) is **not continuous at** 𝒙 = 2  
                    ▣ There is **no single function** 𝓕 that differentiates to 𝒇 over [0,6]
          ○ **What should we do instead?**
               ■ Split the interval into parts where the function is continuous:
                    ▣ ∫[0,6] 𝒇(𝒙)·𝒅𝒙 = ∫[0,2] 𝒙³·𝒅𝒙 + ∫[2,6] (5𝒙 − 1)·𝒅𝒙
                    ▣ On each subinterval:
                         ▢ 𝒇(𝒙) is **continuous**  
                         ▢ We can apply **FTC Part II**  
                         ▢ We compute the area using the appropriate antiderivative for each part
          ○ **Think about it:** 
               ■ **Core Idea:** If the Fundamental Theorem of Calculus **cannot be applied directly** because of a **discontinuity inside the interval**,  
                **split the integral into continuous sections**  and apply the theorem to each one **individually**.
          ○ [38:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2320). ❌ if 5𝒙 - 1,    𝒙 > 2, the function 𝒇(𝒙) is **not defined** at 𝒙=2 in the given statement.
               ■ This is a problem because in order to split the definite integral at 𝒙 = 2, the function must be defined at that point.  
     ■ Since 𝒇(𝒙) omits the value at 𝒙 = 2, the expression ∫[0,6] 𝒇(𝒙)·𝒅𝒙 is not properly defined as a standard definite integral.  
     ■ To fix this, the piecewise function must include a definition for 𝒙 = 2, either from the left or the right.  
         



Ｔｏｔａｌ　ａｒｅａ
  
● [46:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2810). Introduction to the concept of total area Vs. signed net area [📷image](../img/Calculus 1 Lecture 4.5/[46-50]-01.png)
     ◉ Explaining the difference between total area and signed net area
          ○ ᴛᴏᴛᴀʟ ᴀʀᴇᴀ: This is calculated by integrating the absolute value of the function over an interval, ensuring all 
               areas contribute positively regardless of whether they are above or below the 𝒙-axis.
               ■ ∫[𝓪,𝓫] | 𝒇(𝒙) |·𝒅𝑥 and | 𝒇(𝒙) | = {
                                                                         𝒇(𝒙),   𝒇(𝒙)  ≥ 0
                                                                        -𝒇(𝒙),   𝒇(𝒙)  < 0
                                                                     }
          ○ ꜱɪɢɴᴇᴅ ɴᴇᴛ ᴀʀᴇᴀ: This result comes from a standard integral without absolute values, where areas above the 𝒙-axis are positive and
           those below are negative, potentially leading to cancellation if regions offset each other.
               ■  ∫[𝓪,𝓫] 𝒇(𝒙)·𝒅𝑥

● [54:25](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=3265).  🧩 Example – Example of total area calculation using sign analysis: 1 - 𝒙² on [0,2] [📷image-1](../img/Calculus 1 Lecture 4.5/[54-25]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[54-25]-02.png)
     ◉ Step 1: Find zeros of 𝒇(𝒙) = 0  
       ○ Solve 1 − 𝒙² = 0 → 𝒙 = ±1  
  ◉ Step 2: Create a sign analysis using these roots (those which are within the integration interval) and the interval limits  
       ○ 𝒙 = 0, 𝒙 = 1, 𝒙 =2
  ◉ Step 3: Determine where 𝒇(𝒙) is positive or negative  
    ○ Positive: [0,1]  
    ○ Negative: [1,2]  
  ◉ Step 4: Split the integral according to the sign of 𝒇(𝒙)  
    ○ Use absolute value:  
      |𝒇(𝒙)| = { 
                                       𝒇(𝒙)  if 𝒇(𝒙) ≥ 0  
              −𝒇(𝒙)  if 𝒇(𝒙) < 0  
                                   }
    ○ So:  
      A = ∫[0,1] (1 − 𝒙²)·𝒅𝒙 + ∫[1,2] −(1 − 𝒙²)·𝒅𝒙  
        = ∫[0,1] (1 − 𝒙²)·𝒅𝒙 − ∫[1,2] (1 − 𝒙²)·𝒅𝒙  
 ◉ Step 5: Integrate and evaluate each interval  
     ○ First integral:  
      ∫[0,1] (1 − 𝒙²)·𝒅𝒙 = [𝒙 − 𝒙³/3] ∣ [0,1]  
        = (1 − 1/3) − (0 − 0) = 2/3  
     ○ Second integral:  
      ∫[1,2] (1 − 𝒙²)·𝒅𝒙 = [𝒙 − 𝒙³/3] ∣ [1,2]  
        = (2 − 8/3) − (1 − 1/3)  
        = (−2/3) − (2/3) = −4/3  
        → with the minus sign from before: −(−4/3) = +4/3  
      ○ Final calculation of total area  
        ■ A = 2/3 + 4/3 = 2 



Ｔｈｅ　ｆｕｎｄａｍｅｎｔａｌ　ｔｈｅｏｒｅｍ　ｏｆ　ｃａｌｃｕｌｕｓ　（FTC）　　
                                                           𝒫𝒜𝑅𝒯  Ⅰ 

● [1:09:08](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4148). The Fundamental Theorem of Calculus (FTC),  𝒫𝒜𝑅𝒯  Ⅰ [📷image](../img/Calculus 1 Lecture 4.5/[1-09-08]-01.png)
     ◉ Derivatives and integrals as inverse operations
     ◉ Defining the area function 𝓐(𝒙) as the integral of 𝒇(𝓉) from a to 𝒙
     ◉ Statement of  FTC  𝒫𝒜𝑅𝒯  Ⅰ :
            {
                I̲f̲       𝘺 = 𝒇(𝒙) 𝘪𝘴 𝘤𝘰𝘯𝘵𝘪𝘯𝘶𝘰𝘶𝘴 𝘰𝘷𝘦𝘳 [𝓪, 𝒙],  
               t̲h̲e̲n̲   𝘵𝘩𝘦 𝘢𝘳𝘦𝘢 𝘪𝘴:  𝒜(𝒙) 𝘴𝘶𝘤𝘩 𝘵𝘩𝘢𝘵 𝒜′(𝒙) = 𝒇(𝒙)  
                                    𝒜(𝒙) = ∫[𝓪, 𝒙] 𝒇(𝓉)·𝒅𝓉
            }
     ◉ Teaching notes:  
       ○ If you define the area function from 𝒫𝒜𝑅𝒯 Ⅰ as 𝒜(𝒙) = ∫[𝓪, 𝒙] 𝒇(t)·𝒅t, then 𝒜′(𝒙) = 𝒇(𝒙),  
    and thus ∫[𝓪, 𝓫] 𝒇(𝒙)·𝒅𝒙 = 𝒜(𝓫) − 𝒜(𝓪).  
    ○ The indefinite integral is a family: ∫ 𝒇(𝒙)·𝒅𝒙 = 𝓕(𝒙) + 𝓒.  
    ■ 𝒫𝒜𝑅𝒯 Ⅱ tells you how to use any 𝓕 to evaluate the definite integral on [𝓪, 𝓫].  
    ○ Typical Calc I hypothesis: 𝒇 continuous on [𝓪, 𝓫] (ensures existence and evaluability).
     ◉  [1:13:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4380). Another interpretation of 𝒜(𝒙)
          ○ 𝒅/𝒅𝑥 [𝒜(𝒙)] = 𝒇(𝒙) → 𝒅/𝒅𝑥 [ ∫[𝓪, 𝒙] 𝒇(𝓉)·𝒅𝓉 ] = 𝒇(𝒙) 

● [1:16:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4610). 🧩 Example – Applying the Fundamental Theorem of Calculus (FTC 𝒫𝒜𝑅𝒯  Ⅰ): 𝒅/𝒅𝑥 [ ∫[1,𝒙] 𝓉⁴·d𝓉 ] [📷image](../img/Calculus 1 Lecture 4.5/[1-16-50]-01.png)
     ◉ 𝒅/𝒅𝑥 [ ∫[1,𝒙] 𝓉⁴·d𝓉 ] = 𝒙⁴
     ◉ Find an antiderivative of 𝓣⁴
                ∫ 𝓉⁴·d𝓉 = 𝓉⁵⁄₅
     ◉ Evaluate the definite integral with limits [1, 𝒙]:
            = 𝒅/𝒅𝑥 [ (𝒙⁵⁄₅) − (1⁵⁄₅) ]
            = 𝒅/𝒅𝑥 [ 𝒙⁵⁄₅ − 1⁄₅ ]
     ◉ Differentiate the result:
              𝒅/𝒅𝑥 [ 𝒙⁵⁄₅ − 1⁄₅ ] = 𝒙⁴
     ◉ **Conclusion:**
          ○ This confirms the **Fundamental Theorem of Calculus (Part I)**:
               ■ If 𝓐(𝒙) = ∫[𝓪,𝒙] 𝒇(𝓉)·d𝓉, then 𝓐′(𝒙) = 𝒇(𝒙) — as long as 𝒇 is continuous.
               
● [1:19:13](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4753).🧩 Example – Applying the Fundamental Theorem of Calculus (FTC 𝒫𝒜𝑅𝒯  Ⅰ): 𝒅/𝒅𝑥 [∫[𝓪, 𝒙] (sin(𝓉)/𝓉)∙𝒅𝓉] [📷image](../img/Calculus 1 Lecture 4.5/[1-19-13]-01.png)
     ◉  Conditions for FTC  𝒫𝒜𝑅𝒯  Ⅰ: continuity and boundedness on the interval
     ◉  𝒅/𝒅𝑥 [∫[𝓪, 𝒙] (sin(𝓉)/𝓉)∙𝒅𝓉] = sin(𝒙)/𝒙



Ｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌｓ　ｗｉｔｈ　ｓｕｂｓｔｉｔｕｔｉｏｎ

● [1:21:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4860). Definite integrals with substitution
     ◉ Introduction to the substitution method in definite integrals
          ○ Two main approaches
      
● [1:22:19](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4939). 𝓜𝓮𝓽𝓱𝓸𝓭 I [📷image](../img/Calculus 1 Lecture 4.5/[1-22-19]-01.png)
     ◉ No change to integration limits; substitute back to 𝒙 before evaluating.
     ◉ 🧩 Example – Definite Integral with Substitution (Method 1): ∫[0,2] 4𝒙(𝒙² - 1)³ ·𝒅𝑥
          ○ Substitution, finding 𝒅𝓾 and expressing 𝒅𝑥:  
                𝓾 = 𝒙² − 1  
                𝒅𝓾 = 2𝒙·𝒅𝒙  
               𝒅𝓾 / 2𝒙 = 𝒅𝒙  
          ○ Rewrite integral:  
                 ∫[0,2] 4𝒙·(𝒙² − 1)³·𝒅𝒙  
                 = ∫[0,2] 2·𝓾³·𝒅𝓾  
                 = 2 ∫[0,2] 𝓾³·𝒅𝓾  
          ○ Integration:  
                 ∫ 𝓾³·d𝓾 = 𝓾⁴/4  
                → 2·(𝓾⁴/4) = 𝓾⁴/2  
          ○ Back-substitution (don’t change bounds): 
                  𝓾⁴/2 → ( (𝒙² − 1)⁴ / 2 ) ∣ [0,2]
          ○ Evaluate:  
                 = [ (2² − 1)⁴ / 2 ] − [ (0² − 1)⁴ / 2 ]  
                 = [ (3)⁴ / 2 ] − [ (−1)⁴ / 2 ]  
                 = (81/2) − (1/2)  
                 = 40  
             
● [1:33:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=5630). 𝓜𝓮𝓽𝓱𝓸𝓭 II [📷image](../img/Calculus 1 Lecture 4.5/[1-33-50]-01.png)
     ◉ Change the limits to match 𝓾; no resubstitution. 
     ◉ **NO** Back-substitution
     ◉ 🧩 Example – Definite Integral with Substitution (Method 2): ∫[0,2] 4𝒙(𝒙² - 1)³ ·𝒅𝑥
          ○ Substitution:  
                 𝓾 = 𝒙² − 1  
                 𝒅𝓾 = 2𝒙·𝒅𝒙  
                 𝒅𝓾 / 2𝒙 = 𝒅𝒙  
          ○ Change bounds:  
                 If 𝒙 = 2 → 𝓾 = 2² − 1 = 3  
                 If 𝒙 = 0 → 𝓾 = 0² − 1 = −1  
          ○ Rewrite integral:  
                ∫[0,2] 4𝒙·(𝒙² − 1)³·𝒅𝒙  
                = ∫[−1,3] 2·𝓾³·𝒅𝓾  
                = 2 ∫[−1,3] 𝓾³·𝒅𝓾  
          ○ Integration:  
                ∫ 𝓾³·𝒅𝓾 = 𝓾⁴/4  
               → 2·(𝓾⁴/4) = 𝓾⁴/2  
          ○ Evaluate:  
                [ 𝓾⁴/2 ]∣[−1,3]  
               = (3⁴ / 2) − ((−1)⁴ / 2)  
               = (81/2) − (1/2)  
               = 40  
          ○ **Conclusion:**  
               ■ By changing the bounds to match the substitution,  
                    ▣ there is **no need to back-substitute** into 𝒙.                    
 
● [1:41:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6060). Discussion of both methods and common errors

● [1:45:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6340). 🧩 Example – Definite Integral with Substitution (Method 2): ∫[0, π/8] sin⁵(2𝒙) · cos(2𝒙) · 𝒅𝑥 [📷image-1](../img/Calculus 1 Lecture 4.5/[1-45-40]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[1-45-40]-02.png)
     ◉ ∫[0, 7π/8] [sin(2𝒙)]⁵· cos(2𝒙) · 𝒅𝑥
          ○ The integral is rewritten in the form [𝓰(𝒙)]ⁿ · 𝓰′(𝒙), which is exactly the pattern for applying the reverse chain rule (substitution).
     ◉ 𝓾 = sin(2𝒙)
          ○ 𝒅𝓾 = 2cos(2𝒙)·𝒅𝒙  ⟹  𝒅𝒙 = 𝒅𝓾 / (2cos(2𝒙))
     ◉ [1:51:02](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6662). Converting original 𝒙-limits into new 𝓾-limits
          ○ 𝒙 = 0 ⟹ 𝓾 = sin(0) = 0  
          ○ 𝒙 = 7π/8 ⟹ 𝓾 = sin(2π/8) = (√2) / 2
     ◉ Substituting and integrating
          ○ ∫[0,√2/2] 𝓾⁵ · (𝒅𝓾 / 2)  
             = (1/2) ∫[0,(√2) / 2] 𝓾⁵·𝒅𝓾  
             = (1/2) · [𝓾⁶/6] ∣ [0,(√2) / 2] 
             = (1/12)·[((√2) / 2)⁶ − 0]  
             = (1/12)·(8/64)  
             = (1/12)·(1/8)  
             = 1/96 
               
● [1:57:15](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=7035). 🧩 Example – Definite Integral with Substitution (Method 2): ∫[2, 5] (2𝒙 - 5)∙(𝒙 - 3)⁹· 𝒅𝑥  [📷image-1](../img/Calculus 1 Lecture 4.5/[1-57-15]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[1-57-15]-02.png)
     ◉ Substitution: 𝓾 = 𝒙 - 3, so that: 𝒅𝓾 = 𝒅𝑥
     ◉ The integration limits change:
          ○ When 𝒙 = 2 → 𝓾 = 2 - 3 = -1
          ○ When 𝒙 = 5 → 𝓾 = 5 - 3 = 2
     ◉ Rewriting 2𝒙 - 5 in terms of 𝓾:
          ○ Since 𝒙 = 𝓾 + 3, then:  2𝒙 - 5 = 2(𝓾 + 3) - 5 = 2𝓾 + 6 - 5 = 2𝓾 + 1
     ◉ Substituting into the integral:  
          ∫[-1, 2] (2𝓾 + 1)·𝓾⁹·𝒅𝓾
             = ∫[-1, 2] (2𝓾¹⁰ + 𝓾⁹)·𝒅𝓾
             = [ (2𝓾¹¹)/11 + (𝓾¹⁰)/10 ] ∣ [-1,2]
     ◉ Evaluation:
          = ( (2·2¹¹)/11 + (2¹⁰)/10 ) − ( (2·(−1)¹¹)/11 + ((−1)¹⁰)/10 )  
          = ( 4096/11 + 1024/10 ) − ( −2/11 + 1/10 )  
          = 4096/11 + 1024/10 + 2/11 − 1/10  
          = 4098/11 + 1023/10  
     ◉ Final simplified result:
          = 52,233 / 110
               
● [2:11:29](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=7889). 🧩 Example – Definite Integral with Substitution (Method 2): ∫[1, 3] [cos(π/𝒙)/𝒙²]·𝒅𝑥 [📷image-1](../img/Calculus 1 Lecture 4.5/[2-11-29]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[2-11-29]-02.png)
     ◉ Substitution: 𝓾 = π/𝒙; 𝒅𝓾 = -π𝒙⁻² · 𝒅𝑥
     ◉ Changing the limits:
          ○ 𝒙 = 3 → 𝓾 = π/3
          ○ 𝒙 = 1 → 𝓾 = π
     ◉ Rewriting the integral:
          ○ ∫[π/3, π] cos(𝓾) · (-π/𝒙²) · 𝒅𝑥
     ◉ Substituting 𝒅𝑥:
          ○ ∫[π/3, π] cos(𝓾) · (-1/π) · 𝒅𝓾
     ◉ Applying the  𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.4.2 (indefinite interaks) of sign change in limits:
          ○ (-1/π)·∫[π, π/3] cos(𝓾)·𝒅𝓾 = (1/π)·∫[π/3, π] cos(𝓾)·𝒅𝓾
               ■ ∫[𝓫,𝓪]𝒇(𝒙) 𝒅𝑥 = - ∫[𝓪,𝓫]𝒇(𝒙)·𝒅𝑥
     ◉ Final evaluation:
          ○ (1/π)·[sin(𝓾)]∣[π/3, π]
          ○ (1/π)·(sin(π) − sin(π/3))
          ○ (1/π)·(0 − √3/2) = −√3 / (2π)
 


Ｉｎｔｅｇｒａｌｓ　ｏｆ　ｅｖｅｎ　ａｎｄ　ｏｄｄ　ｆｕｎｃｔｉｏｎｓ

● [2:26:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=8800). Introduction

● [1:27:30](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=5250). ᴇᴠᴇɴ ꜰᴜɴᴄᴛɪᴏɴꜱ [📷image](../img/Calculus 1 Lecture 4.5/[1-27-30]-01.png)
     ◉ 𝒇(-𝒙) = 𝒇(𝒙), showing symmetry about the y-axis
     ◉ Symmetry: The function is symmetric with respect to the y-axis, which means that if we reflect any point on the
         graph over the vertical axis (y-axis), we obtain another point that also belongs to the graph.
     ◉  𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.1 of integrating an even function over [-a, a]
          ○ If 𝒇(𝒙) is even: ∫[-a, a]𝒇(𝒙)∙𝒅𝑥 = 2 · ∫[0, a] 𝒇(𝒙)∙𝒅𝑥
     ◉ [2:32:30] 🧩 Example – even function: ∫[-2, 2] (𝒙² + 4)·𝒅𝑥 [📷image](../img/Calculus 1 Lecture 4.5/[2-32-30]-01.png)
          ○ Step 1: Identify symmetry
               ■ 𝒇(−𝒙) = (−𝒙)² + 4 = 𝒙² + 4 = 𝒇(𝒙) → 𝒇 is **even**
          ○ Step 2: Apply property of even functions
               ■ ∫[−𝓪, 𝓪] 𝒇(𝒙)·𝒅𝑥 = 2∫[0, 𝓪] 𝒇(𝒙)·𝒅𝑥
               ■ ∫[−3, 3] (𝒙² + 4)·𝒅𝑥 = 2∫[0, 3] (𝒙² + 4)·𝒅𝑥
          ○ Step 3: Compute the integral
                ■ 2 [ (𝒙³/3 + 4𝒙) ]∣[0, 3]
               ■ = 2 [ (27/3 + 12) − 0 ]
               ■ = 2 (9 + 12) = 2(21) = 42          
 
● [2:36:10](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=9370). ᴏᴅᴅ ꜰᴜɴᴄᴛɪᴏɴꜱ [📷image](../img/Calculus 1 Lecture 4.5/[2-36-10]-01.png)
     ◉ 𝒇(-𝒙) = -𝒇(𝒙), showing symmetry about the origin.
     ◉ Symmetry: The function exhibits symmetry with respect to the origin, which means that if we rotate any 
         point on the graph 180 degrees around the origin (switching the signs of both coordinates), we obtain another point that 
         also belongs to the graph.
     ◉ 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.2  of integrating an odd function over [-a, a]
          ○ If 𝒇(𝒙) is odd: ∫[-a, a] 𝒇(𝒙)∙𝒅𝑥 = 0
     ◉ [2:42:10](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=9730) 🧩 Example – odd function: [-3, 3] sin(𝒙)  /  √(1 + 𝒙²) ·𝒅𝑥 [📷image](../img/Calculus 1 Lecture 4.5/[2-42-10]-01.png)
          ○ Step 1: Define the function
               ■ 𝒇(𝒙) = sin(𝒙) / √(1 + 𝒙²)
          ○ Step 2: Test odd/even symmetry
               ■ 𝒇(−𝒙) = sin(−𝒙) / √(1 + (−𝒙)²) 
                        = (−sin(𝒙)) / √(1 + 𝒙²) 
                        = −𝒇(𝒙)
               ■ Therefore, 𝒇(𝒙) is **odd**.
          ○ Step 3: Apply 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.2 of odd functions
               ■ For any odd function, the areas on symmetric intervals [−𝓪,0] and [0,𝓪] cancel out:
                    ▣ From 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.4.5 of definite integrals:
                         ▢ ∫[−𝓪, 𝓪] 𝒇(𝒙)·𝒅𝑥 = ∫[−𝓪, 0] 𝒇(𝒙)·𝒅𝑥 + ∫[0, 𝓪] 𝒇(𝒙)·𝒅𝑥
                    ▣ Since 𝒇(−𝒙) = −𝒇(𝒙), the negative side is the exact opposite of the positive side.
                    ▣ Thus, the two contributions cancel each other out.
               ■ Conclusion: ∫[−𝓪, 𝓪] 𝒇(𝒙)·𝒅𝑥 = 0