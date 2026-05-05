🛒 Shopee Cart (Simulação de Carrinho)

Este projeto é uma simulação simples de um carrinho de compras inspirado na Shopee, desenvolvido com JavaScript utilizando Node.js. O objetivo é praticar conceitos como modularização, manipulação de arrays e lógica de negócios.

🚀 Funcionalidades
✅ Adicionar itens ao carrinho
➖ Remover quantidade de um item
❌ Deletar item completamente
📋 Listar itens do carrinho
💰 Calcular o valor total da compra
📁 Estrutura do Projeto
src/
 ├── index.js              # Arquivo principal
 └── services/
      ├── cart.js          # Regras do carrinho
      └── item.js          # Criação dos itens
🧠 Conceitos Aplicados
Modularização com ES Modules
Funções assíncronas (async/await)
Manipulação de arrays (push, splice, reduce)
Organização por responsabilidade (services)
📦 Como Rodar o Projeto
Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
Acesse a pasta:
cd seu-repositorio
Execute o projeto:
node src/index.js
🛠️ Exemplo de Uso

O sistema cria itens automaticamente e executa algumas ações:

const item1 = await createItem("hotwheels ferrari", 20.99, 1);
const item2 = await createItem("hotwheels lamborghini", 39.99, 3);

await cartService.addItem(myCart, item1);
await cartService.addItem(myCart, item2);
🧾 Saída Esperada
Shopee cart list:
1. hotwheels ferrari - R$ 20.99 | 1x | Subtotal = 20.99
2. hotwheels lamborghini - R$ 39.99 | 3x | Subtotal = 119.97

Shopee Cart TOTAL IS:
🎁Total: 140.96
📌 Melhorias Futuras
Interface gráfica (HTML/CSS)
Persistência de dados (Banco de Dados)
Sistema de usuários
Integração com API
