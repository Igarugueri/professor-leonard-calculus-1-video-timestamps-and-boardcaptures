-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．１　Iｎｔｒｏｄｕｃｔｉｏｎ　Tｏ　Tｈｅ　Dｅｒｉｖａｔｉｖｅ　Oｆ　ａ　Fｕｎｃｔｉｏｎ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ．

● [0:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=0). Reminder of the limit of the difference quotient 📷[Image](../img/Calculus 1 Lecture 2.1/[0-00]-01.png)
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{h\to 0}\dfrac{𝒇(𝒙_{0}+h)-𝒇(𝒙_{0})}{h}$
     $\rule{0pt}{}$
     ◉ This limit has been used to calculate the instantaneous rate of change, 
         instantaneous velocity, and the slope of a curve at a point.
     ◉ The concept of the derivative
            ○ It is defined as the 𝒔𝙡𝒐𝙥𝒆 𝒐𝙛 𝙖 𝙘𝒖𝙧𝒗𝙚 𝙖𝒕 𝒂 𝒑𝙤𝒊𝙣𝒕.
            ○ The derivative of a function at a specific point provides the slope of the curve
               at that point, which is also equivalent to the 𝙨𝙡𝙤𝙥𝙚 𝙤𝙛 𝙩𝙝𝙚 𝙩𝙖𝙣𝙜𝙚𝙣𝙩 𝙡𝙞𝙣𝙚 𝙩𝙤 𝙩𝙝𝙚 𝙘𝙪𝙧𝙫𝙚 𝙖𝙩 𝙩𝙝𝙖𝙩 𝙨𝙖𝙢𝙚 𝙥𝙤𝙞𝙣𝙩.

               
● [2:05](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=125). The importance of understanding the meaning of the derivative 
     ◉ The slope of a curve at a point.

     
● [2:30](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=150). The notation for the derivative 
$\rule{0pt}{}$
     ◉ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
     $\rule{0pt}{}$
     ◉ Read as "the derivative of the function 𝒇 with respect to 𝒙."
     ◉ Also referred to as "𝒇 prime of 𝒙."

     
● [3:25](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=205). The specific point 𝒙₀ is removed from the notation:
     ◉ This indicates that the general derivative function is being sought.
     



Ｅｘａｍｐｌｅｓ　ｄｅｄｉｃａｔｅｄ　ｔｏ　ｆｉｎｄｉｎｇ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ａ　ｆｕｎｃｔｉｏｎ.

● [5:33](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=333).  🧩 Example – Find the derivative of the function $𝒇(𝒙)=2x^{2}-3$ and the equation 
              of the tangent line at the point $(2,5)$. 📷[Image-1](../img/Calculus 1 Lecture 2.1/[5-33]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 2.1/[5-33]-02.png) 
     ◉ [7:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=420). The formula for what is a derivative.
     $\rule{0pt}{}$
            ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
            $\rule{0pt}{}$
     ◉ Calculate $𝒇(𝒙+h)$ and $𝒇(𝒙)$  for the given function:
     $\rule{0pt}{}$
            ○ $𝒇(𝒙+h)=2(𝒙+h)^{2}-3$
            ○ $𝒇(𝒙)=2𝒙^{2}-3$
     ◉ Substitution into the formula:
     $\rule{0pt}{}$
            ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{2(𝒙+h)^{2}-3-\big(2𝒙^{2}-3\big)}{h}$
            $\rule{0pt}{}$
     ◉ Process of factoring:
            ○ Expand the expression:
            $\rule{0pt}{}$
                 ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{2(𝒙^{2}+2𝒙 h+h^{2})-3-2𝒙^{2}+3}{h}$
                 $\rule{0pt}{}$
            ○ Simplify:
            $\rule{0pt}{}$
                 ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{4𝒙 h+2h^{2}}{h}$
                 $\rule{0pt}{}$
            ○ Factor out $h$:
            $\rule{0pt}{}$
                 ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{h\,(4𝒙+2h)}{h}$
                 $\rule{0pt}{}$
            ○ Cancel $h$:
            $\rule{0pt}{}$
                 ■  $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\big(4𝒙+2h\big)$
                 $\rule{0pt}{}$
     ◉ Limit calculation:
            ○ As $h$ approaches zero, $𝒇'(𝒙)=4x$ is obtained.
     ◉ **Use of the derivative**
            ○ How to find the slope of the curve at any point.
                  ■ By applying the derivative to the given point $𝒙=2$  from $(2,5)$
                       ▣  $m=𝒇'(2)=4\cdot 2=8$
     ◉[12:54](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=774). Use the point-slope form:
            ○ $𝒚-𝒚_{1}=m(𝒙-𝒙_{1})$
            ○ Substitute the point $(2,5)$ and slope $(8)$:
                 ■ $𝒚-5=8(𝒙-2)$
            ○ Expand:
                 ■ $𝒚-5=8𝒙-16$
                 ■ $𝒚=8𝒙-11$
            ○ Final answer:
                 ■ Equation of the tangent line: $𝒚=8𝒙-11$ 


