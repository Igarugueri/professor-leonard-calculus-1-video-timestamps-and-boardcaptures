----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　１．２：　Pｒｏｐｅｒｔｉｅｓ　Oｆ　Lｉｍｉｔｓ．　Ｔｅｃｈｎｉｑｕｅｓ　Oｆ　Lｉｍｉｔ　Cｏｍｐｕｔａｔｉｏｎ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ ｔｏ ｔｈｅ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｌｉｍｉｔｓ

● [0:50]. The Limit of a Constant: 
     ◉ The limit of a constant is defined as: limₓ→ₐ 𝓒 = 𝓒, where 𝓒 is a constant.
     ◉ If a function always has the same value, it doesn’t matter what value x approaches — the result does not change.
     
● [2:53]. The Limit of a Simple Variable: 
     ◉ The limit of a simple variable is defined as: limₓ→ₐ 𝒙 = 𝒂.
     ◉ If the function is just 𝒙 itself, then as 𝒙 gets closer to a, the function gets closer to a — so the limit is the value it approaches.
     
● [5:10]. The Importance of Equality of One-sided Limits: 
     ◉ The importance that the one-sided limits are equal for the general limit to e𝒙ist is emphasized.
     ◉ Examples of one-sided limits that are not equal are provided, resulting in the non-e𝒙istence of the general limit.
          ○ limₓ→₀⁻ 1/x = -∞ and limₓ→₀⁺ 1/𝒙 = +∞    



     
Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｌｉｍｉｔｓ

● [6:25]. Properties of Limits: 
     ◉ The properties of limits are introduced, including sum, difference, product, quotient, and e𝒙ponents.
           ○ If limₓ→ₐ 𝒇(𝒙) = 𝑳 and limₓ→ₐ 𝓰(𝒙) = 𝑳₂, then:
                1.2.1 limₓ→ₐ   𝒇(𝒙)  ±  𝓰(𝒙)  = limₓ→𝒂) 𝒇(𝒙)  ± limₓ→𝒂 𝓰(𝒙)
                1.2.2 limₓ→ₐ  𝒇(𝒙)  ·  𝓰(𝒙) ] = limₓ→𝒂) 𝒇(𝒙)  · limₓ→𝒂 𝓰(𝒙)
                1.2.3 limₓ→ₐ   𝒇(𝒙) / 𝓰(𝒙) = limₓ→𝒂) 𝒇(𝒙)  / limₓ→𝒂 𝓰(𝒙),  provided limₓ→𝒂 𝓰(𝒙) ≠ 0
                1.2.4 limₓ→ₐ  𝒇(𝒙)ⁿ = (limₓ→ₐ 𝒇(𝒙))ⁿ
                     1.2.4.1 limₓ→ₐ   ⁿ√𝒇(𝒙) = ⁿ√(limₓ→ₐ 𝒇(𝒙)) (✔ The property is valid only if the limit exists, and in the case of even roots, the value inside the root must be non-negative)

● [11:05]. Recapitulation

     

Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ ｉｎ Ｐｏｌｙｎｏｍｉａｌｓ

● [12:20]. 🧩 Evaluation of limₓ→₂  𝒙³ - 2𝒙 + 7: 
     ◉ limₓ→₂ (𝒙³ - 2𝒙 + 7) is calculated using the properties of limits.
          ○ limₓ→₂ 𝒙³ - limₓ→₂ 2𝒙 + limₓ→₂ 7
             limₓ→₂ 𝒙³  -  (limₓ→₂ 2) ⋅ (limₓ→₂ 𝒙)  + limₓ→₂ 7
             limₓ→₂ 𝒙³ - 2𝒙 + 7 = 11
             f(2) = 11
     
● [17:04].  𝑻𝒉𝒆 𝑳𝒊𝒎𝒊𝒕 𝒐𝒇 𝑨𝒏𝒚 𝑷𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍: 
     ◉ limₓ→ₐ 𝒫(𝒙) = 𝒫(𝒂)
          ○ 𝑻𝒉𝒆 𝒍𝒊𝒎𝒊𝒕 𝒐𝒇 𝒂 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒂𝒔 𝒙 𝒂𝒑𝒑𝒓𝒐𝒂𝒄𝒉𝒆𝒔 𝒂 𝒑𝒐𝒊𝒏𝒕 𝒂 𝒊𝒔 𝒋𝒖𝒔𝒕 𝒕𝒉𝒆 𝒗𝒂𝒍𝒖𝒆 𝒐𝒇 𝒕𝒉𝒆 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍 𝒂𝒕 𝒕𝒉𝒂𝒕 𝒑𝒐𝒊𝒏𝒕.
     
● [20:16]. 🧩 Evaluation of limₓ→₂  (𝒙⁵ - 3𝒙 + 4)³:³.png) 
     ◉ The calculation is simplified by evaluating the function at 𝒙 = 2 and then cubing the result.
     

   
 

Ｌｉｍｉｔｓ ｏｆ Ｎｏｎ－Ｐｏｌｙｎｏｍｉａｌ Ｆｕｎｃｔｉｏｎｓ

● [23:05]. 🧩  Evaluation of limₓ→₂  (4𝒙² + 1) / (𝒙 + 3):  ∕  (𝒙 + 3).png) 
     ◉ Apply property 1.2.3 → limₓ→₂ (4𝓍² + 1) / limₓ→₂  (𝓍 − 3) 
     ◉ Then we check that both the numerator and the denominator are polynomials, so we can substitute 𝒙 = 2  directly.

● [26:20]. 🧩 Evaluation of  limₓ→₁   ∛((5𝒙 + 7) / (𝒙² + 1))  ∕  (𝒙² + 1)).png) 
     ◉ limₓ→₁  ∛((5𝒙 + 7) / (𝒙² + 1))  =  ∛((5·1 + 7) / (1² + 1)) = ∛6
     ◉ It is mentioned that the same properties as for polynomials can be used, as long as domain issues, such as division by zero, are avoided.
          
