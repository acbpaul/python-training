# Guia básico de Markdown

Markdown Syntax é uma sintaxe usada para padronizar e facilitar formatação de texto na web, utilizada em aplicativos como Slack e GitHub. Textos estilizados com Markdown são, na maioria dos casos, apenas texto com caracteres não-alfabéticos,  usados para a configuração de títulos, listas, itálico, negrito e inserção de imagens.

## Lista de comandos em Markdown

### Titulação

<div>
# Título
## Título
### Título
#### Título
##### Título
###### Título
</div>

# Título
## Título
### Título
#### Título
##### Título
###### Título

### Ênfase

<div>
Negrito - **texto** ou __texto__
Itálico - *texto* ou _texto_
</div>

Negrito - **texto** ou __texto__
Itálico - *texto* ou _texto_

### Links

<div>
Podem ser usados no formato link direto ou texto-link.

Para link direto, usa-se <link>

Para texto-link, usa-se o formato [texto](link)
</div>

Este é um [link no formato texto-link](www.google.com) e este é um link direto <www.google.com>

### Listas

Para listas não ordenadas, utilize um asterisco na frente do item da lista:

<div>
* Item 1
* Item 2
* Item 3
</div>

* Item 1
* Item 2
* Item 3

Para listas ordenadas, utilize o número do item seguido de ponto:

<div>
1. Item 1
2. Item 2
3. Item 3
</div>

1. Item 1
2. Item 2
3. Item 3

### Imagens

Semelhante ao formato texto-link, mas com um ponto de exclamação no início:

<div>
![Título da imagem](URL da imagem)
</div>

### Citação (Quote)

Para transformar um texto em uma citação ou comentário, utilize o sinal > no início da linha que será formatada:

<div>
>Este é um *blockquote*.
>Para adicionar novas linhas, aperte Enter
>e adicione novamente o símbolo.
</div>

>Este é um *blockquote*.
>Para adicionar novas linhas, aperte Enter
>e adicione novamente o símbolo.

### Código (Code Highlight)

Há dois modos de adicionar trechos de código em *Markdown*:

* **Código em linha única** *(inline)*: adicione um acento grave ` no início e no final do código.

* **Código em múltiplas linhas**: adicione três acentos graves ou três tils no início e no final do bloco de código.

<div>
`import pandas as pd`

```
import pandas as pd
import numpy as np
```
</div>

`import pandas as pd`

~~~
import pandas as pd
import numpy as np
~~~

Para especificar a lingugagem utilizada, adicione o nome da linguagem de programação após o triplo acento ou triplo til de um bloco:

<div>
~~~python
Esta é uma linha de código em Python.
~~~

~~~java
Esta é uma linha de código em Java.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~
</div>

~~~python
Esta é uma linha de código em Python.
~~~

~~~java
Esta é uma linha de código em Java.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~

### Tabela

Delimite as colunas utilizando `|` e utilize hífen `-` na segunda linha para separar o título das colunas de seu conteúdo, utilizando novamente `|` entre as colunas:

<div>
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
</div>

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize `:` ao lado do campo horizontal de hífens `---`, na segunda linha da sua tabela. Veja abaixo:

**Alinhado a esquerda**: usar `:` no lado esquerdo (alinhamento padrão);
**Alinhado a direita**: usar `:` no lado direito;
**Centralizado**: usar `:` dos dois lados.

<div>
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
</div>

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor


Para mais detalhes de referência, [clique aqui](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown)