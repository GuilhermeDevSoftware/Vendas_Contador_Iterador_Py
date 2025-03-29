# 📊 Analisador de Vendas

Este projeto é um pequeno sistema em Python que simula a leitura e análise de um arquivo de vendas. Ele processa um arquivo `.txt` contendo registros com a **categoria** do produto e o **valor da venda**, exibindo o total acumulado das vendas e a contagem por categoria.

É uma ótima aplicação para estudar conceitos como **iteradores personalizados**, **geradores** e **manipulação de arquivos em Python**.

## 💡 Como funciona

O programa utiliza uma classe iteradora (`VendasInterator`) que lê o arquivo linha por linha, retornando os dados no formato `(categoria, valor)`. Com isso, um gerador (`gerador_soma`) vai somando os valores das vendas e exibindo o total progressivo.

No final da execução, ele ainda mostra quantas vendas foram feitas em cada categoria.

## 📁 Exemplo de arquivo de entrada (`vendas.txt`)

eletronicos,400
roupas,200
alimentos,150
eletronicos,170
alimentos,300
roupas,100 

## Exemplo de saída

Processando vendas...
Categoria: eletronicos - Preço R$400.00 - Total R$400.00
Categoria: roupas - Preço R$200.00 - Total R$600.00
Categoria: alimentos - Preço R$150.00 - Total R$750.00
Categoria: eletronicos - Preço R$170.00 - Total R$920.00
Categoria: alimentos - Preço R$300.00 - Total R$1220.00
Categoria: roupas - Preço R$100.00 - Total R$1320.00
eletronicos : 2 vendas
roupas : 2 vendas
alimentos : 2 vendas

## 🎓 Objetivo

Este projeto tem como principal finalidade **educacional**, sendo ideal para estudantes que estão aprendendo sobre:

- Leitura e escrita de arquivos
- Iteradores e geradores em Python
- Lógica de programação e estruturas de controle

Ele demonstra como processar dados de forma eficiente utilizando recursos nativos da linguagem Python, mantendo o código simples e didático.

Você pode usá-lo como base para projetos maiores, como sistemas de relatórios, análise de vendas mais avançada, ou até integração com arquivos CSV e bancos de dados.

Sinta-se à vontade para adaptar ou expandir o projeto com mais funcionalidades!


