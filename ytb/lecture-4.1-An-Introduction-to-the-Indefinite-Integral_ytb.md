-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　４．１　Aｎ　Iｎｔｒｏｄｕｃｔｉｏｎ　Tｏ　Tｈｅ　Iｎｄｅｆｉｎｉｔｅ　Iｎｔｅｇｒａｌ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

●[0:08]. A change in focus: from derivatives to integrals.
     ◉ The two main problems of calculus:
          ○ Finding the slope of a curve at a point (derivatives).
          ○ Finding the area under a curve.
     ◉ [0:44]. Two methods to find the area under a curve:
          ○ The rectangular method.
          ○ The antiderivative method.

● [1:50]. ᴛ̳ʜ̳ᴇ̳ ̳ʀ̳ᴇ̳ᴄ̳ᴛ̳ᴀ̳ɴ̳ɢ̳ᴜ̳ʟ̳ᴀ̳ʀ̳ ̳ᴍ̳ᴇ̳ᴛ̳ʜ̳ᴏ̳ᴅ̳   
     ◉ Method description: divide the interval into equal subsections, create a rectangle for each subsection.  
          ○ Divide [𝓪,𝓫] into n equal subsections — equal width ensures uniformity in the calculation.  
               ■ Width of each rectangle: Δx = (𝓫 − 𝓪) / n.  
               ■ If widths were different, each rectangle’s area would need separate handling.  
          ○ Different ways to determine the height of the rectangles:  
               ■ Left endpoints → use 𝒇(𝒙ᵢ) at the start of each subinterval.  
               ■ Right endpoints → use 𝒇(𝒙ᵢ) at the end of each subinterval.  
               ■ [5:45]. Midpoints → use 𝒇 at the middle of each subinterval.  
               ■ In all cases, the height corresponds to the value of the function at the chosen point.  
     ◉ [6:50]. Calculation of the approximate area by summing the areas of the rectangles.  
          ○ [7:58]. Improving the approximation: increasing the number of rectangles.  
               ■ The more rectangles I have, the better the approximation becomes.  
          ○ [8:20]. As the number of rectangles (n) approaches infinity, the space between them approaches zero,  
                         improving the approximation.  
               ■ Consequence: For a better approximation, make the space between each interval (the width of the rectangles) approach zero.  
     ◉ Note:  
          ○ If the function dips below the x-axis in any subinterval, the corresponding rectangle will have negative area in the sum.  

