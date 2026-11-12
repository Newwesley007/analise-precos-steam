# Variação de preços de jogos na Steam Brasil

Projeto acadêmico em grupo que compara os preços de 200 jogos lançados na Steam em 2020 com os preços dos mesmos títulos em 2026. A análise foi feita em Python no Google Colab, com um dashboard em Plotly.

## Metodologia

- Os preços de 2020 vieram de publicações do GameBlast próximas aos lançamentos. Os de 2026 foram coletados na Steam Brasil em 10 de novembro de 2026.
- A comparação usa os preços normais dos jogos, em reais, sem ajuste pela inflação.
- Os preços foram pareados por jogo. A análise por gênero inclui grupos com pelo menos 10 títulos.

## Resultados

| Indicador | 2020 | 2026 |
| --- | ---: | ---: |
| Preço médio | R$ 36,58 | R$ 42,38 |
| Preço mediano | R$ 28,99 | R$ 28,99 |

O preço médio subiu **15,9%**. Na amostra, **74 jogos** ficaram mais caros, **41** ficaram mais baratos e **85** mantiveram o preço.

## Minha contribuição

Defini o recorte da análise e usei o ChatGPT para gerar e ajustar o código e o dashboard.


## Notebook

[Abrir notebook da análise no Google Colab](https://colab.research.google.com/drive/1Hrvilc47cGuTl_lJVq5iIxf2eGMTnI_m?usp=sharing)
