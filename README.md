# Lista-1
Logica
1-a) Não é uma fórmula da Lógica Proposicional, pois contém um símbolo inválido o numeral 10.000.

1-b) É uma fórmula da Lógica Proposicional, pois contém apenas símbolos válidos da Lógica Proposicional.

1-c) É uma fórmula da Lógica Proposicional, pois, um símbolo proposicional válido (P) e a negação (¬), que é um símbolo lógico válido na regra.

1-d) Não é uma fórmula da Lógica Proposicional, pois tem que ter pelo menos duas fórmulas proposicionais ou expressões lógicas para formar uma disjunção.

1-e) É uma fórmula da Lógica Proposicional, pois contém apenas símbolos válidos da Lógica Proposicional.

2-a) Sim, pois somente quando uma fórmula composta de um único símbolo de verdade ou algum símbolo proposicional.

2-b) Tem 4, símbolos de pontuação, símbolos proposicionais, símbolos de verdade e conectivos proposicionais.

2-c) Não,não existe fórmula da Lógica Proposicional com algum conectivo, mas sem símbolo de pontuação.

3-a)H=((¬¬P ∨ Q) ↔ (P → Q)) ∧ P10.000
Comp[H]=((¬¬P ∨ Q) ↔ (P → Q)) ∧ P10.000
Comp[H]=((¬¬P ∨ Q) ↔ (P → Q)) comp[P10.000]+1
Comp[H]=((¬¬P ∨ Q)(P → Q)) comp[P10.000]+1+1
Comp[H]=((¬¬P ∨ Q)+comp[P]+comp[Q]+1+3
Comp[H]=comp[P]+comp[Q]+1+1+1+6
comp[H]=1+1+1+1+1+6
comp[H]=11
Subformula= {((¬¬P ∨ Q) ↔ (P → Q)) ∧ P10.000, P, Q, P10.000, ((¬¬P ∨ Q) ↔ (P → Q)), (P → Q),  , (¬¬P ∨ Q), ¬¬P,¬P}

b)  H= P → ((Q → R) → ((P → R) → (P → R)))
Comp[H] = Comp[P]+1+ ((Q → R) → ((P → R) → (P → R)))
Comp[H] = 1+1+Comp[Q]+Comp[R]+1+1+1+(P → R)+(P → R)
Comp[H] = 7+Comp[P]+Comp[R]+1+Comp[P]+Comp[R]+1
Comp[H] = 7+1+1+1+1+1+1
Comp[H] = 13

Subformula{ P → ((Q → R) → ((P → R) → (P → R))), P, Q, R, ((Q → R) → ((P → R) → (P → R), (P → R)+(P → R)}

c) H = ((P → ¬P) ↔ ¬P) ∨ Q
Comp[H] = ((P → ¬P) ↔ ¬P) + Comp[Q] + 1
Comp[H] = (P → ¬P) + Comp[P] + 1 + 1 + 2
Comp[H] = Comp[P]+1+Comp[P]+1+5
Comp[H] = 1 + 1 + 1 + 1 + 5
Comp[H] = 9
Subformula{((P → ¬P) ↔ ¬P) ∨ Q; P; Q; ((P → ¬P) ↔ ¬P); (P → ¬P)}

d) H = ¬(P → ¬P)
Comp[H] = 1 + Comp[P] + 1 + Comp[P] + 1
Comp[H] = 5
Subformula{¬(P → ¬P), P, ¬P, P-> }

4-a)((¬(¬P)) ↔ ((¬((¬(¬(P ∨ Q))) → R)) ∧ P))
((¬(¬P))<->((¬((¬¬(P V Q))-> R))^P))
((¬(¬P)) <-> ((¬((¬¬(P V Q))-> R))^P))
((¬¬P)<->((¬((¬¬(PVQ))->R))^P))

b) (¬P → (Q ∨ R)) ↔ ((P ∧ Q) ↔ (¬¬R ∨ ¬P))
Nada para retirar

c)(( P ∨Q) → (P → (¬Q)))
( P ∨ Q) → (P → ¬Q)
(P V Q) -> (P -> ¬Q)
(P V Q) -> P ->¬Q