● [28:50]. 🧩 Evaluation of  limₓ→₂  (𝒙² - 4) / (𝒙-2)  ∕ (𝒙-2).png) 
     ◉ limₓ→₂  (𝒙² − 4) / (𝒙 − 2)  
         limₓ→₂ [ ((𝒙 + 2)(𝒙 − 2)) / (𝒙 − 2)
         limₓ→₂  [ (𝒙 + 2)  ] 
         Cancel (𝒙 − 2), since we are not evaluating exactly at 𝒙 = 2, but rather approaching it. 
         limₓ→₂  [ 𝒙 + 2 ] = 2 + 2 = 4
     ◉ The original function is undefined because the denominator becomes zero (𝒙 − 2 = 0).  
          ○ This creates a  𝒉𝒐𝒍𝒆 in the graph at the point (2, 4). The function does not diverge to infinity; it simply has a removable discontinuity.  
          ○ This is different from a vertical asymptote, which occurs when the denominator approaches zero but the numerator does  𝒏𝒐𝒕 approach
             zero at the same time (the numerator doesn’t become zero when the denominator does) — causing the function to diverge  to +∞ or −∞.
              
● 📝 N͟O͟T͟E͟: 𝑰𝒇 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒃𝒆𝒄𝒐𝒎𝒆𝒔 𝒛𝒆𝒓𝒐 𝒂𝒏𝒅 𝒘𝒆 𝒄𝒂𝒏 𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒚 𝒕𝒉𝒆 𝒆𝒙𝒑𝒓𝒆𝒔𝒔𝒊𝒐𝒏 𝒃𝒚 𝒄𝒂𝒏𝒄𝒆𝒍𝒊𝒏𝒈 𝒂 𝒄𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓 𝒘𝒊𝒕𝒉 𝒕𝒉𝒆 𝒏𝒖𝒎𝒆𝒓𝒂𝒕𝒐𝒓, 𝒕𝒉𝒆𝒏 𝒕𝒉𝒆𝒓𝒆'𝒔 𝒋𝒖𝒔𝒕 
                     𝒂 𝒉𝒐𝒍𝒆 — 𝒕𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒊𝒔 𝒔𝒕𝒊𝒍𝒍 𝒘𝒆𝒍𝒍-𝒃𝒆𝒉𝒂𝒗𝒆𝒅 𝒏𝒆𝒂𝒓𝒃𝒚. 𝑩𝒖𝒕 𝒊𝒇 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒊𝒔 𝒛𝒆𝒓𝒐 𝒂𝒏𝒅 𝒘𝒆  𝒄͟𝒂͟𝒏͟’͟𝒕͟  𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒚, 𝒕𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒃𝒍𝒐𝒘𝒔 𝒖𝒑 — 𝒕𝒉𝒂𝒕'𝒔 
                     𝒂 𝒗𝒆𝒓𝒕𝒊𝒄𝒂𝒍 𝒂𝒔𝒚𝒎𝒑𝒕𝒐𝒕𝒆.


     
Ｆａｃｔｏｒｉｚａｔｉｏｎ ａｎｄ Ｓｉｍｐｌｉｆｉｃａｔｉｏｎ ｔｏ Ｅｖａｌｕａｔｅ Ｌｉｍｉｔｓ

● [33:45]. Factorization and Simplification to Evaluate Limits: 
     ◉ 🧩 Evaluation of limₓ→₋₄  (2𝒙 + 8) / (𝒙² + 𝒙 - 12) 
              limₓ→₋₄ (2𝒙 + 8) / (𝒙² + 𝒙 − 12) 
               limₓ→₋₄  2(𝒙 + 4) / ((𝒙 + 4)(𝒙 − 3)) 
              limₓ→₋₄  2 / (𝒙 − 3) = 2 / (−4 − 3) = 2 / (−7) = −2/7
     ◉ The technique of factoring and simplifying serve for evaluate limits when direct substitution results in 0/0.
     ◉ 𝑪𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓𝒔 𝒊𝒏 𝒂 0/0 𝒊𝒏𝒅𝒆𝒕𝒆𝒓𝒎𝒊𝒏𝒂𝒕𝒊𝒐𝒏 𝒇𝒐𝒓 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔: 𝑰𝒇 𝒃𝒐𝒕𝒉 𝒕𝒉𝒆 𝒏𝒖𝒎𝒆𝒓𝒂𝒕𝒐𝒓 𝒂𝒏𝒅 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒂𝒓𝒆 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔 
         𝒂𝒏𝒅 𝒃𝒆𝒄𝒐𝒎𝒆 0 𝒂𝒕 𝒕𝒉𝒆 𝒔𝒂𝒎𝒆 𝒑𝒐𝒊𝒏𝒕 𝒙=𝒄, 𝒊𝒕 𝒎𝒆𝒂𝒏𝒔 𝒕𝒉𝒂𝒕 𝒙=𝒄 𝒊𝒔 𝒂 𝒓𝒐𝒐𝒕 𝒐𝒇 𝒃𝒐𝒕𝒉 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔. 𝑻𝒉𝒊𝒔 𝒊𝒎𝒑𝒍𝒊𝒆𝒔 𝒕𝒉𝒆𝒚 𝒔𝒉𝒂𝒓𝒆
         𝒂 𝒄𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓 (𝒙−𝒄). 𝑻𝒉𝒊𝒔 𝒇𝒂𝒄𝒕𝒐𝒓 𝒄𝒂𝒏 𝒃𝒆 𝒆𝒍𝒊𝒎𝒊𝒏𝒂𝒕𝒆𝒅 𝒕𝒉𝒓𝒐𝒖𝒈𝒉 𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒊𝒄𝒂𝒕𝒊𝒐𝒏, 𝒂𝒍𝒍𝒐𝒘𝒊𝒏𝒈 𝒕𝒉𝒆 𝒍𝒊𝒎𝒊𝒕 𝒕𝒐 𝒃𝒆 𝒓𝒆𝒔𝒐𝒍𝒗𝒆𝒅.
     ◉ The importance of maintaining the limit notation until the limit is evaluated is emphasized.



Ｌｉｍｉｔｓ   ｗｉｔｈ   Ｖｅｒｔｉｃａｌ   Ａｓｙｍｐｔｏｔｅｓ

● [38:23]. 🧩 Evaluation of limₓ→₅  (𝒙² - 3𝒙 - 10) / (𝒙² - 10𝒙 + 25)  ∕ (𝒙² - 10𝒙 + 25).png) 
     ◉ limₓ→₅ (𝒙² - 3𝒙 - 10) / (𝒙² - 10𝒙 + 25) is attempted by factoring and simplifying, but a 🔶vertical asymptote🔶 is found.
          ○ limₓ→₅ (𝒙² − 3𝒙 − 10) / (𝒙² − 10𝒙 + 25) 
             limₓ→₅ ((𝒙 − 5)(𝒙 + 2))/ ((𝒙 − 5)(𝒙 − 5)) 
             limₓ→₅ (𝒙 + 2) / (𝒙 − 5) 
          ○ 📝 N͟O͟T͟E͟: Before rushing to factor the expression, 𝒂𝒍𝒘𝒂𝒚𝒔 𝒄𝒉𝒆𝒄𝒌 the value you're approaching—in this case, 𝒙 = 5.  
                                If plugging in the number gives a defined result, there's no need to factor.  Factoring would just waste time and might confuse you unnecessarily.
     ◉ The difference is clarified between:
          ○  A 𝒉𝒐𝒍𝒆 in the graph (removable discontinuity, can be simplified), and  
          ○  A 🔶vertical asymptote🔶 (non-removable, cannot be simplified).
     ◉ [40:45].   ͟𝐒͟𝐢͟𝐠͟𝐧͟ ͟𝐀͟𝐧͟𝐚͟𝐥͟𝐲͟𝐬͟𝐢͟𝐬͟ ͟𝐓͟𝐞͟𝐬͟𝐭͟:
          ○ The sign analysis test is presented to determine the behavior of a function **around** a 🔶vertical asymptote🔶.
               ■ Steps for Sign Analysis at 𝒙 = 5:
                    1.  Check the function:
                           - At 𝒙 = 5, the denominator becomes 0 and cannot be canceled out.
                           - This means there is a 🔶vertical asymptote🔶 at 𝒙 = 5 — not a hole.
                     2. Identify key points:
                           - Problem point: 𝒙 = 5
                           - Optional helper point: 𝒙 = −2 (just to clearly separate intervals on the number line)
                     3. Draw a number line to analyze signs
                              ─────●───────────────●────
                                          -2                                      5
                    4. Pick a number to the right of 5 (e.g., 𝒙 = 6):
                            𝒇(𝒙) = (𝒙 + 2)/(𝒙 − 5)
                            𝒇(6) = (6 + 2)/(6 − 5) = 8/1 = 8 > 0 → Positive
                            So as 𝒙 → 5⁺, 𝒇(𝒙) → +∞
                                                                                    |
                                                                                    |
                                                                                   ╰----
                             ─────●───────────────●────
                                         -2                                      5
                        5. Pick a number to the left of 5 (e.g., 𝒙 = 0):
                             𝒇(𝒙) = (𝒙 + 2)/(𝒙 − 5)
                             𝒇(0) = (0 + 2)/(0 − 5) = 2/−5 = −2/5 < 0 → Negative
                            So as 𝒙 → 5⁻, 𝒇(𝒙) → −∞
                                                                                |
                                                                                |
                                                                               ╰---
                            ─────●──────────────●────
                                         -2                           ---╮5
                                                                            |
                                                                            |
              6. The limit D.N.E because the left-hand limit (−∞) and right-hand limit (+∞) are not the same.
                  This confirms a vertical asymptote at 𝒙 = 5.


                  
