[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Data Science - Sarah F. Rezende

#  **Projeto** - Análise de Departamento de Recursos Humanos

[PROJETO (COLAB)](https://github.com/SarahFeanor/Covid_19_EDA_Project/blob/main/Analise_Covid_19.ipynb)

Bem-vindos(as). Este repositório foi criado com o propósito de estudo. Vale ressaltar que todos os dados são exclusivamente para fins de demonstração, garantindo total privacidade e conformidade ética.

<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1202442953998733392/global_economic_barometer_covid19.jpg?ex=65cd7944&is=65bb0444&hm=87c25a6d548f80b55a74198ca834de715b89ef73007e1eb5fc35c5e68a2d43f0&" alt="capa" width="500" height="300">
  </a>
</p> <p align="center"> <sup> Covid-19 — Foto de PortalFGV</sup> </p>

# **Análise de Departamento de Recursos Humanos** 💼📊

É amplamente reconhecido que a retenção de talentos e o enfrentamento de demissões inesperadas são desafios enfrentados por empresas de todos os setores. A redistribuição de tarefas de um funcionário que se desliga pode acarretar em atrasos e/ou queda na qualidade do serviço, resultando em contratempos que repercutem no produto final ou no relacionamento com o cliente. Diante disso, surge a possibilidade de utilizar dados para identificar quais colaboradores apresentam maior probabilidade de deixar a organização.

# 📍 Objetivo

Este estudo tem como objetivo identificar potenciais elementos que influenciam os pedidos de demissão dos colaboradores. Ele visa também aplicar modelos de machine learning ao conjunto de dados para prever quais funcionários estão mais propensos a sair da empresa e avaliar a eficácia desses modelos com base em métricas como precisão, recall e pontuação.

### Etapas:

1. Introdução ao Problema
2. Dicionário de Variáveis
3. Importação de Bibliotecas e Conjunto de Dados
4. Visualização dos Dados
5. Pré-processamento e Divisão em Conjuntos de Treinamento/Teste
6. Aplicação de Modelos de Aprendizado de Máquina
7. Considerações Finais

# 1. **Introdução ao Problema**

De acordo com um relatório do [G1](https://https//g1.globo.com/trabalho-e-carreira/noticia/2022/06/30/pais-bate-recorde-de-pedidos-de-demissao-em-12-meses-mostra-levantamento.ghtml), entre junho de **2021** e maio de **2022**, o Brasil testemunhou aproximadamente **6,175** milhões de pedidos de demissão, equivalendo a cerca de **33%** de todos os desligamentos no país.

Um estudo intitulado ["There Are Significant Business Costs to Replacing Employees"](https://www.americanprogress.org/wp-content/uploads/2015/08/CostofTurnover0815.pdf) ressalta que os custos decorrentes de uma demissão, independentemente da sua natureza, podem representar, em média, **16%** do salário anual do colaborador. Para cargos que demandam conhecimentos especializados e anos de experiência, esse custo pode chegar a até **213%** do salário anual. O estudo também conclui que os principais fatores para a retenção de funcionários incluem benefícios familiares que proporcionam flexibilidade para lidar com questões familiares e uma ambiente de trabalho que oferece adaptabilidade.

Conclusão

A partir dos métodos de avaliação utilizados foi possível identificar fatores significativos e grupos de funcionários que possuem uma maior propensão a sair da empresa.

**Os principais fatores que foram identificados foram:**

* Idade
* Cargo
* Anos de trabalho na empresa
* Mesmo gerente
* Hora extra
* Distância de casa ao trabalho
* Número de empresas que o funcionário já trabalhou

**Os grupos de funcionários que possuem uma maior propensão a sair da empresa são:**

* Funcionários mais jovens
* Funcionários que ocupam cargos mais baixos
* Funcionários que trabalham na empresa há menos tempo
* Funcionários que trabalham com o mesmo gerente há mais tempo
* Funcionários que trabalham mais horas extras
* Funcionários que moram longe do trabalho
* Funcionários que já trabalharam em várias empresas

Com base nos métodos de avaliação utilizados, os modelos com melhor resultado foram a regressão logística e o SVM. No entanto, o SVM foi ligeiramente superior tanto para classificar quem vai ficar na empresa como quem pretende sair da empresa.

Os resultados deste estudo podem ser usados para ajudar as empresas a identificar os funcionários que estão em maior risco de sair da empresa. As empresas podem então tomar medidas para reduzir esse risco, como oferecendo salários mais altos, benefícios melhores, oportunidades de crescimento profissional e um ambiente de trabalho mais agradável.

Este projeto representa um passo em direção ao entendimento e solução dos desafios propostos, evidenciando o potencial da análise de dados e da aprendizagem ao longo deste processo.


Além disso, a substituição de funcionários acarreta não apenas em custos diretos relacionados ao processo de contratação, mas também na perda de produtividade durante o período de adaptação do novo colaborador. Nesse contexto, este estudo tem como objetivo identificar indivíduos com maior probabilidade de deixar a empresa, possibilitando a adoção de medidas que incentivem esses funcionários a optarem por permanecer em seus cargos.
