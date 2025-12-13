-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　４．１　Aｎ　Iｎｔｒｏｄｕｃｔｉｏｎ　Tｏ　Tｈｅ　Iｎｄｅｆｉｎｉｔｅ　Iｎｔｅｇｒａｌ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

●[0:08](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8). A change in focus: from derivatives to integrals.
     ◉ The two main problems of calculus:
          ○ Finding the slope of a curve at a point (derivatives).
          ○ Finding the area under a curve.
     ◉ [0:44](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=44). Two methods to find the area under a curve:
          ○ The rectangular method.
          ○ The antiderivative method.

● [1:50](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=110). ᴛ̳ʜ̳ᴇ̳ ̳ʀ̳ᴇ̳ᴄ̳ᴛ̳ᴀ̳ɴ̳ɢ̳ᴜ̳ʟ̳ᴀ̳ʀ̳ ̳ᴍ̳ᴇ̳ᴛ̳ʜ̳ᴏ̳ᴅ̳  [📷image](../img/Calculus 1 Lecture 4.1/[1-50]-01.png) 
     ◉ Method description: divide the interval into equal subsections, create a rectangle for each subsection.  
          ○ Divide [𝓪,𝓫] into n equal subsections — equal width ensures uniformity in the calculation.  
          $\rule{0pt}{}$
               ■ Width of each rectangle: $\Delta x=\dfrac{𝓫-𝓪}{n}$.  
               $\rule{0pt}{}$
               ■ If widths were different, each rectangle’s area would need separate handling.  
          ○ Different ways to determine the height of the rectangles:  
               ■ Left endpoints → use $𝒇(𝒙_i)$ at the start of each subinterval.  
               $\rule{0pt}{}$
               ■ Right endpoints → use $𝒇(𝒙_i)$ at the end of each subinterval.  
               $\rule{0pt}{}$
               ■ [5:45](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=345). Midpoints → use $𝒇$ at the middle of each subinterval.  
               $\rule{0pt}{}$
               ■ In all cases, the height corresponds to the value of the function at the chosen point.  
     ◉ [6:50](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=410). Calculation of the approximate area by summing the areas of the rectangles.  
          ○ [7:58](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=478). Improving the approximation: increasing the number of rectangles.  
               ■ The more rectangles I have, the better the approximation becomes.  
          ○ [8:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=500). As the number of rectangles (n) approaches infinity, the space between them approaches zero,  
                      improving the approximation.  
               ■ Consequence: For a better approximation, make the space between each interval (the width of the rectangles) approach zero.  
     ◉🗒️NOTE: 
          ○ If the function dips below the x-axis in any subinterval, the corresponding rectangle will have negative area in the sum.  



