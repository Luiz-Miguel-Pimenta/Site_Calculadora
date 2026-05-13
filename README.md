# 🧮 Calculadora

Uma calculadora funcional desenvolvida com HTML, CSS e JavaScript puro, criada durante o aprendizado de JavaScript.

## 📋 Sobre o Projeto

A **Calculadora** é uma aplicação web que simula uma calculadora de bolso no navegador. Desenvolvida como projeto de estudo de JavaScript, ela suporta as quatro operações matemáticas básicas, entrada de números decimais, limpeza do display e remoção do último caractere digitado.

## ✨ Funcionalidades

- ➕ Adição
- ➖ Subtração
- ✖️ Multiplicação
- ➗ Divisão
- 🔢 Entrada de números decimais (vírgula)
- 🧹 Limpar display (`C`)
- ⬅️ Apagar último caractere (`<`)
- 🟰 Calcular resultado (`=`)

## 🎹 Layout dos Botões

```
[ C ]  [ < ]  [ / ]  [ X ]
[ 7 ]  [ 8 ]  [ 9 ]  [ - ]
[ 4 ]  [ 5 ]  [ 6 ]  [ + ]
[ 1 ]  [ 2 ]  [ 3 ]  [   ]
[   0   ]  [ , ]  [ = ]
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura e layout da calculadora com `<table>`
- **CSS3** — Estilização dos botões e interface (`estilo.css`)
- **JavaScript** — Lógica de operações e manipulação do display (`Aprendendo_ JS.js`)

## 📁 Estrutura do Projeto

```
Site_Calculadora/
├── index.html          # Estrutura da calculadora
├── estilo.css          # Estilos e layout
└── Aprendendo_ JS.js   # Funções JavaScript da calculadora
```

## ⚙️ Funções JavaScript

| Função | Descrição |
|--------|-----------|
| `insert(valor)` | Adiciona um número ou operador ao display |
| `calcular()` | Calcula e exibe o resultado da expressão |
| `clean()` | Limpa todo o conteúdo do display |
| `back()` | Remove o último caractere digitado |

## 🚀 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Luiz-Miguel-Pimenta/Site_Calculadora.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd Site_Calculadora
   ```

3. Abra o arquivo `index.html` no seu navegador — não é necessário nenhum servidor ou instalação adicional.

## 🖥️ Como Utilizar a Interface

1. Clique nos **números** para formar a expressão
2. Clique em um **operador** (`+`, `-`, `X`, `/`) para definir a operação
3. Clique em **`=`** para calcular o resultado
4. Use **`C`** para limpar tudo ou **`<`** para apagar o último caractere
5. Use **`,`** para inserir números decimais

## 👤 Autor

**Luiz Miguel Pimenta**

- GitHub: [@Luiz-Miguel-Pimenta](https://github.com/Luiz-Miguel-Pimenta)
