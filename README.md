# ⚡ Bubble Sort — Controle de Consumo de Energia

**Descubra quais eletrodomésticos são os maiores "vilões" da sua conta de luz.**

![Linguagem C](https://img.shields.io/badge/Linguagem-C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Algoritmo](https://img.shields.io/badge/Algoritmo-Bubble%20Sort-FF6B35?style=for-the-badge&logo=thealgorithms&logoColor=white)
@@ -25,7 +24,7 @@
| | |
|---|---|
| **Disciplina** | Algoritmos e Pensamento Computacional |
| **Professora** | Karla |
| **Professora** | Karla Roberto  |

---

@@ -97,13 +96,13 @@ Desenvolver um programa em linguagem C que armazene o consumo mensal (em kWh) de

É possível rodar o projeto no [OnlineGDB](https://www.onlinegdb.com/online_c_compiler), criando os arquivos `.c` e `.h` no mesmo ambiente e executando o `main.c`.

### Localmente com GCC
### Localmente com GCC no VSCode
Abra a pasta do projeto no VS Code, abra o terminal (Ctrl+') e compile e execute:

```bash
gcc main.c dados.c bubble.c interface.c -o consumo
./consumo
```

---

## 🫧 Funcionamento do Bubble Sort
@@ -193,8 +192,6 @@ Dica: priorize economizar nos maiores consumos!

## 🖥️ Módulo de Interface (`interface.c` / `interface.h`)

**Responsável:** Safira

Este módulo cuida de tudo o que aparece na tela (terminal). Ele não ordena nem guarda dados: apenas mostra as informações de forma clara e organizada para o usuário.

### Arquivos
