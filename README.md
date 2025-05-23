# Projeto Banco de Dados com SQLite no Google Colab

Este projeto demonstra a criação e manipulação de um banco de dados simples usando **SQLite** no ambiente **Google Colab**, com foco educacional e prático para estudantes de banco de dados.

---

## 🧠 O que o projeto faz?

O notebook realiza as seguintes ações:

- Cria um banco de dados com três tabelas principais: `pessoas`, `produtos` e `vendas`;
- Insere dados de exemplo nessas tabelas;
- Realiza consultas com **JOIN** para exibir vendas realizadas, associando cliente e produto;
- Apresenta **relatórios simples** com totais e médias;
- Gera **gráficos interativos** com `matplotlib` e `pandas`.

Veja o diagrama do banco de dados:  
📄 [Diagrama ER](docs/diagrama.png)

---

## 📂 Como abrir o notebook

Clique no link abaixo para abrir diretamente no Google Colab:

🔗 [Abrir Projeto no Google Colab](https://colab.research.google.com/github/LeonardoRobert/projeto-bd-colab/blob/main/Projeto_BD_SQLite.ipynb)

---

## ▶️ Como reproduzir o projeto

1. Acesse o notebook pelo link acima;
2. No Colab, clique em **"Executar tudo"** ou use `Ctrl + F9` para executar todas as células;
3. Você verá:
   - A criação do banco;
   - Dados inseridos;
   - Consultas SQL com resultado impresso;
   - Relatórios em formato de tabela;
   - Gráfico de barras com total de vendas por produto.

Não é necessário instalar nada em seu computador. Tudo funciona diretamente no navegador, graças ao ambiente online do Google Colab.

---

## 💡 Exemplo de resultado de consulta

```text
ID | Cliente | Produto | Quantidade
1  | Maria   | Caneta  | 10
2  | João    | Caderno | 2
