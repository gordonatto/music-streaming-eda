🎧 Análise de Dados: Serviço de Streaming de Música

📌 Visão Geral

Este projeto simula um cenário real de Data Science em uma empresa de streaming. O objetivo foi analisar uma base de dados de usuários para entender padrões de comportamento, diferenças entre assinantes (Premium vs. Gratuito) e identificar gargalos técnicos na plataforma.

💼 O Problema de Negócio

A empresa precisava responder a perguntas estratégicas para direcionar os times de Produto e Marketing:

Qual é o perfil demográfico predominante?

O plano Premium realmente gera mais engajamento?

Existem problemas técnicos em dispositivos específicos afetando a satisfação (Churn)?

Quais as oportunidades para campanhas de Upsell?

🛠️ Estratégia da Solução

O projeto foi desenvolvido em Python, seguindo o pipeline de Análise Exploratória de Dados (EDA):

Limpeza de Dados: Validação e tratamento de tipos com Pandas.

Análise Estatística: Cálculo de medidas de tendência central (Média, Mediana, Moda) e dispersão (Desvio Padrão) para entender a distribuição dos usuários.

Visualização de Dados: Criação de gráficos avançados com Seaborn e Matplotlib para identificar correlações e outliers.

Storytelling: Compilação dos achados em um relatório executivo automatizado.

📊 Principais Insights

Engajamento Premium: Usuários Premium passam significativamente mais tempo na plataforma e pulam menos músicas, validando a hipótese de que a experiência sem anúncios aumenta a retenção.

Oportunidade de Upsell: Usuários Gratuitos têm uma alta taxa de "pulos" de música. Recomendou-se uma campanha de marketing focada na dor da interrupção ("Pare de Pular, Comece a Curtir").

Alerta Técnico: Foi identificado um dispositivo específico com avaliação média crítica (muito abaixo da média global), sugerindo bugs de versão ou problemas de UX que precisam de correção imediata pela engenharia.

🚀 Como Executar

Clone este repositório.

Instale as dependências:

pip install pandas seaborn matplotlib scipy


Execute o notebook analise_streaming_final.py (ou abra no Jupyter/VS Code).

Projeto desenvolvido para portfólio de Ciência de Dados.
