-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　２．８　Rｅｌａｔｅｄ　Rａｔｅｓ**------------------------------—





Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　ｔｈｅ　ｃｏｎｃｅｐｔ　ｏｆ　ｒｅｌａｔｅｄ　ｒａｔｅｓ

● [0:00]. Definition and examples.
     ◉ Definition of related rates: how a formula relates to its change over time.
     ◉ Examples:
          ○ Cost as a function of time.
          ○ Profit as a function of time.
          ○ Volume in expansion or contraction as a function of time.
     ◉ Objective of related rates: relating a formula to time.
     


Ｉｎｔｒｏｄｕｃｔｏｒｙ　ｅｘａｍｐｌｅ：　ｃｏｎｅ　ｗｉｔｈ　ｗａｔｅｒ　ｌｅａｋ

● [1:05]. Description and variables.
     ◉ Description of the problem:
          ○ A cone with a water leak at the bottom.
          ○ The water level in the cone changes over time.
     ◉ Variables to consider:
          ○ Height of the water (𝒉).
          ○ Radius of the water surface (𝒓).

● [2:45]. Objective: Find the rate of change of the volume of water with respect to time (𝒅𝓥/𝒅𝓉).

● [3:34]. Considerations:
     ◉ The height (𝒉) and radius (𝒓) of the water change as the water drains.
     ◉ The volume of water (𝓥) depends on 𝒉 and 𝒓, and thus also changes over time.

● [4:13]. Steps to Solve the Problem:
     ◉ Step 1: Find a formula that relates the involved variables.
          ○ In this case, the formula for the volume of a cone:  𝓥  = (π/3)𝒓²𝒉.
     ◉ [5:35]  Step 2: Differentiate the formula implicitly with respect to time (𝓉).
          ○ Justification: Volume (𝓥), radius (𝒓), and height (𝒉) are functions of time.
          ○ Use the chain rule to differentiate each variable with respect to 𝓉, resulting in 
              terms like 𝒅𝓥/𝒅𝓉, 𝒅𝒓/𝒅𝓉, and 𝒅𝒉/𝒅𝓉.
          ○Take advantage of Implicit Differentiation
               ■ Why Use Implicit Differentiation in Related Rates.
                    ▣ Many related rates problems present relationships where variables cannot be easily isolated. 
                    ▣ Implicit differentiation allows us to handle these complexities by:
                         ▢ Treating dependent variables (like 𝐲) as functions of independent variables (like 𝒙 or 𝓉).
                         ▢ Applying the chain rule to account for the interdependence of variables.
                              ▲ Example Insight: In the cone with a water leak example, the volume 𝓥 depends on both the radius 𝒓 and the height 𝒉, 
                                   which are themselves **changing over time.** Implicit differentiation facilitates finding how 𝓥 changes with time 
                                   without needing to isolate 𝒓 or 𝒉.

● [8:27]. Interpretation of the Derivative Terms:
     ◉ 𝒅/𝒅𝓉 [𝓥] = 𝒅/𝒅𝓉 [(π/3)𝒓²𝒉]
          ○ 𝒅𝓥/𝒅𝓉: Rate of change of volume with respect to time; 𝓥 is a function of 𝓉; describes how the volume is changing with respect to time.
          ○ 𝒅𝓻/𝒅𝓉: Rate of change of radius with respect to time; 𝒓 is a function of 𝓉; describes how the radius is changing with respect to time.
          ○ 𝒅𝒉/𝒅𝒕: Rate of change of height with respect to time; 𝒉 is a function of 𝓉; describes how the height is changing with respect to time.

