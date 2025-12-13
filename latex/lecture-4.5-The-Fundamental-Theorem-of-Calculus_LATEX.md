-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ４．５  Ｔｈｅ  Ｆｕｎｄａｍｅｎｔａｌ  Ｔｈｅｏｒｅｍ  ｏｆ  Ｃａｌｃｕｌｕｓ**---------------------------------





Ｔｈｅ　Ｆｕｎｄａｍｅｎｔａｌ　Ｔｈｅｏｒｅｍ　ｏｆ　Ｃａｌｃｕｌｕｓ（FTC）　　
　　　　　　　　　　　　　　　　 𝒫𝒜𝑅𝒯 Ⅱ

● [2:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=120). Introduction to the Fundamental Theorem of Calculus (FTC) [📷image](../img/Calculus 1 Lecture 4.5/[02-00]-01.png)
     ◉ Visualizing the area under the curve from 𝓪 to 𝓫
          ○ Subtracting areas: area up to 𝓫 minus area up to 𝓪
     ◉ Analogy with distance: 𝓫-𝓪
     ◉ The area as a function
          ○ Definite integrals as areas with specific limits
          ○ Definition of the definite integral as the difference of the antiderivative evaluated at the integration limits
               ■ The area from 𝓪 to 𝓫 is $𝓕(𝓫)-𝓕(𝓪)$ (FTC 𝒫𝒜𝑅𝒯 Ⅱ )
          ○ The starting point of the integral does not matter, as long as it’s the same for both limits
          