● [11:15](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=675). ᴛ̳ʜ̳ᴇ̳ ̳ᴀ̳ɴ̳ᴛ̳ɪ̳ᴅ̳ᴇ̳ʀ̳ɪ̳ᴠ̳ᴀ̳ᴛ̳ɪ̳ᴠ̳ᴇ̳ ̳ᴍ̳ᴇ̳ᴛ̳ʜ̳ᴏ̳ᴅ̳  [📷image](../img/Calculus 1 Lecture 4.1/[11-15]-01.png) 
     ◉ [12:15](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=735). Introduction to the area function $\mathcal{A}(𝒙)$.
     ◉ [13:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=800). Key relationship: the derivative of the area function is the original function.
     $\rule{0pt}{}$
          ○ If $\mathcal{A}(𝒙)$ is the area function for some $𝒇(𝒙)$ on $[𝓪,𝓫]$, then: $\mathcal{A}'(𝒙)=𝒇(𝒙)$ or $\dfrac{d}{dx}\big[\mathcal{A}(𝒙)\big]=𝒇(𝒙)$
                                                   $\color{magenta}{\text{↓ this implies ↓}}$
          ○ [15:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=900). $\color{magenta}{\text{Finding the area under the curve involves undoing the derivative (finding the antiderivative).}}$
               ■ $\color{magenta}{\text{The antiderivative is the area under the curve.}}$
          ○ [18:45](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=1125). 🧩 Example [📷image](../img/Calculus 1 Lecture 4.1/[18-45]-01.png) – Demonstration of the relationship between the area function and the original function.
               ■ $𝒇(𝒙)=𝒙+1$  Find area on $[-1,𝒙]$
               $\rule{0pt}{}$
               ■ Geometric picture (for $𝒙\ge -1$):
               $\rule{0pt}{}$
                    ▣ On $[-1,𝒙]$, the graph of $𝒇$ is a line of slope $1$ with $𝒇(-1)=0$.
                    $\rule{0pt}{}$
                    ▣ The region under $𝒇$ from $-1$ to $𝒙$ is a right triangle.
                         ▢ base $=𝒙-(-1)=𝒙+1$
                         ▢ height $=𝒇(𝒙)=𝒙+1$
                    ▣ Area function:
                    $\rule{0pt}{}$
                         ▢  $\mathcal{A}(𝒙)=\dfrac{1}{2}\cdot\text{base}\cdot\text{height}$
                                                  $\rule{0pt}{}$
                         ▢ $\dfrac{1}{2}\cdot(𝒙+1)\cdot(𝒙+1)$
                         $\rule{0pt}{}$
                         ▢ $\dfrac{1}{2}\cdot(𝒙^{2}+2𝒙+1)$
                                                                       $\rule{0pt}{}$
                          ▢ $\dfrac{𝒙^{2}}{2}+𝒙+\dfrac{1}{2}$
                                                                        $\rule{0pt}{}$
                    ▣ Differentiate $\mathcal{A}(𝒙)$:
                    $\rule{0pt}{}$
                         ▢ $\mathcal{A}'(𝒙)=\dfrac{d}{dx}\big[\dfrac{𝒙^{2}}{2}+𝒙+\dfrac{1}{2}\big]=𝒙+1=𝒇(𝒙)$
                         $\rule{0pt}{}$
                    ▣ Takeaway (a preview of a powerful upcoming result):
                         ▢ The derivative of the area-under-the-curve function equals the original integrand:
                         $\rule{0pt}{}$
                              ▲ $\mathcal{A}'(𝒙)=𝒇(𝒙)$.
                              $\rule{0pt}{}$
                         ▢ $\mathcal{A}(𝒙)$ gives the (signed) area from $-1$ to $𝒙$; for $𝒙\ge -1$ it matches the triangle’s area above.
                         ▢ 🗒️NOTE:
                              ▲ The rate of change of the area function $\mathcal{A}(𝒙)$ equals the original function $𝒇(𝒙)$.
                              ▲ This is an early glimpse of a deep connection between differentiation and finding areas — a connection
                                            we will formalize later.
          ○ [26:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=1580). 🧩 Example [📷image-1](../img/Calculus 1 Lecture 4.1/[26-20]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[26-20]-02.png)– : Find area under $𝒇(𝒙)=𝒙^{2}$ on $[0,1]$.
               ■ Idea:
                    ▣ If $𝒇(𝒙)=𝒙^{2}$ and the area function $\mathcal{A}(𝒙)$ satisfies $\mathcal{A}'(𝒙)=𝒇(𝒙)$, then we have: $\mathcal{A}'(𝒙)=𝒙^{2}$.
                    $\rule{0pt}{}$
                    ▣ Question: Can we find a function $\mathcal{A}(𝒙)$ whose derivative is $𝒙^{2}$?
               ■ Trial and correction:
                    ▣ Guess: $\mathcal{A}(𝒙)=𝒙^{3}$  
                    $\rule{0pt}{}$
                         ▢  $\mathcal{A}'(𝒙)=3𝒙^{2}$ → too large (factor of 3).
                          $\rule{0pt}{}$
                    ▣ Adjust: $\mathcal{A}(𝒙)=\dfrac{𝒙^{3}}{3}$  
                    $\rule{0pt}{}$
                         ▢  $\mathcal{A}'(𝒙)=𝒙^{2}$ → correct.
                           $\rule{0pt}{}$
                    ▣ NOTE: Adding a constant does not change the derivative:
                    $\rule{0pt}{}$
                         ▢  $\mathcal{A}(𝒙)=\dfrac{𝒙^{3}}{3}+7 \;\Rightarrow\; \mathcal{A}'(𝒙)=𝒙^{2}\;✔$
                                    $\rule{0pt}{}$
                         ▢  $\mathcal{A}(𝒙)=\dfrac{𝒙^{3}}{3}+𝒞 \;\Rightarrow\; \mathcal{A}'(𝒙)=𝒙^{2}\;✔$
                                    $\rule{0pt}{}$
               ■ General form of the area function:
               $\rule{0pt}{}$
                    ▣ $\mathcal{A}(𝒙)=\dfrac{𝒙^{3}}{3}+𝒞$, where $𝒞$ is any constant.
                    $\rule{0pt}{}$
                    ▣ This tells us that all antiderivatives of $𝒙^{2}$ differ by a constant.
               ■ Takeaway (preview of a powerful upcoming result):
                    ▣ The process of finding the area function is essentially finding an antiderivative.
                    ▣ Later, we will formalize the connection between the area and the antiderivative
                       using the Fundamental Theorem of Calculus.
               ■ [31:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=1880). The importance of the constant "𝓒" in the antiderivative: it represents a family of curves.
               $\rule{0pt}{}$
                    ▣ [33:30](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2010). $\mathcal{A}(𝒙)=\dfrac{1}{3}𝒙^{3}+𝓒$
                    $\rule{0pt}{}$
                         ▢ $𝓒$ is a constant
                         ▢ $𝓒$ is an $y$-axis intercept
                         ▢ $𝓒$ can be found by $𝒙=0$
                         ▢ When we talk about the family of curves (or the family of antiderivatives), we refer to all the functions that, when derived, 
                         $\rule{0pt}{}$
                              yield the same original function. For example, if $\dfrac{d}{dx}\big[𝓕(𝒙)\big]=𝒇(𝒙)$, then the family of antiderivative is written as $𝓕(𝒙)+𝓒$,
                              $\rule{0pt}{}$
                              where $𝓒$ is a real constant. Each value of $𝓒$ defines a different vertical shift in the graph (⇡), but all those curves share the same derivative $𝒇(𝒙)$. 
                              That’s why we say there is a family of curves with the same slope at every point.
                    ▣ [34:50](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2090). How is the area on $[0,𝓍]$ defined, and what is the role of the initial constant $𝓒$ on $\mathcal{A}(𝒙)=\dfrac{1}{3}𝒙^{3}+𝓒$
                         ▢ 1.  Area at a single point: When we talk about “the area from $0$ to $𝓍$” over the interval $[0,𝓍]$, it’s important to note that the interval $[0,0]$ has no “width.” Therefore, the area within $[0,0]$ is $0$ (single point: there’s no space to generate area). This implies $\mathcal{A}(0)=0$  (◈)
                                  $\rule{0pt}{}$
                          ▢ 2. Constant of integration $𝓒$:
                              ▲ 2.1 When defining a function $\mathcal{A}(𝓍)$ that measures the area over $[0,𝓍]$, it is usually expressed as:
                              $\rule{0pt}{}$
                                    ◭ $\mathcal{A}(𝓍)=\text{(area over }[0,𝓍]) + 𝓒$.
                                         $\rule{0pt}{}$
                                    ◭ If we want the area to be $0$ when $𝓍=0$, it must satisfy:
                                    $\rule{0pt}{}$
                                          △  $\mathcal{A}(0)=0+𝓒$ 
                                         $\rule{0pt}{}$
                                          △  $\mathcal{A}(0)=𝓒$  (◈◈)
                                         $\rule{0pt}{}$
                                    ◭ Furthermore, from (◈) and (◈◈) if we assume that $\mathcal{A}(0)=0$ (meaning “there’s no accumulated area at $𝓍=0$”), then $𝓒=0$.
                              ▲ 2.2 Hence on find area under $𝒇(𝒙)=𝒙^{2}$ on $[0,1]$
                              $\rule{0pt}{}$
                                    ◭  $\mathcal{A}(𝒙)=\dfrac{1}{3}𝒙^{3}$  and $\mathcal{A}(1)=\dfrac{1}{3}$ on the interval $[0,1]$
                                        $\rule{0pt}{}$
                         ▢ 3. When the problem allows an initial offset ($𝓒\neq 0$):
                              ▲ In some cases, the function $\mathcal{A}(𝓍)$ may be defined with a nonzero initial value. For example, if at $𝓍=0$ there is alrea𝒅𝑦 an “initial area” of $5$ units, then:
                                    ◭ $\mathcal{A}(0)=5 \Rightarrow 𝓒=5$.
                              ▲ Thus, the constant $𝓒$ adjusts to the initial condition required by the problem.
                    ▣ In summary, $𝓒$ vertically shifts the area function $\mathcal{A}(𝓍)$ and sets the initial accumulated area. When no area is accumulated at the start, $𝓒=0$.





