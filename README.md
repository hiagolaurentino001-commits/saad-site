# SAAD – Social Assessoria Administrativa

Site de página única da SAAD (Aracaju/SE): benefícios do INSS, regularização de imóveis e recrutamento para empresas. O foco da página é levar o visitante ao WhatsApp.

## Arquivos

- `index.html`: a página inteira (HTML e CSS, sem dependências).
- `assets/saad-logo.svg`: logo horizontal.
- `assets/saad-logo.png`: logo em imagem, usada na prévia de compartilhamento.
- `assets/saad-icone.png`: ícone da aba do navegador (favicon).

## Antes de publicar

1. **Número do WhatsApp:** no fim do `index.html`, troque `var WHATSAPP = "5579000000000";` pelo número real (55 + DDD + número, só algarismos). Todos os botões passam a usar esse número.
2. **Horário de atendimento:** substitua `[HORÁRIO DE ATENDIMENTO]` na chamada final.
3. **Instagram:** substitua `[@saadadministra]` no rodapé.

## Publicar com GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch `main`, pasta `/ (root)` → Save.
Em alguns minutos o site fica disponível em `https://<usuario>.github.io/<repositorio>/`.
