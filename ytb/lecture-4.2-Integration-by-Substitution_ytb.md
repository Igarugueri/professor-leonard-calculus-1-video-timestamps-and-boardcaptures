-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　４．２　Iｎｔｅｇｒａｔｉｏｎ　Bｙ　Sｕｂｓｔｉｔｕｔｉｏｎ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:54]. The need for an integral to fit into the integration table.
     ◉ If the integral doesn't fit, it cannot be solved directly.
          ○ The integral must be adjusted in order to fit.
               ■ We aim to manipulate the integral through distribution, division, or trigonometric functions.
     ◉ Intro𝒅𝑢ction to u-substitution, where the letter "𝑢" is used.



Ｅｘａｍｐｌｅ　ｏｆ　ａｎ　ｉｎｔｅｇｒａｌ　ｔｈａｔ　ｃａｎｎｏｔ　ｂｅ　ｓｏｌｖｅｄ　ｄｉｒｅｃｔｌｙ　ｕｓｉｎｇ　ｂａｓｉｃ　ｍｅｔｈｏｄｓ．

● [2:14]. ∫ (𝒙² + 1)·2𝒙·𝒅𝒙
     ◉ Can not fit the integration table but you could do it by distribution.
      
● ∫ (𝒙² + 1)³·2𝒙·𝒅𝒙
     ◉ The alternative of “raising it to the third power” repeatedly is a long and complicated process,
              but you could do it by distribution.
              
● 🧩 Example –: ∫ (𝒙² + 1)⁵⁰·2𝒙·𝒅𝒙
     ◉ There is a need for a better way to solve the problem.

● [3:20]. Substitution is a method to handle complex integrals. 
     ❶ Pick “𝑢” so the integral is easier.
          ○ Usually the “inside” of some thing.
          ○ The derivative of “𝑢” must be in the ∫ (disregard constants). In this context, it means that when using
               the substitution method to solve an integral, you can disregard constant factors that appear when differentiating 𝑢.
     ❷ [6:15]. Transform: ∫ 𝒙·𝒅𝒙 → ∫ 𝑢·𝒅𝑢
          ○The integral must end up in terms of "𝑢·𝒅𝑢."
          ○ After the transformation, the integral must match something in the integration table.
          ○ If the integral does not fit in the table, either another substitution is required or it cannot be done by these methods.
          ○ There are integrals that cannot be solved with these methods.
     ❸ Do the integral.
     ❹ Translate back to "𝒙".

● [9:30].  🧩 Example (continuation) –:  ∫ (𝒙² + 1)⁵⁰·2𝒙·𝒅𝒙 – ∫ (𝒙² + 1)⁵⁰·2𝒙·𝒅𝒙.png) 
     ◉ You must choose a "u" whose derivative is present in the integral.
          ○   Constants are not very relevant in the derivative.
     ◉"u" is usually chosen as the interior part.
          ○ 𝑢 = 𝒙² + 1
     ◉The derivative of the chosen portion is calculated o both sides.
          ○ 𝒅𝑢 = 2𝒙 ⋅𝒅𝒙
     ◉ [9:26]. Verify that the derivative is in the integral. 
     ◉"𝒅𝒙" is isolated for the substitution.
          ○ 𝒅𝑢 = 2𝒙 ⋅𝒅𝒙 → 𝒅𝒙 = 𝒅𝑢 / 2𝒙
     ◉ The substitution is carried out in the original integral.
          ○ ∫ 𝑢⁵⁰ · 2𝒙 · (𝒅𝑢 / 2𝒙)
          ○ The interior portion is replaced by "𝑢".
          ○ "𝒅𝒙" is replaced by its "𝒅𝑢" equivalent.
     ◉ The integral is simplified after the substitution.
          ○ ∫ 𝑢⁵⁰  · 𝒅𝑢
     ◉ The expression is integrated in terms of "𝑢".
          ○ [The integral is calculated and the chain rule is applied.
               ■  ∫ 𝑢⁵⁰ · 𝒅𝑢  = 𝑢⁵¹ / 51 + 𝓒
          ○ It is stressed that all 𝒙 terms must vanish before integration.
          ○ You cannot integrate if both "𝒙" and "u" are present.
          ○ It is reiterated that all "𝒙" must disappear prior to integration.
     ◉ Translate back to "𝒙"
          ○ (𝑢⁵¹ / 51) + 𝓒  →  ((𝒙² + 1)⁵¹ / 51) + 𝓒



🧩Ｅｘａｍｐｌｅｓ　ｂｙ　ｓｕｂｓｔｉｔｕｔｉｏｎ    ｍｅｔｈｏｄ       

● [17:19].  ∫ 𝒙² · (𝒙³ - 4)⁵ · 𝒅𝒙⁵ · 𝒅𝒙.png) 
     ◉ 𝑢 = 𝒙³ - 4  →  𝒅𝑢 = 3𝒙² 𝒅𝒙  →   𝒅𝒙 =  𝒅𝑢 / 3𝒙²  
     ◉ ∫ 𝒙² · 𝑢⁵ · (𝒅𝑢 / 3𝒙²)  =  1/3) ∫ 𝑢⁵ 𝒅𝑢  =
     ◉ = (1/3) · (𝑢⁶ / 6) + 𝓒  
     ◉ Translate back to "𝒙": ((𝒙³ - 4)⁶) / 18 + 𝓒

