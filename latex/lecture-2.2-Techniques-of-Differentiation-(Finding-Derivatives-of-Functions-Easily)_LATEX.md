-----------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．２　Tｅｃｈｎｉｑｕｅｓ　Oｆ　Dｉｆｆｅｒｅｎｔｉａｔｉｏｎ　（ｆｉｎｄｉｎｇ　ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　ｆｕｎｃｔｉｏｎｓ　ｅａｓｉｌｙ)**-------------




I ｎｔｒｏｄｕｃｔｉｏｎ.

● [0:21](https://www.youtube.com/watch?v=EY6FHX6asU0&t=21). Derivative of a Constant. Exploring the slope of a horizontal line 📷[image](../img/Calculus 1 Lecture 2.2/[2-44]-01.png)
     ◉ Graph of a constant: Horizontal or vertical? 🧩 Example – : $𝒚=c$.
     ◉ The slope of a constant line is zero.
     
● [1:27](https://www.youtube.com/watch?v=EY6FHX6asU0&t=87). Meaning of "derivative": Represents the slope of a curve.
     ◉ The derivative as the slope of a function.
     ◉ Generalization: the derivative of any constant is zero.
     ◉ The relationship between the slope of a horizontal line and the derivative of a constant is the same $=0$.
     
● [2:44](https://www.youtube.com/watch?v=EY6FHX6asU0&t=164). In summary: **The derivative of a constant is zero**. 
     ◉ Basic 🧩 Examples –: 📷[image](../img/Calculus 1 Lecture 2.2/[3-05]-01.png)
          ○ Derivative of $3$.
          ○ Derivative of $-1$.
          ○ Derivative of $\pi$.



    
Ｆｏｒｍｕｌａ　ｆｏｒ　ｆｉｎｄｉｎｇ　ａ　ｄｅｒｉｖａｔｉｖ. 

● [4:10](https://www.youtube.com/watch?v=EY6FHX6asU0&t=250). Using limits to find derivatives when there is a variable.
$\rule{0pt}{}$
     ◉ $\dfrac{d}{d𝑥}[𝒇(𝒙)]=\displaystyle \lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$

     
● [4:53](https://www.youtube.com/watch?v=EY6FHX6asU0&t=293). 🧩 Example – : Find the derivative of $𝒇(𝒙)=𝒙^{3}$. [📷image ](../img/Calculus 1 Lecture 2.2/[4-53]-01.png)
     ◉ Formula for the derivative:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
          $\rule{0pt}{}$
     ◉ Step 1: Define the functions:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙+h)=(𝒙+h)^{3}$
          ○ $𝒇(𝒙)=𝒙^{3}$
          $\rule{0pt}{}$
     ◉ Step 2: Substitution into the formula:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{(𝒙+h)^{3}-𝒙^{3}}{h}$
          $\rule{0pt}{}$
     ◉ Step 3: Expand the cube:
     $\rule{0pt}{}$
          ○ $(𝒙+h)^{3}=𝒙^{3}+3𝒙^{2}h+3𝒙h^{2}+h^{3}$
          $\rule{0pt}{}$
     ◉ Step 4: Substitution of the expanded expression:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{(𝒙^{3}+3𝒙^{2}h+3𝒙h^{2}+h^{3})-𝒙^{3}}{h}$
          $\rule{0pt}{}$
     ◉ Step 5: Simplify the expression:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{3𝒙^{2}h+3𝒙h^{2}+h^{3}}{h}$
          $\rule{0pt}{}$
     ◉ Step 6: Factor out $h$:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{h\big(3𝒙^{2}+3𝒙h+h^{2}\big)}{h}$
          $\rule{0pt}{}$
     ◉ Step 7: Cancel $h$:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\displaystyle \lim_{h\to 0}\big(3𝒙^{2}+3𝒙h+h^{2}\big)$
          $\rule{0pt}{}$
     ◉ Step 8: Apply the limit as $h\to 0$:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=3𝒙^{2}$
          $\rule{0pt}{}$
     ◉ Final answer:
          ○ The derivative of $𝒇(𝒙)=𝒙^{3}$ is $𝒇'(𝒙)=3𝒙^{2}$.


● [7:51](https://www.youtube.com/watch?v=EY6FHX6asU0&t=471). The expression $3𝒙^{2}$ gives the slope of the curve $𝒙^{3}$ at any point.




 P ｏｗｅｒ　ｒｕｌｅ　ｆｏｒ　ｄｅｒｉｖａｔｉｖｅｓ

● [8:35](https://www.youtube.com/watch?v=EY6FHX6asU0&t=515). Looking for an easier method to find the derivative.
     ◉ Observing the pattern in the derivative of $𝒙^{3}$.
     ◉ Introduction to the power rule for derivatives: a shorthand method.

     
● [11:58](https://www.youtube.com/watch?v=EY6FHX6asU0&t=718). **ᴩᴏᴡᴇʀ ʀᴜʟᴇ ꜰᴏʀ ᴅᴇʀɪᴠᴀᴛɪᴠᴇꜱ**:  [📷image ](../img/Calculus 1 Lecture 2.2/[11-58]-01.png)
     ◉ $\dfrac{d}{d𝑥}[𝒙^{n}]=n\cdot 𝒙^{\,n-1}$, where $n$ is an integer (for now).

     
● [13:14](https://www.youtube.com/watch?v=EY6FHX6asU0&t=794). 🧩 Examples – of the Power Rule:  [📷image -1](../img/Calculus 1 Lecture 2.2/[13-14]-02.png) [📷image-2](../img/Calculus 1 Lecture 2.2/[13-14]-01.png)
     ◉ $\dfrac{d}{d𝑥}[𝑥^{2}]=2𝑥$.
     $\rule{0pt}{}$
     ◉ $\dfrac{d}{d𝑥}[𝑥^{5}]=5𝒙^{4}$.
     $\rule{0pt}{}$
     ◉ $\dfrac{d}{d𝒔}[𝒔^{15}]=15𝒔^{14}$.
     $\rule{0pt}{}$
     ◉ Adaptation of notation according to the variable.
     ◉ [16:21](https://www.youtube.com/watch?v=EY6FHX6asU0&t=981). Derivatives with Negative Exponents
          ○ $\dfrac{d}{d𝑥}[𝒙^{-3}]=-3𝒙^{-4}$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒑}[𝒑^{-2}]=-2𝒑^{-3}$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒑}\big[-2𝒑^{-5}\big]=10𝒑^{-6}=\dfrac{10}{𝒑^{6}}$
          $\rule{0pt}{}$
               ■ General rule: Rewrite the derivative with positive exponents
               $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝑥}\Big[\dfrac{1}{𝒙}\Big]=-\dfrac{1}{𝒙^{2}}$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝑥}[𝒙]=1\cdot 𝒙^{0}=1$          

        


D ｅｒｉｖａｔｉｖｅｓ　ｗｉｔｈ　ｃｏｎｓｔａｎｔ　ｍｕｌｔｉｐｌｉｃａｔｉｖｅ　ｆａｃｔｏｒｓ

● [20:25](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1225). **ʀᴜʟᴇ ꜰᴏʀ ᴅᴇʀɪᴠᴀᴛɪᴠᴇꜱ ᴡɪᴛʜ ᴄᴏɴꜱᴛᴀɴᴛ ᴍᴜʟᴛɪᴩʟɪᴄᴀᴛɪᴠᴇ ꜰᴀᴄᴛᴏʀꜱ**: [📷image -1](../img/Calculus 1 Lecture 2.2/[20-25]-01.png)
      ◉ $\dfrac{d}{d𝑥}[𝖼\cdot 𝒇(𝒙)]=𝖼\cdot \dfrac{d}{d𝑥}[𝒇(𝒙)]$, where $𝖼$ is a constant.

                  
● [22:00](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1320). 🧩 Example – : $\dfrac{d}{d𝑥}[5𝒙^{4}]=5\cdot \dfrac{d}{d𝑥}[𝒙^{4}]=20𝒙^{3}$.


● [23:13](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1393). 🧩 Example – : $\dfrac{d}{d𝑥}[-𝒙^{7}]=-1\cdot \dfrac{d}{d𝑥}[𝒙^{7}]=-7𝑥^{6}$.


● [24:06](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1446). 🧩 Example – : $\dfrac{d}{d𝑥}\Big[\dfrac{\pi}{𝒙^{2}}\Big]$.
     ◉ Rewrite the expression to apply the power rule: $\dfrac{d}{d𝑥}\big[\pi\cdot 𝒙^{-2}\big]$.
     $\rule{0pt}{}$
     ◉ Apply the constant multiplicative rule: $\pi\cdot \dfrac{d}{d𝑥}[𝒙^{-2}]=-2\pi 𝒙^{-3}$.
     $\rule{0pt}{}$
     ◉ Rewrite with positive exponents: $-\dfrac{2\pi}{𝒙^{3}}$.

    



D ｅｒｉｖａｔｉｖｅｓ　ｏｆ　ｓｕｍｓ　ａｎｄ　ｄｉｆｆｅｒｅｎｃｅｓ

● [27:25](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1645). **ʀᴜʟᴇ ꜰᴏʀ ᴅᴇʀɪᴠᴀᴛɪᴠᴇꜱ ᴏꜰ ꜱᴜᴍꜱ ᴀɴᴅ ᴅɪꜰꜰᴇʀᴇɴᴄᴇꜱ:** [📷image](../img/Calculus 1 Lecture 2.2/[27-25]-01.png)
     ◉ $\dfrac{d}{d𝑥}\big[𝒇(𝒙)\pm 𝓰(𝑥)\big]=\dfrac{d}{d𝑥}[𝒇(𝒙)]\pm \dfrac{d}{d𝑥}[𝓰(𝑥)]$.

     
● [28:40](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1720). 🧩 Example – : $\dfrac{d}{d𝑥}\big[3𝒙^{9}-𝒙^{-3}\big]$.
     ◉ Separate the derivative into two terms: $\dfrac{d}{d𝑥}[3𝑥^{9}]-\dfrac{d}{d𝑥}[𝑥^{-3}]$.
     $\rule{0pt}{}$
     ◉ Apply the constant multiplicative rule: $3\cdot \dfrac{d}{d𝑥}[𝒙^{9}]-\dfrac{d}{d𝑥}[𝑥^{-3}]$.
     $\rule{0pt}{}$
     ◉ Result: $27𝒙^{8}-(-3𝒙^{-4})=27𝒙^{8}+\dfrac{3}{𝒙^{4}}$.

     
● [36:50](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2210). 🧩 Example – : $\dfrac{d}{d𝑥}\big[5𝒙^{7}-3𝒙^{4}+2𝒙^{3}+𝒙-1\big]=35𝒙^{6}-12𝒙^{3}+6𝒙^{2}+1$.





D ｅｒｉｖａｔｉｖｅｓ　ｗｉｔｈ　ｆｒａｃｔｉｏｎａｌ　ｅｘｐｏｎｅｎｔｓ

● [32:54](https://www.youtube.com/watch?v=EY6FHX6asU0&t=1974). 🧩 Example – : $\dfrac{d}{d𝑥}\big[4-3\sqrt{𝒙}\big]$. [📷image](../img/Calculus 1 Lecture 2.2/[32-54]-01.png)
     ◉ Rewrite the root as a fractional exponent: $\dfrac{d}{d𝑥}[4]-\dfrac{d}{d𝑥}\big[3𝒙^{1/2}\big]$.
     ◉ Apply the power rule: $0-\dfrac{3}{2}𝒙^{-1/2}$.    

    


H ｏｒｉｚｏｎｔａｌ　ｔａｎｇｅｎｔ　ｌｉｎｅｓ

● [40:10](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2410). Application of derivatives: finding points where a function has horizontal tangent lines. [📷image](../img/Calculus 1 Lecture 2.2/[40-10]-01.png)


● [41:00](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2460). Horizontal tangent lines have a slope of zero.


● [42:00](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2520). To find points with horizontal tangent lines:
     ◉ Find the derivative of the function.
     ◉ Set the derivative equal to zero.
     ◉ Solve for $𝒙$.

     
● [43:00](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2580). 🧩 Example – : Find the points where $𝒚=𝒙^{3}-3𝒙+4$ has horizontal tangent lines.
$\rule{0pt}{}$
     ◉ Find the derivative: $\dfrac{d𝒚}{d𝑥}=3𝒙²-3$.
     $\rule{0pt}{}$
          ○ [44:25](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2665). When a curve’s slope is zero at a point, it signifies a critical point that may  be a local or global 
                         maximum or minimum. Identifying these points is crucial for optimization and analyzing the behavior of functions in various fiel𝒅𝒔.:
                              ■ Local extrema (maximum or minimum) are the highest or lowest points within a nearby region.
                              ■ Global extrema (maximum or minimum) are the absolute highest or lowest points across the entire domain.                      
     ◉ Set the derivative to zero: $3𝒙²-3=0$.
     ◉ Solve for $𝒙$: $𝒙=1$; $𝒙=-1$
     ◉ Find the corresponding points on the original function: $(-1,\;6)\text{ and }(1,\;2)$.

    



H ｉｇｈｅｒ－ｏｒｄｅｒ　ｄｅｒｉｖａｔｉｖｅｓ

● [47:31](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2851). Introduction to higher-order derivatives. [📷image](../img/Calculus 1 Lecture 2.2/[48-12]-01.png)

● [48:12](https://www.youtube.com/watch?v=EY6FHX6asU0&t=2892). Notation for higher-order derivatives: 
     ◉ $f''(𝒙)$ for the second derivative.
     ◉ $f'''(𝒙)$ for the third derivative, and so on.
     $\rule{0pt}{}$
     ◉ $\dfrac{d^{2}𝒚}{d𝑥^{2}}$ for the second derivative of $𝒚$ with respect to $𝑥$.
     $\rule{0pt}{}$
     ◉ $\dfrac{d^{3}𝒚}{d𝑥^{3}}$ for the third derivative of $𝒚$ with respect to $𝑥$, and so on.

     
● [52:00](https://www.youtube.com/watch?v=EY6FHX6asU0&t=3120). Finding all higher-order derivatives of $7𝒙^{4}-3𝒙^{3}-5𝒙^{2}+9𝒙-347$.
     ◉ First derivative: $28𝒙^{3}-9𝒙^{2}-10𝒙+9$.
     ◉ Second derivative: $84𝒙^{2}-18𝒙-10$.
     ◉ Third derivative: $168𝒙-18$.
     ◉ Fourth derivative: $168$.
     ◉ Fifth derivative: $0$.
     ◉ Sixth derivative and all subsequent derivatives: $0$.

     
● [56:36](https://www.youtube.com/watch?v=EY6FHX6asU0&t=3396). In polynomials, higher-order derivatives eventually become zero.



Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　ｃｏｍｐｌｅｘ　ｑｕｏｔｉｅｎｔｓ

● [58:45](https://www.youtube.com/watch?v=EY6FHX6asU0&t=3525). 🧩 Example – : $\dfrac{d}{d𝑥}\Big[\dfrac{𝒙^{5}-2𝒙-3}{3\sqrt{𝒙}}\Big]$. [📷image](../img/Calculus 1 Lecture 2.2/[58-45]-01.png)
$\rule{0pt}{}$
     ◉ Simplify the expression: $\dfrac{𝒙^{5}-2𝒙-3}{3𝒙^{1/2}}$.
     $\rule{0pt}{}$
     ◉ Cannot take the derivative of each term of the quotient separately.
     $\rule{0pt}{}$
     ◉ Separate the fraction into three terms: $\dfrac{𝒙^{5}}{3𝒙^{1/2}}-\dfrac{2𝒙}{3𝒙^{1/2}}-\dfrac{3}{3𝒙^{1/2}}$.
     $\rule{0pt}{}$
     ◉ [1:02:35](https://www.youtube.com/watch?v=EY6FHX6asU0&t=3755). Simplify each term using exponent properties.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{5}}{3𝒙^{1/2}}=\dfrac{1}{3}𝒙^{9/2}$
          $\rule{0pt}{}$
          ○ $\dfrac{2𝒙}{3𝒙^{1/2}}=\dfrac{2}{3}𝒙^{1/2}$
          $\rule{0pt}{}$
          ○ $\dfrac{3}{3𝒙^{1/2}}=𝒙^{-1/2}$
          $\rule{0pt}{}$
     ◉ [1:06:48](https://www.youtube.com/watch?v=EY6FHX6asU0&t=4008). Take the derivative of each term separately.
     $\rule{0pt}{}$
          ○ Result: $\dfrac{3}{2}𝒙^{7/2}-\dfrac{1}{3}𝒙^{-1/2}+\dfrac{1}{2}𝒙^{-3/2}$
          $\rule{0pt}{}$
     ◉ [1:10:48](https://www.youtube.com/watch?v=EY6FHX6asU0&t=4248). Rewrite the derivative with roots: $\dfrac{3}{2}\sqrt{𝒙^{7}}-\dfrac{1}{3\sqrt{𝒙}}+\dfrac{1}{2\sqrt{𝒙^{3}}}$.
