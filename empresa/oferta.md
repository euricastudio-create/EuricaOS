# O que vendemos

> Um material low ticket por vez, modelado de uma oferta validada, com bônus e order bumps.
> O preço de cada produto é descoberto testando: começa em US$ 6,90 e sobe até parar de vender.
> Produto que dá certo continua e vai para outros idiomas; produto que dá errado é trocado.

| Produto | Preço | Para quem | Promessa |
|---|---|---|---|
| 40 bolsas de crochê (pronto, ainda não lançado) | teste começa em US$ 6,90; meta de chegar a pelo menos US$ 24,90 | mulheres de 30 a 65 anos que gostam de artesanato | "40 modelos de bolsas que realmente vendam", com aparência de boutique |

## 40 bolsas de crochê
- **Nome do produto:** 40 Bolsos a Crochet que Parecen de Boutique (40 modelos, 6 lâminas A4 cada)
- **Bônus (5):**
  1. Tabla de Puntos y Abreviaturas (amarelo pastel, 6 páginas)
  2. Bolso Festival Porta Celular (rosé, 5 páginas)
  3. Billetera a Crochet (verde sálvia, 8 páginas)
  4. Portachaquetas a Crochet (azul pastel, 6 páginas)
  5. SÚPER BONO: Estuche para Lentes a Crochet (terracota, 4 páginas)
- **Order bumps (coleção de acessórios para tecnologia):**
  1. Miniestuche para Audífonos (mel, 4 páginas)
  2. Portacelular de Carga (terracota, 4 páginas)
  3. Funda para Tablet (verde-oliva, 5 páginas)
  4. Bolso para Laptop (azul-petróleo, 6 páginas)
  5. Colección Premium: os quatro juntos + brinde Ranita Amigurumi (chaveiro de sapinho, 5 páginas)
- **Ideia de preço dos bumps:** 5,90, 6,90 e 9,90, mais a Colección Premium por 19,90 (moeda a confirmar; preços ainda em definição com o Claude)
- **Upsell:** ainda não pensado
- **Página:** nova versão em `paginas/40-bolsos/` (17/10). Para publicar faltam o link do checkout Hotmart (`CHECKOUT_URL`) e o ID do Pixel do Meta (`META_PIXEL_ID`), os dois no bloco CONFIGURACIÓN no fim do `index.html`. Sobe para a Hostinger a pasta inteira (index.html + assets, inclusive `assets/g/`, que são as versões grandes usadas para ampliar)
- **Valores riscados na página (ancoragem), desde 17/10:** principal US$ 47,90; Bônus 1 US$ 7,90; Bônus 2 US$ 9,90; Bônus 3 US$ 9,90; Bônus 4 US$ 5,90; Súper Bono US$ 12,90; total US$ 94,40
  - Regras: o principal vale mais que todos os bônus juntos; o Súper Bono é o bônus de maior valor; tudo termina em ,90 (a ancoragem e o preço de venda); a âncora tem que continuar forte quando o preço chegar a US$ 24,90
- **Garantia:** 7 dias
- **Order bumps:** aparecem só no checkout da Hotmart, não na página
- **Arquivos do produto:** organizados em `C:\Users\ferna\OneDrive\Desktop\EURICA\40 Bolsos a Crochet - Entregaveis\` (produto principal em PDF; bônus e bumps em PNG A4, uma imagem por página). Versões que não foram usadas ficam em `_versoes_descartadas`
- **Arquivos para subir na Hotmart (17/10):** pasta `04 PDFs para Hotmart\`: `40 Bolsos a Crochet.pdf` (modelos 01 a 40, 240 páginas, 26,9 MB, com índice de navegação por modelo, sem a lista oficial), 5 PDFs de bônus e 5 PDFs de bumps (1,6 a 3,2 MB cada; o Bump 5 junta a capa da Colección Premium com a Ranita)

## Como um leva ao outro
- Produto principal → order bumps no checkout da Hotmart → (upsell `[a preencher]`)
- Quem compra um material costuma comprar qual outro depois: `[a preencher]`

## Testados e parados
- Libera Espacio en tu Celular (espanhol, com 4 bônus): tentado, não deu certo
- Personagens de tarot (MVM EUA): projeto de outro curso, não andou

## Fora da EURICA por enquanto
- Kit Sem Encrenca: vai ser com a Fernanda aparecendo (Instagram, YouTube); retomar só quando o low ticket estiver rodando certinho
- Nutri (Láminas Nutricionales Pro e Prescripción Nutricional Pro): coprodução com a sócia, em outra pasta