Ｓｕｍｍａｒｙ ｏｆ Ｔｅｃｈｎｉｑｕｅｓ ｆｏｒ Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ

● [47:35]. Summary of Techniques for Evaluating Limits 
     ◉ 📝 NOTE:
                          ① If 𝟎/𝟎, factor and simplify.
                          ② If you can’t cancel the “problem,” check with  ͟𝐒͟𝐢͟𝐠͟𝐧͟ ͟𝐀͟𝐧͟𝐚͟𝐥͟𝐲͟𝐬͟𝐢͟𝐬͟ ͟𝐓͟𝐞͟𝐬͟𝐭͟  because the limit might not exist.


     
Ｒａｔｉｏｎａｌｉｚａｔｉｏｎ ｔｏ Ｅｖａｌｕａｔｅ Ｌｉｍｉｔｓ

● Rationalization to Evaluate Limits:
     ◉ When solving limits involving radicals:
           ① Multiply by the conjugate:
                  ➔ Especially if there’s a radical in the denominator.
                  ➔ The goal is to eliminate the radical from the denominator. Multiply by the conjugate to use the identity:
                          (a - b)(a + b) = a² - b²
                  ➔ This clears the radical in the denominator.
           ② Do not expand (distribute) the numerator immediately:
                  ➔ Avoid expanding the numerator right away.
                  ➔ First, look to simplify — sometimes you can cancel factors.
                  ➔ If you expand too soon, you might miss cancellations and make the problem messier.   