● [16:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=960). 🧩 Example – Find the derivative of the function $𝒇(𝒙)=2x^{3}-x$.  📷[Image-1](../img/Calculus 1 Lecture 2.1/[16-00]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 2.1/[16-00]-02.png)
     ◉[17:10](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=1030). The formula for what is a derivative.
     $\rule{0pt}{}$
          ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
          $\rule{0pt}{}$
     ◉ Calculate $𝒇(𝒙+h)$ and $𝒇(𝒙)$ for the given function:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙+h)=2(𝒙+h)^{3}-(𝒙+h)$
          ○ $𝒇(𝒙)=2𝒙^{3}-𝒙$
     ◉ Substitution into the formula:
     $\rule{0pt}{}$
          ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{2(𝒙+h)^{3}-(𝒙+h)-\big(2𝒙^{3}-𝒙\big)}{h}$
          $\rule{0pt}{}$
     ◉ Process of factoring:
          ○ Expand the expression:
          $\rule{0pt}{}$
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{2\big(𝒙^{3}+3𝒙^{2}h+3𝒙 h^{2}+h^{3}\big)-(𝒙+h)-2𝒙^{3}+𝒙}{h}$
               $\rule{0pt}{}$
          ○ Simplify:
          $\rule{0pt}{}$
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{2𝒙^{3}+6𝒙^{2}h+6𝒙 h^{2}+2h^{3}-𝒙-h-2𝒙^{3}+𝒙}{h}$
               $\rule{0pt}{}$
          ○ Combine like terms:
          $\rule{0pt}{}$
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{6𝒙^{2}h+6𝒙 h^{2}+2h^{3}-h}{h}$
               $\rule{0pt}{}$
          ○ Factor out $h$:
          $\rule{0pt}{}$
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{h\,(6𝒙^{2}+6𝒙 h+2h^{2}-1)}{h}$
               $\rule{0pt}{}$
          ○ Cancel $h$:
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\big(6𝒙^{2}+6𝒙 h+2h^{2}-1\big)$
               $\rule{0pt}{}$
     ◉ Limit calculation:
          ○ As $h$ approaches zero:
               ■ $𝒇'(𝒙)=6𝒙^{2}-1$
     ◉ **Use of the derivative**
          ○ How to find the slope of the curve at any point.
               ■ By applying the derivative to the given point $𝒙=3$:
                    ▣ $m=𝒇'(3)=6(3)^{2}-1=53$


● [27:30](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=1650). 🧩 Example – Find the derivative of the function $𝒇(𝒙)=3x+2$. 📷[Image](../img/Calculus 1 Lecture 2.1/[27-30]-01.png)
     ◉ Explanation of linear functions:
          ○ The slope is constant, so the derivative is the coefficient of $x$ (in this case, $3$).
     ◉ [29:10](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=1750). Generalization:
          ○ For any linear function of the form $y=mx+b$, the derivative is always $m$.


