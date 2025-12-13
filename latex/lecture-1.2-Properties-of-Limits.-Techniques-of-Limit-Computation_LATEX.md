----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　１．２：　Pｒｏｐｅｒｔｉｅｓ　Oｆ　Lｉｍｉｔｓ．　Ｔｅｃｈｎｉｑｕｅｓ　Oｆ　Lｉｍｉｔ　Cｏｍｐｕｔａｔｉｏｎ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ ｔｏ ｔｈｅ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｌｉｍｉｔｓ

● [0:50](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=50). The Limit of a Constant: [📷image](../img/Calculus 1 Lecture 1.2/[0-50]-01.png) 
     ◉ The limit of a constant is defined as: $\displaystyle \lim_{x\to a} 𝓒=𝓒$, where $𝓒$ is a constant.
$\rule{0pt}{}$
     ◉ If a function always has the same value, it doesn’t matter what value $x$ approaches — the result does not change.
$\rule{0pt}{}$
     
● [2:53](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=173). The Limit of a Simple Variable: [📷image](../img/Calculus 1 Lecture 1.2/[2-53]-01.png) 
     ◉ The limit of a simple variable is defined as: $\displaystyle \lim_{x\to a} 𝒙=𝒂$.
$\rule{0pt}{}$
     ◉ If the function is just $𝒙$ itself, then as $𝒙$ gets closer to $a$, the function gets closer to $a$ — so the limit is the value it approaches.
$\rule{0pt}{}$
     
● [5:10](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=310). The Importance of Equality of One-sided Limits: [📷image](../img/Calculus 1 Lecture 1.2/[5-10]-01.png) 
     ◉ The importance that the one-sided limits are equal for the general limit to e𝒙ist is emphasized.
     ◉ Examples of one-sided limits that are not equal are provided, resulting in the non-e𝒙istence of the general limit.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0^-}\dfrac{1}{x}=-\infty$ and $\displaystyle \lim_{x\to 0^+}\dfrac{1}{𝒙}=+\infty$
$\rule{0pt}{}$



     
Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｌｉｍｉｔｓ

● [6:25](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=385). Properties of Limits: [📷image](../img/Calculus 1 Lecture 1.2/[6-25]-01.png) 
     ◉ The properties of limits are introduced, including sum, difference, product, quotient, and e𝒙ponents.
     $\rule{0pt}{}$
           ○ If $\displaystyle \lim_{x\to a}𝒇(𝒙)=L$ and $\displaystyle \lim_{x\to a}𝓰(𝒙)=L_{2}$, then:
$\rule{0pt}{}$
                ■ 1.2.1 $\displaystyle \lim_{x\to a}\big(𝒇(𝒙)\pm 𝓰(𝒙)\big)=\lim_{x\to a} 𝒇(𝒙)\ \pm\ \lim_{x\to a} 𝓰(𝒙)$
$\rule{0pt}{}$
                ■ 1.2.2 $\displaystyle \lim_{x\to a}\big(𝒇(𝒙)\cdot 𝓰(𝒙)\big)=\big(\lim_{x\to a} 𝒇(𝒙)\big)\cdot \big(\lim_{x\to a} 𝓰(𝒙)\big)$
$\rule{0pt}{}$
                ■ 1.2.3 $\displaystyle \lim_{x\to a}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=\dfrac{\lim_{x\to a} 𝒇(𝒙)}{\lim_{x\to a} 𝓰(𝒙)}$,  provided $\displaystyle \lim_{x\to a} 𝓰(𝒙)\neq 0$
$\rule{0pt}{}$
                ■ 1.2.4 $\displaystyle \lim_{x\to a}\big(𝒇(𝒙)\big)^{n}=\big(\lim_{x\to a} 𝒇(𝒙)\big)^{n}$
$\rule{0pt}{}$
                        ▣ 1.2.4.1 $\displaystyle \lim_{x\to a}\sqrt[n]{\,𝒇(𝒙)\,}=\sqrt[n]{\,\lim_{x\to a} 𝒇(𝒙)\,}$ (✔ The property is valid only if the limit exists, and in the case of even roots, the value inside the root must be non-negative)
$\rule{0pt}{}$

● [11:05](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=665). Recapitulation



     

Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ ｉｎ Ｐｏｌｙｎｏｍｉａｌｓ

● [12:20](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=740). 🧩 Evaluation of $\displaystyle \lim_{x\to 2}\ (𝒙^{3}-2𝒙+7)$: [📷image](../img/Calculus 1 Lecture 1.2/[12-20]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 2}(𝒙^{3}-2𝒙+7)$ is calculated using the properties of limits.
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 2}𝒙^{3}-\lim_{x\to 2}2𝒙+\lim_{x\to 2}7$
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 2}𝒙^{3}-\big(\lim_{x\to 2}2\big)\cdot \big(\lim_{x\to 2}𝒙\big)+\lim_{x\to 2}7$
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 2}𝒙^{3}-2𝒙+7=11$
$\rule{0pt}{}$
          ○ $f(2)=11$
$\rule{0pt}{}$
     
● [17:04](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=1024).  𝑻𝒉𝒆 𝑳𝒊𝒎𝒊𝒕 𝒐𝒇 𝑨𝒏𝒚 𝑷𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍: [📷image](../img/Calculus 1 Lecture 1.2/[17-04]-01.png) 
     ◉ $\displaystyle \lim_{x\to a}\mathcal{P}(𝒙)=\mathcal{P}(𝒂)$
$\rule{0pt}{}$
          ○ 𝑻𝒉𝒆 𝒍𝒊𝒎𝒊𝒕 𝒐𝒇 𝒂 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒂𝒔 $𝒙$ 𝒂𝒑𝒑𝒓𝒐𝒂𝒄𝒉𝒆𝒔 𝒂 𝒑𝒐𝒊𝒏𝒕 $a$ 𝒊𝒔 𝒋𝒖𝒔𝒕 𝒕𝒉𝒆 𝒗𝒂𝒍𝒖𝒆 𝒐𝒇 𝒕𝒉𝒆 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍 𝒂𝒕 𝒕𝒉𝒂𝒕 𝒑𝒐𝒊𝒏𝒕.
$\rule{0pt}{}$
     
● [20:16](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=1216). 🧩 Evaluation of $\displaystyle \lim_{x\to 2}\ \big(𝒙^{5}-3𝒙+4\big)^{3}$: [📷image](../img/Calculus 1 Lecture 1.2/[20-16]-01.png) 
$\rule{0pt}{}$
     ◉ The calculation is simplified by evaluating the function at $𝒙=2$ and then cubing the result.
$\rule{0pt}{}$


         

Ｌｉｍｉｔｓ ｏｆ Ｎｏｎ－Ｐｏｌｙｎｏｍｉａｌ Ｆｕｎｃｔｉｏｎｓ

● [23:05](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=1385). 🧩  Evaluation of $\displaystyle \lim_{x\to 2}\ \dfrac{4𝒙^{2}+1}{𝒙+3}$: [📷image](../img/Calculus 1 Lecture 1.2/[23-05]-01.png) 
$\rule{0pt}{}$
     ◉ Apply property 1.2.3 → $\displaystyle \dfrac{\lim_{x\to 2}(4𝒙^{2}+1)}{\lim_{x\to 2}(𝒙+3)}$
$\rule{0pt}{}$
     ◉ Then we check that both the numerator and the denominator are polynomials, so we can substitute $𝒙=2$ directly.
