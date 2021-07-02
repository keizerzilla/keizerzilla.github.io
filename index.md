---
layout: default
title: "EM CONSTRUÇÃO... 🚧"
---

Bem-vindo. Me chamo Artur e eu sou Engenheiro de Computação. Minha área de atuação é Reconhecimento de Padrões e Visão Computacional. Este blog não é um espaço de textos técnicos, mas de compartilhamento de ensaios em política, filosofia e sociedade a partir do prisma da tradição crítica latino-americana.

Todos os ensaios encontrados aqui estão em perpétua mudança. Alguns mais explicitamente que outros, pois é comum encontrar textos inacabados. A escolha por guardá-los num lugar que salva a memória de cada mudança ocorrida tem motivação dupla:

1. Preservar o fluxo constante de aprendizado acumulado.
2. Registrar os principais pontos de mudança de ideia, em especial os erros.

Que este seja um espaço de crítica e de construção do socialismo. Eu te convido a colaborar.

## Textos

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