● [31:10](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=1870).🧩 Example – Find the derivative of the function $𝒇(𝒙)=\sqrt{x}$ and the equation of the tangent line at $x=4$. 📷[Image-1](../img/Calculus 1 Lecture 2.1/[31-10]-01.png) 📷[Image-2](../img/Calculus 1 Lecture 2.1/[31-10]-02.png)
     ◉ Use of the The formula for what is a derivative:
     $\rule{0pt}{}$
          ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
          $\rule{0pt}{}$
          ○ Necessary because it is not a linear function.
     ◉ [32:25](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=1945). Importance of finding the general derivative function:
          ○ Before evaluating at a specific point.
     ◉ Calculate $𝒇(𝒙+h)$ and $𝒇(𝒙)$ for the given function:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙+h)=\sqrt{𝒙+h}$
          ○ $𝒇(𝒙)=\sqrt{𝒙}$
     ◉ Substitution into the formula:
     $\rule{0pt}{}$
          ○ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{\sqrt{𝒙+h}-\sqrt{𝒙}}{h}$
          $\rule{0pt}{}$
     ◉ Process of factoring:
          ○ Multiply and divide by the conjugate to rationalize the numerator:
          $\rule{0pt}{}$
                ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{\big(\sqrt{𝒙+h}-\sqrt{𝒙}\big)\big(\sqrt{𝒙+h}+\sqrt{𝒙}\big)}{\,h\big(\sqrt{𝒙+h}+\sqrt{𝒙}\big)}$
                $\rule{0pt}{}$
          ○ Expand the numerator using the difference of squares:
          $\rule{0pt}{}$
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{(𝒙+h)-𝒙}{\,h\big(\sqrt{𝒙+h}+\sqrt{𝒙}\big)}$
               $\rule{0pt}{}$
          ○ Simplify:
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{h}{\,h\big(\sqrt{𝒙+h}+\sqrt{𝒙}\big)}$
               $\rule{0pt}{}$
          ○ Cancel $h$:
               ■ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{1}{\sqrt{𝒙+h}+\sqrt{𝒙}}$
               $\rule{0pt}{}$
    ◉ Limit calculation:
         ○ As $h$ approaches zero:
         $\rule{0pt}{}$
              ■ $\displaystyle 𝒇'(𝒙)=\dfrac{1}{2\sqrt{𝒙}}$
              $\rule{0pt}{}$
    ◉ **Use of the derivative**
         ○ How to find the slope of the curve at the point $𝒙=4$:
         $\rule{0pt}{}$
              ■ $m=𝒇'(4)=\dfrac{1}{2\sqrt{4}}=\dfrac{1}{4}$
              $\rule{0pt}{}$
    ◉ [37:13](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=2233). Explanation to find the equation of the tangent line. Application of the point-slope method.
         ○ Find the value of the function at the point:
              ■ $𝒇(4)=\sqrt{4}=2$
         ○ Point: $(4,2)$
         ○ $𝒚-𝒚_{1}=m(𝒙-𝒙_{1})$
         ○ Substitute the point $(4,2)$ and slope $\big(\dfrac{1}{4}\big)$:
              ■ $𝒚-2=\dfrac{1}{4}(𝒙-4)$
              $\rule{0pt}{}$
         ○ Expand:
              ■ $𝒚-2=\dfrac{1}{4}𝒙-1$
              $\rule{0pt}{}$
              ■ $𝒚=\dfrac{1}{4}𝒙+1$
         ○ Final answer:
              ■ Equation of the tangent line: $𝒚=\dfrac{1}{4}𝒙+1$

     

     
Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｏｆ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｉｎｓｔａｎｔａｎｅｏｕｓ　ｖｅｌｏｃｉｔｙ　ａｓ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ｔｈｅ　ｐｏｓｉｔｉｏｎ　ｆｕｎｃｔｉｏn.

● [41:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=2460).  Definition of instantaneous velocity:  📷[Image](../img/Calculus 1 Lecture 2.1/[41-00]-01.png)
$\rule{0pt}{}$
     ◉ $\displaystyle v_{\text{inst.}}=\lim_{h\to 0}\dfrac{𝒇(t+h)-𝒇(t)}{h}$
     $\rule{0pt}{}$
     ◉  $v_{\text{inst.}}=v(t)=𝒇'(t)$
     ◉ **Instantanious velocity is the first derivative of a position curve**
     ◉ Relationship between instantaneous velocity and the derivative:
           ○ $v(t)=s'(t)$, where $s(t)$ is the psition function.
           $\rule{0pt}{}$
           ○ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{s(t+h)-s(t)}{h}$


