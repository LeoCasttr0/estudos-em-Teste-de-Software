# 📘 Aula 7 – Níveis e Tipos de Teste

Nesta aula aprendemos que o teste não é uma atividade única.  
Ele acontece em diferentes **níveis (onde testar)** e possui diferentes **tipos (o que testar)**.

---

# 🔹 1. Níveis de Teste

Os níveis de teste estão relacionados:

- 📌 À fase em que o software se encontra  
- 📌 Ao tamanho da parte que está sendo testada  

À medida que o sistema evolui, o nível de teste também evolui.

---

## 1️⃣ Teste de Componente (ou Unitário)

Testa as **menores partes do sistema individualmente**, como:

- Funções  
- Métodos  
- Classes  

**Características:**

- Geralmente realizado pelo próprio desenvolvedor  
- Exige acesso ao código-fonte  
- Foco na lógica interna  

**Objetivo:**

- Identificar erros de lógica  
- Evitar que pequenos defeitos comprometam outras partes do sistema  

---

## 2️⃣ Teste de Integração

Verifica como os **componentes interagem entre si**.

**Foco:**

- Comunicação entre módulos  
- Troca de dados  
- Integração com sistemas externos (ex: APIs)

**Objetivo:**

- Garantir que as partes funcionem corretamente quando conectadas  

---

## 3️⃣ Teste de Sistema

Avalia o **sistema completo como um todo**.

**Verifica:**

- Requisitos funcionais  
- Regras de negócio  
- Regras contratuais  
- Normas legais (quando aplicável)  
- Expectativas dos stakeholders  

**Objetivo:**

- Validar o comportamento global do produto  

---

## 4️⃣ Teste de Aceite

É o nível focado na validação final antes do lançamento.

**Características:**

- Envolve usuários finais ou clientes  
- Ocorre antes da disponibilização oficial  

**Exemplos:**

- Teste Alfa  
- Teste Beta  

**Objetivo:**

- Confirmar que o sistema atende às necessidades reais do usuário  

---

# 🔹 2. Tipos de Teste

Enquanto os **níveis** indicam *onde testar*, os **tipos** indicam *o que está sendo avaliado*.

---

## 1️⃣ Teste Funcional

Avalia **o que o sistema faz**.

- As funcionalidades estão corretas?  
- Os requisitos foram implementados corretamente?  

---

## 2️⃣ Teste Não Funcional

Avalia **como o sistema se comporta**.

Inclui:

- ⚡ Performance (tempo de resposta, velocidade)  
- 🔒 Segurança  
- 👤 Usabilidade  
- 📈 Escalabilidade  

---

## 3️⃣ Teste Estrutural

Avalia a **estrutura interna do código**.

Verifica:

- Caminhos lógicos  
- Fluxo de dados  
- Cobertura de código  

---

## 4️⃣ Testes Relacionados a Alterações

Realizados após modificações no sistema.

### ✔ Confirmação (Reteste)

- Verifica se um defeito corrigido realmente foi resolvido  

### ✔ Regressão

- Garante que uma correção não afetou funcionalidades que já estavam funcionando corretamente  

---

# 📌 Resumo

- **Níveis → Onde testar**  
- **Tipos → O que testar**