$\rule{0pt}{}$

● [26:20](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=1580). 🧩 Evaluation of  $\displaystyle \lim_{x\to 1}\ \sqrt[3]{\dfrac{5𝒙+7}{𝒙^{2}+1}}$ [📷image](../img/Calculus 1 Lecture 1.2/[26-20]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 1}\sqrt[3]{\dfrac{5𝒙+7}{𝒙^{2}+1}}=\sqrt[3]{\dfrac{5\cdot 1+7}{1^{2}+1}}=\sqrt[3]{6}$
$\rule{0pt}{}$
     ◉ It is mentioned that the same properties as for polynomials can be used, as long as domain issues, such as division by zero, are avoided.
          
● [28:50](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=1730). 🧩 Evaluation of  $\displaystyle \lim_{x\to 2}\ \dfrac{𝒙^{2}-4}{𝒙-2}$ [📷image](../img/Calculus 1 Lecture 1.2/[28-50]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 2}\dfrac{𝒙^{2}-4}{𝒙-2}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 2}\dfrac{(𝒙+2)(𝒙-2)}{𝒙-2}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 2}\big[\,𝒙+2\,\big]$
$\rule{0pt}{}$
     ◉ Cancel $(𝒙-2)$, since we are not evaluating exactly at $𝒙=2$, but rather approaching it. 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 2}\big[𝒙+2\big]=2+2=4$
$\rule{0pt}{}$
     ◉ The original function is undefined because the denominator becomes zero $(𝒙-2=0)$.  
$\rule{0pt}{}$
          ○ This creates a  𝒉𝒐𝒍𝒆 in the graph at the point $(2,4)$. The function does not diverge to infinity; it simply has a removable discontinuity.  
$\rule{0pt}{}$
          ○ This is different from a vertical asymptote, which occurs when the denominator    approaches zero but the numerator does  𝒏𝒐𝒕 approach
             zero at the same time (the numerator doesn’t become zero when the denominator does) — causing the function to diverge to $+\infty$ or $-\infty$.
$\rule{0pt}{}$
              
● 📝 N͟O͟T͟E͟: 𝑰𝒇 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒃𝒆𝒄𝒐𝒎𝒆𝒔 𝒛𝒆𝒓𝒐 𝒂𝒏𝒅 𝒘𝒆 𝒄𝒂𝒏 𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒚 𝒕𝒉𝒆 𝒆𝒙𝒑𝒓𝒆𝒔𝒔𝒊𝒐𝒏 𝒃𝒚 𝒄𝒂𝒏𝒄𝒆𝒍𝒊𝒏𝒈 𝒂 𝒄𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓 𝒘𝒊𝒕𝒉 𝒕𝒉𝒆 𝒏𝒖𝒎𝒆𝒓𝒂𝒕𝒐𝒓, 𝒕𝒉𝒆𝒏 𝒕𝒉𝒆𝒓𝒆'𝒔 𝒋𝒖𝒔𝒕 
                     𝒂 𝒉𝒐𝒍𝒆 — 𝒕𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒊𝒔 𝒔𝒕𝒊𝒍𝒍 𝒘𝒆𝒍𝒍-𝒃𝒆𝒉𝒂𝒗𝒆𝒅 𝒏𝒆𝒂𝒓𝒃𝒚. 𝑩𝒖𝒕 𝒊𝒇 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒊𝒔 𝒛𝒆𝒓𝒐 𝒂𝒏𝒅 𝒘𝒆  𝒄͟𝒂͟𝒏͟’͟𝒕͟  𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒚, 𝒕𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 𝒃𝒍𝒐𝒘𝒔 𝒖𝒑 — 𝒕𝒉𝒂𝒕'𝒔 
                     𝒂 𝒗𝒆𝒓𝒕𝒊𝒄𝒂𝒍 𝒂𝒔𝒚𝒎𝒑𝒕𝒐𝒕𝒆.



     
Ｆａｃｔｏｒｉｚａｔｉｏｎ ａｎｄ Ｓｉｍｐｌｉｆｉｃａｔｉｏｎ ｔｏ Ｅｖａｌｕａｔｅ Ｌｉｍｉｔｓ

● [33:45](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=2025). Factorization and Simplification to Evaluate Limits: 
     ◉ 🧩 Evaluation of $\displaystyle \lim_{x\to -4}\ \dfrac{2𝒙+8}{𝒙^{2}+𝒙-12}$ [📷image](../img/Calculus 1 Lecture 1.2/[33-45]-01.png) 
$\rule{0pt}{}$
          ○$\displaystyle \lim_{x\to -4}\dfrac{2𝒙+8}{𝒙^{2}+𝒙-12}$
$\rule{0pt}{}$
          ○$\displaystyle \lim_{x\to -4}\dfrac{2(𝒙+4)}{(𝒙+4)(𝒙-3)}$
$\rule{0pt}{}$
          ○$\displaystyle \lim_{x\to -4}\dfrac{2}{𝒙-3}= \dfrac{2}{-4-3}=\dfrac{2}{-7}=-\dfrac{2}{7}$
$\rule{0pt}{}$
     ◉ The technique of factoring and simplifying serve for evaluate limits when direct substitution results in $0/0$.
$\rule{0pt}{}$
     ◉ 𝑪𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓𝒔 𝒊𝒏 𝒂 $0/0$ 𝒊𝒏𝒅𝒆𝒕𝒆𝒓𝒎𝒊𝒏𝒂𝒕𝒊𝒐𝒏 𝒇𝒐𝒓 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔: 𝑰𝒇 𝒃𝒐𝒕𝒉 𝒕𝒉𝒆 𝒏𝒖𝒎𝒆𝒓𝒂𝒕𝒐𝒓 𝒂𝒏𝒅 𝒕𝒉𝒆 𝒅𝒆𝒏𝒐𝒎𝒊𝒏𝒂𝒕𝒐𝒓 𝒂𝒓𝒆 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔 
         𝒂𝒏𝒅 𝒃𝒆𝒄𝒐𝒎𝒆 $0$ 𝒂𝒕 𝒕𝒉𝒆 𝒔𝒂𝒎𝒆 𝒑𝒐𝒊𝒏𝒕 $x=c$, 𝒊𝒕 𝒎𝒆𝒂𝒏𝒔 $x=c$ 𝒊𝒔 𝒂 𝒓𝒐𝒐𝒕 𝒐𝒇 𝒃𝒐𝒕𝒉 𝒑𝒐𝒍𝒚𝒏𝒐𝒎𝒊𝒂𝒍𝒔. 𝑻𝒉𝒊𝒔 𝒊𝒎𝒑𝒍𝒊𝒆𝒔 𝒕𝒉𝒆𝒚 𝒔𝒉𝒂𝒓𝒆
         𝒂 𝒄𝒐𝒎𝒎𝒐𝒏 𝒇𝒂𝒄𝒕𝒐𝒓 $(𝒙-𝒄)$. 𝑻𝒉𝒊𝒔 𝒇𝒂𝒄𝒕𝒐𝒓 𝒄𝒂𝒏 𝒃𝒆 𝒆𝒍𝒊𝒎𝒊𝒏𝒂𝒕𝒆𝒅 𝒕𝒉𝒓𝒐𝒖𝒈𝒉 𝒔𝒊𝒎𝒑𝒍𝒊𝒇𝒊𝒄𝒂𝒕𝒊𝒐𝒏, 𝒂𝒍𝒍𝒐𝒘𝒊𝒏𝒈 𝒕𝒉𝒆 𝒍𝒊𝒎𝒊𝒕 𝒕𝒐 𝒃𝒆 𝒓𝒆𝒔𝒐𝒍𝒗𝒆𝒅.
     ◉ The importance of maintaining the limit notation until the limit is evaluated is emphasized.




