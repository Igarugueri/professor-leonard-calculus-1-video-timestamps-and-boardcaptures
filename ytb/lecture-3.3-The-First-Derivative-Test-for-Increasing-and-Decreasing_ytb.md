-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．３　Tｈｅ　Fｉｒｓｔ　Dｅｒｉｖａｔｉｖｅ　Tｅｓｔ　Fｏｒ　Iｎｃｒｅａｓｉｎｇ　ａｎｄ　Dｅｃｒｅａｓｉｎｇ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00]. Topic: The First Derivative Test — determining intervals of increase and decrease of a function.
     ◉ Identifying where 𝒇′(𝒙) > 0 or 𝒇′(𝒙) < 0 to locate increasing and decreasing behavior.
     ◉ Application to curve sketching: analyzing the shape of a function by detecting local maxima, minima, and transitions in slope.



Ｒｅｖｉｅｗ　ｏｆ　ｐｒｅｖｉｏｕｓ　ｃｏｎｃｅｐｔｓ

● [0:55]. Review of the meaning of the first derivative and its relationship with a function’s increase and decrease. 
     ◉ [1:10]. If 𝒇'(𝒙) > 0, the function 𝒇(𝒙) is increasing.
     ◉ [2:16]. If 𝒇'(𝒙) < 0, the function 𝒇(𝒙) is decreasing.
     ◉ [2:33]. If 𝒇'(𝒙) = 0, constant, the function 𝒇(𝒙) has a horizontal tangent, and a critical number is identified.



Ｔｈｅ　ｆｉｒｓｔ　ｄｅｒｉｖａｔｉｖｅ　ｔｅｓｔ

● [3:05]. Introduction to the First Derivative Test to find relative extrema (maximums and minimums).

● [3:26]. Step-by-step explanation of the First Derivative Test: 
     ❶ [4:21]. Find the first derivative, 𝒇′(𝒙).
     ❷ [4:40]. Set the first derivative equal to zero, 𝒇′(𝒙) = 0, to find critical numbers.
          ○ In addition to the values where 𝒇′(𝒙) = 0, you must also include as **critical numbers** any point where 𝒇′(𝒙) does not exist. 
             This is because c̲r̲i̲t̲i̲c̲a̲l̲ ̲n̲u̲m̲b̲e̲r̲s̲ are defined as **any 𝒙 in the domain of 𝒇** where either  t̲h̲e̲ ̲d̲e̲r̲i̲v̲a̲t̲i̲v̲e̲ ̲ ̲i̲s̲ ̲z̲e̲r̲o̲ ̲  or th̲e̲ ̲d̲e̲r̲i̲v̲a̲t̲i̲v̲e̲ ̲i̲s̲ ̲u̲n̲d̲e̲f̲i̲n̲e̲d̲..  
             Even if the derivative does not exist at such a point, it can still correspond to a local maximum, a local minimum, or some other important change in 
             the behavior of the function.
               ■ Points where the denominator is zero (possible vertical asymptotes).
                    ▣ This occurs when the function is not defined (or tends to ±∞) as 𝒙 approaches a certain value 𝒙 = a.
                         ▢ Example: 𝒇(𝒙) = 1 / 𝒙. As 𝒙 → 0, 𝒇(𝒙) → ±∞, and the line 𝒙 = 0 is a vertical asymptote. The function does not reach a 
                             finite value at 𝒙 = 0; it simply diverges.
               ■ Sharp corners or cusps (abrupt changes in slope).
               ■ Vertical tangents (infinite slope).
                    ▣ This occurs when the function is defined at a point, but its derivative becomes infinite (or tends to ±∞).
                         ▢ Example: 𝒇(𝒙) = 𝒙¹ᐟ³ at 𝒙 = 0. The function is defined at 𝒙 = 0, but 𝒇′(𝒙) = 1 / (3𝒙²ᐟ³) tends to ±∞ as 𝒙 → 0, indicating a vertical tangent.
               ■ Discontinuities (jump, infinite, removable).
     ❸ [4:58]. Create a first derivative sign chart using the critical numbers.
          ○ Draw a number line and mark the critical points.
                                       C.N          C.N  
                  𝒇′(x)                  ∣              ∣
                               ----------∣------------∣-----------
          ○ Indicate the sign of 𝒇′(𝒙) above the number line for each interval.
     ❹ [6:16]. Test a point in each interval defined by the critical numbers.
          ○ Determine the sign of 𝒇′(𝒙) in each interval.
          ○ Substitute a sample value into 𝒇′(𝒙) to check if the slope is positive or negative.
          ○ The sign of 𝒇′(𝒙) tells whether the function is increasing or decreasing in that interval.
          ○ Local Maximum:
                     i̲f̲ 𝒇′(𝒙) changes from positive to negative at a critical number,  
                     t̲h̲e̲n̲ there is a local maximum.
          ○ Local Minimum:
                     i̲f̲ 𝒇′(𝒙) changes from negative to positive at a critical number,  
                     t̲h̲e̲n̲ there is a local minimum.
          ○ Neither Maximum nor Minimum:
                     i̲f̲ 𝒇′(𝒙) does not change sign at a critical number,  
                     t̲h̲e̲n̲ it is not classified as a maximum or minimum.
               ■ Sometimes referred to as a **horizontal inflection point**, if:
                    ▣ 𝒇′(𝒙) = 0.
                    ▣ The concavity changes (i.e., 𝒇′(𝒙) doesn't change sign, but 𝒇″(𝒙) does).
                    ▣ 🧩 Example –: 𝒇(𝒙) = 𝒙³
                         ▢ 𝒇′(𝒙) = 3𝒙² → 𝒇′(0) = 0, but stays positive on both sides of 0.
                         ▢ 𝒇″(𝒙) = 6𝒙 → changes sign at 𝒙 = 0.
                         ▢ So, 𝒙 = 0 is a critical point, not a max or min, but a **horizontal inflection point**.

● [10:44]. 🧩 Example –: Application of the first derivative test to an example 𝒇(𝒙) = 𝒙³ -3𝒙 +1 = 𝒙³ -3𝒙 +1.png) 
     ❶ Find the first derivative:
               𝒇(𝒙) = 𝒙³ − 3𝒙 + 1  ⇒ 𝒇′(𝒙) = 3𝒙² − 3
     ❷ Set the first derivative equal to zero:
               3𝒙² − 3 = 0  ⇒ 𝒙² = 1  ⇒ 𝒙 = −1 and 𝒙 = 1
              There are no points where 𝒇′(𝒙) is undefined.
              Critical numbers: 𝒙 = −1, 𝒙 = 1 (both are in the domain of the original funcction)
     ❸ Check for values that make the derivative undefined.
     ❸ Create a sign chart for 𝒇′(𝒙):
                                      -1             1
              𝒇′(𝒙)                ∣              ∣
                              --------∣------------∣--------
    ❹ Test a value from each interval in 𝒇'(𝒙) to determine the sign.  
          ○ Test values:   𝒙 = −2 → 𝒇′(𝒙) > 0
                                  𝒙 =  0 → 𝒇′(𝒙) < 0
                                  𝒙 =  2 → 𝒇′(𝒙) > 0
          ○ Sign chart:
                                    -1             1
            𝒇′(𝒙)        +      ∣      −      ∣     +
                          ----------∣------------∣--------
          ○ Apply the First Derivative Test:
               At 𝒙 = −1: 𝒇′ changes from + to − → Local Maximum
               At 𝒙 = 1:  𝒇′ changes from − to + → Local Minimum
          ○ Evaluate the function at critical points:
               𝒇(−1) = (−1)³ − 3(−1) + 1 = 3
               𝒇(1) = 1³ − 3(1) + 1 = −1
     ◉ Answer:
          ○ Local Maximum at (−1, 3)
          ○ Local Minimum at (1, −1)

