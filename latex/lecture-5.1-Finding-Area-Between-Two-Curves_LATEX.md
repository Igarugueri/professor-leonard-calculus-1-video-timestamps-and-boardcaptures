-----------------------------------**Ｃａｌｃｕｌｕｓ １  Ｌｅｃｔｕｒｅ ５．１  Ｆｉｎｄｉｎｇ  Ａｒｅａ  Ｂｅｔｗｅｅｎ  Ｔｗｏ  Ｃｕｒｖｅｓ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [00:00](https://www.youtube.com/watch?v=c7wur9Lixb0&t=0). Introduction to finding the area between two curves [📷image](../img/Calculus 1 Lecture 5.1/[00-00]-01.png)
     ◉ General idea: A function $𝒇(𝒙)$ is above another function $𝓰(𝒙)$ over an interval $[𝓪,𝓫]$.
          ○ The area between $𝒇(𝒙)$ and $𝓰(𝒙)$ is the area under $𝒇(𝒙)$ minus the area under $𝓰(𝒙)$.
               ■ The area between two curves is always non-negative. If you get a negative value, something is wrong (ordering or setup).
     ◉ [03:55](https://www.youtube.com/watch?v=c7wur9Lixb0&t=235). Representation with integrals
          ○ **Area under $𝒇(𝒙)$ minus area under $𝓰(𝒙)$:**
          $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝓪}^{𝓫}𝒇(𝒙)\,𝒅𝒙 - \int_{𝓪}^{𝓫}𝓰(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
                    ▣ $\displaystyle \int_{𝓪}^{𝓫}\big(𝒇(𝒙)-𝓰(𝒙)\big)\,𝒅𝒙$, assuming $𝒇(𝒙)\geq 𝓰(𝒙)$ for all $𝒙\in[𝓪,𝓫]$
                    $\rule{0pt}{}$
          ○ [05:59](https://www.youtube.com/watch?v=c7wur9Lixb0&t=359). Important note: For the single-integral formula to work, $𝒇(𝒙)\geq 𝓰(𝒙)$ on the entire interval $[𝓪,𝓫]$
               ■ $𝒇(𝒙)$ may touch $𝓰(𝒙)$, but must not go below it on $[𝓪,𝓫]$
               ■ If the graphs intersect inside $(𝓪,𝓫)$, split at all intersection points and integrate piecewise, keeping the upper–minus–lower order on each subinterval.
          ○ [09:48](https://www.youtube.com/watch?v=c7wur9Lixb0&t=588). Relationship with total area [📷image](../img/Calculus 1 Lecture 5.1/[09-48]-01.png)
               ■ Generalization: The “area under a curve” is the area between $𝒇(𝒙)$ and the 𝒙-axis ($y=0$).
                $\rule{0pt}{}$
                    ▣ $\displaystyle \int_{𝓪}^{𝓫}\big(𝒇(𝒙)-0\big)\,𝒅𝒙$ (here $𝓰(𝒙)=0$).
                     $\rule{0pt}{}$
               ■ If $𝒇(𝒙)$ dips below the 𝒙-axis, use absolute value or split at its zeros:
                    ▣ “Above − below” by splitting at $𝓬$ where $𝒇(𝓬)=0$:
                     $\rule{0pt}{}$
                         ▢ $\displaystyle \int_{𝓪}^{𝓬}(𝒇(𝒙)-0)\,𝒅𝒙+\int_{𝓬}^{𝓫}(0-𝒇(𝒙))\,𝒅𝒙=\int_{𝓪}^{𝓬}𝒇(𝒙)\,𝒅𝒙-\int_{𝓬}^{𝓫}𝒇(𝒙)\,𝒅𝒙$
                          $\rule{0pt}{}$
                    ▣ Equivalently, the total area is $\displaystyle \int_{𝓪}^{𝓫}\lvert 𝒇(𝒙)\rvert\,𝒅𝒙$.
                     $\rule{0pt}{}$
               ■ Conclusion: “Area between two curves” and “area under a curve” are the same concept with $𝓰(𝒙)=0$ as the baseline.




Ｅｘａｍｐｌｅｓ

● [14:40](https://www.youtube.com/watch?v=c7wur9Lixb0&t=880). 🧩 Example – Find the area: Bounded above by $y=2𝒙+5$ and below by $y=𝒙^{3}$ on $[0,2]$ [📷image](../img/Calculus 1 Lecture 5.1/[14-40]-01.png)
     ◉ Problem setup: Identify the integration limits and which function is on top.
     ◉ The importance of parentheses when subtracting the two functions with multiple terms.
          ○ If the function below had been $𝓰(𝒙)=𝒙^{3}+1$ note the difference between:
          $\rule{0pt}{}$
               ■ $\displaystyle \int_{0}^{2}\big[(2𝒙+5)-(𝒙^{3}+1)\big]\,𝒅𝒙$ and $\displaystyle \int_{0}^{2}(2𝒙+5)-𝒙^{3}+1\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Integrate and evaluate the resulting integral.
     $\rule{0pt}{}$
          ○ $\displaystyle 𝓐=\int_{0}^{2}\big((2𝒙+5)-(𝒙^{3})\big)\,𝒅𝒙=\int_{0}^{2}(2𝒙+5-𝒙^{3})\,𝒅𝒙=\Big(𝒙^{2}+5𝒙-\dfrac{𝒙^{4}}{4}\Big)\Big|_{0}^{2}$
          $\rule{0pt}{}$
          ○ $𝓐=\big(2^{2}+5\cdot2-(2^{4}/4)\big)-0=10$

            
● [24:35](https://www.youtube.com/watch?v=c7wur9Lixb0&t=1475). 🧩 Example – Finding the area between two curves without a given interval: $𝒇(𝒙)=𝒙^{2},\;𝓰(𝒙)=𝒙+6$ [📷image-1](../img/Calculus 1 Lecture 5.1/[24-35]-01.png) [📷image-2](../img/Calculus 1 Lecture 5.1/[24-35]-02.png)
     ◉ Steps to follow
          ○ [25:10](https://www.youtube.com/watch?v=c7wur9Lixb0&t=1510). 𝒮𝓉ℯ𝓅 1: **Find the intersection points** of the curves.  
               ■ Set $𝒇(𝒙)=𝓰(𝒙)$.  
               ■ Solve $𝒙^{2}=𝒙+6 \;\;\Rightarrow\;\; (𝒙-3)(𝒙+2)=0 \;\;\Rightarrow\;\; 𝒙=-2,𝒙=3$.  
               ■ These are the limits of integration.
          ○ [27:18](https://www.youtube.com/watch?v=c7wur9Lixb0&t=1638). 𝒮𝓉ℯ𝓅 2: **Determine which function is on top** in the interval $[−2,3]$.  
               ■ Test a point (e.g. $𝒙=0$).  
               $\rule{0pt}{}$
               ■ $𝒇(0)=0^{2}=0,\;𝓰(0)=0+6=6$.  
               $\rule{0pt}{}$
               ■ Since $𝓰(𝒙)>𝒇(𝒙)$, the line $𝒙+6$ is above the parabola $𝒙^{2}$.
               $\rule{0pt}{}$
          ○ [32:00](https://www.youtube.com/watch?v=c7wur9Lixb0&t=1920). 𝒮𝓉ℯ𝓅 3: **Set up and solve the integral**.  
          $\rule{0pt}{}$
               ■ $\displaystyle 𝓐=\int_{-2}^{3}\big(𝓰(𝒙)-𝒇(𝒙)\big)\,𝒅𝒙                        =\int_{-2}^{3}(𝒙+6-𝒙^{2})\,𝒅𝒙$  
                $\rule{0pt}{}$
               ■ Compute:  
                    ▣ Antiderivative: $\displaystyle \dfrac{1}{2}𝒙^{2}+6𝒙-\dfrac{1}{3}𝒙^{3}.$  
$\rule{0pt}{}$
                    ▣ Evaluate:  $\displaystyle \Big[\dfrac{1}{2}(3^{2})+6\cdot 3-\dfrac{1}{3}(3^{3})\Big]\;-\;\Big[\dfrac{1}{2}((-2)^{2})+6(-2)-\dfrac{1}{3}((-2)^{3})\Big]$  
$\rule{0pt}{}$
                    ▣ Result: $\displaystyle \dfrac{125}{6}$.



● [38:20](https://www.youtube.com/watch?v=c7wur9Lixb0&t=2300). 🧩 Example – Finding the area between two curves without a given interval: $𝒇(𝒙)=𝒙^{3},\;𝓰(𝒙)=𝒙$ [📷image-1](../img/Calculus 1 Lecture 5.1/[38-20]-01.png) [📷image-2](../img/Calculus 1 Lecture 5.1/[38-20]-02.png)
     ◉ 𝒮𝓉ℯ𝓅 1: Solve $𝒇(𝒙)=𝒙^{3}=𝒙$ → intersections: $−1,0,1$.
     ◉ 𝒮𝓉ℯ𝓅 2: Test points in each interval to see which function is on top.
          ○ $n$ intervals means $n$ integrals
          ○ For each interval test a point to see which function has the higher value.
                    $\rule{0pt}{}$
               ■ On $[−1,0]$: $𝒙^{3}>𝒙$
                         $\rule{0pt}{}$
               ■ On $[0,1]$: $𝒙>𝒙^{3}$
                         $\rule{0pt}{}$
          ○ Split the problem into $n$ integrals because the functions cross.
                    $\rule{0pt}{}$
    ◉ 𝒮𝓉ℯ𝓅 3: Set up the two integrals: $\displaystyle \int_{-1}^{0}(𝒙^{3}-𝒙)\,𝒅𝒙+\int_{0}^{1}(𝒙-𝒙^{3})\,𝒅𝒙$
         ○ Antiderivatives:
$\rule{0pt}{}$
              ■ $\displaystyle \int(𝒙^{3}-𝒙)\,𝒅𝒙=\dfrac{𝒙^{4}}{4}-\dfrac{𝒙^{2}}{2}$
$\rule{0pt}{}$
              ■ $\displaystyle \int(𝒙-𝒙^{3})\,𝒅𝒙=\dfrac{𝒙^{2}}{2}-\dfrac{𝒙^{4}}{4}$
$\rule{0pt}{}$
             $\rule{0pt}{}$
         ○ Evaluate each piece:
$\rule{0pt}{}$
             ■ $\displaystyle \Big[\dfrac{𝒙^{4}}{4}-\dfrac{𝒙^{2}}{2}\Big]_{-1}^{0}=(0-0)-\Big(\dfrac{1}{4}-\dfrac{1}{2}\Big)=\dfrac{1}{4}$
$\rule{0pt}{}$
             ■ $\displaystyle \Big[\dfrac{𝒙^{2}}{2}-\dfrac{𝒙^{4}}{4}\Big]_{0}^{1}=\Big(\dfrac{1}{2}-\dfrac{1}{4}\Big)-(0-0)=\dfrac{1}{4}$
$\rule{0pt}{}$
$\rule{0pt}{}$
        ○ Total area: 
        $\rule{0pt}{}$
             ■ $\displaystyle 𝒜=\dfrac{1}{4}+\dfrac{1}{4}=\dfrac{1}{2}$


                   

Ａｐｐｌｉｃａｔｉｏｎｓ

● [51:00](https://www.youtube.com/watch?v=c7wur9Lixb0&t=3060). 🧩 Example – Distance between two racing cars. [📷image](../img/Calculus 1 Lecture 5.1/[51-00]-01.png)
     ◉ The curves represent each car’s speed as a function of time.
     ◉ The area between the curves represents the distance between the cars.
          ○ The area of each rectangle is $𝓿\cdot𝓽=$ Distance
          $\rule{0pt}{}$
     ◉ Distance $=\displaystyle \int_{𝓪}^{𝓫}\big(\text{Car1 speed}-\text{Car2 speed}\big)\,dt$
     $\rule{0pt}{}$
     ◉ The area shows how far "my" car is ahead of "your" car.
     ◉ If the cars cross paths multiple times, multiple integrals must be set up.
     ◉ The net integral gives the final distance between the cars.


● [1:00:55](https://www.youtube.com/watch?v=c7wur9Lixb0&t=3655). 🧩 Example – Advanced example: Area between $𝒙=𝑦^{2}$ and $𝑦=𝒙-2$ [📷image-1](../img/Calculus 1 Lecture 5.1/[1-00-55]-01.png) [📷image-2](../img/Calculus 1 Lecture 5.1/[1-00-55]-02.png) [📷image-3](../img/Calculus 1 Lecture 5.1/[1-00-55]-03.png) 
     ◉ This problem is tricky because it is not expressed in terms of 𝒙 functions.
     ◉ It helps to sketch a graph.
     ◉ If you only find the intersection points, you miss part of the area.
          ○ The parabola $𝒙=𝑦^{2}$ starts at $𝒙=0$ (vertex at $(0,0)$).
     ◉ [1:05:00](https://www.youtube.com/watch?v=c7wur9Lixb0&t=3900). Integration with respect to 𝒙 Vs. integration with respect to 𝑦
          ○ $𝑦^{2}=𝑦+2$
          ○ Factor the quadratic to find $𝑦$-values of the intersection points.
               ■ $𝑦=-1,\;𝑦=2$
          ○ [1:07:20](https://www.youtube.com/watch?v=c7wur9Lixb0&t=4040). Discussion
               ■ Vertical slices require splitting; horizontal slices do not.
                    ▣ Riemann view: 
                         ▢ Vertical rectangles need two sub-sums ($[0,1]$ & $[1,4]$); 
                         $\rule{0pt}{}$
                         ▢ Horizontal rectangles need one sub-sum ($𝑦∈[−1,2]$).
                         $\rule{0pt}{}$
     ◉ Integration with respect to 𝒙
          ○  𝒮𝓉ℯ𝓅  1: Solve both equations for $𝑦$ in terms of $𝒙$.
               ■ $𝒙=𝑦^{2}$ becomes $𝑦=±\sqrt{𝒙}$.
               ■ $𝑦=𝒙-2$ remains the same.
                    ▣  Solve for $𝑦$: $𝑦^{2}=𝑦+2$
                         ▢ ① Obtaining the values $𝑦=2$ and $𝑦=-1$.
                         ▢ ② Then, substitute these into $𝒙=𝑦^{2}$ (or $𝒙=𝑦+2$) to find the corresponding $𝒙$-values for the integration limits.
                         ▢ ③ Finally, the new limits in terms of $𝒙$ will be $𝒙=1$ and $𝒙=4$, allowing the integral to be rewritten in terms of $𝒙$.
                       $\rule{0pt}{}$
                         ▢ NOTE1: Functions: $\sqrt{𝒙}$ and $-\sqrt{𝒙}$                           $\rule{0pt}{}$
                              ▲ Domain: $𝒙\ge 0$  
                                              $\rule{0pt}{}$
                              ▲ Set equal: $\sqrt{𝒙}=-\sqrt{𝒙}$; $2\sqrt{𝒙}=0 \Rightarrow \sqrt{𝒙}=0 \Rightarrow 𝒙=0$  
                                              $\rule{0pt}{}$
                              ▲ Intersection point: $(0,0)$  
                                              $\rule{0pt}{}$
                         ▢ The functions $\sqrt{𝒙}$ and $-\sqrt{𝒙}$ intersect only at the origin so $𝒙=0$ is another integration limit.
                         ▢ Intersections of the two curves: at $𝑦=-1 \Rightarrow (𝒙,𝑦)=(1,-1)$; at $𝑦=2 \Rightarrow (𝒙,𝑦)=(4,2)$.
          ○ 𝒮𝓉ℯ𝓅 2: Test points in each interval to see which function is on top.
               ■ The function $𝒙=𝑦^{2}$ starts at $0$ (NOTE1) so there are two intervals $[0,1]$, $[1,4]$ 
                    ▣ 2 intervals means 2 integrals
               ■ [1:12:05](https://www.youtube.com/watch?v=c7wur9Lixb0&t=4325). **Re-draw the graph for clarity of the area zone**.
               ■ Identify the upper and lower functions in each region.
              $\rule{0pt}{}$
                             +$\sqrt{𝒙}$              +$\sqrt{𝒙}$
                      ┌───────┬───────┬
                      0                   1                  4
                            -$\sqrt{𝒙}$               $𝒙-2$
                            $\rule{0pt}{}$
                    ▣ Check: at $𝒙=2 \Rightarrow \sqrt{2}\approx 1.414$ vs $𝒙-2=0$ ⇒ top is $\sqrt{𝒙}$; at $𝒙=0.25 \Rightarrow \sqrt{𝒙}=0.5$ and $−\sqrt{𝒙}=−0.5$ ⇒ top is $\sqrt{𝒙}$.
          ○ 𝒮𝓉ℯ𝓅  3: Set up the two integrals:
         $\rule{0pt}{}$
               ■ [1:17:03](https://www.youtube.com/watch?v=c7wur9Lixb0&t=4623). $\displaystyle \int_{0}^{1}\big(\sqrt{𝒙}-(-\sqrt{𝒙})\big)\,𝒅𝒙+\int_{1}^{4}\big(\sqrt{𝒙}-(𝒙-2)\big)\,𝒅𝒙$
              $\rule{0pt}{}$
               ■ Evaluation: $\displaystyle \int_{0}^{1}2\,𝒙^{1/2}\,𝒅𝒙+\int_{1}^{4}\big(𝒙^{1/2}-𝒙+2\big)\,𝒅𝒙=9/2$
              $\rule{0pt}{}$
     ◉ [1:26:40](https://www.youtube.com/watch?v=c7wur9Lixb0&t=5200). Integration with respect to 𝑦 (the best mode).
          ○ Introduction
               ■ **It is easier to integrate with respect to $𝑦$** because only two functions are involved,
                   and one is always to the right of the other.
               ■ The formula is similar to integrating with respect to $𝒙$, but with $𝒙$ and $𝑦$ reversed along the $𝑦$-axis
                    ▣ Now we have to go from $𝓒$ to $𝓓$ along the $𝑦$-axis over one interval $[𝓒,𝓓]$
                    ▣ General idea: A function $𝒇(𝒙)$ is **on the right** of another function $𝓰(𝒙)$ over an interval $[𝓒,𝓓]$
                         ▢ Note that the right function was the above (top) function on interval $[𝓪,𝓫]$ when we integrate with respect to $𝒙$
               ■ **Set up the equations in terms of $𝑦$:** $𝒙=𝒉(𝑦)$, $𝒙=𝓰(𝑦)$.
               $\rule{0pt}{}$
               ■ [1:29:10](https://www.youtube.com/watch?v=c7wur9Lixb0&t=5350). The area is $\displaystyle \int_{𝓒}^{𝓓}\big(𝒉(𝑦)-𝓰(𝑦)\big)\,𝒅𝑦$  if  $𝒉(𝑦)\ge 𝓰(𝑦)$ for all $𝑦\in[𝓒,𝓓]$
               $\rule{0pt}{}$
               ■ Use letters: $𝓒=−1$, $𝓓=2$.
          ○ 𝒮𝓉ℯ𝓅  1: Solve for $𝑦$: $𝑦^{2}=𝑦+2$
               ■ Obtaining the values $𝑦=2$ and $𝑦=-1$.
          ○ 𝒮𝓉ℯ𝓅 2: Determine the integration limits (the $𝑦$-values) and which function is on the right and on the left.
               ■ On the right  $𝑦+2$; on the left  $𝑦^{2}$
                    ▣ Justify right − left on the whole interval: $𝑦^{2}\le 𝑦+2 \Leftrightarrow (𝑦−2)(𝑦+1)\le 0$, true for $𝑦\in[−1,2]$ ⇒ no split needed.
               ■ Continuity note: both curves are continuous; the region is closed and bounded → area via definite integrals applies directly.
               ■ Domain note (for $𝑦=±\sqrt{𝒙}$): $𝒙\ge 0$, which explains the vertical left bound $𝒙=0$ and the split at $𝒙=1$.
          ○ 𝒮𝓉ℯ𝓅  3: Set up the integral:
          $\rule{0pt}{}$
               ■ $\displaystyle \int_{-1}^{2}\big((𝑦+2)-𝑦^{2}\big)\,𝒅𝑦$
               $\rule{0pt}{}$
               ■ Evaluation: Antiderivative $-\tfrac{𝑦^{3}}{3}+\tfrac{𝑦^{2}}{2}+2𝑦$, so area $=9/2$

