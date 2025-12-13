-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　４．２　Iｎｔｅｇｒａｔｉｏｎ　Bｙ　Sｕｂｓｔｉｔｕｔｉｏｎ**---------------------------------






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:54](https://www.youtube.com/watch?v=aiBD9aI69C8&t=54). The need for an integral to fit into the integration table.
     ◉ If the integral doesn't fit, it cannot be solved directly.
          ○ The integral must be adjusted in order to fit.
               ■ We aim to manipulate the integral through distribution, division, or trigonometric functions.
     ◉ Intro𝒅𝑢ction to u-substitution, where the letter "$𝑢$" is used.




Ｅｘａｍｐｌｅ　ｏｆ　ａｎ　ｉｎｔｅｇｒａｌ　ｔｈａｔ　ｃａｎｎｏｔ　ｂｅ　ｓｏｌｖｅｄ　ｄｉｒｅｃｔｌｙ　ｕｓｉｎｇ　ｂａｓｉｃ　ｍｅｔｈｏｄｓ．

● [2:14](https://www.youtube.com/watch?v=aiBD9aI69C8&t=134). $\displaystyle \int (𝒙^{2}+1)\cdot 2𝒙\,dx$
$\rule{0pt}{}$
     ◉ Can not fit the integration table but you could do it by distribution.

      
● $\displaystyle \int (𝒙^{2}+1)^{3}\cdot 2𝒙\,dx$
$\rule{0pt}{}$
     ◉ The alternative of “raising it to the third power” repeatedly is a long and complicated process,
              but you could do it by distribution.

              
● 🧩 Example –: $\displaystyle \int (𝒙^{2}+1)^{50}\cdot 2𝒙\,dx$
$\rule{0pt}{}$
     ◉ There is a need for a better way to solve the problem.


● [3:20](https://www.youtube.com/watch?v=aiBD9aI69C8&t=200). Substitution is a method to handle complex integrals.  [📷image](../img/Calculus 1 Lecture 4.2/[3-20]-01.png) 
     ❶ Pick “$𝑢$” so the integral is easier.
          ○ Usually the “inside” of some thing.
          ○ The derivative of “$𝑢$” must be in the $\int$ (disregard constants). In this context, it means that when using
               the substitution method to solve an integral, you can disregard constant factors that appear when differentiating $𝑢$.
     ❷ [6:15](https://www.youtube.com/watch?v=aiBD9aI69C8&t=375). Transform: $\int 𝒙\,dx \;\to\; \int 𝑢\,du$
          ○ The integral must end up in terms of "$𝑢\,du$."
          ○ After the transformation, the integral must match something in the integration table.
          ○ If the integral does not fit in the table, either another substitution is required or it cannot be done by these methods.
          ○ There are integrals that cannot be solved with these methods.
     ❸ Do the integral.
     ❹ Translate back to "$𝒙$".


● [9:30](https://www.youtube.com/watch?v=aiBD9aI69C8&t=570).  🧩 Example (continuation) –:  $\displaystyle \int (𝒙^{2}+1)^{50}\cdot 2𝒙\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[9-30]-01.png) 
     ◉ You must choose a "$u$" whose derivative is present in the integral.
          ○   Constants are not very relevant in the derivative.
     ◉ "$u$" is usually chosen as the interior part.
          ○ $𝑢=𝒙^{2}+1$
     ◉ The derivative of the chosen portion is calculated on both sides.
          ○ $du=2𝒙\,dx$
     ◉ [9:26](https://www.youtube.com/watch?v=aiBD9aI69C8&t=566). Verify that the derivative is in the integral. 
     ◉ "$dx$" is isolated for the substitution.
     $\rule{0pt}{}$
          ○ $du=2𝒙\,dx \;\to\; dx=\dfrac{du}{2𝒙}$
          $\rule{0pt}{}$
     ◉ The substitution is carried out in the original integral.
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝑢^{50}\cdot 2𝒙\cdot \left(\dfrac{du}{2𝒙}\right)$
          $\rule{0pt}{}$
          ○ The interior portion is replaced by "$𝑢$".
          ○ "$dx$" is replaced by its "$du$" equivalent.
     ◉ The integral is simplified after the substitution.
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝑢^{50}\,du$
          $\rule{0pt}{}$
     ◉ The expression is integrated in terms of "$𝑢$".
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝑢^{50}\,du=\dfrac{𝑢^{51}}{51}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ It is stressed that all $𝒙$ terms must vanish before integration.
          ○ You cannot integrate if both "$𝒙$" and "$u$" are present.
          ○ It is reiterated that all "$𝒙$" must disappear prior to integration.
     ◉ Translate back to "$𝒙$"
     $\rule{0pt}{}$
          ○ $\dfrac{𝑢^{51}}{51}+\mathcal{C}\;\to\; \dfrac{(𝒙^{2}+1)^{51}}{51}+\mathcal{C}$




🧩Ｅｘａｍｐｌｅｓ　ｂｙ　ｓｕｂｓｔｉｔｕｔｉｏｎ    ｍｅｔｈｏｄ       

● [17:19](https://www.youtube.com/watch?v=aiBD9aI69C8&t=1039).  $\displaystyle \int 𝒙^{2}\,(𝒙^{3}-4)^{5}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[17-19]-01.png) 
     ◉ $𝑢=𝒙^{3}-4 \;\to\; du=3𝒙^{2}\,dx \;\to\; dx=\dfrac{du}{3𝒙^{2}}$  
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝒙^{2}\cdot 𝑢^{5}\cdot \left(\dfrac{du}{3𝒙^{2}}\right)=\dfrac{1}{3}\int 𝑢^{5}\,du$
     $\rule{0pt}{}$
     ◉ $=\dfrac{1}{3}\cdot\dfrac{𝑢^{6}}{6}+\mathcal{C}$  
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $\dfrac{(𝒙^{3}-4)^{6}}{18}+\mathcal{C}$


● [21:13](https://www.youtube.com/watch?v=aiBD9aI69C8&t=1273).  $\displaystyle \int 𝒙^{2}\,(𝒙^{3}-4)^{5}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[21-13]-01.png) 
     ◉ $𝑢=𝒙^{4} \;\to\; du=4𝒙^{3}\,dx \;\to\; dx=\dfrac{du}{4𝒙^{3}}$  
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 2𝒙^{3}\cdot \sin(𝑢)\cdot \left(\dfrac{du}{4𝒙^{3}}\right)=\dfrac{2}{4}\int \sin(𝑢)\,du$
     $\rule{0pt}{}$
     ◉ $=\dfrac{1}{2}\left(-\cos(𝑢)\right)+\mathcal{C}$  
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":  $-\dfrac{1}{2}\cos(𝒙^{4})+\mathcal{C}$
     

● [27:20](https://www.youtube.com/watch?v=aiBD9aI69C8&t=1640). $\displaystyle \int \left(\dfrac{1}{𝒙^{2}}+\sec^{2}(\pi\cdot 𝒙)\right)\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[27-20]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{1}{𝒙^{2}}\,dx \;+\; \int \sec^{2}(\pi 𝒙)\,dx$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{1}{𝒙^{2}}\,dx=-\dfrac{1}{𝒙}+\mathcal{C}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \sec^{2}(\pi\cdot 𝒙)\,dx$
          ○ $𝑢=\pi\cdot 𝒙 \;\to\; du=\pi\,dx \;\to\; dx=\dfrac{du}{\pi}$
          $\rule{0pt}{}$
     ◉ $\displaystyle \int \sec^{2}(\pi\cdot 𝒙)\,dx=\dfrac{1}{\pi}\int \sec^{2}(𝑢)\,du=\dfrac{1}{\pi}\tan(𝑢)+\mathcal{C}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":  $-\dfrac{1}{𝒙}+\dfrac{1}{\pi}\tan(\pi\cdot 𝒙)+\mathcal{C}$


● [29:00](https://www.youtube.com/watch?v=aiBD9aI69C8&t=1740). $\displaystyle \int \cos(5𝒙)\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[29-00]-01.png) 
$\rule{0pt}{}$
     ◉  $𝑢=5𝒙 \;\to\; du=5\,dx \;\to\; dx=\dfrac{du}{5}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \cos(5𝒙)\,dx=\int \cos(𝑢)\left(\dfrac{du}{5}\right)$
     $\rule{0pt}{}$
     ◉ $\dfrac{1}{5}\int \cos(𝑢)\,du=\dfrac{1}{5}\sin(𝑢)$ 
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":    $\dfrac{1}{5}\sin(5𝒙)+\mathcal{C}$


● [34:50](https://www.youtube.com/watch?v=aiBD9aI69C8&t=2090).  $\displaystyle \int (2𝒙-3)^{15}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[36-46]-02.png) 
     ◉ $𝑢=2𝒙-3 \;\to\; du=2\,dx \;\to\; dx=\dfrac{du}{2}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int (2𝒙-3)^{15}\,dx=\int 𝑢^{15}\left(\dfrac{du}{2}\right)$
     $\rule{0pt}{}$
     ◉ $\dfrac{1}{2}\int 𝑢^{15}\,du=\dfrac{1}{2}\cdot \dfrac{𝑢^{16}}{16}=\dfrac{𝑢^{16}}{32}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":     $\dfrac{(2𝒙-3)^{16}}{32}+\mathcal{C}$


● [36:46](https://www.youtube.com/watch?v=aiBD9aI69C8&t=2206). $\displaystyle \int \left(\dfrac{1}{𝒙^{2}}+\sec^{2}(\pi 𝒙)\right)\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[36-46]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \int [𝒙^{-2}+\sec^{2}(\pi 𝒙)]\,dx$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝒙^{-2}\,dx+\int \sec^{2}(\pi 𝒙)\,dx$
     $\rule{0pt}{}$
     ◉ $𝑢=\pi 𝒙,\; du=\pi\,dx,\; dx=\dfrac{du}{\pi}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝒙^{-2}\,dx+\dfrac{1}{\pi}\int \sec^{2}(𝑢)\,du$
     $\rule{0pt}{}$
     ◉ $-\;𝒙^{-1}+\dfrac{1}{\pi}\int \sec^{2}(𝑢)\,du$
     $\rule{0pt}{}$
     ◉ $-\;𝒙^{-1}+\dfrac{1}{\pi}\tan(𝑢)+\mathcal{C}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $-\;𝒙^{-1}+\dfrac{1}{\pi}\tan(\pi 𝒙)+\mathcal{C}$


● [44:33](https://www.youtube.com/watch?v=aiBD9aI69C8&t=2673). $\displaystyle \int \sin^{2}(𝒙)\,\cos(𝒙)\,dx$  $(𝑢=\cos(𝒙))$ [📷image](../img/Calculus 1 Lecture 4.2/[44-33]-01.png) 
$\rule{0pt}{}$
     ◉ This is an example of choosing the wrong substitution ($𝑢$) in integration. By selecting $𝑢=\cos(𝒙)$, 
         the substitution complicates the integral rather than simplifying it, leading to unnecessary terms or even 
         making it unsolvable in its current form. Always aim to choose $𝑢$ so that it simplifies the integral effectively, 
         often by targeting the "inner" function or a term whose derivative is present elsewhere in the expression.
         $\rule{0pt}{}$
     ◉ $𝑢=\cos(𝒙)$  
     $\rule{0pt}{}$
     ◉ $du=-\sin(𝒙)\,dx$  
     $\rule{0pt}{}$
     ◉ $dx=\dfrac{du}{-\sin(𝒙)}$  
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \sin^{2}(𝒙)\cdot 𝑢\cdot \left(\dfrac{du}{-\sin(𝒙)}\right)\;\; \color{red}{\text{❌}}$


● [47:00](https://www.youtube.com/watch?v=aiBD9aI69C8&t=2820). $\displaystyle \int \sin^{2}(𝒙)\,\cos(𝒙)\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[47-00]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \int \sin^{2}(𝒙)\,\cos(𝒙)\,dx$
     $\rule{0pt}{}$
          ○ $𝑢=\sin(𝒙),\; du=\cos(𝒙)\,dx$
          $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝑢^{2}\,\cos(𝒙)\left(\dfrac{du}{\cos(𝒙)}\right)$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝑢^{2}\,du \;\to\; \dfrac{𝑢^{3}}{3}+\mathcal{C}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":  $\dfrac{\sin^{3}(𝒙)}{3}+\mathcal{C}$ 
     $\rule{0pt}{}$

● [51:25](https://www.youtube.com/watch?v=aiBD9aI69C8&t=3085). $\displaystyle \int \dfrac{\cos(\sqrt{𝒙})}{\sqrt{𝒙}}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[51-25]-01.png) 
$\rule{0pt}{}$
     ◉ $𝑢=\sqrt{𝒙}\;\Rightarrow\; du=\dfrac{1}{2}\,𝒙^{-1/2}\,dx$
     $\rule{0pt}{}$
     ◉ $2\,du=𝒙^{-1/2}\,dx \;\to\; 2\,du=\dfrac{1}{𝑢}\,dx \;\to\; dx=2𝑢\,du \;\; (\text{because } 𝑢=\sqrt{𝒙})$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{\cos(𝑢)}{𝑢}\cdot (2𝑢)\,du \;\to\; 2\int \cos(𝑢)\,du=2\sin(𝑢)+\mathcal{C}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $2\sin(\sqrt{𝒙})+\mathcal{C}$
     $\rule{0pt}{}$

● [1:00:00](https://www.youtube.com/watch?v=aiBD9aI69C8&t=3600). $\displaystyle \int 𝒙^{4}\,\sqrt[3]{\,3-5𝒙^{5}\,}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[1-00-00]-01.png) 
     ◉ $𝑢=3-5𝒙^{5} \;\to\; du=-25𝒙^{4}\,dx \;\to\; dx=\dfrac{du}{-25𝒙^{4}}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 𝒙^{4}\,\sqrt[3]{𝑢}\left(\dfrac{du}{-25𝒙^{4}}\right)$
     $\rule{0pt}{}$
     ◉ $-\dfrac{1}{25}\int 𝑢^{1/3}\,du$
     $\rule{0pt}{}$
     ◉ $-\dfrac{1}{25}\cdot \dfrac{𝑢^{4/3}}{\dfrac{4}{3}}\;=\;-\dfrac{1}{25}\cdot \dfrac{3}{4}\,𝑢^{4/3}$
     $\rule{0pt}{}$
     ◉ $-\dfrac{3}{100}\,𝑢^{4/3}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $-\dfrac{3}{100}\,(3-5𝒙^{5})^{4/3}+\mathcal{C}\;\;\to\;\;-\dfrac{3}{100}\,\sqrt[3]{(3-5𝒙^{5})^{4}}+\mathcal{C}$


● [1:08:40](https://www.youtube.com/watch?v=aiBD9aI69C8&t=4120). $\displaystyle \int 𝒙^{2}\sqrt{\,𝒙-1\,}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[1-08-40]-01.png) 
$\rule{0pt}{}$
     ◉ $𝑢=𝒙-1 \;\to\; 𝒙=𝑢+1 \;\to\; du=dx$
     $\rule{0pt}{}$
     ◉  $\displaystyle \int 𝒙^{2}\sqrt{𝑢}\,du$
     $\rule{0pt}{}$
          ○ $𝒙^{2}=(𝑢+1)^{2}=𝑢^{2}+2𝑢+1$
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{2}\sqrt{𝑢}\,du \;\to\; \int (𝑢^{2}+2𝑢+1)\cdot \sqrt{𝑢}\,du$
          $\rule{0pt}{}$
     ◉ $\displaystyle \int (𝑢^{2}+2𝑢+1)\cdot 𝑢^{1/2}\,du \;\to\; \int \big(𝑢^{5/2}+2𝑢^{3/2}+𝑢^{1/2}\big)\,du$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝑢^{7/2}}{\dfrac{7}{2}}+ 2\,\dfrac{𝑢^{5/2}}{\dfrac{5}{2}}+ \dfrac{𝑢^{3/2}}{\dfrac{3}{2}}$
     $\rule{0pt}{}$
     ◉ $\dfrac{2}{7}𝑢^{7/2}+ \dfrac{4}{5}𝑢^{5/2}+ \dfrac{2}{3}𝑢^{3/2}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$":     $\dfrac{2}{7}(𝒙-1)^{7/2}+ \dfrac{4}{5}(𝒙-1)^{5/2}+ \dfrac{2}{3}(𝒙-1)^{3/2}+\mathcal{C}$
     $\rule{0pt}{}$

● [1:17:40](https://www.youtube.com/watch?v=aiBD9aI69C8&t=4660). $\displaystyle \int \dfrac{2-𝒙}{\sqrt{\,2𝒙^{2}-8𝒙+1\,}}\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[1-17-40]-01.png) 
$\rule{0pt}{}$
     ◉ $𝑢=2𝒙^{2}-8𝒙+1 \;\to\; du=(4𝒙-8)\,dx \;\to\; du=-4(2-𝒙)\,dx \;\to\; dx=\dfrac{du}{-4(2-𝒙)}$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \dfrac{2-𝒙}{\sqrt{𝑢}}\left(\dfrac{du}{-4(2-𝒙)}\right)$
     $\rule{0pt}{}$
     ◉ $-\dfrac{1}{4}\int \dfrac{1}{\sqrt{𝑢}}\,du$
     $\rule{0pt}{}$
     ◉ $-\dfrac{1}{4}\int 𝑢^{-1/2}\,du \;\to\; -\dfrac{1}{4}\cdot \dfrac{𝑢^{1/2}}{\dfrac{1}{2}}$
     ◉ $-\dfrac{1}{2}\,𝑢^{1/2}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $-\dfrac{1}{2}\sqrt{\,2𝒙^{2}-8𝒙+1\,}+\mathcal{C}$


● [1:25:07](https://www.youtube.com/watch?v=aiBD9aI69C8&t=5107).  $\displaystyle \int \cos^{3}(𝒙)\,dx$ [📷image](../img/Calculus 1 Lecture 4.2/[1-25-07]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \int \cos^{3}(𝒙)\,dx \;\to\; \int \big(\cos^{2}(𝒙)\cdot \cos(𝒙)\big)\,dx$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \big[1-\sin^{2}(𝒙)\big]\cos(𝒙)\,dx$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \big[1-(\sin(𝒙))^{2}\big]\cos(𝒙)\,dx$
     $\rule{0pt}{}$
          ○ Pick "$𝑢$" so the integral is easier.
               ■ Usually the "inside" of some thing.
                    ▣ Choosing $u$ as $\sin(𝒙)$ comes from the fact that $\sin(𝒙)$ is "inside" a more complex operation: 
                         the square $(\sin(𝒙))^{2}$.  Furthermore, its derivative, $\cos(𝒙)\,dx$, is present in the integrand, which 
                         simplifies the substitution.
                    ▣ $𝑢=\sin(𝒙)\;\to\; du=\cos(𝒙)\,dx \;\to\; \dfrac{du}{\cos(𝒙)}=dx$
                    $\rule{0pt}{}$
     ◉ $\displaystyle \int \big[1-𝑢^{2}\big]\cos(𝒙)\left(\dfrac{du}{\cos(𝒙)}\right)$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int \big(1-𝑢^{2}\big)\,du$
     $\rule{0pt}{}$
     ◉ $\displaystyle \int 1\,du-\int 𝑢^{2}\,du \;\to\; 𝑢-\dfrac{𝑢^{3}}{3}$
     $\rule{0pt}{}$
     ◉ Translate back to "$𝒙$": $\sin(𝒙)-\dfrac{\sin^{3}(𝒙)}{3}+\mathcal{C}$
