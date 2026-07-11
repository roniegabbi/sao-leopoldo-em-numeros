# São Leopoldo em Números

Radiografia em números do município de São Leopoldo/RS — iniciativa da
**Secretaria de Desenvolvimento Econômico**. Site estático de página única com
12 capítulos (identidade, economia, indústria, inovação, universitária, trabalho,
exportações, saúde, segurança, mobilidade, turismo e cultura).

## Estrutura
- `index.html` — o site completo (HTML + CSS + JS em arquivo único)
- `img/` — logo e fotos da cidade

## Deploy (Vercel)
Projeto 100% estático, sem etapa de build — a raiz do projeto é a saída (`index.html`).

## Dados
Os números vivem no objeto `DATA` dentro do `index.html` e há um bloco
`SUPABASE_CONFIG` preparado para, futuramente, alimentar os indicadores a partir
de um banco Supabase (painel interno no rodapé · ⚙ Painel interno).
