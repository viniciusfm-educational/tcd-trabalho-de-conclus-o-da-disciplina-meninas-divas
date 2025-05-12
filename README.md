#tcd-trabalho-de-conclus-o-da-disciplina-meninas-divas
------------------------------------------------------
NOME DO PROJETO: Outfit.exe

NOME DO TIME DE DESENVOLVIMENTO: meninas divas

NOME DE CADA INTEGRANTE E SEU USUÁRIO NO GITHUB: 
------------------------------------------------------
|             NOME                |     USUÁRIO        |
------------------------------------------------------
| Ana Clara Albino Carvalho       |    anacaqui        |
------------------------------------------------------
| Camila Lima Rossi               |    Camilalimarossi |
------------------------------------------------------
| Emylle Yasmin Côrrea Santos     |    Eily-YCS        |
------------------------------------------------------
| Maria Luiza Rodrigues Oliveira  |    mluizasz        |  
------------------------------------------------------

DESCRIÇÃO DO SOFTWARE
    O software será um aplicativo voltado para a gestão de um brechó online, com foco em usabilidade, estética e funcionalidade. O sistema vai permitir o cadastro, gerenciamento e exibição de produtos de segunda mão, organizados por categorias como roupas, calçados e acessórios, além de filtros por estilo (Y2K, retrô, street, minimalista etc). O objetivo principal é facilitar a administração do acervo e melhorar a experiência de compra dos clientes por meio de uma interface visualmente atraente e intuitiva.

    A plataforma contará com um painel administrativo onde o proprietário do brechó poderá cadastrar produtos com fotos, descrições, preços e disponibilidade. Também incluirá funções como atualização de estoque, controle de pedidos e geração de relatórios simples de vendas. Do lado do cliente, haverá um catálogo interativo com busca, filtros e carrinho de compras. O sistema poderá ser integrado a meios de pagamento online, como Pix e cartão de crédito.

    Além disso, o design será pensado para atrair um público jovem e conectado às tendências de moda sustentável, com elementos visuais inspirados em estéticas como Y2K, pastel e cybercore. O software será desenvolvido utilizando tecnologias modernas de front-end e back-end, prezando pela responsividade e segurança dos dados.

TODO LIST

IMAGENS

# NOME DO PROJETO
*O nome do projeto é ***Outfit.exe***.*
<hr>

# NOME DO TIME DE DESENVOLVIMENTO
*O nome do time que vai desenvolver o projeto é ***Meninas divas***.*
<hr>

# NOME DE CADA INTEGRANTE

| Nomes                          |          Usuário               |
|--------------------------------|--------------------------------|
| Ana Clara Albino Carvalho      | anacaqui                       |
| Camila Lima Rossi              | Camilalimarossi                |
| Emylle Yasmin Côrrea Santos    | Eily-YCS                       |
| Maria Luiza Rodrigues Oliveira | mluizasz                       |


## Descrição do Software

    O software será um aplicativo voltado para a gestão de um brechó online, com foco em usabilidade, estética e funcionalidade. O sistema vai permitir o cadastro, gerenciamento e exibição de produtos de segunda mão, organizados por categorias como roupas, calçados e acessórios, além de filtros por estilo (Y2K, retrô, street, minimalista etc). O objetivo principal é facilitar a administração do acervo e melhorar a experiência de compra dos clientes por meio de uma interface visualmente atraente e intuitiva.

    A plataforma contará com um painel administrativo onde o proprietário do brechó poderá cadastrar produtos com fotos, descrições, preços e disponibilidade. Também incluirá funções como atualização de estoque, controle de pedidos e geração de relatórios simples de vendas. Do lado do cliente, haverá um catálogo interativo com busca, filtros e carrinho de compras. O sistema poderá ser integrado a meios de pagamento online, como Pix e cartão de crédito.

    Além disso, o design será pensado para atrair um público jovem e conectado às tendências de moda sustentável, com elementos visuais inspirados em estéticas como Y2K, pastel e cybercore. O software será desenvolvido utilizando tecnologias modernas de front-end e back-end, prezando pela responsividade e segurança dos dados.

**OBS**: Verifique a seção [Compilação de Programas *Kotlin*](#compilação-de-programas-kotlin) para relembrar como compilar um código **main.kt** usando o comando **build.sh**.

<hr>
<p style="font-size: 2em">Boa sorte!!! 😄</p>
<hr>

## Compilação de programas *Kotlin*

1) Verifique se o arquivo `build.sh` possui permissão de executável usando o comando `ls -la`
    * Caso o arquivo esteja como executável, irá aparecer a letra `x` no campo de permissões

```bash
...
-rwxr-xr-x. 1 vinicius vinicius  181 Feb 28 13:06 build.sh
...
```

* Caso o arquivo não esteja como executável, dê a ele esta permissão:
```bash
chmod +x build.sh
```

2) Execute o *script*. Ele está programado para compilar e executar o programa.

```bash
./build.sh
# caso não der permissão de execução para o build.sh execute
bash build.sh
```
> OBS: Durante a compilação, uma pasta `build` irá surgir e um arquivo `*.jar` será criado nela. O arquivo `*.jar` é resultante da compilação do código-fonte.

3) Você pode executar o programa de forma idependente do *script* `build.sh`. Basta você executar o comando abaixo:

```bash
java -jar ./build/main.jar
```
