-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ５．３  Ｖｏｌｕｍｅ  ｏｆ  Ｓｏｌｉｄｓ  Ｂｙ  Ｃｙｌｉｎｄｒｉｃａｌ  Ｓｈｅｌｌｓ  Ｍｅｔｈｏｄ**------------------------------—





Tｈｅ  Ｃｙｌｉｎｄｒｉｃａｌ  Ｓｈｅｌｌｓ  Ｍｅｔｈｏｄ

● [00:01](https://www.youtube.com/watch?v=BDmlottZVd4&t=1). Introduction to the Cylindrical Shells Method [📷image](../img/Calculus 1 Lecture 5.3/[00-01]-01.png)
     ◉ Main idea: Calculate the volume of a solid of revolution around the 𝑦-axis, bounded by vertical lines 𝓐 and 𝓑 and a function 𝒇(𝒙)
     ◉ Alternative to the disk/washer method: The disk/washer method would require two integrals; cylindrical shells aim to solve it with a single integral
     ◉ Visualization: The region is considered a function of 𝒙 rotated around the 𝑦-axis
     ◉ Cake analogy: The method is explained using the analogy of slicing a cake into concentric cylindrical layers with a "coffee cutter"
     ◉ Idea of limits: The thickness of each cylinder tends to be very, very small     

● [02:53](https://www.youtube.com/watch?v=BDmlottZVd4&t=173). Volume of a Cylinder [📷image](../img/Calculus 1 Lecture 5.3/[02-53]-01.png)
     ◉ Volume is the cross-sectional area multiplied by the height
     ◉ The cross-section is a circle (or a washer), obtained by subtracting a smaller circle from a larger one
     $\rule{0pt}{}$
     ◉ Cross-sectional area: $\pi\cdot \mathcal{R}_1^2 - \pi\cdot \mathcal{R}_2^2$, where $\mathcal{R}_1$ and $\mathcal{R}_2$ are the outer and inner radii
     $\rule{0pt}{}$
     ◉ The height is the function 𝒇(𝒙)
          ○ An arbitrary point is chosen to determine the height

● [06:52](https://www.youtube.com/watch?v=BDmlottZVd4&t=412). Mathematical Development of the Formula [📷image](../img/Calculus 1 Lecture 5.3/[06-52]-01.png)
     ◉ Volume = Cross-sectional area × height
     $\rule{0pt}{}$
     ◉ Factoring out π: $\pi(\mathcal{R}_1^2-\mathcal{R}_2^2)\cdot \mathcal{h}$
     $\rule{0pt}{}$
     ◉ Difference of squares: $\pi(\mathcal{R}_1+\mathcal{R}_2)(\mathcal{R}_1-\mathcal{R}_2)\cdot \mathcal{h}$
     $\rule{0pt}{}$
     ◉ Multiplication by $\dfrac{2}{2}$ → $2\cdot\dfrac{1}{2}$: $2\pi\cdot\dfrac{1}{2}\cdot(\mathcal{R}_1+\mathcal{R}_2)\cdot(\mathcal{R}_1-\mathcal{R}_2)\cdot \mathcal{h}$
     $\rule{0pt}{}$
     ◉ Identification of terms:
          ○ 𝒉 = height
          $\rule{0pt}{}$
          ○ $\mathcal{R}_1-\mathcal{R}_2$ = thickness of the cylindrical shell
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}(\mathcal{R}_1+\mathcal{R}_2)$ = average radius
          $\rule{0pt}{}$
     ◉ [11:40](https://www.youtube.com/watch?v=BDmlottZVd4&t=700). General formula: 
          ○ **Volume = $2\pi \cdot (\text{average radius}) \cdot (\text{height}) \cdot (\text{thickness})$**


● [13:00](https://www.youtube.com/watch?v=BDmlottZVd4&t=780). Connection with the Function 𝒇(𝒙) and the Differential [📷image](../img/Calculus 1 Lecture 5.3/[13-00]-01.png)
     ◉ A cylindrical slice is taken within the shell at an arbitrary point $x_{k}^{\ast}$
          ○ [15:30](https://www.youtube.com/watch?v=BDmlottZVd4&t=930). $x_{k}^{\ast}$ is chosen as the midpoint of the interval.
          $\rule{0pt}{}$
               ■ $x_{k}^{\ast}$ is the average point between $x_{k-1}$ and $x_k$
               $\rule{0pt}{}$
     ◉ [16:24](https://www.youtube.com/watch?v=BDmlottZVd4&t=984). The thickness of the slice is $\Delta x$ (the difference between the previous and current slices).
     $\rule{0pt}{}$
     ◉ The height at $x_{k}^{\ast}$ is  $𝒇(x_k^* )$
     $\rule{0pt}{}$
     ◉ [18:20](https://www.youtube.com/watch?v=BDmlottZVd4&t=1100). Volume of an individual shell: $2\pi\cdot x_{k}^{\ast}\cdot 𝒇(x_k^* )\cdot \Delta x$
     $\rule{0pt}{}$
          ○  $2\pi\times(\text{average radius})\times(\text{height})\times(\text{thickness})$
          $\rule{0pt}{}$
     ◉ [20:00](https://www.youtube.com/watch?v=BDmlottZVd4&t=1200). The volumes of all shells are summed to approximate the total volume:
     $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \sum_{k=1}^{n} 2\pi\cdot x_{k}^{\ast}\cdot 𝒇(x_k^* )\cdot \Delta x$
          $\rule{0pt}{}$
     ◉ The limit is taken as the number of shells approaches infinity, converting the sum into an integral:
     $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \lim_{n\to\infty}\sum_{k=1}^{n}2\pi\cdot x_{k}^{\ast}\cdot 𝒇(x_k^* )\cdot\Delta x$
          $\rule{0pt}{}$
     ◉ Final formula:
     $\rule{0pt}{}$
          ○ $\boxed{\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot 𝒙\cdot 𝒇(𝒙)\,d𝒙}$
          $\rule{0pt}{}$
               ■ Random arbitrary points $x_k^*$ are represented by 𝒙  
               ■ Around 𝒚-axis
     ◉ NOTE: Axis of revolution: Around the 𝒚-axis, integration is performed with respect to 𝒙
          ○ **Important!** When rotating around the 𝒙-axis, the function must be in terms of 𝒙:
          $\rule{0pt}{}$
               ■ $\boxed{\mathcal{V}=\displaystyle \int_{\mathcal{c}}^{\mathcal{d}}2\pi\cdot 𝒚\cdot 𝒇(𝒚)\,d𝒚}$
               $\rule{0pt}{}$
               ■ Around 𝒙-axis


● [24:35](https://www.youtube.com/watch?v=BDmlottZVd4&t=1475). 🧩 Example – Region bounded by 𝒇(𝒙)=√𝒙, 𝒙=1, 𝒙=4, revolved around the 𝒚-axis [📷image](../img/Calculus 1 Lecture 5.3/[24-35]-01.png)
     ◉ Confirmation of the function in terms of 𝒙
     $\rule{0pt}{}$
     ◉ Integral setup: $\mathcal{V}=\displaystyle \int_{1}^{4}2\pi\cdot 𝒙\sqrt{𝒙}\,d𝒙$
     $\rule{0pt}{}$
     ◉ Simplification: $2\pi\displaystyle\int_{1}^{4}𝒙^{\dfrac{3}{2}}\,d𝒙$
     $\rule{0pt}{}$
     ◉ Integration: $2\pi\Big[\dfrac{2}{5}𝒙^{\dfrac{5}{2}}\Big]\Big|_{1}^{4}$
     $\rule{0pt}{}$
     ◉ Evaluating limits: $\dfrac{4\pi}{5}\big(4^{\dfrac{5}{2}}-1^{\dfrac{5}{2}}\big)$
     $\rule{0pt}{}$
     ◉ Final result: $\mathcal{V}=\dfrac{124\pi}{5}$


● [29:03](https://www.youtube.com/watch?v=BDmlottZVd4&t=1743). Comparison with Disks/Washers and Functions Between Curves 
     ◉ Cylindrical shells method is an alternative to the disk/washer method, with a key difference:
          ○ Orientation of slices:
               ■ Disks/washers: slices ⟂ to axis of rotation  
               ■ Shells: slices ∥ to axis of rotation → thin strips wrap into cylinders
     ◉ Wrapping around the 𝒚-axis
          ○ Use vertical strips (width $d𝒙$)
          ○ Radius = 𝒙
          $\rule{0pt}{}$
          ○ Height = $[𝒇_{\text{upper}}(𝒙)−𝒇_{\text{lower}}(𝒙)]$
          $\rule{0pt}{}$
          ○ Thickness = $d𝒙$
     ◉ Wrapping around the 𝒙-axis
          ○ Use horizontal strips (width $d𝒚$)
          ○ Radius = 𝒚
          $\rule{0pt}{}$
          ○ Height = $[𝒇_{\text{right}}(𝒚)−𝒇_{\text{left}}(𝒚)]$
          $\rule{0pt}{}$
          ○ Thickness = $d𝒚$
     ◉ Regions bounded by two curves
          ○ Height = upper − lower, similar to areas
     ◉ Integration limits (𝓪, 𝓫)
          ○ Determined by intersection points of the two functions in 𝒙
     ◉ General cylindrical shell formula:
    $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot(\text{radius})\cdot(\text{height})\,d𝒙$
         $\rule{0pt}{}$
          ○ For rotation about the 𝒚-axis: $\boxed{\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot𝒙\cdot[𝒇_{\text{upper}}(𝒙)−𝒇_{\text{lower}}(𝒙)]\,d𝒙}$
         $\rule{0pt}{}$
          ○ For rotation about the 𝒙-axis: $\boxed{\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot𝒚\cdot[𝒇_{\text{right}}(𝒚)−𝒇_{\text{left}}(𝒚)]\,d𝒚}$
         $\rule{0pt}{}$
     ◉ Identifying the “top” function
          ○ Always check which curve is above (larger 𝑦) in the interval


● [29:50](https://www.youtube.com/watch?v=BDmlottZVd4&t=1790). 🧩 Example – Cylindrical shells method: Region bounded by 𝒇(𝒙)=𝒙 and 𝓰(𝒙)=𝒙², around the 𝒚-axis [📷image](../img/Calculus 1 Lecture 5.3/[29-50]-01.png)
     ◉ Problem setup: Volume between two curves around the 𝒚-axis  
     $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot 𝒙\cdot[𝒇_{\text{upper}}(𝒙)−𝒇_{\text{lower}}(𝒙)]\,d𝒙$
          $\rule{0pt}{}$
     ◉ Integration limits:
          ○ $𝒙=𝒙²$
          ○ $𝒙=0$ and $𝒙=1$
     ◉ Identifying the "Top" Function
     $\rule{0pt}{}$
          ○ For $𝒙\in[0,1]$, $𝒇(𝒙)=𝒙$ is on top
          $\rule{0pt}{}$
     ◉ Integration: $\displaystyle \int_{0}^{1}2\pi\cdot 𝒙(𝒙−𝒙²)\,d𝒙$
     $\rule{0pt}{}$
     ◉ Simplification: $2\pi\displaystyle \int_{0}^{1}(𝒙²−𝒙³)\,d𝒙$
     $\rule{0pt}{}$
     ◉ Integration: $2\pi\Big[\dfrac{𝒙³}{3}−\dfrac{𝒙⁴}{4}\Big]_{0}^{1}$
     $\rule{0pt}{}$
     ◉ Evaluating limits: $2\pi\big(\dfrac{1}{3}−\dfrac{1}{4}\big)$
     $\rule{0pt}{}$
     ◉ Final result: Volume $=\dfrac{\pi}{6}$


● [36:25](https://www.youtube.com/watch?v=BDmlottZVd4&t=2185). 🧩 Example – Region bounded by 𝒇(𝒚)=−𝒚²+6𝒚 and 𝓰(𝒚)=0, around the 𝒙-axis [📷image](../img/Calculus 1 Lecture 5.3/[36-25]-01.png)
     ◉ Problem setup: Volume between two curves around the 𝒙-axis  
     $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \int_{\mathcal{a}}^{\mathcal{b}}2\pi\cdot𝒚\cdot[𝒇_{\text{right}}(𝒚)−𝒇_{\text{left}}(𝒚)]\,d𝒚$
          $\rule{0pt}{}$
     ◉ Identifying the "Right" Function
     $\rule{0pt}{}$
          ○ $𝓰(𝒚)=0$ → $𝒙=0$ ⇢ vertical line at $𝒙=0$
          $\rule{0pt}{}$
          ○ $𝒇_{\text{right}}(𝒚)=−𝒚²+6𝒚$
          $\rule{0pt}{}$
     ◉ Integration limits:
     $\rule{0pt}{}$
          ○ $−𝒚²+6𝒚=0$ → $𝒚=0$ and $𝒚=6$
          $\rule{0pt}{}$
     ◉ Integration:
     $\rule{0pt}{}$
          ○ $\mathcal{V}=2\pi\displaystyle\int_{0}^{6}𝒚(−𝒚²+6𝒚)\,d𝒚=2\pi\displaystyle\int_{0}^{6}(−𝒚³+6𝒚²)\,d𝒚$
         $\rule{0pt}{}$
     ◉ Evaluating limits:
     $\rule{0pt}{}$
         ○ $\mathcal{V}=2\pi\Big[−\dfrac{𝒚⁴}{4}+2𝒚³\Big]_{0}^{6}=2\pi\big(−\dfrac{6⁴}{4}+432\big)=216\pi$


● [45:00](https://www.youtube.com/watch?v=BDmlottZVd4&t=2700). 🧩 Example – Cylindrical shells method: Region bounded by 𝒇(𝒙)=𝒙²+1, 𝓰(𝒙)=−𝒙+1, and 𝒙=1, around the 𝒚-axis [📷image](../img/Calculus 1 Lecture 5.3/[45-00]-01.png)
     ◉ Problem Definition
          ○ Find the volume generated by rotating the region bounded by three functions around the 𝒚-axis
          ○ Given functions:
               ■ $𝒇(𝒙)=𝒙²+1$ → Parabola shifted up 1 unit  
               $\rule{0pt}{}$
               ■ $𝓰(𝒙)=−𝒙+1$ → Line with positive slope  
               $\rule{0pt}{}$
               ■ $𝒉(𝒙)=1$ → Vertical boundary
          ○ The region lies in the first quadrant
     ◉ Cylindrical Shells Method Setup
    $\rule{0pt}{}$
          ○ General formula: $\mathcal{V}=\displaystyle\int_{\mathcal{a}}^{\mathcal{b}}2\pi(\text{radius})(\text{height})\,d𝒙$
         $\rule{0pt}{}$
          ○ Radius: distance from 𝒚-axis → $r=𝒙$
          ○ Height: difference between upper and lower functions → $(𝒙²+1)−(−𝒙+1)$
          ○ Integration from $𝒙=0$ to $𝒙=1$
         $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle\int_{0}^{1}2\pi\cdot 𝒙\cdot[(𝒙²+1)−(−𝒙+1)]\,d𝒙$
         $\rule{0pt}{}$
          ○ Simplify: $\mathcal{V}=2\pi\displaystyle\int_{0}^{1}(𝒙³+𝒙²)\,d𝒙=2\pi\Big[\dfrac{𝒙⁴}{4}+\dfrac{𝒙³}{3}\Big]_{0}^{1}=2\pi\big(\dfrac{1}{4}+\dfrac{1}{3}\big)=\dfrac{7\pi}{6}$
         $\rule{0pt}{}$
     ◉ [45:00](https://www.youtube.com/watch?v=BDmlottZVd4&t=2700). 🧩 Example –  Disk/Washer Method: Region bounded by 𝒇(𝒙) = 𝒙² + 1,  𝓰(𝒙) = -𝒙 + 1 and  𝒙 = 𝒉(𝒚) = 1 , around the 𝒚-axis [📷image](../img/Calculus 1 Lecture 5.3/[45-00]-01.png)
          ○ Picture & plan
               ■ Axis: 𝒚-axis ⇒ cross-sections ⟂ to 𝒚 ⇒ **washers** in $𝒅𝒚$.
               ■ Horizontal slice at height $𝑦$ spans from a **left boundary** $𝒙_{\text{left}}(𝑦)$ to the **right wall** $𝒙=1$.
          ○ Express 𝒙 in terms of 𝑦 (for horizontal radii)
          $\rule{0pt}{}$
               ■ From $𝒇(𝒙)=𝒙^{2}+1$:  $𝑦=𝒙^{2}+1 \Rightarrow 𝒙=\pm\sqrt{𝑦-1}$  (take $+\sqrt{\;\,}$ branch for $𝑦\ge 1$)
               $\rule{0pt}{}$
               ■ From $𝓰(𝒙)=-𝒙+1$:  $𝑦=-𝒙+1 \Rightarrow 𝒙=1-𝑦$
               $\rule{0pt}{}$
          ○ 𝑦-interval and piecewise left boundary
          $\rule{0pt}{}$
               ■ Intersections $𝒙^{2}+1=-𝒙+1 \Rightarrow 𝒙(𝒙+1)=0 \;\Rightarrow\;$✳️$(𝒙,𝑦)=(0,1)\text{ and }(-1,2)$
               $\rule{0pt}{}$
               ■ Intersections with the vertical wall $𝒙=1$:
                    ▣ With $𝒇(𝒙)=𝒙^{2}+1$:  at $𝒙=1 \Rightarrow 𝒚=2$ → point $(1,2)$
                    $\rule{0pt}{}$
                    ▣ With $𝓰(𝒙)=-𝒙+1$:  at $𝒙=1 \Rightarrow 𝒚=0$ → point $(1,0)$
                    $\rule{0pt}{}$
                    ▣ Therefore, $𝒙=1$ spans vertically from $𝒚=0$ (line) up to $𝒚=2$ (parabola).
                    $\rule{0pt}{}$
                    ▣ Both curves intersect at ✳️$(0,1)$, which is exactly where the region changes its left boundary.
                    $\rule{0pt}{}$
               ■ Piecewise left boundary (split at $𝒚=1$):
               $\rule{0pt}{}$
                    ▣ For $𝒚\in[0,1]$: left boundary given by the line ⇒ $𝒙_{\text{left}}(𝑦)=1-𝑦$.
                    $\rule{0pt}{}$
                         ▢ Reason: the parabola $𝒚=𝒙^{2}+1$ starts at $𝒚=1$ (no real $𝒙$ for $𝒚<1$).
                         $\rule{0pt}{}$
                    ▣ For $𝒚\in[1,2]$: left boundary given by the parabola ⇒ $𝒙_{\text{left}}(𝑦)=\sqrt{𝑦-1}$.
                    $\rule{0pt}{}$
                         ▢ Check: at $𝒚=1$ both meet at $(0,1)$; for $𝒚>1$, $1-𝒚<0$ (left of 𝒚-axis) while $\sqrt{𝑦-1}\ge 0$.
                         $\rule{0pt}{}$
          ○ Radii w.r.t. the 𝒚-axis ($𝒙=0$)
               ■ Outer radius $\mathcal{R}(𝑦)=$ distance to $𝒙=1$ ⇒ $\mathcal{R}(𝑦)=1$   (for all $𝑦$ in the region).
               $\rule{0pt}{}$
               ■ Inner radius $𝑟(𝑦)=$ distance to $𝒙_{\text{left}}(𝑦)$ ⇒ $𝑟(𝑦)=𝒙_{\text{left}}(𝑦)$.
               $\rule{0pt}{}$
                    ▣ $𝑟(𝑦)=1-𝑦$ for $𝑦\in[0,1]$; \;\; $𝑟(𝑦)=\sqrt{𝑦-1}$ for $𝑦\in[1,2]$.
                    $\rule{0pt}{}$
          ○ Set up the washer integrals
         $\rule{0pt}{}$
               ■ $\displaystyle \mathcal{V}=\pi\int_{0}^{1}\!\big(1-(1-𝑦)^{2}\big)\,𝒅𝑦 \;+\; \pi\int_{1}^{2}\!\big(1-(\sqrt{𝑦-1})^{2}\big)\,𝒅𝑦$
              $\rule{0pt}{}$
                    ▣ First piece: $2𝑦-𝑦^{2}$
                    ▣ Second piece: $2-𝑦$
          ○ Evaluate
          $\rule{0pt}{}$
               ■ $I_{1}=\displaystyle \int_{0}^{1}(2𝑦-𝑦^{2})\,𝒅𝑦=\Big[\,𝑦^{2}-\dfrac{𝑦^{3}}{3}\,\Big]\Big|_{0}^{1}=1-\dfrac{1}{3}=\dfrac{2}{3}$
              $\rule{0pt}{}$
               ■ $I_{2}=\displaystyle \int_{1}^{2}(2-𝑦)\,𝒅𝑦=\Big[\,2𝑦-\dfrac{𝑦^{2}}{2}\,\Big]\Big|_{1}^{2}=(4-2)-\Big(2-\dfrac{1}{2}\Big)=\dfrac{1}{2}$
              $\rule{0pt}{}$
               ■ $\displaystyle \mathcal{V}=\pi\big(I_{1}+I_{2}\big)=\pi\!\left(\dfrac{2}{3}+\dfrac{1}{2}\right)=\dfrac{7\pi}{6}$

