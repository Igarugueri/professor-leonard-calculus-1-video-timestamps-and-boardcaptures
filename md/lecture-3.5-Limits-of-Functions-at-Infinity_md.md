-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．５　ｌｉｍｉｔｓ　ｏｆ　ｆｕｎｃｔｉｏｎｓ　ａｔ　ｉｎｆｉｎｉｔｙ**---------------------------------




Ｒｅｖｉｅｗ　ｏｆ　ｖｅｒｔｉｃａｌ　ａｓｙｍｐｔｏｔｅｓ　ａｎｄ　ｒｅｍｏｖａｂｌｅ　ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ　

● [0:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=0). Reminder of the definition of vertical asymptote (VA): lim ₓ→ₐ 𝒇(𝒙) = ±∞ [📷image](../img/Calculus 1 Lecture 3.5/[0-00]-01.png) 
     ◉ Two cases for a vertical asymptote:
          ○ lim ₓ→ₐ⁻ 𝒇(𝒙) = lim ₓ→ₐ⁺ 𝒇(𝒙) = ±∞               # The limit **exists** (both one-sided limits agree)
          ○ lim ₓ→ₐ⁻ 𝒇(𝒙) = ∞  and  lim ₓ→ₐ⁺ 𝒇(𝒙) = −∞   # The limit **does not exist** (one-sided limits disagree)
     ◉ to find discontinuities **denominator equals zero**.
          ○ If a factor **cannot be canceled**, the discontinuity is a **vertical asymptote**.
          ○ If a factor **can be canceled**, it is a **removable discontinuity**, not a vertical asymptote.
     
