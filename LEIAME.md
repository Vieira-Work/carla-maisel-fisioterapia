# Site — Carla Maisel Fisioterapia

Landing page estática (HTML + CSS + JS, sem dependências). Abre com dois cliques
no `index.html` e pode ser publicada em qualquer lugar (Vercel, Netlify, GitHub
Pages, hospedagem comum).

## Estrutura
- `index.html` — conteúdo e seções
- `styles.css` — visual (paleta verde da marca + base neutra)
- `script.js` — animação de entrada ao rolar, nav e ano do rodapé
- `assets/` — fotos

## Conteúdo já preenchido
- WhatsApp: **(12) 99741-7891** (`5512997417891`) — usado em todos os botões e no flutuante
- CREFITO: **3/79817-F**
- Endereço: Ed. Plaza JK, sala 710 · Av. Juscelino Kubitscheck de Oliveira, 1301 · Campo do Galvão · Guaratinguetá/SP
- Seções: início, tratamentos (áreas 01–05), atendimento domiciliar, quando procurar, sobre, onde atendo, rodapé

## Fotos — IMPORTANTE
As duas fotos vieram de posts do Facebook (tinham texto de marketing). Recortei a
figura dela e removi o texto:
- `assets/carla-hero.jpg` — jaleco, fundo verde (hero)
- `assets/carla-sobre.jpg` — escritório (seção domiciliar)
- `assets/carla-jaleco.png` / `assets/carla-escritorio.png` — originais (guardados)

**Recomendado:** substituir por fotos limpas em boa resolução quando a Carla tiver.
Basta trocar os arquivos `carla-hero.jpg` e `carla-sobre.jpg` mantendo o mesmo nome.

## Ajustes fáceis
- Trocar textos: direto no `index.html`.
- Cor de acento: variáveis `--green-*` no topo do `styles.css`.
- Mapa: o `iframe` do rodapé aponta para o endereço; só aparece com internet.

## Publicar (sugestão)
Arrastar a pasta em https://app.netlify.com/drop — fica no ar em segundos com link.
