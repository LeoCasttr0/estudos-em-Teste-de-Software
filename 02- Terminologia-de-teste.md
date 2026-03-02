
#  Erro, Defeito e Falha

## Objetivo
Entender os conceitos de **Erro**, **Defeito** e **Falha** no contexto de teste de software e aprender a diferenciar cada um com exemplos práticos.

---

## Conceitos

### 1. Erro
- **Definição:** Uma ação incorreta feita pelo desenvolvedor ou pelo usuário que pode levar a um defeito no sistema.  
- **Exemplo:** Um desenvolvedor escreve `x = y + z` quando deveria ser `x = y - z`.  

### 2. Defeito
- **Definição:** Uma imperfeição ou bug no software que foi causado por um erro.  
- **Exemplo:** O código acima (`x = y + z`) gera um resultado errado no cálculo do sistema.  
- **Obs:** É algo que **existe no sistema**, mas ainda não necessariamente causou problemas visíveis ao usuário.  

### 3. Falha
- **Definição:** Quando o defeito se manifesta durante a execução do sistema, causando comportamento inesperado ou incorreto.  
- **Exemplo:** O sistema calcula o valor final errado e mostra ao usuário um total incorreto em uma nota fiscal.  

---

## Resumo Visual

| Termo   | O que é                               | Exemplo |
|---------|--------------------------------------|---------|
| Erro    | Ação incorreta de alguém              | Digitar `+` em vez de `-` no código |
| Defeito | Problema no código ou sistema         | Cálculo errado implementado no software |
| Falha   | Problema se manifesta no uso real     | Usuário vê valor incorreto na nota fiscal |

---

## Conclusão
- Um **erro** leva a um **defeito**, e quando o defeito é executado no sistema, ele gera uma **falha**.  
- Entender essa diferença ajuda a **organizar testes e priorizar correções** de forma mais eficiente.
