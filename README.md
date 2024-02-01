# :computer: Guia de tipos de dados :coffee: Java

Guia conciso sobre tipos de dados numéricos em Java, cobrindo byte, short, int e long, incluindo tamanhos e valores máximos.

## :1234: int
Geralmente tem um tamanho de 4 bytes em sistemas de 32 bits e 8 bytes em sistemas de 64 bits. Exemplo: 5, -10, 1000

## :1234: double
Um tipo de dado de ponto flutuante que pode representar números com parte decimal. Geralmente, é de 8 bytes de tamanho. Exemplo: 3.14, -0.001, 100.5

## :1234: float
Outro tipo de dado com ponto flutuante, mas com menos precisão do que o double. Normalmente ocupa 4 bytes de espaço na memória. É importante observar que em algumas linguagens, como Java, os literais de ponto flutuante são do tipo double por padrão, então é necessário adicionar o sufixo "f" para indicar que é do tipo float. Exemplo: 3.14f, -0.001f, 100.5f

## :1234: short
Similar ao tipo int, mas com a capacidade de armazenamento menor. Geralmente, tem 2 bytes de tamanho. É usado quando o espaço de armazenamento é uma preocupação e os valores a serem armazenados são pequenos. Exemplo: 10, -5, 100

## :1234: byte
É o menor tipo de dado numérico em muitas linguagens de programação. Ele armazena valores inteiros na faixa de -128 a 127 em 1 byte de espaço de memória. É comumente usado em situações onde o espaço é crítico, como em matrizes grandes ou comunicação de rede. Exemplo: 5, -100, 127.

## Tamanhos de Bytes e Bits

| Quantidade de Bits | Quantidade de Bytes | Abreviação  |
|--------------------|---------------------|-------------|
|         8          |          1          |     1B      |
|         16         |          2          |     2B      |
|         32         |          4          |     4B      |
|         64         |          8          |     8B      |
|        128         |         16          |     16B     |

## Valores Máximos Absolutos

|    Tipo de Dado   |          Tamanho (em bytes)         |       Valor Máximo (absoluto)          |
|-------------------|-------------------------------------|----------------------------------------|
|       byte        |                 1                   |                  255                   |
|       short       |                 2                   |               32,767                   |
|        int        |                 4                   |           2,147,483,647                |
|       float       |                 4                   |           3.4028235E38                 |
|      double       |                 8                   |    1.7976931348623157E308              |
|        long       |                 8                   |  9,223,372,036,854,775,807 (9x10^18)   |

