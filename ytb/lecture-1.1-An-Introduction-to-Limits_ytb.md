----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　１．１：　ａｎ　ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｌｉｍｉｔｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00]. Introduction.

● [0:53]. The two objectives of calculus: 
     ◉ Objective 1: Find the tangent line to a curve (slope) at a given point.
     ◉ Objective 2: Find the area under a curve between two points.



Ｔｈｅ Ｐｒｏｂｌｅｍ ｏｆ ｔｈｅ Ｔａｎｇｅｎｔ

● [5:56]. Introduction to the problem of the tangent: how to find the equation of the tangent line to a curve at a given point.  
     ◉ [7:24]. The concept of the secant line is introduced as an approximation to the tangent line. 
          ○ 🕵To find the tangent line to a curve at a point: First, we need to calculate the slope of the tangent line. But…
               ■ We can'𝑦 find the slope with just one point!
               ■ So we use another nearby point on the curve, called 𝑸.
          ○ 📌 The line through the given point P and the nearby point Q:𝑷𝑸⃡, is called a secant line.
     ◉ [08:28]. Is this secant line 𝑷𝑸⃡ a good approximation of the tangent line? How could we get a better approximation?
          ○ 𝑷 is a fixed point, but 𝑸 is a movable point.
     ◉ [9:40]. It is explained how to move 𝑸 on the secant line so that it approaches the tangent line.
          ○ If we move 𝑸 closer along the curve, the approximation becomes even better.
               ■ When can we stop? Can we get as close as possible to point 𝑷?
               ■ We can’𝑦 actually reach point 𝑷, because we need two points to define a line.
               ■ The I͟D͟E͟A͟ is to move point 𝑸 so, so, so, so close to 𝑷 that the secant line becomes practically identical to the tangent line at point 𝑷.
     ◉ [13:35]. The concept of a limit is introduced: bringing one point closer to another without them being the same.
          ○ 𝑰𝙣 𝙘𝒂𝙡𝒄𝙪𝒍𝙪𝒔, 𝙩𝒘𝙤 𝙥𝒐𝙞𝒏𝙩𝒔 𝒄𝙖𝒏 𝒃𝙚 𝙞𝒏𝙛𝒊𝙣𝒊𝙩𝒆𝙨𝒊𝙢𝒂𝙡𝒍𝙮 𝙘𝒍𝙤𝒔𝙚 𝙩𝒐 𝒆𝙖𝒄𝙝 𝙤𝒕𝙝𝒆𝙧 — 𝙣𝒐𝙩 𝙚𝒙𝙖𝒄𝙩𝒍𝙮 𝙩𝒉𝙚 𝙨𝒂𝙢𝒆, 𝙗𝒖𝙩 𝙨𝒐 𝒄𝙡𝒐𝙨𝒆 𝒕𝙝𝒂𝙩 𝙩𝒉𝙚 𝙙𝒊𝙛𝒇𝙚𝒓𝙚𝒏𝙘𝒆 𝒃𝙚𝒄𝙤𝒎𝙚𝒔 𝒏𝙚𝒈𝙡𝒊𝙜𝒊𝙗𝒍𝙚. 
             𝑻𝙝𝒊𝙨 𝙞𝒔 𝒕𝙝𝒆 𝒇𝙤𝒖𝙣𝒅𝙖𝒕𝙞𝒐𝙣 𝙤𝒇 𝒕𝙝𝒆 𝒄𝙤𝒏𝙘𝒆𝙥𝒕 𝒐𝙛 𝙡𝒊𝙢𝒊𝙩𝒔.
               ■ The name “infinitesimal calculus” comes from its core idea: working with quantities that are **infinitesimally small** — values that
                  are not zero, but **so close to zero that they behave almost like it**. For example, when finding the tangent line to a curve at a point, we imagine 
                  a second point Q getting  i͟n͟f͟i͟n͟i͟te͟s͟i͟m͟a͟l͟l͟y ͟c͟l͟o͟s͟e͟ to the fixed point 𝑷. As 𝑸 approaches 𝑷, the secant line 𝑷𝑸⃡ becomes almost indistinguishable from the tangent line.
                  This process — letting the distance between two points **shrink infinitely** — is what makes calculus so powerful. It allows us to define limits, derivatives, and integrals.

