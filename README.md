# projeto-bd-colab
🗃️ Projeto Banco de Dados com SQLite + Google Colab
Este projeto consiste em uma simulação de um pequeno banco de dados usando SQLite dentro do ambiente Google Colab. Ele envolve a criação de tabelas, inserção de dados e realização de consultas com JOIN, usando Python.

🔗 [Clique aqui para abrir o notebook no Google Colab](https://colab.research.google.com/github/LeonardoRobert/projeto-bd-colab/blob/main/Projeto_BD_SQLite.ipynb)

🔧 Estrutura do Banco de Dados
O banco é composto por três tabelas principais:

🧍 Tabela pessoas
Coluna	Tipo	Descrição
id	INTEGER (PK)	Identificador da pessoa
nome	TEXT	Nome da pessoa
idade	INTEGER	Idade da pessoa

📦 Tabela produtos
Coluna	Tipo	Descrição
id	INTEGER (PK)	Identificador do produto
descricao	TEXT	Nome/descritivo do produto
estoque	INTEGER	Quantidade disponível
preco	REAL	Preço do produto

🛒 Tabela vendas
Coluna	Tipo	Descrição
id_venda	INTEGER (PK)	Identificador da venda
id_pessoa	INTEGER (FK)	Referência para a tabela pessoas
id_produto	INTEGER (FK)	Referência para a tabela produtos
quantidade	INTEGER	Quantidade vendida

🔍 Consultas Realizadas
O notebook executa um JOIN entre as tabelas para listar as vendas realizadas com nome da pessoa, produto e quantidade. Exemplo de resultado:

bash
Copiar
Editar
(1, 'Maria', 'Caneta', 10)
(2, 'João', 'Caderno', 2)
▶️ Como Executar
Clique no botão abaixo para abrir no Google Colab:


Execute as células na ordem (Shift + Enter)

Veja os resultados dos comandos SQL diretamente no notebook

📌 Observações
O banco está em memória (:memory:), ou seja, será perdido ao fechar o notebook.

Para manter os dados, altere a linha de conexão para:

python
Copiar
Editar
conn = sqlite3.connect('projeto.db')