● FTC, 𝒫𝒜𝑅𝒯 II — “Evaluation Theorem”
     ◉ Connects the definite integral to any antiderivative.
     ◉ Statement of FTC 𝒫𝒜𝑅𝒯 II:
     $\rule{0pt}{}$
       $\displaystyle\left\{\begin{aligned}&\underline{\text{If }}\; 𝒇 \text{ is continuous on } [𝓪,𝓫] \text{ and } 𝓕 \text{ is an antiderivative of } 𝒇 \text{ on } [𝓪,𝓫] \; (\text{i.e., } 𝓕'(𝒙)=𝒇(𝒙)), \\[10pt]&\underline{\text{Then }}\; \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙 \;=\; 𝓕(𝓫) - 𝓕(𝓪)\end{aligned}\right.$
 $\rule{0pt}{}$
     ◉ Equivalent form (Net Change Theorem):
      $\rule{0pt}{}$
         $\displaystyle \int_{𝓪}^{𝓫} 𝓕′(𝒙)\,𝒅𝒙 = 𝓕(𝓫) - 𝓕(𝓪)$.

     
● [10:45](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=645). Explanation of why +𝓒 is eliminated in definite integrals [📷image](../img/Calculus 1 Lecture 4.5/[10-45]-01.png)
     ◉ The constant cancels when subtracting antiderivatives, it belogs to the same function.
     ◉ The definite integral results in a single number representing area


● [11:49](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=709).  Examples of definite integrals
 $\rule{0pt}{}$
     ◉ [11:49](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=709). 🧩 Example – 1: $\displaystyle \int_{1}^{5} 𝒙\cdot 𝒅𝒙$ [📷image](../img/Calculus 1 Lecture 4.5/[11-49]-01.png) 
          ○ Antiderivative: 
          $\rule{0pt}{}$
               ■ $𝓕(𝒙)=\dfrac{𝒙^{2}}{2}$
               $\rule{0pt}{}$
          ○ Evaluate at the bounds:  
          $\rule{0pt}{}$
               ■ $\left.\dfrac{𝒙^{2}}{2}\right|_{1}^{5}=\dfrac{5^{2}}{2}-\dfrac{1^{2}}{2}=\dfrac{25}{2}-\dfrac{1}{2}=\dfrac{24}{2}=12$
               $\rule{0pt}{}$
     ◉ [14:02](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=842). 🧩 Example – 2: $\displaystyle \int_{0}^{\pi/2} \cos(𝒙)\,𝒅𝒙$ [📷image-1](../img/Calculus 1 Lecture 4.5/[14-02]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[14-02]-02.png)
     $\rule{0pt}{}$
          ○ Antiderivative:
               ■ $𝓕(𝒙)=\sin(𝒙)$
          ○ Evaluate at the bounds:  
          $\rule{0pt}{}$
               ■ $\left.\sin(𝒙)\right|_{0}^{\pi/2}=\sin\!\left(\dfrac{\pi}{2}\right)-\sin(0)=1-0=1$
               $\rule{0pt}{}$
          ○ Visualizing the area under the cosine function
               ■ Relation to the circle’s area
               ■ Introduction to the idea of signed net area
                $\rule{0pt}{}$
     ◉ [18:30](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1110). 🧩 Example – 3: $\displaystyle \int_{4}^{9} 𝒙^{2}\cdot \sqrt{𝒙}\, 𝒅𝒙$ [📷image](../img/Calculus 1 Lecture 4.5/[18-30]-01.png)
     $\rule{0pt}{}$
          ○ Rewrite with exponents:
          $\rule{0pt}{}$
               ■ $\sqrt{𝒙}=𝒙^{1/2}\;\Rightarrow\; 𝒙^{2}\cdot \sqrt{𝒙}=𝒙^{2}\cdot 𝒙^{1/2}=𝒙^{5/2}$
               $\rule{0pt}{}$
          ○ Antiderivative::
          $\rule{0pt}{}$
               ■  $𝓕(𝒙)=\displaystyle \int 𝒙^{5/2}\,𝒅𝒙=\dfrac{𝒙^{7/2}}{7/2}=\dfrac{2}{7}\cdot 𝒙^{7/2}$
               $\rule{0pt}{}$
          ○ Evaluate at bounds:
          $\rule{0pt}{}$
               ■ $\left.\dfrac{2}{7}\cdot 𝒙^{7/2}\right|_{4}^{9}=\dfrac{2}{7}\cdot 9^{7/2}-\dfrac{2}{7}\cdot 4^{7/2}$
               $\rule{0pt}{}$
          ○ Powers and roots:
          $\rule{0pt}{}$
               ■ $9^{7/2}=(\sqrt{9})^{7}=3^{7}=2187$
               $\rule{0pt}{}$
               ■ $4^{7/2}=(\sqrt{4})^{7}=2^{7}=128$
               $\rule{0pt}{}$
          ○ Final result:
          $\rule{0pt}{}$
             $\dfrac{2}{7}\cdot 2187-\dfrac{2}{7}\cdot 128=\dfrac{4118}{7}$
              $\rule{0pt}{}$
     ◉ [22:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1370). 🧩 Example – 4: $\displaystyle \int_{0}^{\pi/3}\sec^{2}(𝒙)\,𝒅𝒙$ [📷image](../img/Calculus 1 Lecture 4.5/[22-50]-01.png)
          ○ Antiderivative:
          $\rule{0pt}{}$
               ■  $𝓕(𝒙)=\displaystyle \int \sec^{2}(𝒙)\,𝒅𝒙=\tan(𝒙)$
               $\rule{0pt}{}$
          ○ Evaluate at bounds:
          $\rule{0pt}{}$
               ■  $\left.\tan(𝒙)\right|_{0}^{\pi/3}=\tan\!\left(\dfrac{\pi}{3}\right)-\tan(0)=\sqrt{3}-0=\sqrt{3}$
     ◉ [25:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1540). 🧩 Example – 5: Definite integral with reversed limits $\displaystyle \int_{0}^{4} 𝒙^{3}\,𝒅𝒙$ [📷image](../img/Calculus 1 Lecture 4.5/[25-40]-01.png)
     $\rule{0pt}{}$
          ○ Apply 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.2: Reversing the limits of integration changes the sign of the integral.
          $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝓫}^{𝓪} 𝒇(𝒙)\,𝒅𝒙=-\int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{4}^{0} 𝒙^{3}\,𝒅𝒙=\left.\dfrac{𝒙^{4}}{4}\right|_{4}^{0}=\dfrac{0^{4}}{4}-\dfrac{4^{4}}{4}=-64$
               $\rule{0pt}{}$
               ■ $-\displaystyle \int_{0}^{4} 𝒙^{3}\,𝒅𝒙=-\left[\left.\dfrac{𝒙^{4}}{4}\right|_{0}^{4}\right]=-\left[\dfrac{4^{4}}{4}-\dfrac{0^{4}}{4}\right]=-64$
               $\rule{0pt}{}$
     ◉ [28:25](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1705). 🧩 Example – 6: $\displaystyle \int_{1}^{-1} \dfrac{1}{𝒙^{2}}\,𝒅𝒙$ [📷image-1](../img/Calculus 1 Lecture 4.5/[28-25]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[28-25]-02.png) 
      $\rule{0pt}{}$
          ○ Rewrite the integrand with negative exponent:
          $\rule{0pt}{}$
               ■ $𝒙^{-2}=\dfrac{1}{𝒙^{2}}$
               $\rule{0pt}{}$
          ○ Apply the power rule:
          $\rule{0pt}{}$
               ■ $\displaystyle \int 𝒙^{-2}\,𝒅𝒙=\dfrac{𝒙^{-1}}{-1}=-\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
          ○ Evaluate the definite integral:
          $\rule{0pt}{}$
               ■ $\left.-\dfrac{1}{𝒙}\right|_{-1}^{1}=\left(-\dfrac{1}{1}\right)-\left(-\dfrac{1}{-1}\right)=-1-1=-2\; \; \; ❓$
               $\rule{0pt}{}$
          ○ Analysis of the Result
               ■ This result suggests a **negative area**, which raises concerns because the function $𝒇(𝒙)=\dfrac{1}{𝒙^{2}}$ is **always positive** on its domain. According to:
                    ▣ 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.6: If the function is positive, the integral is positive (and vice versa).
                     $\rule{0pt}{}$
                         ▢ If $𝒇(𝒙)\ge 0$ for all $𝒙\in[𝓪,𝓫]$ then $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙 \ge 0$
                          $\rule{0pt}{}$
                              ▲ If $𝒇(𝒙)$ is above the 𝒙-axis, the integral is positive
                               $\rule{0pt}{}$
                         ▢ If $𝒇(𝒙)\le 0$ for all $𝒙\in[𝓪,𝓫]$ then $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙 \le 0$
                          $\rule{0pt}{}$
                              ▲ If $𝒇(𝒙)$ is below the 𝒙-axis, the integral is negative
               ■ So how can the integral be negative, if the function is positive? The issue lies in the **discontinuity** at $𝒙=0$.
                    ▣ Discontinuity and Asymptote
                    $\rule{0pt}{}$
                         ▢ The function $𝒇(𝒙)=\dfrac{1}{𝒙^{2}}$ is **undefined at** $𝒙=0$, and has a **vertical asymptote** there.  
                         $\rule{0pt}{}$
                              ▲ Therefore, the interval $[-1,1]$ includes a point of discontinuity.  
                              $\rule{0pt}{}$
                         ▢ This means the integral is not proper and **must be treated as an improper integral**, using limits.
                              ▲ The function is unbounded and discontinuous at $𝒙=0$, leading to an asymptote.
                         ▢ [33:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=1980). Graphical interpretation showing how the asymptote affects the area.
                              ▲ **Observation:** If, because of the asymptote, some of those rectangles blow up to infinity, then the area can’t be computed.
                         ▢ Domain issue: When an asymptote lies within or at the limit of integration, the integral 
                             may diverge or require special treatment (e.g., improper integrals).
                              ▲ **Observation:** If the integrand has a vertical asymptote that makes some Riemann rectangles unbounded, the corresponding
                                   improper integral diverges; therefore, the area is not defined.
          ○🗒️ NOTE: 🛡️ Pre-check: Domain & Continuity of the Integrand
               ■ Before applying any property (like 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.6), **you must verify that the integrand $𝒇(𝒙)$ is continuous on the interval** $[𝓪,𝓫]$.
                    ▣ If $𝒇(𝒙)$ is **not defined or not continuous** at any point in $[𝓪,𝓫]$, the integral becomes **improper**.
                    ▣ For improper integrals, **standard properties of definite integrals do not necessarily apply**.
                    ▣  In particular, **you cannot directly say that a positive function implies a positive integral** unless the function is continuous throughout the interval.
               ■ **Think about it:**
                    ▣ **Checklist before integrating:**
                         ▢ 1. 📌 Is $𝒇(𝒙)$ defined at every point in $[𝓪,𝓫]$?
                         ▢ 2. 📌 Is $𝒇(𝒙)$ continuous on $[𝓪,𝓫]$?
                    ▣  If **yes**, proceed with Fundamental Theorem & integral properties.
                    ▣ If **no**, analyze the integral as **improper** (i.e., split it or use limits).
     ◉ [37:23](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2243). 🧩 Example – 7: Integrals with piecewise-defined functions [📷image](../img/Calculus 1 Lecture 4.5/[37-23]-01.png)
     $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{6} 𝒇(𝒙)\,𝒅𝒙,\;\;  𝒇(𝒙)=\begin{cases}𝒙^{3}, & 𝒙<2\\[2pt]5𝒙-1, & 𝒙\ge 2\end{cases}$
          $\rule{0pt}{}$
          ○ Splitting the integral over intervals where the function is defined
               ■ Continuity is required to split the integral properly
          ○ Computing each integral separately:
          $\rule{0pt}{}$
           ■ $\displaystyle \int_{0}^{2} 𝒙^{3}\,𝒅𝒙=\left.\dfrac{𝒙^{4}}{4}\right|_{0}^{2}\to \dfrac{2^{4}}{4}-0=\dfrac{16}{4}=4$  
            $\rule{0pt}{}$
      ■ $\displaystyle \int_{2}^{6} (5𝒙-1)\,𝒅𝒙=\int 5𝒙\,𝒅𝒙+\int (-1)\,𝒅𝒙=\dfrac{5𝒙^{2}}{2}-𝒙 \;\Rightarrow\; \left.\left(\dfrac{5𝒙^{2}}{2}-𝒙\right)\right|_{2}^{6}=[90-6]-[10-2]=84-8=76$  
       $\rule{0pt}{}$
    ■ Total area: $4+76=80$
          ○ **What happens at $𝒙=2$?**
               ■ At $𝒙=2$, the function is **discontinuous** (it jumps from one branch to another).  
               ■ Therefore, it is **not differentiable** at that point.  
               ■ **Result:**  There is **no single, continuous antiderivative** on the entire interval $[0,6]$.
               $\rule{0pt}{}$
          ○ **Can we apply the FTC directly to $\displaystyle \int_{0}^{6} 𝒇(𝒙)\,𝒅𝒙$?**
               ■ **No.**  
               ■ The **Fundamental Theorem of Calculus – Part II** (the evaluation part) requires that:
               $\rule{0pt}{}$
                    ▣ 1. $𝒇(𝒙)$ is **continuous over** $[𝓪,𝓫]$  
                   $\rule{0pt}{}$
                    ▣ 2. There exists a function $𝓕$ such that $𝓕′(𝒙)=𝒇(𝒙)$
                   $\rule{0pt}{}$
               ■ In this case, these conditions **are not met** because:
                    ▣ $𝒇(𝒙)$ is **not continuous at** $𝒙=2$  
                    ▣ There is **no single function** $𝓕$ that differentiates to $𝒇$ over $[0,6]$
          ○ **What should we do instead?**
               ■ Split the interval into parts where the function is continuous:
               $\rule{0pt}{}$
                    ▣ $\displaystyle \int_{0}^{6} 𝒇(𝒙)\,𝒅𝒙=\int_{0}^{2} 𝒙^{3}\,𝒅𝒙+\int_{2}^{6}(5𝒙-1)\,𝒅𝒙$
                    $\rule{0pt}{}$
                    ▣ On each subinterval:
                         ▢ $𝒇(𝒙)$ is **continuous**  
                         ▢ We can apply **FTC Part II**  
                         ▢ We compute the area using the appropriate antiderivative for each part
          ○ **Think about it:** 
               ■ **Core Idea:** If the Fundamental Theorem of Calculus **cannot be applied directly** because of a **discontinuity inside the interval**,  
                **split the integral into continuous sections**  and apply the theorem to each one **individually**.
          ○ [38:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2320). ❌ if $5𝒙-1,\; 𝒙>2$, the function $𝒇(𝒙)$ is **not defined** at $𝒙=2$ in the given statement.
               ■ This is a problem because in order to split the definite integral at $𝒙=2$, the function must be defined at that point.  
              $\rule{0pt}{}$
       ■ Since $𝒇(𝒙)$ omits the value at $𝒙=2$, the expression $\displaystyle \int_{0}^{6} 𝒇(𝒙)\,𝒅𝒙$ is not properly defined as a standard definite integral.  
      $\rule{0pt}{}$
       ■ To fix this, the piecewise function must include a definition for $𝒙=2$, either from the left or the right.  
         



Ｔｏｔａｌ　ａｒｅａ
  
● [46:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=2810). Introduction to the concept of total area Vs. signed net area [📷image](../img/Calculus 1 Lecture 4.5/[46-50]-01.png)
     ◉ Explaining the difference between total area and signed net area
          ○ ᴛᴏᴛᴀʟ ᴀʀᴇᴀ: This is calculated by integrating the absolute value of the function over an interval, ensuring all 
               areas contribute positively regardless of whether they are above or below the 𝒙-axis.
                $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝓪}^{𝓫}\lvert 𝒇(𝒙)\rvert\,𝒅𝒙$ and $\lvert 𝒇(𝒙)\rvert=\begin{cases}𝒇(𝒙), & 𝒇(𝒙)\ge 0\\[2pt]-𝒇(𝒙), & 𝒇(𝒙)<0\end{cases}$
                $\rule{0pt}{}$
          ○ ꜱɪɢɴᴇᴅ ɴᴇᴛ ᴀʀᴇᴀ: This result comes from a standard integral without absolute values, where areas above the 𝒙-axis are positive and
           those below are negative, potentially leading to cancellation if regions offset each other.
            $\rule{0pt}{}$
               ■  $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙$

