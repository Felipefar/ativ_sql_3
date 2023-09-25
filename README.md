# atividade-III-banco-paises
## Questão 1
Selecione todos os dados dos países da **tabela_paises**<p>
```SQL
select * from tabela_paises
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/e3a8b86a-03c3-4ec1-b114-8d6a8eb1addc)

## Questão 2
Selecione todas as cidades cujo país seja **Brazil**
```SQL
select cidade from tabela_paises where pais = 'Brazil';
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/65b1531f-50c2-4c42-adf8-7d4d89208fe0)

## Questão 3
Selecione todas as cidades cuja região(estado) é **Ceará**
```SQL
select cidade from tabela_paises where regiao = 'Ceará';
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/e0ade35a-9508-405b-8382-e5a9c16fb63e)


## Questão 4
Utilize a função **count** para saber QUANTAS regiões(estados) existem na China, utilize também o **group by**
```SQL
select pais, count(distinct regiao) as numero_de_regioes
from tabela_paises where pais='China' group by pais
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/c6cb813d-a375-4d4c-908c-13ee56f7b070)

## Questão 5
QUAIS regiões, diferentes, existem no Canadá?
```SQL
select distinct regiao from tabela_paises where pais='Canada'
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/dac4519b-1451-4a41-b67a-d2e0e3a88c6c)

## Questão 6
QUANTOS países diferentes existem na tabela 'tabela_paises';
```SQL
select count(distinct pais) from tabela_paises
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/f392e4ea-222e-44db-b3f6-56e7e552dcd8)

## Questão 7
Quantas cidades diferentes existem no **brazil**;
```SQL
select count(distinct cidade) from tabela_paises where pais='Brazil'
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/65ac9867-80b4-4f27-ac33-3f75e560c545)

## Questão 8
Selecione os países e quantas regiões cada país possui;
```SQL
select distinct pais,count(distinct regiao) as numero_de_regioes from tabela_paises group by pais
```
### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/932e05f8-4ea3-4f17-a248-8f9eff391c72)

## Questão 9
Quantas pessoas com nome começando em 'João' existem no banco?
```SQL

```
### Resultado esperado
## Questão 10
Quantas pessoas têm o nome John?
```SQL

```
### Resultado esperado

## Questão 11
Ordene os nomes dos países sem repetição em ordem alfabética;
```SQL

```
### Resultado esperado
