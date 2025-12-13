-----------------------------------**Ｃａｌｃｕｌｕｓ １  Ｌｅｃｔｕｒｅ ５．１  Ｆｉｎｄｉｎｇ  Ａｒｅａ  Ｂｅｔｗｅｅｎ  Ｔｗｏ  Ｃｕｒｖｅｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [00:00]. Introduction to finding the area between two curves
     ◉ General idea: A function 𝒇(𝒙) is above another function 𝓰(𝒙) over an interval [𝓪, 𝓫].
          ○ The area between 𝒇(𝒙) and 𝓰(𝒙) is the area under 𝒇(𝒙) minus the area under 𝓰(𝒙).
               ■ The area between two curves is always non-negative. If you get a negative value, something is wrong (ordering or setup).
     ◉ [03:55]. Representation with integrals
          ○ **Area under 𝒇(𝒙) minus area under 𝓰(𝒙):**
               ■ ∫[𝓪,𝓫] 𝒇(𝒙)·𝒅𝒙 − ∫[𝓪,𝓫] 𝓰(𝒙)·𝒅𝒙
                    ▣ ∫[𝓪,𝓫] (𝒇(𝒙) − 𝓰(𝒙))·𝒅𝒙, assuming 𝒇(𝒙) ≥ 𝓰(𝒙) for all 𝒙 ∈ [𝓪,𝓫]
          ○ [05:59]. Important note: For the single-integral formula to work, 𝒇(𝒙) ≥ 𝓰(𝒙) on the entire interval [𝓪, 𝓫]
               ■ 𝒇(𝒙) may touch 𝓰(𝒙), but must not go below it on [𝓪,𝓫]
               ■ If the graphs intersect inside (𝓪,𝓫), split at all intersection points and integrate piecewise, keeping the upper–minus–lower order on each subinterval.
          ○ [09:48]. Relationship with total area
               ■ Generalization: The “area under a curve” is the area between 𝒇(𝒙) and the 𝒙-axis (𝑦=0).
                    ▣ ∫[𝓪,𝓫] (𝒇(𝒙) − 0)·𝒅𝒙  (here 𝓰(𝒙)=0).
               ■ If 𝒇(𝒙) dips below the 𝒙-axis, use absolute value or split at its zeros:
                    ▣ “Above − below” by splitting at 𝓬 where 𝒇(𝓬)=0:
                         ▢ ∫[𝓪,𝓬] (𝒇(𝒙) − 0)·𝒅𝒙 + ∫[𝓬,𝓫] (0 − 𝒇(𝒙))·𝒅𝒙 =
                             = ∫[𝓪,𝓬] 𝒇(𝒙)·𝒅𝒙 − ∫[𝓬,𝓫] 𝒇(𝒙)·𝒅𝒙
                    ▣ Equivalently, the total area is ∫[𝓪,𝓫] |𝒇(𝒙)|·𝒅𝒙.
               ■ Conclusion: “Area between two curves” and “area under a curve” are the same concept with 𝓰(𝒙)=0 as the baseline.




Ｅｘａｍｐｌｅｓ

● [14:40]. 🧩 Example –  Find the area: Bounded above by 𝑦 = 2𝒙 + 5 and below by 𝑦 = 𝒙³ on [0,2]
     ◉ Problem setup: Identify the integration limits and which function is on top.
     ◉ The importance of parentheses when subtracting the two functions with multiple terms.
          ○ if the function below had been 𝓰(𝒙) = 𝒙³+1 note the differenve between:
               ■ ∫[0,2] (2𝒙 + 5) - (𝒙³ + 1) ·𝒅𝒙 and ∫[0,2] (2𝒙 + 5) - 𝒙³+1 ·𝒅𝒙
     ◉ Integrate and evaluate the resulting integral.
          ○ 𝓐 = ∫[0,2] (2𝒙 + 5) - (𝒙³) ·𝒅𝒙
                 = ∫[0,2] (2𝒙 + 5 - 𝒙³) ·𝒅𝒙
                 = [ 𝒙² + 5𝒙 - (𝒙⁴ / 4) ] | [0,2]
             𝓐 = [ 2² + 5·2 - (2⁴ / 4) ] - [ 0 ]
             𝓐 = 10
            