● [11:15]. ᴛ̳ʜ̳ᴇ̳ ̳ᴀ̳ɴ̳ᴛ̳ɪ̳ᴅ̳ᴇ̳ʀ̳ɪ̳ᴠ̳ᴀ̳ᴛ̳ɪ̳ᴠ̳ᴇ̳ ̳ᴍ̳ᴇ̳ᴛ̳ʜ̳ᴏ̳ᴅ̳   
     ◉ [12:15]. Introduction to the area function 𝓐(𝒙).
     ◉ [13:20]. Key relationship: the derivative of the area function is the original function.
          ○ If 𝒜(𝒙) is the area function for some 𝒇(𝒙) on [𝓪,𝓫], then: 𝒜'(𝒙) = 𝒇(𝒙) or 𝒅/𝒅𝒙 [𝓐(𝒙)] = 𝒇(𝒙)
                                                   ↓ this implies ↓
          ○ [15:00]. Finding the area under the curve involves undoing the derivative (finding the antiderivative).
               ■ The antiderivative is the area under the curve.
          ○ [18 :45]. 🧩 Example  – Demonstration of the relationship between the area function and the original function.
               ■ 𝒇(𝒙) = 𝒙 + 1  Find area on [−1, 𝒙]
               ■ Geometric picture (for 𝒙 ≥ −1):
                    ▣ On [−1, 𝒙], the graph of 𝒇 is a line of slope 1 with 𝒇(−1) = 0.
                    ▣ The region under 𝒇 from −1 to 𝒙 is a right triangle.
                         ▢ base = 𝒙 − (−1) = 𝒙 + 1
                         ▢ height = 𝒇(𝒙) = 𝒙 + 1
                    ▣ Area function:
                         ▢  𝒜(𝒙) = (1/2)·base·height = (1/2)·(𝒙 + 1)·(𝒙 + 1)
                                                                       = (1/2)·(𝒙² + 2𝒙 + 1)
                                                                       = 𝒙²/2 + 𝒙 + 1/2
                    ▣ Differentiate 𝒜(𝒙):
                         ▢ 𝒜′(𝒙) = 𝒅/d𝒙 [ 𝒙²/2 + 𝒙 + 1/2 ] = 𝒙 + 1 = 𝒇(𝒙)
                    ▣ Takeaway (a preview of a powerful upcoming result):
                         ▢ The derivative of the area-under-the-curve function equals the original integrand:
                              ▲ 𝒜′(𝒙) = 𝒇(𝒙).
                         ▢ 𝒜(𝒙) gives the (signed) area from −1 to 𝒙; for 𝒙 ≥ −1 it matches the triangle’s area above.
                         ▢ NOTE:
                                         – The rate of change of the area function 𝒜(𝒙) equals the original function 𝒇(𝒙).
                                         – This is an early glimpse of a deep connection between differentiation and finding areas — a connection
                                            we will formalize later.
          ○ [26:20]. 🧩 Example  – : Find area under 𝒇(𝒙) = 𝒙² on [0, 1]
               ■ Idea:
                    ▣ If 𝒇(𝒙) = 𝒙² and the area function 𝒜(𝒙) satisfies 𝒜′(𝒙) = 𝒇(𝒙), then we have: 𝒜′(𝒙) = 𝒙².
                    ▣ Question: Can we find a function 𝒜(𝒙) whose derivative is 𝒙²?
               ■ Trial and correction:
                    ▣ Guess: 𝒜(𝒙) = 𝒙³  
                          – Derivative: 𝒜′(𝒙) = 3𝒙² → too large (factor of 3).
                    ▣ Adjust: 𝒜(𝒙) = 𝒙³ / 3  
                          – Derivative: 𝒜′(𝒙) = 𝒙² → correct.
                    ▣ NOTE: Adding a constant does not change the derivative:
                                    𝒜(𝒙) = (𝒙³ / 3) + 7  → 𝒜′(𝒙) = 𝒙² ✔
                                    𝒜(𝒙) = (𝒙³ / 3) + 𝒞 → 𝒜′(𝒙) = 𝒙² ✔
               ■ General form of the area function:
                    ▣ 𝒜(𝒙) = (𝒙³ / 3) + 𝒞, where 𝒞 is any constant.
                    ▣ This tells us that all antiderivatives of 𝒙² differ by a constant.
               ■ Takeaway (preview of a powerful upcoming result):
                    ▣ The process of finding the area function is essentially finding an antiderivative.
                    ▣ Later, we will formalize the connection between the area and the antiderivative
                       using the Fundamental Theorem of Calculus.
               ■ [31:20]. The importance of the constant "𝓒" in the antiderivative: it represents a family of curves.
                    ▣ [33:30]. 𝒜(𝒙) = (1/3)𝒙³ + 𝓒
                         ▢ 𝓒 is a constant
                         ▢ 𝓒 is an 𝑦-axis intercept
                         ▢ 𝓒 can be found by 𝒙 = 0
                         ▢ When we talk about the family of curves (or the family of antiderivatives), we refer to all the functions that, when derived, 
                              yield the same original function. For example, if 𝒅/𝑑𝑥 [𝓕(𝒙)] = 𝒇(𝒙), then the family of antiderivative is written as 𝓕(𝒙) + 𝓒,
                              where 𝓒 is a real constant. Each value of 𝓒 defines a different vertical shift in the graph (⇡), but all those curves share the same derivative 𝒇(𝒙). 
                              That’s why we say there is a family of curves with the same slope at every point.
                    ▣ [34:50]. How is the area on [0,𝓍] defined, and what is the role of the initial constant 𝓒 on 𝒜(𝒙) = (1/3)𝒙³ + 𝓒
                         1.  Area at a single point:
                              When we talk about “the area from 0 to 𝓍” over the interval [0, 𝓍], it’s important to note that the interval [0, 0] has no “width.”
                              Therefore, the area within [0, 0]. is 0 (single point: there’s no space to generate area).
                                  → this implies 𝒜(0) = 0  (◈)
                         2. Constant of integration 𝓒:
                              2.1 When defining a function 𝒜(𝓍) that measures the area over [0, 𝓍], it is usually expressed as:
                                         𝒜(𝓍) = (area over [0, 𝓍]) + 𝓒.
                                    If we want the area to be 0 when 𝓍 = 0, it must satisfy:
                                         𝒜(0) = 0 + 𝓒 
                                         𝒜(0) = 𝓒  (◈◈)
                                    Furthermore, from (◈) and (◈◈) if we assume that 𝒜(0) = 0 (meaning “there’s no accumulated area at 𝓍 = 0”), then 𝓒 = 0.
                              2.2 Hence on find area under 𝒇(𝒙) = 𝒙² on [0, 1]
                                        𝒜(𝒙) = (1/3)𝒙³  and 𝒜(1) = 1/3 on the interval [0,1]
                       3. When the problem allows an initial offset (𝓒 ≠ 0):
                           In some cases, the function 𝒜(𝓍) may be defined with a nonzero initial value. For example, if at 𝓍 = 0 there is 
                           alrea𝒅𝑦 an “initial area” of 5 units, then:
                                       𝒜(0) = 5 ⟹ 𝓒 = 5.
                         Thus, the constant 𝓒 adjusts to the initial condition required by the problem.
                    ▣ In summary, 𝓒 vertically shifts the area function 𝒜(𝓍) and sets the initial accumulated area. When no area is accumulated at the start, 𝓒 = 0.



