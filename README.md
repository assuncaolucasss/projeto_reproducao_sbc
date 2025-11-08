# projeto_reproducao_sbc
Projeto de Reprodução Científica: Análise Psicométrica de Rubrica de ML

Artigo Original

Título: Análise do desempenho de aprendizagem de Machine Learning na Educação Básica aplicando a Teoria de Resposta ao Item
Autores: Marcelo Fernando Rauber et al.
Evento: EduComp 2023 (Anais do Simpósio Brasileiro de Educação em Computação)
Problema Central: Avaliação da confiabilidade e validade de uma rubrica de avaliação de ML na Educação Básica.

Objetivo da Reprodução

Reproduzir a análise psicométrica (Teoria Clássica do Teste - TCT e Teoria de Resposta ao Item - TRI) realizada pelos autores, utilizando os dados agregados publicados no artigo (Tabela 3), a fim de validar os indicadores de confiabilidade (Coeficiente Ômega) e dimensionalidade/calibração da rubrica.

Estrutura do Repositório

projeto_reproducao_sbc/
├── analise_e_plano.md      # Análise Detalhada (Etapa 2 e 3)
├── README.md               # Este arquivo
├── requirements.txt        # Dependências do Python
├── data/
│   └── dados_simulados.csv # Dados brutos simulados (43 linhas)
└── src/
    └── analise_tct.py      # Script Python para a reprodução da TCT e análise de itens


Instruções de Configuração e Execução

1. Configurar o Ambiente

É fortemente recomendado o uso de um ambiente virtual (venv).

# 1. Criar o ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate  # No Linux/macOS
# .\venv\Scripts\activate  # No Windows

# 2. Instalar as dependências
pip install -r requirements.txt


2. Executar a Reprodução

O script principal irá gerar o dataset simulado (dados_simulados.csv) e, em seguida, executar as análises da TCT.

# Executar o script de análise
python src/analise_tct.py


3. Resultados Esperados

O script exibirá no console:

A Tabela de Contingência dos 7 itens finais.

Métricas da Teoria Clássica do Teste (Média, Desvio Padrão).

O Coeficiente Ômega Global (se a biblioteca for instalada e configurada).

Um resumo da análise dos itens, comparando os resultados com a Tabela 5 do artigo.

A dificuldade na obtenção dos mesmos valores de a e b da TRI será discutida no Relatório Técnico devido à ausência dos dados brutos e à complexidade das ferramentas necessárias.
