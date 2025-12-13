-----------------------------------**Ｃａｌｃｕｌｕｓ １ Ｌｅｃｔｕｒｅ ０．１ Ｌｉｎｅｓ， Λｎｇｌｅ ｏｆ Ｉｎｃｌｉｎａｔｉｏｎ， ａｎｄ ｔｈｅ Ｄｉｓｔａｎｃｅ Ｆｏｒｍｕｌａ**------------------------------—




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01]. Introduction
     ◉ Review of Math 2 concepts and basic algebra needed for Calculus.
     ◉ Topics to cover:
          ○ Basic lines.
          ○ Families of curves.
          ○ Trigonometric functions.
          ○ Introduction to Calculus.



 Ｌｉｎｅｓ

● [0:34]. Lines 
     ◉ What is special about a line?
          ○ You need at least two points to define a line.
          ○ Lines do not curve.
          ○ Lines do not end.
          ○ Lines have slope.
     ◉ [1:03]. What do we need to graph a line?
          ○ Two points or . . .
          ○ . . . One point and the slope
     ◉ [1:10]. **Slope of a Line**
          ○ The slope describes how a line rises or falls.
          ○ Deriving the slope formula:
               ■ Take two generic points on a line: (𝒙₁, 𝒚₁) and (𝒙₂, 𝒚₂).
               ■ Coordinates of a point (𝒙, 𝒚).
               ■ Distinguishing two points using subscripts.
               ■ Calculating the “run” (change in 𝒙): 𝒙₂ - 𝒙₁.
               ■ Calculating the “rise” (change in 𝒚): 𝒚₂ - 𝒚₁.
               ■ [3:30]. Defining the slope (𝒎) as rise over run: 
                    ▣ 𝒎 = (𝒚₂ - 𝒚₁) / (𝒙₂ - 𝒙₁).
                         ▢ The formula works for any pair of points on the line.
     ◉ [5:39]. **Equation of a Line from the Slope Formula**
           ○ Manipulating the slope formula to get the equation of a line.
           ○ Fix one point (𝒙₁, 𝒚₁) and let the other point be variable (𝒙, 𝒚).
           ○ Substituting into the slope formula: 𝒎 = (𝒚 - 𝒚₁) / (𝒙 - 𝒙₁).
           ○ The resulting equation allows solving for 𝒚 when a value for 𝒙 is provided.
           ○ Isolating (𝒚 - 𝒚₁)
           ○ [8:05]. **Point-Slope Form of a Line’s Equation**
                 ■ 𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁).
                 ■ Called point-slope form because you need one point (𝒙₁, 𝒚₁) and the slope (𝒎) to define it.
     ◉ [9:40]. 🧩 Example – Finding a Line’s Equation Given Two Points:  (-2,-3) and (8,2)  and (8,2).png)
           ○ Necessary steps:
                ■ We need one point (we have two).
                ■ We need the slope (we must calculate it).
           ○ Calculating the slope using the two given points.
                 𝒎 =  2 - (-3)) / (8 - (-2)) = 5 / 10
                 𝒎 = 1/2
           ○ Using the point-slope form to find the equation.
                 𝒚 - (-3) = (1/2)(𝒙 - (-2));
                 𝒚 + 3 = (1/2)(𝒙 + 2);
                 𝒚 + 3 = (1/2)𝒙 + 1
                 𝒚 = (1/2)𝒙 - 2
           ○ [15:10]. **Slope-Intercept Form of a Line’s Equation**
                ■ Transforming the point-slope form to slope-intercept form 
                     ▣ (𝒚 = 𝒎𝒙 + 𝒃).
                ■ Identifying the slope (𝒎) and the 𝒚-intercept (𝒃).
                ■ 🧩 Example – Graphing using slope-intercept form.
                ■ Interpretation of positive or negative slope.
                ■ Two points define a unique line.
                     ▣ 𝒚 = (1/2)𝒙 - 2;  
                          ▢ 𝒃=-2 point (0,-2)
                          ▢ 𝒎 = 1/2; from (0,2) one unit up (rise) ⇡ and two units to he right ⇢ (run)
                               ▲ (-1,2) is the second  point
     ◉ [17:24]. **Special Types of Lines** 
          ○ [17:46]. Horizontal lines: 𝒚 = 𝒄 (where 𝒄 is a constant).
               ■ Intersects the 𝒚-axis at 𝒄.
               ■ Slope is zero.
          ○ [18:45]. Vertical lines: 𝒙 = 𝒄 (where 𝒄 is a constant).
               ■ Intersects the 𝒙-axis at 𝒄.
               ■ Slope is undefined.
     ◉ [19:50]. **Standard Form of a Line’s Equation** 
          ○ [21:52]. 🧩 Example – Converting from standard form to slope-intercept form by isolating 𝒚: 4𝒙 +2𝒚-3 =0  →  𝒚 = 𝒎𝒙 + 𝒃
               ■ Start from the standard form
                    ▣ 4𝒙 + 2𝒚 − 3 = 0
               ■ Move the constant term to the other side
                    ▣ 4𝒙 + 2𝒚 = 3
               ■ Divide each term by −2 to isolate 𝒚
                    ▣ (4𝒙 − 3)/−2 = −2𝒙 + 3/2 = 𝒚
               ■ Final slope–intercept form
                    ▣ 𝒚 = −2𝒙 + 3/2
                         ▢ Here, slope 𝒎 = −2 and intercept 𝒃 = 3/2
          ○ [22:02]. **Cover-Up Method for Graphing from Standard Form**
               ■ To find the 𝒙-intercept, cover the term with 𝒚.
               ■ To find the 𝒚-intercept, cover the term with 𝒙.
               ■ 🧩 Example –: 3𝒙 + 4𝒚 = 4 (𝒙-intercept at 4/3, 𝒚-intercept at 1).
          ○ [23:02]. **Parallel Lines**
               ■ Have the same slope.
               ■ Stair analogy: both rise or fall at the same rate, never intersecting.
                    ▣ Algebraic condition for parallelism:
                         ▢ Two lines 𝑦 = 𝒎₁𝑥 + 𝒃₁ and 𝑦 = 𝒎₂𝑥 + 𝒃₂ are parallel if and only if 𝒎₁ = 𝒎₂, but 𝒃₁ ≠ 𝒃₂.
                         ▢ Different intercepts (𝒃₁, 𝒃₂) shift the lines vertically without changing their slope.
               ■ Geometric interpretation: equal slope ⇒ same inclination angle with respect to the 𝒙-axis.
         ○ [23:39]. **Perpendicular Lines**
               ■ Intersect at a right angle (90°).
               ■ If one slope is positive, the other is negative.
               ■ Their slopes are negative reciprocals of each other.
                    ▣ Algebraic condition for perpendicularity:
                         ▢ 𝒎₁ · 𝒎₂ = −1.
                              ▲ Example: if 𝒎₁ = 2, then 𝒎₂ = -1/2
                    ▣ Special case (vertical and horizontal lines):
                         ▢ A vertical line (undefined slope) and a horizontal line (slope = 0) are perpendicular even though 𝒎₁ · 𝒎₂ ≠ −1 (since one slope is undefined).
                    ▣ Visual cue: perpendicular lines form a “T” or “L” shape where they intersect.
          ○ [25:24]. 🧩 Example – Finding the Equation of a Line Parallel to:  2𝒙 +3𝒚 = 12 passing through the point (6,7) .png)
               ■ Identify the slope of the given line (in slope-intercept form).
                   2𝒙 + 3𝒚 = 12;
                   3𝒚 = -2𝒙 + 12; 
                   𝒚 = (-2/3)𝒙 + 4 
               ■ The slope of the parallel line is the same: 𝒎 = -2/3
               ■ Use the point-slope form with the point (6,7)  and the parallel slope.
               ■ Convert to slope-intercept form.
                   𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁); 
                   𝒚 - 7 = (-2/3)(𝒙- 6); 
                   𝒚 - 7 = (-2/3)𝒙 + 4; 
                   𝒚 = (-2/3)𝒙 + 11
          ○ [29:50]. 🧩 Example – Finding the Equation of a Line Perpendicular to:  2𝒙 +3𝒚 = 12 passing through the point (6,7) 
               ■ 𝒎 = -2/3  → 𝒎 = 3/2 (slopes are negative reciprocals of each other)
               ■ Use the point-slope form:
                   𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁);  
                   𝒚 - 7 = (3/2)(𝒙 - 6); 
                   𝒚 - 7 = (3/2)𝒙 - 9; 
                   𝒚 = (3/2)𝒙 - 2




 Ａｎｇｌｅ ｏｆ Ｉｎｃｌｉｎａｔｉｏｎ

