-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．８　Rｅｌａｔｅｄ　Rａｔｅｓ**------------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｒｅｌａｔｅｄ　ｒａｔｅｓ

● [0:00](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=0). Definition and examples.
     ◉ Definition of related rates: how a formula relates to its change over time.
     ◉ Examples:
          ○ Cost as a function of time.
          ○ Profit as a function of time.
          ○ Volume in expansion or contraction as a function of time.
     ◉ Objective of related rates: relating a formula to time.
     



Ｉｎｔｒｏｄｕｃｔｏｒｙ　ｅｘａｍｐｌｅ：　ｃｏｎｅ　ｗｉｔｈ　ｗａｔｅｒ　ｌｅａｋ

● [1:05](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=65). Description and variables. [📷image](../img/Calculus 1 Lecture 2.8/[1-05]-01.png)
     ◉ Description of the problem:
          ○ A cone with a water leak at the bottom.
          ○ The water level in the cone changes over time.
     ◉ Variables to consider:
          ○ Height of the water ($𝒉$).
          ○ Radius of the water surface ($𝒓$).


● [2:45](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=165). Objective: Find the rate of change of the volume of water with respect to time ($\dfrac{d𝓥}{d𝓉}$).


● [3:34](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=214). Considerations:
     ◉ The height ($𝒉$) and radius ($𝒓$) of the water change as the water drains.
     ◉ The volume of water ($𝓥$) depends on $𝒉$ and $𝒓$, and thus also changes over time.


● [4:13](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=253). Steps to Solve the Problem:
     ◉ Step 1: Find a formula that relates the involved variables.
     $\rule{0pt}{}$
          ○ In this case, the formula for the volume of a cone:  $𝓥=\dfrac{\pi}{3}𝒓^{2}𝒉$.
          $\rule{0pt}{}$
     ◉ [5:35]  Step 2: Differentiate the formula implicitly with respect to time ($𝓉$).
          ○ Justification: Volume ($𝓥$), radius ($𝒓$), and height ($𝒉$) are functions of time.
          ○ Use the chain rule to differentiate each variable with respect to $𝓉$, resulting in 
          $\rule{0pt}{}$
              terms like $\dfrac{d𝓥}{d𝓉}$, $\dfrac{d𝒓}{d𝓉}$, and $\dfrac{d𝒉}{d𝓉}$.
              $\rule{0pt}{}$
          ○ Take advantage of Implicit Differentiation
               ■ Why Use Implicit Differentiation in Related Rates.
                    ▣ Many related rates problems present relationships where variables cannot be easily isolated. 
                    ▣ Implicit differentiation allows us to handle these complexities by:
                         ▢ Treating dependent variables (like $𝐲$) as functions of independent variables (like $𝒙$ or $𝓉$).
                         ▢ Applying the chain rule to account for the interdependence of variables.
                              ▲ Example Insight: In the cone with a water leak example, the volume $𝓥$ depends on both the radius $𝒓$ and the height $𝒉$, 
                                   which are themselves **changing over time.** Implicit differentiation facilitates finding how $𝓥$ changes with time 
                                   without needing to isolate $𝒓$ or $𝒉$.


● [8:27](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=507). Interpretation of the Derivative Terms:
$\rule{0pt}{}$
     ◉ $\dfrac{d}{d𝓉}[𝓥]=\dfrac{d}{d𝓉}\!\Big[\dfrac{\pi}{3}𝒓^{2}𝒉\Big]$
     $\rule{0pt}{}$
          ○ $\dfrac{d𝓥}{d𝓉}$: Rate of change of volume with respect to time; $𝓥$ is a function of $𝓉$; describes how the volume is changing with respect to time.
          $\rule{0pt}{}$
          ○ $\dfrac{d𝒓}{d𝓉}$: Rate of change of radius with respect to time; $𝒓$ is a function of $𝓉$; describes how the radius is changing with respect to time.
          $\rule{0pt}{}$
          ○ $\dfrac{d𝒉}{d𝓉}$: Rate of change of height with respect to time; $𝒉$ is a function of $𝓉$; describes how the height is changing with respect to time.
          $\rule{0pt}{}$

