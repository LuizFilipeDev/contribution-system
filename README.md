# Sistema de Contribuição

Aplicação para gerenciar as contribuições incluindo o cadastro dos contribuintes e também um sistema de relatório e sorteio entre os contribuintes.

## Interface

Tela inicial com os contribuintes cadastrados e as configurações

![01](https://user-images.githubusercontent.com/74942532/139558201-e437fd1c-2656-4ded-bc53-b3604d640f41.png)

![001](https://user-images.githubusercontent.com/74942532/139558246-b325b465-bff3-4916-a17f-b78cf29259b5.png)

Tela de cadastro dos contribuintes

![02](https://user-images.githubusercontent.com/74942532/139558254-24cd7afc-0729-4ab7-95d6-9163e02b07de.png)

Tela com as contribuições

![03](https://user-images.githubusercontent.com/74942532/139558267-eaef2307-87f3-4c3f-afbf-c7d12dea3022.png)

Tela de relatório

![04](https://user-images.githubusercontent.com/74942532/139558270-c8955500-2cb1-42ed-a9de-cccbb4146ea8.png)

Tela de sorteio

![05](https://user-images.githubusercontent.com/74942532/139558276-4690273f-94cf-48ca-91ce-4b28258e728c.png)

Tela com os sorteios efetuados

![06](https://user-images.githubusercontent.com/74942532/139558286-719ca644-c486-484b-9253-b1e85905246e.png)

## Quais são as funções?

Sistema completo de contribuição podendo adicionar contribuintes, gerenciar contribuintes e as contribuiçoes com um relatório completo e um sistema de sorteio entre os constribuintes. 

## Antes de rodar o projeto

`1` Para rodar o projeto, utilizamos o Wamp(https://www.wampserver.com/en/) como nosso servidor local. O wamp por padrão pode gerar portas diferentes das
configuradas no projeto, por isso vá ao arquivo no diretório `\sistema-de-contribuicao-php\conexao\conexao_bd.php` e configure a variável `$servidor` com localhost e porta
específica que o Wamp gerou na sua máquina.

`2` Importe o banco de dados localizado no diretório `\sistema-de-contribuicao-php\banco_de_dados\sdd.sql` para o MySql

Logo após as etapas, rode o projeto acessando o localhost do Wamp e aproveite.

## Sobre

Aplicação desenvolvida utilizando as seguintes tecnologias: Wamp (Servidor Local), MySql (Banco de dados), PHP, HTML, CSS, JavaScript e Bootstrap.