● [42:45](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=2565). 🧩 Example –  The position function $s(t)=1250-16t^{2}$ is provided for an object falling from the Empire State Building.
     ◉ [43:14](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=2594). Three questions are posed:  📷[Image-1](../img/Calculus 1 Lecture 2.1/[42-45]-01.png)
          ○ 1. Find the formula for instantaneous velocity $v(t)$. 📷[Image-2](../img/Calculus 1 Lecture 2.1/[42-45]-02.png)
                ■ [47:20](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=2840). The first question is solved: find $v(t)$.
                     ▣ Formula for instantaneous velocity:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=s'(t)=\lim_{h\to 0}\dfrac{s(t+h)-s(t)}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 1: Define the functions:
                           ▢ $s(t+h)=1250-16(t+h)^{2}$
                           ▢ $s(t)=1250-16t^{2}$
                     ▣ Step 2: Substitution into the formula:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{1250-16(t+h)^{2}-\big(1250-16t^{2}\big)}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 3: Expand the square:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{1250-16\big(t^{2}+2t h+h^{2}\big)-1250+16t^{2}}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 4: Simplify the expression:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{1250-16t^{2}-32t h-16h^{2}-1250+16t^{2}}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 5: Cancel out common terms:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{-32t h-16h^{2}}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 6: Factor out $h$:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\dfrac{h(-32t-16h)}{h}$
                           $\rule{0pt}{}$
                     ▣ Step 7: Cancel $h$:
                     $\rule{0pt}{}$
                           ▢ $\displaystyle v(t)=\lim_{h\to 0}\big(-32t-16h\big)$
                           $\rule{0pt}{}$
                     ▣ Step 8: Apply the limit as $h\to 0$:
                           ▢ $v(t)=-32t$
                     ▣ Final answer:
                           ▢ The instantaneous velocity $v(t)=-32t$.
          ○ 2. Determine when the object hits the ground. 📷[Image-3](../img/Calculus 1 Lecture 2.1/[42-45]-03.png)
                ■ [51:16](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3076). The second question is solved: determine when the object hits the ground.
                      ▣ The equation $1250-16t^{2}=0$ is posed to find the time when the height is zero.
                      $\rule{0pt}{}$
                      ▣ It is solved from the equation, obtaining $t=\sqrt{\dfrac{1250}{16}}$.
                      $\rule{0pt}{}$
                      ▣ It is calculated, obtaining $t\approx 8.84$ seconds.
          ○ 3. Calculate the velocity of the object upon impact.  📷[Image-4](../img/Calculus 1 Lecture 2.1/[42-45]-03.png)
                ■ [54:29](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3269). The third question is solved: calculate the velocity of the object upon impact.
                      ▣ $t=8.84$ seconds is substituted into the formula for instantaneous velocity $v(t)=-32t$.
                      ▣ The velocity is calculated, obtaining $v(8.84)\approx -282.88$ feet per second.




Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｄｉｆｆｅｒｅｎｔｉａｂｉｌｉｔｙ.

● [57:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3420).  A function's ability to have a derivative at a point. 

  
● [57:36](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3456). It is explained that for a function to be differentiable at a point, the limit of the difference 
              quotient must exist at that point.
              $\rule{0pt}{}$
     ◉ $\displaystyle 𝒇'(𝒙)=\lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$ must exist


● [58:40](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3520). Relationship between differentiability and limits:
     ◉ Differentiability exists if the limit of the difference quotient exists.
           ○ The existence of the limit is connected with continuity and the equality of the one-sided limits.

           
● [59:20](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3560). **Two implications of differentiability:** 📷[Image](../img/Calculus 1 Lecture 2.1/[57-00]-01.png)
     ◉ [59:40](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3580). ① ᴛʜᴇ ᴅᴇʀɪᴠᴀᴛɪᴠᴇ ᴄᴀɴɴᴏᴛ ʙᴇ ᴛᴀᴋᴇɴ ᴀᴛ ᴀ ꜱʜᴀʀᴩ ᴩᴏɪɴᴛ 𝑎.
     $\rule{0pt}{}$
           ○ The slope from the left    ≠    The slope from the right
                              $𝒇'^{-}(𝑎)$             ≠             $𝒇'^{+}(𝑎)$
                                                  $\rule{0pt}{}$
              $\displaystyle \lim_{h\to 0^{-}}\dfrac{𝒇(𝑎+h)-𝒇(𝑎)}{h}\;\neq\;\lim_{h\to 0^{+}}\dfrac{𝒇(𝑎+h)-𝒇(𝑎)}{h}$
                                   $\rule{0pt}{}$
           ○ The slope of the function exist but the limit of our slop doesn't exist
           $\rule{0pt}{}$
                 ■ $\displaystyle \lim_{𝒙\to 𝑎}𝒇(𝒙)$ exits
                 $\rule{0pt}{}$
                 ■ $\displaystyle \lim_{h\to 0}\dfrac{𝒇(𝑎+h)-𝒇(𝑎)}{h}$ doesn't exist
                 $\rule{0pt}{}$
     ◉ [1:03:16](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3796). ② ᴛʜᴇ ᴅᴇʀɪᴠᴀᴛɪᴠᴇ ᴄᴀɴɴᴏᴛ ʙᴇ ᴛᴀᴋᴇɴ ᴀᴛ ᴀ ᴩᴏɪɴᴛ ᴡʜᴇʀᴇ ᴛʜᴇ ꜱʟᴏᴩᴇ ɪꜱ ᴠᴇʀᴛɪᴄᴀʟ (ᴜɴᴅᴇꜰɪɴᴇᴅ).
           ○ It is explained that the limit of the derivative at a point with a vertical slope does not
              exist because the one-sided limits tend to positive and negative infinity, respectively.


