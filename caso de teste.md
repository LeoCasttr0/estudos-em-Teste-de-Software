# Caso de Teste – Tela de Login (Usuário e Senha)

| Ação | Resultado Esperado |
|------|------------------|
| **Caso 1 – Login válido**<br>1. Abrir a tela de login<br>2. Inserir usuário válido<br>3. Inserir senha válida<br>4. Clicar em "Entrar" | Usuário é autenticado e redirecionado para a tela principal |
| **Caso 2 – Senha inválida**<br>1. Abrir a tela de login<br>2. Inserir usuário válido<br>3. Inserir senha inválida<br>4. Clicar em "Entrar" | Sistema exibe mensagem de erro: "Usuário ou senha incorretos" |
| **Caso 3 – Usuário inválido**<br>1. Abrir a tela de login<br>2. Inserir usuário inexistente<br>3. Inserir qualquer senha<br>4. Clicar em "Entrar" | Sistema exibe mensagem de erro: "Usuário não encontrado" |
| **Caso 4 – Campos vazios**<br>1. Abrir a tela de login<br>2. Deixar campos usuário e senha vazios<br>3. Clicar em "Entrar" | Sistema exibe alerta: "Por favor, preencha todos os campos" |