● [24:35]. 🧩 Example – Finding the area between two curves without a given interval: 𝒇(𝒙) = 𝒙², 𝓰(𝒙) = 𝒙 + 6
     ◉ Steps to follow
          ○ [25:10]. 𝒮𝓉ℯ𝓅  1: **Find the intersection points** of the curves.  
               ■ Set 𝒇(𝒙) = 𝓰(𝒙).  
               ■ Solve 𝒙² = 𝒙 + 6 ⟹ (𝒙 - 3)(𝒙 + 2) = 0 ⟹ 𝒙 = -2, 𝒙 = 3.  
               ■ These are the limits of integration.
          ○ [27:18]. 𝒮𝓉ℯ𝓅  2: **Determine which function is on top** in the interval [−2, 3].  
               ■ Test a point (e.g. 𝒙 = 0).  
               ■ 𝒇(0) = 0² = 0, 𝓰(0) = 0 + 6 = 6.  
               ■ Since 𝓰(𝒙) > 𝒇(𝒙), the line 𝒙 + 6 is above the parabola 𝒙².
          ○ [32:00]. 𝒮𝓉ℯ𝓅  3: **Set up and solve the integral**.  
               ■ 𝓐 = ∫[−2,3] (𝓰(𝒙) − 𝒇(𝒙)) ·𝒅𝒙  
                        = ∫[−2,3] (𝒙 + 6 − 𝒙²) ·𝒅𝒙.  
               ■ Compute:  
                    ▣ Antiderivative: ½𝒙² + 6𝒙 − ⅓𝒙³.  
                    ▣ Evaluate: [½(3²) + 6·3 − ⅓(3³)] − [½(−2)² + 6(−2) − ⅓(−2)³].  
                    ▣ Result = 125/6. 

● [38:20]. 🧩 Example – Finding the area between two curves without a given interval: 𝒇(𝒙) = 𝒙³, 𝓰(𝒙) = 𝒙
     ◉ 𝒮𝓉ℯ𝓅  1: Solve 𝒇(𝒙) = 𝒙³ = 𝒙 to find intersection points: −1, 0, 1.
     ◉ 𝒮𝓉ℯ𝓅  2: Test points in each interval to see which function is on top.
          ○ n intervals means n integrals
               ■ For each interval test a point to see which function has the higher value.
                    ▣ In the interval [-1, 0], 𝒙³ > 𝒙
                    ▣ In the interval [0, 1], 𝒙 > 𝒙³
                         ▢ Split the problem into n integrals because the functions cross.
    ◉ 𝒮𝓉ℯ𝓅  3: Set up the two integrals: ∫[−1, 0] (𝒙³ − 𝒙)·𝒅𝒙 + ∫[0, 1] (𝒙 − 𝒙³)·𝒅𝒙
        ○ Antiderivatives:
             ■ ∫ (𝒙³ − 𝒙)·𝒅𝒙 = 𝒙⁴/4 − 𝒙²/2
             ■ ∫ (𝒙 − 𝒙³)·𝒅𝒙 = 𝒙²/2 − 𝒙⁴/4
        ○ Evaluate each piece:
             ■ ∫[−1, 0] (𝒙³ − 𝒙)·𝒅𝒙 = [𝒙⁴/4 − 𝒙²/2]∣[−1,0]
                       = (0 − 0) − (1/4 − 1/2) = 0 − (−1/4) = 1/4
             ■ ∫[0, 1] (𝒙 − 𝒙³)·𝒅𝒙 = [𝒙²/2 − 𝒙⁴/4]∣[0,1]
                       = (1/2 − 1/4) − (0 − 0) = 1/4
       ○ Total area:
             ■ 𝒜 = 1/4 + 1/4 = 1/2
                   



Ａｐｐｌｉｃａｔｉｏｎｓ

● [51:00]. 🧩 Example – Distance between two racing cars.
     ◉ The curves represent each car’s speed as a function of time.
     ◉ The area between the curves represents the distance between the cars.
          ○ The are of each rextangle is 𝓿∙𝓽 = Distance
     ◉ Distance = ∫[𝓪, 𝓫] (Car 1's speed - Car 2's speed)·dt
     ◉ The area shows how far "my" car is ahead of "your" car.
     ◉ If the cars cross paths multiple times, multiple integrals must be set up.
     ◉ The net integral gives the final distance between the cars.

