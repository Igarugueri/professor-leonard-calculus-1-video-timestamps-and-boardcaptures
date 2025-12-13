-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．５　Lｉｍｉｔｓ　Oｆ　Fｕｎｃｔｉｏｎｓ　ａｔ　Iｎｆｉｎｉｔｙ**---------------------------------





Ｒｅｖｉｅｗ　ｏｆ　ｖｅｒｔｉｃａｌ　ａｓｙｍｐｔｏｔｅｓ　ａｎｄ　ｒｅｍｏｖａｂｌｅ　ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ　

● [0:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=0). Reminder of the definition of vertical asymptote (VA): $\lim_{x\to a} 𝒇(𝒙)=\pm\infty$ [📷image](../img/Calculus 1 Lecture 3.5/[0-00]-01.png) 
     ◉ Two cases for a vertical asymptote:
     $\rule{0pt}{}$
          ○ $\lim_{x\to a^-} 𝒇(𝒙)=\lim_{x\to a^+} 𝒇(𝒙)=\pm\infty$               # The limit **exists** (both one-sided limits agree)
          $\rule{0pt}{}$
          ○ $\lim_{x\to a^-} 𝒇(𝒙)=\infty$  and  $\lim_{x\to a^+} 𝒇(𝒙)=-\infty$   # The limit **does not exist** (one-sided limits disagree)
          $\rule{0pt}{}$
     ◉ to find discontinuities **denominator equals zero**.
          ○ If a factor **cannot be canceled**, the discontinuity is a **vertical asymptote**.
          ○ If a factor **can be canceled**, it is a **removable discontinuity**, not a vertical asymptote.

     
