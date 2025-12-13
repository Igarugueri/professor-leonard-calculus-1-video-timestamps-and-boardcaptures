-----------------------------------**Ｃａｌｃｕｌｕｓ １  Ｌｅｃｔｕｒｅ ４．４  Ｔｈｅ  Ｅｖａｌｕａｔｉｏｎ  Oｆ  Ｄｅｆｉｎｉｔｅ  Ｉｎｔｅｇｒａｌｓ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌ　ａｎｄ　ｉｔｓ　ｃｏｎｎｅｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ａｒｅａ

● [0:00](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=0). Introduction to the definite integral and its connection to the concept of area [📷image](../img/Calculus 1 Lecture 4.4/[0-00]-01.png)
$\rule{0pt}{}$
     ◉ AREA  𝒜ₙ = $\displaystyle \lim_{n\to\infty}\sum_{k=1}^{n} 𝒇(x_k^* )\cdot \Delta x$  on $[𝓪,𝓫]$  Equivalent to:
                    $\rule{0pt}{}$
         ○ 𝒜 =$\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx$
                    $\rule{0pt}{}$
     ◉ Indefinite integrals are expressed with “+ $𝓒$” because they represent the family of antiderivatives without a specific bound,
        meaning without defining an exact area. On the other hand, the definite integral, evaluated over an interval $[𝓪,𝓫]$, precisely 
        calculates the net area, $𝒜$, under the curve between those two points, considering both the positive and negative regions depending on 
        their position relative to the 𝒙-axis.
     ◉ [1:44](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=104). Similarity to the calculation of derivatives using limits.
          ○ **Both the derivative and the integral are based on the concept of a limit**: the derivative is defined as the limit of the difference 
             quotient (which measures the instantaneous slope), while the integral is conceived as the limit of the sum of the areas of rectangles 
             (the Riemann sum). In this process, the height of each rectangle can be arbitrarily chosen within its subinterval, and although there are 
             shortcuts for calculating derivatives without always relying on the explicit limit, both concepts share the central idea of approaching an
             exact value through **infinitesimal** sums or differences.
               ■ " Difference quotient" refers to the average rate of change of a function between two nearby points. More concretely, if you have a function 
               $\rule{0pt}{}$
                  𝒇(𝒙), the difference quotient is expressed as $\displaystyle \frac{𝒇(𝒙+h)-𝒇(𝒙)}{h}$
     ◉ Limit of a Sum:
          ○ The interval $[𝓪,𝓫]$ is divided into small partitions. In each partition, an arbitrary point $x_k^*$ is chosen, and a rectangle is formed with height $𝒇(x_k^*)$ and width $\Delta x$.
     ◉ Infinitesimal Rectangles:
          ○ As the number of partitions tends to infinity, the width $\Delta x$ approaches a differential $dx$ (that is, it becomes infinitesimal), allowing the sum of the rectangles to 
             transform into an integral.
     ◉ Analogy with the Derivative:
          ○ Just as the derivative is defined from the change between two infinitesimally close points, the integral sums the areas of rectangles whose widths become progressively smaller.
     ◉ Geometric Interpretation:
          ○ The integral represents the net area (with sign) under the curve $𝒇(𝒙)$ between the limits $𝓪$ and $𝓫$.
     ◉ Flexibility in Partitions:
          ○ Although partitions of equal width can be used to simplify calculations, this is not mandatory; what matters is that, 
             in the limit, all the rectangles become infinitesimally thin.
     ◉ [4:50](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=290). Net signed area:
     $\rule{0pt}{}$
          ○ 𝒜 = $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx$ ⇢ The definite integral is precisely that sum of very small rectangles, so small that, in the limit, it becomes 
          $\rule{0pt}{}$
                     exact. The finer these rectangles are ($\Delta x \rightsquigarrow dx$ As the number of rectangles increases indefinitely: $n\to\infty$), the more accurate the result, allowing us to obtain 
                     the area under the curve $𝒇(𝒙)$ over the interval $[𝓪,𝓫]$.
                     $\rule{0pt}{}$
               ■ Which is equivalent to  𝒜ₙ  = $\displaystyle \lim_{n\to\infty}\sum_{k=1}^{n} 𝒇(x_k^*)\cdot \Delta x$  on $[𝓪,𝓫]$

     



Ｕｓｉｎｇ　ｇｅｏｍｅｔｒｉｃ　ｍｅｔｈｏｄｓ　ｔｏ　ｆｉｎｄ　ｔｈｅ　ａｒｅａ