Ｌｉｍｉｔｓ   ｗｉｔｈ   Ｖｅｒｔｉｃａｌ   Ａｓｙｍｐｔｏｔｅｓ

● [38:23](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=2303). 🧩 Evaluation of $\displaystyle \lim_{x\to 5}\ \dfrac{𝒙^{2}-3𝒙-10}{𝒙^{2}-10𝒙+25}$ [📷image](../img/Calculus 1 Lecture 1.2/[38-23]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 5}\dfrac{𝒙^{2}-3𝒙-10}{𝒙^{2}-10𝒙+25}$ is attempted by factoring and simplifying, but a 🔶vertical asymptote🔶 is found.
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 5}\dfrac{(𝒙-5)(𝒙+2)}{(𝒙-5)(𝒙-5)}$  =   $\displaystyle \lim_{x\to 5}\dfrac{𝒙+2}{𝒙-5}$
$\rule{0pt}{}$
          ○ 📝 N͟O͟T͟E͟: Before rushing to factor the expression, 𝒂𝒍𝒘𝒂𝒚𝒔 𝒄𝒉𝒆𝒄𝒌 the value you're approaching—in this case, $𝒙=5$.  
                                If plugging in the number gives a defined result, there's no need to factor.  Factoring would just waste time and might confuse you unnecessarily.
     ◉ The difference is clarified between:
          ○  A 𝒉𝒐𝒍𝒆 in the graph (removable discontinuity, can be simplified), and  
          ○  A 🔶vertical asymptote🔶 (non-removable, cannot be simplified).
     ◉ [40:45](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=2445).   ͟𝐒͟𝐢͟𝐠͟𝐧͟ ͟𝐀͟𝐧͟𝐚͟𝐥͟𝐲͟𝐬͟𝐢͟𝐬͟ ͟𝐓͟𝐞͟𝐬͟𝐭͟:
          ○ The sign analysis test is presented to determine the behavior of a function **around** a 🔶vertical asymptote🔶.
               ■ Steps for Sign Analysis at $𝒙=5$:
                    ▣  1.  Check the function:
                         ▢ At $𝒙=5$, the denominator becomes $0$ and cannot be canceled out.
                         ▢ This means there is a 🔶vertical asymptote🔶 at $𝒙=5$ — not a hole.
$\rule{0pt}{}$
                    ▣  2. Identify key points:
                         ▢ Problem point: $𝒙=5$
                         ▢ Optional helper point: $𝒙=-2$ (just to clearly separate intervals on the number line)
$\rule{0pt}{}$
                    ▣  3. Draw a number line to analyze signs
                     $\rule{0pt}{}$
                              ─────●───────────────●────
                                          -2                                      5
                                          $\rule{0pt}{}$
                    ▣  4. Pick a number to the right of 5 (e.g., $𝒙=6$):
$\rule{0pt}{}$
                         ▢ $𝒇(𝒙)=\dfrac{𝒙+2}{𝒙-5}$
$\rule{0pt}{}$
                          ▢ $𝒇(6)=\dfrac{6+2}{6-5}=\dfrac{8}{1}=8>0$ → Positive
$\rule{0pt}{}$
                          ▢ So as $𝒙\to 5^{+}$, $𝒇(𝒙)\to +\infty$
$\rule{0pt}{}$
                                                                                    |
                                                                                    |
                                                                                   ╰----
                             ─────●───────────────●────
                                         -2                                      5
                                         $\rule{0pt}{}$
                     ▣  5. Pick a number to the left of 5 (e.g., $𝒙=0$):
$\rule{0pt}{}$
                             $𝒇(𝒙)=\dfrac{𝒙+2}{𝒙-5}$
$\rule{0pt}{}$
                             $𝒇(0)=\dfrac{0+2}{0-5}=\dfrac{2}{-5}=-\dfrac{2}{5}<0$ → Negative
$\rule{0pt}{}$
                            So as $𝒙\to 5^{-}$, $𝒇(𝒙)\to -\infty$
$\rule{0pt}{}$
                                                                                |
                                                                                |
                                                                               ╰---
                            ─────●──────────────●────
                                         -2                           ---╮5
                                                                            |
                                                                            |
                                                                            $\rule{0pt}{}$
                   ▣  6. The limit D.N.E because the left-hand limit ($-\infty$) and right-hand limit ($+\infty$) are not the same.  $\rule{0pt}{}$
                           This confirms a vertical asymptote at $𝒙=5$.



                  
Ｓｕｍｍａｒｙ ｏｆ Ｔｅｃｈｎｉｑｕｅｓ ｆｏｒ Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ

● [47:35](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=2855). Summary of Techniques for Evaluating Limits 
     ◉ 📝  N͟O͟T͟E͟:
          ○ ① If $0/0$, factor and simplify.
          ○ ② If you can’t cancel the “problem,” check with  ͟𝐒͟𝐢͟𝐠͟𝐧͟ ͟𝐀͟𝐧͟𝐚͟𝐥͟𝐲͟𝐬͟𝐢͟𝐬͟ ͟𝐓͟𝐞͟𝐬͟𝐭͟  because the limit might not exist.



     
Ｒａｔｉｏｎａｌｉｚａｔｉｏｎ ｔｏ Ｅｖａｌｕａｔｅ Ｌｉｍｉｔｓ

● Rationalization to Evaluate Limits:
     ◉ When solving limits involving radicals:
           ○ ① Multiply by the conjugate:
                ■ Especially if there’s a radical in the denominator.
                ■ The goal is to eliminate the radical from the denominator. Multiply by the conjugate to use the identity:
                  $\rule{0pt}{}$
                     ▣  $(a-b)(a+b)=a^{2}-b^{2}$
$\rule{0pt}{}$
                ■ This clears the radical in the denominator.
           ○ ② Do not expand (distribute) the numerator immediately:
                ■ Avoid expanding the numerator right away.
                ■ First, look to simplify — sometimes you can cancel factors.
                ■ If you expand too soon, you might miss cancellations and make the problem messier.   


● [50:50](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=3050). 🧩 Evaluation of $\displaystyle \lim_{x\to 1}\ \dfrac{𝒙-1}{\sqrt{𝒙}-1}$ [📷image](../img/Calculus 1 Lecture 1.2/[50-50]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 1}\dfrac{𝒙-1}{\sqrt{𝒙}-1}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 1}\dfrac{(𝒙-1)\cdot(\sqrt{𝒙}+1)}{(𝒙-1)}$               Multiply by the conjugate: $\dfrac{\sqrt{𝒙}+1}{\sqrt{𝒙}+1}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 1}\big(\sqrt{𝒙}+1\big)$                               Simplify cancelling $(𝒙-1)$
$\rule{0pt}{}$
     ◉ $\sqrt{1}+1=2$                                   Substitute directly
$\rule{0pt}{}$
        
