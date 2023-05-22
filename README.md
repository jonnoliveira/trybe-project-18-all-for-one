# PROJETO 18 - ALL FOR ONE :computer:

## Esse projeto pertence ao módulo de `back-end` da [Trybe](https://www.betrybe.com/) :green_heart:

### Stacks utilizadas no desenvolvimento:
<div style="display: inline_block"><br>
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Shield" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Shield" />
</div>
 
 #
<details>
 
<summary>
  
## 1- Resumo
  
</summary>

Nesse projeto trabalhei com a aplicação dos conceitos de SQL onde pude exibir dados específicos de tabelas, filtrando os elementos com precisão e manipulando a informação de diversas formas possíveis, como:

* Filtragem condicional;
* Adicionando novas colunas e valores em determinadas tabelas;
* Atualizando dados de uma coluna existente utilizando condicionais;
* Deletando dados e tabelas específicas; Veja mais abaixo!
  
</details>

#

<details>
 
<summary>
 
## 2- Requisitos

</summary>

* I. Exiba apenas os nomes dos produtos na tabela products.
* II. Exiba os dados de todas as colunas da tabela products.
* III. Escreva uma query que exiba os valores da coluna que representa a primary key da tabela products.
* IV. Conte quantos registros existem na coluna product_name da tabela products.
* V. Monte uma query que exiba os dados da tabela products a partir do quarto registro até o décimo terceiro.
* VI. Exiba os dados das colunas product_name e id da tabela products de maneira que os resultados estejam em ordem alfabética dos nomes.
* VII. Mostre apenas os ids dos 5 últimos registros da tabela products (a ordenação deve ser baseada na coluna id).
* VIII. Faça uma consulta na tabela employees que retorne o nome completo da pessoa colaboradora (colunas first_name e last_name) com o nome full_name e também a localização completa (colunas city, state_province e address) com o nome location.
* IX. Mostre todos os valores de notes da tabela purchase_orders que não são nulos.
* X. Mostre todos os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by em que o created_by é maior ou igual a 3.
* XI. Exiba os dados da coluna notes da tabela purchase_orders em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39.
* XII. Mostre as submitted_date de purchase_orders em que a submitted_date é do dia 26 de abril de 2006.
* XIII. Mostre o supplier_id das purchase_orders em que o supplier_id seja 1 ou 3.
* XIV. Mostre os resultados da coluna supplier_id da tabela purchase_orders em que o supplier_id seja maior ou igual a 1 e menor ou igual 3.
* XV. Mostre somente as horas (sem os minutos e os segundos) da coluna submitted_date de todos registros da tabela purchase_orders.
* XVI. Exiba a submitted_date das purchase_orders que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
* XVII. Mostre os registros das colunas id e supplier_id das purchase_orders em que os supplier_id sejam tanto 1, ou 3, ou 5, ou 7.
* XVIII. Mostre todos os registros de purchase_orders que tem o supplier_id igual a 3 e status_id igual a 2.
* XIX. Mostre a quantidade de pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6, e que foram enviados através do método(coluna) shipper_id igual a 2.
* XX. Adicione à tabela order_details um registro com order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129.
* XXI. Adicione com um único INSERT, duas linhas à tabela order_details com os mesmos dados do requisito 20. 
* XXII. Atualize todos os dados da coluna discount, na tabela order_details, para 15.
* XXIII. Atualize os dados da coluna discount da tabela order_details para 30, onde o valor na coluna unit_price seja menor que 10.0000.
* XXIV. Atualize os dados da coluna discount da tabela order_details para 45, onde o valor na coluna unit_price seja maior que 10.0000 e o id seja um número entre 30 e 40.
* XXV. Delete todos os dados em que a unit_price da tabela order_details seja menor que 10.0000.
* XXVI. Delete todos os dados em que a unit_price da tabela order_details seja maior que 10.0000.
* XXVII. Delete todos os dados da tabela order_details.

</details>

# 

<details>
 
<summary>

## 3- Nota do Projeto
 
</summary>

## 100% :heavy_check_mark:

![Project-all-for-one](https://github.com/jonnoliveira/trybe-project-18-all-for-one/blob/main/images/all-for-one-grade.png)

</details> 
 
# 
