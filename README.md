# Python Finance Lab

*Finanças na prática, notebook por notebook.*

[![YouTube](https://img.shields.io/badge/YouTube-%40PythonFinanceLab-red?logo=youtube)](https://www.youtube.com/@PythonFinanceLab)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)

Aqui ficam os notebooks das aulas do canal **Python Finance Lab** no YouTube. Cada aula parte de uma pergunta que todo investidor iniciante já se fez e responde a ela com dados reais, em Python, começando do zero.

O caminho é sempre o mesmo: **conceito financeiro → fórmula → código → validação → interpretação**. A mesma carteira de 10 ações acompanha a série do começo ao fim, e o Python cresce um degrau por aula.

> **Aviso:** conteúdo exclusivamente educacional. Nada aqui é recomendação de investimento.

## Aulas da 1ª temporada

Cada notebook é publicado aqui junto com o vídeo da aula. Se o link de uma aula ainda não abrir, o vídeo dela ainda não saiu.

| # | Pergunta | Python novo | Notebook | Abrir no navegador | Vídeo |
|---|---|---|---|---|---|
| 1 | Minha carteira de 10 ações ganhou do Ibovespa e do CDI? | Variáveis, listas, DataFrame, gráfico | [Aula_01.ipynb](notebooks/Aula_01.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_01.ipynb) | [▶ Assistir](https://www.youtube.com/watch?v=FC0pOAz4rrY) |
| 2 | Quanto risco eu corri para ter esse retorno? | Funções (`def`) e `apply` | [Aula_02.ipynb](notebooks/Aula_02.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_02.ipynb) | [▶ Assistir](https://www.youtube.com/watch?v=7rZs7w6K3PA) |
| 3 | E se eu tivesse investido R\$ 200 todo mês? | Laço `for`, `resample` mensal | [Aula_03.ipynb](notebooks/Aula_03.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_03.ipynb) | [▶ Assistir](https://www.youtube.com/watch?v=4Uo9hT1_j_Q) |
| 4 | Rebalancear a carteira vale a pena? | `if` dentro do laço, dicionários | [Aula_04.ipynb](notebooks/Aula_04.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_04.ipynb) | [▶ Assistir](https://www.youtube.com/watch?v=-y-km-1Fq1Y) |
| 5 | 10 ações diversificam de verdade? | `corr()`, mapa de calor, combinações | [Aula_05.ipynb](notebooks/Aula_05.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_05.ipynb) | [▶ Assistir](https://www.youtube.com/watch?v=FZySkrlX3lM) |
| 6 | Qual a "melhor" combinação de pesos? | NumPy, sorteio de milhares de carteiras | [Aula_06.ipynb](notebooks/Aula_06.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_06.ipynb) | em breve |
| 7 | Como baixar dados de cripto direto da fonte? | API com parâmetros, JSON, `while`, plotly | [Aula_07.ipynb](notebooks/Aula_07.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_07.ipynb) | em breve |
| 8 | E se 5% da carteira fosse Bitcoin? | Alinhar calendários e fusos horários | [Aula_08.ipynb](notebooks/Aula_08.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_08.ipynb) | em breve |
| 9 | Média móvel funciona? | `rolling`, sinais, `shift` | [Aula_09.ipynb](notebooks/Aula_09.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_09.ipynb) | em breve |
| 10 | Quanto essa carteira pode valer em 10 anos? | Módulo `.py` próprio, `ipywidgets` | [Aula_10.ipynb](notebooks/Aula_10.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chygnus/python-finance-lab-aulas/blob/main/notebooks/Aula_10.ipynb) | em breve |

## Como usar

### Opção 1: abrir no navegador, sem instalar nada

Clique em **Open in Colab** na linha da aula. O notebook abre no Google Colab, que pede uma conta Google. Rode as células de cima para baixo com **Shift + Enter**. Para guardar o que você mudou, use **Arquivo → Salvar uma cópia no Drive**.

### Opção 2: baixar e rodar no seu computador

- **Uma aula só:** clique no nome do notebook na tabela acima. Na página que abrir, clique no botão **Download raw file** (a setinha para baixo, no canto direito, logo acima do conteúdo).
- **Todas as aulas de uma vez:** clique no botão verde **<> Code**, no topo desta página, e depois em **Download ZIP**.

Para rodar, você precisa do Python com o Jupyter. O jeito mais simples é instalar o [Anaconda](https://www.anaconda.com/download), que já vem com quase tudo. Depois, abra o **Anaconda Prompt**, entre na pasta que você baixou e rode:

```
pip install -r requirements.txt
jupyter notebook
```

Se aparecer `ModuleNotFoundError` logo depois de instalar uma biblioteca, reinicie o kernel (**Kernel → Restart Kernel**) e rode o notebook de novo desde o começo.

## A carteira e as premissas

- **Carteira:** ITUB4, VALE3, PETR4, WEGE3, ABEV3, EGIE3, SUZB3, RADL3, VIVT3 e TOTS3, uma ação por setor. É um exemplo didático, não uma recomendação.
- **Período:** de 01/10/2021 a 30/09/2026. As datas são fixas para que todo mundo que rodar o notebook chegue aos mesmos números do vídeo.
- **Dinheiro:** capital inicial de R\$ 2.000, ou seja, R\$ 200 em cada ação. A partir da aula 3, entra um aporte de R\$ 200 por mês.
- **Comparação:** sempre contra o Ibovespa e o CDI, sem custos e impostos, exceto nas aulas que tratam deles.

## De onde vêm os dados

Todas as fontes são gratuitas e não pedem cadastro.

| Dado | Fonte | Aulas |
|---|---|---|
| Ações e Ibovespa | Yahoo Finance, pela biblioteca `yfinance` | 1 a 10 |
| CDI | Banco Central, sistema SGS (série 12) | 1 a 10 |
| Dólar | Banco Central, sistema SGS (série 1) | 8 |
| IPCA | Banco Central, sistema SGS (série 433) | 10 |
| Criptomoedas | API pública da Binance (`/api/v3/klines`) | 7 e 8 |

O Yahoo Finance não é uma fonte oficial, por isso toda aula confere pelo menos um número com outra fonte. Se uma célula que baixa dados der erro de conexão, espere alguns minutos e rode de novo: às vezes a fonte fica fora do ar por um tempo.

## Licença

O **código** dos notebooks é livre, sob a licença MIT: você pode usar, modificar e compartilhar, desde que mantenha o aviso de copyright. Os **textos explicativos** fazem parte do ebook do Python Finance Lab: estão liberados para estudo pessoal, mas não podem ser republicados nem vendidos sem autorização. Os detalhes estão no arquivo [LICENSE](LICENSE).

---

Feito pelo [Python Finance Lab](https://www.youtube.com/@PythonFinanceLab). Se as aulas estão te ajudando, deixe uma estrela neste repositório e se inscreva no canal.