Ｔｈｅ　ｉｎｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌ

● [41:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2460). Introduction.
     ◉ Definition of the indefinite integral: **it has no defined limits**.
     ◉ The indefinite integral represents the area function  $\mathcal{A}(𝒙)$, not a specific area.
      
● [43:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2580). Formal definition of antiderivative. [📷image](../img/Calculus 1 Lecture 4.1/[43-00]-01.png)
     ◉ Given a function, $𝒇$, on some interval, $𝐼$, 
     $\rule{0pt}{}$
          ○ $𝓕$ is called an antiderivative, if  $𝓕'(𝓍)=𝒇(𝓍)$ (or $\dfrac{d}{dx}\big[𝓕(𝒙)\big]=𝒇(𝒙)$)
          $\rule{0pt}{}$
               ■ $𝓕(𝓍)=\mathcal{A}(𝒙)$
     ◉ [45:45](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2745). 🧩 Example –: $𝒇(𝒙)=𝒙^{2}$, $𝓕(𝒙)=\dfrac{1}{3}𝒙^{3}$ this is one antiderivative and Why?…
     $\rule{0pt}{}$
          ○ ... Because $\dfrac{d}{dx}\big[𝓕(𝒙)\big]=\dfrac{d}{dx}\big[\dfrac{1}{3}𝒙^{3}\big]=𝒙^{2}=𝒇(𝒙)$
          $\rule{0pt}{}$
          ○ ... Because $\dfrac{d}{dx}\big[𝓕(𝒙)\big]=\dfrac{d}{dx}\big[\dfrac{1}{3}𝒙^{3}+4\big]=𝒙^{2}=𝒇(𝒙)$
          $\rule{0pt}{}$
          ○ $𝓕(𝒙)=\dfrac{1}{3}𝒙^{3}+𝓒$  This represents all possible antiderivatives of $𝒇(𝒙)=𝒙^{2}$
          $\rule{0pt}{}$
     ◉ [49:10](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2950). The process to find the antiderivative is also colled ɪ̳ɴ̳ᴛ̳ᴇ̳ɢ̳ʀ̳ᴀ̳ᴛ̳ɪ̳ᴏ̳ɴ̳. [📷image](../img/Calculus 1 Lecture 4.1/[49-10]-01.png)


