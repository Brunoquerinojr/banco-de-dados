# Comando SQL - CRUD (referência)

## Resumo
C -> Create (insere dados)
R -> Read (Ler dados)
U -> Update (Atualizar dados)
D -> Delete (Deletar dados)

## Insert
## Fabricantes 

```sql

INSERT INTO fabricantes (nome) VALUE ('Asus');
INSERT INTO fabricantes (nome) VALUE ('Dell');
INSERT INTO fabricantes (nome) VALUE ('Dell');
INSERT INTO fabricantes (nome) 
VALUE ('Apple'),('LG'),('Samsung'),('Brastamp');

```

```sql

INSERT INTO fabricantes (nome)
VALUE ('Positivo'),('Microsoft');

```


## Insert
## Produtos

```sql

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_(id)) 
VALUES ('Ultrabook',
'Ultrabook Asus Intel Core I9',
6500.99,
7,
1
);


INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Geladeira',
'Frost-free com acesso a internet',
8500.99,
10,
6
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Tablet Android',
'Tablet 10 polegadas com 256gb de armazenamento',
4999,
3,
5
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Iphone 14 Pro Max',
'Processor Bionic 15 com 512gb de armazenamento',
9999.97,
3,
3
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Ipad mini',
'Tablet com tela de retina 4k com 512gb de armazenamento',
5000,
8,
3
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Xbob',
'Console de ultima geração',
2500,
6,
8
);

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) 
VALUES ('Ultrabook',
'AMD Ryzen 5 16Gb RAM...',
4500.97,
12,
7
);



```
