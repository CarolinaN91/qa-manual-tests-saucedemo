QA manual tests - SauceDemo

Objetivo

Este projeto tem como objetivo aplicar práticas de Qualidade de Software (QA) em um ambiente de e-commerce simulado (SauceDemo), realizando testes manuais funcionais, exploratórios, negativos e de validação de fluxo completo do usuário.

O foco é demonstrar habilidades em criação de casos de teste, execução de cenários e documentação de bugs.

---

Sistema testado

SauceDemo - aplicação de e-commerce demo utilizada para práticas de testes manuais.

---

Escopo dos testes

Foram testadas as seguintes funcionalidades:

- Login de usuários
- Listagem de produtos
- Carrinho de compras
- Fluxo de checkout

---

Tipos de testes

- Testes funcionais
- Testes exploratórios
- Testes negativos
- Testes de usabilidade (UX)

---

Ferramentas

- Navegador Google Chrome
- Git e GitHub

---

Resultado dos testes

- Total de cenários executados: 8
- Bugs encontrados: 8
- Fluxos críticos validados com sucesso: 100%

---

Resumo dos testes

Os testes realizados validaram os fluxos de login, produtos, carrinho e checkout.

Foram identificados pontos de melhoria relacionados a:

- Clareza de mensagens de erro
- Formatação
- Compatibilidade entre imagem e título/descrição de produtos
- Funcionamento de botões
- Validação de dados

O fluxo de checkout não pôde ser concluído com êxito.

---

Resumo dos bugs

- BUG001 - Mensagem de erro genérica no login
    - Impacto: atrasa a detecção e correção do problema, causa frustração no usuário e pode fazer com que ele desista de uma compra
    - Sugestão: gerar mensagens de erro separadas para erro no usuário e erro na senha

- BUG002 - Erro na descrição do produto Sauce Labs Backpack
    - Impacto: causa impressão de falta de profissionalismo e atrapalha o funcionamento de leitores de tela
    - Sugestão: corrigir formatação

- BUG003 - Erro no título e na descrição do produto Sauce Labs Bolt T-Shirt
    - Impacto: causa impressão de falta de profissionalismo, atrapalha o funcionamento de leitores de tela, gera frustração no cliente ao receber algo diferente do que esperava e pode causar prejuízos financeiros como devolução do produto e perda de cliente
    - Sugestão: corrigir a imagem

- BUG004 - Erro no título e na descrição do produto Test.allTheThings() T-Shirt (Red)
    - Impacto: causa impressão de falta de profissionalismo, atrapalha o funcionamento de leitores de tela, gera frustração no cliente ao receber algo diferente do que esperava e pode causar prejuízos financeiros como devolução do produto e perda de cliente
    - Sugestão: corrigir a imagem e a formatação do título

- BUG005 - Erro no botão Add to cart
    - Impacto: gera frustração no cliente por não conseguir adicionar o produto desejado no carrinho, o que pode causar prejuízos financeiros como a perda do cliente
    - Sugestão: corrigir o botão

- BUG006 - O valor total dos produtos não é exibido
    - Impacto: atrapalha a experiência do usuário, que não consegue ver quanto será gasto no pedido
    - Sugestão: adicionar a soma dos produtos no carrinho

- BUG007 - A aplicação aceita dados inválidos no checkout
    - Impacto: a finalização de um pedido com dados inválidos pode atrapalhar tanto o fluxo de cobrança quanto o fluxo de entrega, podendo gerar frustração no cliente e prejuízo para a empresa
    - Sugestão: adicionar regras de negócios que não permitam a adição de dados inválidos juntamente com mensagens de erro claras sobre o problema, por exemplo, "O campo deve conter apenas letras e números."

- BUG008 - Botão Finish não funciona
    - Impacto: a impossibilidade de concluir a compra faz o cliente procurar a concorrência, causando prejuízo financeiro para a empresa
    - Sugestão: corrigir o botão Finish

---

Análise de qualidade

Durante os testes, foram identificados pontos críticos relacionados à experiência do usuário, principalmente nas informações e imagens fornecidas, bem como no funcionamento de itens de UI.

---

Conclusão

A aplicação apresenta erros críticos em seus principais fluxos.

Recomenda-se ajustes para melhorar a experiência do usuário e evitar prejuízos para a empresa.