● [54:25](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=3265).  🧩 Example – Example of total area calculation using sign analysis: $1-𝒙^{2}$ on $[0,2]$ [📷image-1](../img/Calculus 1 Lecture 4.5/[54-25]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[54-25]-02.png)
     ◉ Step 1: Find zeros of $𝒇(𝒙)=0$  
       ○ Solve $1-𝒙^{2}=0 \;\Rightarrow\; 𝒙=\pm 1$  
  ◉ Step 2: Create a sign analysis using these roots (those which are within the integration interval) and the interval limits  
       ○ $𝒙=0,\; 𝒙=1,\; 𝒙=2$
  ◉ Step 3: Determine where $𝒇(𝒙)$ is positive or negative  
    ○ Positive: $[0,1]$  
    ○ Negative: $[1,2]$  
  ◉ Step 4: Split the integral according to the sign of $𝒇(𝒙)$  
    ○ Use absolute value: 
     $\rule{0pt}{}$
         ■ $\lvert 𝒇(𝒙)\rvert=\begin{cases}𝒇(𝒙) & \text{if } 𝒇(𝒙)\ge 0\\[2pt]-𝒇(𝒙) & \text{if } 𝒇(𝒙)<0\end{cases}$
       $\rule{0pt}{}$
    ○ So:  
      ■ $A=\displaystyle \int_{0}^{1} (1-𝒙^{2})\,𝒅𝒙+\int_{1}^{2} -(1-𝒙^{2})\,𝒅𝒙=\int_{0}^{1} (1-𝒙^{2})\,𝒅𝒙-\int_{1}^{2} (1-𝒙^{2})\,𝒅𝒙$  
       $\rule{0pt}{}$
  ◉ Step 5: Integrate and evaluate each interval  
      ○ First integral:  
       $\rule{0pt}{}$
        ■$\displaystyle \int_{0}^{1} (1-𝒙^{2})\,𝒅𝒙=\left.[𝒙-\dfrac{𝒙^{3}}{3}]\right|_{0}^{1}=(1-\tfrac{1}{3})-(0-0)=\dfrac{2}{3}$  
       $\rule{0pt}{}$
      ○ Second integral:  
     ■$\displaystyle \int_{1}^{2} (1-𝒙^{2})\,𝒅𝒙=\left.[𝒙-\dfrac{𝒙^{3}}{3}]\right|_{1}^{2}=\left(2-\dfrac{8}{3}\right)-\left(1-\dfrac{1}{3}\right)=\left(-\dfrac{2}{3}\right)-\left(\dfrac{2}{3}\right)=-\dfrac{4}{3}$  
       $\rule{0pt}{}$
          ▣ with the minus sign from before: $-(-\dfrac{4}{3})=+\dfrac{4}{3}$  
       ○ Final calculation of total area  
       $\rule{0pt}{}$
           ■ $A=\dfrac{2}{3}+\dfrac{4}{3}=2$ 




