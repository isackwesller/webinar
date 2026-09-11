# Meet Aula · sistema de ícones

## Fonte única

`/icons.svg` é a **única fonte de geometria dos ícones da interface**. As telas não devem copiar `<path>` de ícones, criar aproximações ou corrigir glifos via CSS mask.

Uso de interface:

```html
<svg class="ma-icon" aria-hidden="true">
  <use href="../icons.svg#heart" />
</svg>
```

Ajuste o caminho relativo conforme a pasta da tela.

## Regra geral

- Ícones funcionais usam **Lucide**, `24×24`, `stroke-width="2"`, `stroke-linecap="round"` e `stroke-linejoin="round"`.
- `.ma-icon` é exclusiva para ícones de traço da interface.
- Logos e marcas externas usam o glifo da própria marca através de `.ma-brand-icon` e símbolos `brand-*` do sprite.
- Emojis são reservados para reações e ondas de reação da sala.
- Um mesmo conceito usa sempre o mesmo símbolo em todas as telas.

## Marcas do protótipo

- `brand-whatsapp`: glifo vetorial da marca; referência consultada no SVG Repo / Simple Icons.
- `brand-google-drive`: glifo da marca usado na importação.
- `brand-google-calendar`: glifo da marca usado em “Adicionar ao Google Agenda”.

## Não fazer

- Não desenhar aproximações de marcas, como balão genérico para WhatsApp.
- Não inserir novos paths Lucide diretamente nos arquivos HTML; acrescente o símbolo uma vez em `/icons.svg`.
- Não usar caracteres Unicode como `←`, `×`, `+` ou `✓` quando exercem função de ícone de interface.
- Não misturar ícones outline de famílias diferentes.
- Não usar CSS masks para substituir SVGs incorretos em telas individuais.
