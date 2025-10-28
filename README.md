# VeloLog-Performance-Dashboard

![Status do Projeto: Concluído](https://img.shields.io/badge/status-concluído-brightgreen)

## 📝 Análise de Performance Logística com Power BI | Projeto VeloLog

Olá a todos!

Tenho o prazer de compartilhar um projeto de Dashboard que desenvolvi utilizando o Power BI, focado na análise de performance de operações logísticas. Este projeto foi concebido para resolver um problema real de negócios: identificar gargalos em entregas e otimizar custos em uma empresa de entregas, a VeloLog.

## 🚀 O Problema de Negócio:
A VeloLog, uma empresa de logística de médio porte, enfrentava queixas crescentes de atrasos nas entregas. O desafio era entender a raiz do problema:

Quais regiões estavam com pior desempenho?

Quais transportadoras parceiras eram as mais problemáticas?

Existem tipos de frete específicos com mais atrasos?

Como os custos de frete e combustível impactam a performance?

O objetivo principal era criar um painel de controle intuitivo que permitisse ao Diretor de Operações identificar rapidamente onde intervir.

## 📊 A Base de Dados:
Para simular o cenário, utilizei uma base de dados fictícia no Excel, contendo informações essenciais sobre cada frete, como: ID_Frete, Data_Pedido, Data_Prevista, Data_Entrega, Status_Entrega, Regiao_Destino, Transportadora, Tipo_Frete, Custo_Frete, Custo_Combustivel e KM_Rodado.

Esta base foi a espinha dorsal para a criação dos nossos indicadores e visuais no Power BI.

## ✨ O Dashboard no Power BI:
Com os dados carregados e tratados, criei um Dashboard interativo, focado em clareza e actionable insights. A seguir, apresento os principais visuais desenvolvidos:

**1. Visão Geral do Dashboard**
Aqui está uma visão completa do dashboard que construí. Ele foi projetado para ser intuitivo e permitir uma navegação rápida pelas informações mais críticas.

![Dashboard VeloLog](https://github.com/user-attachments/assets/1bccd2eb-24d6-41db-abfb-a676cbfc1aa0)

**2. KPI Principal: Taxa de Atraso (SLA)**
O primeiro e mais crítico KPI é a Taxa de Atraso. Utilizei um visual de "Medidor" e um cartão para mostrar claramente onde estamos em relação à nossa meta de 30%. O cartão serve para dar destaque ao número vergonhoso da Taxa de Atraso.

<img width="531" height="214" alt="image" src="https://github.com/user-attachments/assets/3aa63263-b172-4a77-adfa-889743d3b061" />
<br>
<br>

**3. Atrasos por Região**
Para identificar geograficamente os problemas, utilizei um Gráfico de Barras 100% Empilhadas, mostrando a proporção de cada status de entrega por região. Isso revela rapidamente as regiões com maior incidência de atrasos.

<img width="316" height="243" alt="image" src="https://github.com/user-attachments/assets/ff8765f9-95bf-432a-976c-2a112b719492" />
<br>
<br>

**4. Performance da Transportadora**
Para entender qual parceiro logístico contribui mais para os atrasos, um Gráfico de Anel (Donut Chart) foi utilizado, filtrado para mostrar apenas fretes atrasados.

<img width="343" height="257" alt="image" src="https://github.com/user-attachments/assets/6571a6b9-f865-4e9a-8ebf-4c4222d08031" />
<br>
<br>

**5. Atrasos por Tipo de Frete**
Este visual, um Gráfico de Barras 100% Empilhadas, compara a proporção de atrasos entre os tipos de frete "Expresso" e "Econômico".

<img width="373" height="227" alt="image" src="https://github.com/user-attachments/assets/327d8bcb-1961-4235-81dd-cac26ab3f6bc" />
<br>
<br>

**6. Custo Médio por KM Rodado**
Para monitorar a eficiência de custos, criei um KPI que calcula o custo médio por quilômetro rodado, incluindo frete e combustível.

<img width="258" height="180" alt="image" src="https://github.com/user-attachments/assets/c1152408-3486-45d9-8042-70443672a206" />
<br>
<br>

## 📂 Arquivos do Projeto:

Sinta-se à vontade para baixar os arquivos utilizados neste projeto, seja para explorar a base de dados original ou para analisar as medidas DAX, relacionamentos e a estrutura do dashboard no Power BI Desktop.

* **[Base de Dados (Excel)](./Base_VeloLog.xlsx)** - O arquivo `.xlsx` com todos os dados fictícios que serviram de fonte.
* **[Dashboard (Power BI)](./VeloLog-Performance-Dashboard.pbix)** - O arquivo `.pbix` completo. Sinta-se à vontade para abri-lo, explorar os visuais e as fórmulas DAX.


**💡 Impacto e Próximos Passos:**
Este dashboard oferece ao Diretor de Operações da VeloLog a clareza necessária para tomar decisões baseadas em dados. Ele pode agora:

Direcionar esforços para a Região Nordeste.

Abrir diálogo com a Transportadora TransNorte para entender os problemas operacionais.

Reavaliar a logística do Tipo de Frete Econômico.

Monitorar de perto a eficiência de custos por KM.

Este projeto demonstra minha capacidade de transformar dados brutos em insights acionáveis usando Power BI e DAX.

## Agradecimentos:
Obrigado por conferir este projeto! Estou aberto a feedbacks e discussões sobre análise de dados e Power BI.

**👨‍💻 Autor:**

Desenvolvido por Caio Augusto Freitas Geraets.

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caio-geraets/)