● [51:25](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3085). Notation for the indefinite integral. [📷image](../img/Calculus 1 Lecture 4.1/[51-25]-01.png)
     ◉ Another way to write:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}\big[𝓕(𝒙)+𝓒\big]=𝒇(𝒙))$  is:
          $\rule{0pt}{}$
               ■ $𝓕(𝒙)+𝓒=\displaystyle \int 𝒇(𝒙)\,𝒅𝒙$  (The indefinite integral)
               $\rule{0pt}{}$
                    ▣ The symbol $\displaystyle \int$ represents the integral.
                    ▣ $𝒅𝒙$ indicates the variable of integration $(𝒙)$  or $𝒅𝓉$ if the variable is $𝓉$.
                    ▣ $𝓒$ represents an arbitrary constant.
          ○ [54:25](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3265). Interpretation of the notation: find the antiderivative of $𝒇(𝒙)$ with respect to $𝒙$.
          $\rule{0pt}{}$
     ◉ [55:40](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3340). NOTE: $\dfrac{d}{dx}\Big[\displaystyle \int 𝒇(𝒙)\,𝒅𝒙\Big]=𝒇(𝒙)$ [📷image](../img/Calculus 1 Lecture 4.1/[55-40]-01.png)
     $\rule{0pt}{}$
     ◉ [57:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3420). 🧩 Example – :  $\displaystyle \int 𝒙^{2}\,𝒅𝒙$ [📷image](../img/Calculus 1 Lecture 4.1/[57-00]-01.png)
     $\rule{0pt}{}$
          ○ I want to integrate $𝒇(𝒙)=𝒙^{2}$ with respect to $𝒙$.
          $\rule{0pt}{}$
               ■   $\displaystyle \int 𝒙^{2}\,𝒅𝒙=\dfrac{1}{3}𝒙^{3}+𝓒$

          
