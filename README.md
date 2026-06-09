# Collin Professional Dashboard 5.5 Executive Stable

Versão gerada do zero para corrigir erro de abertura no GitHub Pages.

Arquivos para subir na raiz do repositório:
- index.html
- styles.css
- app.js
- data/clientes.json
- assets/icon.svg

Importante:
- Esta versão NÃO usa Chart.js externo.
- Esta versão NÃO registra service-worker, evitando cache quebrado.
- Abre com data/clientes.json local e tenta AutoSync com Google Sheets em segundo plano.
- Se o Google Sheets falhar, o dashboard continua funcionando.

Depois de subir, abra:
https://lukaskweller.github.io/dashbordrepresetantecollin/?v=54


## Versão 5.5
- Adicionada aba "Editor de Textos".
- Permite alterar títulos e descrições direto no dashboard.
- Salva no navegador via localStorage.
- Permite exportar/importar configurações de texto em JSON.
