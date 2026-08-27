# Valorant Hub

O Valorant Hub é um projeto desenvolvido para apresentar informações sobre o jogo Valorant.
O site reunirá informações sobre agentes, mapas, armas e outros elementos do jogo.
O objetivo é organizar essas informações de forma simples e fácil de entender.

# Avaliador Juan Riquelme Silva Félix 27/08/2026--Avaliação do INDEX.HTML:


   ACERTOS:
  - Estrutura HTML5 correta: DOCTYPE, lang="pt-BR", charset, viewport.
  - Apenas um <main>, com <header> e <footer> bem posicionados.
  - <ul> com 3 itens do tema e <table> com 2x2 dados reais.
  - Link externo com target="_blank" e rel="noopener noreferrer" corretos.
  - <img> com alt descritivo (não genérico).
  - Hierarquia de headings correta (h1 > h2), sem pular níveis.
  - <fieldset> + <legend> agrupando o formulário.
  - Todos os label[for] batem com os id dos inputs (nome, email, agente, nota).
  - Tipos semânticos corretos: type="email" e type="number" (min/max) na nota.
  - required presente em pelo menos 2 campos (nome e email).
  - <video> com atributo controls e type="video/mp4" especificado no source.

  ERROS:
  1. MÍDIA: apenas UM <source> no <video> — falta o segundo formato de fallback
     (ex: WebM), exigido no checkpoint da Aula 04.
  2. MÍDIA: falta o atributo poster no <video>.
  3. MÍDIA: falta preload definido e o comentário justificando a escolha
     (none/metadata/auto).
  4. MÍDIA: nome do arquivo com espaço ("video valorant2.mp4") — viola
     convenção de nomes de arquivo (Aula 02) e pode causar erro 404.
  5. SEMÂNTICA: o vídeo está dentro de uma <div> sem heading, quebrando o
     padrão de <section> usado no resto da página — usar <section> ou <figure>.
  6. SEMÂNTICA: campo "Agente" usa type="text", mas deveria ser <select>,
     já que representa um conjunto fixo de opções.
  7. FORMULÁRIO: falta o botão de envio (<button type="submit">) — sem ele
     não é possível testar a validação de campos obrigatórios vazios.
  8. BOAS PRÁTICAS: uso de style inline no <img> e no <video>, quando o
     projeto já tem pasta css/ para isso.
  9. BOAS PRÁTICAS: nome de arquivo da imagem pouco descritivo (images.jpg).
-->