● [32:10]. Angle of Inclination 
     ◉ Definition: The angle a line forms with the positive 𝒙-axis.
     ◉ Relationship with change in 𝒙 (Δ𝒙) and change in 𝒚 (Δ𝒚).
     ◉ Using basic trigonometry on a right triangle formed by the line, Δ𝒙, and Δ𝒚.
     ◉ The tangent of the angle of inclination (𝜃) equals the slope (𝒎): 
          ○ tan(𝜃) = Δ𝒚 / Δ𝒙 = 𝒎.
     ◉ If the angle is known, the slope can be found. If the slope is known, the angle can be found.
     ◉ [35:50]. 🧩 Example – Finding the Slope Given the Angle of Inclination:  30° or π/6 radians 
          ○ Using the formula 𝒎 = tan(𝜃).
          ○ Calculating tan(π/6) = sin(π/6) / cos(π/6) = (1/2) / (√3/2) = 1/√3 = √3/3.
     ◉ [39:00]. 🧩 Example – Finding the Angle of Inclination Given the Slope: 𝒎 = -1 
          ○ Using tan(𝜃) = 𝒎 → -1 = tan(𝜃).
          ○ Applying the inverse tangent function: 𝜃 = tan⁻¹(-1).
          ○ Interpreting the inverse tangent: finding the angle whose tangent is -1.
          ○ Using the unit circle to find angles where sine and cosine have the same absolute value but opposite signs.
               ■ 135°   → Second quadrant
               ■ 315°   → Fourth quadrant
     ◉ Importance of practicing these trigonometric concepts.
     ◉ Trigonometry will be used extensively in Calculus.




Ｄｉｓｔａｎｃｅ Ｆｏｒｍｕｌａ

● [44:20]. Distance Formula  
     ◉ Derived using two random points (𝒙₁, 𝒚₁) and (𝒙₂, 𝒚₂).
     ◉ Forming a right triangle with sides |𝒙₂ - 𝒙₁| and |𝒚₂ - 𝒚₁|.
     ◉ Applying the Pythagorean Theorem: 𝒅² = (𝒙₂ - 𝒙₁)² + (𝒚₂ - 𝒚₁)².
     ◉ Solving for the distance 𝒅: 
            ○ 𝒅 = √[(𝒙₂ - 𝒙₁)² + (𝒚₂ - 𝒚₁)²]
     ◉ We omit the negative root because distance cannot be negative.      