● [18:40]. 🧩 Example –: Find the equation of the tangent line to the curve 𝑦 = 𝑥² at the point 𝑷(1, 1)_1.png)_2.png)  📷_3.png)
     ◉ Define a moving point 𝑸 on the curve: 𝑸(𝒙, 𝒙²).
     ◉ Recall the slope formula for a line between two points:
             m = (𝑦₂ - 𝑦₁) / (𝒙₂ - 𝒙₁)
     ◉ [23:30]. Compute the slope of the secant line between P and Q:
             m_sec = (𝒙² - 1) / (𝒙 - 1)
                          = [(𝒙 + 1)(𝒙 - 1)] / (𝒙 - 1)
                          = 𝒙 + 1   (as long as 𝒙 ≠ 1)
     ◉ ⚠ Why 𝒙 ≠ 1?
          ○ We can’𝑦 divide by zero.
          ○ This is why 𝑸 ≠ 𝑷. We use 𝑸 to approach 𝑷, not coincide.
     ◉ 📌 I͟D͟E͟A͟:  is to move point 𝑸 so, so, so, so close to 𝑷 that the secant line becomes practically identical to the tangent line at point 𝑷.
          ○ The slope of the secant line is related to the slope of the tangent line using the concept of a limit:
                     As         𝑸 → 𝑷,
                          m_sec → m_tan
          ○ I͟D͟E͟A͟: What appens to the value of m_sec as 𝒙 → 1 ,that is, as 𝑸 → 𝑷
               ■ Imagine Q getting  i͟n͟f͟i͟n͟i͟𝑦͟e͟s͟i͟m͟a͟l͟l͟𝑦͟ ͟c͟l͟o͟s͟e͟ to the fixed point 𝑷(1, 1) 
                    ▣ if 𝑸(4,𝑦) we get m_sec│₍𝒙₌₄₎ = 4 + 1 =  5
                    ▣ if 𝑸(2,𝑦) we get m_sec│₍𝒙₌₂₎ = 2 + 1 =  3
                    ▣ if 𝑸(1.5,𝑦) we get m_sec│₍𝒙₌₁.₅₎ = 1.5 + 1 = 2.5
                    ▣ . . .
                    ▣ if 𝑸(1.0000...1,𝑦) we get m_sec│₍𝒙₌₁.₀₀₀₀...₁₎ = 1.0000...1 + 1 = 2.0000...1
                    ▣ Because 𝒙 is infinitely close to 1, we can now “jump” to 1 — the secant has effectively become the tangent.
                         ▢ In͟f͟i͟n͟i͟te͟s͟i͟m͟a͟l͟l͟y ͟c͟l͟o͟s͟e͟: We are visualizing the limit as a progressive approach where there is no practical difference between being
                              infinitely close to the point and being at the point itself.
               ■ m_sec│₍𝒙₌₁₎ = 1 + 1 = 2 so as 𝒙 → 1 m_sec  → 2
                    ▣ Hence, because m_sec → m_tan, m_tan = 2
     ◉ Conclusion: the slope of the tangent line at P(1, 1) is 2.
     ◉ Find the tangent line using point-slope form:
               𝑦 - 1 = 2(𝒙 - 1) → 𝑦 = 2𝒙 - 1


 
Ｔｈｅ  Ｐｒｏｂｌｅｍ ｏｆ  ｔｈｅ  Ａｒｅａ

● [36:40]. Brief introduction to the area problem 
     ◉ The question is posed: how to find the area under a curve.
     ◉ The idea of approximating the area with rectangles is introduced.
     ◉ It is explained that by using an infinite number of rectangles, the area is calculated exactly.



 Ｄｅｆｉｎｉｔｉｏｎ ｏｆ  ａ  Ｌｉｍｉｔ

● [39:20]. The concept of a limit is defined in general terms: 
     ◉ 𝑾𝙝𝒂𝙩 𝙙𝒐𝙚𝒔 𝒕𝙝𝒆 𝒇𝙪𝒏𝙘𝒕𝙞𝒐𝙣 𝙙𝒐 𝒂𝙨 𝙖 𝙫𝒂𝙧𝒊𝙖𝒃𝙡𝒆 𝒂͟𝙥͟𝒑͟𝙧͟𝒐͟𝙖͟𝒄͟𝙝͟𝒆͟𝙨͟ 𝙖 𝙜𝒊𝙫𝒆𝙣 𝙫𝒂𝙡𝒖𝙚?
     
