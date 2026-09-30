# Quiz Modo Criador

`index.html` é o quiz completo, pronto pra deploy (Vercel, Netlify, etc). É uma página única, sem build step: HTML + Tailwind via CDN + JS inline, no mesmo estilo visual do site atual do Modo Criador (fundo escuro, verde `#36C65B`, Inter + JetBrains Mono). Todas as imagens estão embutidas como WebP (base64), então o arquivo é autossuficiente — não depende de nenhuma outra pasta de assets.

## Fluxo
Capa → nome → 7 perguntas (dispositivo, crença, checklist, 4 de perfil embaralhadas) → tela de carregamento → resultado com diagnóstico, currículo, bônus, depoimentos reais, antes/depois reais, FAQ e oferta.

## Único item pendente

- **CNPJ no rodapé**: usei `44.997.333/0001-13` (corrigi um dígito extra que tinha no número que você mandou). Só confirmar se está certo antes de publicar.

## Já é tudo real, nada mais é placeholder

- **Preço**: R$97 à vista ou 12x de R$9,34 (de R$397).
- **Checkout**: `https://go.rodrigobaiao.com/pay/quiz`.
- **WhatsApp de suporte**: `+55 21 98927-3119`, com mensagem pré-definida nos links.
- **Garantia**: incondicional de 7 dias.
- **3 depoimentos**: prints reais de alunos via WhatsApp, fundo removido.
- **3 antes/depois**: Claudemir (esposa), Willian Capriata e Lucas — extraídos do "Manual do Especialista".
- **Módulos, bônus (5, avaliados em R$815) e FAQ**: vêm do site atual (`leticiarequiel/modocriador`, pasta "Novo site") e do Manual do Especialista.

Resolvendo o CNPJ, dá pra subir direto.