● [17:12]. 🧩 Example –: Presentation of a second example to apply the first derivative test 𝒇(𝒙) = 3𝒙⁵ᐟ³ − 15𝒙²ᐟ³ = 3𝒙⁵ᐟ³ − 15𝒙²ᐟ³.png)
     ❶ Find the first derivative:  
    𝒇(𝒙) = 3𝒙⁵ᐟ³ − 15𝒙²ᐟ³  ⇒ 𝒇′(𝒙) = 5𝒙²ᐟ³ − 10𝒙⁻¹ᐟ³
     ❷ Set the first derivative equal to zero:  
    5𝒙²ᐟ³ − 10𝒙⁻¹ᐟ³ = 0  
    Multiply both sides by 𝒙¹ᐟ³:  
    5𝒙 − 10 = 0  ⇒ 𝒙 = 2  

    Check where 𝒇′(𝒙) is undefined:  
    𝒇′(𝒙) is undefined at 𝒙 = 0 (due to 𝒙⁻¹ᐟ³)

    Critical numbers: 𝒙 = 0, 𝒙 = 2 (both are in the domain of 𝒇)
   ❸ Create a sign chart for 𝒇′(𝒙):  
                  0       2  
    𝒇′(𝒙)            ∣        ∣   
           ----------∣----------------∣----------
   ❹ Test a value from each interval in 𝒇′(𝒙) to determine the sign:  
          ○ Test values:  
    𝒙 = −1  → 𝒇′(−1) = 5(-1)²ᐟ³ − 10(-1)⁻¹ᐟ³ > 0 → 𝒇′(𝒙) < 0  
    𝒙 = 1  → 𝒇′(1) = 5 − 10 < 0            → 𝒇′(𝒙) < 0  
    𝒙 = 3  → 𝒇′(3) = 5(3)²ᐟ³ − 10(3)⁻¹ᐟ³ > 0     → 𝒇′(𝒙) > 0
       ○ Sign chart:  
               0       2  
    𝒇′(𝒙)           +  ∣    −    ∣  +  
           -----------∣---------------∣----------
       ○ Apply the First Derivative Test:  
    At 𝒙 = 0: The derivative 𝒇′ is undefined due to a vertical tangent, so this point is not considered a local extremum.  
                         (This will become clearer when we study the second derivative test.)
    At 𝒙 = 2: 𝒇′ changes from − to + ⇒ Local Minimum.
       ○ Evaluate the function at critical points:  
    𝒇(0) = 3·0 − 15·0 = 0  
    𝒇(2) = 3(2)⁵ᐟ³ − 15(2)²ᐟ³ ≈ 9.52 − 23.81 ≈ −14.29
     ◉ Answer:  
          ○ Local Minimum at (2, −14.29)  
          ○ Vertical tangent (not extremum) at (0, 0)