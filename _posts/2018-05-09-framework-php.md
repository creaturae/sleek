---
layout: post
title: Fazer ou não fazer um framework PHP em 2018?
featured-img: sleek
mathjax: true
---

# Fazer ou não fazer um framework PHP em 2018?
No início de todo projeto, existe sempre a mesma pergunta crucial que pode definir não o seu sucesso ou ou o seu fracasso, mas sim a quantidade de horas extras e de esforço desnecessário despendido até a entrega. Geralmente um sistema web vem definido como: "Tudo bem, iremos fazer o projeto X, será em PHP com banco de dados MySQL. Mas qual framework iremos utilizar?"

Longe de ser uma resposta fácil, é uma resposta simples para quem não quer pensar no problema, seja pela falta de tempo hábil, ou por já ter se acostumado em ouvir sempre a mesma resposta, ou por não querer mesmo se envolver nessas questões, ou mesmo por entender que o melhor é fazer o que todo mundo já está fazendo. Vai muito da empresa, do seu tamanho, de seu expertise em tecnologia, de sua maturidade de desenvolvimento, e muitos outros fatores.

## Frameworks de PHP em 2018
Hoje, em 2018, não vivemos mais uma guerra de frameworks como vivíamos no passado. As coisas se consolidaram. Laravel se tornou o padrão. É o rei dos frameworks e ponto. Ninguém em sã consciência se atreve a questionar isso. Ninguém a não ser o próprio criador do PHP, Rasmus Lerdorf. Para ele, todos os frameworks são uma perda de tempo e esforço.

Voltando ao rei dos frameworks, seus concorrentes, deixados para trás por longa margem, são todos projetos de peso e até com maior credibiliade que ele. Projetos já testados e utilizados há anos, como Symfony que á a base de outros projetos importantes como Drupal e muitos outros e o Zend, feito pelos próprios criadores do PHP que á a base do Magento. Isso sem contar com dois dos quais nenhum programador que use abre mão como CakePHP e CodeIgniter, além do Yii.

É preciso entender que essa hegemonia não é uma verdade absoluta.

## PHP precisa de um framework?
Hoje, em pleno 2018, segundo nosso bom e velho amigo Rasmus Lerdorf, não!

Um concorrente do PHP, o NodeJS se sai muito bem tendo uma boa quantidade de bibliotecas que executam somente um trabalho e possui um e somente um framework de requisição HTTP, o Express. Todos os outros são feitos em cima dele, coisa que nem de longe acontece com o PHP.

## O que fazer?
Criar uma solução utilizando pequenas e boas bibliotecas e um micro framework como o FatFree, ou o Slim me parece uma solução muito mais viável para um projeto.
E cada parte do projeto que for necessária deve ser desenvolvida, pois para cada caso existe uma solução específica. 
Um micro framework não possui partes que ficarão obsoletas posi ele resolve muito poouca coisa, somente as partes fundamentais, como resolver as rotas e fazer a injeção de dependência corrretamente

## O projeto de software
Mas o que deve conter um projeto? Quais partes são necessárias?

O framework é um conjunto de bibliotecas porém agrupadas de uma forma que são totalmente dependentes umas das outras. Não se pega o modelo de um e coloca o cache de outro. Mas cnão no caso do Symfony. Ele foi feito desde sua comcepção para ser dessa forma, um cojunto de bibliotecas interoperáveis e desacopladas.

E porque não usar somente o Symfony? Bom, depende do gosto de cada um, mas o conjunto todo é doferenet da soma de suas partes. A comunidade tem preferido utilizar suas bibliotecas , mas não ele como um todo. 

Além dele, existem boas bibliotecas no github disponíveis e também amplamente utilizadas.

Os componentes essenciais  são:
    Abstração HTTP - síncrono e assíncrono
    Rotas
    Modelo
    Validação
    Template
    Banco de Dados
    Controle de Acesso
    Logs
    Tradução

Adicionalmente mas também não menos importante:    
    Especificação
    Testes Unitários

#Links
https://symfony.com/components
http://br.phptherightway.com/
http://www.phpthewrongway.com/
