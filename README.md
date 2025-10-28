# VeloLog-Performance-Dashboard
Análise de Performance Logística com Power BI | Projeto VeloLog
Olá a todos!

Tenho o prazer de compartilhar um projeto de Dashboard que desenvolvi utilizando o Power BI, focado na análise de performance de operações logísticas. Este projeto foi concebido para resolver um problema real de negócios: identificar gargalos em entregas e otimizar custos em uma empresa de entregas, a VeloLog.

🚀 O Problema de Negócio
A VeloLog, uma empresa de logística de médio porte, enfrentava queixas crescentes de atrasos nas entregas. O desafio era entender a raiz do problema:

Quais regiões estavam com pior desempenho?

Quais transportadoras parceiras eram as mais problemáticas?

Existem tipos de frete específicos com mais atrasos?

Como os custos de frete e combustível impactam a performance?

O objetivo principal era criar um painel de controle intuitivo que permitisse ao Diretor de Operações identificar rapidamente onde intervir.

📊 A Base de Dados
Para simular o cenário, utilizei uma base de dados fictícia no Excel, contendo informações essenciais sobre cada frete, como: ID_Frete, Data_Pedido, Data_Prevista, Data_Entrega, Status_Entrega, Regiao_Destino, Transportadora, Tipo_Frete, Custo_Frete, Custo_Combustivel e KM_Rodado.

Esta base foi a espinha dorsal para a criação dos nossos indicadores e visuais no Power BI.

✨ O Dashboard no Power BI
Com os dados carregados e tratados, criei um Dashboard interativo, focado em clareza e actionable insights. A seguir, apresento os principais visuais desenvolvidos:

1. Visão Geral do Dashboard
Aqui está uma visão completa do dashboard que construí. Ele foi projetado para ser intuitivo e permitir uma navegação rápida pelas informações mais críticas.

![Dashboard VeloLog](https://github.com/user-attachments/assets/1bccd2eb-24d6-41db-abfb-a676cbfc1aa0)




2. KPI Principal: Taxa de Atraso (SLA)
O primeiro e mais crítico KPI é a Taxa de Atraso. Utilizei um visual de "Medidor" para mostrar claramente onde estamos em relação à nossa meta de 5%.

<img width="220" height="161" alt="image" src="https://github.com/user-attachments/assets/b79cc897-aced-4d29-95b2-d23e197b5a2f" />




3. Atrasos por Região
Para identificar geograficamente os problemas, utilizei um Gráfico de Barras 100% Empilhadas, mostrando a proporção de cada status de entrega por região. Isso revela rapidamente as regiões com maior incidência de atrasos.





(Insira AQUI a print/screenshot SOMENTE do Gráfico de Barras 100% Empilhadas de "Atrasos por Região") Insight: Claramente, a região Nordeste se destaca com uma alta proporção de atrasos.

4. Performance da Transportadora
Para entender qual parceiro logístico contribui mais para os atrasos, um Gráfico de Anel (Donut Chart) foi utilizado, filtrado para mostrar apenas fretes atrasados.





(Insira AQUI a print/screenshot SOMENTE do Gráfico de Anel de "Performance da Transportadora") Insight: A TransNorte é a principal responsável pelos atrasos identificados.

5. Atrasos por Tipo de Frete
Este visual, um Gráfico de Barras 100% Empilhadas, compara a proporção de atrasos entre os tipos de frete "Expresso" e "Econômico".





(Insira AQUI a print/screenshot SOMENTE do Gráfico de Barras 100% Empilhadas de "Atrasos por Tipo de Frete") Insight: O frete Econômico mostra uma taxa de atraso proporcionalmente maior, mesmo que o número absoluto seja semelhante ao Expresso, indicando um problema de eficiência.

6. Custo Médio por KM Rodado
Para monitorar a eficiência de custos, criei um KPI que calcula o custo médio por quilômetro rodado, incluindo frete e combustível.





(Insira AQUI a print/screenshot SOMENTE do Cartão (Card) com o "Custo Médio por KM Rodado") Explicação DAX: A medida considera apenas fretes Entregues ou Atrasados para garantir que o cálculo seja baseado em dados completos de KM rodado e custos.

💡 Impacto e Próximos Passos
Este dashboard oferece ao Diretor de Operações da VeloLog a clareza necessária para tomar decisões baseadas em dados. Ele pode agora:

Direcionar esforços para a Região Nordeste.

Abrir diálogo com a Transportadora TransNorte para entender os problemas operacionais.

Reavaliar a logística do Tipo de Frete Econômico.

Monitorar de perto a eficiência de custos por KM.

Este projeto demonstra minha capacidade de transformar dados brutos em insights acionáveis usando Power BI e DAX.

Agradecimento
Obrigado por conferir este projeto! Estou aberto a feedbacks e discussões sobre análise de dados e Power BI.
