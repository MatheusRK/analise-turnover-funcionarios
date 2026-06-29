# Análise de Turnover de Funcionários


## Sobre o Projeto

Este projeto tem como objetivo investigar os fatores associados ao turnover de funcionários por meio da análise de dados do departamento de Recursos Humanos.

Foram analisados indicadores relacionados a desligamentos, cargos, departamentos, remuneração, tempo de empresa e perfil dos colaboradores, buscando identificar padrões de rotatividade e gerar insights que possam apoiar estratégias de retenção de talentos.


## Base de Dados

Foi utilizado o conjunto de dados **IBM HR Analytics Employee Attrition & Performance**, disponibilizado na plataforma **Kaggle**. A base é amplamente utilizada para estudos de People Analytics, servindo como referência para o desenvolvimento de habilidades analíticas em cenários corporativos.

A base contém informações de 1.470 colaboradores e 35 variáveis relacionadas a aspectos demográficos, profissionais, financeiros e comportamentais dos funcionários.

Antes do início das análises, foi realizada uma etapa de validação da qualidade dos dados, contemplando:

* Verificação de valores nulos
* Identificação de registros duplicados
* Validação de tipos de dados
* Análise da consistência das categorias
* Conferência de possíveis valores discrepantes

Os resultados indicaram uma base íntegra e adequada para análises exploratórias e construção de indicadores de Recursos Humanos.


## Qualidade dos Dados

Após a etapa de validação, foram identificados:

* 1.470 registros
* 35 variáveis
* 0 valores nulos
* 0 registros duplicados
* Tipos de dados consistentes com o contexto de negócio

Essas verificações garantiram uma base adequada para análises exploratórias e construção de indicadores.


## Perguntas de Negócio

O projeto busca responder às seguintes questões:

1. Qual é a taxa geral de turnover da empresa?
2. Quais departamentos apresentam maior rotatividade?
3. Quais cargos possuem maior percentual de desligamentos?
4. Existe relação entre remuneração e turnover?
5. O tempo de empresa influencia a decisão de desligamento?
6. Quais perfis de colaboradores apresentam maior risco de saída?


## Stack Utilizada

* Microsoft Excel para inspeção inicial e validação da qualidade dos dados
* MySQL Workbench para exploração, tratamento e análise dos dados
* Power BI para construção do dashboard e visualização dos insights
* GitHub para documentação, versionamento e compartilhamento do projeto


## Estrutura do Projeto

```text
data/
sql/
dashboard/
imagens/
README.md
```


## Metodologia de Análise

A análise foi conduzida de forma investigativa, partindo da taxa geral de turnover da empresa e aprofundando progressivamente a investigação para identificar grupos com maior risco de desligamento.

As etapas da análise foram:

1. Cálculo da taxa geral de turnover da empresa
2. Identificação dos departamentos com maior rotatividade
3. Análise da relação entre tempo de empresa e desligamentos
4. Investigação da influência da faixa etária no turnover
5. Comparação da taxa de turnover dos funcionários de 18 a 24 anos com a média geral da empresa
6. Identificação dos departamentos mais impactados pelo turnover entre colaboradores jovens
7. Análise dos cargos ocupados pelos funcionários jovens do departamento de Vendas
8. Comparação entre remuneração e turnover nos cargos analisados

Essa abordagem permitiu identificar padrões de desligamento e possíveis fatores associados à retenção de talentos.


## Principais Insights

* A taxa geral de turnover da empresa é de **16,12%**
* O departamento de Vendas (Sales) apresentou a maior taxa de turnover entre os setores da empresa, **20,63%**
* Funcionários com **até 5 anos** de empresa registraram a maior taxa de desligamento, **20,88%**
* Colaboradores **entre 18 e 24 anos** apresentaram turnover de **39,18%**, valor **23,06** pontos percentuais **acima da média geral** da empresa
* Entre os funcionários de 18 a 24 anos, o departamento de Vendas (Sales) registrou turnover de **51,85%**
* O cargo de Representante de Vendas (Sales Representative) apresentou simultaneamente a **maior taxa de turnover** (**56,52%**) e a **menor remuneração média** (**R$ 2.319,65**) entre os cargos analisados no departamento de Vendas (Sales)
* Os resultados sugerem uma possível associação entre **remuneração**, **faixa etária**, **tempo de empresa** e **turnover**


## Dashboard
Em desenvolvimento.


## Conclusões

A análise identificou que o turnover da empresa não ocorre de forma homogênea entre os colaboradores.

Os resultados demonstraram que funcionários mais jovens e com menor tempo de empresa apresentam maior propensão ao desligamento, especialmente no departamento de Sales. Entre os colaboradores de 18 a 24 anos, a taxa de turnover foi significativamente superior à média geral da organização.

Ao aprofundar a investigação no departamento de Vendas, observou-se que o cargo de Sales Representative concentrou simultaneamente a maior rotatividade e a menor remuneração média entre os cargos analisados. Embora os dados não permitam estabelecer relações de causalidade, os resultados sugerem que fatores como estágio de carreira, tempo de empresa e remuneração podem estar associados à retenção de talentos.

Esses achados podem servir como ponto de partida para estratégias de retenção direcionadas aos grupos mais suscetíveis ao desligamento.