● [1:00:55]. 🧩 Example – Advanced example: Area between 𝒙 = 𝑦² and 𝑦 = 𝒙 - 2 
     ◉ This problem is tricky because it is not expressed in terms of 𝒙 functions.
     ◉ It helps to sketch a graph.
     ◉ If you only find the intersection points, you miss part of the area.
          ○ The parabola 𝒙 = 𝑦² starts at 𝒙 = 0 (vertex at (0,0)).
     ◉ [1:05:00]. Integration with respect to 𝒙 Vs. integration with respect to 𝑦
          ○ 𝑦² = 𝑦 + 2
          ○ Factor the quadratic to find 𝑦-values of the intersection points.
               ■ 𝑦 = -1, 𝑦 = 2
          ○ [1:07:20]. Discussion
               ■ Vertical slices require splitting; horizontal slices do not.
                    ▣ Riemann view: 
                         ▢ Vertical rectangles need two sub-sums ([0,1] & [1,4]); 
                         ▢ Horizontal rectangles need one sub-sum (𝑦∈[−1,2]).
     ◉ Integration with respect to 𝒙
          ○  𝒮𝓉ℯ𝓅  1: Solve both equations for 𝑦 in terms of 𝒙.
               ■ 𝒙 = 𝑦² becomes 𝑦 = ±√𝒙.
               ■ 𝑦 = 𝒙 - 2 remains the same.
                    ▣  Solve for 𝑦: 𝑦² = 𝑦 + 2
                         ▢ ① Obtaining the values 𝑦 = 2 and 𝑦 = -1.
                         ▢ ② Then, substitute these values into the equation 𝒙 = 𝑦² (or 𝒙 = 𝑦 + 2) to find the corresponding 𝒙-values for the integration limits.
                         ▢ ③ Finally, the new limits in terms of 𝒙 will be 𝒙 = 1 and 𝒙 = 4, allowing the integral to be rewritten in terms of 𝒙.
                         ▢ NOTE1: Functions: √𝒙 and -√𝒙  
                                              Domain: 𝒙 ≥ 0  
                                              Set equal: √𝒙 = -√𝒙; 2√𝒙 = 0 → √𝒙 = 0 → 𝒙 = 0  
                                              Intersection point: (0, 0)  
                         ▢ The functions √𝒙 and -√𝒙 intersect only at the origin so 𝒙 = 0 is another integration limit.
                         ▢ Intersections of the two curves: at 𝑦 = -1 → (𝒙,𝑦) = (1, -1); at 𝑦 = 2 → (𝒙,𝑦) = (4, 2).
          ○ 𝒮𝓉ℯ𝓅 2: Test points in each interval to see which function is on top.
               ■ The function 𝒙 = 𝑦² starts at 0 (NOTE1) so there are two intervals [0,1], [1,4] 
                    ▣ 2 intervals means 2 integrals
               ■ [1:12:05]. **Re-draw the graph for clarity of the area zone**.
               ■ Identify the upper and lower functions in each region.
              $\rule{0pt}{}$
                             +√𝒙                +√𝒙
                      ┌───────┬───────┬
                      0                   1                  4
                            -√𝒙                   𝒙 - 2
                            $\rule{0pt}{}$
                    ▣ Check: at 𝒙 = 2 → √2 ≈ 1.414 vs 𝒙 - 2 = 0 ⇒ top is √𝒙; at 𝒙 = 0.25 → √𝒙 = 0.5 and −√𝒙 = −0.5 ⇒ top is √𝒙.
          ○ 𝒮𝓉ℯ𝓅  3: Set up the two integrals:
               ■ [1:17:03]. ∫[0, 1] (√𝒙 - (-√𝒙)) ·𝒅𝒙 + ∫[1, 4] (√𝒙 - (𝒙 - 2)) ·𝒅𝒙
               ■ Evaluation: ∫[0,1] 2𝒙¹ᐟ²·𝒅𝒙 + ∫[1,4] (𝒙¹ᐟ² − 𝒙 + 2)·𝒅𝒙 = 9/2
     ◉ [1:26:40]. Integration with respect to 𝑦 (the best mode).
          ○ Introduction
               ■ **It is easier to integrate with respect to 𝑦** because only two functions are involved,
                   and one is always to the right of the other.
               ■ The formula is similar to integrating with respect to 𝒙, but with 𝒙 and 𝑦 reversed along the 𝑦-axis
                    ▣ Now we have to go from 𝓒 to 𝓓 along the 𝑦-axis over one interval [𝓒, 𝓓]
                    ▣ General idea: A function 𝒇(𝒙) is **on the right** of another function 𝓰(𝒙) over an interval [𝓒, 𝓓]
                         ▢ Note that the right function was the above (top) function on interval [𝓪, 𝓫] when we integrate with respect to 𝒙
               ■ **Set up the equations in terms of 𝑦:** 𝒙 = 𝒉(𝑦), 𝒙 = 𝓰(𝑦).
               ■ [1:29:10]. The area is ∫[𝓒, 𝓓] (𝒉(𝑦) - 𝓰(𝑦)) ·𝒅𝑦 if 𝒉(𝑦) ≥ 𝓰(𝑦) for all 𝑦 in [𝓒, 𝓓]
               ■ Use letters: 𝓒 = −1, 𝓓 = 2.
          ○ 𝒮𝓉ℯ𝓅  1: Solve for 𝑦: 𝑦² = 𝑦 + 2
               ■ Obtaining the values 𝑦 = 2 and 𝑦 = -1.
          ○ 𝒮𝓉ℯ𝓅 2: Determine the integration limits (the 𝑦-values) and which function is on the right and on the left.
               ■ On the right  𝑦 + 2; on the left  𝑦²
                    ▣ Justify right − left on the whole interval: 𝑦² ≤ 𝑦 + 2 ⇔ (𝑦 − 2)(𝑦 + 1) ≤ 0, true for 𝑦 ∈ [−1,2] ⇒ no split needed.
               ■ Continuity note: both curves are continuous; the region is closed and bounded → area via definite integrals applies directly.
               ■ Domain note (for 𝑦 = ±√𝒙): 𝒙 ≥ 0, which explains the vertical left bound 𝒙 = 0 and the split at 𝒙 = 1.
          ○ 𝒮𝓉ℯ𝓅  3: Set up the integral:
               ■ ∫[-1, 2] ( (𝑦 + 2) - 𝑦² ) ·𝒅𝑦
               ■ Evaluation: Antiderivative −𝑦³/3 + 𝑦²/2 + 2𝑦, so area = 9/2