● [10:00](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=600). Use of the product rule when differentiating the volume formula.
$\rule{0pt}{}$
     ◉ $\dfrac{d}{d𝓉}[𝓥]=\dfrac{d}{d𝓉}\!\Big[\dfrac{\pi}{3}𝒓^{2}𝒉\Big]$
     $\rule{0pt}{}$
          ○  Differentiate implicitly, as $r$ and $h$ depend on $t$
          $\rule{0pt}{}$
          ○ $\dfrac{d𝓥}{d𝓉}=\dfrac{\pi}{3}\cdot\dfrac{d}{d𝓉}[𝒓^{2}𝒉]$                                  # Constants can be factored out
          $\rule{0pt}{}$
          ○ $\dfrac{d𝓥}{d𝓉}=\dfrac{\pi}{3}\cdot\Big[\,\dfrac{d}{d𝓉}(𝒓^{2})\cdot 𝒉+𝒓^{2}\cdot\dfrac{d𝒉}{d𝓉}\,\Big]$      # Product rule: $\dfrac{d}{d𝓉}[uv]=\dfrac{d}{d𝓉}[u]\cdot v+u\cdot\dfrac{d}{d𝓉}[v]$
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝓉}(𝒓^{2})=2𝒓\cdot\dfrac{d𝒓}{d𝓉}$                             # Chain rule, since $𝒓=𝒓(𝓉)$
               $\rule{0pt}{}$
          ○ $\dfrac{d𝓥}{d𝓉}=\dfrac{\pi}{3}\cdot\Big[\,2𝒓\cdot\dfrac{d𝒓}{d𝓉}\cdot 𝒉+𝒓^{2}\cdot\dfrac{d𝒉}{d𝓉}\,\Big]$     # Substitute the result above
          $\rule{0pt}{}$
          ○ $\dfrac{d𝓥}{d𝓉}=\dfrac{\pi}{3}\Big[\,2𝒓𝒉\cdot\dfrac{d𝒓}{d𝓉}+𝒓^{2}\cdot\dfrac{d𝒉}{d𝓉}\,\Big]$           # This gives the rate of change of volume in terms of rates of $r$ and $h$

                
● [13:33](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=813). Information Needed to Solve the Problem:
     ◉ Value of the radius ($𝒓$) at a given moment.
     ◉ Value of the height ($𝒉$) at a given moment.
     $\rule{0pt}{}$
     ◉ Rate of change of the radius ($\dfrac{d𝒓}{d𝓉}$).
     $\rule{0pt}{}$
     ◉ Rate of change of the height ($\dfrac{d𝒉}{d𝓉}$).
     

● [14:54](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=894). Transition to Simpler Examples to Illustrate the Concept of Related Rates. [📷image](../img/Calculus 1 Lecture 2.8/[14-54]-01.png)
$\rule{0pt}{}$
     ◉ [15:26](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=926). 🧩 Example –: Find $\dfrac{d𝑦}{d𝓉}$ when $𝑦=𝒙^{3}$ at $𝓉=1$
     $\rule{0pt}{}$
          ○ Assume that $𝑦$ and $𝒙$ are functions of time ($𝓉$).
          ○ Differentiate the equation implicitly with respect to $𝓉$, resulting in $\dfrac{d𝑦}{d𝓉}=3𝒙^{2}\cdot\dfrac{d𝒙}{d𝓉}$
               ■ [17:34](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1054). Additional Information Needed!:
                    ▣ Value of $𝒙$ at a given moment (e.g., $𝓉=1$) and value of $\dfrac{d𝒙}{d𝓉}$ at the same moment (e.g., $𝓉=1$).
                    $\rule{0pt}{}$
                         ▢ Find this out: If $𝒙=2$ and $\dfrac{d𝒙}{d𝓉}=4$ at $𝓉=1$.
                         $\rule{0pt}{}$
                              ▲ What is happening at $𝓉=1$?
                              $\rule{0pt}{}$
                                   ◭  $\dfrac{d𝒙}{d𝓉}=4$  "The variable $𝒙$ is changing with respect to time $𝓉$ at a rate of 4 units per unit of time."
                                   $\rule{0pt}{}$
                                   ◭  The actual position is $𝒙=2$
                                   $\rule{0pt}{}$
                    ▣  $\dfrac{d𝑦}{d𝓉}=3\cdot(2)^{2}\cdot 4=3\cdot 4\cdot 4=48$
                    $\rule{0pt}{}$
                         ▢ So, at $𝓉=1$, $\dfrac{d𝑦}{d𝓉}=48$




🧩Ｅｘａｍｐｌｅ：　ｏｉｌ　ｓｐｉｌｌ [📷image](../img/Calculus 1 Lecture 2.8/[19-46]-01.png)

● [19:46](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1186).  Description ad objective of the problem:
     ◉ An oil spill is expanding in a circular shape.
     ◉ The radius of the spill is increasing at a constant rate of 3 feet (0.91 m) per second.
     ◉ Objective: Determine how quickly the area of the spill is increasing when the radius is 30 feet (9.14 m).


● [23:19](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1399). Steps to Solve the Problem:
     ◉ Step 1: Assign letters to the variables:
          ○ $𝓉$ for time.
          ○ $𝓐$ for area.
          ○ $𝒓$ for radius.
     ◉ Step 2: Identify the formula that relates the variables:
          ○ In this case, the area of a circle: $𝓐=\pi 𝒓^{2}$.
     ◉ Step 3: Identify the given rates in the problem:
     $\rule{0pt}{}$
          ○ $\dfrac{d𝒓}{d𝓉}=3$ feet per second (rate of change of the radius).
          $\rule{0pt}{}$
          ○ $\dfrac{d𝓐}{d𝓉}$ rate of change of area
          $\rule{0pt}{}$
    ◉ [27:12](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1632). Step 6: Differentiate the formula implicitly with respect to time ($𝓉$):
    $\rule{0pt}{}$
          ○ $\dfrac{d𝓐}{d𝓉}=2\pi 𝒓\cdot\dfrac{d𝒓}{d𝓉}$
          $\rule{0pt}{}$
     ◉ Step 5: Substitute the known values into the differentiated equation and solve for 
     $\rule{0pt}{}$
      the unknown rate of change ($\dfrac{d𝓐}{d𝓉}$):
      $\rule{0pt}{}$
          ○ $\dfrac{d𝓐}{d𝓉}=2\pi\cdot (30\ \text{feet})\cdot\big(3\ \text{feet/second}\big)=180\pi\ \text{square feet per second}.$
          



