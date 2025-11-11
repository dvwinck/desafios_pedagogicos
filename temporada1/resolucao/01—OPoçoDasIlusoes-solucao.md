# Desafio 1 — O Poço das Ilusões
Um sapo está preso num poço de 30 metros de profundidade.

Ele sobe 3,5 metros durante o dia, mas à noite escorrega 2 metros.

A cada 5 dias, o sapo fica mais cansado e passa a:

subir 0,2 metro a menos por dia;
escorregar 0,1 metro a menos por noite.
Pergunta: Em quantos dias o sapo sairá do poço, considerando todos esses fatores?

##Pergunta:
Em quantos dias o sapo conseguirá sair do poço, considerando todas as variações acima?
---

### 📘 Dados do problema

* Profundidade do poço: **30 metros**
* Dia 1: sobe **3,5 m**, desce **2,0 m**
* A cada **5 dias**:

  * sobe **0,2 m a menos**,
  * escorrega **0,1 m a menos**.
* O sapo **não escorrega na noite em que sai**.

---

### 📊 Tabela de progresso diário

| Dia | Sobe (m) | Desce (m) | Evento                            | Altura ao fim do dia (m) | Altura ao fim da noite (m) |
| --- | -------- | --------- | --------------------------------- | ------------------------ | -------------------------- |
| 1   | 3.5      | 2.0       | —                                 | 3.5                      | 1.5                        |
| 2   | 3.5      | 2.0       | —                                 | 5.0                      | 3.0                        |
| 3   | 3.5      | 2.0       | —                                 | 6.5                      | 4.5                        |
| 4   | 3.5      | 2.0       | —                                 | 8.0                      | 6.0                        |
| 5   | 3.5      | 2.0       | **Fadiga → sobe 3.3 / desce 1.9** | 9.5                      | 7.6                        |
| 6   | 3.3      | 1.9       | —                                 | 10.9                     | 9.0                        |
| 7   | 3.3      | 1.9       | —                                 | 12.3                     | 10.4                       |
| 8   | 3.3      | 1.9       | —                                 | 13.7                     | 11.8                       |
| 9   | 3.3      | 1.9       | —                                 | 15.1                     | 13.2                       |
| 10  | 3.3      | 1.9       | **Fadiga → sobe 3.1 / desce 1.8** | 16.5                     | 14.7                       |
| 11  | 3.1      | 1.8       | —                                 | 17.8                     | 16.0                       |
| 12  | 3.1      | 1.8       | —                                 | 19.1                     | 17.3                       |
| 13  | 3.1      | 1.8       | —                                 | 20.4                     | 18.6                       |
| 14  | 3.1      | 1.8       | —                                 | 21.7                     | 19.9                       |
| 15  | 3.1      | 1.8       | **Fadiga → sobe 2.9 / desce 1.7** | 23.0                     | 21.3                       |
| 16  | 2.9      | 1.7       | —                                 | 23.9                     | 22.2                       |
| 17  | 2.9      | 1.7       | —                                 | 24.8                     | 23.1                       |
| 18  | 2.9      | 1.7       | —                                 | 25.7                     | 24.0                       |
| 19  | 2.9      | 1.7       | —                                 | 26.6                     | 24.9                       |
| 20  | 2.9      | 1.7       | **Fadiga → sobe 2.7 / desce 1.6** | 27.5                     | 25.9                       |
| 21  | 2.7      | 1.6       | —                                 | 28.6                     | **— Saiu!**                |

---

### ✅ **Conclusão**

O sapo **sai do poço no dia 21**.

No início do dia 21 ele sobe 2,7 metros a partir de 25,9 m, atingindo **28,6 m**, mas ao final do próximo dia ele ultrapassa os 30 m — portanto, ele **escapa ao fim do dia 21**, **sem escorregar à noite**.

---

### 💡 Interpretação

* **Progresso líquido inicial:** +1,5 m/dia.
* **Progresso após 15 dias:** +1,2 m/dia.
* O sapo mantém um avanço médio positivo e **sai antes da 5ª fadiga**.

Esse tipo de problema é excelente para introduzir **progressões com decremento periódico**, **simulação lógica** e **padrões de convergência não linear**.
