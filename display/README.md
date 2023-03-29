![1](https://user-images.githubusercontent.com/103377845/228640113-5efa6ffe-31a1-4d37-816f-02f63be55c49.png)


"_Todo elemento em uma página web é renderizado como uma caixa retangular. A propriedade `display` de CSS vai determinar como essa caixa vai ser comportar_" - [Chris Coyier](https://twitter.com/chriscoyier)

Entender a propriedade `display` é fundamental para que possamos compreender o fluxo e estruturação de uma página web. Todos os elementos por padrão já possuem um valor para a propriedade e, geralmente estas são `block` ou `inline`.

A propriedade `display` especifica o comportamento de exibição (o tipo de caixa de renderização) de um elemento.

Formalmente, a propriedade **`display`** define os _tipos de exibição_ internos e externos de um elemento. O tipo externo define a participação de um elemento no [layout de fluxo](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flow_Layout "Currently only available in English (US)"); o tipo interno define o layout dos filhos. Alguns valores de `display` são totalmente definidos em suas próprias especificações individuais; por exemplo, o detalhe do que acontece quando `display: flex` é declarado é definido na especificação CSS Flexible Box Model.

Alguns estão listados em seguida :

```
display: block;
display: inline;
display: inline-block;
display: flex;
display: grid;
```

______________________________

![2](https://user-images.githubusercontent.com/103377845/228640146-a99b3b06-2f4e-4af5-a233-9f3e386fbbb0.png)


`block`

O elemento gera uma caixa de elemento de bloco, gerando quebras de linha antes e depois do elemento quando no fluxo normal.
- aceita as propriedades _width_ e _height_

![3](https://user-images.githubusercontent.com/103377845/228640188-3344d487-6602-44d6-b1fc-0a26ea473f6d.png)


`inline`

O elemento gera uma ou mais caixas de elemento em linha que não geram quebras de linha antes ou depois de si mesmas. No fluxo normal, o próximo elemento estará na mesma linha se houver espaço.
-  não aceita as propriedades _width_ e _height_.


![4](https://user-images.githubusercontent.com/103377845/228640243-57fe5d4c-80e3-40fb-8f95-11813e91ece7.png)

`inline-block`

O elemento gera uma caixa de elemento de bloco que fluirá com o conteúdo ao redor como se fosse uma única caixa em linha (comportando-se como um elemento substituído faria).

É equivalente a `inline flow-root`.

![5](https://user-images.githubusercontent.com/103377845/228640282-242149a4-76bc-4b8a-b675-2ce1d8eb5c18.png)


`flex`

O elemento se comporta como um elemento de bloco e apresenta seu conteúdo de acordo com o [modelo flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout).

![6](https://user-images.githubusercontent.com/103377845/228640367-a1998257-db1a-4f41-b04c-a4d4500ffc4a.png)


`grid`


O elemento se comporta como um elemento de bloco e apresenta seu conteúdo de acordo com o [modelo de grade](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout).