● [7:00](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=420). 🧩 Example – 1: $\displaystyle \int_{1}^{4} 2\,dx$ [📷image](../img/Calculus 1 Lecture 4.4/[7-00]-01.png)
$\rule{0pt}{}$
     ◉ Integration limits: from 1 to 4.
     ◉ Graph of $𝒇(𝒙)=2$.
          ○ $𝒇(𝒙)=2$ is a constant function (horizontal line).
     ◉ The area under $𝒇(𝒙)=2$ between 1 and 4 corresponds to the integral’s value.
     ◉ Calculating the geometric area of that rectangle.
          ○ Rectangle’s base = 3.
          ○ Rectangle’s height = 2.
     ◉ The rectangle’s area is 6 square units, matching the integral’s value.
     ◉ The rectangular area remains 6 regardless of the partition.

● [9:00](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=540). 🧩 Example – 2: $\displaystyle \int_{-1}^{2} (\;𝒙 + 2\;)\,dx$ [📷image](../img/Calculus 1 Lecture 4.4/[9-00]-01.png)
$\rule{0pt}{}$
     ◉ $𝒇(𝒙)=𝒙+2$.
     ◉ Graph of $𝒇(𝒙)=𝒙+2$.
          ○ The graph starts at $y=2$ with slope $1$.
          ○ The integral represents the area under the line $𝒙+2$.
          ○ Splitting the region into a rectangle and a triangle.
     ◉ Calculating the rectangle’s area.
          ○ Rectangle’s base = 3.
          ○ Rectangle’s height = 1.
          ○ Rectangle’s area = 3.
     ◉ Calculating the triangle’s area.
          ○ Triangle’s base = 3.
          ○ Triangle’s height = 3.
          $\rule{0pt}{}$
          ○ Triangle’s area = $\displaystyle \frac{9}{2}$.
          $\rule{0pt}{}$
     ◉ Total area is the sum of the rectangle’s area and the triangle’s area.
     $\rule{0pt}{}$
          ○ Correcting the computation, total area = $\displaystyle \frac{15}{2}$.


● [12:15](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=735). 🧩 Example – 3: $\displaystyle \int_{0}^{1} \sqrt{\,1-𝒙^{2}\,}\,dx$ [📷image](../img/Calculus 1 Lecture 4.4/[12-15]-01.png)
$\rule{0pt}{}$
     ◉ Identifying the function as the upper half of a circle.
          ○ The definite integral finds area under the function.
          $\rule{0pt}{}$
          ○ Recognizing $𝒇(𝒙)=\sqrt{\,1-𝒙^{2}\,}$ as a semicircle.
     ◉ Semicircle in the upper half-plane.
     ◉ The function is a semicircle of radius 1.
     ◉ Integration limits from 0 to 1.
          ○ The integration limits need not cover the entire domain of the function.
          ○ That area is a quarter circle.
     ◉ Calculating the area of a circle.
          ○ Formula for circle area: $\pi r^{2}$.
          ○ Computing one quarter of a circle.
          $\rule{0pt}{}$
          ○ The area of a quarter circle is $\displaystyle \frac{\pi}{4}$.
          $\rule{0pt}{}$
     ◉ Definite integrals can sometimes be solved using geometric methods.
          ○ Geometry alone, has limitations for more complex functions.
          ○ [15:24](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=924). We require more advanced methods for functions like $𝒙^{3}$ or $𝒙^{2}$.
               ■ Riemann sums as one approach.

   


Ｐｒｏｐｅｒｔｉｅｓ　ｏｆ　ｄｅｆｉｎｉｔｅ　ｉｎｔｅｇｒａｌｓ

● [📷image-1](../img/Calculus 1 Lecture 4.4/[16-40]-01.png) [📷image-2](../img/Calculus 1 Lecture 4.4/[16-40]-02.png)

● [16:40](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1000). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.1:  An integral with identical upper and lower limits is zero.
$\rule{0pt}{}$
     ◉ $\displaystyle \int_{𝓪}^{𝓪} 𝒇(𝒙)\,dx = 0$ (Area under a single point).
     $\rule{0pt}{}$
     ◉ There is no interval over which to integrate.
     ◉ The area under a function over a single point is zero.     
 
● [18:00](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1080). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.2: Reversing the limits of integration changes the sign of the integral.
$\rule{0pt}{}$
     ◉ $\displaystyle \int_{𝓫}^{𝓪} 𝒇(𝒙)\,dx = - \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx$
     $\rule{0pt}{}$
     ◉ This 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 is useful when changing the order of limits during calculations or simplifying expressions 
         involving definite integrals.
     ◉ The integral from b to a is the negative of the integral from $𝓪$ to $𝓫$.
     ◉ The reversed integral represents the area below the 𝒙-axis.   

