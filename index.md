---
layout: default
title: "EM CONSTRUÇÃO... 🚧"
---

Bem-vindo. Me chamo Artur e eu sou Engenheiro de Computação. Minha área de atuação é Reconhecimento de Padrões e Visão Computacional. Este blog é um espaço de compartilhamento de textos sobre política, filosofia e sociedade, sempre pelo olhar da tradição crítica latino-americana; um espaço de debate e construção do socialismo.

Todos os ensaios encontrados aqui estão em perpétua mudança. Alguns mais explicitamente que outros, pois é comum encontrar textos inacabados. A escolha por guardá-los num lugar que salva a memória de cada mudança ocorrida tem motivação dupla:

1. Preservar o fluxo de aprendizado acumulado.
2. Registrar os principais pontos de mudança de ideia (em especial os erros).

## Textos

<ul class="list-group list-group-flush">
  {% for post in site.posts %}
    <li class="list-group-item">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
