----------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．５　Fｉｎｄｉｎｇ　Dｅｒｉｖａｔｉｖｅｓ　Oｆ　Tｒｉｇｏｎｏｍｅｔｒｉｃ　Fｕｎｃｔｉｏｎｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ　ａｎｄ　ｍｏｔｉｖａｔｉｏｎ

● [0:08](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=8). Introduction to trigonometric functions and their importance in later calculus courses.

● [0:53](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=53). Presentation of two fundamental concepts necessary for the demonstration:
$\rule{0pt}{}$
     ◉ Trigonometric identity:  $\displaystyle \lim_{h\to 0}\dfrac{\sin(h)}{h}=1$.
     $\rule{0pt}{}$
     ◉ Trigonometric identity:  $\displaystyle \lim_{h\to 0}\dfrac{1-\cos(h)}{h}=0$.

    

Ｄｅｍｏｎｓｔｒａｔｉｏｎ　ｏｆ　ｔｈｅ　ｄｅｒｉｖａｔｉｖｅ　ｏｆ　ｔｈｅ　ｓｉｎｅ　ｆｕｎｃｔｉｏｎ

● [2:07](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=127). Objective: find the derivative of $𝑓(𝒙)=\sin(𝒙)$, denoted as $𝑓'(𝒙)$. [📷image-1](../img/Calculus 1 Lecture 2.5/[2-07]-01.png) [📷image-2](../img/Calculus 1 Lecture 2.5/[2-07]-02.png)
     ◉ Reminder of the concept of derivative as a limit:
     $\rule{0pt}{}$
          ○ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{𝑓(𝒙+h)-𝑓(𝒙)}{h}$ 

    
● [2:55](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=175). Application of the limit concept to the sine function:
     ◉ $𝑓(𝒙)=\sin(𝒙)$.
     ◉ $𝑓(𝒙+h)=\sin(𝒙+h)$.
     ◉ Restriction: the expression $𝒙+h$ inside the sine function cannot 
         be separated without using trigonometric identities.
        
● [3:32](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=212). First step of the demonstration:
$\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{\sin(𝒙+h)-\sin(𝒙)}{h}$ 
    
● [5:00](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=300). Use of the angle sum trigonometric identity for sine:
     ◉ $\sin(𝒙+h)=\sin(𝒙)\cdot \cos(h)+\cos(𝒙)\cdot \sin(h)$
     $\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{\sin(𝒙)\cdot \cos(h)+\cos(𝒙)\cdot \sin(h)-\sin(𝒙)}{h}$


● [5:55](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=355). Reorder the expresion
$\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\dfrac{\sin(𝒙)\cdot \cos(h)-\sin(𝒙)+\cos(𝒙)\cdot \sin(h)}{h}$ 

● [6:40](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=400). Separation of the expression into two fractions with denominator $h$.
$\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\left(\dfrac{\sin(𝒙)\cdot \cos(h)-\sin(𝒙)}{h}\right)+\left(\dfrac{\cos(𝒙)\cdot \sin(h)}{h}\right)$
     
● [7:15](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=435). Factoring out $\sin(𝒙)$ in the first term and $\displaystyle \lim_{h\to 0}$ the second term.
$\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\Big(\sin(𝒙)\cdot \dfrac{\cos(h)-1}{h}\Big)+\Big(\cos(𝒙)\cdot \dfrac{\sin(h)}{h}\Big)$ 
     $\rule{0pt}{}$
          ○ Algebraic manipulation to obtain the known trigonometric limits:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{h\to 0}\dfrac{\sin(h)}{h}=1$ 
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{h\to 0}\dfrac{1-\cos(h)}{h}=0$ 
               $\rule{0pt}{}$
                    ▣ Factoring ‘$-1$’ from the first term (we reverse $\cos(h)-1$):
                    $\rule{0pt}{}$
                         ▢ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\Big(-\sin(𝒙)\cdot \dfrac{1-\cos(h)}{h}\Big)+\Big(\cos(𝒙)\cdot \dfrac{\sin(h)}{h}\Big)$ 
                         
