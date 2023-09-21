### Criar banco de dados

```sql

CREATE DATABASE fnd CHARACTER SET utf8mb4;

```
<!-- ______________________________________________________´__ -->
### Criar tabela fabricantes

```sql

CREATE TABLE filmes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR(45) NOT NULL,
    lancamento YEAR(4) NOT NULL,
    
)

-- ### Adicionar campo/coluna em uma tabela



ALTER TABLE filmes ADD genero_id INT NOT NULL
AFTER lancamento;

/*_________________________*/
ALTER TABLE filmes
# CONSTRAINT é uma restrição definida no relacionamento
ADD CONSTRAINT fk_filmes_generos
# A chave estrangeira deve fazer referência a chave primária
FOREIGN KEY(genero_id) REFERENCES generos(id)
-- _________________________
### Criar tabela produtos

sql

CREATE TABLE genero(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL,
)
