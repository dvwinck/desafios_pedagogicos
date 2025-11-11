**1. Título**
**O Enigma dos Pontos e Triângulos**

---

**2. Contexto / História curta**

O Oráculo da Razão surgiu em meio às brumas do deserto geométrico e falou:

> “Toda forma nasce da relação entre pontos.
> Quando há apenas um, há solidão.
> Com dois, há linha.
> Com três, o primeiro universo se fecha — o triângulo.
> Mas e quando o mundo cresce? Quando o aprendiz lança mais e mais pontos no espaço,
> quantos universos podem ser criados a partir deles?”

Dizem que os antigos geômetras tentaram responder a isso e perderam-se em linhas infinitas e ângulos improváveis. Agora, é tua vez de continuar o raciocínio que começou há milênios.

---

**3. Regras e Dados**

1. Todos os pontos estão no mesmo plano (não no espaço tridimensional).
2. Nenhum trio de pontos está perfeitamente alinhado (ou seja, qualquer três pontos distintos podem formar um triângulo).
3. Um triângulo é definido pela escolha de **3 pontos distintos** entre os disponíveis.
4. À medida que novos pontos são adicionados, as combinações possíveis de triângulos crescem rapidamente — mas nem sempre de forma intuitiva.

O aprendiz deve descobrir:

* Quantos triângulos podem ser formados com 5 pontos?
* Com 7 pontos?
* Com 10 pontos?
* E, finalmente, se existe uma **fórmula genérica** que permita descobrir esse número para qualquer quantidade ( n ) de pontos no plano.

Mas cuidado: o Oráculo adverte que **nem toda combinação é visível de imediato** — há uma forma de contá-las sem precisar desenhá-las todas.

---

**4. Pergunta principal**

Quantos triângulos distintos podem ser formados a partir de ( n ) pontos não colineares, para ( n = 5, 7, 10 )?
E qual é a fórmula geral que expressa esse crescimento?

---

**5. Dicas (Progressivas)**

**Dica 1 (Nível 1):**
Não tente desenhar todos os triângulos. O segredo está em **contar combinações**, não em visualizá-las.

**Dica 2 (Nível 2):**
Cada triângulo é formado pela **escolha de 3 pontos distintos** entre os ( n ) disponíveis. Há uma notação matemática para esse tipo de contagem: ( C(n, 3) ), ou “n escolhe 3”.

**Dica 3 (Nível 3):**
A fórmula de combinação é:
[
C(n, 3) = \frac{n \times (n - 1) \times (n - 2)}{6}
]
Atenção: ela só vale se **nenhum trio de pontos estiver alinhado**. Caso alguns estejam, o número real de triângulos é menor.

---
