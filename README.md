![Introdução a paradigmas](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/4b809e9f-cba5-45f2-8edd-f92400518e5f)

  Na disciplina de paradigmas de programação trabalhamos com diferentes abordagens e estilos na resolução de problemas computacionais. Na faculdade iniciamos o estudo de algoritmos com C, consolidando uma base sólida, partimos para uma abordagem multiparadigma.

![domínios de aplicação](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/a1422a37-ea6b-4863-a58a-160a7e8541e8)

  Mas para que compreender os multiparadigmas? Porque o futuro é multiparadigma. É necessário se desvencilhar de uma única linguagem de programação, de uma única abordagem para a resolução de problemas e começar a se desvencilhar disso para se tornar mais versátil e capaz de escolher maneiras mais eficazes para a solução das adversidades do dia a dia.
  
# Repositório 
  A priori, criei este repositório para sintetizar o conteúdo de Programação Funcional disponibilizado pela docente da disciplina de Paradigmas de Programação em um formato de slides com templates interativos e que facilitassem o estudo para a avaliação da disciplina. Ao iniciar os estudos de Haskell, aprendi sobre funções pré-definidas e a melhor desenvolver funções com seus respectivos nomes, valores e tipos. Na aba "Issues" se encontra as imagens utilizadas e também um resumo digital que fiz a mão.

# O que é programação funcional?
  A programação funcional é um paradigma de programação na qual vincula funções matemáticas puras.

![O que é](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/a3263c1a-368b-45cd-858f-38357a50cac5)

## Paradigmas
  Dentre os paradigmas de programação podemos citar: Procedural/Procedimental, funcional, lógico, orientado a objetos, concorrente, orientado a aspectos, orientado a eventos e visual.

![paradigmas](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/49998f98-3478-45a8-b080-cb5b86b863c4)

# Haskell
Linguagem de programação funcional. "Um comando em Haskell é uma fórmula escrita na sintaxe da linguagem."

![O que é](https://github.com/isabelaacr/Haskell/assets/118640598/0b1f22b8-cbff-42f3-8b59-3054011b1ae4)

## Ambiente de execução

![ambiente](https://github.com/isabelaacr/Haskell/assets/118640598/3c8472f2-3cc0-414d-85c3-4b07cc22e3a9)

## Sintaxe Geral

```Haskell
nomefunc arg1 ... argn
```

![SINTAXE](https://github.com/isabelaacr/Haskell/assets/118640598/dfe47968-9f8e-4009-8b1e-6aea0349208c)

## Sintaxe Geral para função sem tipo específico

```Haskell
nomefunc arg1 ... argn = expressão
```

![SINTAXE (2)](https://github.com/isabelaacr/Haskell/assets/118640598/0bd5f3c9-4c99-4878-a974-d7536f0bfcb0)

## Funções de alta ordem (higher order)
Funções que recebem outras funções como argumento e/ou produzem funções como resultado.

##### Exemplos: map e filter

![fUNÇÕES DE ALTA ORDEM](https://github.com/isabelaacr/Haskell/assets/118640598/ea2c4064-e2f9-4ed5-9508-6443aa076c5e)

- Quanto a função map, esta aplica a função a cada elemento da lista, inserindo cada resultado na lista resultante. Ou seja, "mapeia" os elementos da lista de entrada e os insere na lista resultante.
- Sobre a função filter, utiliza de uma função booleana e uma lista para que sua saída sejam apenas os elementos que sejam verdadeiros (true). Ou seja, filtra os elementos de uma lista e seu resultado será referente a função booleana em cada elemento da lista, sendo de tamanho igual ou inferior ao da lista de entrada.

## Outras funções

### Função zipWith
  A função zipWith recebe uma função e duas listas como argumento, para que seja aplicado a função a cada par de elementos correspondentes nas duas listas recebidas, produzindo outra lista como saída.
  
![FUNÇÃO ZIPWITH](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/54931d35-b50e-4caa-8fe9-45cb009e7449)

No exemplo consta: add x y = x + y
Ao aplicar: zipWith add [10,11,12] [1,2,3]
Foi somado 10+1, 11+2, 12+3, resultando a nova lista: [11,13,15]

### Função lambda

![LAMBDA](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/84cbf479-1ffe-4c1a-adad-68c01a5103e6)

### Função left...in

![FUNÇÃO LEFT IN](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/a12fd9bb-adc5-4b3c-a430-52c2b7b6c422)

#### Função where

![Função Where](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/561aad43-d6d2-44ab-9acb-43db4842721e)

## List comprehension

![list comprehension](https://github.com/isabelaacr/Paradigma-Haskell/assets/118640598/e4288ea8-da72-4f19-bae3-0e10a020581d)

## Referências:
[1] Material disponibilizado em aula
[2] https://www.inf.ufpr.br/andrey/ci062/ProgramacaoHaskell.pdf