● [50:50]. 🧩 Evaluation of limₓ→₁ (𝒙 -1 ) /  (√(𝒙) - 1)  ∕  (√(𝒙) - 1).png) 
     ◉ limₓ→₁ (𝒙−1) / (√(𝒙)−1) 
         limₓ→₁ (𝒙−1)∙(√(𝒙)+1)  /  (𝒙−1)       Multiply by the conjugate: (√𝒙+1) / (√𝒙+1)
         limₓ→₁ √(𝒙) + 1                               Simplify cancelling (𝒙−1)
         √1 + 1 = 2                                       Substitute directly
        
● [55:25]. 🧩 Evaluation of limₓ→₀  (√(1+𝒙) - 1) / 𝒙 - 1)  ∕ 𝒙.png) 
     ◉ limₓ→₀  (√(1+𝒙) − 1) / 𝒙 
         limₓ→₀  (1+𝒙) − 1 / ( 𝒙 ∙(√(1+𝒙) + 1) )         Multiply by by the conjugate: ( (√1+𝒙) + 1 ) / ( (√1+𝒙) + 1 )
         limₓ→₀  1 / (√(1+𝒙) + 1 )                             Simplify cancelling (𝒙)
         1 / (√(1+0) + 1 ) = 1/2                                 Substitute directly


     
Ｌｉｍｉｔｓ  ｂｙ  Ｐａｒｔｓ

● [1:01:10]. Limits by Parts 
     ◉ The concept of limits by parts is introduced, where different functions are considered for different intervals of the domain.
     ◉ I͟D͟E͟A͟: To evaluate a limit by parts (limits for piecewise functions), the one-sided limits 🟪at the points '𝒄'  of change of the functions must be considered🟪 
                    and see if they're equal:
                      ① You must check the limit from the left (𝒙 → 𝒄⁻) and from the right (𝒙 → 𝒄⁺) at the point 𝒄.
                            ➔ Finding the limit from the left means identifying which piece of the function approaches 𝒄 from values smaller than 𝒄.
                            ➔ Finding the limit from the right means identifying which piece of the function approaches 𝒄 from values larger than 𝒄.
                      ②  If both one-sided limits are equal, then the limit exists at 𝒄. If they are different, the overall limit does not exist at that point.

● [1:03:12]. 🧩 Evaluation of Limits by Parts:
     ◉ The need to determine which function to use for each one-sided limit, depending on the interval of the domain, is emphasized.
     ◉ An e𝒙ample of limit by parts is worked out for a function defined in three intervals.
          The function is:
           𝒇(𝒙) =  1/(𝒙+2)        if      𝒙 < -2            (𝒇₁)
           𝒇(𝒙) =  𝒙² - 5           if      -2 < 𝒙 ≤ 3      (𝒇₂)
          𝒇(𝒙) =  √(𝒙+13)        if      𝒙 > 3             (𝒇₃)
          ○ 🟪Points '𝒄'  of Change: find the limits as 𝒙 approaches -2 and 3🟪
          ○ [1:05:10]. Graphical Representation the e𝒙ample.
                               𝒇₁ ⇢  ⇠    𝒇₂     ⇢  ⇠  𝒇₃
                          <---------|----------------|---------->
                                     -2                  3
          ○ In this piecewise function 𝒇(𝒙):
              ■🟪We must check the limit at each transition point (𝒙 = -2 and 𝒙 = 3)🟪
                  Steps:
                        1. Find the limit from the left (𝒙 → 𝒄⁻) and the right (𝒙 → 𝒄⁺) separately at the point 𝒄:
                              - Finding the limit from the left means identifying which piece of the function is used when approaching 𝒄 from the left.
                                         Example: For 𝒙 → -2⁻, use 𝒇₁(𝒙).
                                         Example: For 𝒙 → 3⁻, use 𝒇₂(𝒙).
                              - Finding the limit from the right means identifying which piece of the function is used when approaching 𝒄 from the right.
                                          Example: For 𝒙 → -2⁺, use 𝒇₂(𝒙).
                                          Example: For 𝒙 → 3⁺, use 𝒇₃(𝒙).
                       2. Compare the limits at each point:
                             𝒙 = 3
                                    limₓ→₃⁻  𝒙² − 5] = 4
                                    limₓ→₃⁺  √(𝒙 + 13) = 4
                                    limₓ→₃ 𝒇(𝒙) = 4
                                    Due to the left and right limits are equal, the limit exists at 𝒙 = 3
                            𝒙 = -2
                                    limₓ→₋₂⁻ 1 / (𝒙 + 2) = −∞
                                    limₓ→₋₂⁺ 𝒙² − 5  = −1
                                    limₓ→₋₂ 𝒇(𝒙) = D.N.E.  (Does Not Exist)
                                    Due to they are different, the limit does not exist at 𝒙 = -2



Ｌｉｍｉｔｓ ｉｎ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｆｕｎｃｔｉｏｎｓ

● [1:19:43]. 𝙨𝒊𝙣(𝒙) 𝒂𝙣𝒅 𝒄𝙤𝒔(𝒙) 𝙖𝒓𝙚 𝙘𝒐𝙣𝒕𝙞𝒏𝙪𝒐𝙪𝒔 𝒆𝙫𝒆𝙧𝒚𝙬𝒉𝙚𝒓𝙚. 𝒂𝙣𝒅 𝒄𝙤𝒔(𝒙) 𝙖𝒓𝙚 𝙘𝒐𝙣𝒕𝙞𝒏𝙪𝒐𝙪𝒔 𝒆𝙫𝒆𝙧𝒚𝙬𝒉𝙚𝒓𝙚.png) 
     ◉ limₓ→ₐ 𝐬𝐢𝐧(𝒙) = 𝐬𝐢𝐧(𝒂)
     ◉ limₓ→ₐ 𝐜𝐨𝐬(𝒙) = 𝐜𝐨𝐬(𝒂)