● [58:19](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3499). Basic integration table. [📷image-1](../img/Calculus 1 Lecture 4.1/[58-19]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[58-19]-02.png)
$\rule{0pt}{}$
     ◉ From $\dfrac{d}{dx}\big[𝒙^{r}\big]=r\cdot 𝒙^{r-1}$  to:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{r}\,𝒅𝒙=\dfrac{𝒙^{r+1}}{r+1}+𝒞 \;\;(r\neq -1)$  (▽)
          $\rule{0pt}{}$
     ◉ [1:01:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=3660). The integration table shows derivatives and their corresponding integrals.
     $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[𝒙]=1 \quad \to \quad \displaystyle \int 1\,𝒅𝒙=𝒙+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}\big[𝒙^{r}\big]=r\cdot 𝒙^{r-1} \quad \to \quad \displaystyle \int 𝒙^{r}\,𝒅𝒙=\dfrac{𝒙^{r+1}}{r+1}+𝒞$ (▽)
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[\sin(𝒙)]=\cos(𝒙) \quad \to \quad \displaystyle \int \cos(𝒙)\,𝒅𝒙=\sin(𝒙)+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[-\cos(𝒙)]=\sin(𝒙) \quad \to \quad \displaystyle \int \sin(𝒙)\,𝒅𝒙=-\cos(𝒙)+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[\tan(𝒙)]=\sec^{2}(𝒙) \quad \to \quad \displaystyle \int \sec^{2}(𝒙)\,𝒅𝒙=\tan(𝒙)+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[-\cot(𝒙)]=\csc^{2}(𝒙) \quad \to \quad \displaystyle \int \csc^{2}(𝒙)\,𝒅𝒙=-\cot(𝒙)+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[\sec(𝒙)]=\sec(𝒙)\tan(𝒙) \quad \to \quad \displaystyle \int \sec(𝒙)\tan(𝒙)\,𝒅𝒙=\sec(𝒙)+𝓒$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dx}[-\csc(𝒙)]=\csc(𝒙)\cot(𝒙) \quad \to \quad \displaystyle \int \csc(𝒙)\cot(𝒙)\,𝒅𝒙=-\csc(𝒙)+𝓒$
          $\rule{0pt}{}$
     ◉ [37:30](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=2250). The importance of proper sign manipulation in trigonometric integrals.


● [1:17:48](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=4668). 🧩 Examples of indefinite integrals [📷image](../img/Calculus 1 Lecture 4.1/[1-17-48]-01.png) –:
$\rule{0pt}{}$
     ◉ $\displaystyle \int 𝒙^{4}\,𝒅𝒙=\dfrac{1}{5}𝒙^{5}+𝓒$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{1}{𝒙^{3}}\,𝒅𝒙=\displaystyle \int 𝒙^{-3}\,𝒅𝒙=\dfrac{𝒙^{-2}}{-2}+𝓒= -\dfrac{1}{2𝒙^{2}}+𝓒$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \sqrt{𝒙}\,𝒅𝒙=\displaystyle \int 𝒙^{1/2}\,𝒅𝒙=\dfrac{𝒙^{3/2}}{3/2}=\dfrac{2}{3}\cdot 𝒙^{3/2}+𝓒$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙=\displaystyle \int 𝒙^{-1}\,𝒅𝒙$ 
     $\rule{0pt}{}$
          ○ Attempt using the general power rule:
          $\rule{0pt}{}$
               ■$\displaystyle \int 𝒙^{-1}\,𝒅𝒙=\dfrac{𝒙^{n+1}}{n+1}=\dfrac{𝒙^{0}}{0}=\dfrac{1}{0}$ (undefined)
               $\rule{0pt}{}$
               ■ This calculation shows that we cannot use the power rule $\big(\dfrac{𝒙^{n+1}}{n+1}\big)$ when the exponent is $n=-1$, because the  denominator becomes zero (▽).
               $\rule{0pt}{}$
               ■ Therefore, the integral of $\dfrac{1}{𝒙}$ is an exception and is defined as:
               $\rule{0pt}{}$
                    ▣$\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙=\ln|𝒙|+𝓒$


