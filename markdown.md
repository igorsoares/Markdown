# Guia de linguagem Markdown
Explicação sobre os principais usos da linguagem de marcação Markdown.
## Para que serve ?
A linguagem Markdown é uma linguagem para marcação de textos, assim como o HTML. Com ela é possível adicionar facilmente formatações em textos, imagens, links e entre outros...
### Principais usos

Escrever em **negrito**

```
**negrito**
```

Escrever em *italico*

```
*italico*
_italico_
```

### Títulos

Os títulos são criados com # no início, indo de um até seis.

```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

Os itens acima resultam em:

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

### Links
A linkagem de sites é feita através de **link direto** ou **texto-âncora**

Linkagem direta

_<Site_destino>_

```
<https://www.github.com/igorsoares>
```

Com ancoragem

_[Título](Site destino)_

```
[Meu Github](https://www.github.com/igorsoares)
```


### Listas

Tipos de listas:
* Não ordenadas
* Ordenadas

#### Listas não ordernadas 

```
* Lista não ordenada 1
* Lista não ordenada 2
* Lista não ordenada 3
```

Os itens acima serão aparecidos como:
    
* Lista não ordenada 1 
* Lista não ordenada 2
* Lista não ordenada 3

#### Listas ordenadas

```
1. lista ordenada
2. lista ordenada 2
3. lista ordenada 3
```

Os itens acima serão aparecidos como:

1. lista ordenada
2. lista ordenada 2
3. lista ordenada 3

### Imagens
Colocando imagens



` ![titulo](caminho/imagem.png) `

### Citação
Para adicionar uma citação / comentário, utiliza-se ">" na frente do texto.

` > Esse é um comentário `

O item acima aparecerá como:

> Esse é um comentário



### Textos pré formatados

Utilizados para mostrar algum código.

Utiliza-se ` na mesma linha ou ``` para abrir e fechar um bloco.


#### Um bloco

```

    ```
        using System;

        namespace Teste{

            public class Produtos{
                public static void Main(){
                    Console.WriteLine("Hello World!");
                }
            }


        }
    ```

```

#### Uma linha

```
    `Na mesma linha`
```

Será aparecido como: 

` Na mesma linha `

### Tabela

#### Como fazer
1. Construa as colunas. Com "coluna1 | coluna2"
    
    1.1 Feche as colunas com  "---|---|", onde é três traços e um PIPE para cada coluna na tabela

2. Para colocar as linhas, faz-se "linha1|linha2"

ID | Nome | Nota
---|---|---|
105|Igor|9.5
107|Maria|8.7
102|Carlos|5.5

```
ID | Nome | Nota
---|---|---|
105|Igor|9.5
107|Maria|8.7
102|Carlos|5.5
```

