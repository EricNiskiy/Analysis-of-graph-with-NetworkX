# Análise da amostra da rede de garantia de direitos da proteção social especial de Diadema

Este projeto é uma análise de uma amostra da rede de garantia de direitos da Assistência Social de Diadema. A análise foi desenvolvida no ambiente do Google Colab, em Python, com funções da biblioteca NetworkX. Outras duas bibliotecas auxiliares foram usadas: Pandas e MatPlotLib.

As informações do grafo foram coletadas diretamente na Prefeitura de Diadema, organizados na planilha Grafo.xlsx e modelados visualmente conforme visto abaixo no aplicativo <a href="https://www.drawio.com/">Draw.io</a>. As etapas de organização finalizaram com a síntese dos dados no arquivo "lista de arestas.csv". Ele é utilizado no código, através da biblioteca Pandas, para obter seus nós e relações, tornando possível trabalhar com o grafo aplicando funções da biblioteca NetworkX.

<img src="Modelagem do grafo.png" alt="Grafo modelado no Draw.io" height=500>

Para que o código funcione adequadamente, é necessário atentar-se ao caminho correto do arquivo "lista de arestas.csv" em:

`df = pd.read_csv('/content/Lista de arestas.csv', header=0)`