● [1:25:15](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=5115). Properties of indefinite integrals. [📷image-1](../img/Calculus 1 Lecture 4.1/[1-25-15]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[1-25-15]-02.png)
     ◉ Similarity to derivative properties.
     ◉ Properties:
     $\rule{0pt}{}$
          ○ 1. $\displaystyle \int k\cdot 𝒇(𝒙)\,𝒅𝒙=k\cdot \displaystyle \int 𝒇(𝒙)\,𝒅𝒙$ (k is a constant)
           $\rule{0pt}{}$
          ○ 2. $\displaystyle \int \big[𝒇(𝒙)+𝓰(𝒙)\big]\,𝒅𝒙=\displaystyle \int 𝒇(𝒙)\,𝒅𝒙+\displaystyle \int 𝓰(𝒙)\,𝒅𝒙$
           $\rule{0pt}{}$
          ○ 3. $\displaystyle \int \big[𝒇(𝒙)-𝓰(𝒙)\big]\,𝒅𝒙=\displaystyle \int 𝒇(𝒙)\,𝒅𝒙-\displaystyle \int 𝓰(𝒙)\,𝒅𝒙$
           $\rule{0pt}{}$
     ◉ [1:27:34](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=5254). One cannot separate the integral of a product of functions.
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒇(𝒙)\cdot 𝓰(𝒙)\,𝒅𝒙 \neq \Big(\displaystyle \int 𝒇(𝒙)\,𝒅𝒙\Big)\cdot \Big(\displaystyle \int 𝓰(𝒙)\,𝒅𝒙\Big)$ 
          $\rule{0pt}{}$
               ■ [1:32:31](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=5551). Example: $\displaystyle \int 𝒙^{2}\cdot (𝒙+3)\,𝒅𝒙$ use distribution but …
               $\rule{0pt}{}$
                    ▣ … you could not do it here $\displaystyle \int 𝒙^{2}\cdot (𝒙+3)^{3}\,𝒅𝒙$
                    $\rule{0pt}{}$
     ◉ [1:27:25](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=5245). The importance of using a single constant "𝓒" at the end of an indefinite integral calculation.
     $\rule{0pt}{}$
          ○🧩 Example –: $\displaystyle \int 2𝒙\,𝒅𝒙=2\displaystyle \int 𝒙\,𝒅𝒙=\dfrac{2𝒙^{2}}{2}+𝓒$ 
          $\rule{0pt}{}$
         ○ 🧩 Example –: $\displaystyle \int (1 + x)\,dx$:
              ■$\displaystyle \int 1\,dx + \int x\,dx$                           # linearity of the integral
                                                           $\rule{0pt}{}$
              ■ $\displaystyle (x + C_{1}) + \left(\dfrac{x^{2}}{2} + C_{2}\right)$               # $\displaystyle \int 1\,dx = x + C_{1}$, $\displaystyle \int x\,dx = \dfrac{x^{2}}{2} + C_{2}$
                                                            $\rule{0pt}{}$
              ■ $\displaystyle x + \dfrac{x^{2}}{2} + (C_{1} + C_{2})$                      # collect terms
                                                            $\rule{0pt}{}$
              ■ $\displaystyle x + \dfrac{x^{2}}{2} + C$                                    # merge constants into a single $C$


● [1:33:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=5600). 🧩 Examples of indefinite integrals [📷image-1](../img/Calculus 1 Lecture 4.1/[1-33-20]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[1-33-20]-02.png) [📷image-3](../img/Calculus 1 Lecture 4.1/[1-33-20]-03.png) –:
$\rule{0pt}{}$
     ◉ $\displaystyle \int 4\cos(𝒙)\,𝒅𝒙=4\displaystyle \int \cos(𝒙)\,𝒅𝒙=4\sin(𝒙)+𝓒$
     $\rule{0pt}{}$
     ◉ Use of parenthesis.
     $\rule{0pt}{}$
          ○ $\displaystyle \int (𝒙+𝒙^{2})\,𝒅𝒙=\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}+𝓒$    is the same as $\displaystyle \int 𝒙+𝒙^{2}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ $\displaystyle \int \big(2𝒙^{5}-3𝒙^{2}+4𝒙-8\big)\,𝒅𝒙=\dfrac{1}{3}𝒙^{6}-𝒙^{3}+2𝒙^{2}-8𝒙+𝓒$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int (𝒙^{2}-2)(𝒙^{2}-3)\,𝒅𝒙$ 
     $\rule{0pt}{}$
     ◉ Expanding the product:
        $\rule{0pt}{}$
          ○$\displaystyle \int (𝒙^{4}-5𝒙^{2}+6)\,𝒅𝒙$
            $\rule{0pt}{}$
     ◉ Applying the integration rule:
        $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{5}}{5}-\dfrac{5𝒙^{3}}{3}+6𝒙+𝓒$  
            $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{\cos(𝒙)}{\sin^{2}(𝒙)}\,𝒅𝒙 \;\to\; \displaystyle \int \dfrac{1}{\sin(𝒙)}\cdot \dfrac{\cos(𝒙)}{\sin(𝒙)}\,𝒅𝒙 \;\to\; \displaystyle \int \csc(𝒙)\cot(𝒙)\,𝒅𝒙=-\csc(𝒙)+𝓒$
     $\rule{0pt}{}$
     ◉ [1:46:24](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=6384).  $\displaystyle \int \dfrac{T^{2}-2T^{4}}{T^{4}}\,dT = \displaystyle \int \left(\dfrac{T^{2}}{T^{4}}-\dfrac{2T^{4}}{T^{4}}\right)\,dT = \displaystyle \int (T^{-2}-2)\,dT = \displaystyle \int T^{-2}\,dT-\displaystyle \int 2\,dT                                                         = \left(-\dfrac{1}{T}\right)-2T+C$