● [1:04:45](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=3885). 🧩 Example – The differentiability of the absolute value function $𝒇(𝒙)=|x|$ is analyzed. 📷[Image](../img/Calculus 1 Lecture 2.1/[1-04-45]-01.png)
     ◉ It is observed that the function has a sharp point at $x=0$.
     ◉ It is explained that the function is not differentiable at $x=0$ because the slopes of the 
         one-sided limits are different ($-1$ and $1$).
     ◉ It is clarified that the function is differentiable at all other points.


● [1:07:47](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=4067).**Relationship between continuity and differentiability** 📷[Image](../img/Calculus 1 Lecture 2.1/[7-07-47]-01.png)
    ◉ A graph is used to illustrate a function discontinuous **at a point.**
         ○ It is concluded that  **ɪꜰ ᴀ ꜰᴜɴᴄᴛɪᴏɴ ɪꜱ ɴᴏᴛ ᴄᴏɴᴛɪɴᴜᴏᴜꜱ ᴀᴛ ᴀ ᴩᴏɪɴᴛ, ɪᴛ ɪꜱ ɴᴏᴛ ᴅɪꜰꜰᴇʀᴇɴᴛɪᴀʙʟᴇ ᴀᴛ ᴛʜᴀᴛ ᴩᴏɪɴᴛ.**
         $\rule{0pt}{}$
                ■ $\displaystyle \lim_{x\to a}𝒇(𝒙)\neq 𝒇(a)\;\Rightarrow\;𝒇'(a)$ does not exist
                $\rule{0pt}{}$
    ◉ [1:09:00](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=4140). A graph is used to illustrate a function continuous at a point but not differentiable at that point (a sharp point).
         ○ It is concluded that **ᴄᴏɴᴛɪɴᴜɪᴛy ᴅᴏᴇꜱ ɴᴏᴛ ɪᴍᴩʟy ᴅɪꜰꜰᴇʀᴇɴᴛɪᴀʙɪʟɪᴛy.**
         $\rule{0pt}{}$
              ■ $\displaystyle \lim_{x\to a}𝒇(𝒙)=𝒇(a)\;\nRightarrow\;𝒇'(a)$
                $\rule{0pt}{}$
         ○ It is established that  **ᴅɪꜰꜣᴇʀᴇɴᴛɪᴀʙɪʟɪᴛy ɪᴍᴩʟɪᴇꜱ ᴄᴏɴᴛɪɴᴜɪᴛy.**
         $\rule{0pt}{}$
              ■ $𝒇'(a)$ exist  $\Rightarrow$ $\displaystyle \lim_{x\to a}𝒇(𝒙)=𝒇(a)$
                $\rule{0pt}{}$
         ○ It is reiterated that differentiability is a stronger condition than continuity.
              ■ Differentiability   ⇒  Continuity
            ■ Continuity           ⇏  Differentiability


● [1:11:28](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=4288). The different notations for the derivative are reviewed.  📷[Image](../img/Calculus 1 Lecture 2.1/[1-11-28]-01.png)
    ◉ Prime notation: $𝒇'(𝒙)$
    $\rule{0pt}{}$
    ◉ Leibniz notation: $\dfrac{d}{dx}\big[𝒇(𝒙)\big]$
    $\rule{0pt}{}$
    ◉ Prime notation for functions with variable $𝒚$: $𝒚'$
    $\rule{0pt}{}$
    ◉ Leibniz notation for functions with variable $𝒚$: $\dfrac{d𝒚}{d𝒙}$


● [1:13:24](https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&t=4404). It is explained how to evaluate derivatives at specific points.  📷[Image](../img/Calculus 1 Lecture 2.1/[1-11-28]-02.png)
    ◉ Notation to evaluate the derivative of $𝒇$ at point $a$: $𝒇'(𝑎)$
    ◉ Alternative notation to evaluate the derivative of $𝒇$ at point $a$: $\left.\dfrac{d}{d𝒙}\big[𝒇(𝒙)\big]\right|_{𝒙=𝑎}$
    ◉ Notation to evaluate the derivative of $𝒚$ at point $a$: $𝒚'(𝑎)$
    ◉ Alternative notation to evaluate the derivative of $𝒚$ at point $a$: $\left.\dfrac{d𝒚}{d𝒙}\right|_{𝒙=𝑎}$
