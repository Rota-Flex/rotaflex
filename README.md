# Análise da Eficiência nos Portos Brasileiros (2023-2024)

Nós, alunos do 4º semestre do curso de Logística da Fatec, desenvolvemos este projeto com o objetivo acadêmico de ampliar nossa capacidade analítica e aprimorar nossas habilidades logísticas, promovendo a prática interdisciplinar. Baseado na metodologia ágil SCRUM, o projeto visa estimular a proatividade, a autonomia, a colaboração e a entrega de resultados, preparando os participantes para desafios reais do mercado.

# Índice
* [Projeto](#projeto-template)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Sprints](#Sprints)
* [Burndown](#Burndown)
* [Backlog do produto](#Backlog-do-produto)

# Projeto (API) 
Nosso parceiro acadêmico solicitou à equipe uma análise detalhada da eficiência operacional do sistema portuário brasileiro no período de 2014 a 2023, com foco no carregamento de granéis. O estudo abrange três frentes principais.
Primeiramente, busca-se compreender a variação da prancha média operacional de carregamento de granéis sólidos (t/h) ao longo dos meses dentro do período analisado, desenvolvendo um modelo preditivo baseado em tendências para avaliar o desempenho passado e projetar cenários futuros.
Em segundo lugar, pretende-se examinar a distribuição estatística dos tempos de operação no berço, identificando padrões e variabilidades que impactam a eficiência do carregamento.
Por fim, o projeto tem como objetivo ranquear os 10 principais terminais de movimentação de granéis, considerando o número de berços disponíveis e a respectiva prancha média operacional, proporcionando uma visão comparativa do desempenho desses terminais e possibilitando a identificação dos mais eficientes.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |Maria Felix|     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/maria-eduarda-rharena-b19a35220?utm) 
| Scrum Master  |Miriele Santos|      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/miriele-santos-7597a01a3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)      |
| Team Member   |Guilherme Caravalho|         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-anthony-853606287?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)         |
|  Team Member  |Noemy Siqueira|         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-vitor-c1/)         |
|  Team Member  |Paulo Sousa|   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/paulo-ribeiro-74b043244?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)    |
|  Team Member  |Marcelo de Oliveira|           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/marcelo-uch%C3%B4as-de-oliveira-b2536a18b/)           |
|  Team Member  |Josiane Araújo|           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/josiane-viana-de-araújo-0859a8195)           |

# Objetivo do Projeto
Este projeto tem como objetivo realizar uma análise aprofundada da eficiência operacional do sistema portuário brasileiro, com ênfase no carregamento de granéis, por meio de abordagens estatísticas e modelagens avançadas. Para isso, busca-se:
* Examinar a variação mensal da prancha média operacional de carregamento, desenvolvendo um modelo preditivo baseado em tendências para projeção de desempenho futuro;
* Avaliar a distribuição estatística dos tempos de operação no berço, identificando padrões e variabilidades que impactam a eficiência do carregamento;
* Elaborar um ranking de eficiência dos 10 principais terminais de movimentação de granéis, considerando fatores operacionais críticos;
* Criar um dashboard interativo para apresentação clara e informativa dos resultados da análise e do ranking, facilitando a tomada de decisão;
*	Utilizar ferramentas como R para estruturar e conduzir a modelagem analítica dos dados;
* Implementar a metodologia DEA (Data Envelopment Analysis) para avaliação comparativa da eficiência dos terminais portuários;
* Desenvolver habilidades técnicas avançadas em análise de dados, modelagem estatística e tecnologias aplicadas à logística portuária.
Com essa abordagem, o projeto busca fornecer insights estratégicos sobre a eficiência do sistema portuário brasileiro, contribuindo para a otimização dos processos logísticos e a melhoria do desempenho operacional dos terminais analisados.

# Conteúdo do Projeto

