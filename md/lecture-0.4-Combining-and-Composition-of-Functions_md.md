-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　０．４：Cｏｍｂｉｎｉｎｇ　ａｎｄ　ｃｏｍｐｏｓｉｔｉｏｎ　ｏｆ　ｆｕｎｃｔｉｏｎｓ**---------------------------------




Ｃｏｍｂｉｎｉｎｇ Ｆｕｎｃｔｉｏｎｓ

● [0:44](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=44). Introduction to Combining Functions: addition, subtraction, multiplication, division. [📷image](../img/Calculus 1 Lecture 0.4/[0-44]-01.png) 
      ◉ [0:57](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=57). 🧩 Example – with functions: 𝒇(𝒙) = 1 + √(𝒙 − 2) and 𝓰(𝒙) = 𝒙 − 3  
            ○ Addition of functions: (𝒇 + 𝓰)(𝒙)  
                 ■ (𝒇 + 𝓰)(𝒙) = 𝒇(𝒙) + 𝓰(𝒙) = (1 + √(𝒙 − 2)) + (𝒙 − 3) = −2 + √(𝒙 − 2) + 𝒙
            ○ Subtraction of functions: (𝒇 − 𝓰)(𝒙)  
                 ■ (𝒇 − 𝒈)(𝒙) = 𝒇(𝒙) − 𝒈(𝒙) = (1 + √(𝒙 − 2)) − (𝒙 − 3) = 4 + √(𝒙 − 2) − 𝒙
            ○  Multiplication of functions: (𝒇 ⋅ 𝓰)(𝒙)  
                 ■ (𝒇 · 𝓰)(𝒙) = 𝒇(𝒙) · 𝓰(𝒙) = (1 + √(𝒙 − 2)) · (𝒙 − 3) = 𝒙 + 𝒙√(𝒙 − 2) − 3 − 3√(𝒙 − 2)
             ○ Division of functions: (𝒇 / 𝓰)(𝒙)  
                 ■ (𝒇 / 𝓰)(𝒙) = 𝒇(𝒙) / 𝓰(𝒙) = (1 + √(𝒙 − 2)) / (𝒙 − 3)

● [3:58](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=238). Domain of Combined Functions 
     ◉ The domain is the  i͟n͟t͟e͟r͟s͟e͟c͟t͟i͟o͟n͟  of the domains of the o͟r͟i͟g͟i͟n͟a͟l͟   functions.  
     ◉ [4:30](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=270). 🧩 Example – illustrate domain restriction: [📷image](../img/Calculus 1 Lecture 0.4/[4-30]-01.png) 
          ○ √𝒙 ⋅ √𝒙 = 𝒙. The domain is not all real numbers  
               ■  The domain of √𝒙 ⋅ √𝒙 is numbers greater than or equal to 0  
    ◉ Domain restrictions cannot be removed; when functions are combined, they accumulate rather than cancel out.
          ○ 🧩 Example –:
                  Let:
                        𝒇(𝒙)=√(𝒙−1) → domain: 𝒙≥1  
                         𝓰(𝒙)=1/(𝒙−2) → domain: 𝒙≠2  
               ■ Now consider the combined function: (𝒇+𝓰)(𝒙)=√(𝒙−1)+1/(𝒙−2)
               ■ To find the domain of (𝒇+𝓰)(𝒙), we must satisfy both conditions:
                    ▣ 𝒙≥1  (so the square root is defined)  
                    ▣ 𝒙≠2  (so we don’t divide by zero)  
               ■ ⇒ Final domain: all real numbers 𝒙 such that 𝒙≥1 and 𝒙≠2  
               ■ Conclusion: domain issues do not cancel out — they accumulate.



Ｃｏｍｐｏｓｉｔｉｏｎ ｏｆ Ｆｕｎｃｔｉｏｎｓ

● [7:37](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=457). Introduction by examples to Composition of Functions [📷image](../img/Calculus 1 Lecture 0.4/[7-37]-01.png) 
     ◉ [7:56](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=476). 🧩 Example –: 𝒇(𝒙) = 𝒙³ − 4 and 𝓰(𝒙) = √𝒙  
          ○ [8:29](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=509). Composition (𝒇 ∘ 𝓰)(𝒙) = 𝒇(𝓰(𝒙))  
                ■ (𝒇 ∘ 𝓰)(𝒙) = 𝒇(𝓰(𝒙)) = 𝒇(√𝒙) = (√𝒙)³ − 4
          ○ [10:15](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=615). Composition (𝓰 ∘ 𝒇)(𝒙) = 𝓰(𝒇(𝒙))  
                ■ (𝓰 ∘ 𝒇)(𝒙) = 𝓰(𝒇(𝒙)) = 𝓰(𝒙³ − 4) = √(𝒙³ − 4)

● [11:07](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=667). Multiple Composition of Functions by example [📷image](../img/Calculus 1 Lecture 0.4/[11-07]-01.png) 
    ◉ [11:26](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=686). 🧩 Example –: 𝒇(𝒙) = √𝒙, 𝓰(𝒙) = 1/𝒙, and 𝒉(𝒙) = 𝒙³  
         ○ [11:51](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=711). (𝒇 ∘ 𝓰 ∘ 𝒉)(𝒙)  
               ■ (𝒇 ∘ 𝓰 ∘ 𝒉)(𝒙) = 𝒇(𝓰(𝒉(𝒙))) = 𝒇(𝓰(𝒙³)) = 𝒇(1 / 𝒙³)  = √(1 / 𝒙³) = 1 / √(𝒙³) = 1 / 𝒙^(3/2)
         ○ [13:30](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=810). (𝒇 ∘ 𝓰 ∘ 𝒉)(8)  
               ■ (𝒇 ∘ 𝓰 ∘ 𝒉)(8) = 1 / 8³ᐟ²

● [14:44](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=884). Decomposing a Function into a Composition of Functions by example [📷image](../img/Calculus 1 Lecture 0.4/[14-44]-01.png) 
    ◉ 🧩 Example –: 𝒉(𝒙) = (𝒙 − 7)³ can be written as a composition 𝒇(𝓰(𝒙))
         ○ (𝒇 ∘ 𝓰)(𝒙);     𝒇(𝒙) = 𝒙³;    𝓰(𝒙) = 𝒙 − 7



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ
 
● [openstax](https://openstax.org/books/college-algebra-2e/pages/3-4-composition-of-functions)