● [1:52:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=6740). Applications of indefinite integrals. [📷image](../img/Calculus 1 Lecture 4.1/[1-52-20]-01.png)
     ◉  Finding the equation of a curve given its slope at every point.
     ◉ 🧩 Example –: Find the equation of a curve whose slope at each point is $𝒙^{2}$ . . .
     $\rule{0pt}{}$
          ○ The slope $\dfrac{dy}{dx}=𝒙^{2}$
          ○ The family equation of the curve $\dfrac{dy}{dx}=𝒙^{2} \;\Rightarrow\; \displaystyle \int dy=\displaystyle \int 𝒙^{2}\,dx \;\Rightarrow\; y=\displaystyle \int 𝒙^{2}\,dx=\dfrac{1}{3}𝒙^{3}+𝓒$
          $\rule{0pt}{}$
               ■ We have to find out $𝓒$ to find the exact equation
          ○ . . .  passing through $(2,1)$.
               ■ Substituting the point $(2,1)$ into the equation yields $𝓒=-\dfrac{5}{3}$.
               $\rule{0pt}{}$
          ○ The equation of the curve is $y=\dfrac{1}{3}𝒙^{3}-\dfrac{5}{3}$.
               ■ Therefore, it is the only curve within the family  $y=\dfrac{1}{3}𝒙^{3}+𝓒$
                   that passes through $(2,1)$, fixing the value of the constant $𝓒=-\dfrac{5}{3}$.




Ｂｒｉｅｆ　ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｄｉｆｆｅｒｅｎｔｉａｌ　ｅｑｕａｔｉｏｎｓ

● [2:00:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=7200). Family of solutions
$\rule{0pt}{}$
     ◉ $\dfrac{dy}{dx}=𝒇(𝒙)$; IDEA: Can you find $𝓕(𝒙)$ such that $y=𝓕(𝒙)$ satisfies $\dfrac{dy}{dx}=𝒇(𝒙)$?
     $\rule{0pt}{}$
          ○ Example: $\dfrac{dy}{dx}=𝒙^{4}$
          $\rule{0pt}{}$
               ■ $\displaystyle \int \Big(\dfrac{dy}{dx}\Big)\,dx=\displaystyle \int 𝒙^{4}\,dx \;\Rightarrow\; \displaystyle \int 1\,dy=\displaystyle \int 𝒙^{4}\,dx \;\Rightarrow\; y=\dfrac{𝒙^{5}}{5}+𝓒$
               $\rule{0pt}{}$
                    ▣ Find the equation of a curve whose slope at each point is $𝒙^{4}$


● [2:06:14](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=7574). One solution. Initial value problem  [📷image-1](../img/Calculus 1 Lecture 4.1/[2-06-14]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[2-06-14]-02.png)
$\rule{0pt}{}$
     ◉ If, in addition to the differential equation $\dfrac{dy}{dx}=𝒇(𝒙)$, an initial condition is specified, 
     $\rule{0pt}{}$
         for example $y(𝒙_{0})=y_{0}$, then that condition allows us to determine the value of the constant of integration and obtain 
         $\rule{0pt}{}$
         a unique particular solution of the form: $y(𝒙)=\displaystyle \int 𝒇(𝒙)\,dx+𝓒$,  where $𝓒$ is determined using the condition $y(𝒙_{0})=y_{0}$.
         $\rule{0pt}{}$
         In this way, from the family of solutions (which includes all possible values of $𝓒$), exactly one solution is selected that 
         satisfies the given condition.
         $\rule{0pt}{}$
          ○ [2:14:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8040). 🧩 Example –: $\dfrac{dy}{dx}=\dfrac{1}{(2𝒙)^{3}}$, $y(1)=0$ 
          $\rule{0pt}{}$
               ■ $\displaystyle \int (2𝒙)^{-3}\,dx \;\to\; \displaystyle \int 2^{-3}\cdot 𝒙^{-3}\,dx = \displaystyle \int \dfrac{1}{8}𝒙^{-3}\,dx = \dfrac{1}{8}\displaystyle \int 𝒙^{-3}\,dx = \dfrac{1}{8}\cdot \Big(\dfrac{𝒙^{-2}}{-2}\Big)= -\dfrac{1}{16𝒙^{2}}+𝓒$
               $\rule{0pt}{}$
                    ▣ This is a family of curves such that  if I take its derivative I obtain   $\dfrac{1}{(2𝒙)^{3}}$
                    $\rule{0pt}{}$
                         ▢ **How I find a specific curve?** We have to use the initial value
                         $\rule{0pt}{}$
                              ▲ $y(1)=0 \;\Rightarrow\; y=-\dfrac{1}{16𝒙^{2}}+𝓒 \;\Rightarrow\; 0=-\dfrac{1}{16(1)^{2}}+𝓒 \;\Rightarrow\; 𝓒=\dfrac{1}{16}$ 
                              $\rule{0pt}{}$
                    ▣ $y=-\dfrac{1}{16𝒙^{2}}+\dfrac{1}{16}$ this is the exactly on curve that satisfied the initial value. 
                    $\rule{0pt}{}$
          ○ [2:14:20](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8060). 🧩 Example –: Find the equation of a curve whose slope at each point is $\cos(𝒙)$, with the initial condition $y(0)=1$.
          $\rule{0pt}{}$
               ■ $\dfrac{dy}{dx}=\cos(𝒙)$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \Big(\dfrac{dy}{dx}\Big)\,dx=\displaystyle \int \cos(𝒙)\,dx \;\Rightarrow\; y=\sin(𝒙)+𝓒$ 
               $\rule{0pt}{}$
               ■ Substituting the initial condition $y(0)=1 \;\Rightarrow\; 1=\sin(0)+𝓒$  yields $𝓒=1$.
               ■ The equation of the curve is $y=\sin(𝒙)+1$.


