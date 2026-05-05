# 🛒 Shopee Cart (Simulação de Carrinho)

## 🚀 Sobre o Projeto
<p>
Este projeto é uma simulação de um carrinho de compras inspirado na Shopee,
desenvolvido com <strong>Node.js</strong> e <strong>JavaScript</strong>.
O objetivo é praticar lógica de programação e organização de código.
</p>

## ⚙️ Funcionalidades
<ul>
  <li>Adicionar itens ao carrinho</li>
  <li>Remover quantidade de um item</li>
  <li>Excluir item do carrinho</li>
  <li>Listar produtos</li>
  <li>Calcular total da compra</li>
</ul>

## 📁 Estrutura
<pre>
src/
 ├── index.js
 └── services/
      ├── cart.js
      └── item.js
</pre>

## 🧠 Conceitos
<ul>
  <li>Modularização</li>
  <li>Async/Await</li>
  <li>Manipulação de Arrays</li>
  <li>Separação de responsabilidades</li>
</ul>

## 📦 Como Executar

<pre>
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
node src/index.js
</pre>

## 🛠️ Exemplo

<pre>
const item1 = await createItem("hotwheels ferrari", 20.99, 1);
const item2 = await createItem("hotwheels lamborghini", 39.99, 3);

await cartService.addItem(myCart, item1);
await cartService.addItem(myCart, item2);
</pre>

## 📊 Saída

<pre>
Shopee cart list:
1. hotwheels ferrari - R$ 20.99 | 1x | Subtotal = 20.99
2. hotwheels lamborghini - R$ 39.99 | 3x | Subtotal = 119.97

Total: 140.96
</pre>

## 🔮 Melhorias Futuras
<ul>
  <li>Interface gráfica</li>
  <li>Banco de dados</li>
  <li>Sistema de login</li>
</ul>

## 👨‍💻 Autor
<p>Daniel Rocha</p>
