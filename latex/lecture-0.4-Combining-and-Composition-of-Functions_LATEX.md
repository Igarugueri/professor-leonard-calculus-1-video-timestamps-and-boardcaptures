-----------------------------------**Ｃａｌｃｕｌｕｓ　１　ｌｅｃｔｕｒｅ　０．４：Cｏｍｂｉｎｉｎｇ　ａｎｄ　ｃｏｍｐｏｓｉｔｉｏｎ　ｏｆ　ｆｕｎｃｔｉｏｎｓ**---------------------------------





Ｃｏｍｂｉｎｉｎｇ Ｆｕｎｃｔｉｏｎｓ

● [0:44](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=44). Introduction to Combining Functions: addition, subtraction, multiplication, division. [📷image](../img/Calculus 1 Lecture 0.4/[0-44]-01.png) 
$\rule{0pt}{}$
      ◉ [0:57](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=57). 🧩 Example – with functions: $\mathcal{f}(x)=1+\sqrt{x-2}$ and $\mathcal{g}(x)=x-3$  
      $\rule{0pt}{}$
            ○ Addition of functions: $(\mathcal{f}+\mathcal{g})(x)$  
            $\rule{0pt}{}$
                 ■ $(\mathcal{f}+\mathcal{g})(x)=\mathcal{f}(x)+\mathcal{g}(x)=(1+\sqrt{x-2})+(x-3)=-2+\sqrt{x-2}+x$
                 $\rule{0pt}{}$
            ○ Subtraction of functions: $(\mathcal{f}-\mathcal{g})(x)$  
            $\rule{0pt}{}$
                 ■ $(\mathcal{f}-\mathcal{g})(x)=\mathcal{f}(x)-\mathcal{g}(x)=(1+\sqrt{x-2})-(x-3)=4+\sqrt{x-2}-x$
                 $\rule{0pt}{}$
            ○ Multiplication of functions: $(\mathcal{f}\cdot\mathcal{g})(x)$  
            $\rule{0pt}{}$
                 ■ $(\mathcal{f}\cdot\mathcal{g})(x)=\mathcal{f}(x)\cdot\mathcal{g}(x)=(1+\sqrt{x-2})\cdot(x-3)=x+x\sqrt{x-2}-3-3\sqrt{x-2}$
                 $\rule{0pt}{}$
            ○ Division of functions: $(\mathcal{f}/\mathcal{g})(x)$  
            $\rule{0pt}{}$
                 ■ $(\mathcal{f}/\mathcal{g})(x)=\dfrac{\mathcal{f}(x)}{\mathcal{g}(x)}=\dfrac{1+\sqrt{x-2}}{x-3}$


● [3:58](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=238). Domain of Combined Functions 
     ◉ The domain is the i͟n͟t͟e͟r͟s͟e͟c͟t͟i͟o͟n͟  of the domains of the  o͟r͟i͟g͟i͟n͟a͟l͟   functions.  
     ◉ [4:30](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=270). 🧩 Example – illustrate domain restriction: [📷image](../img/Calculus 1 Lecture 0.4/[4-30]-01.png) 
          ○ $\sqrt{x}\cdot\sqrt{x}=x$. The domain is not all real numbers.  
               ■ The domain of $\sqrt{x}\cdot\sqrt{x}$ is numbers greater than or equal to $0$.  
     ◉ Domain restrictions cannot be removed; when functions are combined, they accumulate rather than cancel out.
          ○ 🧩 Example –:
                  Let:
                        $\mathcal{f}(x)=\sqrt{x-1}$ → domain: $x\ge1$  
                        $\mathcal{g}(x)=\dfrac{1}{x-2}$ → domain: $x\neq2$  
               ■ Now consider the combined function: $(\mathcal{f}+\mathcal{g})(x)=\sqrt{x-1}+\dfrac{1}{x-2}$
               ■ To find the domain of $(\mathcal{f}+\mathcal{g})(x)$, we must satisfy both conditions:
                    ▣ $x\ge1$ (so the square root is defined)  
                    ▣ $x\neq2$ (so we don’t divide by zero)  
               ■ ⇒ Final domain: all real numbers $x$ such that $x\ge1$ and $x\neq2$  
               ■ Conclusion: domain issues do not cancel out — they accumulate.




Ｃｏｍｐｏｓｉｔｉｏｎ ｏｆ Ｆｕｎｃｔｉｏｎｓ

● [7:37](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=457). Introduction by examples to Composition of Functions [📷image](../img/Calculus 1 Lecture 0.4/[7-37]-01.png) 
$\rule{0pt}{}$
     ◉ [7:56](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=476). 🧩 Example –: $\mathcal{f}(x)=x^{3}-4$ and $\mathcal{g}(x)=\sqrt{x}$  
     $\rule{0pt}{}$
          ○ [8:29](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=509). Composition $(\mathcal{f}\circ\mathcal{g})(x)=\mathcal{f}(\mathcal{g}(x))$  
          $\rule{0pt}{}$
                ■ $(\mathcal{f}\circ\mathcal{g})(x)=\mathcal{f}(\mathcal{g}(x))=\mathcal{f}(\sqrt{x})=(\sqrt{x})^{3}-4$
                $\rule{0pt}{}$
          ○ [10:15](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=615). Composition $(\mathcal{g}\circ\mathcal{f})(x)=\mathcal{g}(\mathcal{f}(x))$  
          $\rule{0pt}{}$
                ■ $(\mathcal{g}\circ\mathcal{f})(x)=\mathcal{g}(\mathcal{f}(x))=\mathcal{g}(x^{3}-4)=\sqrt{x^{3}-4}$


● [11:07](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=667). Multiple Composition of Functions by example [📷image](../img/Calculus 1 Lecture 0.4/[11-07]-01.png) 
$\rule{0pt}{}$
    ◉ [11:26](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=686). 🧩 Example –: $\mathcal{f}(x)=\sqrt{x}$, $\mathcal{g}(x)=\dfrac{1}{x}$, and $\mathcal{h}(x)=x^{3}$  
         ○ [11:51](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=711). $(\mathcal{f}\circ\mathcal{g}\circ\mathcal{h})(x)$  
               ■ $(\mathcal{f}\circ\mathcal{g}\circ\mathcal{h})(x)=\mathcal{f}(\mathcal{g}(\mathcal{h}(x)))=\mathcal{f}(\mathcal{g}(x^{3}))=\mathcal{f}\!\left(\dfrac{1}{x^{3}}\right)=\sqrt{\dfrac{1}{x^{3}}}=\dfrac{1}{\sqrt{x^{3}}}=\dfrac{1}{x^{3/2}}$
               $\rule{0pt}{}$
         ○ [13:30](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=810). $(\mathcal{f}\circ\mathcal{g}\circ\mathcal{h})(8)$  
               ■ $(\mathcal{f}\circ\mathcal{g}\circ\mathcal{h})(8)=\dfrac{1}{8^{3/2}}$


● [14:44](https://www.youtube.com/watch?v=f-_UsIP5jyA&t=884). Decomposing a Function into a Composition of Functions by example [📷image](../img/Calculus 1 Lecture 0.4/[14-44]-01.png) 
    ◉ 🧩 Example –: $\mathcal{h}(x)=(x-7)^{3}$ can be written as a composition $\mathcal{f}(\mathcal{g}(x))$
    $\rule{0pt}{}$
         ○ $(\mathcal{f}\circ\mathcal{g})(x)$; $\mathcal{f}(x)=x^{3}$; $\mathcal{g}(x)=x-7$




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● [openstax](https://openstax.org/books/college-algebra-2e/pages/3-4-composition-of-functions)