5-a)
P ∨ ¬Q → R → ¬R
(P ∨ ¬Q) → R → ¬R
(P ∨ ¬Q) → (R → ¬R)
(P ∨ (¬Q → R)) → ¬R
P ∨ (¬Q → (R → ¬R))
P ∨ ¬(Q → R → ¬R)

b)
Q → ¬P ∧ Q
Q → (¬P ∧ Q)
Q → ¬(P ∧ Q)

c)
¬P ∨ Q ↔ Q
(¬P ∨ Q) ↔ Q
¬(P ∨ Q) ↔ Q
¬(P ∨ Q ↔ Q)

d)
¬¬P → Q ≡ P ∧ P¬¬R
Esta não é uma fórmula válida

6-Exercício 3
a) ∧ <-> ∨ ¬¬PQ ->PQtrue
b) ->P->->QR->->PR->PR
c) ∨ <->->P¬P¬PQ
d) ¬ ->P¬P
Exercício 4
a) <-> ∧¬ -> ¬¬∨PQRP¬¬P
b) <->-> ¬P∨QR<-> ∧PQ∨¬¬R¬P
c) ->∨PQ->P¬Q

7-a)



10)
a) Seria um numero impar

b) é o dobro de conectivos, mais um


Capitulo 2

2-

3- A formula ^ ≠ v, exemplo de afirmações --   Afirma que vou ao cinema e teatro.
<-> implicação desse conectivo afirma que ao ir para o cinema tambem ira ao teatro.
¬ negação aqui nega qualquer ação, como exemplo não irei al cinema.

4-a) I[P} = T
b) I [Q] = T
c) I[H] = T
d) Não se pode finalizar
e) I[H] = F

5-a) (¬P ∨ Q) ↔ (P → Q): Esta fórmula é conhecida como a lei do meio excluído e afirma que para qualquer proposição P, ou P é verdadeiro ou ¬P é verdadeiro, e não há meio chão.

b) P → ((Q → R) → ((P → R) → (P → R))): Esta fórmula é uma tautologia, o que significa que é sempre verdadeira.

c) (P → ¬Q) ↔ ¬P: Esta fórmula é conhecida como a contrapositiva do modus tollens e afirma que se P implica não Q, então não P também deve ser verdadeiro.

d) (Q → ¬P): Esta fórmula afirma que se Q é verdadeiro, então P deve ser falso.

e) (P → (Q → R)) ↔ ((P ∧ Q) → R): Esta fórmula é conhecida como a lei da separação e afirma que se P implica Q implica R, então P e Q juntos implicam R.

f) (R ∧ ¬P) ↔ (P ∧ R): Esta fórmula é comutativa e não fornece quaisquer implicações adicionais.

g) (P → Q) → (((P ∧ Q) ↔ P) ∧ ((P ∨ Q) ↔ Q)): Esta fórmula é uma tautologia e sempre verdadeira.

h) (falso → Q) ↔ R: Esta fórmula é equivalente a ¬Q ↔ R, significando que Q é falso se e somente se R for verdadeiro.

i) verdadeiro → Q: Esta fórmula implica que Q deve ser verdadeiro.

j) (P → falso) ↔ R: Esta fórmula é equivalente a P ↔ ¬R, significando que P é verdadeiro se e somente se R é falso.

k) P → verdadeiro: Esta fórmula implica que P deve ser verdadeiro.

6-a) I[(P ∨ R) → (Q ∨ R)]: Esta fórmula pode ser reescrita como (¬(P ∨ R) ∨ (Q ∨ R)), que é equivalente a (¬P ∧ ¬R) ∨ (Q ∨ R). Como I[P → Q] = T, sabemos que P é falso ou Q é verdadeiro. Portanto, podemos deduzir que (¬P ∧ ¬R) ∨ (Q ∨ R) deve ser verdadeiro, pois pelo menos um dos disjuntos deve ser verdadeiro.

b) I[(P ∧ R) → (Q ∧ R)]: Esta fórmula pode ser reescrita como (¬(P ∧ R) ∨ (Q ∧ R)), que é equivalente a (¬P ∨ ¬R ∨ Q ∨ R). Como I[P → Q] = T, sabemos que P é falso ou Q é verdadeiro. Portanto, podemos deduzir que (¬P ∨ ¬R ∨ Q ∨ R) deve ser verdadeiro, pois pelo menos um dos disjuntos deve ser verdadeiro.