Ｔｈｅ　ｉｎｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌ

● [41:00]. Introduction.
     ◉ Definition of the indefinite integral: **it has no defined limits**.
     ◉ The indefinite integral represents the area function  𝒜(𝒙), not a specific area.
      
● [43:00]. Formal definition of antiderivative. 
     ◉ Given a function, 𝒇, on some interval, 𝐼, 
          ○ 𝓕 is called an antiderivative, if  𝓕'(𝓍) = 𝒇(𝓍) (or 𝒅/𝒅𝒙 [𝓕(𝒙)] = 𝒇(𝒙))
               ■ 𝓕(𝓍) = 𝒜(𝒙)
     ◉ [45:45]. 🧩 Example –: 𝒇(𝒙) = 𝒙² 𝓕(𝒙) = (1/3)𝒙³ this is one antiderivative and Why?...
          ○ ... Because 𝒅/𝒅𝒙 [𝓕(𝒙)]  = 𝒅/𝒅𝒙 [(1/3)𝒙³]  = 𝒙² = 𝒇(𝒙)
          ○ ... Because 𝒅/𝒅𝒙 [𝓕(𝒙)]  = 𝒅/𝒅𝒙 [(1/3)𝒙³ + 4]  = 𝒙² = 𝒇(𝒙)
          ○ 𝓕(𝒙) = (1/3)𝒙³ + 𝓒  This represents all possible antiderivatives of 𝒇(𝒙) = 𝒙²
     ◉ [49:10]. The process to find the antiderivative is also colled ɪ̳ɴ̳ᴛ̳ᴇ̳ɢ̳ʀ̳ᴀ̳ᴛ̳ɪ̳ᴏ̳ɴ̳. 

