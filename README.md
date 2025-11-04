# 🧠 Dashboar de manutenção - Fábrica de refrigerante
Desenvolvimento de um Dashboard de indicadores de manutenção de uma industria de bebidas para consolidar os principais indicadores e facilitar a extração de insights valiosos e gerar decisões mais estratégicas baseadas nos dados do sistema para alavancar resultados.

# 🧩 Problema
Ao ingressar no time de planejamento de manutenção de uma industria de refrigerante identifiquei uma gama de oportunidades. Entre elas a falta de controle de indicadores do fluxo de atividades da manutenção. A equipe de planejamento centralizava seus esforço basicamente em compra de peças e atuações em manutenções corretivas e emergenciais fora do planejamento. Portanto, a construção de um novo Dashboard de indicadores seria uma maneira eficiente de proporcionar uma maior visiblidade das principais lacunas que estariam comprometendo a eficiência da equipe de manutenção.  
Exemplos: grande quantidade de notas de manutenção pendentes no sistema e de idade longa; Falta de cumprimento dos planos de manutenção; alto indice de quebras dos equipamentos; falta de controle de backlog (ativiades pendentes) por área; falta de controle de condições inseguras comprimentendo a segurança dos funcionarios e equipamentos; falta de controle das rotinas preditivas (tipos de atividades mais importantes), falta de planejamento da equipe, etc.

# 🎯 Objetivo
Construção de um novo Dashboard de manutenção que proporcione ao time de planejamento e de execução uma visibilidade gerencial das atividades de manutenção mais importantes, evidenciando pontos com maior oportunidade de atuação, maior criticidade e permitindo ajustes estratégicos no planejamento e programação.

# 📊 Indicadores a serem controlados  
**- Controle de relatos de condições inseguras.**  
Priorizar a tratativa destas anomalias para eliminar o risco de acidentes. Importante destacar estas atividades e focar na sua solução para proporcionar um ambiente mais seguro para todos.  
![Logo CI](img/solar_ci.png?raw=true)   
  
**- Controle de notas de manutenção**  
Gráficos demonstrando numero de notas pendentes por área, por idade média, e por criticidade. 
Importante controlar numero de notas pendentes para acelerar essa etapa  para que as notas virem Ordens de manutenção e sejam tratadas, e não deixar notas antigas esquecidas para não acarretar em quebra do equipamento.  
![Logo CI](img/solar_notas.png?raw=true)  

**- Controle de backlog**  
Gráficos demonstrando evolução da quantidade de backlog (em Horas) por área para acompanhar onde as pendências estão aumentando ou diminuindo; 
Grafico de pizza demonstrando como o backlog está distribuido por especialidade (mecânica, elétrica, automação ou predial);  
Grafico mostrando a especialidade de soldador por área para dar visibilidade da área mais critica nesta especialidade compartilhada.  
Gráfico exibindo numero de Ordens mais antigas por área (acima de 200 dias de idade), etc.
![Logo CI](img/solar_backlog.png?raw=true)   

**- Controle de planos de manutenção**  
Gráficos demonstrando numero de Ordens geradas automaticamente pelo sistema de planos de manutenção. 
Importante controlar e melhorar o indice de cumprimento dos planos visto que são atividades anteriormente idealizadas importantes para manter o nivel de confiabilidade dos equipamentos.  
![Logo CI](img/solar_planos.png?raw=true)  


# 🛠️ Ferramentas e Tecnologias
- Excel avançado com graficos e tabelas dinamicas e macros como com fórmulas avançadas para adequar ao contexto de manutenção;
- Linguagem de programação VBA para otmizar a planilha e automatizar a atualização das bases, extração de dados e lógica das fórmulas avançadas;
- Sistema SAP e Linguagem de Script do sistema SAP

# 🔍 Etapas do Projeto
1 - identificação do problema (alto numero de notas incompletas, dificuldade de tratativas, baixa eficiência na execução;
2 - Análise e comportamento do fenômeno e entendimento do fluxo correto de tratativas de manutenção;
3 - levantamento de requisitos para eliminar o problema;
4 - construção da ferramenta;
5 - Realização de testes e treinamento da equipe;
6 - Implantação e acompanhamento da evolução dos indicadores

# 📈 Resultados Principais
- Evolução de varios indicadores em todas as áreas da planta;
- Saneamento de notas pendentes mais antigas, eliminação de notas ja resolvidas, aceleração no tratamento de notas criticas;
- Saneamento de backlog de Ordens, encerramentos de ordens já expiradas/obsoletas, priorização de ordens mais antigas(maior idade).
- Melhoria no cumprimento de planos de manutenção, melhor no planejamento das atividades semanais.
- Evolução nos indicadores da manutenção
- Melhor eficiência nas etapas do fluxo de manutenção.


# 🧭 Próximos Passos
- Criação de planilha de programação utilizando a base de ordens do backlog para construir uma programação semanal mais eficiente para todas as áreas;  
- Criar plano de ação com as saídas da reunião diária de manutenção com uso do Dashboard;  
- Automatizar Dashboard para importação e atualização das bases extraidas do sistema SAP.  

# 👤 Autor
Alexandro Grigório Ferreira  
📧 alexanndro@gmail.com  
🔗 https://www.linkedin.com/in/alexsidius/   
🔗 https://github.com/Alexsidius  

Este projeto faz parte de minha experiência como Analista de manutenção e estudos práticos para análise e ciência de dados.
