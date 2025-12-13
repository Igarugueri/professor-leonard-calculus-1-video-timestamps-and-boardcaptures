-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．１　Iｎｔｒｏｄｕｃｔｉｏｎ　Tｏ　Tｈｅ　Dｅｒｉｖａｔｉｖｅ　Oｆ　ａ　Fｕｎｃｔｉｏｎ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ．

● [0:00]. Reminder of the limit of the difference quotient 📷
     ◉ limₕ→₀ (𝒇(𝒙₀ + h) - 𝒇(𝒙₀)) / h
     ◉ This limit has been used to calculate the instantaneous rate of change, 
         instantaneous velocity, and the slope of a curve at a point.
     ◉ The concept of the derivative
            ○ It is defined as the 𝒔𝙡𝒐𝙥𝒆 𝒐𝙛 𝙖 𝙘𝒖𝙧𝒗𝙚 𝙖𝒕 𝒂 𝒑𝙤𝒊𝙣𝒕.
            ○ The derivative of a function at a specific point provides the slope of the curve
               at that point, which is also equivalent to the 𝙨𝙡𝙤𝙥𝙚 𝙤𝙛 𝙩𝙝𝙚 𝙩𝙖𝙣𝙜𝙚𝙣𝙩 𝙡𝙞𝙣𝙚 𝙩𝙤 𝙩𝙝𝙚 𝙘𝙪𝙧𝙫𝙚 𝙖𝙩 𝙩𝙝𝙖𝙩 𝙨𝙖𝙢𝙚 𝙥𝙤𝙞𝙣𝙩.
               
● [2:05]. The importance of understanding the meaning of the derivative 
     ◉ The slope of a curve at a point.
     
● [2:30]. The notation for the derivative 
     ◉ 𝒇'(𝒙) = limₕ→₀ (𝒇(𝒙 + h) - 𝒇(𝒙)) / h 
     ◉ Read as "the derivative of the function 𝒇 with respect to 𝒙."
     ◉ Also referred to as "𝒇 prime of 𝒙."
     
● [3:25]. The specific point 𝒙₀ is removed from the notation:
     ◉ This indicates that the general derivative function is being sought.
     


Ｅｘａｍｐｌｅｓ　ｄｅｄｉｃａｔｅｄ　ｔｏ　ｆｉｎｄｉｎｇ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ａ　ｆｕｎｃｔｉｏｎ.

● [5:33].  🧩 Example – Find the derivative of the function 𝒇(𝒙) = 2x² - 3 and the equation 
              of the tangent line at the point (2, 5). 📷 📷 
     ◉ [7:00]. The formula for what is a derivative.
            ○ 𝒇'(𝒙) = limₕ→₀ 𝒇(𝒙 + h) - 𝒇(𝒙)  / h 
     ◉ Calculate 𝒇(𝒙 + h) and 𝒇(𝒙)  for the given function:
            ○ 𝒇(𝒙 + h)  = 2(𝒙 + h)² - 3
            ○ 𝒇(𝒙) = 2𝒙² - 3
     ◉ Substitution into the formula:
            ○ 𝒇'(𝒙) = limₕ→₀ 2(𝒙 + h)² - 3 - (2𝒙² - 3)  / h 
     ◉ Process of factoring:
            ○ Expand the expression:
                 ■ 𝒇'(𝒙)  = limₕ→₀ (2(𝒙² + 2𝒙h + h²) - 3 - 2𝒙² + 3)  / h 
            ○ Simplify:
                 ■ 𝒇'(𝒙) = limₕ→₀ (4𝒙h + 2h²)  / h 
            ○ Factor out h:
                 ■ 𝒇'(𝒙) = limₕ→₀ (h (4𝒙 + 2h)) / h 
            ○ Cancel h:
                 ■  𝒇'(𝒙) = limₕ→₀ 4𝒙 + 2h 
     ◉ Limit calculation:
            ○ As h approaches zero, 𝒇'(𝒙) = 4x is obtained.
     ◉ **Use of the derivative**
            ○ How to find the slope of the curve at any point.
                  ■ By applying the derivative to the given point 𝒙 = 2  from (2, 5)
                       ▣  m = 𝒇'(2) = 4 × 2 = 8
     ◉[12:54]. Use the point-slope form:
            ○ 𝒚 - 𝒚₁ = m (𝒙 - 𝒙₁)
            ○ Substitute the point (2, 5) and slope (8):
                 ■ 𝒚 - 5 = 8 (𝒙 - 2)
            ○ Expand:
                 ■ 𝒚 - 5 = 8𝒙 - 16
                 ■ 𝒚 = 8𝒙 - 11
            ○ Final answer:
                 ■ Equation of the tangent line: 𝒚 = 8𝒙 - 11 