● [21:13].  ∫ 𝒙²·(𝒙³ - 4)⁵·𝒅𝒙⁵·𝒅𝒙.png) 
     ◉ 𝑢 = 𝒙⁴  →  𝒅𝑢 = 4𝒙³ · 𝒅𝒙  →  𝒅𝒙 = 𝒅𝑢 / 4𝒙³  
     ◉ ∫ 2𝒙³ · sin(u) · (𝒅𝑢 / 4𝒙³)   =  (2 / 4) ∫ sin(u) · 𝒅𝑢  =
     ◉ = (1 / 2) (-cos(u)) + 𝓒  
     ◉ Translate back to "𝒙":  -(1 / 2)·cos(𝒙⁴) + 𝓒

● [27:20]. ∫ [ (1 / 𝒙²) + sec²(π·𝒙) ]· 𝒅𝒙 + sec²(π·𝒙)·𝒅𝒙.png) 
     ◉ ∫ [1/𝒙² · 𝒅𝒙  +  ∫ sec²(π𝒙)· 𝒅𝒙
     ◉  ∫ (1/𝒙²) · 𝒅𝒙 = -1/𝒙 + 𝓒
     ◉ ∫ sec²(π·𝒙) · 𝒅𝒙
          ○ 𝑢 = π·𝒙 → 𝒅𝑢 = π · 𝒅𝒙  →  𝒅𝒙 = 𝒅𝑢/π
     ◉ ∫ sec²(π·𝒙)  · 𝒅𝒙  =  (1/π) ∫ sec²(𝑢) · 𝒅𝑢 = (1/π)·tan(𝑢) +  𝓒
     ◉ Translate back to "𝒙":  -1/𝒙 + (1/π)· tan(π·𝒙) +  𝓒

● [29:00]. ∫ cos(5𝒙)· 𝒅𝒙· 𝒅𝒙.png) 
     ◉  𝑢 = 5𝒙  →  𝒅𝑢 = 5 · 𝒅𝒙  →  𝒅𝒙 = 𝒅𝑢 / 5
     ◉ ∫ cos(5𝒙) · 𝒅𝒙 = ∫ cos(𝑢)·(𝒅𝑢 / 5)
     ◉  (1/5) ∫ cos(𝑢)·𝒅𝑢 = (1/5) sin(𝑢) 
     ◉ Translate back to "𝒙":    (1/5) sin(5𝒙) + 𝓒

● [34:50].  ∫ (2𝒙 - 3)¹⁵· 𝒅𝒙 + sec²(π𝒙) · 𝒅𝒙.png) 
     ◉ 𝑢 = 2𝒙 - 3  →  𝒅𝑢 = 2·𝒅𝒙  →  𝒅𝒙 = 𝒅𝑢 / 2
     ◉ ∫ (2𝒙 - 3)¹⁵·𝒅𝒙  =  ∫ 𝑢¹⁵·(𝒅𝑢 / 2)
     ◉ (1/2) ∫ 𝑢¹⁵·𝒅𝑢 =   (1/2) (𝑢¹⁶ / 16)  =   𝑢¹⁶ / 32 
     ◉ Translate back to "𝒙":     (2𝒙 - 3)¹⁶ / 32 + 𝓒

