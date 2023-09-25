# atividade-III-banco-paises
## Questão 1
Selecione todos os dados dos países da *tabela_paises*<p>
SQL
select * from tabela_paises

### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/e3a8b86a-03c3-4ec1-b114-8d6a8eb1addc)

## Questão 2
Selecione todas as cidades cujo país seja *Brazil*
SQL
select cidade from tabela_paises where pais = 'Brazil';

### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/65b1531f-50c2-4c42-adf8-7d4d89208fe0)

## Questão 3
Selecione todas as cidades cuja região(estado) é *Ceará*
SQL
select cidade from tabela_paises where regiao = 'Ceará';

### Resultado esperado
![image](https://github.com/DavidSSF/atividade-III-banco-paises/assets/117132755/e0ade35a-9508-405b-8382-e5a9c16fb63e)