● [16:00]. 🧩 Example – Find the derivative of the function 𝒇(𝒙) = 2x³ - x.  📷 📷
     ◉[17:10]. The formula for what is a derivative.
          ○ 𝒇'(𝒙) = limₕ→₀ (𝒇(𝒙 + h) - 𝒇(𝒙))  / h 
     ◉ Calculate 𝒇(𝒙 + h) and 𝒇(𝒙) for the given function:
          ○ 𝒇(𝒙 + h) = 2(𝒙 + h)³ - (𝒙 + h)
          ○ 𝒇(𝒙) = 2𝒙³ - 𝒙
     ◉ Substitution into the formula:
          ○ 𝒇'(𝒙) = limₕ→₀ 2(𝒙 + h)³ - (𝒙 + h) - (2𝒙³ - 𝒙) / h 
     ◉ Process of factoring:
          ○ Expand the expression:
               ■ 𝒇'(𝒙) = limₕ→₀ (2(𝒙³ + 3𝒙²h + 3𝒙h² + h³) - (𝒙 + h) - 2𝒙³ + 𝒙) ) / h 
          ○ Simplify:
               ■ 𝒇'(𝒙) = limₕ→₀ (2𝒙³ + 6𝒙²h + 6𝒙h² + 2h³ - 𝒙 - h - 2𝒙³ + 𝒙)  / h 
          ○ Combine like terms:
               ■ 𝒇'(𝒙) = limₕ→₀ (6𝒙²h + 6𝒙h² + 2h³ - h)  / h 
          ○ Factor out h:
               ■ 𝒇'(𝒙) = limₕ→₀ (h (6𝒙² + 6𝒙h + 2h² - 1))/ h 
          ○ Cancel h:
               ■ 𝒇'(𝒙) = limₕ→₀ 6𝒙² + 6𝒙h + 2h² - 1 
     ◉ Limit calculation:
          ○ As h approaches zero:
               ■ 𝒇'(𝒙) = 6𝒙² - 1
     ◉ **Use of the derivative**
          ○ How to find the slope of the curve at any point.
               ■ By applying the derivative to the given point 𝒙 = 3:
                    ▣ m = 𝒇'(3) = 6(3)² - 1  = 53

● [27:30]. 🧩 Example – Find the derivative of the function 𝒇(𝒙) = 3x + 2. 📷
     ◉ Explanation of linear functions:
          ○ The slope is constant, so the derivative is the coefficient of x (in this case, 3).
     ◉ [29:10]. Generalization:
          ○ For any linear function of the form y = mx + b, the derivative is always m.

● [31:10].🧩 Example – Find the derivative of the function 𝒇(𝒙) = √x and the equation of the tangent line at x = 4. 📷 📷
     ◉ Use of the The formula for what is a derivative:
          ○ 𝒇'(𝒙) = limₕ→₀ (𝒇(𝒙 + h) - 𝒇(𝒙)) / h 
          ○ Necessary because it is not a linear function.
     ◉ [32:25]. Importance of finding the general derivative function:
          ○ Before evaluating at a specific point.
     ◉ Calculate 𝒇(𝒙 + h) and 𝒇(𝒙) for the given function:
          ○ 𝒇(𝒙 + h) = √(𝒙 + h)
          ○ 𝒇(𝒙) = √𝒙
     ◉ Substitution into the formula:
          ○ 𝒇'(𝒙) = limₕ→₀ (√(𝒙 + h) - √𝒙) / h 
     ◉ Process of factoring:
          ○ Multiply and divide by the conjugate to rationalize the numerator:
                ■ 𝒇'(𝒙) = limₕ→₀ (√(𝒙 + h) - √𝒙) * (√(𝒙 + h) + √𝒙) / (h * (√(𝒙 + h) + √𝒙)) 
          ○ Expand the numerator using the difference of squares:
               ■ 𝒇'(𝒙) = limₕ→₀ (𝒙 + h) - 𝒙 / h * (√(𝒙 + h) + √𝒙) 
          ○ Simplify:
               ■ 𝒇'(𝒙) = limₕ→₀ h / h * (√(𝒙 + h) + √𝒙) 
          ○ Cancel h:
               ■ 𝒇'(𝒙) = limₕ→₀ 1 / (√(𝒙 + h) + √𝒙) 
    ◉ Limit calculation:
         ○ As h approaches zero:
              ■ 𝒇'(𝒙) = 1 / (2√𝒙)
    ◉ **Use of the derivative**
         ○ How to find the slope of the curve at the point 𝒙 = 4:
              ■ m = 𝒇'(4) = 1 / (2√4) = 1/4
    ◉ [37:13]. Explanation to find the equation of the tangent line. Application of the point-slope method.
         ○ Find the value of the function at the point:
              ■ 𝒇(4) = √4 = 2
         ○ Point: (4, 2)
         ○ 𝒚 - 𝒚₁ = m (𝒙 - 𝒙₁)
         ○ Substitute the point (4, 2) and slope (1/4):
              ■ 𝒚 - 2 = (1/4)(𝒙 - 4)
         ○ Expand:
              ■ 𝒚 - 2 = (1/4)𝒙 - 1
              ■ 𝒚 = (1/4)𝒙 + 1
         ○ Final answer:
              ■ Equation of the tangent line: 𝒚 = (1/4)𝒙 + 1

     
     
Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｏｆ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｉｎｓｔａｎｔａｎｅｏｕｓ　ｖｅｌｏｃｉｔｙ　ａｓ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ｔｈｅ　ｐｏｓｉｔｉｏｎ　ｆｕｎｃｔｉｏn.

