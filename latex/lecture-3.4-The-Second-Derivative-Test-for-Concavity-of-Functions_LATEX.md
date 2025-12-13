-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　３．４　Tｈｅ　Sｅｃｏｎｄ　Dｅｒｉｖａｔｉｖｅ　Tｅｓｔ　Fｏｒ　Cｏｎｃａｖｉｔｙ　Oｆ　Fｕｎｃｔｉｏｎｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:16](https://www.youtube.com/watch?v=29GbRaQxtzY&t=16). The second derivative describes how a function’s slope changes, determining whether the curve is concave up or concave down. [📷image](../img/Calculus 1 Lecture 3.4/[0-16]-01.png) 
     ◉ If the second derivative is positive, the slope is increasing, and the curve is concave up.
     ◉ If the second derivative is negative, the slope is decreasing, and the curve is concave down.
     ◉ If $𝒇′′(𝓬)=0$, this is only a possible inflection point (PIP).
          ○ A brief note: to confirm whether an inflection point truly exists, it is necessary to check whether 
              the sign of the second derivative changes on either side of that point.
          ○ If the sign does not change, then there is no real inflection.
           


           
Ｓｅｃｏｎｄ　ｄｅｒｉｖａｔｉｖｅ　ｔｅｓｔ

● [3:21](https://www.youtube.com/watch?v=29GbRaQxtzY&t=201). The second derivative test is used to find inflection points. The steps are: [📷image](../img/Calculus 1 Lecture 3.4/[3-21]-01.png) 
     ❶ Find the function’s second derivative.
     ❷ Set the second derivative equal to zero and solve for $𝒙$. This provides the possible inflection points.
          ○ Additionally, check for points where the second derivative does not exist (due to discontinuities, vertical asymptotes, etc.). 
             These points can also be potential inflection points if the concavity changes.
     ❸ Create a second derivative chart:
          ○ Place the possible inflection points on a number line.
          ○ Evaluate the sign of the second derivative in each interval.
          ○ A positive sign indicates concave up; a negative sign indicates concave down.
          $\rule{0pt}{}$
                                 -----------∣---------------∣-------------
                $𝒇′′(𝒙)$                   ∣                  ∣
                                            PIP₁             PIP₂ . . .
                                         $\rule{0pt}{}$
     ❹ Remember that if  $𝒇′′(𝓬)=0$,  it is only a possible inflection point. To confirm if there is a 
           real change in concavity, you must check the sign of  $𝒇′′(𝒙)$ before and after $𝒙=𝓬$. 
           If there is no change in sign, then there is no true inflection.


● [7:21](https://www.youtube.com/watch?v=29GbRaQxtzY&t=441). The first derivative provides information about relative maxima and minima, while the second 
             derivative provides information about concavity and inflection points.


● [8:00](https://www.youtube.com/watch?v=29GbRaQxtzY&t=480). 🧩 Example –: Find the inflection points of the function  $𝒇(𝒙)=𝒙^4-4𝒙^3+12$ [📷image](../img/Calculus 1 Lecture 3.4/[8-00]-01.png) 
     ❶ Find the first and second derivatives:
     $\rule{0pt}{}$
          ○ $𝒇′(𝒙)=4𝒙^3-12𝒙^2$
          $\rule{0pt}{}$
          ○ $𝒇′′(𝒙)=12𝒙^2-24𝒙$
          $\rule{0pt}{}$
     ❷ Set the second derivative equal to zero and solve for $𝒙$:
     $\rule{0pt}{}$
          ○ $12𝒙^2-24𝒙=0$
          $\rule{0pt}{}$
          ○ $𝒙=0,\; 𝒙=2$
          $\rule{0pt}{}$
     ❸ Create the second derivative chart:
     $\rule{0pt}{}$
                Interval        | Sign of  $𝒇′′(𝒙)$   |    Concavity
          ----------------------------------------------------------------------------
             $(-∞,0)$         |           $+$              | Concave up
             $(0,2)$              |           $-$              | Concave down
             $(2,∞)$            |           $+$              | Concave up
             $\rule{0pt}{}$
                              -----------∣--------------∣------------
            $𝒇′′(𝒙)$                +     ∣         -       ∣     +
                                          0                2
                                          $\rule{0pt}{}$
     ❹ The inflection points are $(0,12)$ and $(2,-4)$.     


● [15:27](https://www.youtube.com/watch?v=29GbRaQxtzY&t=927). 🧩 Example –: Find the inflection points of the function $𝓰(𝒙)=(𝒙-1)^{1/3}$ [📷image](../img/Calculus 1 Lecture 3.4/[15-27]-01.png) 
     ❶  Find the first and second derivatives:
     $\rule{0pt}{}$
          ○ $𝓰′(𝒙)=\dfrac{1}{3}(𝒙-1)^{-2/3}$
          $\rule{0pt}{}$
          ○ $𝓰′′(𝒙)= -\dfrac{2}{9}(𝒙-1)^{-5/3}$
          $\rule{0pt}{}$
     ❷ Identify points where the second derivative is undefined:
          ○ $𝒙=1$
     ❸ Create the second derivative chart:
     $\rule{0pt}{}$
            Interval          | Sign of $𝓰′′(𝒙)$     |   Concavity
        -------------------------------------------------------------------
           $(-∞,1)$         |             $+$             | Concave up
             $(1,∞)$          |             $-$             | Concave down
           $\rule{0pt}{}$
                           -----------∣----------
           $𝒇′′(𝒙)$           +     ∣       -
                                        1
                                       $\rule{0pt}{}$
     ❹ The inflection point is $(1,0)$.




Ｃｏｍｂｉｎｉｎｇ　ｔｈｅ　ｆｉｒｓｔ　ａｎｄ　ｓｅｃｏｎｄ　ｄｅｒｉｖａｔｉｖｅ　ｔｅｓｔｓ

● [24:06](https://www.youtube.com/watch?v=29GbRaQxtzY&t=1446). The first and second derivative tests can be combined to get a complete picture of the function’s behavior.


● [25:10](https://www.youtube.com/watch?v=29GbRaQxtzY&t=1510). 🧩 Example –: Analyze the function $𝒉(𝒙)=𝒙^3-3𝒙^2+24𝒙-32$ [📷image](../img/Calculus 1 Lecture 3.4/[25-10]-01.png) 
     ◉ First Derivative Test: 
          ○ $𝒉′(𝒙)=3𝒙^2-6𝒙+24$
          ○ Critical numbers: $𝒙=-2,\; 𝒙=4$
          ○ First derivative chart:
          $\rule{0pt}{}$
              Interval         |     Sign of $𝒉′(𝒙)$    |   Behavior
           --------------------------------------------------------------
              $(-∞,-2)$    |                $+$             | Increasing
              $(-2,4)$         |                $-$             | Decreasing
              $(4,∞)$          |                $+$             | Increasing 
           $\rule{0pt}{}$
                                            -2             4  
            $𝒇′(𝒙)$               +       ∣       -      ∣     +
                                  ----------∣------------∣--------—
                                  $\rule{0pt}{}$
     ◉ [29:29](https://www.youtube.com/watch?v=29GbRaQxtzY&t=1769). Second Derivative Test: 
          ○ $𝒉′′(𝒙)=6𝒙-6$
          ○ Possible inflection point: $𝒙=1$
          ○ Second derivative chart:
          $\rule{0pt}{}$
              Interval            | Sign of $𝒉′′(𝒙)$   |   Concavity
             -----------------------------------------------------------------
               $(-∞,1)$         |             $-$           | Concave down
               $(1,∞)$            |             $+$           | Concave up
               $\rule{0pt}{}$
                                         -2                      4  
              $𝒇′(𝒙)$             +   ∣           -            ∣     +
                                ---------∣---------∣----------∣-----------
               $𝒇′′(𝒙)$                 -          ∣           + 
                                                      1
                                                   $\rule{0pt}{}$
     ◉ Remember, the second derivative can also help classify critical points from
       the first derivative test:
       $\rule{0pt}{}$
          ○ If $𝒇′(𝓬)=0$ (critical point) and $𝒇′′(𝓬)>0$, there's a relative minimum at $𝒙=𝓬$.
          $\rule{0pt}{}$
          ○ If $𝒇′(𝓬)=0$ and $𝒇′′(𝓬)<0$, there's a relative maximum at $𝒙=𝓬$.
          $\rule{0pt}{}$
          ○ If $𝒇′(𝓬)=0$ and $𝒇′′(𝓬)=0$, the second derivative test is inconclusive, and further analysis is 
             required (e.g., higher-order derivative tests or the first derivative test).
             $\rule{0pt}{}$
     ◉  [31:53](https://www.youtube.com/watch?v=29GbRaQxtzY&t=1913). Combining both tests provides the following information:
          ○ Relative maximum: $(-2,60)$
          ○ Relative minimum: $(4,-48)$
          ○ Inflection point: $(1,6)$




Ｌｉｍｉｔｓ　ａｔ　ｉｎｆｉｎｉｔｙ

● [36:01](https://www.youtube.com/watch?v=29GbRaQxtzY&t=2161). Section 3.5 of the course will address limits at infinity, allowing us to analyze a function’s behavior as $𝒙$ approaches positive or negative infinity.
