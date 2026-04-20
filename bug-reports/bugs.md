Bug report - SauceDemo

BUG001 - Mensagem de erro genérica no login
Severidade: Média
Prioridade: Média

Passos
1. Inserir senha inválida
2. Clicar no botão Login

Resultado atual
É exibida uma mensagem genérica: "Username and password do not match any user in this service"

Resultado esperado
Mensagem de erro mais específica informando onde está o erro, por exemplo: "Incorrect password"

---

BUG002 - Erro na descrição do produto Sauce Labs Backpack
Severidade: Baixa
Prioridade: Média

Passos
1. Clicar no link do produto
2. Verificar as informações

Resultado atual
É exibido um texto com formatação incorreta: "carry.allTheThings()"

Resultado esperado
Texto com formatação correta: "Carry all the things"

---

BUG003 - Erro no título e na descrição do produto Sauce Labs Bolt T-Shirt
Severidade: Média
Prioridade: Média

Passos
1. Clicar no link do produto
2. Verificar as informações

Resultado atual
O título e a descrição do produto "heather gray with red bolt" não condizem com a imagem, que mostra uma camiseta preta sem estampa

Resultado esperado
A imagem deve mostrar uma camiseta cinza com um raio vermelho

---

BUG004 - Erro no título e na descrição do produto Test.allTheThings() T-Shirt (Red)
Severidade: Média
Prioridade: Média

Passos
1. Clicar no link do produto
2. Verificar as informações

Resultado atual
- O título e a descrição do produto "red t-shirt" não condizem com a imagem, que mostra uma blusa de moletom laranja
- É exibido um texto com formatação incorreta: "Test.allTheThings()"

Resultado esperado
- A imagem deve mostrar uma camiseta vermelha 
- Texto com formatação correta: "Test all the things"

---

BUG005 - Erro no botão Add to cart
Severidade: Alta
Prioridade: Alta

Passos
1. Entrar com o usuário problem_user
1. Clicar no botão Add to cart do produto desejado
3. Verificar se o botão foi alterado para Remove e se o produto foi adicionado ao carrinho

Resultado atual
Ao clicar no botão Add to cart, não há nenhuma mudança de estado, ou seja, ele não é alterado para Remove e o produto não é adicionado ao carrinho

Resultado esperado
Ao clicar no botão Add to cart, ele deverá ser alterado para Remove e o produto deverá ser adicionado ao carrinho

---

BUG006 - Erro no valor total dos produtos
Severidade: Média
Prioridade: Média

Passos
1. Adicionar mais de um produto ao carrinho
2. Clicar no ícone de carrinho
3. Verificar se é exibido o valor total no final da página

Resultado atual
Quando mais de um produto é adicionado ao carrinho, a página de carrinho não exibe o valor total

Resultado esperado
Quando mais de um produto for adicionado ao carrinho, a página de carrinho deverá exibir o valor total