● [3:55](https://www.youtube.com/watch?v=-PYebK8DKPc&t=235). Difference between removable discontinuities (holes) and VA. [📷image](../img/Calculus 1 Lecture 3.5/[3-55]-01.png) 
     ◉ ʜ̳ᴏ̳ʟ̳ᴇ̳ꜱ̳: removable discontinuities where only one point is missing in the function. 
          ○ Occur when the **numerator and denominator are zero at the same time**, allowing cancellation of factors.
          ○ One single point is missing from the function.
     ◉ ᴠ̳ᴀ̳: non-removable discontinuities.
          ○ Occur when **discontinuities cannot be canceled**. 
          
● [6:40](https://www.youtube.com/watch?v=-PYebK8DKPc&t=400). 🧩 Example –: 𝒇(𝒙) = 𝒙 / ((𝒙 + 3)(𝒙 − 1)) [📷image](../img/Calculus 1 Lecture 3.5/[6-40]-01.png) 
     ◉ Vertical asymptotes at 𝒙 = 1 and 𝒙 = −3 → non-cancelable factors in the denominator.
     ◉ Critical sign-change values are found by:
          ○ Setting the **denominator equal to zero** → to identify discontinuities (**vertical asymptotes**).
          ○ Setting the **numerator equal to zero** → to identify values where the function **crosses the 𝒙-axis**.
               ■ These are not discontinuities, but they must be **included in the sign analysis** since they may cause a sign change in the rational expression.
                    ▣ In this case, 𝒙 = 0 makes the numerator zero → the function is zero at this point and may change sign around it.
     ◉ General rule for analyzing a rational function 𝒇(𝒙) = 𝒫(𝒙)/𝒬(𝒙):
          ○ Fully factor both 𝒫(𝒙) and 𝒬(𝒙), and simplify the expression if possible.
          ○ Identify points of discontinuity from 𝒬(𝒙) = 0:
               ■ If a factor in the denominator **does not cancel** with the numerator, its zero corresponds to a **vertical asymptote (VA)**.
                    ▣ These values are **not in the domain** and divide the number line into intervals.
                    ▣ They are essential in the **sign chart**, as they may trigger sign changes in 𝒇(𝒙).
               ■ If a factor in the denominator **does cancel** with one in the numerator, the corresponding 𝒙-value results in a **hole** (removable discontinuity).
                    ▣ The function is undefined at this point, but the behavior around it may be continuous.
                    ▣ Holes **do not cause sign changes** like VAs do, but must still be **noted** in the analysis.
          ○ Set 𝒫(𝒙) = 0 → determine **x-intercepts** (zeros of the numerator).
               ■ Include them in the sign analysis **only if they are in the domain**, as they may indicate a sign change in the rational expression.
     ◉ [8:14](https://www.youtube.com/watch?v=-PYebK8DKPc&t=494). Using sign analysis to determine behavior around VAs:
          ○ Sign chart:
                                                     ¦ ◟                              ¦ ◟  
                                        -----------∣--------------∣-------------∣------------
                      𝒇(𝒙)               -    ◝ ¦         +              -    ◝ ¦   +
                                                   -3                0               1
          ○ Limits at critical values:
               ■ Near 𝒙 = −3 (vertical asymptote):
                    ▣ lim ₓ→₋₃⁻ 𝒇(𝒙) = −∞   # denominator → 0⁺, numerator < 0 ⇒ −∞  
                    ▣ lim ₓ→₋₃⁺ 𝒇(𝒙) = +∞   # denominator → 0⁻, numerator < 0 ⇒ +∞  
                    ▣ Limit does not exist.
               ■ At 𝒙 = 0 (zero of the numerator):
                    ▣ lim ₓ→₀ 𝒇(𝒙) = 0   # numerator → 0, denominator ≠ 0 ⇒ crosses the x-axis.
               ■ Near 𝒙 = 1 (vertical asymptote):
                    ▣ lim ₓ→₁⁻ 𝒇(𝒙) = −∞   # denominator → 0⁻, numerator > 0 ⇒ −∞  
                    ▣ lim ₓ→₁⁺ 𝒇(𝒙) = +∞   # denominator → 0⁺, numerator > 0 ⇒ +∞  
                    ▣ Limit does not exist.
                    
● [11:55](https://www.youtube.com/watch?v=-PYebK8DKPc&t=715). 🧩 Example –: lim ₜ→₁  𝒕³ / (𝒕² - 1)² [📷image](../img/Calculus 1 Lecture 3.5/[11-55]-01.png) 
     ◉ Discontinuities:
          ○ Discontinuities occur where the denominator equals zero.
          ○ For this problem, they happen at 𝒕 = ±1 because (𝒕² - 1)² = 0.
          ○ These are **vertical asymptotes as they cannot be removed by factoring (non-removable discontinuities)**.
     ◉ Focus on the limit:
          ○ Even though there are two discontinuities (𝒕 = ±1), only 𝒕 = 1 matters since the limit is evaluated near this value.
               ■ 𝒕 = -1 can be ignored for this problem.
     ◉ Importance of the numerator:
          ○ It is crucial for calculating the limit at vertical asymptotes (VA), as these points determine where the function
             may change its sign in the adjacent intervals.
          ○ Check where the numerator (𝒕³ = 0) equals zero, which happens at 𝒕 = 0.
          ○ 𝒕 = 0 is not an asymptote, but it is useful to divide intervals and check for sign changes.
     ◉ Strategy:
          ○ Divide the interval into regions around 𝒕 = 0 and 𝒕 = 1.
          ○ Evaluate specific points in each region (e.g., 𝒕 = 0.5, 𝒕 = 2) to understand the function's behavior.
          ○ Sign chart:
                                                     ¦                              ◞ ¦ ◟  
                                        -----------∣--------------∣-------------∣------------
                      𝒇(𝒙)                         ¦                            +   ¦   +
                                                    -1               0               1
               ■ Near 𝒙 = 1 (vertical asymptote):
                    ▣ lim ₓ→₁⁻ 𝒇(𝒙) = +∞   # denominator → 0⁻, numerator > 0 ⇒ +∞  
                    ▣ lim ₓ→₁⁺ 𝒇(𝒙) = +∞   # denominator → 0⁺, numerator > 0 ⇒ +∞  
                    ▣ Limit exist: ▣ lim ₓ→₁ 𝒇(𝒙) = +∞   



Ｌｉｍｉｔｓ　ａｔ　ｉｎｆｉｎｉｔｙ

● [16:30](https://www.youtube.com/watch?v=-PYebK8DKPc&t=990). Question: What happens to a function as **𝒙 approaches positive or negative infinity?** [📷image](../img/Calculus 1 Lecture 3.5/[16-30]-01.png) 
     ◉ Exploring the behavior of 1/𝒙 as 𝒙 increases:
          ○ As 𝒙 increases, 1/𝒙 approaches zero. 
               ■ lim ₓ→∞ 1/𝒙 = 0 
               ■ lim ₓ→ -∞ 1/𝒙 = 0 
   
● [20:25](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1225). Definition of limit at infinity : 
     ◉ If 𝒇(𝒙) approaches a number as 𝒙 approaches infinity, the limit exists.
          
● [21:07](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1267). Relation between limits at infinity and **horizontal asymptotes (HA)**:
     ◉ HA represent the value a function approaches as 𝒙 goes to positive or negative infinity. 
          
● [23:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1380). The rules for calculating limits as 𝒙 approaches positive infinity (𝒙 → +∞) or negative infinity [📷image](../img/Calculus 1 Lecture 3.5/[23-00]-01.png) 
                 (𝒙 → -∞) are the same as before. Therefore, the same rules and techniques apply in both cases.  
     ◉ lim ₓ→∞ 1/𝒙ⁿ = 0 for any n > 0 :
          ○ Any **constant divided by a variable raised to a power approaching infinity will approach zero**. 
               
● [26:10](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1570). Behavior of polynomials at infinity [📷image](../img/Calculus 1 Lecture 3.5/[26-10]-01.png) 
     ◉ Polynomials do not approach a specific number at infinity but tend to positive or negative infinity. 
     ◉ The behavior of a polynomial at infinity is determined by the **highest power term**. 
          ○ This is because, as 𝒙 approaches infinity, the lower exponent terms become insignificant compared to the dominant term.
     ◉ 🧩 Example –:lim ₓ→-∞ -3𝒙³ - 2𝒙² - 𝒙 + 9 = lim ₓ→-∞ -3𝒙³ = ∞



Ｃａｌｃｕｌａｔｉｎｇ　ｌｉｍｉｔｓ　ａｔ　ｉｎｆｉｎｉｔｙ

● [36:27](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2187). Introduction.

● [38:15](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2295). 🧩 Example –: llim ₓ→∞ (5𝒙 - 2) / (3𝒙 + 9) [📷image](../img/Calculus 1 Lecture 3.5/[38-15]-01.png) 
     ◉  Key idea: **divide each term by the highest power of 𝒙 in the denominator**. 
     ◉ Terms with 𝒙 in the denominator approach zero as 𝒙 approaches infinity. 
     ◉ llim ₓ→∞ (5 - 2/𝒙) / (3 + 9/𝒙) = 5/3 
     ◉ Observation: the limit at infinity of a rational function where the powers of 𝒙 in the 
         numerator and denominator are equal is the ratio of the leading coefficients. 
                 
● [44:28](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2668). 🧩 Example –: lim ₓ→∞  (5𝒙² - 4𝒙) / (15𝒙³ - 3𝒙) [📷image](../img/Calculus 1 Lecture 3.5/[44-28]-01.png) 
     ◉ Divide each term by 𝒙³, the highest power in the denominator. 
     ◉ Divide all terms by the highest power of x in the denominator (x³):
         lim ₓ→−∞ [(5x² / x³) − (4x / x³)] / [(15x³ / x³) − (3 / x³)] =
         = lim ₓ→−∞ (5/x − 4/x²) / (15 − 3/x³)
     ◉ Analyze behavior as x → −∞:
          5/x → 0
          4/x² → 0
          3/x³ → 0
     ◉ Substitute limits:
         (0 − 0) / (15 − 0) = 0 / 15 = 0
         limₓ→−∞ (5x² − 4x) / (15x³ − 3) = 0

● [48:05](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2885). 🧩 Example –: lim ₓ→∞ (7𝒙³ - 2𝒙² + 1) / (9 - 2𝒙) [📷image](../img/Calculus 1 Lecture 3.5/[48-05]-01.png) 
     ◉ Divide all terms by the highest power of x in the denominator (x):
        limₓ→−∞ [(7x³ / x) − (2x² / x) + (1 / x)] / [(9 / x) − 2]
        = limₓ→−∞ [7x² − 2x + 1/x] / [9/x − 2]
     ◉ Analyze behavior as x → −∞:
       7x² → +∞
       −2x → +∞
       1/x → 0
       9/x → 0
       Denominator → −2
     ◉ Substitute limits:
      (+∞ + ∞ + 0) / (−2) = +∞ / (−2) = −∞
      limₓ→−∞ (7x³ − 2x² + 1) / (9 − 2x) = −∞

● [52:15](https://www.youtube.com/watch?v=-PYebK8DKPc&t=3135). 🧩 Example –: llim ₓ→∞ ³√( (2𝒙² - 3) / (𝒙² - 5) ) [📷image](../img/Calculus 1 Lecture 3.5/[52-15]-01.png) 
     ◉ Divide all terms by the highest power of x² (inside the cubic root):
        limₓ→∞ ³√( (2x² − 3) / (3x² − 5) ) =
        = ³√( limₓ→∞ (2x²/x² − 3/x²) / (3x²/x² − 5/x²) )
        = ³√( limₓ→∞ (2 − 3/x²) / (3 − 5/x²) )
     ◉ Analyze behavior as x → ∞:
       3/x² → 0
       5/x² → 0
     ◉ Substitute limits:
       ³√( (2 − 0) / (3 − 0) ) = ³√(2/3)
     
● [53:50](https://www.youtube.com/watch?v=-PYebK8DKPc&t=3230). 🧩 Example –: lim ₓ→-∞ (√(𝒙² + 2) ) / (3𝒙 - 6) [📷image-1](../img/Calculus 1 Lecture 3.5/[53-50]-01.png) [📷image-2](../img/Calculus 1 Lecture 3.5/[53-50]-02.png)  [📷image-3](../img/Calculus 1 Lecture 3.5/[53-50]-03.png) 
     ◉ Divide each term by 𝒙, the highest power in the denominator.
          ➀  [56:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=3360). _Applied Property_: Multiplication of Terms with Fractional Powers: a⋅b = (a²⋅b²)¹ᐟ²
               ■ 🧩 Example –: (1 / 𝒙 ) ⋅ (𝒙² + 2)¹ᐟ² = ( (1 / 𝒙)²  ⋅  (𝒙² + 2) )¹ᐟ² =
                                                                         = ( 1 / 𝒙²  ⋅  (𝒙² + 2) )¹ᐟ² =
                                                                         = ( (𝒙² + 2)  /  𝒙² )¹ᐟ²
          ➁  Pay attention to the use of absolute value when simplifying square roots: √(𝒙²) = |𝒙| 
               (i) Why is x ≠ √(x²) in general?
                     – If x ≥ 0:
                          • x² is positive, and the principal square root is simply x.
                          • So, in this case: x = √(x²)
                     – If x < 0:
                          • For example, let x = -3. Then x² = 9, and √9 = 3 (because the square root function returns the positive root).
                          • But -3 ≠ 3, so the equality does NOT hold.
                          • That’s why in general: x ≠ √(x²)
               (ii) Why is |x| = √(x²) always true?
                    – The absolute value removes any negative sign.
                    – The square root function also always returns a non-negative number.
                    – So both |x| and √(x²) give the same non-negative result, regardless of whether x is positive or negative.
     ◉ Step 1. Factor out the highest power inside the square root (x²):
                      x² + 2 = x² · (1 + 2/x²) =
                     = √(x² + 2) = √(x²) · √(1 + 2/x²) =
                     = |x| · √(1 + 2/x²)    (because √(x²) = |x|)
     ◉ Step 2. Substitute into the fraction:
                     √(x² + 2) / (3x − 6) =
                     = [|x| · √(1 + 2/x²)] / (3x − 6)
     ◉ Step 3. Divide numerator and denominator by x (highest power in the denominator):
                      Numerator:   [|x| · √(1 + 2/x²)] / x = (|x|/x) · √(1 + 2/x²)
                      Denominator: (3x − 6)/x = 3 − 6/x
                      Therefore: √(x² + 2) / (3x − 6)  = [ (|x|/x) · √(1 + 2/x²) ] / [ 3 − 6/x ]
     ◉ Step 4. Take the limit as x → −∞:
          ○ |x|/x → −1         (since x is negative)
               ■  First, apply the absolute value definition:
                                       |x| = −x   (since x < 0 as x → −∞)
                               Then:
                                       |x|/x = (−x)/x = −1
                               So:
                                       limₓ→−∞ (|x|/x) = −1
          ○ √(1 + 2/x²) → 1    (because 2/x² → 0)
          ○ 3 − 6/x → 3          (since 6/x → 0)
     ◉ Conclusion:  lim ₓ→-∞ (√(𝒙² + 2) ) / (3𝒙 - 6) = (−1 · 1) / 3 = −1/3
          
● [1:06:53](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4013). 🧩 Example –: lim ₓ→∞ (√(𝒙⁴ + 2) - 𝒙²) [📷image](../img/Calculus 1 Lecture 3.5/[1-06-53]-01.png) 
     ◉ Rationalize the expression by multiplying by the conjugate. 
     ◉ Divide each term by 𝒙², the highest power in the denominator. 
     ◉ Step 1: Multiply by the conjugate to rationalize the expression
                     = limₓ→+∞ [ (√(x⁴ + 2) − x²) · (√(x⁴ + 2) + x²) ] / [√(x⁴ + 2) + x²]
     ◉ Step 2: Use the identity (a − b)(a + b) = a² − b²
                     = limₓ→+∞ [ (x⁴ + 2 − x⁴) / (√(x⁴ + 2) + x²) ]
                     = limₓ→+∞ [ 2 / (√(x⁴ + 2) + x²) ]
     ◉ Step 3: Divide numerator and denominator by x²
                     = limₓ→+∞ [ (2 / x²) / ( (√(x⁴ + 2) / x²) + (x² / x²) ) ]
                     = limₓ→+∞ [ (2 / x²) / ( √(1 + 2/x⁴) + 1 ) ]
     ◉ Step 4: Take the limit
          ○ As x → ∞:
               ■ 2 / x² → 0
               ■ √(1 + 2/x⁴) → 1
     ◉ Final result: lim ₓ→∞ (√(𝒙⁴ + 2) - 𝒙²) = 0 / (1 + 1) = 0 / 2 = 0
     
● [1:16:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4560). 🧩 Example –: lim ₓ→∞ (√(𝒙⁴ + 2𝒙) - 𝒙²) [📷image](../img/Calculus 1 Lecture 3.5/[1-16-00]-01.png) 
     ◉ Rationalize the expression by multiplying by the conjugate. 
     ◉ Divide each term by 𝒙², the highest power in the denominator. 
     ◉ Step 1: Multiply by the conjugate to rationalize the expression
                     = limₓ→+∞ [ (√(x⁴ + 2x² + x²) − x²) · (√(x⁴ + 2x² + x²) + x²) ] / [ √(x⁴ + 2x² + x²) + x² ]
     ◉ Step 2: Use the identity (a − b)(a + b) = a² − b²
                     = limₓ→+∞ [ (x⁴ + 2x² + x² − x⁴) / (√(x⁴ + 2x² + x²) + x²) ]
                     = limₓ→+∞ [ 2x² / (√(x⁴ + 2x² + x²) + x²) ]
     ◉ Step 3: Divide numerator and denominator by x²
                     = limₓ→+∞ [ 2 / (√(x⁴ + 2x² + x²) / x² + x² / x²) ]
                     = limₓ→+∞ [ 2 / (√(x⁴/x⁴ + 2x²/x⁴ + x²/x⁴) + 1) ]
                     = limₓ→+∞ [ 2 / (√(1 + 2/x² + 1/x²) + 1) ]
                     = limₓ→+∞ [ 2 / (√(1 + 2/x² + 1/x²) + 1) ]
     ◉ Step 4: Take the limit
          ○ As x → ∞:
               ■ 2/x² → 0
               ■ 1/x² → 0
               ■ √(1 + 0 + 0) → √1 = 1
     ◉ Final result: limₓ→+∞ (√(x⁴ + 2x² + x²) − x²) = 2 / (1 + 1) = 2 / 2 = 1   
     
● [1:20:51](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4851). 🧩 Example –: lim ₓ→∞ √(7 - 𝒙)  [📷image](../img/Calculus 1 Lecture 3.5/[1-20-51]-01.png) 
     ◉ Does not exist: D.N.E
     ◉ The expression inside the square root becomes negative as 𝒙 approaches positive infinity.

╭───────────────────────────────────────────────────────── ──╮
│             ✦ MAGIC SUMMARY: INDETERMINATE FORMS ✦                                                         │
│               When x → ∞ or x → −∞ in limits                                                                                        │
├────────────┬───────────────────────────────────────────────┤
│  Form                     │                Interpretation                                                                                   │
├────────────┼───────────────────────────────────────────────┤
│ ∞ / ∞                      │ A race of growth: who wins?                                                                           │
│                               │ → Divide all terms by the highest power of x                                                 │
├────────────┼───────────────────────────────────────────────┤
│ 0 / 0                       │ A hidden simplification awaits!                                                                        │
│                               │ → Factor, cancel, ( or apply L’Hôpital’s Rule [CALCULUS 2] )                     │
├────────────┼───────────────────────────────────────────────┤
│ ∞ − ∞                     │ Big values clashing… unclear result!                                                             │
│                               │ → Combine into a single fraction                                                                   │
├────────────┼───────────────────────────────────────────────┤
│ 0 × ∞                      │ Shrinking and growing — who dominates?                                                   │
│                               │ → Rewrite as a fraction to resolve it                                                              │
├────────────┼───────────────────────────────────────────────┤
│ 1^∞                        │ Exponential surprise!                                                                                      │
│ 0^0                         │ Ambiguous start of power                                                                               │
│ ∞^0                        │ Explosive base with vanishing power                                                             │
│                                │ → Use logarithms or rewrite using e^ln                                                         │
╰────────────┴──────────────────────────────────────────────╯