● [10:00]. Use of tthe product rule when Differentiating the Volume Formula.
     ◉ 𝒅/𝒅𝓉 [𝓥] = 𝒅/𝒅𝓉 [(π/3)𝒓²𝒉]
          ○  Differentiate implicitly, as r and h depend on t
          ○ 𝒅𝓥/𝒅𝓉 = (𝜋 / 3) · 𝒅/𝒅𝓉 [𝒓²𝒉]                                  # Constants can be factored out
          ○ 𝒅𝓥/𝒅𝓉 = (𝜋 / 3) · [ 𝒅/𝒅𝓉 (𝒓²) · 𝒉 + 𝒓² · 𝒅𝒉/𝒅𝓉 ]      # Product rule: 𝒅/𝒅𝓉[uv] = 𝒅/𝒅𝓉[u] ∙ v  +  u ∙ 𝒅/𝒅𝓉[v]
               ■ 𝒅/𝒅𝓉 (𝒓²) = 2𝒓 · 𝒅𝒓/𝒅𝓉                                       # Chain rule, since 𝒓 = 𝒓(𝓉)
          ○ 𝒅𝓥/𝒅𝓉 = (𝜋 / 3) · [ 2𝒓 · 𝒅𝒓/𝒅𝓉 · 𝒉 + 𝒓² · 𝒅𝒉/𝒅𝓉 ]    # Substitute the result above
          ○ 𝒅𝓥/𝒅𝓉 = (𝜋 / 3) [ 2𝒓𝒉 · 𝒅𝒓/𝒅𝓉 + 𝒓² · 𝒅𝒉/𝒅𝓉 ]          # This gives the rate of change of volume in terms of rates of r and h
                
● [13:33]. Information Needed to Solve the Problem:
     ◉ Value of the radius (𝒓) at a given moment.
     ◉ Value of the height (𝒉) at a given moment.
     ◉ Rate of change of the radius (𝒅𝒓/𝒅𝓉).
     ◉ Rate of change of the height (𝒅𝒉/𝒅𝓉).

● [14:54]. Transition to Simpler Examples to Illustrate the Concept of Related Rates.
     ◉ [15:26]. 🧩 Example –: Find 𝒅𝑦/𝒅𝓉 when 𝑦 = 𝒙³ at 𝓉 = 1
          ○ Assume that 𝑦 and 𝒙 are functions of time (𝓉).
          ○ Differentiate the equation implicitly with respect to 𝓉, resulting in 𝒅𝑦/𝒅𝓉 = 3𝒙² 𝒅𝒙/𝒅𝓉
               ■ [17:34]. Additional Information Needed!:
                    ▣ Value of 𝒙 at a given moment (e.g., 𝓉 = 1) and value of 𝒅𝒙/𝒅𝓉 at the same moment (e.g., 𝓉 = 1).
                         ▢ Find this out: If 𝒙 = 2 and 𝒅𝒙/𝒅𝓉 = 4 at 𝓉 = 1.
                              ▲ What is happening at 𝓉 = 1?
                                   ◭  𝒅𝒙/𝒅𝓉 = 4  "The variable 𝒙 is changing with respect to time 𝓉 at a rate of 4 units per unit of time."
                                   ◭  The actual position is 𝒙 = 2
                    ▣  𝒅𝑦/𝒅𝓉 = 3·(2)²·4 = 3·4·4 = 48
                         ▢ So, at 𝓉 = 1, 𝒅𝑦/𝒅𝓉 = 48



Ｅｘａｍｐｌｅ：　ｏｉｌ　ｓｐｉｌｌ

● [19:46]. Description ad objective of the problem:
     ◉ An oil spill is expanding in a circular shape.
     ◉ The radius of the spill is increasing at a constant rate of 3 feet (0.91 m) per second.
     ◉ Objective: Determine how quickly the area of the spill is increasing when the radius is 30 feet (9.14 m).