● [9:35](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=575). Application of the limits and simplification to obtain the derivative of sine:
$\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\displaystyle \lim_{h\to 0}\Big(-\sin(𝒙)\cdot 0\Big)+\Big(\cos(𝒙)\cdot 1\Big)$ 
     $\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=0+\cos(𝒙)$
     $\rule{0pt}{}$
     ◉ $𝑓'(𝒙)=\cos(𝒙)$ or $\dfrac{d}{d𝒙}\big[\sin(𝒙)\big]=\cos(𝒙)$
    
● [11:15](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=675). Interpretation: the derivative of the sine function is the cosine function, meaning 
                 that the slope of the sine curve at any point is equal to the value of the cosine at that point.

                 

Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　ｏｔｈｅｒ　ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｆｕｎｃｔｉｏｎｓ

● [12:50](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=770).**Presentation of the derivatives of the six main trigonometric functions:** [📷image](../img/Calculus 1 Lecture 2.5/[12-50]-01.png)
$\rule{0pt}{}$
     ○ 1. $\dfrac{d}{d𝒙}\big[\sin(𝒙)\big]=\cos(𝒙)$.
    $\rule{0pt}{}$
     ○ 2. $\dfrac{d}{d𝒙}\big[\cos(𝒙)\big]=-\sin(𝒙)$.
    $\rule{0pt}{}$
     ○ 3. $\dfrac{d}{d𝒙}\big[\tan(𝒙)\big]=\sec^{2}(𝒙)$.
    $\rule{0pt}{}$
     ○ 4. $\dfrac{d}{d𝒙}\big[\sec(𝒙)\big]=\sec(𝒙)\tan(𝒙)$.
    $\rule{0pt}{}$
     ○ 5. $\dfrac{d}{d𝒙}\big[\csc(𝒙)\big]=-\csc(𝒙)\cot(𝒙)$.
    $\rule{0pt}{}$
     ○ 6. $\dfrac{d}{d𝒙}\big[\cot(𝒙)\big]=-\csc^{2}(𝒙)$.

    
● [13:41](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=821). The derivatives of tangent, secant, cosecant, and cotangent can be obtained using 
                 the quotient rule and the derivatives of sine and cosine.
                 
● [16:17](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=977). Observation on the relationships between the derivatives of trigonometric functions,
                 which can help in memorizing them.
                 



Ｅｘａｍｐｌｅｓ　ｏｆ　ａｐｐｌｙｉｎｇ　ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｄｅｒｉｖａｔｉｖｅｓ

● [19:08](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=1148). 🧩 Example – 1: Find the derivative of $𝐲=𝒙\cdot \sin(𝒙)$. [📷image](../img/Calculus 1 Lecture 2.5/[19-08]-01.png)
     ◉ Identification of the need to use the product rule.
     ◉ Application of the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\big[𝒙\cdot \sin(𝒙)\big]=\Big(\dfrac{d}{d𝒙}[𝒙]\cdot \sin(𝒙)\Big)+\Big(𝒙\cdot \dfrac{d}{d𝒙}[\sin(𝒙)]\Big)$.
          $\rule{0pt}{}$
     ◉ Simplification to obtain the derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\big[𝒙\cdot \sin(𝒙)\big]=\sin(𝒙)+𝒙\cdot \cos(𝒙)$.
          $\rule{0pt}{}$
     ◉ Interpretation: the obtained expression represents the slope function for 
        the curve $𝐲=𝒙\cdot \sin(𝒙)$.


● [21:35](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=1295). 🧩 Example – 2: Find the equation of the tangent line to the curve $𝐲=𝒙\cdot \sin(𝒙)$ at the point $𝒙=\pi/2$. [📷image](../img/Calculus 1 Lecture 2.5/[21-35]-01.png)
     ◉ Requirements for the equation of a line: a point and the slope.
     ◉ Obtaining the slope $(m)$ at $𝒙=\pi/2$:
          ○ $m=\sin(𝒙)+𝒙\cdot \cos(𝒙)$.
               ■ $m=\sin(\pi/2)+(\pi/2)\cdot \cos(\pi/2)=1$.
     ◉ Obtaining the point $(\pi/2,𝐲)$ by substituting $𝒙=\pi/2$ into the original equation:
          ○ $𝐲=(\pi/2)\cdot \sin(\pi/2)=\pi/2$.
     ◉ Use of the point-slope formula $𝐲-𝐲_{1}=m(𝒙-𝒙_{1})$ to obtain the equation of the tangent line.
          ○ $𝐲-\pi/2=1(𝒙-\pi/2)\;\rightarrow\;𝐲=𝒙$

          
