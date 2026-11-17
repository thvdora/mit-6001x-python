# 🐍 Curso edX — Introdução à Ciência da Computação com Python

Repositório com os exercícios, problem sets e a prova final que resolvi durante o curso de **Introdução à Ciência da Computação e Programação com Python** na plataforma [edX](https://www.edx.org/).

O objetivo do repositório é documentar meu aprendizado de lógica de programação e Python, desde estruturas básicas até recursão, programação orientada a objetos e pequenos jogos/aplicações.

## 📚 Conteúdo abordado

- Variáveis, tipos de dados, `input` e `print`
- Estruturas condicionais e laços (`for`, `while`)
- Manipulação de strings
- Funções, recursão e iteração
- Algoritmos de busca: **bisseção** e **busca binária**
- Listas, tuplas e dicionários
- Leitura de arquivos
- Programação orientada a objetos (classes, herança, `super()`)
- Testes unitários simples
- Criptografia clássica (cifra de César)

## 🗂️ Estrutura do repositório

```
Curso EDX python/
├── bisection.py          # Raiz quadrada aproximada pelo método da bisseção
├── CharIsIn.py           # Busca binária recursiva de um caractere em uma string ordenada
├── iterpower.py          # Potência de forma iterativa
├── recurpower.py         # Potência de forma recursiva
├── secretnumber.py       # Jogo: o computador adivinha seu número secreto (bisseção)
├── ProblemSet1/          # Strings e laços
├── ProblemSet2/          # Cálculos financeiros (saldo de cartão e pagamento mínimo)
├── ProblemSet4/          # Jogo de palavras (estilo Scrabble)
├── ProblemSet5/          # Cifra de César: criptografar e descriptografar mensagens
└── FinalExam/            # Exercícios da prova final
```

## 🧩 Detalhes dos problem sets

### Problem Set 1 — Strings e laços
| Arquivo | Descrição |
|---|---|
| `unit1problem1.py` | Conta o número de vogais em uma string |
| `unit1problem2.py` | Conta quantas vezes a sequência `bob` aparece em uma string |
| `unit1problem3.py` | Encontra a maior substring em ordem alfabética |

### Problem Set 2 — Cálculos financeiros
| Arquivo | Descrição |
|---|---|
| `unit2problem1.py` | Calcula o saldo restante de um cartão de crédito após 12 meses pagando o valor mínimo |
| `unit2problem2.py` | Descobre o menor pagamento mensal fixo para quitar a dívida em 12 meses |

### Problem Set 4 — Jogo de palavras
Implementação de um jogo de palavras no estilo Scrabble, jogável por uma pessoa ou pelo computador.

| Arquivo | Descrição |
|---|---|
| `ps4a.py` | Lógica do jogo: pontuação, sorteio e atualização da mão, validação de palavras e `playHand`/`playGame` |
| `ps4b.py` | Jogador computador (`compChooseWord`, `compPlayHand`) e modo de jogo completo |
| `handClass.py` | Classe `Hand` que representa a mão de letras |
| `test_ps4a.py` | Testes unitários das funções de `ps4a.py` |
| `words.txt` | Lista de palavras válidas |

### Problem Set 5 — Cifra de César
Classes `Message`, `PlaintextMessage` e `CiphertextMessage` para criptografar mensagens com um deslocamento (*shift*) e descriptografar automaticamente textos cifrados, testando todos os deslocamentos possíveis e escolhendo o que gera mais palavras válidas.

| Arquivo | Descrição |
|---|---|
| `ps5.py` | Implementação das classes e da função `decrypt_story` |
| `story.txt` | Texto cifrado a ser decifrado |
| `words.txt` | Lista de palavras válidas |

### Final Exam
| Arquivo | Descrição |
|---|---|
| `McNuggets.py` | Verifica se é possível comprar exatamente *n* McNuggets em caixas de 6, 9 e 20 |
| `permutation.py` | Verifica se uma lista é permutação de outra e retorna o elemento mais frequente |
| `dictionary.py` | Retorna, em ordem, as chaves de um dicionário cujos valores são únicos |
| `classes.py` | Hierarquia de classes `Person` → `Lecturer` → `Professor` → `ArrogantProfessor` |

## ▶️ Como executar

Requisitos: [Python 3.10+](https://www.python.org/downloads/)

```bash
# Clone o repositório
git clone https://github.com/<seu-usuario>/<nome-do-repositorio>.git
cd "<nome-do-repositorio>/Curso EDX python"

# Execute um exercício
python bisection.py
python secretnumber.py

# Jogo de palavras (execute dentro da pasta, pois lê o words.txt)
cd ProblemSet4
python ps4b.py

# Testes do jogo de palavras
python test_ps4a.py

# Cifra de César
cd ../ProblemSet5
python ps5.py
```

> **Obs.:** alguns arquivos dos Problem Sets 1 e 2 (`unit1problem1.py`, `unit2problem1.py`, `unit2problem2.py`) usam variáveis como `s`, `balance` e `annualInterestRate`, que no curso são fornecidas pelo avaliador automático da edX. Para rodá-los localmente, defina essas variáveis antes do código.

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 👩‍💻 Autora

**Isadora Soares Couto**
Estudante de Ciência da Computação — FIAP

- GitHub: [[@thvdora](https://github.com/thvdora)
- LinkedIn: (https://www.linkedin.com/in/isadora-couto/)

## Aviso:
Os enunciados dos exercícios pertencem ao curso da edX. Este repositório contém apenas as minhas soluções, para fins de estudo e portfólio.