● [40:55]. 🧩 Example – : 𝑾𝙝𝒂𝙩 𝙙𝒐𝙚𝒔 𝒕𝙝𝒆 𝒇𝙪𝒏𝙘𝒕𝙞𝒐𝙣 𝒇(𝒙) = 𝒙² 𝙙𝒐 𝒂𝙨  𝒙 𝒂͟𝙥͟𝒑͟𝙧͟𝒐͟𝙖͟𝒄͟𝙝͟𝒆͟𝙨͟  2? = 𝒙² do as 𝒙 aproaches 2.png) 
     ◉ A table of values is constructed to approximate the limit.
         ┌───────┬─────┬─────┬──────┬───┬──────┬─────┬─────┐
         │       𝒙          │    1.5   │    1.9     │   1.99     │   2   │    2.001   │    2.1    │    2.5    │
         ├───────┼─────┼─────┼──────┼───┼──────┼─────┼─────┤
         │      𝒇(𝒙)      │   2.25   │   3.61   │  3.9601   │ ❌ │   4.004    │   4.41   │   6.25   │
         └───────┴─────┴─────┴──────┴───┴──────┴─────┴─────┘
                                                      TO THE LEFT      2   TO THE  RIGHT
                                            >>>>>>>>>>>>>>>>>>>|<<<<<<<<<<<<<<<<<<<
     ◉ It is observed that the function approaches 4 from boththe right and the left.
     
● [44:40]. The formal notation of the limit is introduced: 
     ◉ 𝑦̳h̳e̳ ̳f̳u̳n̳c̳𝑦̳i̳o̳n̳ ̳m̳u̳s̳𝑦̳ ̳a̳p̳p̳r̳o̳a̳c̳h̳ ̳𝑦̳h̳e̳ ̳s̳a̳m̳e̳ ̳v̳a̳l̳u̳e̳ ̳f̳r̳o̳m̳ ̳l̳e̳f̳𝑦̳ ̳a̳n̳d̳ ̳r̳i̳g̳h̳𝑦̳ ̳f̳o̳r̳ ̳l̳i̳m̳i̳𝑦̳ ̳𝑦̳o̳ ̳e̳𝒙̳i̳s̳𝑦̳.
     ◉ limₓ→ₐ 𝒇(𝒙) = L; limₓ→₂ 𝒙² = 4
     
● It is emphasized that the limit does not depend on the value of the function at the point, but o̲n̲ ̲i̲𝑦̲s̲ ̲b̲e̲h̲a̲v̲i̲o̲r̲ ̲n̲e̲a̲r̲ ̲𝑦̲h̲e̲ ̲p̲o̲i̲n̲𝑦̲.

● [47:14]. 🧩 Example – What are limits?: limₓ→₁ (𝒙 - 1)/(𝒙² - 1) ∕ (𝒙² - 1).png)
     ◉ Since the function has a hole at 𝒙 = 1, it is best to create a table again.
           ┌─────────┬──────┬──────┬───────┬────┬───────┬──────┬──────┐
           │           𝒙           │      0.5    │    0.99     │    0.999     │     1    │    1.001     │     1.01   │      1.5     │
           ├─────────┼──────┼──────┼───────┼────┼───────┼──────┼──────┤
           │         𝒇(𝒙)        │     0.67    │ 0.503     │    0.5002    │   ❌  │     0.499    │    0.497   │      0.4    │
           └─────────┴──────┴──────┴───────┴────┴───────┴──────┴──────┘
     ◉ limₓ→₁ (𝒙 - 1)/(𝒙² - 1) = 0.5

    

Ｏｎｅ－ｓｉｄｅｄ  Ｌｉｍｉｔｓ

● [57:30]. Introduction to one-sided limits 
     ◉ The notation for one-sided limits is explained.
          ○ right-hand limits  limₓ→ₐ⁺ 𝒇(𝒙) 
          ○ left-hand  limits  limₓ→ₐ⁻ 𝒇(𝒙)
          
● [1:00:00]. 🧩 Example –: Calculate the one-sided limits of a function represented graphically as 𝒙 approaches 2 
     ◉ It is observed that limₓ→₂⁺ 𝒇(𝒙)  = 1 and llimₓ→₂⁻ 𝒇(𝒙)  = -1.
     ◉ [1:02:32]. 𝐍𝐎𝐓𝐄: 𝑻𝙝𝒆 𝒄𝙤𝒏𝙙𝒊𝙩𝒊𝙤𝒏 𝒇𝙤𝒓 𝒕𝙝𝒆 𝒆𝙭𝒊𝙨𝒕𝙚𝒏𝙘𝒆 𝒐𝙛 𝙖 𝙡𝒊𝙢𝒊𝙩 𝙞𝒔 𝒔𝙩𝒂𝙩𝒆𝙙: 
          ○ 𝙏𝒉𝙚 𝙤𝒏𝙚-𝙨𝒊𝙙𝒆𝙙 𝙡𝒊𝙢𝒊𝙩𝒔 𝒎𝙪𝒔𝙩 𝙗𝒆 𝒆𝙦𝒖𝙖𝒍.
               ■ limₓ→ₐ⁺ 𝒇(𝒙)  = limₓ→ₐ⁻ 𝒇(𝒙)  ⇔  The limit exist
     ◉ It is concluded that limₓ→₂ 𝒇(𝒙) does not exist: D.N.E.
     
