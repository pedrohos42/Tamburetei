5ª Lista de Exercícios de Teoria da Computação
Prof. Andrey Brito

01. Prove que as linguagens abaixo são decidíveis:
L1 = {<R,w> | R é uma expressão regular que gera a cadeia w }
L2 = {<G> | G é uma Gramática Livre de Contexto e L(G) = ∅ }

02. Considere as linguagens L1 e L2 sendo linguagens reconhecíveis e as linguagens L3 e L4 sendo decidíveis. Informe se a linguagem resultante a cada operação abaixo é reconhecível ou decidível. Justifique.
    1. L1 ∩ L2
    2. L1 ∩ L3
    3. L3 ∪ L4
    4. L1 ∪ L3
    5. (L1 ∩ L2) ∪ L3
    6. (L1 ∩ L3) ∪ Complemento(L3)

3.  Avalie as afirmações em verdadeiro ou falso, justificando as afirmações falsas
( ) Sendo as linguagens L1, L2 e L3 linguagens regulares ou livre-de-contexto, não é possível categorizá-las como decidíveis ou reconhecíveis apenas com estas informações.
(  ) A possibilidade de criação de um enumerador para uma linguagem nada implica sobre sua reconhecibilidade ou decidibilidade.
(  ) É possível criar uma máquina de turing para qualquer linguagem livre de contexto ou regular.
(  ) Uma Máquina de Turing Multifita reconhece uma classe de linguagens maior do que uma Máquina de Turing de uma fita só.

04. Prove que a linguagem L = {<M1,M2> | M1 e M2 são Máquinas de Turing e L(M1) = L(M2)} é indecidível.