🧩Ｅｘａｍｐｌｅ：　ｃａｍｅｒａ　ｆｏｌｌｏｗｉｎｇ　ａ　ｒｏｃｋｅｔ

● [30:18](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1818). Description ad objective of the problem. [📷image-1](../img/Calculus 1 Lecture 2.8/[30-18]-01.png) [📷image-2](../img/Calculus 1 Lecture 2.8/[30-18]-02.png)
     ◉ Description of the problem:
          ○ A rocket is launched from the ground vertically.
          ○ A camera on the ground must follow the rocket by adjusting its elevation angle.
             It is a distance of 3000 feet (0.91 km) from the rocket.
          ○ The rocket ascends at a speed of 600 feet (0.18 km) per second when the rocket is at 4000 feet (1.22 km).
     ◉ Objective: Determine how quickly the elevation angle of the camera must change to keep the rocket centered
         in the frame when the rocket is 4000 feet high.

● [31:43](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1903). Considerations:
     ◉ The height of the rocket ($𝒉$) changes over time.
     ◉ The elevation angle of the camera ($\theta$) must change to follow the rocket.

● [32:29](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=1949). Steps to Solve the Problem:
     ◉ Step 1: Assign letters to the variables:
          ○ $𝓉$ for time.
          ○ $𝒉$ for the height of the rocket.
          ○ $\theta$ for the elevation angle of the camera.
     ◉ Step 2: Find a formula that relates the variables:
     $\rule{0pt}{}$
          ○ Use the tangent function: $\tan(\theta)=\dfrac{𝒉}{3000}$ 
          $\rule{0pt}{}$
             (where $3000$ is the constant horizontal distance between the camera and the launch point).
             $\rule{0pt}{}$
     ◉ [36:30](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=2190). Step 3: Identify the given rates in the problem:
     $\rule{0pt}{}$
          ○ $\dfrac{d𝒉}{d𝓉}=600$ feet (0.18 km) per second (rate of change of the rocket's height) when $𝒉=4000$ feet (1.22 km).
          $\rule{0pt}{}$
          ○ $\dfrac{d\theta}{d𝓉}$ rate of change of angle of the camera.
          $\rule{0pt}{}$
     ◉ [42:32](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=2552). Step 4: Differentiate the formula implicitly with respect to time ($𝓉$):
     $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝓉}\big[\tan(\theta)\big]=\dfrac{d}{d𝓉}\!\Big[\dfrac{1}{3000}\cdot 𝒉\Big]$
          $\rule{0pt}{}$
               ■ $\sec^{2}(\theta)\cdot\dfrac{d\theta}{d𝓉}=\dfrac{1}{3000}\cdot\dfrac{d𝒉}{d𝓉}$
               $\rule{0pt}{}$
     ◉ [44:40](https://www.youtube.com/watch?v=43Qt6wc44To&list=PLF797E961509B4EB5&t=2680). Step 5: Determine the value of $\sec^{2}(\theta)$ when the rocket's height is 4000 feet (1.22 km):
          ○ Use the Pythagorean theorem to calculate the hypotenuse of the right triangle formed by the rocket, the camera, and the ground.
               ■ The rocket is $4{,}000$ feet high.
               $\rule{0pt}{}$
               ■ $\text{hypotenuse}^{2}=4000^{2}+3000^{2}\;\Rightarrow\;\text{hypotenuse}=5000$ feet
               $\rule{0pt}{}$
          ○ Use the definition of secant ($\sec(\theta)=1/\cos(\theta)$) to calculate $\sec(\theta)$.
          $\rule{0pt}{}$
               ■ $\cos(\theta)=\dfrac{3000}{5000}=\dfrac{3}{5}\;\Rightarrow\; \sec(\theta)=\dfrac{5}{3}$
               $\rule{0pt}{}$
     ◉ Step 6: Substitute the known values into the differentiated equation and solve for the unknown rate of change ($\dfrac{d\theta}{d𝓉}$):
     $\rule{0pt}{}$
          ○ $\dfrac{d\theta}{d𝓉}=\dfrac{\big(\dfrac{1}{3000}\big)\big(600\ \text{feet/second}\big)}{\big(\dfrac{5}{3}\big)^{2}}=\dfrac{9}{125}\ \text{radians/second}$ (when the height is $4000$ feet)
          $\rule{0pt}{}$
          ○ Convert the rate of change to degrees per second: $\big(\dfrac{9}{125}\ \text{radians/second}\big)\cdot\dfrac{180^\circ}{\pi}\approx 4.13^\circ/\text{second}$