● [1:06:00]. 🧩 Example –: Calculate limₓ→₂ 𝓰(𝒙).png) 
     ◉ It is confirmed that limₓ→₂⁺ 𝓰(𝒙) = 3 and limₓ→₂⁻ 𝓰(𝒙) = 1.
     ◉ It is concluded that limₓ→₂ 𝓰(𝒙) D.N.E. because the one-sided limits are different.
     
 ● [1:10:20]. 🧩 Example –: Calculate limimₓ→₅ 𝒽(𝒙).png) 
     ◉ It is confirmed that limₓ→₅⁺ 𝒽(𝒙) = 3 and limₓ→₅⁻ 𝒽(𝒙) = 3.
     ◉ It is concluded that limₓ→₅ 𝒽(𝒙) exists and is equal to 3 because the one-sided limits are equal.



Ｉｎｆｉｎｉｔｅ  Ｌｉｍｉｔｓ  ａｎｄ  Ａｓｙｍｐｔｏｔｅｓ

 ● [1:14:12]. 🧩 Example –: Find limit of 𝒇(𝒙) = 1/𝒙  as  𝒙 → 0 = 1∕𝒙  as  𝒙 → 0.png) 
     ◉ What happens to the function 1/𝒙 as 𝒙 approaches 0.
     ◉ A table of values is constructed to approximate the one-sided limits.
       ┌────────┬──────┬────────┬─────────┬────┬─────────┬─────┬────┐
       │         𝒙          │     -0.5    │      -0.01       │       -0.001      │     0    │       0.001      │    0.01   │  0.5   │
       ├────────┼──────┼────────┼─────────┼────┼─────────┼─────┼────┤
       │        𝒇(𝒙)      │        -2     │        -100     │       -1000       │    ❌  │        1000       │    100   │     2    │
       └────────┴──────┴────────┴─────────┴────┴─────────┴─────┴────┘
     ◉ [1:17:43]. It is observed that limₓ→₀⁻ 1/𝒙 is positive infinity and limₓ→₀⁻ 1/𝒙 is negative infinity.
          ○ limₓ→₀⁻ 1/𝒙 = -∞    and    limₓ→₀⁺ 1/𝒙 = +∞
          
● [1:19:43]. The infinite limit is related to the existence of a vertical asymptote.  
     ◉  limₓ→ₐ± 𝒇(𝒙) = ±∞   ⇔   𝒗𝒆𝒓𝒕𝒊𝒄𝒂𝒍 𝒂𝒔𝒚𝒎𝒑𝒕𝒐𝒕𝒆

● [1:22:15]. 📌 The four possible cases of vertical asymptotes and their relation to infinite limits are graphically explained.  
     ◉ The behavior of the function in each case is analyzed.  
     ◉ The limit exists only when both one-sided limits tend to the same infinite value:
          ■ limₓ→ₐ⁺ 𝒇(𝒙) = +∞   and   limₓ→ₐ⁻ 𝒇(𝒙) = +∞   ⟶  vertical asymptote at 𝒙 = 𝒂  
          ■ limₓ→ₐ⁺ 𝒇(𝒙) = −∞   and   limₓ→ₐ⁻ 𝒇(𝒙) = −∞   ⟶  vertical asymptote at 𝒙 = 𝒂  
          ■ limₓ→ₐ⁺ 𝒇(𝒙) = +∞   and   limₓ→ₐ⁻ 𝒇(𝒙) = −∞   ⟶  opposite-sided divergence (no single limit)  
          ■ limₓ→ₐ⁺ 𝒇(𝒙) = −∞   and   limₓ→ₐ⁻ 𝒇(𝒙) = +∞   ⟶  opposite-sided divergence (no single limit)  
     ◉ In the first two cases, the infinite limit “exists” (in the extended sense) and defines the vertical asymptote.  
     ◉ In the last two cases, the function still has a vertical asymptote at 𝒙 = 𝒂, but the two sides diverge in opposite directions, so the limit does not exist.
 