● [36:46]. ∫ (1/𝒙²) + sec²(π𝒙) · 𝒅𝒙 + sec²(π𝒙) · 𝒅𝒙 .png) 
     ◉ ∫ [1/𝒙² + sec²(π𝒙)] · 𝒅𝒙
     ◉ ∫ (1/𝒙²) 𝒅𝒙 + ∫ sec²(π𝒙) · 𝒅𝒙
     ◉ 𝑢 = π𝒙, 𝒅𝑢 = π·𝒅𝒙, 𝒅𝒙 = 𝒅𝑢/π
     ◉ ∫ 𝒙⁻² · 𝒅𝒙 + ∫ sec²(𝑢) · (𝒅𝑢/π)
     ◉ -𝒙⁻¹ + (1/π) ∫ sec²(𝑢)·𝒅𝑢
     ◉ -𝒙⁻¹ + (1/π) tan(𝑢) + 𝓒
     ◉ Translate back to "𝒙": -𝒙⁻¹ + (1/π)·tan(π𝒙) + 𝓒

● [44:33]. ∫ sin²(𝒙)·cos(𝒙)·𝒅𝒙  (𝑢 = cos(𝒙) )·cos(𝒙)·𝒅𝒙  (𝑢 = cos(𝒙) ).png) 
     ◉ This is an example of choosing the wrong substitution (𝑢) in integration. By selecting 𝑢 = cos(𝒙), 
         the substitution complicates the integral rather than simplifying it, leading to unnecessary terms or even 
         making it unsolvable in its current form. Always aim to choose 𝑢 so that it simplifies the integral effectively, 
         often by targeting the "inner" function or a term whose derivative is present elsewhere in the expression.
     ◉ 𝑢 = cos(𝒙)  
     ◉ 𝒅𝑢 = -sin(𝒙) · 𝒅𝒙  
     ◉ 𝒅𝒙 = 𝒅𝑢 / -sin(𝒙)  
     ◉ ∫ sin²(𝒙)·𝑢·(𝒅𝑢 /-sin(𝒙))  ❌

● [47:00]. ∫ sin²(𝒙)·cos(𝒙)·𝒅𝒙·cos(𝒙)·𝒅𝒙  .png) 
     ◉ ∫ sin²(𝒙) cos(𝒙) · 𝒅𝒙 
          ○ 𝑢 = sin(𝒙),  𝒅𝑢 = cos(𝒙) · 𝒅𝒙
     ◉ ∫ 𝑢² · cos(𝒙) · (𝒅𝑢 / cos(𝒙))
     ◉ ∫ 𝑢² · 𝒅𝑢  →  (𝑢³ / 3) + 𝓒
     ◉ Translate back to "𝒙":  (sin³(𝒙) / 3) + 𝓒 

● [51:25]. ∫ (cos(√𝒙) / √𝒙) · 𝒅𝒙 ／ √𝒙) · 𝒅𝒙.png) 
     ◉ 𝑢 = √𝒙 → 𝒅𝑢 = (1/2) · 𝒙⁻¹ᐟ²· 𝒅𝒙
     ◉ 2 · 𝒅𝑢 = 𝒙⁻¹ᐟ² · 𝒅𝒙 → 2 · 𝒅𝑢 = 1/𝑢· 𝒅𝒙 → 𝒅𝒙 = 2𝑢·𝒅𝑢 because 𝑢 = √𝒙
     ◉ ∫ (cos(𝑢) / 𝑢) · 2𝑢 · 𝒅𝑢 → 2·∫ cos(𝑢)· 𝒅𝑢 = 2·sen(𝑢) + 𝓒 
     ◉Translate back to "𝒙": 2·sen(√𝒙) + 𝓒

● [1:00:00]. ∫ 𝒙⁴ (³√(3 - 5𝒙⁵)) · 𝒅𝒙) · 𝒅𝒙.png) 
     ◉ 𝑢 = 3 - 5𝒙⁵  →  𝒅𝑢 = -25𝒙⁴ · 𝒅𝒙  →  𝒅𝒙 = 𝒅𝑢 / (-25𝒙⁴)
     ◉ ∫ 𝒙⁴ (³√𝑢) · (𝒅𝑢 / -25𝒙⁴)
     ◉ (-1/25) ∫ 𝑢¹ᐟ³ · 𝒅𝑢
     ◉ (-1/25) · (𝑢⁴ᐟ³ / (4/3)) → (-1/25) · (3/4) · 𝑢⁴ᐟ³
     ◉ - (3 / 100) · 𝑢⁴ᐟ³
     ◉ Translate back to "𝒙": - (3 / 100) · (3 - 5𝒙⁵)⁴ᐟ³ + 𝓒  →  - (3 / 100) · ³√(3 - 5𝒙⁵)⁴ + 𝓒

