# Projeto Modular Ciência de Dados: Analise Dados Saúde


Este projeto foi desenvolvido para responder às questões do **desafio modular da MBA em Ciências de Dados da Faculdade XP**. Para garantir um ambiente organizado e eficiente, **todas as análises foram realizadas utilizando a linguagem Python em um notebook Jupyter**, dentro de um **ambiente virtual criado exclusivamente para esta atividade**. Essa abordagem proporciona maior controle sobre dependências, facilitando a reprodução dos resultados.

---


### 📁 Estrutura do Projeto
AnaliseDadosSaude/<br>
  **├── ADSAUDE/**      # Ambiente virtual (ignorado no .gitignore)<br>
  **├── src/**           # Código-fonte do projeto (.py)<br>
  **├── notebooks/**     # Notebooks Jupyter (.ipynb)<br>
  **├── data/**          # Arquivos de dados (Excel, CSV, JSON, etc.)<br>
  **├── .gitignore**     # Arquivo para ignorar o ambiente virtual<br>
  **├── requirements.txt** # Lista de dependências<br>
  **├── README.md**      # Documentação do projeto<br>

---

### 📋Enunciado do Projeto

Você foi contratado como cientista de dados para realizar uma análise
detalhada dos dados de pacientes em um projeto de pesquisa na área da
saúde. Os dados estão organizados em três conjuntos principais:
dados_clinicos, dados_pacientes e dados_estados. Cada conjunto de dados
contém as seguintes informações:

- **dados_clinicos**: Informações dos pacientes, como id_cliente, peso, colesterol e gênero.

- **dados_pacientes**: Detalhes adicionais como id_cliente, idade,classe_trabalho, escolaridade, id_estado, estado_civil, raça, quantidadede filhos e salário.

- **dados_estados**: Dados sobre os estados, como id_estado, sigla, estado,região e país.


#### Importância da Análise de Dados em Saúde
Analisar dados de saúde é essencial para identificar padrões que podem melhorar os cuidados com os pacientes e a saúde pública. Com essa análise, você pode:


1. Identificar fatores de risco para a saúde de diferentes grupos de pessoas.
2. Prever resultados clínicos e ajudar os profissionais de saúde a tomarem decisões mais informadas.
3. Melhorar a distribuição de recursos de saúde, entendendo melhor as necessidades de cada região.
4. Apoiar políticas de saúde, fornecendo dados que ajudem a melhorar o acesso e a qualidade dos cuidados.

#### Benefícios
A análise de dados na saúde pode levar a tratamentos mais eficientes e personalizados, ajudando a melhorar a qualidade de vida das pessoas e a reduzir custos com saúde.

#### Atividades
1. Carregar e explorar o conjunto de dados para obter uma compreensão inicial dos dados.
2. Criar representações gráficas dos gráficos
3. Analisar e corrigir dados
4. Visualizar os clusters e analisar os padrões identificados para fornecer insights significativos para a equipe de pesquisa.


### 📝 Instrucoes Iniciais

Avaliem se será necessário realizar tratamento de dados ausentes nos datasets disponibilizados.

Instruções para correção de dados ausentes

- Moda para Variáveis Categóricas Preencher valores ausentes nas colunas categóricas com a moda.

- Mediana para Variáveis Numéricas: Preencher valores ausentes nas colunas numéricas com a mediana.