Ｔｈｅ　ｆｕｎｄａｍｅｎｔａｌ　ｔｈｅｏｒｅｍ　ｏｆ　ｃａｌｃｕｌｕｓ　（FTC）　　
                                                           𝒫𝒜𝑅𝒯  Ⅰ 

● [1:09:08](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4148). The Fundamental Theorem of Calculus (FTC),  𝒫𝒜𝑅𝒯  Ⅰ [📷image](../img/Calculus 1 Lecture 4.5/[1-09-08]-01.png)
     ◉ Derivatives and integrals as inverse operations
     ◉ Defining the area function 𝓐(𝒙) as the integral of 𝒇(𝓉) from a to 𝒙
     ◉ Statement of  FTC  𝒫𝒜𝑅𝒯  Ⅰ :
     $\rule{0pt}{}$
         $\displaystyle\left\{\begin{aligned}&\underline{\text{If }}\; 𝒚 = 𝒇(𝒙) \text{ is continuous over } [𝓪,𝒙], \\[8pt]&\underline{\text{Then }}\; \text{the area is } 𝒜(𝒙) \text{ such that } 𝒜'(𝒙)=𝒇(𝒙), \\[12pt]&𝒜(𝒙)=\int_{𝓪}^{𝒙} 𝒇(𝓉)\,𝒅𝓉\end{aligned}\right.$
$\rule{0pt}{}$
     ◉ Teaching notes:  
       ○ If you define the area function from 𝒫𝒜𝑅𝒯 Ⅰ as $𝒜(𝒙)=\displaystyle \int_{𝓪}^{𝒙} 𝒇(t)\,𝒅t$, then $𝒜′(𝒙)=𝒇(𝒙)$,  
    and thus $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝒙=𝒜(𝓫)-𝒜(𝓪)$.  
    ○ The indefinite integral is a family: $\displaystyle \int 𝒇(𝒙)\,𝒅𝒙=𝓕(𝒙)+𝓒$.  
    $\rule{0pt}{}$
    ■ 𝒫𝒜𝑅𝒯 Ⅱ tells you how to use any $𝓕$ to evaluate the definite integral on $[𝓪,𝓫]$.  
    ○ Typical Calc I hypothesis: $𝒇$ continuous on $[𝓪,𝓫]$ (ensures existence and evaluability).
     ◉  [1:13:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4380). Another interpretation of $𝒜(𝒙)$
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}[𝒜(𝒙)]=𝒇(𝒙)\;\Rightarrow\; \dfrac{𝒅}{𝒅𝑥}\!\left[\displaystyle \int_{𝓪}^{𝒙} 𝒇(𝓉)\,𝒅𝓉 \right]=𝒇(𝒙)$ 

