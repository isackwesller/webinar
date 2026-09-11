# Meet Aula · sistema de ícones

## Regra geral

- Ícones funcionais da interface usam a família **Lucide**, em SVG inline, `viewBox="0 0 24 24"`, `stroke-width="2"`, `stroke-linecap="round"` e `stroke-linejoin="round"`.
- A classe compartilhada é `.ma-icon` e nunca deve receber `fill` de marca.
- Logos e marcas externas usam o glifo oficial da marca, em SVG preenchido, pela classe `.ma-brand-icon`.
- Emojis são reservados para reações da sala.

## Marcas usadas no protótipo

- WhatsApp: glifo oficial/brand glyph em SVG; referência visual e licença consultadas no SVG Repo. A geometria incorporada no código é a versão vetorial pública mantida pelo Simple Icons.
- Google Drive: glifo oficial/brand glyph em SVG, incorporado no botão de importação.
- Google Calendar: glifo de marca no botão “Adicionar ao Google Agenda”.

## Não fazer

- Não desenhar aproximações de logos (ex.: balão genérico para representar WhatsApp).
- Não misturar ícones preenchidos de marca com `.ma-icon`.
- Não usar caracteres Unicode como `←` ou `✓` quando a função é de ícone de interface; usar o equivalente Lucide.
- Não misturar famílias outline com espessuras diferentes na mesma interface.
