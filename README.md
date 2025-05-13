# O que entendi da aula "Banco de Dados III - Joins"?

Os autoestudos me ajudaram a ter uma compreensão geral sobre o que são joins em SQL. Pude assistir as vídeo aulas e ter uma noção ideal para aula. Não consegui terminar de ler os artigos, mas planejo fazer isso no final de semana. 

No autoestudo, eu entendi que:
- a separação de dados em um banco de dados relacional não é feita de forma aleatória (e sim planejada);
- o uso de diferentes tabelas é essencial para controlar redundâncias e evitar problemas de consistência;
- normalização (informações não se repetem dentro das tabelas, apenas usa-se o id) ajudam a economizar espaço de armazenamento;
- a estrutura fragmentada do banco de dados facilita a gestão (um "tabelão" usaria a memória de forma desnecessária).

Na aula, eu entendi que:

Inner join (ou somente join): retorna apenas os registros que têm correspondências em ambas as tabelas.
```SQL
SELECT colunas
FROM tabela1
INNER JOIN tabela2 ON tabela1.coluna = tabela2.coluna
```

Left join (ou left outer join): retorna todos os registros da tabela à esquerda (primeira tabela) e os correspondentes da tabela à direita. se não houver correspondência, retorna NULL para as colunas da tabela à direita.
```SQL
SELECT colunas
FROM tabela1
LEFT JOIN tabela2 ON tabela1.coluna = tabela2.coluna
```
Também entendi sobre right join, mas eu precisaria consultar anotações para conseguir escrever o código.