● [1:16:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4610). 🧩 Example – Applying the Fundamental Theorem of Calculus (FTC 𝒫𝒜𝑅𝒯  Ⅰ): $\dfrac{𝒅}{𝒅𝑥}\!\left[\displaystyle \int_{1}^{𝒙} 𝓉^{4}\,𝒅𝓉 \right]$ [📷image](../img/Calculus 1 Lecture 4.5/[1-16-50]-01.png)
     ◉ $\dfrac{𝒅}{𝒅𝑥}\!\left[\displaystyle \int_{1}^{𝒙} 𝓉^{4}\,𝒅𝓉 \right]=𝒙^{4}$
     $\rule{0pt}{}$
     ◉ Find an antiderivative of $𝓉^{4}$
     $\rule{0pt}{}$
          ○$\displaystyle \int 𝓉^{4}\,𝒅𝓉=\dfrac{𝓉^{5}}{5}$
                $\rule{0pt}{}$
     ◉ Evaluate the definite integral with limits $[1,𝒙]$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\!\left[\dfrac{𝒙^{5}}{5}-\dfrac{1^{5}}{5}\right] = \dfrac{𝒅}{𝒅𝑥}\!\left[\dfrac{𝒙^{5}}{5}-\dfrac{1}{5}\right]$
            $\rule{0pt}{}$
     ◉  Differentiate the result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\!\left[\dfrac{𝒙^{5}}{5}-\dfrac{1}{5}\right]=𝒙^{4}$
              $\rule{0pt}{}$
     ◉ **Conclusion:**
          ○ This confirms the **Fundamental Theorem of Calculus (Part I)**:
           $\rule{0pt}{}$
               ■ If $𝒜(𝒙)=\displaystyle \int_{𝓪}^{𝒙} 𝒇(𝓉)\,𝒅𝓉$, then $𝒜′(𝒙)=𝒇(𝒙)$ — as long as $𝒇$ is continuous.

               
● [1:19:13](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4753).🧩 Example – Applying the Fundamental Theorem of Calculus (FTC 𝒫𝒜𝑅𝒯  Ⅰ): $\dfrac{𝒅}{𝒅𝑥}\!\left[\displaystyle \int_{𝓪}^{𝒙} \dfrac{\sin(𝓉)}{𝓉}\,𝒅𝓉 \right]$ [📷image](../img/Calculus 1 Lecture 4.5/[1-19-13]-01.png)
     ◉  Conditions for FTC  𝒫𝒜𝑅𝒯  Ⅰ: continuity and boundedness on the interval
      $\rule{0pt}{}$
     ◉  $\dfrac{𝒅}{𝒅𝑥}\!\left[\displaystyle \int_{𝓪}^{𝒙} \dfrac{\sin(𝓉)}{𝓉}\,𝒅𝓉 \right]=\dfrac{\sin(𝒙)}{𝒙}$





Ｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌｓ　ｗｉｔｈ　ｓｕｂｓｔｉｔｕｔｉｏｎ

● [1:21:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4860). Definite integrals with substitution
     ◉ Introduction to the substitution method in definite integrals
          ○ Two main approaches

      
