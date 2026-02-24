# Resolução de conflito do `index.html` (GitHub)

Se o GitHub mostrar conflito entre:
- versão **dashboard** (branch atual), e
- versão **relatório visual antigo** (main),

a resolução correta deste projeto é **manter o dashboard em `index.html`** e manter o relatório em `visual.html`.

## Decisão de merge
- ✅ `index.html` = dashboard/hub de navegação
- ✅ `visual.html` = relatório visual claro
- ✅ `diagnostico.html` = relatório diagnóstico escuro

## Checklist rápido no editor de conflitos
1. Remover todos os marcadores `<<<<<<<`, `=======`, `>>>>>>>`.
2. Em `index.html`, manter apenas:
   - título `Svicero Studio | Dashboard de Relatórios`
   - cards com links para `visual.html`, `diagnostico.html`, `COMO_USAR_TEMPLATE.md`
3. Salvar e marcar como resolvido.

## Motivo
Essa separação evita que o arquivo de entrada (`index.html`) conflite conceitualmente com o conteúdo de relatório e mantém cada página com responsabilidade única.
