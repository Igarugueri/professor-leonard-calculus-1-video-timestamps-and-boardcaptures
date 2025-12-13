-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ４．３  Ａｒｅａ  Ｕｎｄｅｒ  ａ  Ｃｕｒｖｅ， Ｌｉｍｉｔ  Ａｐｐｒｏａｃｈ， Ｒｉｅｍａｎｎ  Ｓｕｍｓ**---------------------------------




S ｉｇ ｍ ａ　ｎｏｔａｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=0). Introduction to Sigma ( ∑ ) notation.
     ◉ Definition of Sigma as a Greek letter meaning "sum".
    
● [2:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=140). Detailed explanation of Sigma notation.  
     ◉🧩 Example –:  ∑ (from k=0 to 5) k³  
     ◉ Sigma notation indicates the addition of terms.  
     ◉ Use of indices (k) and how they vary in the summation is defined.  
     ◉ ∑ (from k=0 to 5) k³ = 0³ + 1³ + 2³ + 3³ + 4³ + 5³   

● [3:15](https://www.youtube.com/watch?v=F0uuW-I6icY&t=195). Summation properties. [📷image-1](../img/Calculus 1 Lecture 4.3/[3-15]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.3/[3-15]-02.png)  
     ◉ [3:30](https://www.youtube.com/watch?v=F0uuW-I6icY&t=210). Property ➀: ᴇxᴛʀᴀᴄᴛɪᴏɴ ᴏꜰ ᴄᴏɴꜱᴛᴀɴᴛꜱ ꜰʀᴏᴍ ᴛʜᴇ ꜱᴜᴍᴍᴀᴛɪᴏɴ.  
          ○ If a constant 𝓬 does not depend on k, the constant factor in the summation can be pulled out.  
               ■ ∑ (from k=1 to n) [𝓬 · 𝒇(k)] = 𝓬 · ∑ (from k=1 to n) [𝒇(k)]  
               ■ Special case: ∑ (from k=1 to n) 𝓬 = 𝓬·n  
          ○ [5:27](https://www.youtube.com/watch?v=F0uuW-I6icY&t=327). 🧩 Example –: ∑ (from j=1 to 5) 𝒙³
               ■ 𝒙³ ⋅ ∑ (from j=1 to 5) 1 = 𝒙³ · (1 + 1 + 1 + 1 + 1) = 5𝒙³  
     ◉ [9:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=540). Property ➁: ᴅɪꜱᴛʀɪʙᴜᴛɪᴠᴇ ᴩʀᴏᴩᴇʀᴛy ᴏꜰ ꜱᴜᴍᴍᴀᴛɪᴏɴ ᴏᴠᴇʀ ᴀᴅᴅɪᴛɪᴏɴ ᴀɴᴅ ꜱᴜʙᴛʀᴀᴄᴛɪᴏɴ.  
          ○ Just like derivatives and integrals, the summation can split sums and differences into separate summations.  
               ■ ∑ (from k=1 to n) [𝒇(k) + 𝓰(k)] = ∑ (from k=1 to n) 𝒇(k) + ∑ (from k=1 to n) 𝓰(k)  
               ■ 🧩 Example –: ∑ (from k=1 to 3) [k + 2k] = ∑ (from k=1 to 3) k + ∑ (from k=1 to 3) 2k  


● [9:35](https://www.youtube.com/watch?v=F0uuW-I6icY&t=575). ꜰᴏʀᴍᴜʟᴀꜱ ꜰᴏʀ ꜱᴜᴍᴍᴀᴛɪᴏɴ ᴍᴀɴɪᴩᴜʟᴀᴛɪᴏɴ [📷image](../img/Calculus 1 Lecture 4.3/[9-35]-01.png)
     ❶ ∑ (from k=1 to n) k = 1 + 2 + 3 + 4 + ... + n  = n(n + 1) / 2
     ❷ ∑ (from k=1 to n) k² = 1² + 2² + 3² + ... + n²  = [n(n + 1)(2n + 1)] / 6
     ❸ ∑ (from k=1 to n) k³ = 1³ + 2³ + 3³ + ... + n³  = [n(n + 1) / 2]² 
     ❹ ∑ (from k=1 to n) 1 = n ; ∑ (from k=1 to n) 𝓬 = 𝓬 + 𝓬 + 𝓬 + ... + 𝓬 (n terms) = 𝓬 ⋅ (1 + 1 + 1 + ... + 1) = 𝓬 ⋅ n

● [17:15](https://www.youtube.com/watch?v=F0uuW-I6icY&t=1035). 🧩 Example – Applying summation formulas: ∑ (from k=1 to 10) [k(k + 1)]  [📷image](../img/Calculus 1 Lecture 4.3/[17-15]-01.png)
     ◉ The need to manipulate sums in order to use the above formulas.
     ◉ The idea of distributing products of terms so the formulas can be applied is presented.
     ◉ It is explained that summations can be separated through addition or subtraction.
     ◉ ∑ (from k=1 to 10) [k(k + 1)]  = ∑ (from k=1 to 10) [k² + k]  =
                = ∑ (from k=1 to 10) k² + ∑ (from k=1 to 10) k  ➁
        Applied formulas:  
                  ∑ (from k=1 to n) k² = [n(n + 1)(2n + 1)] / 6  ❷
                  ∑ (from k=1 to n) k    = [n(n + 1)] / 2             ❶
       Substituting n = 10:  
                   [10(10 + 1)(2 · 10 + 1)] / 6 + [10(10 + 1)] / 2 =
                = [10(11)(21)] / 6 + [10(11)] / 2 = 
                = 385 + 55  = 440



Ｃａｌｃｕｌａｔｉｎｇ　ｔｈｅ　ａｒｅａ　ｕｎｄｅｒ　ａ　ｃｕｒｖｅ　ｕｓｉｎｇ　ｒｅｃｔａｎｇｌｅｓ

● [23:15](https://www.youtube.com/watch?v=F0uuW-I6icY&t=1395). Definition of the rectangular method. [📷image](../img/Calculus 1 Lecture 4.3/[23-15]-01.png)
     ◉ How the area under the curve is split into n equal subdivisions is explained.
     ◉ Partition of the interval [𝓪, 𝓫] into n equal subintervals.
          ○ Equal-width subintervals simplify the algebra and notation.
          ○ Define the cut points (partition): 𝒙₀, 𝒙₁, 𝒙₂, …, 𝒙ₙ with 𝒙₀ = 𝓪 and 𝒙ₙ = 𝓫.
          ○ These cuts determine n adjacent subintervals [𝒙ₖ₋₁, 𝒙ₖ] and hence n rectangles.
               ■ and k ∈ {1, 2, …, n}   (index)
     ◉ [25:02](https://www.youtube.com/watch?v=F0uuW-I6icY&t=1502). The width of each rectangle is defined as Δ𝒙.
          ○ Δ𝒙 is the change in 𝒙 from one point to the next, for example from 𝓪 to 𝒙₁.
          ○ It is shown how to calculate the width of the rectangles by:
               ■ 𝓫 - 𝓪
          ○ The formula for the width of each rectangle is given: 
               ■ Δ𝒙 = (𝓫 - 𝓪) / n
          ○ It is pointed out that all the rectangle bases are the same, **simplifying their sum**.
     ◉ [28:05](https://www.youtube.com/watch?v=F0uuW-I6icY&t=1685). Choice of sample points to determine the heights.
          ○ In each subinterval [𝒙ₖ₋₁, 𝒙ₖ], pick an arbitrary sample point 𝒙ₖ* ∈ [𝒙ₖ₋₁, 𝒙ₖ] 
               ■ Examples: a point in [𝓪, 𝒙₁] or in [𝒙₃, 𝒙₄].
          ○ The **height of the k-th rectangle** is 𝒇(𝒙ₖ*).
               ■ With that height hₖ, you build ONE rectangle that spans the entire subinterval:
                    ▣ base = Δ𝒙 = 𝒙ₖ − 𝒙ₖ₋₁ (constant if the partition is uniform)
                    ▣ height = hₖ = f(xₖ*) (constant across the whole subinterval)
                    ▣ area of the k-th rectangle: Aₖ = f(𝒙ₖ*) · Δ𝒙
     ◉ It is explained that to sum the areas of all rectangles, one can consider each rectangle individually.
          ○ The sum of the n rectangle areas approximates the area under the curve.
     ◉ It is explained that the area under the curve is approximated by summing the rectangles’ areas.
          ○ The approximation improves as n increases (Δ𝒙 → 0).
     ◉ NOTE: Remarks on choices of 𝒙ₖ* (special cases used in practice).
          ○ Left endpoints: 𝒙ₖ* = 𝒙ₖ₋₁  (left Riemann sum).
          ○ Right endpoints: 𝒙ₖ* = 𝒙ₖ    (right Riemann sum).
          ○ Midpoints: 𝒙ₖ* = (𝒙ₖ₋₁ + 𝒙ₖ) / 2 (often more accurate for smooth 𝒇).
          
● [34:24](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2064). Analysis of the area of an individual rectangle. [📷image](../img/Calculus 1 Lecture 4.3/[34-24]-01.png)
     ◉ [36:10](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2170). Rectangle base (width): Δ𝒙 = (𝓫 − 𝓪) / n for uniform partitions.
     ◉ The idea of using an arbitrary point 𝒙ₖ* to get the rectangles’ heights is presented.
     ◉ [39:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2340). To get each rectangle’s height, 𝒇(𝒙ₖ*)  is evaluated at that arbitrary point.
     ◉ [41:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2480). It follows that the area of a rectangle is its base times height: Δ𝒙 ⋅ 𝒇(𝒙ₖ*).
     ◉ [42:36](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2556). The sum of the areas of all individual rectangles. 
          ○ 𝒜 = ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙.
     ◉ NOTE: Summary of definitions (clean reference).
          ○ Partition: 𝑷 = {𝒙₀ = 𝓪 < 𝒙₁ < … < 𝒙ₙ = 𝓫}.
          ○ Widths: Δ𝒙 = (𝓫 − 𝓪)/n 
          ○ Sample points: 𝒙ₖ* ∈ [𝒙ₖ₋₁, 𝒙ₖ].
          ○ Riemann sum: ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙  

● [46:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2810). Improving the approximation using limits.
     ◉ It is explained that to improve the approximation, the number of rectangles must increase.
          ○  𝒜ₙ = ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙 ⇢  𝒜ₙ aproximation based on n
               ■ Index and points:
                    ▣ k ∈ {1, 2, …, n}
                    ▣ x₀ = 𝓪, xₙ = 𝓫, with 𝓪 = x₀ < x₁ < … < xₙ = 𝓫   ⇒   xₖ ∈ [𝓪,𝓫]
                    ▣ xₖ* ∈ [xₖ₋₁, xₖ]
     ◉ If the number of rectangles tends to infinity, the approximation is exact.
     ◉ When the number of rectangles increases, each rectangle’s width shrinks, tending to zero.
     ◉ The concept of the limit is introduced to handle n → ∞.
     ◉ It is stated that to let n → ∞, one uses the limit operation.
     ◉ [48:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=2930). It is established that applying lim_(n → ∞) to the sum of the rectangles’ areas yields the exact area under the curve.
          ○ 𝒜ₙ = limₙ→ ∞ ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙
               ■  **It is stated that the limit of a sum is the foundation of the integral**.
                    ▣ 𝒜ₙ  =  limₙ→∞ ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙   →  ∫[𝓪,𝓫] 𝒇(𝒙ₖ*) · dx
                    ▣ [𝓪,𝓫] are the limits of the interval (Definite Integral because of [𝓪,𝓫]) over which the integral is evaluated.

                       


Ｈｏｗ　ｔｏ　ｕｓｅ　ｔｈｅ　ｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌ　ｔｏ　ｆｉｎｄ　ａｒｅａｓ

● [50:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3050). Arbitrary point’s of each subinterval.[📷image](../img/Calculus 1 Lecture 4.3/[50-50]-01.png)
     ◉ It is explained that the arbitrary point 𝒙ₖ* can be any point in the subinterval.
     ◉ The arbitrary point’s position does not matter, as the rectangle width tends to zero.
     ◉ For convenience, one typically chooses consistently the left endpoint, right endpoint, or midpoint.
     ◉ Choosing arbitrary points: Left, Right, and Midpoint.
          ○ 𝒙ₖ* can represent the left, right, or midpoint of the subinterval.
     ◉ [53:55](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3235). Visualizing the cut points on the 𝒙-axis.
          ○ To calculate the area, one needs a finite interval from 𝓪 to 𝓫
          ○ The cuts on the 𝒙-axis are set as 𝒙₁, 𝒙₂, 𝒙₃, ... 𝒙ₙ.
          ○ The width of each rectangle is Δ𝒙.
          ○ There is an arbitrary point at each cut.
          ○ Visualizing the different options for the arbitrary point
               ■ For left-end selection, the arbitrary point is the left endpoint of each subinterval.
          ○ Left endpoints: 𝒙ₖ* = 𝒙ₖ₋₁  (left Riemann sum).
               ■ For right-end selection, the arbitrary point is the right endpoint of each subinterval.
          ○ Right endpoints: 𝒙ₖ* = 𝒙ₖ    (right Riemann sum).
               ■ For midpoint selection, the arbitrary point is the midpoint of each subinterval.
          ○ Midpoints: 𝒙ₖ* = (𝒙ₖ₋₁ + 𝒙ₖ)/2 (often more accurate for smooth 𝒇). 
               ■   xₖ₋₁        xₖ*          xₖ
                    │----------│----------│   ← base = Δx;  k ∈ {1, 2, …, n}
                                 ▲
                                  │ 𝒇(xₖ*)  
          ○ According to the choice.
               ■ A formula is needed to calculate each arbitrary point.
               ■ The goal is to find a formula for 𝒙ₖ* so it can be substituted into 𝒇(𝒙ₖ*).
                    ▣ 𝒜ₙ  =  limₙ→∞ ∑ (from k=1 to n) 𝒇(𝒙ₖ*) · Δ𝒙 
               ■ It is explained that the formula for 𝒙ₖ* will give a value in terms of 𝒙 and k.
               ■ The result allows one to handle the sum and the limit.
     ◉ [57:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3440). The formula for each arbitrary points 𝒙ₖ* must start with 𝓪
          ○ 𝒙ₖ* = 𝓪 . . .
          
● [58:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3500). Arbitrary points using the right endpoint.
          ○ It is explained that for right endpoints, the first arbitrary point is 𝓪 + Δ𝒙, not just a.
          ○ The second arbitrary point is 𝓪 + 2⋅Δ𝒙.
          ○ For the nth point, the distance from a is n⋅Δ𝒙.
          ○ The formula for 𝒙ₖ* using the right endpoint is 𝒙ₖ* =  𝒙ₖ  = 𝓪 + k⋅Δ𝒙.
          
● [1:0:17](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3617). Arbitrary points using the left endpoint.
          ○ It is explained that for left endpoints, the first arbitrary point is 𝓪.
          ○ The second arbitrary point is 𝓪 + Δ𝒙.
          ○ The formula for 𝒙ₖ* using the left endpoint is 𝒙ₖ* = 𝒙ₖ₋₁ = 𝓪 + (k - 1)⋅Δ𝒙.
          ○ It is noted that, compared to the right endpoints, one starts one subinterval earlier.
          
● [1:02:35](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3755). Arbitrary points using the midpoint.
          ○ It is stated that for midpoints, one must compute half the width of each subinterval.
          ○ The general formula for the midpoint is 𝒙ₖ* =  (𝒙ₖ₋₁ + 𝒙ₖ)/2 = 𝓪 + (k - ½)⋅Δ𝒙.
          ○ Midpoints often provide a better approximation even with fewer rectangles, especially for smooth functions.


● Summary of formulas for arbitrary points.
   | Method            | Formula for 𝒙ₖ*                  | Equivalent form             |
|-------------------|----------------------------------|-----------------------------|
| Left Endpoints    | 𝒙ₖ* = 𝓪 + (k − 1)Δ𝒙             | 𝒙ₖ₋₁                       |
| Right Endpoints   | 𝒙ₖ* = 𝓪 + kΔ𝒙                   | 𝒙ₖ                         |
| Midpoints         | 𝒙ₖ* = 𝓪 + (k − ½)Δ𝒙             | (𝒙ₖ₋₁ + 𝒙ₖ)/2              |
  


     
       

Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｐｒａｃｔｉｃａｌ　ａｐｐｌｉｃａｔｉｏｎ　ｏｆ　ｔｈｅ　ｍｅｔｈｏｄ

● [1:04:26](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3866). A practical example is necessary to understand the method’s concept.
     ◉ The idea is to sum the areas of small rectangles and then apply the limit.
     ◉ The concept of limits is the foundation of calculus.

● [1:05:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=3950). 🧩 Example –1: Calculating the area under 𝒇(𝒙) = 𝒙² on [0,1] using right endpoints. [📷image-1](../img/Calculus 1 Lecture 4.3/[1-05-50]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.3/[1-05-50]-02.png)
     ◉ In real life one could pick any arbitrary point, and all choices yield the same final result.
     ◉ Right endpoints are used here.
     ◉ It is mentioned that right endpoints are often easier to handle than left endpoints.
     ◉ The first step is to calculate Δ𝒙.
     ◉ [1:06:55](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4015). Step 1: Calculate Δ𝒙.
          ○ The formula Δ𝒙 = (𝓫 - 𝓪)/n is stated.
          ○ With 𝓪 = 0 and 𝓫 = 1, it follows that Δ𝒙 = 1/n.
     ◉ [1:09:05](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4145). Step 2: Calculate 𝒙ₖ*
          ○ Recall the formula for the right endpoint: 𝒙ₖ* = a + k⋅Δ𝒙.
          ○ Substituting 𝓪 = 0 and Δ𝒙 = 1/n gives 𝒙ₖ* = k/n.
     ◉ [1:10:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4250). Step 3: Calculate 𝒇(𝒙ₖ*).
          ○ It is recalled that 𝒙ₖ* must be substituted into the function 𝒇(𝒙).
          ○ Substituting 𝒙ₖ* = k/n into 𝒇(𝒙) = 𝒙² gives 𝒇(𝒙ₖ*) = (k/n)².
          ○ If there were a constant added to 𝒙ₖ*, the problem would be more difficult.
          ○ It is noted that this can be done using the integral as well.
     ◉ [1:13:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4380). Step 4: Build the summation.
          ○ The approximation for the area is given by ∑ (from k=1 to n) [𝒇(𝒙ₖ*)⋅Δ𝒙]
          ○ The previously calculated values are substituted.
               ■ ∑ (from k=1 to n) (k² / n³) 
          ○ This expression must be algebraically manipulated to be evaluated.
          ○ Manipulating the summation.
               ■ The property of summation is used to separate constants.
               ■ It is noted that k² is a variable term and n³ is constant in the summation, so n³ can be factored out.
               ■ This property is why the earlier steps were carried out.
                         ▢ ∑ (from k=1 to n) (k² / n³) → (1 / n³) · ∑ (from k=1 to n) k²
               ■ The formula for summing k² is applied: ∑ (from k=1 to n) k² = [n⋅(n+1)⋅(2n+1)] / 6
               ■ hence: ∑ (from k=1 to n) (k² / n³) = [(2n² + 3n + 1) / (6n²)]
     ◉ [1:17:30](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4650). Step 5: Calculate the limit.
          ○ After evaluating the summation, lim_(n → ∞) can be computed.
          ○ It is noted that such a limit yields a finite value since the area under the curve is finite.
          ○ The limit is applied to the previously obtained algebraic expression.
          ○ The method for solving limits at infinity for rational functions is recalled.
          ○ By applying these properties, the result 1/3 is obtained.
               ■ lim_ (n → ∞) [(2n² + 3n + 1) / (6n²)] = 1/3
          ○ It is concluded that the area under 𝒇(𝒙) = 𝒙² on [0, 1] is 1/3.

          

Ｄｉｓｃｕｓｓｉｏｎ　ｏｎ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　“ｓｉｇｎｅｄ　ｎｅｔ　ａｒｅａ”

● [1:22:40](https://www.youtube.com/watch?v=F0uuW-I6icY&t=4960). The concept of “signed net area”.[📷image](../img/Calculus 1 Lecture 4.3/[1-22-40]-01.png) 
     ◉ The concept of “signed net area” is introduced as the result of the integration method.  
     ◉ Up to this point, the examples considered functions entirely above the 𝒙-axis.  
     ◉ When the function dips below the 𝒙-axis:  
          ○ The integral assigns **positive area** to regions above the axis.  
          ○ The integral assigns **negative area** to regions below the axis.  
     ◉ The net area is obtained by combining both contributions:  
          ○ 𝒜 = 𝒜_above − 𝒜_below  
          ○ This means the integral computes the difference, not the total geometric area.  
     ◉ Important clarification:  
          ○ Symmetry alone does not determine the sign of the result.  
          ○ The computed value is always the **signed net area**, which incorporates the idea of orientation relative to the 𝒙-axis.  
     ◉ 🧩 Example –: ∫ (from -1 to 1) 𝑥 · d𝑥  
          ○ The graph of 𝑓(𝑥) = 𝑥 is symmetric about the origin.  
          ○ The area from [0,1] is positive: ∫[0,1] 𝑥∙d𝑥 = 1/2.  
          ○ The area from [−1,0] is negative: ∫[−1,0] 𝑥∙d𝑥 = −1/2.  
          ○ Adding them: (1/2) + (−1/2) = 0.  
               ■ The **total area** (geometric) is 1, but the **net signed area** is 0.  

● [1:27:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=5240). 🧩 Example – 2: Calculating the net area under 𝒇(𝒙) = 𝒙 - 1 on [0,2] using **left endpoints**. [📷image-1](../img/Calculus 1 Lecture 4.3/[1-27-20]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.3/[1-27-20]-02.png) [📷image-3](../img/Calculus 1 Lecture 4.3/[1-27-20]-03.png)
     ◉ [1:27:50](https://www.youtube.com/watch?v=F0uuW-I6icY&t=5270). Step 1: Calculate Δ𝒙
          ○ The formula Δ𝒙 = (𝓫 - 𝓪)/n is noted
          ○ With 𝓪 = 0 and 𝓫 = 2, it follows that Δ𝒙 = 2/n
     ◉ [1:28:20](https://www.youtube.com/watch?v=F0uuW-I6icY&t=5300). Step 2: Calculate  𝒙ₖ*
          ○ Recall the formula for the left endpoint:  𝒙ₖ* = 𝓪 + (k - 1)⋅Δ𝒙
          ○ Substituting 𝓪 = 0 and Δ𝒙 = 2/n yields  𝒙ₖ* = [2(k - 1)] / n
          ○ It is recommended not to distribute 2/n for easier subsequent operations.
     ◉ [1:30:30](https://www.youtube.com/watch?v=F0uuW-I6icY&t=5430). Step 3: Calculate 𝒇(**𝒙ₖ***).
          ○ The value 𝒙ₖ* is substituted into 𝒇(𝒙).
          ○ Substituting 𝒙ₖ* = 2(k - 1)/n into 𝒇(𝒙) = 𝒙 - 1 gives 𝒇(𝒙ₖ*) = [2(k - 1)/n] - 1
     ◉ [1:32:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=5520). Step 4: Build the summation.
          ○ The approximation for the net area is ∑ (from k=1 to n) [𝒇(𝒙ₖ*)⋅Δ𝒙]
          ○ The values calculated earlier are substituted.
               ■  ∑ (from k = 1 to n) [(2(k - 1) / n) - 1] · (2 / n)
          ○ Manipulating the summation.
              → ∑ (from k = 1 to n) [(4(k - 1) / n²) - (2 / n)]  
              → [4 / n²] ⋅ ∑ (from k = 1 to n) (k - 1) - [2 / n]⋅ ∑ (from k = 1 to n) 1  
              → [4 / n²] ⋅ [∑ (from k = 1 to n) k - ∑ (from k = 1 to n) 1] - [2 / n]⋅n  
              → [4 / n²] ⋅ [(n(n + 1) / 2) - n] - 2  
              → [2(n + 1) / n] - (4 / n) - 2  
              → 2 + (2 / n) - (4 / n) - 2  
     ◉ [1:44:30](https://www.youtube.com/watch?v=F0uuW-I6icY&t=6270). Step 5: Calculate the limit.
          ○ After evaluating the summation, the limit as n → ∞ is taken.
          ○ The limit operation is applied to the resulting algebraic expression.
          ○ limₙ→∞ ∑ (from k = 1 to n) 𝒇(𝒙ₖ*)⋅ Δ𝒙   → limₙ→∞ [2/n - 4/n]  →  lim_( n → ∞) [-2/n]  = 0
          ○ An area of 0 is peculiar and suggests analyzing the graph.
     ◉ [1:46:00](https://www.youtube.com/watch?v=F0uuW-I6icY&t=6360). Graphical analysis of the result.
          ○ The function 𝒇(𝒙) = 𝒙 - 1 is described as a line with slope 1 and y-intercept -1.
          ○ The area of triangles above and below the 𝒙-axis is computed.
          ○ The result is 0 because positive and negative areas cancel each other out.

● [1:48:55](https://www.youtube.com/watch?v=F0uuW-I6icY&t=6535). 🧩 Example – 3: Calculating the net area under f(x) = 2x − x³ on [0,1] using right endpoints.  [📷image-1](../img/Calculus 1 Lecture 4.3/[1-48-55]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.3/[1-48-55]-02.png)
     ◉ Step 1: Calculate Δx
          ○ Formula: Δx = (𝓫-𝓪)/n = (1 − 0)/n = 1/n
     ◉ Step 2: Define the right endpoint 𝒙ₖ*
          ○ Formula: 𝒙ₖ* = 𝓪 + k·Δx
          ○ With 𝓪 = 0 and Δx = 1/n → 𝒙ₖ* = k/n
     ◉ Step 3: Evaluate the function at the right endpoint
          ○ f(𝒙ₖ*) = 2(k/n) − (k/n)³
     ◉ Step 4: Build the summation
          ○ Approximation: ∑ (from k=1 to n) f(𝒙ₖ*)·Δx
          ○ = ∑ (from k=1 to n) [2(k/n) − (k/n)³]·(1/n)
          ○ = ∑ (from k=1 to n) [(2k / n²) − (k³ / n⁴)]
          ○ Split: (2/n²) ∑ (from k=1 to n) k − (1/n⁴) ∑ (from k=1 to n) k³
     ◉ Step 5: Apply summation formulas
          ○ ∑ (from k=1 to n) k = n(n+1)/2
          ○ ∑ (from k=1 to n) k³ = [n(n+1)/2]²
          Substitution:
          (2/n²)·[n(n+1)/2] − (1/n⁴)·[n(n+1)/2]² = (n+1)/n − (n²+2n+1)/(4n²)
                                                                      = (n/n + 1/n) − (n²+2n+1)/(4n²)
                                                                      = ( n/n + 1/n ) − ( n²/(4n²) + 2n/(4n²) + 1/(4n²) )
     ◉ Step 6: Take the limit as n → ∞
           limₙ→∞ [(n+1)/n − (n²+2n+1)/(4n²)] = limₙ→∞ [1 + 1/n − 1/4 − 2/(4n) − 1/(4n²)]
                                                                     = 1 − 1/4 = 3/4
     ◉ Final Answer:
           The net area under f(x) = 2x − x³ on [0,1] is:
           𝒜 = 3/4