● [1:22:32].  𝑻𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒕𝒂𝒏(𝒙) 𝒆𝒙𝒊𝒔𝒕𝒔 𝒆𝒙𝒄𝒆𝒑𝒕 𝒂𝒕 𝒕𝒉𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒘𝒉𝒆𝒓𝒆 𝒄𝒐𝒔(𝒙) = 0. 𝑻𝒉𝒆𝒔𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒂𝒓𝒆 𝒙 = ±π/2 + 𝒏π, 𝒏 ∈ 𝒁. 𝒆𝒙𝒊𝒔𝒕𝒔 𝒆𝒙𝒄𝒆𝒑𝒕 𝒂𝒕 𝒕𝒉𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒘𝒉𝒆𝒓𝒆 𝒄𝒐𝒔(𝒙) = 0 𝑻𝒉𝒆𝒔𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒂𝒓𝒆 𝒙 = ±π ∕ 2 + 𝒏π, 𝒏 ∈ 𝒁.png) 
     ◉ limₓ→ₐ tan(𝒙) = tan(a) ; 𝒙 ≠ ±π/2 + 𝒏π, 𝒏 ∈ 𝒁.  

● [1:28:15]. 🧩 Evaluation of limₓ→₁  𝐜𝐨𝐬((𝒙²−1) / (𝒙−1))  ∕  (𝒙−1)).png) 
     ◉ cos(𝒙) is 𝒄𝒐𝒏𝒕𝒊𝒏𝒖𝒐𝒖𝒔 𝒔𝒐 𝒃𝒚 𝒄𝒐𝒎𝒑𝒐𝒔𝒊𝒕𝒊𝒐𝒏 ...
         𝐜𝐨𝐬( limₓ→₁  (𝒙²−1)/(𝒙−1) )
         𝐜𝐨𝐬( limₓ→₁  (𝒙+1)(𝒙−1)/(𝒙−1) )
         𝐜𝐨𝐬( limₓ→₁  (𝒙+1) )
         𝐜𝐨𝐬(1+1)
         𝐜𝐨𝐬(2)
     ◉ 📝 NOTE: Since 𝐜𝐨𝐬(𝒙) is continuous, we can move the limit inside by the composition rule:
          ○ 𝓟𝓻𝓸𝓹𝓮𝓻𝓽𝔂: Limit of Continuous Functions (Composition Rule)
                Statement:
                                             If 𝒇(𝒙) is continuous at 𝒙 = a, then:
                                             limₓ→ₐ 𝒇(𝒙) = 𝒇(a)
                Application:
                                             For continuous functions like 𝐬𝐢𝐧(𝒙), 𝐜𝐨𝐬(𝒙), 𝐩𝐨𝐥𝐲𝐧𝐨𝐦𝐢𝐚𝐥𝐬, 𝐫𝐚𝐭𝐢𝐨𝐧𝐚𝐥𝐬, 𝐞𝐱𝐩𝐨𝐧𝐞𝐧𝐭𝐢𝐚𝐥𝐬, etc., 
                                             you can move the limit inside:
                                             limₓ→ₐ 𝒇(𝒙) = 𝒇(limₓ→ₐ 𝒙) = 𝒇(a)
                Important:
                                            This is why when dealing with continuous functions, limits are straightforward to compute.

● [1:33:00]. 🧩 Evaluation of limₓ→π∕₂  3𝒙² + cos(𝒙).png) 
     ◉ Since there is no issue of discontinuity or undefined values at 𝒙 = π/2, we are allowed to directly substitute the value into the expression.
     ◉📝 NOTE: Whenever the function is continuous at the point — meaning there is no division by zero,
                           no square root of a negative number in the real domain, and no discontinuity — 
                           we can evaluate the limit by direct substitution.
     ◉ So: limₓ→π∕₂  3𝒙² + cos(𝒙) = 3(π/2)² + cos(π/2)
                                                    = 3(π²/4) + 0
                                                    = (3π²)/4

● [1:37:15]. ∴ 𝑫𝒆𝒎𝒐𝒏𝒔𝒕𝒓𝒂𝒕𝒊𝒐𝒏 𝒐𝒇 limₓ→₀ 𝒔𝒊𝒏 (𝒙) / 𝒙 = 1  ∕ 𝒙 _1.png)  ∕ 𝒙 _2.png) 
     ◉ limₓ→₀  sin 𝒙 / 𝒙  = 1 is demonstrated using the squeeze theorem and areas of triangles and sectors.
     ◉ Triangles and sectors in a unit circle are constructed to compare their areas and establish the necessary inequalities for the squeeze theorem.
     ◉ To understand why limₓ→₀ 𝒔𝒊𝒏(𝒙)/𝒙 = 1, we can use a geometric approach involving areas in the unit circle. Here's a step-by-step explanation:
          ○ 1. Unit Circle Setup:
               ■ Consider a unit circle centered at the origin.
               ■ Let 𝒙 be an angle near 0 on the positive 𝒙-axis.
          ○ 2. First Triangle;  Two possible interpretations:
               ■ Option 1: Right triangle
                    ▣ Base = cos(𝒙), height = sin(𝒙).
                    ▣ Area = (1/2) × cos(𝒙) × sin(𝒙).
                    ▣ It is a right triangle formed by dropping a perpendicular from the circle to the x-axis.
               ■ Option 2: General triangle (more accurate for this limit discussion)
                    ▣ Base = 1 (the radius of the unit circle).
                    ▣ Height = sin(𝒙).
                    ▣ Area = (1/2) × 1 × sin(𝒙) = (1/2)·sin(𝒙).
                    ▣ This is a scalene triangle (three unequal sides), not necessarily a right triangle.
               ■ 📝 NOTE: For the purpose of proving the  limit limₓ→₀ 𝒔𝒊𝒏(𝒙)/𝒙 = 1, we usually consider the triangle where the base is 1 and the height is sin(𝒙),
                                    leading to the simpler expression Area = (1/2)·sin(𝒙).
          ○ 3. Sector Area (Area = (1/2)·𝒙):
               ■ The sector is formed by the angle 𝒙 in the unit circle.
               ■ The area formula for a sector is (1/2)·r²·θ. Since r = 1, it simplifies to (1/2)·𝒙.
          ○ 4. Larger Triangle Involving the Tangent Line:
               ■ Extend the tangent line from the point where the terminal side meets the circle.
               ■ This creates a larger triangle whose height corresponds to tan(𝒙).
          ○ 5. Setting Up Inequalities:
               ■ Comparing areas:  (1/2)·sin(𝒙) < (1/2)·𝒙 < (1/2)·tan(𝒙) 
          ○ 6. Simplifying the Inequalities:
               ■ Multiply through by 2:   sin(𝒙) < 𝒙 < tan(𝒙)
               ■ Divide all parts by sin(𝒙):  1 < 𝒙/sin(𝒙) < 1/cos(𝒙)
               ■ By taking the reciprocal of all positive terms, the inequality reverses its direction:
                    ▣  1 < 𝒙/sin(𝒙) < 1/cos(𝒙)  ⟶  cos(𝒙) < sin(𝒙)/𝒙 < 1
          ○ 7. Applying the Squeeze Theorem:
               ■ As 𝒙 → 0, cos(𝒙) → 1, so 1/cos(𝒙) → 1.
               ■ Thus, 𝒙/sin(𝒙) is squeezed between 1 and something approaching 1.
               ■ By the Squeeze Theorem: limₓ→₀  𝒔𝒊𝒏(𝒙)/𝒙 = 1
     ◉ 📝 NOTE: In the proof using the Squeeze Theorem for limₓ→₀ (𝒔𝒊𝒏(𝒙)/𝒙) = 1, it is correct to use the symbol "<" instead of "≤". 
                           The reason is:
                                - We are comparing areas or values strictly, not saying they are equal.
                                - For very small 𝒙 near 0 (but not exactly 0), we have strict inequalities.
                                - The Squeeze Theorem only requires the function to be trapped between two functions, not necessarily touching them.
                                  Thus, using "<" is perfectly fine and appropriate.