● [1:22:19](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=4939). 𝓜𝓮𝓽𝓱𝓸𝓭 I [📷image](../img/Calculus 1 Lecture 4.5/[1-22-19]-01.png)
     ◉ No change to integration limits; substitute back to 𝒙 before evaluating.
     $\rule{0pt}{}$
     ◉ 🧩 Example – Definite Integral with Substitution (Method 1): $\displaystyle \int_{0}^{2} 4𝒙(𝒙^{2}-1)^{3}\,𝒅𝒙$
          ○ Substitution, finding 𝒅𝓾 and expressing 𝒅𝑥:  
          $\rule{0pt}{}$
               ■  $𝓾=𝒙^{2}-1$  
               ■  $𝒅𝓾=2𝒙\cdot 𝒅𝒙$  
               ■ $\dfrac{𝒅𝓾}{2𝒙}=𝒅𝒙$  
               $\rule{0pt}{}$
          ○ Rewrite integral:  
          $\rule{0pt}{}$
               ■ $\displaystyle \int_{0}^{2} 4𝒙(𝒙^{2}-1)^{3}\,𝒅𝒙=\int_{0}^{2} 2\cdot 𝓾^{3}\,𝒅𝓾=2\int_{0}^{2} 𝓾^{3}\,𝒅𝓾$  
                 $\rule{0pt}{}$
          ○ Integration:  
          $\rule{0pt}{}$
               ■ $\displaystyle \int 𝓾^{3}\,𝒅𝓾=\dfrac{𝓾^{4}}{4}\;\Rightarrow\; 2\cdot \dfrac{𝓾^{4}}{4}=\dfrac{𝓾^{4}}{2}$  
                 $\rule{0pt}{}$
          ○ Back-substitution (don’t change bounds): 
          $\rule{0pt}{}$
               ■ $\dfrac{𝓾^{4}}{2}\;\to\; \left.\dfrac{(𝒙^{2}-1)^{4}}{2}\right|_{0}^{2}$
                  $\rule{0pt}{}$
          ○ Evaluate:  
          $\rule{0pt}{}$
                ■ $\left.\dfrac{(2^{2}-1)^{4}}{2}\right.-\left.\dfrac{(0^{2}-1)^{4}}{2}\right.=\dfrac{3^{4}}{2}-\dfrac{(-1)^{4}}{2}=\dfrac{81}{2}-\dfrac{1}{2}=40$  
             

● [1:33:50](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=5630). 𝓜𝓮𝓽𝒉𝓸𝓭 II [📷image](../img/Calculus 1 Lecture 4.5/[1-33-50]-01.png)
     ◉ Change the limits to match 𝓾; no resubstitution. 
     ◉ **NO** Back-substitution
     ◉ 🧩 Example – Definite Integral with Substitution (Method 2): $\displaystyle \int_{0}^{2} 4𝒙(𝒙^{2}-1)^{3}\,𝒅𝒙$
          ○ Substitution:  
          $\rule{0pt}{}$
               ■ $𝓾=𝒙^{2}-1$  
               ■  $𝒅𝓾=2𝒙\cdot 𝒅𝒙$  
               ■ $\dfrac{𝒅𝓾}{2𝒙}=𝒅𝒙$  
                 $\rule{0pt}{}$
          ○ Change bounds:  
          $\rule{0pt}{}$
               ■ If $𝒙=2\Rightarrow 𝓾=2^{2}-1=3$  
               ■ If $𝒙=0\Rightarrow 𝓾=0^{2}-1=-1$  
                 $\rule{0pt}{}$
          ○ Rewrite integral:  
          $\rule{0pt}{}$
              ■$\displaystyle \int_{0}^{2} 4𝒙(𝒙^{2}-1)^{3}\,𝒅𝒙=\int_{-1}^{3} 2\cdot 𝓾^{3}\,𝒅𝓾=2\int_{-1}^{3} 𝓾^{3}\,𝒅𝓾$  
                $\rule{0pt}{}$
          ○ Integration: 
          $\rule{0pt}{}$
              ■$\displaystyle \int 𝓾^{3}\,𝒅𝓾=\dfrac{𝓾^{4}}{4}\;\Rightarrow\; 2\cdot \dfrac{𝓾^{4}}{4}=\dfrac{𝓾^{4}}{2}$  
                $\rule{0pt}{}$
          ○ Evaluate:  
          $\rule{0pt}{}$
              ■$\left.\dfrac{𝓾^{4}}{2}\right|_{-1}^{3}=\dfrac{3^{4}}{2}-\dfrac{(-1)^{4}}{2}=\dfrac{81}{2}-\dfrac{1}{2}=40$  
                $\rule{0pt}{}$
          ○ **Conclusion:**  
               ■ By changing the bounds to match the substitution,  
                    ▣ there is **no need to back-substitute** into 𝒙.                    

 
● [1:41:00](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6060). Discussion of both methods and common errors

● [1:45:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6340). 🧩 Example – Definite Integral with Substitution (Method 2): $\displaystyle \int_{0}^{\pi/8} \sin^{5}(2𝒙)\cdot \cos(2𝒙)\,𝒅𝒙$[📷image-1](../img/Calculus 1 Lecture 4.5/[1-45-40]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[1-45-40]-02.png)
     ◉ $\displaystyle \int_{0}^{7\pi/8} [\sin(2𝒙)]^{5}\cdot \cos(2𝒙)\,𝒅𝒙$
      $\rule{0pt}{}$
          ○ The integral is rewritten in the form $[𝓰(𝒙)]^{n}\cdot 𝓰'(𝒙)$, which is exactly the pattern for applying the reverse chain rule (substitution).
          $\rule{0pt}{}$
     ◉ $𝓾=\sin(2𝒙)$
          ○ $𝒅𝓾=2\cos(2𝒙)\cdot 𝒅𝒙 \;\Rightarrow\; 𝒅𝒙=\dfrac{𝒅𝓾}{2\cos(2𝒙)}$
          $\rule{0pt}{}$
     ◉ [1:51:02](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=6662). Converting original 𝒙-limits into new 𝓾-limits
     $\rule{0pt}{}$
          ○ $𝒙=0 \Rightarrow 𝓾=\sin(0)=0$  
          ○ $𝒙=7\pi/8 \Rightarrow 𝓾=\sin(2\pi/8)=\dfrac{\sqrt{2}}{2}$
          $\rule{0pt}{}$
     ◉ Substituting and integrating
      $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\sqrt{2}/2} 𝓾^{5}\cdot \left(\dfrac{𝒅𝓾}{2}\right)=\dfrac{1}{2}\int_{0}^{\sqrt{2}/2} 𝓾^{5}\,𝒅𝓾=\dfrac{1}{2}\cdot \left.\dfrac{𝓾^{6}}{6}\right|_{0}^{\sqrt{2}/2} =\dfrac{1}{12}\left[\left(\dfrac{\sqrt{2}}{2}\right)^{6}-0\right]=\dfrac{1}{12}\cdot \dfrac{8}{64}=\dfrac{1}{12}\cdot \dfrac{1}{8}=\dfrac{1}{96}$ 

               