● [3:55](https://www.youtube.com/watch?v=-PYebK8DKPc&t=235). Difference between removable discontinuities (holes) and VA. [📷image](../img/Calculus 1 Lecture 3.5/[3-55]-01.png) 
     ◉ ʜ̳ᴏ̳ʟ̳ᴇ̳ꜱ̳: removable discontinuities where only one point is missing in the function. 
          ○ Occur when the **numerator and denominator are zero at the same time**, allowing cancellation of factors.
          ○ One single point is missing from the function.
     ◉ ᴠ̳ᴀ̳: non-removable discontinuities.
          ○ Occur when **discontinuities cannot be canceled**. 

          
● [6:40](https://www.youtube.com/watch?v=-PYebK8DKPc&t=400). 🧩 Example –: $𝒇(𝒙)=\dfrac{𝒙}{(𝒙+3)(𝒙-1)}$ [📷image](../img/Calculus 1 Lecture 3.5/[6-40]-01.png) 
$\rule{0pt}{}$
     ◉ Vertical asymptotes at $𝒙=1$ and $𝒙=-3$ → non-cancelable factors in the denominator.
     ◉ Critical sign-change values are found by:
          ○ Setting the **denominator equal to zero** → to identify discontinuities (**vertical asymptotes**).
          ○ Setting the **numerator equal to zero** → to identify values where the function **crosses the $𝒙$-axis**.
               ■ These are not discontinuities, but they must be **included in the sign analysis** since they may cause a sign change in the rational expression.
                    ▣ In this case, $𝒙=0$ makes the numerator zero → the function is zero at this point and may change sign around it.
                    $\rule{0pt}{}$
     ◉ General rule for analyzing a rational function $𝒇(𝒙)=\dfrac{𝒫(𝒙)}{𝒬(𝒙)}$:
     $\rule{0pt}{}$
          ○ Fully factor both $𝒫(𝒙)$ and $𝒬(𝒙)$, and simplify the expression if possible.
          ○ Identify points of discontinuity from $𝒬(𝒙)=0$:
               ■ If a factor in the denominator **does not cancel** with the numerator, its zero corresponds to a **vertical asymptote (VA)**.
                    ▣ These values are **not in the domain** and divide the number line into intervals.
                    ▣ They are essential in the **sign chart**, as they may trigger sign changes in $𝒇(𝒙)$.
               ■ If a factor in the denominator **does cancel** with one in the numerator, the corresponding $𝒙$-value results in a **hole** (removable discontinuity).
                    ▣ The function is undefined at this point, but the behavior around it may be continuous.
                    ▣ Holes **do not cause sign changes** like VAs do, but must still be **noted** in the analysis.
          ○ Set $𝒫(𝒙)=0$ → determine **x-intercepts** (zeros of the numerator).
               ■ Include them in the sign analysis **only if they are in the domain**, as they may indicate a sign change in the rational expression.
     ◉ [8:14](https://www.youtube.com/watch?v=-PYebK8DKPc&t=494). Using sign analysis to determine behavior around VAs:
          ○ Sign chart:
          $\rule{0pt}{}$
                                                     ¦ ◟                              ¦ ◟  
                                        -----------∣--------------∣-------------∣------------
                      𝒇(𝒙)               -    ◝ ¦         +              -    ◝ ¦   +
                                                   -3                0               1
                                                   $\rule{0pt}{}$
          ○ Limits at critical values:
               ■ Near $𝒙=-3$ (vertical asymptote):
               $\rule{0pt}{}$
                    ▣ $\lim_{x\to-3^-} 𝒇(𝒙)=-\infty$   # denominator $\to0^+$, numerator $<0$ ⇒ $-\infty$  
                    $\rule{0pt}{}$
                    ▣ $\lim_{x\to-3^+} 𝒇(𝒙)=+\infty$   # denominator $\to0^-$, numerator $<0$ ⇒ $+\infty$  
                    $\rule{0pt}{}$
                    ▣ Limit does not exist.
               ■ At $𝒙=0$ (zero of the numerator):
               $\rule{0pt}{}$
                    ▣ $\lim_{x\to0} 𝒇(𝒙)=0$   # numerator $\to0$, denominator $\neq0$ ⇒ crosses the x-axis.
                    $\rule{0pt}{}$
               ■ Near $𝒙=1$ (vertical asymptote):
               $\rule{0pt}{}$
                    ▣ $\lim_{x\to1^-} 𝒇(𝒙)=-\infty$   # denominator $\to0^-$, numerator $>0$ ⇒ $-\infty$  
                    $\rule{0pt}{}$
                    ▣ $\lim_{x\to1^+} 𝒇(𝒙)=+\infty$   # denominator $\to0^+$, numerator $>0$ ⇒ $+\infty$  
                    $\rule{0pt}{}$
                    ▣ Limit does not exist.

                    
● [11:55](https://www.youtube.com/watch?v=-PYebK8DKPc&t=715). 🧩 Example –: $\lim_{t\to1} \dfrac{t^3}{(t^2-1)^2}$ [📷image](../img/Calculus 1 Lecture 3.5/[11-55]-01.png) 
     ◉ Discontinuities:
          ○ Discontinuities occur where the denominator equals zero.
          ○ For this problem, they happen at $t=\pm1$ because $(t^2-1)^2=0$.
          ○ These are **vertical asymptotes as they cannot be removed by factoring (non-removable discontinuities)**.
     ◉ Focus on the limit:
          ○ Even though there are two discontinuities ($t=\pm1$), only $t=1$ matters since the limit is evaluated near this value.
               ■ $t=-1$ can be ignored for this problem.
     ◉ Importance of the numerator:
          ○ It is crucial for calculating the limit at vertical asymptotes (VA), as these points determine where the function
             may change its sign in the adjacent intervals.
          ○ Check where the numerator ($t^3=0$) equals zero, which happens at $t=0$.
          ○ $t=0$ is not an asymptote, but it is useful to divide intervals and check for sign changes.
     ◉ Strategy:
          ○ Divide the interval into regions around $t=0$ and $t=1$.
          ○ Evaluate specific points in each region (e.g., $t=0.5,\; t=2$) to understand the function's behavior.
          ○ Sign chart:
          $\rule{0pt}{}$
                                                     ¦                              ◞ ¦ ◟  
                                        -----------∣--------------∣-------------∣------------
                      𝒇(𝒙)                         ¦                            +   ¦   +
                                                    -1               0               1
                                                    $\rule{0pt}{}$
               ■ Near $x=1$ (vertical asymptote):
               $\rule{0pt}{}$
                    ▣ $\lim_{x\to1^-} 𝒇(𝒙)=+\infty$   # denominator $\to0^-$, numerator $>0$ ⇒ $+\infty$  
                    $\rule{0pt}{}$
                    ▣ $\lim_{x\to1^+} 𝒇(𝒙)=+\infty$   # denominator $\to0^+$, numerator $>0$ ⇒ $+\infty$  
                    $\rule{0pt}{}$
                    ▣ Limit exist: $\lim_{x\to1} 𝒇(𝒙)=+\infty$   




Ｌｉｍｉｔｓ　ａｔ　ｉｎｆｉｎｉｔｙ

● [16:30](https://www.youtube.com/watch?v=-PYebK8DKPc&t=990). Question: What happens to a function as **$𝒙$ approaches positive or negative infinity?** [📷image](../img/Calculus 1 Lecture 3.5/[16-30]-01.png) 
     ◉ Exploring the behavior of $1/𝒙$ as $𝒙$ increases:
          ○ As $𝒙$ increases, $1/𝒙$ approaches zero. 
          $\rule{0pt}{}$
               ■ $\lim_{x\to\infty} \dfrac{1}{x}=0$ 
               $\rule{0pt}{}$
               ■ $\lim_{x\to-\infty} \dfrac{1}{x}=0$ 

   
● [20:25](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1225). Definition of limit at infinity : 
     ◉ If $𝒇(𝒙)$ approaches a number as $𝒙$ approaches infinity, the limit exists.

          
● [21:07](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1267). Relation between limits at infinity and **horizontal asymptotes (HA)**:
     ◉ HA represent the value a function approaches as $𝒙$ goes to positive or negative infinity. 

          
● [23:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1380). The rules for calculating limits as $𝒙\to+\infty$ or $𝒙\to-\infty$ [📷image](../img/Calculus 1 Lecture 3.5/[23-00]-01.png) 
                 are the same as before. Therefore, the same rules and techniques apply in both cases.  
                 $\rule{0pt}{}$
     ◉ $\lim_{x\to\infty} \dfrac{1}{x^n}=0$ for any $n>0$ :
     $\rule{0pt}{}$
          ○ Any **constant divided by a variable raised to a power approaching infinity will approach zero**. 

               
● [26:10](https://www.youtube.com/watch?v=-PYebK8DKPc&t=1570). Behavior of polynomials at infinity [📷image](../img/Calculus 1 Lecture 3.5/[26-10]-01.png) 
     ◉ Polynomials do not approach a specific number at infinity but tend to positive or negative infinity. 
     ◉ The behavior of a polynomial at infinity is determined by the **highest power term**. 
          ○ This is because, as $𝒙$ approaches infinity, the lower exponent terms become insignificant compared to the dominant term.
          $\rule{0pt}{}$
     ◉ 🧩 Example –: $\lim_{x\to-\infty} \left(-3x^3-2x^2-x+9\right)=\lim_{x\to-\infty} (-3x^3)=\infty$




Ｃａｌｃｕｌａｔｉｎｇ　ｌｉｍｉｔｓ　ａｔ　ｉｎｆｉｎｉｔｙ

● [36:27](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2187). Introduction.

● [38:15](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2295). 🧩 Example –: $\lim_{x\to\infty} \dfrac{5x-2}{3x+9}$ [📷image](../img/Calculus 1 Lecture 3.5/[38-15]-01.png) 
$\rule{0pt}{}$
     ◉  Key idea: **divide each term by the highest power of $𝒙$ in the denominator**. 
     ◉ Terms with $𝒙$ in the denominator approach zero as $𝒙$ approaches infinity. 
     $\rule{0pt}{}$
     ◉ $\lim_{x\to\infty} \dfrac{5-2/x}{3+9/x}=\dfrac{5}{3}$ 
     $\rule{0pt}{}$
     ◉ Observation: the limit at infinity of a rational function where the powers of $𝒙$ in the 
         numerator and denominator are equal is the ratio of the leading coefficients. 
                 
● [44:28](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2668). 🧩 Example –: $\lim_{x\to-\infty} \dfrac{5x^2-4x}{15x^3-3x}$ [📷image](../img/Calculus 1 Lecture 3.5/[44-28]-01.png) 
$\rule{0pt}{}$
     ◉ Divide all terms by the highest power of $x$ in the denominator ($x^3$):
     $\rule{0pt}{}$
          ○ $\lim_{x\to-\infty} \dfrac{5/x-4/x^2}{15-3/x^3}$
         $\rule{0pt}{}$
     ◉ Analyze behavior as $x\to-\infty$:
     $\rule{0pt}{}$
         ○ $5/x\to0$, $4/x^2\to0$, $3/x^3\to0$
          $\rule{0pt}{}$
     ◉ Substitute limits:
     $\rule{0pt}{}$
         ○ $\dfrac{0-0}{15-0}=0$   $\Rightarrow\ \lim_{x\to-\infty} \dfrac{5x^2-4x}{15x^3-3x}=0$


● [48:05](https://www.youtube.com/watch?v=-PYebK8DKPc&t=2885). 🧩 Example –: $\lim_{x\to-\infty} \dfrac{7x^3-2x^2+1}{9-2x}$ [📷image](../img/Calculus 1 Lecture 3.5/[48-05]-01.png) 
$\rule{0pt}{}$
     ◉ Divide all terms by the highest power of $x$ in the denominator ($x$):
     $\rule{0pt}{}$
          ○ $\lim_{x\to-\infty} \dfrac{7x^2-2x+1/x}{9/x-2}$
        $\rule{0pt}{}$
     ◉ Analyze behavior as $x\to-\infty$:
     $\rule{0pt}{}$
         ○ $7x^2\to+\infty$, $-2x\to+\infty$, $1/x\to0$, $9/x\to0$, denominator $\to-2$
         $\rule{0pt}{}$
     ◉ Substitute limits:
     $\rule{0pt}{}$
         ○ $\dfrac{+\infty}{-2}=-\infty$   $\Rightarrow\ \lim_{x\to-\infty} \dfrac{7x^3-2x^2+1}{9-2x}=-\infty$
      $\rule{0pt}{}$

● [52:15](https://www.youtube.com/watch?v=-PYebK8DKPc&t=3135). 🧩 Example –: $\lim_{x\to\infty} \sqrt[3]{\dfrac{2x^2-3}{x^2-5}}$ [📷image](../img/Calculus 1 Lecture 3.5/[52-15]-01.png) 
$\rule{0pt}{}$
     ◉ Divide inside by the highest power $x^2$:
     $\rule{0pt}{}$
           ○ $\sqrt[3]{\dfrac{2-3/x^2}{1-5/x^2}}$
        $\rule{0pt}{}$
     ◉ Take the limit:
     $\rule{0pt}{}$
           ○ $\sqrt[3]{\dfrac{2}{1}}=\sqrt[3]{2}$


● [53:50](https://www.youtube.com/watch?v=-PYebK8DKPc&t=3230). 🧩 Example –: $\lim_{x\to-\infty} \dfrac{\sqrt{x^2+2}}{3x-6}$ [📷image-1](../img/Calculus 1 Lecture 3.5/[53-50]-01.png) [📷image-2](../img/Calculus 1 Lecture 3.5/[53-50]-02.png)  [📷image-3](../img/Calculus 1 Lecture 3.5/[53-50]-03.png) 
$\rule{0pt}{}$
     ◉ Divide by $x$ (highest power in the denominator):
          ➀  _Applied Property_: Multiplication of Terms with Fractional Powers: $a\cdot b=\sqrt{a^2b^2}$
          $\rule{0pt}{}$
               ■ 🧩 Example –: $\dfrac{1}{x}\cdot\sqrt{x^2+2}=\sqrt{\dfrac{x^2+2}{x^2}}$
               $\rule{0pt}{}$
          ➁  Pay attention to the use of absolute value when simplifying square roots: $\sqrt{x^2}=|x|$ 
          $\rule{0pt}{}$
               ■ (i) Why is $x\neq\sqrt{x^2}$ in general?
               $\rule{0pt}{}$
                    ▣ If $x\ge0$: $\sqrt{x^2}=x$  
                     $\rule{0pt}{}$
                    ▣ If $x<0$: e.g., $x=-3\Rightarrow \sqrt{9}=3\neq -3$
                     $\rule{0pt}{}$
               ■ (ii) Why is $|x|=\sqrt{x^2}$ always true?
               $\rule{0pt}{}$
                    ▣ Both yield the non-negative magnitude of $x$.
                    $\rule{0pt}{}$
     ◉ Step 1. Factor inside the root:
     $\rule{0pt}{}$
          ○ $x^2+2=x^2\,(1+2/x^2)\Rightarrow \sqrt{x^2+2}=|x|\sqrt{1+2/x^2}$
                     $\rule{0pt}{}$
     ◉ Step 2. Substitute:
     $\rule{0pt}{}$
         ○ $\dfrac{\sqrt{x^2+2}}{3x-6}=\dfrac{|x|\sqrt{1+2/x^2}}{3x-6}$
                     $\rule{0pt}{}$
     ◉ Step 3. Divide numerator/denominator by $x$:
     $\rule{0pt}{}$
         ○ $\dfrac{|x|/x\cdot\sqrt{1+2/x^2}}{3-6/x}$
                     $\rule{0pt}{}$
     ◉ Step 4. Limit as $x\to-\infty$:
     $\rule{0pt}{}$
         ○ $|x|/x\to-1$, $\sqrt{1+2/x^2}\to1$, $3-6/x\to3$
          $\rule{0pt}{}$
     ◉ Conclusion: 
          ○ $\lim_{x\to-\infty} \dfrac{\sqrt{x^2+2}}{3x-6}=\dfrac{-1\cdot1}{3}=-\dfrac{1}{3}$

          
● [1:06:53](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4013). 🧩 Example –: $\lim_{x\to\infty}\big(\sqrt{x^4+2}-x^2\big)$ [📷image](../img/Calculus 1 Lecture 3.5/[1-06-53]-01.png) 
$\rule{0pt}{}$
     ◉ Rationalize with the conjugate. 
     ◉ Divide by $x^2$ (highest power relevant). 
     ◉ Step 1: Multiply by the conjugate
     $\rule{0pt}{}$
           ○ $\lim_{x\to\infty} \dfrac{(\sqrt{x^4+2}-x^2)(\sqrt{x^4+2}+x^2)}{\sqrt{x^4+2}+x^2}$
                     $\rule{0pt}{}$
     ◉ Step 2: $(a-b)(a+b)=a^2-b^2$
     $\rule{0pt}{}$
           ○ $\lim_{x\to\infty} \dfrac{x^4+2-x^4}{\sqrt{x^4+2}+x^2}=\lim_{x\to\infty} \dfrac{2}{\sqrt{x^4+2}+x^2}$
                     $\rule{0pt}{}$
     ◉ Step 3: Divide top/bottom by $x^2$
     $\rule{0pt}{}$
          ○ $\lim_{x\to\infty} \dfrac{\dfrac{2}{x^2}}{\sqrt{1+\dfrac{2}{x^4}}+1}$
                     $\rule{0pt}{}$
     ◉ Step 4: Take the limit
     $\rule{0pt}{}$
          ○ $\dfrac{0}{1+1}=0$


● [1:16:00](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4560). 🧩 Example –: $\lim_{x\to\infty}\big(\sqrt{x^4+2x^2+x^2}-x^2\big)$  [📷image](../img/Calculus 1 Lecture 3.5/[1-16-00]-01.png) 
     ◉ Rationalize with the conjugate. 
     ◉ Divide each term by $x^2$. 
     ◉ Step 1: Multiply by the conjugate
     $\rule{0pt}{}$
          ○ $\lim_{x\to\infty}\dfrac{(\sqrt{x^4+2x^2+x^2}-x^2)(\sqrt{x^4+2x^2+x^2}+x^2)}{\sqrt{x^4+2x^2+x^2}+x^2}$
                     $\rule{0pt}{}$
     ◉ Step 2: $(a-b)(a+b)=a^2-b^2$
     $\rule{0pt}{}$
          ○ $\lim_{x\to\infty}\dfrac{x^4+2x^2+x^2-x^4}{\sqrt{x^4+2x^2+x^2}+x^2}=\lim_{x\to\infty}\dfrac{2x^2}{\sqrt{x^4+2x^2+x^2}+x^2}$
                     $\rule{0pt}{}$
     ◉ Step 3: Divide by $x^2$
     $\rule{0pt}{}$
          ○ $\lim_{x\to\infty}\dfrac{2}{\sqrt{1+\dfrac{2}{x^2}+\dfrac{1}{x^2}}+1}$
                     $\rule{0pt}{}$
     ◉ Step 4: Take the limit
     $\rule{0pt}{}$
           ○ $\dfrac{2}{1+1}=1$   

     
● [1:20:51](https://www.youtube.com/watch?v=-PYebK8DKPc&t=4851). 🧩 Example –: $\lim_{x\to\infty} \sqrt{7-x}$  [📷image](../img/Calculus 1 Lecture 3.5/[1-20-51]-01.png) 
     ◉ Does not exist: D.N.E
     ◉ The expression inside the square root becomes negative as $𝒙\to+\infty$.

●  SUMMARY: INDETERMINATE FORMS         
     When x → ∞ or x → −∞ in limits         
╭────────────┬───────────────────────────────────────────────╮
│  Form                     │                Interpretation                                                                                   │
├────────────┼───────────────────────────────────────────────┤
│ ∞ / ∞                      │ A race of growth: who wins?                                                                           │
│                               │ → Divide all terms by the highest power of x                                                 │
├────────────┼───────────────────────────────────────────────┤
│ 0 / 0                       │ A hidden simplification awaits!                                                                        │
│                               │ → Factor, cancel, ( or apply L’Hôpital’s Rule [CALCULUS 2] )                     │
├────────────┼───────────────────────────────────────────────┤
│ ∞ − ∞                     │ Big values clashing… unclear result!                                                              │
│                               │ → Combine into a single fraction                                                                    │
├────────────┼───────────────────────────────────────────────┤
│ 0 × ∞                     │ Shrinking and growing — who dominates?                                                     │
│                               │ → Rewrite as a fraction to resolve it                                                               │
├────────────┼───────────────────────────────────────────────┤
│ 1^∞                        │ Exponential surprise!                                                                                     │
│ 0^0                         │ Ambiguous start of power                                                                              │
│ ∞^0                        │ Explosive base with vanishing power                                                            │
│                                │ → Use logarithms or rewrite using $e^{\ln(\cdot)}$                                                       │
╰────────────┴──────────────────────────────────────────────╯
