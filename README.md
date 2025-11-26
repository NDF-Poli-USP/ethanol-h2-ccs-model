# ethanol-h2-ccs-model

Modelo computacional desenvolvido para o Trabalho Final de Graduação: **“Viabilidade da Produção de Hidrogênio com Emissões Negativas via Reforma de Etanol com Captura e Armazenamento de Carbono (CCS)”**  
Escola Politécnica da Universidade de São Paulo (Poli-USP)

## Sobre o modelo
O notebook implementa um modelo completo para estimar:
- emissões de construção (gasoduto, poço injetor, planta de H₂);
- emissões operacionais da rota etanol → hidrogênio;
- taxas de captura e volumes de CO₂ geologicamente armazenáveis;
- resultados por cenário, incluindo ponto de neutralidade e potencial de emissões negativas (BECCS);
- geração de figuras e tabelas utilizadas no estudo.

O código foi estruturado para permitir a reprodução dos cenários avaliados e a adaptação dos parâmetros conforme as necessidades de pesquisa.

## Conteúdo do repositório
- **modelo_emissoes_h2_etanol_ccs_notebook.ipynb**  
  Notebook contendo todas as etapas do modelo:
  - definição dos parâmetros de entrada (distância do duto, profundidade de injeção, produtividade de CO₂ etc.);
  - funções de cálculo de emissões de construção e operação;
  - modelagem do fluxo de CO₂ capturado;
  - simulação dos cinco cenários analisados no estudo;
  - geração automática dos gráficos e resultados.

## Objetivos
O código disponibilizado neste repositório permite:
1. estimar as emissões totais da cadeia etanol → hidrogênio → CCS;
2. calcular o ponto de neutralidade de carbono para diferentes configurações do sistema;
3. analisar o potencial de emissões negativas via Bio-CCS;
4. fornecer base numérica e gráfica para estudos acadêmicos e de engenharia relacionados ao tema.

## Como executar
Requisitos:
- Python 3.11+  

Bibliotecas utilizadas:
- numpy  
- pandas  
- matplotlib  

Para executar:
1. Abra o arquivo `.ipynb` em um ambiente Jupyter.  
2. Execute as células sequencialmente, conforme organizadas no notebook.

## Autoria
Luana Cristofani Salgueiro  
Juliana Rodrigues Prado de Oliveira  

Projeto NDF – Poli-USP  
Research Centre for Greenhouse Gas Innovation (RCGI)