● [1:57:15](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=7035). 🧩 Example – Definite Integral with Substitution (Method 2): $\displaystyle \int_{2}^{5} (2𝒙-5)\,(𝒙-3)^{9}\, 𝒅𝒙$[📷image-1](../img/Calculus 1 Lecture 4.5/[1-57-15]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[1-57-15]-02.png) 
     ◉ Substitution: $𝓾=𝒙-3$, so that: $𝒅𝓾=𝒅𝑥$
     ◉ The integration limits change:
     $\rule{0pt}{}$
          ○ When $𝒙=2 \Rightarrow 𝓾=2-3=-1$
          ○ When $𝒙=5 \Rightarrow 𝓾=5-3=2$
          $\rule{0pt}{}$
     ◉ Rewriting $2𝒙-5$ in terms of $𝓾$:
          ○ Since $𝒙=𝓾+3$, then:  $2𝒙-5=2(𝓾+3)-5=2𝓾+6-5=2𝓾+1$
     ◉ Substituting into the integral:  
      $\rule{0pt}{}$
          ○ $\displaystyle \int_{-1}^{2} (2𝓾+1)\,𝓾^{9}\,𝒅𝓾=\int_{-1}^{2} (2𝓾^{10}+𝓾^{9})\,𝒅𝓾=\left.\left(\dfrac{2𝓾^{11}}{11}+\dfrac{𝓾^{10}}{10}\right)\right|_{-1}^{2}$
           $\rule{0pt}{}$
     ◉ Evaluation:
     $\rule{0pt}{}$
          ○ $\left(\dfrac{2\cdot 2^{11}}{11}+\dfrac{2^{10}}{10}\right)-\left(\dfrac{2\cdot (-1)^{11}}{11}+\dfrac{(-1)^{10}}{10}\right)=\dfrac{4096}{11}+\dfrac{1024}{10}-\left(-\dfrac{2}{11}+\dfrac{1}{10}\right)          =\dfrac{4098}{11}+\dfrac{1023}{10}$  
          $\rule{0pt}{}$
     ◉ Final simplified result:
     $\rule{0pt}{}$
          ○ $\dfrac{52233}{110}$

               
● [2:11:29](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=7889). 🧩 Example – Definite Integral with Substitution (Method 2): $\displaystyle \int_{1}^{3} \dfrac{\cos(\pi/𝒙)}{𝒙^{2}}\,𝒅𝑥$ [📷image-1](../img/Calculus 1 Lecture 4.5/[2-11-29]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.5/[2-11-29]-02.png)
     ◉ Substitution: $𝓾=\dfrac{\pi}{𝒙}$; $𝒅𝓾=-\pi 𝒙^{-2}\,𝒅𝑥$
     $\rule{0pt}{}$
     ◉ Changing the limits:
     $\rule{0pt}{}$
          ○ $𝒙=3 \Rightarrow 𝓾=\pi/3$
          ○ $𝒙=1 \Rightarrow 𝓾=\pi$
          $\rule{0pt}{}$
     ◉ Rewriting the integral:
     $\rule{0pt}{}$
          ○ $\displaystyle \int_{\pi/3}^{\pi} \cos(𝓾)\cdot \left(-\dfrac{\pi}{𝒙^{2}}\right)\,𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Substituting $𝒅𝑥$:
     $\rule{0pt}{}$
          ○ $\displaystyle \int_{\pi/3}^{\pi} \cos(𝓾)\cdot \left(-\dfrac{1}{\pi}\right)\,𝒅𝓾$
          $\rule{0pt}{}$
     ◉ Applying the  𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.4.2 (indefinite interaks) of sign change in limits:
     $\rule{0pt}{}$
          ○ $-\dfrac{1}{\pi}\displaystyle \int_{\pi}^{\pi/3} \cos(𝓾)\,𝒅𝓾=\dfrac{1}{\pi}\displaystyle \int_{\pi/3}^{\pi} \cos(𝓾)\,𝒅𝓾$
           $\rule{0pt}{}$
               ■  𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.2: $\displaystyle \int_{𝓫}^{𝓪} 𝒇(𝒙)\,𝒅𝑥=- \int_{𝓪}^{𝓫} 𝒇(𝒙)\,𝒅𝑥$
               $\rule{0pt}{}$
     ◉ Final evaluation:
     $\rule{0pt}{}$
          ○ $\displaystyle \dfrac{1}{\pi}\left[\sin(𝓾)\right]\Big|_{\pi/3}^{\pi}=\dfrac{1}{\pi}\big(\sin(\pi)-\sin(\pi/3)\big)=\dfrac{1}{\pi}\left(0-\dfrac{\sqrt{3}}{2}\right)=-\dfrac{\sqrt{3}}{2\pi}$

 