● [41:00].  Definition of instantaneous velocity:  📷
     ◉ v_inst. = limₕ→₀ (𝒇(t + h) - 𝒇(t)) / h 
           ○ v_inst. = v(t) = 𝒇'(t)
           ○ **Instantanious velocity is the first derivative of a position curve**
     ◉ Relationship between instantaneous velocity and the derivative:
           ○ v(t) = s'(t), where s(t) is the psition function.
           ○ v(t) = limₕ→₀ (s(t + 𝒉) - s(t)) / 𝒉 

● [42:45]. 🧩 Example –  The position function s(t) = 1250 - 16t² is provided for an object falling from the Empire State Building.
     ◉ [43:14]. Three questions are posed:  📷
          ○ 1. Find the formula for instantaneous velocity v(t). 📷
                ■ [47:20]. The first question is solved: find v(t).
                     ▣ Formula for instantaneous velocity:
                           ▢ v(t) = s'(t) = limₕ→₀ s(t + h) - s(t) / h 
                     ▣ Step 1: Define the functions:
                           ▢ s(t + h) = 1250 - 16(t + h)²
                           ▢ s(t) = 1250 - 16t²
                     ▣ Step 2: Substitution into the formula:
                           ▢ v(t) = limₕ→₀ (1250 - 16(t + h)² - (1250 - 16t²)) / h 
                     ▣ Step 3: Expand the square:
                           ▢ v(t) = limₕ→₀ (1250 - 16(t² + 2th + h²) - 1250 + 16t² ) / h 
                     ▣ Step 4: Simplify the expression:
                           ▢ v(t) = limₕ→₀ (1250 - 16t² - 32th - 16h² - 1250 + 16t²) / h 
                     ▣ Step 5: Cancel out common terms:
                           ▢ v(t) = limₕ→₀ -32th - 16h² / h 
                     ▣ Step 6: Factor out h:
                           ▢ v(t) = limₕ→₀ h(-32t - 16h) / h 
                     ▣ Step 7: Cancel h:
                           ▢ v(t) = limₕ→₀ -32t - 16h 
                     ▣ Step 8: Apply the limit as h → 0:
                           ▢ v(t) = -32t
                     ▣ Final answer:
                           ▢ The instantaneous velocity v(t) = -32t.
          ○ 2. Determine when the object hits the ground. 📷
                ■ [51:16]. The second question is solved: determine when the object hits the ground.
                      ▣ The equation 1250 - 16t² = 0 is posed to find the time when the height is zero.
                      ▣ It is solved from the equation, obtaining t = √(1250/16).
                           ▢ It is calculated, obtaining t ≈ 8.84 seconds.
          ○ 3. Calculate the velocity of the object upon impact.  📷
                ■ [54:29]. The third question is solved: calculate the velocity of the object upon impact.
                      ▣ t = 8.84 seconds is substituted into the formula for instantaneous velocity v(t) = -32t.
                      ▣ The velocity is calculated, obtaining v(8.84) ≈ -282.88 feet per second.


Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｄｉｆｆｅｒｅｎｔｉａｂｉｌｉｔｙ.

● [57:00].  A function's ability to have a derivative at a point. 
  
● [57:36]. It is explained that for a function to be differentiable at a point, the limit of the difference 
              quotient must exist at that point.
     ◉ 𝒇'(𝒙) = limₕ→₀ (𝒇(𝒙 + h) - 𝒇(𝒙)) / h  must exist

● [58:40]. Relationship between differentiability and limits:
     ◉ Differentiability exists if the limit of the difference quotient exists.
           ○ The existence of the limit is connected with continuity and the equality of the one-sided limits.
           