● [1:55:00]. 🧩 Evaluation of limₓ→₀ (1 - cos 𝒙) / 𝒙  ∕  𝒙.png) 
     ◉ limₓ→₀ (1 - cos 𝒙) / 𝒙 is calculated using the technique of multiplying by the conjugate.
     ◉ The trigonometric identity 1 - cos² 𝒙 = sin² 𝒙 is used to simplify the e𝒙pression after multiplying by the conjugate.
     ◉ Multiply and divide by the conjugate of the numerator (1 + cos(𝒙)):
         = limₓ→₀  (1 - cos(𝒙))(1 + cos(𝒙))  /  𝒙(1 + cos(𝒙)) 
         = limₓ→₀ 1 - cos²(𝒙) ] / [ 𝒙(1 + cos(𝒙)) 
     ◉ Use the identity: 1 - cos²(𝒙) = sin²(𝒙)
         = limₓ→₀ sin²(𝒙) / 𝒙(1 + cos(𝒙)) 
     ◉ Split into two factors:
         = limₓ→₀ sin(𝒙)/𝒙  ·  sin(𝒙)/(1 + cos(𝒙)) 
     ◉ Apply known limits:
         limₓ→₀ sin(𝒙)/𝒙 = 1
         limₓ→₀ sin(𝒙) / (1 + cos(𝒙)) = 0 / 2 = 0
     ◉ limₓ→₀ (1 - cos 𝒙) / 𝒙 = 0

● [2:02:55].  🧩 Evaluation of limₓ→₀ tan 𝒙 / 𝒙 
     ◉ limₓ→₀ tan 𝒙 / 𝒙 is calculated using the identity tan 𝒙 = sin 𝒙 / cos 𝒙 .
     ◉ The e𝒙pression is split into two limits: limₓ→₀ sin 𝒙 / 𝒙 and limₓ→₀ 1 / cos 𝒙.
     ◉ Rewrite tangent as sine over cosine:
          = limₓ→₀ (sin(𝒙) / cos(𝒙)) / 𝒙 
     ◉ Simplify the complex fraction:
          = limₓ→₀  sin(𝒙) / cos(𝒙)  · 1 / 𝒙 
          = limₓ→₀  sin(𝒙) / 𝒙 ·  1 / cos(𝒙)
          = limₓ→₀  sin(𝒙) / 𝒙 · limₓ→₀ 1 / cos(𝒙)
          = limₓ→₀  sin(𝒙) / 𝒙 ·1
     ◉ Use known limit: limₓ→₀   sin(𝒙) / 𝒙 = 1
     ◉ limₓ→₀ tan 𝒙 / 𝒙 = 1              



Ｍａｎｉｐｕｌａｔｉｏｎ   ｏｆ   Ｔｒｉｇｏｎｏｍｅｔｒｉｃ   Ｌｉｍｉｔｓ

● Manipulation of Trigonometric Limits 
     ◉ Various examples of manipulating trigonometric limits to match known identities are presented.
     ◉ Examples with sin 𝒙 / 𝒙, (1 - cos 𝒙) / 𝒙, and tan 𝒙 / 𝒙 are included.
     ◉ Techniques such as multiplying by a constant, splitting the limit into multiple limits, and using trigonometric identities are used.
     ◉ **"We transform the unknown into something known"** using mathematical tools such as simplifications, identities, or properties.

● [2:08:00]. 🧩 Evaluation of limₓ→₀  sin (2𝒙) / 𝒙  ∕ 𝒙.png) 
     ◉ Multiply by 2/2 to create a form we can use:  limₓ→₀  sin(2𝒙) / 𝒙  · (2 / 2)
     ◉ Rearrange the expression: limₓ→₀  (2 · sin(2𝒙)) / (2𝒙)
     ◉ Factor out the constant 2:  2 · limₓ→₀ sin(2𝒙) / (2𝒙)
     ◉ Recognize the standard limit:  2 ·   llimᵤ→₀  sin(𝒖) / 𝒖 = 1  → where 𝒖 = 2𝒙
     ◉ So:    = 2 · 1 = 2
     ◉ limₓ→₀  sin(2𝒙) / 𝒙 = 2