● [26:20](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=1580). 🧩 Example – 3: Find the derivative of $𝐲=\dfrac{\sin(𝒙)}{1+\cos(𝒙)}$. [📷image](../img/Calculus 1 Lecture 2.5/[26-20]-01.png)
     ◉ Identification of the need to use the quotient rule.
     ◉ Application of the quotient rule:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\Big[\dfrac{\sin(𝒙)}{1+\cos(𝒙)}\Big]=\dfrac{\Big(\dfrac{d}{d𝒙}[\sin(𝒙)]\cdot (1+\cos(𝒙))\Big)-\Big(\sin(𝒙)\cdot \dfrac{d}{d𝒙}[1+\cos(𝒙)]\Big)}{(1+\cos(𝒙))^{2}}$.
          $\rule{0pt}{}$
     ◉ Calculation of individual derivatives and simplification.
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\Big[\dfrac{\sin(𝒙)}{1+\cos(𝒙)}\Big]=\dfrac{\cos(𝒙)\cdot (1+\cos(𝒙))-\sin(𝒙)\cdot \big(-\sin(𝒙)\big)}{(1+\cos(𝒙))^{2}}$
          $\rule{0pt}{}$
              $\dfrac{\cos(𝒙)+\overbrace{\cos^{2}(𝒙)+\sin^{2}(𝒙)}^{=\,1}}{(1+\cos(𝒙))^{2}}$
          $\rule{0pt}{}$
     ◉ [31:42](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=1902). Use of the trigonometric identity $\cos^{2}(𝒙)+\sin^{2}(𝒙)=1$ to simplify the expression.
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\Big[\dfrac{\sin(𝒙)}{1+\cos(𝒙)}\Big]=\dfrac{\cos(𝒙)+1}{(1+\cos(𝒙))^{2}}$
          $\rule{0pt}{}$
     ◉ Additional simplification to obtain the derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\Big[\dfrac{\sin(𝒙)}{1+\cos(𝒙)}\Big]=\dfrac{1}{1+\cos(𝒙)}$.


● [33:40](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=2020). 🧩 Example – 4: Calculation of higher-order derivatives for the function $\sin(𝒙)$. [📷image](../img/Calculus 1 Lecture 2.5/[33-40]-01.png)
     ◉ Calculation of the second, third, and fourth derivatives of $\sin(𝒙)$.
     $\rule{0pt}{}$
          ○ First derivative: $\dfrac{d𝑦}{d𝑥}=\cos(𝑥)$
          $\rule{0pt}{}$
          ○ Second derivative: $\dfrac{d^{2}𝑦}{d𝑥^{2}}=-\sin(𝑥)$
          $\rule{0pt}{}$
          ○ Third derivative: $\dfrac{d^{3}𝑦}{d𝑥^{3}}=-\cos(𝑥)$
          $\rule{0pt}{}$
          ○ Fourth derivative: $\dfrac{d^{4}𝑦}{d𝑥^{4}}=\sin(𝑥)$
          $\rule{0pt}{}$
     ◉ Observation on the cyclical nature of the derivatives of the sine function.
     ◉ [35:15](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=2115). Variable sustitution [📷image](../img/Calculus 1 Lecture 2.5/[33-40]-02.png)
          ○ Evaluate the second derivative at $𝑥=\pi/2$:
          $\rule{0pt}{}$
          ■ $\left.\dfrac{d^{2}𝑦}{d𝑥^{2}}\right|_{𝑥=\pi/2}=-\sin(𝑥)\Big|_{𝑥=\pi/2}=-\sin(\pi/2)=-1$
          $\rule{0pt}{}$
     ◉ [35:45](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=2145). Graphical Relationship between $\sin(𝑥)$ and Its Derivatives
          ○ The function $𝑦=\sin(𝑥)$ exhibits periodic behavior. To understand the relationship between $\sin(𝑥)$ and its derivatives, 
              we can analyze both the graph of $\sin(𝑥)$ and the slopes (derivatives) at various points.
          ○ If we draw the tangent lines to the graph of $\sin(𝑥)$ at several key points, and then plot the **value of the slope** at each of those points, 
             we obtain the graph of $\cos(𝑥)$, since the derivative of $\sin(𝑥)$ is $\cos(𝑥)$.
          ○ This process can be repeated:
               ■ The derivative of $\cos(𝑥)$ is $-\sin(𝑥)$.
               ■ The derivative of $-\sin(𝑥)$ is $-\cos(𝑥)$.
               ■ The derivative of $-\cos(𝑥)$ is $\sin(𝑥)$.
          ○ **Observation:** After four derivatives, the function returns to its original form ($\sin(𝑥)$), confirming the periodicity and oscillatory nature of sine and cosine functions.
          ○ **Key idea:** The slope of the curve at each point on $\sin(𝑥)$ directly corresponds to the value of $\cos(𝑥)$ at that same $𝑥$.
             If you plot all these slopes, you reconstruct the $\cos(𝑥)$ curve.
          ○ This explains why the graphs of $\sin(𝑥)$, $\cos(𝑥)$, $-\sin(𝑥)$, and $-\cos(𝑥)$ are all phase-shifted versions of each other, and why they oscillate back and forth, 
            always returning to the original position after four derivatives

          
