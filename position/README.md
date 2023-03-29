# Posicionamentos | Positions
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
### 
- _static_
- _fixed_ 
- _sticky_
- _relative_
- _absolute_


![1](https://user-images.githubusercontent.com/103377845/228626459-fc68ca95-45a9-491f-bf3f-fc5fecf049aa.png)


Aqui você encontra o texto para guardar: [position](https://www.canva.com/design/DAFdQR7FbRY/ZekqWUoQmZkIHvZ4NIbyWA/view?website#2:position)


## **Static / estático**

![2](https://user-images.githubusercontent.com/103377845/228626630-afff94ec-f5bc-4fe3-97d3-68dbbd123461.png)


Vem por padrão **position: static**.

Os elementos posicionados estáticos não são afetados pelas propriedades _top, bottom, left, e right_.

## **Fixed / Fixo**

![3](https://user-images.githubusercontent.com/103377845/228627190-c6026a0c-3acb-4560-a596-e304ce2c192e.png)


Um elemento com **posição: fixed;** está posicionado em relação à viewport, o que significa que sempre permanece no mesmo lugar, mesmo que a página seja rolada. As propriedades superior, direita, inferior e esquerda são usadas para posicionar o elemento.

Um elemento fixo não deixa uma lacuna na página onde normalmente estaria localizado.

## **Sticky**

![4](https://user-images.githubusercontent.com/103377845/228627303-27c9ce8f-af2e-408d-a4a0-b64691437460.png)


Um elemento com **posição: sticky;** é posicionado com base na posição de rolagem da pagina do usuário.

Um elemento fixo alterna entre relativo e fixo, dependendo da posição de rolagem. Ele é posicionado relativo até que uma determinada posição de deslocamento seja encontrada na viewport - então ele 'gruda' no lugar (como position:fixed).

## **Relative / Relativo**

![5](https://user-images.githubusercontent.com/103377845/228627361-8d08cd5d-b4cf-4c39-941a-03fcfb313f73.png)


O **position: relative;** é o posicionamento que toma como a sí como relação,seguindo o fluxo padrao.
Outros conteúdos não serão ajustados para caber em qualquer lacuna deixada pelo elemento.

Sem usar os deslocamentos top, right, bottom e left o position relative funciona para nada.

## **Absolute / Absoluto**

![6](https://user-images.githubusercontent.com/103377845/228627392-ca9b3961-e2e2-4c6c-9825-19947549d81f.png)


Um elemento com **posição: absolute;** é posicionado em relação ao ancestral posicionado mais próximo (em vez de posicionado em relação à viewport, como fixo).

No entanto; se um elemento posicionado absoluto não tiver ancestrais posicionados, ele usará o corpo do documento e se moverá junto com a rolagem da página.

Nota: Elementos posicionados absolutos são removidos do fluxo normal e podem sobrepor elementos.