● [2:13:40]. 🧩 Evaluation of limₓ→₀ sin (5𝒙) / 6𝒙  ∕ 6𝒙.png) 
     ◉ Multiply numerator and denominator by 1/𝒙: 
          limₓ→₀ sin(5𝒙) ∙ (1/𝒙)  /   sin(6𝒙) ∙ (1/𝒙) 
          limₓ→₀ (sin(5𝒙)/𝒙) / (sin(6𝒙)/𝒙)  
     ◉ Multiply numerator and denominator by constants:
          limₓ→₀ (sin(5𝒙)/𝒙) · (5/5) / (sin(6𝒙)/𝒙) · (6/6) 
     ◉ Rearrange the expression: 
         (5/6) · limₓ→₀  sin(5𝒙)/(5𝒙) / limₓ→₀ sin(6𝒙)/(6𝒙)
     ◉ Apply the standard limit identity: 
         limₓ→₀  sin(𝒖)/𝒖 = 1  → where 𝒖 = 5𝒙 and 𝒖 = 6𝒙 respectively
     ◉ So:  (5/6) · 1 / 1 = 5/6
     ◉ Therefore: limₓ→₀  sin(5𝒙) / sin(6𝒙) = 5/6

● [2:20:25]. 🧩 Evaluation of  limₓ→₀  sin (𝒙²) / 𝒙  ∕ 𝒙.png) 
     ◉ Rewrite as a product: limₓ→₀ (sin(𝒙²)/𝒙) · (𝒙/𝒙)
     ◉ Rearranged: limₓ→₀  𝒙 ·  sin(𝒙²)/𝒙²
     ◉ Split the limit: (limₓ→₀ 𝒙) · (limₓ→₀  sin(𝒙²)/𝒙²)
     ◉ Use the standard limit identity: llimᵤ→₀ (sin(u)/u) = 1 → with u = 𝒙²
     ◉ Therefore: 0 · 1 = 0
     ◉ Therefore: limₓ→₀ sin(𝒙²)/𝒙 = 0

● [2:24:20]. 🧩 Evaluation of limₓ→₀  sin² (𝒙) / 𝒙  ∕ 𝒙.png) 
     ◉ Use the identity: sin²(𝒙) = sin(𝒙) · sin(𝒙)
     ◉ Rewrite the expression: limₓ→₀ (sin(𝒙)/𝒙) · sin(𝒙)
     ◉ Split the limit: limₓ→₀  sin(𝒙)/𝒙 · limₓ→₀ sin(𝒙) 
     ◉ Apply known limits: 1 · 0 = 0
     ◉ Final result: limₓ→₀  sin²(𝒙)/𝒙  = 0

● [2:25:45]. 🧩 Evaluation of limₓ→₀ sin (1 / 𝒙) (Graphical approach) (Graphical approach).png) 
     ◉ limₓ→₀ sin (1 / 𝒙) = D.N.E
     ◉ Graph behavior:
          ○ As 𝑥 approaches 0, 1/𝑥 increases rapidly in magnitude.
          ○ This makes the sine function oscillate faster and faster.
     ◉ Infinite waves:
          ○ The graph oscillates infinitely between −1 and 1 as 𝑥 → 0.
          ○ It doesn't "settle" on any value — it doesn’t flatten or approach a specific number.
     ◉ No fixed value:
          ○ For the limit to exist, sin(1/𝑥) would need to get closer to a single number.
          ○ But instead, it keeps jumping around with no stabilization.
          ○ There are infinitely many peaks and valleys, getting tighter near 𝑥 = 0.
     ◉ Conclusion:
          ○ Since the function doesn't approach any one value as 𝑥 → 0, the limit does not exist.
          ○ The graph shows a dense “band” of oscillation between −1 and 1 near 𝑥 = 0.

● [2:25:45]. 🧩 Evaluation of limₓ→₀  𝒙∙sin (1 / 𝒙).png) 
     ◉ The correct approach is to apply the **Squeeze Theorem**:
     ◉ We know that:
            -1 ≤ sin(1/𝒙) ≤ 1
     ◉ Multiplying all parts by 𝒙 (which tends to 0), we get: 
            -|𝒙| ≤ 𝒙 · sin(1/𝒙) ≤ |𝒙|
          ○📝 NOTE: - we know that:
                                 ➔ -1 ≤ sin(1/𝒙) ≤ 1
                              - When multiplying by 𝒙, the direction of the inequalities depends on the sign of 𝒙:
                                 ➔ If 𝒙 > 0, the inequality remains the same.
                                 ➔ If 𝒙 < 0, the inequality reverses direction.
                              - To avoid this problem, we use the absolute value on the bounds of the inequality, as follows:
                                 ➔ -|𝒙| ≤ 𝒙 sin(1/𝒙) ≤ |𝒙|
    ◉ We introduce the absolute value to keep the direction of the inequality consistent, since multiplying by 𝒙 would 
        reverse the inequality when 𝒙 < 0. Using |𝒙| ensures the inequality remains −|𝒙| ≤ 𝒙·sin(1/𝒙) ≤ |𝒙| for both positive and negative 𝒙.
    ◉ Apply limits:
          limₓ→0 (−|𝒙|)  ≤  limₓ→0 (𝒙·sin(1/𝒙))  ≤  limₓ→0 (|𝒙|)
    ◉ And since:
          limₓ→0 |𝒙| = 0   ⇢   0 ≤ limₓ→0 (𝒙·sin(1/𝒙)) ≤ 0
   ◉ By the **Squeeze Theorem**, it follows that:
          limₓ→0  𝒙·sin(1/𝒙) = 0
     ◉ ⚠📝 NOTE:  At first glance, the limit:
                                          limₓ→₀ 𝒙 · sin(1/𝒙)
                               might look like it fits the identity:
                                          limᵤ→₀  (sin(𝒖)/𝒖) = 1
                               But that identity  𝐨𝐧𝐥𝐲 𝐚𝐩𝐩𝐥𝐢𝐞𝐬 when the argument of the sine 𝐚𝐧𝐝 the denominator 𝐛𝐨𝐭𝐡 
                               approach 0 at the same time. Now, if we rewrite:
                                         𝒙 · sin(1/𝒙) = sin(1/𝒙) / (1/𝒙)
                               Here, as 𝒙 → 0:
                                           ➔ 1/𝒙 → ∞,  
                                           ➔ and sin(1/𝒙) keeps oscillating between -1 and 1 with no limit.
                              So the expression  𝐬𝐢𝐧(𝟏/𝒙)/(𝟏/𝒙) doesn't approach 1, and we 𝐜𝐚𝐧𝐧𝐨𝐭 apply the identity.