● [39:45](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=2385). 🧩 Example – 5 (verbal problem): Modeling the motion of a spring with a mass.
     ◉ Description of the problem: a spring with a mass is stretched $3$ cm from its 
         resting position and released, oscillating without friction.
     ◉ Modeling the position of the spring with a cosine function: 
          ○ Is the reflection of the 'normal' cosine so it is negative.
          ○ $𝐲(𝒕)=-3\cdot \cos(𝒕)$.
     ◉ Objective: find the velocity function of the spring.
     ◉ Relationship between velocity and position: velocity is the derivative of position.
          ○ **Observation:** The velocity is $0$ where the **slope is parallel to the x-axis**
     ◉ Calculation of the derivative of the position function:
          ○ $𝐲'(𝒕)=3\cdot \sin(𝒕)$.
     ◉ Possible additional questions about the problem:
          ○ Find the points where the velocity is zero.
          ○ Find the equation of the tangent line at a specific point.

        


Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｈａｉｎ　ｒｕｌe

● [45:58](https://www.youtube.com/watch?v=qr1WXiq3S3k&list=PLF797E961509B4EB5&t=2758). Introduction to the chain rule. [📷image](../img/Calculus 1 Lecture 2.5/[45-58]-01.png)
     ◉ Presentation of examples of derivatives that can be calculated _without the chain rule_:
          ○ $\dfrac{d}{d𝒙}\big[3𝒙^{2}\cdot 4\big]$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\big[(3𝒙^{2}\cdot 4)^{2}\big]$; you can apply the product rule or expand, then differentiate.
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\big[(3𝒙^{2}\cdot 4)^{3}\big]$; still doable, but becomes tedious.
          $\rule{0pt}{}$
     ◉ Presentation of examples of derivatives that are difficult to calculate _without the chain rule_:
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\big[(3𝒙^{2}\cdot 4)^{100}\big]$
          $\rule{0pt}{}$
     ◉ **Description of the utility of the chain rule:**
          ○ The chain rule provides a systematic and efficient method for finding the derivative of composite functions, especially when 
              direct expansion or repeated use of the product rule becomes impractical. It is essential for handling functions of the form $𝒇(𝗀(𝒙))$, 
              where one function is nested inside another.
               ■ The chain rule is a fundamental technique for differentiating composite functions. It allows us to find the derivative of a 
                  function inside another function by differentiating the outer function (leaving the inner unchanged) and multiplying by the derivative
                  of the inner function. This method is essential when direct expansion is impractical or impossible, and it is widely used in real-world 
                  problems where functions are nested—such as in physics, engineering, and economics.
                  $\rule{0pt}{}$
                ■ In symbols: $\dfrac{d}{d𝒙}\big[𝒇(𝗀(𝒙))\big]=𝒇'\!\big(𝓰(𝒙)\big)\cdot 𝓰'(𝒙)$