● [51:25]. Notation for the indefinite integral. 
     ◉ Another way to write:
          ○ 𝒅/𝒅𝒙 [𝓕(𝒙) + 𝓒] = 𝒇(𝒙))  is:
               ■ 𝓕(𝒙) + 𝓒 = ∫ 𝒇(𝒙) ⋅ 𝒅𝒙  (The indefinite integral)
                    ▣ The symbol ∫ represents the integral.
                    ▣ 𝒅𝒙 indicates the variable of integration (𝒙)  or 𝒅𝓉 if the variable is 𝓉.
                    ▣ 𝓒 represents an arbitrary constant.
          ○ [54:25]. Interpretation of the notation: find the antiderivative of 𝒇(𝒙) with respect to 𝒙.
     ◉ [55:40]. NOTE: 𝒅/𝒅𝒙 [ ∫ 𝒇(𝒙) ⋅ 𝒅𝒙] = 𝒇(𝒙) 
     ◉ [57:00]. 🧩 Example – :  ∫ 𝒙² ⋅ 𝒅𝒙 
          ○ I want to integrate 𝒇(𝒙) = 𝒙² with respect to 𝒙.
               ■   ∫ 𝒙² ⋅ 𝒅𝒙 = (1/3)𝒙³ + 𝓒
          
● [58:19]. Basic integration table.  
     ◉ From 𝒅/𝒅𝒙 [𝒙ʳ] = r⋅𝒙ʳ⁻¹  to:
          ○ ∫ 𝒙ʳ⋅𝒅𝒙 = 𝒙ʳ⁺¹ / (r+1) + 𝒞   (r ≠ −1)  (▽)
     ◉ [1:01:00]. The integration table shows derivatives and their corresponding integrals.
          ○ 𝒅/𝒅𝒙 [𝒙]           = 1                       →    ∫ 1⋅𝒅𝒙                    = 𝒙 + 𝓒
          ○ 𝒅/𝒅𝒙 [𝒙ʳ]          = r⋅𝒙ʳ⁻¹                 →    ∫ 𝒙ʳ⋅𝒅𝒙 = 𝒙ʳ⁺¹ / (r+1) + 𝓒 (▽)
          ○ 𝒅/𝒅𝒙 [sin(𝒙)]    = cos(𝒙)               →   ∫ cos(𝒙)⋅𝒅𝒙             = sin(𝒙)  + 𝓒
          ○ 𝒅/𝒅𝒙 [-cos(𝒙)]  = sin(𝒙)                →   ∫ sin(𝒙)⋅𝒅𝒙              = -cos(𝒙) + 𝓒
          ○ 𝒅/𝒅𝒙 [tan(𝒙)]    = sec²(𝒙)              →   ∫ sec²(𝒙)⋅𝒅𝒙            = tan(𝒙)  + 𝓒
          ○ 𝒅/𝒅𝒙 [-cot(𝒙)]   = csc²(𝒙)              →   ∫ csc²(𝒙)⋅𝒅𝒙            = -cot(𝒙) + 𝓒
          ○ 𝒅/𝒅𝒙 [sec(𝒙)]    = sec(𝒙)tan(𝒙)     →   ∫ sec(𝒙)tan(𝒙)⋅𝒅𝒙   = sec(𝒙)  + 𝓒
          ○ 𝒅/𝒅𝒙 [-csc(𝒙)]   = csc(𝒙)cot(𝒙)     →   ∫ csc(𝒙)cot(𝒙)⋅𝒅𝒙    = -csc(𝒙) + 𝓒
     ◉ [37:30]. The importance of proper sign manipulation in trigonometric integrals.