● [55:25](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=3325). 🧩 Evaluation of  $\displaystyle \lim_{x\to 0}\ \dfrac{\sqrt{1+𝒙}-1}{𝒙}$  [📷image](../img/Calculus 1 Lecture 1.2/[55-25]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{\sqrt{1+𝒙}-1}{𝒙}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{(1+𝒙)-1}{\,𝒙\cdot(\sqrt{1+𝒙}+1)\,}$              Multiply by the conjugate: $\dfrac{\sqrt{1+𝒙}+1}{\sqrt{1+𝒙}+1}$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{1}{\sqrt{1+𝒙}+1}$                         Simplify cancelling $𝒙$
$\rule{0pt}{}$
     ◉ $\dfrac{1}{\sqrt{1+0}+1}=\dfrac{1}{2}$                         Substitute directly
$\rule{0pt}{}$


     
Ｌｉｍｉｔｓ  ｂｙ  Ｐａｒｔｓ

● [1:01:10](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=3670). Limits by Parts 
     ◉ The concept of limits by parts is introduced, where different functions are considered for different intervals of the domain.
     ◉ I͟D͟E͟A͟: To evaluate a limit by parts (limits for piecewise functions), the one-sided limits 🟪at the points '𝒄'  of change of the functions must be considered🟪 
                    and see if they're equal:
          ○ ① You must check the limit from the left $(𝒙\to 𝒄^{-})$ and from the right $(𝒙\to 𝒄^{+})$ at the point $𝒄$.
$\rule{0pt}{}$
               ■ Finding the limit from the left means identifying which piece of the function approaches $𝒄$ from values smaller than $𝒄$.
$\rule{0pt}{}$
               ■ Finding the limit from the right means identifying which piece of the function approaches $𝒄$ from values larger than $𝒄$.
$\rule{0pt}{}$
          ○ ② If both one-sided limits are equal, then the limit exists at $𝒄$. If they are different, the overall limit does not exist at that point.
$\rule{0pt}{}$

● [1:03:12](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=3792). 🧩 Evaluation of Limits by Parts: [📷image-1](../img/Calculus 1 Lecture 1.2/[1-03-12]-01.png) [📷image-2](../img/Calculus 1 Lecture 1.2/[1-03-12]-02.png)
     ◉ The need to determine which function to use for each one-sided limit, depending on the interval of the domain, is emphasized.
     ◉ An e𝒙ample of limit by parts is worked out for a function defined in three intervals. The function is:
          $\rule{0pt}{}$
          ○ $\displaystyle𝒇(𝒙)=\begin{cases}\dfrac{1}{𝒙+2}, & \text{if } 𝒙<-2 \quad (𝒇_{1})\\[6pt]𝒙^{2}-5, & \text{if } -2<𝒙\le 3 \quad (𝒇_{2})\\[6pt]\sqrt{𝒙+13}, & \text{if } 𝒙>3 \quad (𝒇_{3})\end{cases}$

$\rule{0pt}{}$
          ○ 🟪Points '𝒄'  of Change: find the limits as $𝒙$ approaches $-2$ and $3$🟪
          ○ [1:05:10](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=3910). Graphical Representation the e𝒙ample.
          $\rule{0pt}{}$
                               $𝒇_{1}\ \Rightarrow\ \Leftarrow\ 𝒇_{2}\ \Rightarrow\ \Leftarrow\ 𝒇_{3}$
                          <---------|----------------|---------->
                                     -2                  3
                                     $\rule{0pt}{}$
          ○ In this piecewise function $𝒇(𝒙)$:
              ■🟪We must check the limit at each transition point $(𝒙=-2 \text{ and } 𝒙=3)$🟪. Steps:
                   ▣ 1. Find the limit from the left $(𝒙\to 𝒄^{-})$ and the right $(𝒙\to 𝒄^{+})$ separately at the point $𝒄$:
                        ▢ Finding the limit from the left means identifying which piece of the function is used when approaching $𝒄$ from the left.
$\rule{0pt}{}$
                             ▲ Example: For $𝒙\to -2^{-}$, use $𝒇_{1}(𝒙)$.
$\rule{0pt}{}$
                             ▲ Example: For $𝒙\to 3^{-}$, use $𝒇_{2}(𝒙)$.
$\rule{0pt}{}$
                       ▢ Finding the limit from the right means identifying which piece of the function is used when approaching $𝒄$ from the right.
$\rule{0pt}{}$
                             ▲ Example: For $𝒙\to -2^{+}$, use $𝒇_{2}(𝒙)$.
$\rule{0pt}{}$
                             ▲ Example: For $𝒙\to 3^{+}$, use $𝒇_{3}(𝒙)$.
$\rule{0pt}{}$
                   ▣ 2. Compare the limits at each point:
                        ▢ $𝒙=3$
$\rule{0pt}{}$
                            ▲$\displaystyle \lim_{x\to 3^{-}}\big(𝒙^{2}-5\big)=4$
$\rule{0pt}{}$
                            ▲$\displaystyle \lim_{x\to 3^{+}}\sqrt{𝒙+13}=4$
$\rule{0pt}{}$
                            ▲ $\displaystyle \lim_{x\to 3}𝒇(𝒙)=4$
$\rule{0pt}{}$
                            ▲ Due to the left and right limits are equal, the limit exists at $𝒙=3$.
$\rule{0pt}{}$
                         ▢ $𝒙=-2$
$\rule{0pt}{}$
                             ▲$\displaystyle \lim_{x\to -2^{-}} \dfrac{1}{𝒙+2}=-\infty$
$\rule{0pt}{}$
                             ▲$\displaystyle \lim_{x\to -2^{+}} 𝒙^{2}-5=-1$
$\rule{0pt}{}$
                             ▲ $\displaystyle \lim_{x\to -2}𝒇(𝒙)=\text{D.N.E.}$ (Does Not Exist)
$\rule{0pt}{}$
                             ▲ Due to they are different, the limit does not exist at $𝒙=-2$.
$\rule{0pt}{}$



Ｌｉｍｉｔｓ ｉｎ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｆｕｎｃｔｉｏｎｓ

● [1:19:43](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=4783). 𝙨𝒊𝙣(𝒙) 𝒂𝙣𝒅 𝒄𝙤𝒔(𝒙) 𝙖𝙧𝙚 𝙘𝙤𝙣𝙩𝙞𝙣𝙪𝙤𝙪𝙨 𝒆𝙫𝒆𝙧𝙮𝙬𝒉𝙚𝙧𝙚. [📷image](../img/Calculus 1 Lecture 1.2/[1-19-43]-01.png) 
     ◉ $\displaystyle \lim_{x\to a}\sin(𝒙)=\sin(𝒂)$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to a}\cos(𝒙)=\cos(𝒂)$
$\rule{0pt}{}$

● [1:22:32](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=4952).  𝑻𝒉𝒆 𝒇𝒖𝒏𝒄𝒕𝒊𝒐𝒏 $\tan(𝒙)$ 𝒆𝒙𝒊𝒔𝒕𝒔 𝒆𝒙𝒄𝒆𝒑𝒕 𝒂𝒕 𝒕𝒉𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒘𝒉𝒆𝒓𝒆 $\cos(𝒙)=0$. 𝑻𝒉𝒆𝒔𝒆 𝒑𝒐𝒊𝒏𝒕𝒔 𝒂𝒓𝒆 $𝒙=\pm \pi/2+n\pi,\ n\in\mathbb{Z}$. [📷image](../img/Calculus 1 Lecture 1.2/[1-22-32]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to a}\tan(𝒙)=\tan(a)$ ; $𝒙\neq \pm \pi/2+n\pi,\ n\in\mathbb{Z}$.  
$\rule{0pt}{}$