![Descrição opcional do GIF](https://github.com/Rota-Flex/rotaflex/blob/sprint_3/arquivos/bandicam2025-05-3020-01-10-283-ezgif.com-video-to-gif-converter.gif)


## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
 
![github.jpeg](https://github.com/rotaflex369/rotaflex/blob/e9190044aa8038ef9b4d378c6cfe792a7f5f3d5d/github.jpeg)

# Backlog do produto

## ✅ Sprint 1 – Análise de Cargas & Implementação Inicial  
**Objetivo:** Compreender e visualizar as principais cargas movimentadas nos portos.  
**Ferramentas:** Python + Power BI  
**Fontes:** Dados da ANTAQ  

- [ ] Extração de dados brutos da ANTAQ (CSV/XLS/API);
- [ ] Tratamento e limpeza dos dados com Python (pandas, numpy);
- [ ] Classificação e ranqueamento das cargas por volume (tonelagem) e frequência;
- [ ] Agrupamento por tipo de carga (granel, container, líquidos, etc.);
- [ ] Ranquear portos por estado e localização;
- [ ] Exportação dos dados tratados para Power BI;
- [ ] Criação de visual interativo com as principais cargas movimentadas;
- [ ] Integração inicial Power BI com filtros por tipo de carga e porto;
- [ ] Documentação básica dos scripts utilizados (ex: `rank_portos.py`, `clean_cargas.py`);
- [ ] Criação de vídeo passo a passo para replicabilidade.

---

## ✅ Sprint 2 – Análise de Eficiência e Movimentação Portuária  
**Objetivo:** Avaliar a eficiência operacional dos terminais e o volume de movimentações.  
**Ferramentas:** Python + Power BI  

- [ ] Análise de Eficiência: Comparativo de produtividade entre terminais;
- [ ] Avaliação de Tempos de Operação: Tempos médios de espera, carga e descarga;
- [ ] Análise de Movimentação: Total de operações mensais e principais portos em quantidade transportada;
- [ ] Cálculo de produtividade (toneladas por hora, por berço, por equipamento);
- [ ] Cálculo de tempo médio de operação e espera nos terminais;
- [ ] Visualização com gráficos de barras, mapas e indicadores de desempenho;
- [ ] Filtros por porto, região e tipo de carga;
- [ ] Exportação dos KPIs para Power BI;
- [ ] Implementação das dashboards exigidas pelo cliente;
- [ ] Gravação de vídeo demonstrativo da navegação no dashboard;
- [ ] Ajustes e refinamento conforme feedback;
- [ ] Documentação dos indicadores e métricas utilizadas.


## ✅ Sprint 3 – Análise de Paradas Portuárias  
**Objetivo:** Diagnosticar os principais motivos de paradas portuárias e suas sazonalidades.  
**Ferramentas:** Python + Power BI  

- [ ] Identificação dos Top N motivos de parada (ex: manutenção, clima, fila, etc.);
- [ ] Análise de sazonalidade (correlação com períodos do ano);
- [ ] Extração e tratamento dos dados de paradas;
- [ ] Classificação por tipo e duração da parada;
- [ ] Análise com Python (visualizações com seaborn/matplotlib);
- [ ] Esboço de layout dos visuais no Power BI;
- [ ] Visualização por mês, tipo de parada e terminal;
- [ ] Integração dos dados com painel central;
- [ ] Criação de vídeo explicando os insights;
- [ ] Finalização e revisão dos visuais;
- [ ] Documentação dos scripts utilizados.


## ✅ Sprint 4 – DEA Logístico em R + Integração Final  
**Objetivo:** Avaliar eficiência relativa entre terminais portuários com Análise Envoltória de Dados (DEA).  
**Ferramentas:** R + Power BI  

- [ ] Coleta e estruturação dos dados de entrada e saída para o DEA;
- [ ] Implementação do modelo DEA com R (pacotes `Benchmarking` ou `deaR`);
- [ ] Análise de eficiência dos terminais (portos eficientes vs. ineficientes);
- [ ] Exportação dos resultados em CSV para integração com Power BI;
- [ ] Criação de visual com scores de eficiência e benchmarking;
- [ ] Integração Power BI com script R;
- [ ] Criação de vídeo de apresentação dos resultados;
- [ ] Documentação das premissas, variáveis e interpretação do DEA;
- [ ] Finalização com scripts comentados e organizados para reuso.


# Registro das Sprints

Sprint | Previsão | Status| Histórico|
|------|--------|------|--------|
|01 | 04/04/2025 | a fazer| [MVP](https://) | 
|02|  25/04/2025| a fazer|[MVP](https://) | 
|03| 16/05/2025 | a fazer|[MVP](https://) | 
|04| dd/mm/aaaa |a fazer |[MVP](https://)  | 
|Feira de Soluções|dd/mm/aaaa |a fazer |[MVP](https://) | 