● [1:08:40]. ∫ 𝒙² √(𝒙 - 1) · 𝒅𝒙 · 𝒅𝒙.png) 
     ◉ 𝑢 = 𝒙 - 1  →  𝒙 = 𝑢 + 1 → 𝒅𝑢 = 𝒅𝒙
     ◉  ∫ 𝒙² √𝑢 · 𝒅𝑢 
          ○ 𝒙² = (𝑢 + 1)² = 𝑢² + 2𝑢 + 1
          ○ ∫ 𝒙² √𝑢 · 𝒅𝑢  →  ∫ (𝑢² + 2𝑢 + 1) · √𝑢 · 𝒅𝑢
     ◉ ∫ (𝑢² + 2𝑢 + 1) · 𝑢¹ᐟ² · 𝒅𝑢  →  ∫ (𝑢⁵ᐟ²) + 2𝑢³ᐟ² + 𝑢¹ᐟ²) · 𝒅𝑢
     ◉ (𝑢⁷ᐟ² / (7/2))  +  2(𝑢⁵ᐟ² / (5/2))  +  (𝑢³ᐟ² / (3/2))
     ◉ (2/7)𝑢⁷ᐟ²  +  (4/5)𝑢⁵ᐟ²   +  (2/3)𝑢³ᐟ²
     ◉ Translate back to "𝒙":     (2/7)(𝒙 - 1)⁷ᐟ²  +  (4/5)(𝒙 - 1)⁵ᐟ²  +  (2/3)(𝒙 - 1)³ᐟ²  +  𝓒

● [1:17:40]. ∫ (2 - 𝒙) / √(2𝒙² - 8𝒙 + 1) · 𝒅𝒙 ／ √(2𝒙² - 8𝒙 + 1) · 𝒅𝒙.png) 
     ◉ 𝑢 = 2𝒙² - 8𝒙 + 1  →  𝒅𝑢 = (4𝒙 - 8) · 𝒅𝒙  →  𝒅𝑢 = -4(2 - 𝒙) · 𝒅𝒙  →  𝒅𝒙 =  𝒅𝑢 / -4(2 - 𝒙) 
     ◉ ∫ (2 - 𝒙) / √𝑢 · (𝒅𝑢 / -4(2 - 𝒙))
     ◉ (-1/4)·∫ (1 / √𝑢) · 𝒅𝑢
     ◉ (-1/4)·∫ 𝑢⁻¹ᐟ² · 𝒅𝑢  →  (-1/4) · (𝑢¹ᐟ² / (1/2))
     ◉ (-1/2)·𝑢¹ᐟ²
     ◉ Translate back to "𝒙": (-1/2) · √(2𝒙² - 8𝒙 + 1) + 𝓒

● [1:25:07].  ∫ cos³(𝒙) · 𝒅𝒙 · 𝒅𝒙.png) 
     ◉ ∫ cos³(𝒙) · 𝒅𝒙 → ∫ (cos²(𝒙) · cos(𝒙)) · 𝒅𝒙
     ◉ ∫ [1 - sin²(𝒙)] · cos(𝒙) · 𝒅𝒙
     ◉ ∫ [1 - (sin(𝒙))²] · cos(𝒙) · 𝒅𝒙
          ○ Pick "𝑢" so the integral is easier.
               ■ Usually the "inside" of some thing.
                    ▣ Choosing u as sin(𝒙) comes from the fact that sin(𝒙) is "inside" a more complex operation: 
                         the square (sin(𝒙))².  Furthermore,  its derivative, cos(𝒙) · 𝒅𝒙, is present in the integrand, which 
                         simplifies the substitution.
                    ▣ 𝑢 = sin(𝒙)  →  𝒅𝑢 = cos(𝒙) · 𝒅𝒙  →  𝒅𝑢 / cos(𝒙) = 𝒅𝒙
     ◉ ∫ [1 - 𝑢²]· cos(𝒙) · (𝒅𝑢 / cos(𝒙))
     ◉ ∫ [1 - 𝑢²]· 𝒅𝑢
     ◉ ∫ (1) · 𝒅𝑢 - ∫ (𝑢²) · 𝒅𝑢 → 𝑢 - (𝑢³ / 3)
     ◉ Translate back to "𝒙": sin(𝒙) - (sin³(𝒙) / 3) + 𝓒