ADVPLayC
========
Utilit�rio para compila��o pela linha de comando. Esse pacote n�o possui o 
compilador, o compilador � baixado do projeto do 
[advpl-vscode](https://github.com/killerall/advpl-vscode)


Como instalar
=============

Pelo NPM:

```
$ npm install -g advplc
```

Pelo github:

```
$ git clone https://github.com/danielflira/advplc
$ cd advplc
$ npm install -g
```


Como configurar
===============

� necess�rio configurar as op��es globais com o parametro --cfg e adicionar os 
ambientes com a op��o --add (as duas podem ser utilizadas em conjunto)

```
$ advplc --cfg .
$ advplc --add .

ou

$ advplc --cfg --add .
```

No comando --add caso seja colocar um nome de ambiente j� existente
(respeitando mai�sculas e min�sculas) ser� atualiza as informa��es deste 
ambiente


Como utilizar
=============

Para utilizar dentro do diret�rio que possui o arquivo de configura��o .advplc 
apenas digitar o comando informando o nome do ambiente:

```
$ advplc --env Protheus118 foobar.prw

ou

$ advplc --env Protheus12117 fontes/
```