● [23:19]. Steps to Solve the Problem:
     ◉ Step 1: Assign letters to the variables:
          ○ 𝓉 for time.
          ○ 𝓐 for area.
          ○ 𝒓 for radius.
     ◉ Step 2: Identify the formula that relates the variables:
          ○ In this case, the area of a circle: 𝓐 = π𝒓².
     ◉ Step 3: Identify the given rates in the problem:
          ○ 𝒅𝒓/𝒅𝓉 = 3 feet per second (rate of change of the radius).
          ○ 𝒅𝓐/𝒅𝓉 rate of change of area
     ◉ [27:12]. Step 6: Differentiate the formula implicitly with respect to time (𝓉):
          ○ 𝒅𝓐/𝒅𝓉 = 2π𝒓 𝒅𝒓/𝒅𝓉
     ◉ Step 5: Substitute the known values into the differentiated equation and solve for 
      the unknown rate of change (𝒅𝓐/𝒅𝓉):
          ○ 𝒅𝓐/𝒅𝓉 = 2π (30 feet) (3 feet/second) = 180π square feet per second.
          


Ｅｘａｍｐｌｅ：　ｃａｍｅｒａ　ｆｏｌｌｏｗｉｎｇ　ａ　ｒｏｃｋｅｔ

● [30:18]. Description ad objective of the problem.
     ◉ Description of the problem:
          ○ A rocket is launched from the ground vertically.
          ○ A camera on the ground must follow the rocket by adjusting its elevation angle.
             It is a distance of 3000 feet (0.91 km) from the rocket.
          ○ The rocket ascends at a speed of 600 feet (0.18 km) per second when the rocket is at 4000 feet (1.22 km).
     ◉ Objective: Determine how quickly the elevation angle of the camera must change to keep the rocket centered
         in the frame when the rocket is 4000 feet high.

● [31:43]. Considerations:
     ◉ The height of the rocket (𝒉) changes over time.
     ◉ The elevation angle of the camera (θ) must change to follow the rocket.

● [32:29]. Steps to Solve the Problem:
     ◉ Step 1: Assign letters to the variables:
          ○ 𝓉 for time.
          ○ 𝒉 for the height of the rocket.
          ○ θ for the elevation angle of the camera.
     ◉ Step 2: Find a formula that relates the variables:
          ○ Use the tangent function: tan(θ) = 𝒉 / 3000 
             (where 3000 is the constant horizontal distance between the camera and the launch point).
     ◉ [36:30]. Step 3: Identify the given rates in the problem:
          ○ 𝒅𝒉/𝒅𝓉 = 600 feet (0.18 km) per second (rate of change of the rocket's height) when 𝒉 = 4000 feet (1.22 km).
          ○ 𝒅θ/𝒅𝓉 rate of change of angle of the camera.
     ◉ [42:32]. Step 4: Differentiate the formula implicitly with respect to time (𝓉):
          ○ 𝒅/𝒅𝓉 [tan(θ)] = 𝒅/𝒅𝓉 [(1/3000)⋅𝒉]
               ■ sec²(θ) 𝒅θ/𝒅𝓉 = (1/3000) 𝒅𝒉/𝒅𝓉
     ◉ [44:40]. Step 5: Determine the value of sec²(θ) when the rocket's height is 4000 feet (1.22 km):
          ○ Use the Pythagorean theorem to calculate the hypotenuse of the right triangle formed by the rocket, the camera, and the ground.
               ■ The rocket is 4,000 feet high.
               ■ hypotenuse ²  = 4000² + 3000²  ⇢  hypotenuse = 5000 feet
          ○ Use the definition of secant (sec(θ) = 1/cos(θ)) to calculate sec(θ).
               ■ cos(θ) = 3000 / 5000 = 3 / 5 ⇢ sec(θ) = 5 / 3
     ◉ Step 6: Substitute the known values into the differentiated equation and solve for the unknown rate of change (𝒅θ/𝒅𝓉):
          ○ 𝒅θ/𝒅𝓉 = [(1/3000) (600 feet/second)] / (5/3)² = 9/125 radians/second (when the height is 4000 feet)
          ○ Convert the rate of change to degrees per second: (9/125 radians/second) ⋅ (180°/π) ≈ 4.13°/second