● [1:28:15](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=5295). 🧩 Evaluation of $\displaystyle \lim_{x\to 1}\ \cos\!\left(\dfrac{𝒙^{2}-1}{𝒙-1}\right)$ [📷image](../img/Calculus 1 Lecture 1.2/[1-28-15]-01.png) 
$\rule{0pt}{}$
     ◉ $\cos(𝒙)$ is continuous so by composition ...
$\rule{0pt}{}$
          ○ $\displaystyle \cos\!\left(\lim_{x\to 1}\dfrac{𝒙^{2}-1}{𝒙-1}\right)$
$\rule{0pt}{}$
          ○ $\displaystyle \cos\!\left(\lim_{x\to 1}\dfrac{(𝒙+1)(𝒙-1)}{𝒙-1}\right)$
$\rule{0pt}{}$
          ○ $\displaystyle \cos\!\big(\lim_{x\to 1}(𝒙+1)\big)$
$\rule{0pt}{}$
          ○ $\cos(1+1)$
$\rule{0pt}{}$
          ○ $\cos(2)$
$\rule{0pt}{}$
     ◉ 📝N͟O͟T͟E͟: Since $\cos(𝒙)$ is continuous, we can move the limit inside by the composition rule:
          ○ 𝓟𝓻𝓸𝓹𝓮𝓻𝓽𝔂: Limit of Continuous Functions (Composition Rule)
               ■ Statement:
                    ▣ If $𝒇(𝒙)$ is continuous at $𝒙=a$, then:
$\rule{0pt}{}$
                         ▢ $\displaystyle \lim_{x\to a}𝒇(𝒙)=𝒇(a)$
$\rule{0pt}{}$
               ■ Application:
                    ▣ For continuous functions like $\sin(𝒙)$, $\cos(𝒙)$, polynomials, rationals, exponentials, etc., $\rule{0pt}{}$
                        you can move the limit inside:
                         ▢ $\displaystyle \lim_{x\to a}𝒇(𝒙)=𝒇\!\big(\lim_{x\to a} 𝒙\big)=𝒇(a)$
$\rule{0pt}{}$
               ■ Important:
                    ▣ This is why when dealing with continuous functions, limits are straightforward to compute.


● [1:33:00](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=5580). 🧩 Evaluation of $\displaystyle \lim_{x\to \pi/2}\ \big(3𝒙^{2}+\cos(𝒙)\big)$ [📷image](../img/Calculus 1 Lecture 1.2/[1-33-00]-01.png) 
$\rule{0pt}{}$
     ◉ Since there is no issue of discontinuity or undefined values at $𝒙=\pi/2$, we are allowed to directly substitute the value into the expression.
     ◉📝N͟O͟T͟E͟: Whenever the function is continuous at the point — meaning there is no division by zero,
                           no square root of a negative number in the real domain, and no discontinuity — 
                           we can evaluate the limit by direct substitution.
                           $\rule{0pt}{}$
     ◉ So: $\displaystyle \lim_{x\to \pi/2}\ \big(3𝒙^{2}+\cos(𝒙)\big)=3(\pi/2)^{2}+\cos(\pi/2)=3\cdot \dfrac{\pi^{2}}{4}+0=\dfrac{3\pi^{2}}{4}$
$\rule{0pt}{}$

● [1:37:15](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=5835). ∴ 𝑫𝒆𝒎𝒐𝒏𝒔𝒕𝒓𝒂𝒕𝒊𝒐𝒏 𝒐𝒇 $\displaystyle \lim_{x\to 0}\ \dfrac{\sin 𝒙}{𝒙}=1$ [📷image-1](../img/Calculus 1 Lecture 1.2/[1-37-15]-01.png) [📷image-2](../img/Calculus 1 Lecture 1.2/[1-37-15]-02.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{\sin 𝒙}{𝒙}=1$ is demonstrated using the squeeze theorem and areas of triangles and sectors.
$\rule{0pt}{}$
     ◉ Triangles and sectors in a unit circle are constructed to compare their areas and establish the necessary inequalities for the squeeze theorem.
     $\rule{0pt}{}$
     ◉ To understand why $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}=1$, we can use a geometric approach involving areas in the unit circle. Here's a step-by-step explanation:
$\rule{0pt}{}$
          ○ 1. Unit Circle Setup:
               ■ Consider a unit circle centered at the origin.
               ■ Let $𝒙$ be an angle near $0$ on the positive $𝒙$-axis.
$\rule{0pt}{}$
          ○ 2. First Triangle;  Two possible interpretations:
               ■ Option 1: Right triangle
                    ▣ Base $=\cos(𝒙)$, height $=\sin(𝒙)$.
$\rule{0pt}{}$
                    ▣ Area $=\dfrac{1}{2}\cdot \cos(𝒙)\cdot \sin(𝒙)$.
$\rule{0pt}{}$
                    ▣ It is a right triangle formed by dropping a perpendicular from the circle to the $x$-axis.
               ■ Option 2: General triangle (more accurate for this limit discussion)
                    ▣ Base $=1$ (the radius of the unit circle).
$\rule{0pt}{}$
                    ▣ Height $=\sin(𝒙)$.
$\rule{0pt}{}$
                    ▣ Area $=\dfrac{1}{2}\cdot 1\cdot \sin(𝒙)=\dfrac{1}{2}\sin(𝒙)$.
$\rule{0pt}{}$
                    ▣ This is a scalene triangle (three unequal sides), not necessarily a right triangle.
               ■ 📝N͟O͟T͟E͟: For the purpose of proving the limit $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}=1$, we usually consider the triangle where the base is $1$ and the height is $\sin(𝒙)$,
$\rule{0pt}{}$
                                    leading to the simpler expression $\text{Area}=\dfrac{1}{2}\sin(𝒙)$.
$\rule{0pt}{}$
          ○ 3. Sector Area (Area $=\dfrac{1}{2}\cdot 𝒙$):
$\rule{0pt}{}$
               ■ The sector is formed by the angle $𝒙$ in the unit circle.
$\rule{0pt}{}$
               ■ The area formula for a sector is $\dfrac{1}{2}\,r^{2}\theta$. Since $r=1$, it simplifies to $\dfrac{1}{2}\,𝒙$.
$\rule{0pt}{}$
          ○ 4. Larger Triangle Involving the Tangent Line:
               ■ Extend the tangent line from the point where the terminal side meets the circle.
               ■ This creates a larger triangle whose height corresponds to $\tan(𝒙)$.
$\rule{0pt}{}$
          ○ 5. Setting Up Inequalities:
               ■ Comparing areas:
               $\rule{0pt}{}$  $\rule{0pt}{}$
                    ▣  $\dfrac{1}{2}\sin(𝒙)<\dfrac{1}{2}\,𝒙<\dfrac{1}{2}\tan(𝒙)$ 
$\rule{0pt}{}$
          ○ 6. Simplifying the Inequalities:
               ■ Multiply through by $2$:
               $\rule{0pt}{}$
                    ▣ $\sin(𝒙)<𝒙<\tan(𝒙)$
$\rule{0pt}{}$
               ■ Divide all parts by $\sin(𝒙)$:
               $\rule{0pt}{}$
                    ▣ $1<\dfrac{𝒙}{\sin(𝒙)}<\dfrac{1}{\cos(𝒙)}$
