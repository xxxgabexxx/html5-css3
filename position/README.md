# Posicionamentos | Positions
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
### 
- _static_
- _sticky_
- _fixed_
- _relative_
- _absolute_


Aqui você encontra o texto para guardar: [position](https://www.canva.com/design/DAFdQR7FbRY/ZekqWUoQmZkIHvZ4NIbyWA/view?website#2:position)


## **Static / estático**

Vem por padrão **position: static**.

Os elementos posicionados estáticos não são afetados pelas propriedades _top, bottom, left, e right_.

## **Relative / Relativo**
O **position: relative;** é o posicionamento que toma como a sí como relação,seguindo o fluxo padrao.
Outros conteúdos não serão ajustados para caber em qualquer lacuna deixada pelo elemento.

Sem usar os deslocamentos top, right, bottom e left o position relative funciona para nada.

## **Absolute / Absoluto**
Um elemento com **posição: absolute;** é posicionado em relação ao ancestral posicionado mais próximo (em vez de posicionado em relação à viewport, como fixo).

No entanto; se um elemento posicionado absoluto não tiver ancestrais posicionados, ele usará o corpo do documento e se moverá junto com a rolagem da página.

Nota: Elementos posicionados absolutos são removidos do fluxo normal e podem sobrepor elementos.

## **Fixed / Fixo**

Um elemento com **posição: fixed;** está posicionado em relação à viewport, o que significa que sempre permanece no mesmo lugar, mesmo que a página seja rolada. As propriedades superior, direita, inferior e esquerda são usadas para posicionar o elemento.

Um elemento fixo não deixa uma lacuna na página onde normalmente estaria localizado.

## **Sticky**
Um elemento com **posição: sticky;** é posicionado com base na posição de rolagem da pagina do usuário.

Um elemento fixo alterna entre relativo e fixo, dependendo da posição de rolagem. Ele é posicionado relativo até que uma determinada posição de deslocamento seja encontrada na viewport - então ele 'gruda' no lugar (como position:fixed).

