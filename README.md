# Imersão Vida Memorável · Orlando

Landing page de vendas da Imersão Vida Memorável com Vivi Marques — Orlando, Flórida, 21 de novembro de 2026.

## Estrutura

```
index.html        página completa (HTML, CSS e JS em um único arquivo)
assets/           fotos e logo (webp)
assets/videos/    vídeos dos depoimentos (Mara.mp4, Luana.mp4, Roseli.mp4) — adicionar
```

## Configuração

No fim do `index.html`, o bloco `CONFIG` concentra o que muda com frequência:

| Chave | O que é |
|---|---|
| `lotPercent` | % do lote atual vendido |
| `eventTime` | horário do evento |
| `venue` | local / endereço em Orlando |
| `whatsappNumber` | número do WhatsApp com DDI, só dígitos |
| `careerYears` | anos de carreira da Vivi |
| `cnpj` | CNPJ do rodapé |
| `videos` | caminhos dos vídeos de depoimento |

## Hospedagem

Publicado via GitHub Pages a partir da branch `main`. Para usar um domínio próprio, adicione o domínio em *Settings → Pages → Custom domain* e aponte o DNS na Hostinger.