$\rule{0pt}{}$
               ■ By taking the reciprocal of all positive terms, the inequality reverses its direction:
                    ▣  $1<\dfrac{𝒙}{\sin(𝒙)}<\dfrac{1}{\cos(𝒙)}\ \Longrightarrow\ \cos(𝒙)<\dfrac{\sin(𝒙)}{𝒙}<1$
$\rule{0pt}{}$
          ○ 7. Applying the Squeeze Theorem:
               ■ As $𝒙\to 0$, $\cos(𝒙)\to 1$, so $1/\cos(𝒙)\to 1$.
$\rule{0pt}{}$
               ■ Thus, $𝒙/\sin(𝒙)$ is squeezed between $1$ and something approaching $1$.
$\rule{0pt}{}$
               ■ By the Squeeze Theorem: $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}=1$
$\rule{0pt}{}$
     ◉ 📝N͟O͟T͟E͟: In the proof using the Squeeze Theorem for $\displaystyle \lim_{x\to 0}\big(\sin(𝒙)/𝒙\big)=1$, it is correct to use the symbol “$<$” instead of “$\le$”. The reason is:
          ○ We are comparing areas or values strictly, not saying they are equal.
          ○ For very small $𝒙$ near $0$ (but not exactly $0$), we have strict inequalities.$\rule{0pt}{}$
          ○ The Squeeze Theorem only requires the function to be trapped between two functions, not necessarily touching them.
             Thus, using “$<$” is perfectly fine and appropriate.
$\rule{0pt}{}$

● [1:55:00](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=6900). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{1-\cos 𝒙}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[1-55-00]-01.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{1-\cos 𝒙}{𝒙}$ is calculated using the technique of multiplying by the conjugate.
$\rule{0pt}{}$
     ◉ The trigonometric identity $1-\cos^{2} 𝒙=\sin^{2} 𝒙$ is used to simplify the expression after multiplying by the conjugate.
$\rule{0pt}{}$
     ◉ Multiply and divide by the conjugate of the numerator $(1+\cos(𝒙))$:
$\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{(1-\cos(𝒙))(1+\cos(𝒙))}{𝒙\,(1+\cos(𝒙))}$
$\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{1-\cos^{2}(𝒙)}{𝒙\,(1+\cos(𝒙))}$
$\rule{0pt}{}$
     ◉ Use the identity: $1-\cos^{2}(𝒙)=\sin^{2}(𝒙)$
$\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin^{2}(𝒙)}{𝒙\,(1+\cos(𝒙))}$
$\rule{0pt}{}$
     ◉ Split into two factors:
     $\rule{0pt}{}$
         ○ $\displaystyle \left(\lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}\right)\cdot \left(\lim_{x\to 0}\dfrac{\sin(𝒙)}{1+\cos(𝒙)}\right)$ 
$\rule{0pt}{}$
     ◉ Apply known limits:
     $\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}=1,\quad \lim_{x\to 0}\dfrac{\sin(𝒙)}{1+\cos(𝒙)}=\dfrac{0}{2}=0$
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{1-\cos 𝒙}{𝒙}=0$
$\rule{0pt}{}$

● [2:02:55](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=7375).  🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{\tan 𝒙}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-02-55]-01.png) 
$\rule{0pt}{}$
     ◉ $\tan 𝒙=\dfrac{\sin 𝒙}{\cos 𝒙}$.
$\rule{0pt}{}$
     ◉ The expression is split into two limits: 
               $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin 𝒙}{𝒙}$ and $\displaystyle \lim_{x\to 0}\dfrac{1}{\cos 𝒙}$.
$\rule{0pt}{}$
     ◉ Rewrite tangent as sine over cosine:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)/\cos(𝒙)}{𝒙}$
$\rule{0pt}{}$
     ◉ Simplify the complex fraction:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{\cos(𝒙)}\cdot \dfrac{1}{𝒙}=\left(\lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}\right)\cdot \left(\lim_{x\to 0}\dfrac{1}{\cos(𝒙)}\right)=1\cdot 1$
          $\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{\tan 𝒙}{𝒙}=1$
$\rule{0pt}{}$



Ｍａｎｉｐｕｌａｔｉｏｎ   ｏｆ   Ｔｒｉｇｏｎｏｍｅｔｒｉｃ   Ｌｉｍｉｔｓ

● Manipulation of Trigonometric Limits 
     ◉ Various examples of manipulating trigonometric limits to match known identities are presented.
     ◉ Examples with $\sin 𝒙/𝒙$, $(1-\cos 𝒙)/𝒙$, and $\tan 𝒙/𝒙$ are included.
$\rule{0pt}{}$
     ◉ Techniques such as multiplying by a constant, splitting the limit into multiple limits, and using trigonometric identities are used.
     ◉ **"We transform the unknown into something known"** using mathematical tools such as simplifications, identities, or properties.


● [2:08:00](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=7680). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{\sin(2𝒙)}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-08-00]-01.png) 
$\rule{0pt}{}$
     ◉ Multiply by $2/2$ to create a form we can use: 
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(2𝒙)}{𝒙}\cdot \dfrac{2}{2}$
$\rule{0pt}{}$
     ◉ Rearrange the expression: 
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{2\sin(2𝒙)}{2𝒙}$
$\rule{0pt}{}$
     ◉ Factor out the constant $2$:
     $\rule{0pt}{}$
          ○  $\displaystyle 2\cdot \lim_{x\to 0}\dfrac{\sin(2𝒙)}{2𝒙}$
$\rule{0pt}{}$
     ◉ Recognize the standard limit:
     $\rule{0pt}{}$
          ○  $2\cdot \lim_{u\to 0}\dfrac{\sin u}{u}=2$  → where $u=2𝒙$
     $\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\dfrac{\sin(2𝒙)}{𝒙}=2$
$\rule{0pt}{}$

● [2:13:40](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=8020). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{\sin(5𝒙)}{\sin(6𝒙)}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-13-40]-01.png) 
$\rule{0pt}{}$
     ◉ Multiply numerator and denominator by $1/𝒙$: 
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(5𝒙)}{𝒙}\Big/\dfrac{\sin(6𝒙)}{𝒙}$
$\rule{0pt}{}$
     ◉ Multiply numerator and denominator by constants:
          ○ $\displaystyle \lim_{x\to 0}\left(\dfrac{\sin(5𝒙)}{𝒙}\cdot \dfrac{5}{5}\right)\Big/\left(\dfrac{\sin(6𝒙)}{𝒙}\cdot \dfrac{6}{6}\right)$
$\rule{0pt}{}$
     ◉ Rearrange the expression: 
     $\rule{0pt}{}$
         ○ $\displaystyle \dfrac{5}{6}\cdot \lim_{x\to 0}\dfrac{\sin(5𝒙)}{5𝒙}\Big/\lim_{x\to 0}\dfrac{\sin(6𝒙)}{6𝒙}$
$\rule{0pt}{}$
     ◉ Apply the standard limit identity: 
     $\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin u}{u}=1\ \ \text{with}\ u=5𝒙,\ 6𝒙$
$\rule{0pt}{}$
     ◉ So:  $\dfrac{5}{6}\cdot \dfrac{1}{1}=\dfrac{5}{6}$
