# Como reutilizar o relatório sem quebrar o design

Sim — você pode reaproveitar este layout para próximos diagnósticos.

## Regra prática
No arquivo `diagnostico.html`, **mantenha intacto**:
- `<head>` (fonts, Tailwind config, estilos)
- `<script>` final (animações)
- `<header>` (capa visual)

E troque apenas o conteúdo entre:
- `<!-- BEGIN REPORT CONTENT -->`
- `<!-- END REPORT CONTENT -->`

## Fluxo rápido
1. Abra `diagnostico.html`.
2. Localize os marcadores `BEGIN/END REPORT CONTENT`.
3. Substitua o conteúdo interno pelo body do novo diagnóstico (seções/cards/XML).
4. Exporte para PDF pelo navegador.

## Dica
Se quiser trocar **somente textos** sem mexer no layout, preserve as classes Tailwind já existentes e altere apenas o texto dentro dos elementos.


## Também vale para `visual.html`
A mesma lógica de troca entre `BEGIN/END REPORT CONTENT` também foi aplicada ao `visual.html`.
