# Programa de Formação em Elixir | Teste Técnico

## Como rodar o projeto

- Criar um ambiente virtual
- Com o ambiente virtual ativo, usar o comando:
```
pip install pandas
```
- Após a instalação, executar o comando: 
```
python desafio.py
```

## Listas de dados

Os dados estão na pasta "listas", nessa pasta contem um arquivo com os e-mails e outro arquivo com os itens da lista de compras.

A inserção de novos itens na lista de compras e na lista de e-mails deve obedecer ao padrão .CSV.

lista_compras.csv
|  nome  |  preco  | quantidade  |
| ------------------- | ------------------- | ------------------- |
|  arroz |  250 |  13 |
|  biscoito |  312  |  5  |

lista_emails.csv
|  email  |  
| ------------------- |
|  jonasra4@gmail.com | 
|  carla@hotmail.com | 

## Considerações

Nesse desafio considerei que a entrada dos valores referentes aos preços dos produtos serão em centavos, logo não fiz a conversão de real para centavo e vice-versa.

Se o sistema indentificar alguma irregularidade na entrada de dados, um erro geral sera imprimido e o calculo será cancelado.

