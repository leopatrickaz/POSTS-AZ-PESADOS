# Posts AZ Pesados

Repositório para organizar a criação de conteúdo do Instagram da **AZ Pesados**, empresa especializada na venda de **motores de partida e alternadores novos para veículos pesados** (caminhões, máquinas, tratores, empilhadeiras, ônibus e similares).

## Objetivo

Centralizar o planejamento, a escrita e o histórico dos posts do Instagram: legendas, hashtags, briefings visuais e ideias de pauta — tudo em um só lugar, versionado.

## Estrutura

```
posts/
  fixados/        Posts principais que ficam fixados no perfil (institucional)
  publicados/     Histórico de posts já publicados
  rascunhos/      Posts em elaboração, ainda não publicados
calendario/
  calendario-editorial.md   Planejamento de datas, temas e status dos posts
templates/
  template-legenda.md        Modelo de legenda + hashtags
  template-briefing-visual.md Modelo de briefing para a peça visual/design
ideias/
  banco-de-ideias.md   Lista de pautas e temas para gerar novos posts
```

## Sobre a empresa

**AZ Pesados** vende motores de partida e alternadores novos para veículos pesados: caminhões, máquinas, tratores, empilhadeiras, ônibus, entre outros.

## Como usar

1. Toda nova ideia de post nasce em `ideias/banco-de-ideias.md`.
2. Ao ser desenvolvida, vira um arquivo em `posts/rascunhos/`, usando `templates/template-legenda.md` como base.
3. Depois de publicado, o arquivo é movido para `posts/publicados/` e o status é atualizado em `calendario/calendario-editorial.md`.
4. Os 3 posts institucionais que ficam fixados no perfil vivem em `posts/fixados/`.