$\rule{0pt}{}$
     ◉ Therefore: $\displaystyle \lim_{x\to 0}\dfrac{\sin(5𝒙)}{\sin(6𝒙)}=\dfrac{5}{6}$
$\rule{0pt}{}$

● [2:20:25](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=8425). 🧩 Evaluation of  $\displaystyle \lim_{x\to 0}\ \dfrac{\sin(𝒙^{2})}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-20-25]-01.png) 
$\rule{0pt}{}$
     ◉ Rewrite as a product:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\left(\dfrac{\sin(𝒙^{2})}{𝒙}\right)\cdot \dfrac{𝒙}{𝒙}$
$\rule{0pt}{}$
     ◉ Rearranged: 
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\, 𝒙\cdot \dfrac{\sin(𝒙^{2})}{𝒙^{2}}$
$\rule{0pt}{}$
     ◉ Split the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \big(\lim_{x\to 0} 𝒙\big)\cdot \big(\lim_{x\to 0}\dfrac{\sin(𝒙^{2})}{𝒙^{2}}\big)$
$\rule{0pt}{}$
     ◉ Use the standard limit identity:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{u\to 0}\dfrac{\sin u}{u}=1 \ (u=𝒙^{2})$
$\rule{0pt}{}$
     ◉ Therefore: 
          ○ $0\cdot 1=0$
$\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙^{2})}{𝒙}=0$
$\rule{0pt}{}$

● [2:24:20](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=8660). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{\sin^{2}(𝒙)}{𝒙}$  [📷image](../img/Calculus 1 Lecture 1.2/[2-24-20]-01.png) 
$\rule{0pt}{}$
     ◉ Use the identity: 
               $\rule{0pt}{}$
           ○ $\sin^{2}(𝒙)=\sin(𝒙)\cdot \sin(𝒙)$
$\rule{0pt}{}$
     ◉ Rewrite the expression:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\left(\dfrac{\sin(𝒙)}{𝒙}\right)\cdot \sin(𝒙)$
$\rule{0pt}{}$
     ◉ Split the limit:
     $\rule{0pt}{}$
          ○ $\displaystyle \left(\lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}\right)\cdot \left(\lim_{x\to 0}\sin(𝒙)\right)$ 
$\rule{0pt}{}$
     ◉ Apply known limits:
     $\rule{0pt}{}$
          ○ $1\cdot 0=0$
$\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin^{2}(𝒙)}{𝒙}=0$
$\rule{0pt}{}$

● [2:25:45](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=8745). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \sin\!\left(\dfrac{1}{𝒙}\right)$ (Graphical approach) [📷image](../img/Calculus 1 Lecture 1.2/[2-25-45]-02.png) 
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 0}\sin\!\left(\dfrac{1}{𝒙}\right)=\text{D.N.E}$
$\rule{0pt}{}$
     ◉ Graph behavior:
          ○ As $x$ approaches $0$, $1/x$ increases rapidly in magnitude.
$\rule{0pt}{}$
          ○ This makes the sine function oscillate faster and faster.
     ◉ Infinite waves:
          ○ The graph oscillates infinitely between $-1$ and $1$ as $x\to 0$.
          ○ It doesn't "settle" on any value — it doesn’t flatten or approach a specific number.
     ◉ No fixed value:
          ○ For the limit to exist, $\sin(1/x)$ would need to get closer to a single number.
          ○ But instead, it keeps jumping around with no stabilization.
          ○ There are infinitely many peaks and valleys, getting tighter near $x=0$.
     ◉ Conclusion:
          ○ Since the function doesn't approach any one value as $x\to 0$, the limit does not exist.
          ○ The graph shows a dense “band” of oscillation between $-1$ and $1$ near $x=0$.
$\rule{0pt}{}$

● [2:25:45](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=8745). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\  x\cdot \sin\!\left(\dfrac{1}{𝒙}\right)$ [📷image](../img/Calculus 1 Lecture 1.2/[2-25-45]-01.png) 
$\rule{0pt}{}$
     ◉ The correct approach is to apply the **Squeeze Theorem**:
     ◉ We know that:
          ○  $-1\le \sin(1/𝒙)\le 1$
$\rule{0pt}{}$
     ◉ Multiplying all parts by $𝒙$ (which tends to $0$), we get: 
$\rule{0pt}{}$
          ○  $-|𝒙|\le 𝒙\cdot \sin(1/𝒙)\le |𝒙|$
$\rule{0pt}{}$
          ○📝N͟O͟T͟E͟: 
               ■ we know that:
                    ▣ $-1\le \sin(1/𝒙)\le 1$
$\rule{0pt}{}$
               ■ When multiplying by $𝒙$, the direction of the inequalities depends on the sign of $𝒙$:
$\rule{0pt}{}$
                    ▣ If $𝒙>0$, the inequality remains the same.
$\rule{0pt}{}$
                    ▣ If $𝒙<0$, the inequality reverses direction.
$\rule{0pt}{}$
               ■ To avoid this problem, we use the absolute value on the bounds of the inequality, as follows:
                    ▣ $-|𝒙|\le 𝒙\,\sin(1/𝒙)\le |𝒙|$
$\rule{0pt}{}$
    ◉ We introduce the absolute value to keep the direction of the inequality consistent, since multiplying by $𝒙$ would 
$\rule{0pt}{}$
        reverse the inequality when $𝒙<0$. Using $|𝒙|$ ensures the inequality remains $-|𝒙|\le 𝒙\cdot \sin(1/𝒙)\le |𝒙|$ for both positive and negative $𝒙$.
$\rule{0pt}{}$
    ◉ Apply limits:
         ○ $\displaystyle \lim_{x\to 0}\big(-|𝒙|\big)\ \le\ \lim_{x\to 0}\big(𝒙\cdot \sin(1/𝒙)\big)\ \le\ \lim_{x\to 0}|𝒙|$
$\rule{0pt}{}$
    ◉ And since:
         ○ $\displaystyle \lim_{x\to 0}|𝒙|=0\quad \Rightarrow\quad 0\le \lim_{x\to 0}\big(𝒙\cdot \sin(1/𝒙)\big)\le 0$
$\rule{0pt}{}$
   ◉ By the **Squeeze Theorem**, it follows that:
   $\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}  𝒙\cdot \sin\!\left(\dfrac{1}{𝒙}\right)=0$
$\rule{0pt}{}$
     ◉ ⚠📝 NOTE:  At first glance, the limit:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0} 𝒙 \cdot \sin\!\left(\dfrac{1}{𝒙}\right)$
$\rule{0pt}{}$
          ○ might look like it fits the identity:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{u\to 0} \dfrac{\sin u}{u}=1$
$\rule{0pt}{}$
          ○ But that identity  𝐨𝐧𝐥𝐲 𝐚𝐩𝐩𝐥𝐢𝐞𝐬 when the argument of the sine 𝐚𝐧𝐝 the denominator 𝐛𝐨𝐭𝐡 
             approach $0$ at the same time. Now, if we rewrite:
$\rule{0pt}{}$
               ■ $\displaystyle 𝒙 \cdot \sin\!\left(\dfrac{1}{𝒙}\right)=\dfrac{\sin(1/𝒙)}{1/𝒙}$
$\rule{0pt}{}$
                   ▣ Here, as $𝒙\to 0$:
$\rule{0pt}{}$
                        ▢ $1/𝒙\to \infty$,  
$\rule{0pt}{}$
                        ▢ and $\sin(1/𝒙)$ keeps oscillating between $-1$ and $1$ with no limit.