● [1:17:48]. 🧩 Examples of indefinite integrals  –:
     ◉ ∫ 𝒙⁴⋅𝒅𝒙     = (1/5)𝒙⁵ + 𝓒
     ◉ ∫ 1/𝒙³⋅𝒅𝒙  =  ∫ 𝒙⁻³⋅𝒅𝒙 = 𝒙⁻² / -2  + 𝓒 = -(1/2𝒙²) + 𝓒
     ◉ ∫ √𝒙⋅𝒅𝒙    = ∫ 𝒙¹ᐟ²⋅𝒅𝒙 = 𝒙³ᐟ² / (3/2) = (2/3)⋅𝒙³ᐟ² + 𝓒
     ◉ ∫ (1/𝒙)⋅𝒅𝒙 = ∫ 𝒙⁻¹⋅𝒅𝒙 
          ○ Attempt using the general power rule:
               ∫ 𝒙⁻¹ ⋅ 𝒅𝒙 = (𝒙⁽ⁿ⁺¹⁾) / (n+1) = (𝒙⁰) / 0 = 1/0 (undefined)
               This calculation shows that we cannot use the power rule ((𝒙⁽ⁿ⁺¹⁾) / (n+1) 
               when the exponent is n = -1, because the denominator becomes zero (▽).
               Therefore, the integral of 1/𝒙 is an exception and is defined as:
                ∫ (1/𝒙)⋅𝒅𝒙 = ln|𝒙| + 𝓒

● [1:25:15]. Properties of indefinite integrals.  
     ◉ Similarity to derivative properties.
     ◉ Properties:
           1. ∫ 𝑘 ⋅ 𝒇(𝒙)⋅𝒅𝒙 = 𝑘⋅ ∫ 𝒇(𝒙)⋅𝒅𝒙 (k is a constant)
           2. ∫ [𝒇(𝒙) + 𝓰(𝒙)]⋅𝒅𝒙 = ∫ 𝒇(𝒙)⋅𝒅𝒙 + ∫ 𝓰(𝒙)⋅𝒅𝒙
           3. ∫ [𝒇(𝒙) - 𝓰(𝒙)]⋅𝒅𝒙 =  ∫ 𝒇(𝒙)⋅𝒅𝒙 - ∫ 𝓰(𝒙)⋅𝒅𝒙
     ◉ [1:27:34]. One cannot separate the integral of a product of functions.
          ○ ∫𝒇(𝒙) ⋅ 𝓰(𝒙)⋅𝒅𝒙 ≠ ∫𝒇(𝒙) 𝒅𝒙 ⋅ ∫ 𝓰(𝒙)⋅𝒅𝒙 
               ■ [1:32:31]. Example: ∫𝒙²⋅(𝒙+3)⋅𝒅𝒙 use distribution but ...
                    ▣ … you could not do it here ∫𝒙²⋅(𝒙+3)³
     ◉ [1:27:25]. The importance of using a single constant "𝓒" at the end of an indefinite integral calculation.
          ○🧩 Example –: ∫ 2𝒙⋅𝒅𝒙 = 2  ∫ 𝒙⋅𝒅𝒙 = 2𝒙²/2 + 𝓒
          ○🧩 Example –: ∫ (1 + 𝒙)⋅𝒅𝒙 =
               = ∫ 1⋅𝒅𝒙 + ∫ 𝒙⋅𝒅𝒙                          # linearity of the integral
               = (𝒙 + 𝓒₁) + (𝒙²/2 + 𝓒₂)                 # ∫1⋅𝒅𝒙 = 𝒙 + 𝓒₁,  ∫x dx = x²/2 + 𝓒₂
               = 𝒙 + 𝒙²/2 + (𝓒₁ + 𝓒₂)                   # collect terms
               = 𝒙 + 𝒙²/2 + 𝓒                              # merge constants into a single C

● [1:33:20]. 🧩 Examples of indefinite integrals    –:
     ◉ ∫ 4cos(𝒙)⋅𝒅𝒙 = 4 ∫cos(𝒙)⋅𝒅𝒙 = 4sin(𝒙) + 𝓒
     ◉ Use of parenthesis.
          ○ ∫(𝒙 + 𝒙²)⋅𝒅𝒙 = 𝒙² / 2 + 𝒙³ / 3 +𝓒    is the same as ∫𝒙 + 𝒙²⋅𝒅𝒙
     ◉ ∫ (2𝒙⁵ - 3𝒙² + 4𝒙 - 8)⋅𝒅𝒙 = (1/3)𝒙⁶ - 𝒙³ + 2𝒙² - 8𝒙 + 𝓒
     ◉ ∫ (𝒙² - 2)(𝒙² - 3)⋅𝒅𝒙 
        Expanding the product:
            = ∫ (𝒙⁴ - 5𝒙² + 6)⋅𝒅𝒙 
        Applying the integration rule:
            = 𝒙⁵ / 5  -  5𝒙³ / 3  +  6𝒙  +  𝓒  
     ◉ ∫ (cos(𝒙) / sin²(𝒙))⋅𝒅𝒙 → ∫ (1 / sin(𝒙)) ⋅ (cos(𝒙) / sin(𝒙))⋅𝒅𝒙  → ∫ csc(𝒙) ⋅ cot(𝒙)⋅𝒅𝒙 = -csc(𝒙) + 𝓒
     ◉ [1:46:24].  ∫ (T² − 2T⁴) / T⁴ dT =
                                                         = ∫ (T² / T⁴) − (2T⁴ / T⁴) dT
                                                         = ∫ (T⁻² − 2) dT
                                                         = ∫ T⁻² dT − ∫ 2 dT
                                                         = (−1/T) − 2T + C

● [1:52:20]. Applications of indefinite integrals. 
     ◉  Finding the equation of a curve given its slope at every point.
     ◉ 🧩 Example –: Find the equation of a curve whose slope at each point is 𝒙² . . .
          ○ The slope 𝒅𝑦/𝒅𝒙 = 𝒙²
          ○ The family equation of the curve 𝒅𝑦/𝒅𝒙 = 𝒙²  →  ∫ 𝒅𝑦 = ∫ 𝒙²⋅𝒅𝒙  →  𝑦 = ∫ 𝒙²⋅𝒅𝒙 = (1/3)𝒙³ + 𝓒
               ■ We have to find out 𝓒 to find the exact equation
          ○ . . .  passing through (2, 1).
               ■ Substituting the point (2, 1) into the equation yields 𝓒 = -5/3.
          ○ The equation of the curve is 𝑦 = (1/3)𝒙³ - 5/3.
               ■ Therefore, it is the only curve within the family  𝑦 = (1/3)𝒙³ + 𝓒
                   that passes through (2, 1), fixing the value of the constant 𝓒 = -5/3.




Ｂｒｉｅｆ　ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｄｉｆｆｅｒｅｎｔｉａｌ　ｅｑｕａｔｉｏｎｓ

● [2:00:00]. Family of solutions
     ◉ 𝒅𝑦/𝒅𝒙 = 𝒇(𝒙); IDEA: Can you find 𝓕(𝒙) such that 𝑦 = 𝓕(𝒙) satisfies 𝒅𝑦/𝒅𝒙 = 𝒇(𝒙)?
          ○ Example: 𝒅𝑦/𝒅𝒙  =  𝒙⁴
               ■ ∫ (𝒅𝑦/𝒅𝒙)⋅𝒅𝒙  =  ∫ 𝒙⁴⋅𝒅𝒙  →  ∫ 1⋅𝒅𝑦 = ∫ 𝒙⁴⋅𝒅𝒙 → 𝑦 = 𝒙⁵/5 + 𝓒
                    ▣ Find the equation of a curve whose slope at each point is 𝒙⁴


● [2:06:14]. One solution. Initial value problem   
     ◉ If, in addition to the differential equation 𝒅𝑦/𝒅𝒙 = 𝒇(𝒙), an initial condition is specified, 
         for example 𝑦(𝒙₀) = 𝑦₀, then that condition allows us to determine the value of the constant of integration and obtain 
         a unique particular solution of the form: 𝑦(𝒙) = ∫ 𝒇(𝒙)⋅𝒅𝒙 + 𝓒,  where 𝓒 is determined using the condition 𝑦(𝒙₀) = 𝑦₀.
         In this way, from the family of solutions (which includes all possible values of 𝓒), exactly one solution is selected that 
         satisfies the given condition.
          ○ [2:14:00]. 🧩 Example –: 𝒅𝑦/𝒅𝒙 = 1/(2𝒙)³ , 𝑦(1) = 0 
               ■ ∫ (2𝒙)⁻³⋅𝒅𝒙 → ∫ 2⁻³ ⋅ 𝒙⁻³⋅𝒅𝒙 = ∫(1/8)𝒙⁻³⋅𝒅𝒙 = (1/8) ∫𝒙⁻³⋅𝒅𝒙 = (1/8) ⋅ ( (𝒙⁻² ) / -2) = -1 / (16𝒙²) + 𝓒
                    ▣ This is a family of curves such that  if I take its derivative I obtain   1/(2𝒙)³
                         ▢ **How I find a specific curve?** We have to use the initial value
                              ▲ 𝑦(1) = 0   →   𝑦 = -1 / (16𝒙²) + 𝓒   →   0 =  -1 / ( 16(1)² ) = -1 / 16  + 𝓒   →   𝓒 = 1 / 16 
                    ▣ 𝑦 = -1 / (16𝒙²) + 1 / 16 this is the exactly on curve that satisfied the initial value. 
          ○ [2:14:20]. 🧩 Example –: Find the equation of a curve whose slope at each point is cos(𝒙), with the initial condition 𝑦(0) = 1.
               ■ 𝒅𝑦/𝒅𝒙 = cos(𝒙)
               ■ ∫ (𝒅𝑦/𝒅𝒙)⋅𝒅𝒙 = ∫ cos(𝒙)⋅𝒅𝒙   →   𝑦 = sin(𝒙) + 𝓒 
               ■ Substituting the initial condition 𝑦(0) = 1  →  1  =  sin(0)  + 𝓒  yields 𝓒 = 1.
               ■ The equation of the curve is 𝑦 = sin(𝒙) + 1.


● [2:17:25]. Real-life application 🧩 Example –: Catapult     
     ◉ Problem description: a catapult launches a projectile vertically with an initial
          velocity of 128 ft/s  (39.01 m/s) from a platform 16 ft (4.88 m) high. Find:
           1. The position function of height 𝒮(𝓉).
           2. Maximum height.
           3. When will it hit ground. 
     ◉ [2:20:00]. Definition of the position, velocity, and acceleration functions:
          ○ 𝒮(𝓉): the projectile's position as a function of time.
          ○ 𝒮'(𝓉): the projectile's velocity as a function of time.
          ○ 𝒮''(𝓉): the projectile's acceleration as a function of time.
     ◉ Initial conditions:
          ○ 𝒮(0) = 16 ft (initial height)(⇡)
          ○ 𝒮'(0) = 128 ft/s (initial velocity)
          ○ 𝒮''(𝓉) = -32 ft (ca. -10 meters)/s² (acceleration due to gravity)
     ◉ [2:27:00]. Obtaining the velocity function by integrating the acceleration function:
          ○ 𝒮'(𝓉) = ∫ 𝒮''(𝓉) dt = ∫ -32 dt = -32𝓉 + 𝓒 = 𝒮'(𝓉)
          ○ Using the initial condition 𝒮'(0) = 128 → 128 = -32𝓉 + 𝓒:
               ■ 128 = -32(0) + 𝓒  we get 𝓒 = 128.
          ○ 𝒮'(𝓉) = -32𝓉 + 128
     ◉ [2:32:35]. Obtaining the position function by integrating the velocity function:
          ○ 𝒮(𝓉) = ∫ 𝒮'(𝓉) dt = ∫ (-32𝓉 + 128) dt = -16𝓉² + 128𝓉 + 𝓒 = 𝒮(𝓉)
          ○ Using the initial condition 𝒮(0) = 16 → 16 = -16𝓉² + 128𝓉 + 𝓒 
               ■ 16 = -16(0)² + 128(0) + 𝓒 we get 𝓒 = 16 (⇡).
          ○ 𝒮(𝓉) = -16𝓉² + 128𝓉 + 16
     ◉ [2:39:45]. Calculating the maximum height:
          ○ The maximum height is reached when the velocity is zero, i.e. 𝒮'(𝓉) = 0.
          ○ Solving -32𝓉 + 128 = 0 yields 𝓉 = 4 seconds.
          ○ Substituting 𝓉 = 4 into the position function 𝒮(𝓉) = -16𝓉² + 128𝓉 + 16, gives the maximum height: 𝒮(4) = 784 ft.
     ◉ [2:42:30]. Calculating When will it hit ground.
          ○ The position function is giiven by 𝒮(𝓉) = -16𝓉² + 128𝓉 + 16
          ○ When it hit ground, the position is 0 → 0 = -16𝓉² + 128𝓉 + 16
          ○ 𝓉 = 4 + √17 ≈ 8.123