c) I[(¬P ∨ Q) → (P ∨ Q)]: Esta fórmula pode ser reescrita como ¬(¬P ∨ Q) ∨ (P ∨ Q), que é equivalente a (P ∧ ¬Q) ∨ (P ∨ Q). Como I[P → Q] = T, sabemos que P é falso ou Q é verdadeiro. Portanto, podemos deduzir que (P ∧ ¬Q) ∨ (P ∨ Q) deve ser verdadeiro, pois pelo menos um dos disjuntos deve ser verdadeiro.

7-a) I[¬P ∧ Q]: Q deve ser verdadeiro.
b) I[P ∨ ¬Q]: Q pode ser verdadeiro ou falso.
c) I[Q → P]: Q implica que P deve ser verdadeiro.
d) I[(P ∧ R) ↔ (Q ∧ R)]: (P ∧ R) é verdadeiro se e somente se (Q ∧ R) é verdadeiro.
e) I[(P ∨ R) ↔ (Q ∨ R)]: (P ∨ R) é verdadeiro se e somente se (Q ∨ R) é verdadeiro.

8-a)Se I[P] = F, não podemos tirar nenhuma conclusão sobre I[H], porque o antecedente de H é falso independentemente do valor verdadeiro de H.

b)Se I[P] = T, I[H] = T porque o antecedente de H é verdadeiro, e o consequente também é verdadeiro devido à equivalência dos dois conjuntos da conjunção. Portanto, toda a fórmula H é verdadeira quando I[P] = T.

10-a) José virá à festa e Maria não gostará, ou José não virá à festa e Maria
gostará da festa.
(p ∧ ¬q) ∨ (¬p ∧ q)

b) A novela será exibida, a menos que seja exibido o programa político.

A sentença pode ser representada como: P ∨ ¬Q

c) Se chover, irei para casa, caso contrário, carei no escritório.
A frase pode ser representada como: P → Q, que pode ser lida como "Se chover, eu irei para casa".

d) Se Maria é bonita, inteligente e sensível e se Rodrigo ama Maria, então
ele é feliz.

A frase pode ser representada como: (P ∧ Q ∧ R ∧ S) → Z, que pode ser lida como Se Maria é bonita, inteligente e sensível, e se Rodrigo ama Maria, então ele é feliz.

12-a) É difícil representar Possivelmente irei ao cinema na lógica proposicional, pois a frase se refere a uma possibilidade e não a uma proposição definida.

b) Seja p representando eu era gordo e q represente "estou magro hoje. A frase pode ser representada como p ∧ q, que significa "eu era gordo e hoje sou magro.

c) Seja p representando "Há um aluno" e q represente "Todos os alunos o admiram". A frase pode ser representada como p ∧ q, que significa "Há um aluno admirado por todos no curso de Ciência da Computação".

d) Seja p representando Há um aluno na minha classe e q represente Ele não gosta de nenhum de seus colegas. A frase pode ser representada como p ∧ q, que significa Tem um aluno na minha classe que não gosta de nenhum dos colegas."

e) Seja p representando Há um estudante de Ciência da Computação e q represente Seus colegas o odeiam. A frase pode ser representada como p ∧ q, que significa Há um aluno de Ciência da Computação que é odiado pelos colegas.

f) Seja p representando Algum político é desonesto. A frase pode ser representada como p, que significa Necessariamente algum político é desonesto.

g) Seja p representando Amanhã irei ao cinema eq representa Irei ao teatro depois do cinema. A frase pode ser representada como p ∧ q, que significa Amanhã irei ao cinema e depois irei ao teatro.

h) Seja p representando políticos e q represente desonesto. A frase pode ser representada como ¬(P)(P ∧ ¬Q), que significa Quase todo político é desonesto.

i) Seja p representando Adalton e q represente João Augusto. A frase pode ser representada como (R)(P ∧ Q), que significa Adalton sempre foi amigo de João Augusto.

j) Seja p represente Toda regra e q represente Tem uma exceção. A sentença pode ser representada como (R)(P → Q), que significa Toda regra tem uma exceção.