● [59:20]. **Two implications of differentiability:** 📷
     ◉ [59:40]. ① ᴛʜᴇ ᴅᴇʀɪᴠᴀᴛɪᴠᴇ ᴄᴀɴɴᴏᴛ ʙᴇ ᴛᴀᴋᴇɴ ᴀᴛ ᴀ ꜱʜᴀʀᴩ ᴩᴏɪɴᴛ 𝑎.
           ○ The slope from the left                      ≠             The slope from the right
                                                  𝒇'⁻(𝑎)              ≠             𝒇'⁺(𝑎)
              limₕ→₀⁻ 𝒇(𝑎 + h) - 𝒇(𝑎) / h       ≠           limₕ→₀⁺  (𝒇(𝑎 + h) - 𝒇(𝑎)) / h 
           ○ The slope of the function exist but the limit of our slop doesn't exist
                 ■ lim_(𝒙 → 𝑎) 𝒇(𝒙))  exits
                 ■ limₕ→₀ (𝒇(𝑎 + h) - 𝒇(𝑎)) / h  doesn't exist
     ◉ [1:03:16]. ② ᴛʜᴇ ᴅᴇʀɪᴠᴀᴛɪᴠᴇ ᴄᴀɴɴᴏᴛ ʙᴇ ᴛᴀᴋᴇɴ ᴀᴛ ᴀ ᴩᴏɪɴᴛ ᴡʜᴇʀᴇ ᴛʜᴇ ꜱʟᴏᴩᴇ ɪꜱ ᴠᴇʀᴛɪᴄᴀʟ (ᴜɴᴅᴇꜰɪɴᴇᴅ).
           ○ It is explained that the limit of the derivative at a point with a vertical slope does not
              exist because the one-sided limits tend to positive and negative infinity, respectively.

● [1:04:45]. 🧩 Example – The differentiability of the absolute value function 𝒇(𝒙) = |x| is analyzed. 📷
     ◉ It is observed that the function has a sharp point at x = 0.
     ◉ It is explained that the function is not differentiable at x = 0 because the slopes of the 
         one-sided limits are different (-1 and 1).
     ◉ It is clarified that the function is differentiable at all other points.

● [1:07:47].**Relationship between continuity and differentiability** 📷
    ◉ A graph is used to illustrate a function discontinuous **at a point.**
         ○ It is concluded that  **ɪꜰ ᴀ ꜰᴜɴᴄᴛɪᴏɴ ɪꜱ ɴᴏᴛ ᴄᴏɴᴛɪɴᴜᴏᴜꜱ ᴀᴛ ᴀ ᴩᴏɪɴᴛ, ɪᴛ ɪꜱ ɴᴏᴛ ᴅɪꜰꜰᴇʀᴇɴᴛɪᴀʙʟᴇ ᴀᴛ ᴛʜᴀᴛ ᴩᴏɪɴᴛ.**
                ■ limₓ→ₐ 𝒇(𝒙) ≠ 𝒇(a)  ⇒  𝒇′(a) does not exist
    ◉ [1:09:00]. A graph is used to illustrate a function continuous at a point but not differentiable at that point (a sharp point).
         ○ It is concluded that **ᴄᴏɴᴛɪɴᴜɪᴛy ᴅᴏᴇꜱ ɴᴏᴛ ɪᴍᴩʟy ᴅɪꜰꜰᴇʀᴇɴᴛɪᴀʙɪʟɪᴛy.**
                ■ limₓ→ₐ 𝒇(𝒙) = 𝒇(a)   ⇏  𝒇 ′(a)
         ○ It is established that  **ᴅɪꜰꜰᴇʀᴇɴᴛɪᴀʙɪʟɪᴛy ɪᴍᴩʟɪᴇꜱ ᴄᴏɴᴛɪɴᴜɪᴛy.**
                ■ 𝒇 ′(a) exist  ⇒ limₓ→ₐ 𝒇(𝒙) = 𝒇(a)
    ◉ It is reiterated that differentiability is a stronger condition than continuity.
         ○ Differentiability   ⇒  Continuity
      ○ Continuity           ⇏  Differentiability

● [1:11:28]. The different notations for the derivative are reviewed.  📷
    ◉ Prime notation: 𝒇'(𝒙)
    ◉ Leibniz notation: d/dx [𝒇(𝒙)]
    ◉ Prime notation for functions with variable 𝒚: 𝒚'
    ◉ Leibniz notation for functions with variable 𝒚: d𝒚/d𝒙

● [1:13:24]. It is explained how to evaluate derivatives at specific points.  📷
    ◉ Notation to evaluate the derivative of 𝒇 at point a: 𝒇'(𝑎)
    ◉ Alternative notation to evaluate the derivative of 𝒇 at point a: d/d𝒙 [𝒇(𝒙)] |_(𝒙 = 𝑎)
    ◉ Notation to evaluate the derivative of 𝒚 at point a: 𝒚'(𝑎)
    ◉ Alternative notation to evaluate the derivative of 𝒚 at point a: d𝒚/d𝒙 |_(𝒙 = 𝑎)