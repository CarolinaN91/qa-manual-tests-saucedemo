Casos de testes - Login no SauceDemo

CT001 - Login com sucesso
Pré-condição: usuário válido

Passos
1. Acessar https://www.saucedemo.com/
2. Inserir usuário standard_user
3. Inserir senha secret_sauce
4. Clicar no botão Login

Resultado esperado
O usuário deve acessar a página inicial

---

CT002 - Login com erro

Passos
1. Acessar https://www.saucedemo.com/
2. Inserir usuário inválido
3. Inserir senha inválida
4. Clicar no botão Login

Resultado esperado
Uma mensagem de erro deve ser exibida