Ｉｎｔｅｇｒａｌｓ　ｏｆ　ｅｖｅｎ　ａｎｄ　ｏｄｄ　ｆｕｎｃｔｉｏｎｓ

● [2:26:40](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=8800). Introduction

● [1:27:30](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=5250). ᴇᴠᴇɴ ꜰᴜɴᴄᴛɪᴏɴꜱ [📷image](../img/Calculus 1 Lecture 4.5/[1-27-30]-01.png)
     ◉ $𝒇(-𝒙)=𝒇(𝒙)$, showing symmetry about the y-axis
     ◉ Symmetry: The function is symmetric with respect to the y-axis, which means that if we reflect any point on the
         graph over the vertical axis (y-axis), we obtain another point that also belongs to the graph.
     ◉ 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.1 of integrating an even function over $[-𝓪,𝓪]$
      $\rule{0pt}{}$
          ○ If $𝒇(𝒙)$ is even: $\displaystyle \int_{-a}^{a}𝒇(𝒙)\,𝒅𝑥=2\int_{0}^{a}𝒇(𝒙)\,𝒅𝑥$
           $\rule{0pt}{}$
     ◉ [2:32:30] 🧩 Example – even function: $\displaystyle \int_{-2}^{2}(\,𝒙^{2}+4)\,𝒅𝑥$ [📷image](../img/Calculus 1 Lecture 4.5/[2-32-30]-01.png)
          ○ Step 1: Identify symmetry
          $\rule{0pt}{}$
               ■ $𝒇(−𝒙)=(−𝒙)^{2}+4=𝒙^{2}+4=𝒇(𝒙)\;\to\;𝒇$ is **even**
               $\rule{0pt}{}$
          ○ Step 2: Apply property of even functions
           $\rule{0pt}{}$
               ■ $\displaystyle \int_{-𝓪}^{𝓪}𝒇(𝒙)\,𝒅𝑥=2\int_{0}^{𝓪}𝒇(𝒙)\,𝒅𝑥$
                $\rule{0pt}{}$
               ■ $\displaystyle \int_{-3}^{3}(\,𝒙^{2}+4)\,𝒅𝑥=2\int_{0}^{3}(\,𝒙^{2}+4)\,𝒅𝑥$
                $\rule{0pt}{}$
          ○ Step 3: Compute the integral
          $\rule{0pt}{}$
               ■ $2\Big[\frac{𝒙^{3}}{3}+4𝒙\Big]\Big|_{0}^{3}$
                $\rule{0pt}{}$
               ■ $=2\big[(27/3+12)-0\big]$
               ■ $=2(9+12)=2(21)=42$          
  
● [2:36:10](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=9370). ᴏᴅᴅ ꜰᴜɴᴄᴛɪᴏɴꜱ [📷image](../img/Calculus 1 Lecture 4.5/[2-36-10]-01.png)
     ◉ $𝒇(-𝒙)=-𝒇(𝒙)$, showing symmetry about the origin.
     ◉ Symmetry: The function exhibits symmetry with respect to the origin, which means that if we rotate any 
         point on the graph 180 degrees around the origin (switching the signs of both coordinates), we obtain another point that 
         also belongs to the graph.
     ◉ 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.2 of integrating an odd function over $[-a,a]$
      $\rule{0pt}{}$
          ○ If $𝒇(𝒙)$ is odd: $\displaystyle \int_{-𝓪}^{𝓪}𝒇(𝒙)\,𝒅𝑥=0$
          $\rule{0pt}{}$
     ◉ [2:36:10](https://www.youtube.com/watch?v=xjtEfS0vY2o&t=9370). 🧩 Example – odd function: $\displaystyle \int_{-3}^{3}\frac{\sin(𝒙)}{\sqrt{1+𝒙^{2}}}\,𝒅𝑥$ [📷image](../img/Calculus 1 Lecture 4.5/[2-42-10]-01.png)
          ○ Step 1: Define the function
          $\rule{0pt}{}$
               ■ $𝒇(𝒙)=\dfrac{\sin(𝒙)}{\sqrt{1+𝒙^{2}}}$
               $\rule{0pt}{}$
          ○ Step 2: Test odd/even symmetry
           $\rule{0pt}{}$
               ■ $𝒇(−𝒙)=\dfrac{\sin(−𝒙)}{\sqrt{1+(−𝒙)^{2}}}=\dfrac{−\sin(𝒙)}{\sqrt{1+𝒙^{2}}}=−𝒇(𝒙)$
                $\rule{0pt}{}$
               ■ Therefore, $𝒇(𝒙)$ is **odd**.
          ○ Step 3: Apply 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.5.2 of odd functions
               ■ For any odd function, the areas on symmetric intervals $[−𝓪,0]$ and $[0,𝓪]$ cancel out:
                    ▣ From 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.4.5 of definite integrals:
                     $\rule{0pt}{}$
                         ▢ $\displaystyle \int_{-𝓪}^{𝓪}𝒇(𝒙)\,𝒅𝑥=\int_{-𝓪}^{0}𝒇(𝒙)\,𝒅𝑥+\int_{0}^{𝓪}𝒇(𝒙)\,𝒅𝑥$
                          $\rule{0pt}{}$
                    ▣ Since $𝒇(−𝒙)=−𝒇(𝒙)$, the negative side is the exact opposite of the positive side.
                    ▣ Thus, the two contributions cancel each other out.
                     $\rule{0pt}{}$
               ■ Conclusion: $\displaystyle \int_{-𝓪}^{𝓪}𝒇(𝒙)\,𝒅𝑥=0$