$\rule{0pt}{}$
         ○ So the expression  $\sin(1/𝒙)/(1/𝒙)$ doesn't approach $1$, and we 𝐜𝐚𝐧𝐧𝐨𝐭 apply the identity.
$\rule{0pt}{}$

● [2:35:33](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=9333). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{2-\cos(3𝒙)-\cos(4𝒙)}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-35-33]-01.png) 
$\rule{0pt}{}$
     ◉ Rewrite the expression: $\displaystyle \lim_{x\to 0}\dfrac{2-\cos(3𝒙)-\cos(4𝒙)}{𝒙}$  
$\rule{0pt}{}$
          ○ Use the identity:
          $\rule{0pt}{}$
                  ■ $2-\cos(3𝒙)-\cos(4𝒙)=\big(1-\cos(3𝒙)\big)+\big(1-\cos(4𝒙)\big)$  
$\rule{0pt}{}$
     ◉ Split into two separate limits:  
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{1-\cos(3𝒙)}{𝒙}\ +\ \lim_{x\to 0}\dfrac{1-\cos(4𝒙)}{𝒙}$
$\rule{0pt}{}$
     ◉ Multiply and divide to match the standard form:  
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{1-\cos(3𝒙)}{3𝒙}\cdot 3\ +\ \lim_{x\to 0}\dfrac{1-\cos(4𝒙)}{4𝒙}\cdot 4$
$\rule{0pt}{}$
     ◉ Apply the known limit:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{u\to 0}\dfrac{1-\cos u}{u}=0$  
$\rule{0pt}{}$
     ◉ Evaluate:
     $\rule{0pt}{}$
          ○ $3\cdot 0+4\cdot 0=0$  
$\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{2-\cos(3𝒙)-\cos(4𝒙)}{𝒙}=0$
$\rule{0pt}{}$

● [2:40:45](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=9645). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{𝒙^{2}-3\sin(𝒙)}{𝒙}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-40-45]-01.png) 
$\rule{0pt}{}$
     ◉ Rewrite the expression:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒙^{2}-3\sin(𝒙)}{𝒙}$  
$\rule{0pt}{}$
     ◉ Split the terms:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\left(\dfrac{𝒙^{2}}{𝒙}\right)-3\cdot \left(\dfrac{\sin(𝒙)}{𝒙}\right)$
$\rule{0pt}{}$
     ◉ Simplify each part:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0} 𝒙-3\cdot \left(\dfrac{\sin(𝒙)}{𝒙}\right)$
$\rule{0pt}{}$
     ◉ Apply limits:  
          ○ $\displaystyle \lim_{x\to 0} 𝒙=0$  
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin(𝒙)}{𝒙}=1$  
$\rule{0pt}{}$
     ◉ Compute:
     $\rule{0pt}{}$
          ○ $0-3\cdot 1=-3$  
$\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒙^{2}-3\sin(𝒙)}{𝒙}=-3$
$\rule{0pt}{}$

● [2:42:24](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=9744). 🧩 Evaluation of $\displaystyle \lim_{t\to 0}\ \dfrac{t^{2}}{1-\cos^{2}(t)}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-42-24]-01.png) 
$\rule{0pt}{}$
     ◉ Use the trigonometric identity:
     $\rule{0pt}{}$
          ○ $1-\cos^{2}(t)=\sin^{2}(t)$
$\rule{0pt}{}$
     ◉ Rewrite the limit:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{t\to 0}\dfrac{t^{2}}{1-\cos^{2}(t)}=\lim_{t\to 0}\dfrac{t^{2}}{\sin^{2}(t)}=\lim_{t\to 0}\left(\dfrac{t}{\sin t}\right)^{2}$
$\rule{0pt}{}$
     ◉ Recognize the limit structure:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{t\to 0}\dfrac{\sin T}{T}=1$
$\rule{0pt}{}$
          ○ Then: $\displaystyle \lim_{t\to 0}\dfrac{t}{\sin t}=\left(\lim_{t\to 0}\dfrac{\sin t}{t}\right)^{-1}=1^{-1}=1$
$\rule{0pt}{}$
     ◉ Apply the limit:
     $\rule{0pt}{}$
         ○ $\big(\lim_{t\to 0} t/\sin t\big)^{2}=1^{2}=1$
$\rule{0pt}{}$
     ◉ Final result: $1$
$\rule{0pt}{}$

● [2:50:00](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=10200). 🧩 Evaluation of $\displaystyle \lim_{x\to 0}\ \dfrac{𝒙}{\cos(\pi/2-𝒙)}$ [📷image](../img/Calculus 1 Lecture 1.2/[2-50-00]-01.png) 
$\rule{0pt}{}$
     ◉ Use the co-function identity:
     $\rule{0pt}{}$
          ○ $\cos(\pi/2-𝒙)=\sin(𝒙)$
$\rule{0pt}{}$
          ○ 📝 N͟O͟T͟E͟:  Two angles are complementary if they add up to $90^\circ$:
               ■ $\sin(\text{angle})\ \leftrightarrow\ \cos(\text{complement of angle})$
$\rule{0pt}{}$
     ◉ Replace the expression using the identity:
     $\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒙}{\sin(𝒙)}$
$\rule{0pt}{}$
     ◉ Recognize the standard limit:
     $\rule{0pt}{}$
         ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒙}{\sin(𝒙)}=1$
$\rule{0pt}{}$
                                                                   
● [2:53:40](https://www.youtube.com/watch?v=VSqOZNULRjQ&t=10420). 🧩 Evaluation of  $\displaystyle \lim_{\theta\to 0}\ \dfrac{\theta^{2}}{\,1-\cos(\theta)\,}$  [📷image](../img/Calculus 1 Lecture 1.2/[2-53-40]-01.png) 
$\rule{0pt}{}$
     ◉ Multiply by $1$ in the form of  $\dfrac{1+\cos(\theta)}{1+\cos(\theta)}$ to simplify:
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{\theta\to 0}\dfrac{\theta^{2}\big(1+\cos(\theta)\big)}{1-\cos^{2}(\theta)}$
$\rule{0pt}{}$
     ◉ Use the identity: $1-\cos^{2}(\theta)=\sin^{2}(\theta)$
$\rule{0pt}{}$
          ○ $\displaystyle \lim_{\theta\to 0}\dfrac{\theta^{2}\big(1+\cos(\theta)\big)}{\sin^{2}(\theta)}$
$\rule{0pt}{}$
     ◉ Separate into two limits:
     $\rule{0pt}{}$
          ○ $\displaystyle \left(\lim_{\theta\to 0}\dfrac{\theta^{2}}{\sin^{2}(\theta)}\right)\cdot \left(\lim_{\theta\to 0}1+\cos(\theta)\right)$
$\rule{0pt}{}$
     ◉ Use the identity:
     $\rule{0pt}{}$
         ○ $\displaystyle \lim_{\theta\to 0}\dfrac{\theta}{\sin(\theta)}=1$, so:
$\rule{0pt}{}$
              ■ $\displaystyle \lim_{\theta\to 0}\left(\dfrac{\theta}{\sin(\theta)}\right)^{2}=1^{2}=1$
$\rule{0pt}{}$
     ◉ Evaluate the limits:
         ○ $1\cdot \big(1+\cos(0)\big)=1\cdot (1+1)=2$
$\rule{0pt}{}$