● [2:17:25](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8245). 🧩 Example – Real-life application: Catapult  [📷image-1](../img/Calculus 1 Lecture 4.1/[2-17-25]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.1/[2-17-25]-02.png) [📷image-3](../img/Calculus 1 Lecture 4.1/[2-17-25]-03.png) 
     ◉ Problem description: a catapult launches a projectile vertically with an initial
          velocity of 128 ft/s  (39.01 m/s) from a platform 16 ft (4.88 m) high. Find:
          ○ 1. The position function of height 𝒮(𝓉).
          ○ 2. Maximum height.
          ○ 3. When will it hit ground. 
     ◉ [2:20:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8400). Definition of the position, velocity, and acceleration functions:
          ○ $S$'(𝓉): the projectile's position as a function of time.
          ○ $S$''(𝓉): the projectile's velocity as a function of time.
          ○ $S$'''(𝓉): the projectile's acceleration as a function of time.
     ◉ Initial conditions:
          ○ $S$'(0) = 16 ft (initial height)(⇡)
          ○ $S$''(0) = 128 ft/s (initial velocity)
          ○ $S$''(𝓉) = -32 ft (ca. -10 meters)/s² (acceleration due to gravity)
     ◉ [2:27:00](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=8820). Obtaining the velocity function by integrating the acceleration function:
     $\rule{0pt}{}$
          ○ $S'(𝓉)=\displaystyle \int S''(𝓉)\,dt=\displaystyle \int -32\,dt=-32𝓉+𝓒=S'(𝓉)$
          $\rule{0pt}{}$
          ○ Using the initial condition $S'(0)=128 \;\Rightarrow\; 128=-32𝓉+𝓒$:
          $\rule{0pt}{}$
               ■ $128=-32(0)+𝓒$  we get $𝓒=128$.
               $\rule{0pt}{}$
          ○ $S'(𝓉)=-32𝓉+128$
          $\rule{0pt}{}$
     ◉ [2:32:35](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=9155). Obtaining the position function by integrating the velocity function:
     $\rule{0pt}{}$
          ○ $S(𝓉)=\displaystyle \int S'(𝓉)\,dt=\displaystyle \int \big(-32𝓉+128\big)\,dt=-16𝓉^{2}+128𝓉+𝓒=𝒮(𝓉)$
          $\rule{0pt}{}$
          ○ Using the initial condition $S(0)=16 \;\Rightarrow\; 16=-16𝓉^{2}+128𝓉+𝓒$ 
          $\rule{0pt}{}$
               ■ $16=-16(0)^{2}+128(0)+𝓒$ we get $𝓒=16$ (⇡).
               $\rule{0pt}{}$
          ○ $S(𝓉)=-16𝓉^{2}+128𝓉+16$
          $\rule{0pt}{}$
     ◉ [2:39:45](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=9585). Calculating the maximum height:
          ○ The maximum height is reached when the velocity is zero, i.e. $𝒮'(𝓉)=0$.
          ○ Solving $-32𝓉+128=0$ yields $𝓉=4$ seconds.
          ○ Substituting $𝓉=4$ into the position function $S(𝓉)=-16𝓉^{2}+128𝓉+16$, gives the maximum height: $S(4)=784$ ft.
     ◉ [2:42:30](https://www.youtube.com/watch?v=b2ZFpE_yrLg&t=9750). Calculating When will it hit ground.
          ○ The position function is giiven by $S(𝓉)=-16𝓉^{2}+128𝓉+16$
          ○ When it hit ground, the position is $0 \;\Rightarrow\; 0=-16𝓉^{2}+128𝓉+16$
          ○ $𝓉=4+\sqrt{17}\approx 8.123$