● [19:20](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1160). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.3: Constants can be factored out of the integral.
$\rule{0pt}{}$
     ◉ $\displaystyle \int_{𝓪}^{𝓫} 𝓬 \cdot 𝒇(𝒙)\,dx = 𝓬 \cdot \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx$

● [19:55](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1195). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.4: The integral of a sum or difference equals the sum or difference of the integrals.
$\rule{0pt}{}$
     ◉ $\displaystyle \int_{𝓪}^{𝓫} \big(𝒇(𝒙) \pm 𝓰(𝒙)\big)\,dx = \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx \pm \int_{𝓪}^{𝓫} 𝓰(𝒙)\,dx$   

● [21:19](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1279). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.5: You can partition the integral across intervals.
$\rule{0pt}{}$
     ◉ $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx = \int_{𝓪}^{𝓬} 𝒇(𝒙)\,dx + \int_{𝓬}^{𝓫} 𝒇(𝒙)\,dx$ and  $𝓪 \le 𝓬 \le 𝓫$
    $\rule{0pt}{}$
     ◉ This interval-splitting 𝒫𝓇𝑜𝓅𝑒𝓇𝓉� only applies to definite integrals.
     ◉ Dividing a single integral into multiple intervals.
     ◉ The total area can be split into smaller areas, breaking the integral into subintervals.
     ◉ The total area is the sum of the areas of the subintervals.
     ◉ The integral from 𝓪 to 𝓫 equals the sum of integrals from a to c and from c to b.
     ◉ Subinterval limits must align appropriately.
 
● [23:16](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1396). 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.6: If the function is positive, the integral is positive (and vice versa).
$\rule{0pt}{}$
     ◉ If $𝒇(𝒙) \ge 0$ for all $𝒙 \in [𝓪,𝓫]$ then $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx \ge 0$
     $\rule{0pt}{}$
          ○ If $𝒇(𝒙)$ is above the 𝒙-axis, the integral is positive
         $\rule{0pt}{}$
     ◉ If $𝒇(𝒙) \le 0$ for all $𝒙 \in [𝓪,𝓫]$ then $\displaystyle \int_{𝓪}^{𝓫} 𝒇(𝒙)\,dx \le 0$
     $\rule{0pt}{}$
          ○ If $𝒇(𝒙)$ is below the 𝒙-axis, the integral is negative

● [28:20](https://www.youtube.com/watch?v=K0ORDCt5Ig0&t=1700). 🧩 Example – Evaluate geometrically: $\displaystyle \int_{0}^{1} \big(4 - 2\sqrt{1-𝒙^{2}}\big)\,dx$  [📷image](../img/Calculus 1 Lecture 4.4/[28-20]-01.png)
$\rule{0pt}{}$
     ◉ Step 1: Split by linearity, aply 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎  4.4.3 and 𝒫𝓇𝑜𝓅𝑒𝓇𝓉𝓎 4.4.4  
    $\rule{0pt}{}$
          ○$\displaystyle \int_{0}^{1} \big(4 - 2\sqrt{1-𝒙^{2}}\big)\,dx \;=$ $\displaystyle \int_{0}^{1} 4\,dx \;-\; 2 \int_{0}^{1} \sqrt{1-𝒙^{2}}\,dx$
        $\rule{0pt}{}$
     ◉ Step 2: First integral (rectangle of width 1 and height 4)
    $\rule{0pt}{}$
          ○$\displaystyle \int_{0}^{1} 4\,dx = 4(1 - 0) = 4$
        $\rule{0pt}{}$
     ◉ Step 3: Second integral (quarter of a unit circle) $y=\sqrt{1-𝒙^{2}}$ is the upper semicircle of $𝒙^{2}+y^{2}=1$.
       $\rule{0pt}{}$
          ○ On $[0,1]$ it traces a quarter circle, whose area is $\displaystyle \frac{\pi}{4}$.
       $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{1} 2\sqrt{1-𝒙^{2}}\,dx = 2 \cdot \left(\frac{\pi}{4}\right) = \frac{\pi}{2}$
       $\rule{0pt}{}$
     ◉ Step 4: Combine
    $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{1} \big(4 - 2\sqrt{1-𝒙^{2}}\big)\,dx = 4 - \frac{\pi}{2}$
