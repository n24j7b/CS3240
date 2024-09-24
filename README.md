java c
CS3240 Assignment 1 
1 [20 points]
Assume   the   alphabet   Σ   = {0, 1}.   Consider   the   Deterministic   Finite   Automaton   (DFA) M 
depicted   in   Fig. 1   and   answer   the   following   questions.

Figure   1:   The   DFA   in   Question 1.
1.   Given   a   string w =   001,   will   DFA M accept w?
2.   Given   a   string w =   111,   will   DFA M accept w?
3.   Given   a   string w =   101,   will   DFA M accept w?4.   Please   use   accurate   natural   language   to   describe   the   language L(M ) of   DFA M ,   i.e., which   binary   strings   in   Σ∗ can   be   accepted   by M .   You   can   also   describe L(M ) using math or computer science style. notation.  
2 [20 points] 
Assume   the   alphabet   Σ   =   {0, 1}.   Consider   the   Nondeterministic   Finite   Automaton   (NFA)
N depicted   in   Fig. 2   and   answer   the   following   questions.
1.   Given   a   string w =   00,   will   NFA N accept w?
2.   Given   a   string w =   101,   will   NFA N accept w?
3.   Given   a   string w =   111,   will   NFA N accept w?4.   Does   there   exist   a   computation   path   such   that   the   NFA N will   “hang”   after   running on string w = 000?5.   Please   use   accurate   natural   language   to   describe   the   language L(N ) of   NFA N ,   i.e., which   binary   strings in Σ∗ can be accepted by N .   You can also describe L(N ) using math or computer science style. notation.

Figure   2:   The   NFA N in   Question 2.
3 [20 points]Let   alphabet   Σ   =   {0, 1}   and L =   {100}   ⊆   Σ∗,   i.e.,   language L only   contains   one   string   100. Please design a DFA whose language is L.You can provide details of this DFA by using the formal definition or insert a picture of the state diagram.   Please use a comfortable and clear picture if you want to have a handwritten state diagram.
4 [20 points] Assume   the   alphabet   Σ = {0, 1}.   Please   answer   the   following   questions   based   on   theo- rems and conclusions you have learned in代 写CS3240 Assignment 1
代做程序编程语言 lectures (and textbooks).1.   Let L =   {w ∈   Σ∗|w has   an   odd   number   of   1’s   and   contains   101   as   a   subtring.}.   Is L 
a   regular   language?   Please   justify   your   answer.2.   Let   language L contain   every   binary   string w of   Σ∗ that   satisfies   following   properties,(1) w has   both   101 and   11 as   substrings,   (2)   the   occurrence   of   101 is   before   the   oc- currence   of   11.   For   example,   1010011   ∈ L,   1100101   ∈/ L since   the   occurrence   of   101 is   after   the   occurrence   of   11. Is L a   regular   language? Please   justify   your   answer.3.   Assume L ⊆ Σ∗ is a regular language.   Is that possible that a subset L′ of L (L′ ⊆ L)   is   not   a   regular   language?
5 [20 points] Assume   the   alphabet   Σ   =   {0, 1}.   Please   provide   a   regular   expression   for   each   of   the following language.1. L =   {w ∈   Σ∗|w ̸= ϵ}.2. L =   {w ∈   Σ∗|   both   the   first   and   the   last   character   of w is   0.}.3. L =   {w ∈   Σ∗|w contains   111   as   a   substring.}.
6 [20 points] Please   determine   truth   values   of   following   statements.1.   For any valid regular expression with respect to an alphabet Σ, we can construct a DFA   and   an   NFA   such   that   the   language   of   each   of   those   two   machines   is   exactly   the language described by the regular expression.
2.   For   any   valid   DFA,   we   can   have   a   regular   expression   that   exactly   describes   the   lan- guage of this DFA.
3.   Any   language   consisting   of   a   finite   number   of   strings   is   a   regular   language.
4.   Assume A and B are   regular   languages   over   the   same   alphabet   Σ,   then   the   language
A \ B =   {w ∈   Σ∗|w ∈ A, w ∈/ B}   is   also   a   regular   language.
5.   Assume   the   alphabet   Σ   =   {0, 1}. A =   {0n1n|n ≥   0}   is   not   a   regular   language   and
B =   {0m1n|m, n ≥   0}   is   a   regular   language.



         
加QQ：99515681  WX：codinghelp