● [2:35:33]. 🧩 Evaluation of limₓ→₀  (2 - cos(3𝒙) - cos(4𝒙)) / 𝒙 - cos(4𝒙))  ∕ 𝒙.png) 
     ◉ Rewrite the expression: limₓ→₀  (2 − cos(3𝒙) − cos(4𝒙)) / 𝒙  
          ○ Use the identity:
                   2 − cos(3𝒙) − cos(4𝒙) = (1 − cos(3𝒙)) + (1 − cos(4𝒙))  
     ◉ Split into two separate limits:  
           limₓ→₀  (1 − cos(3𝒙)) / 𝒙   +  limₓ→₀   (1 − cos(4𝒙)) / 𝒙
     ◉ Multiply and divide to match the standard form:  
           limₓ→₀  (1 − cos(3𝒙)) / (3𝒙) · 3  +  limₓ→₀  (1 − cos(4𝒙)) / (4𝒙) · 4  
     ◉ Apply the known limit: llimᵤ→₀ (1 − cos(u)) / u  = 0  
     ◉ Evaluate: 3 · 0 + 4 · 0 = 0  
     ◉ Final result:  limₓ→₀  (2 - cos(3𝒙) - cos(4𝒙)) / 𝒙   = 0

● [2:40:45]. 🧩 Evaluation of limₓ→₀  (𝒙²− 3·sin(𝒙)) / 𝒙)  ∕ 𝒙.png) 
     ◉ Rewrite the expression: limₓ→₀ (𝒙² − 3·sin(𝒙)) / 𝒙  
     ◉ Split the terms: limₓ→₀ (𝒙² / 𝒙) − 3·(sin(𝒙)/𝒙)
     ◉ Simplify each part: limₓ→₀  𝒙 − 3·(sin(𝒙)/𝒙)
     ◉ Apply limits:  
          ○ limₓ→₀ 𝒙 = 0  
          ○ limₓ→₀ sin(𝒙)/𝒙 = 1  
     ◉ Compute: 0 − 3·1 = −3  
     ◉ Final result: limₓ→₀  (𝒙² − 3·sin(𝒙))  / 𝒙  = −3

● [2:42:24]. 🧩 Evaluation of limₜ→₀  t² / (1 - cos²(t))).png) 
     ◉ Use the trigonometric identity: 1 − cos²(t) = sin²(t)
     ◉ Rewrite the limit: limₜ→₀ t² / (1 − cos²(t)) 
          ○ limₜ→₀  t² / sin²(t) 
          ○ limₜ→₀ (t / sin(t))²
     ◉ Recognize the limit structure: limₜ→₀  sin(𝑇) / 𝑇  = 1
          ○ Then: limₜ→₀ t / sin(t)  = limₜ→₀ ( sin(t) / t )⁻¹ =1⁻¹ = 1
     ◉ Apply the limit: ( limₜ→₀ (t / sin(t)) )² = (1)² = 1
     ◉ Final result: 1

● [2:50:00]. 🧩 Evaluation of limₓ→₀   𝒙 / cos(π/2 - 𝒙).png) 
     ◉ Use the co-function identity:
               cos(π/2 − 𝒙) = sin(𝒙)
          ○ 📝 NOTE:  Two angles are omplementary if they add up to 90°
                                 sin( angle )  ↔  cos( complement of angle )
     ◉ Replace the expression using the identity:
               limₓ→₀ 𝒙 / sin(𝒙) 
     ◉ Recognize the standard limit:
              limₓ→₀  𝒙 / sin(𝒙) = 1
                                                                   
● [2:53:40]. 🧩 Evaluation of  lim_(θ→0)  θ² / (1 - cos(θ))  θ² ∕ (1 - cos(θ)).png) 
     ◉ Multiply by 1 in the form of  (1 + cos(𝜃)) / (1 + cos(𝜃)) to simplify:
               lim_(𝜃→0)  𝜃²(1 + cos(𝜃))  /  (1 − cos²(𝜃))  
     ◉ Use the identity: 1 − cos²(𝜃) = sin²(𝜃)
               lim_(𝜃→0)  𝜃²(1 + cos(𝜃)) / sin²(𝜃)  
     ◉ Separate into two limits:
               lim_(𝜃→0)   𝜃² / sin²(𝜃)   ·  lim_(𝜃→0)    1 + cos(𝜃)  
     ◉ Use the identity: lim_(𝜃→0)  𝜃 / sin(𝜃)  = 1, so:
               lim_(𝜃→0)  ( 𝜃 / sin(𝜃) )² = 1² = 1
     ◉ Evaluate the limits:
              1 · (1 + cos(0)) = 1 · (1 + 1) = 2