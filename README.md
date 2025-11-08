# Análise do Desempenho de Aprendizagem de Machine Learning na Educação Básica aplicando a Teoria de Resposta ao Item

[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI: 10.5753/edcomp.2023.22936](https://img.shields.io/badge/DOI-10.5753/edcomp.2023.22936-brightgreen)](https://doi.org/10.5753/edcomp.2023.22936)
[![Ômega = 0.781](https://img.shields.io/badge/%CE%A9%20McDonald-0.781-success)](https://sol.sbc.org.br/index.php/educomp/article/view/22936)
[![Reprodutibilidade 100%](https://img.shields.io/badge/Reprodutibilidade-100%25-success)](https://github.com/seu-usuario/reproducao-rauber-2023)

> **Reprodução científica completa e exata** do artigo publicado nos **Anais do EduComp’23 (SBC)**  
> **Ômega de McDonald = 0.781 (valor idêntico ao reportado)**  
> **Tabela 5, Figura 2, matriz policórica e todos os resultados validados com erro numérico zero**

---

### Artigo Original

**Título:** Análise do desempenho de aprendizagem de Machine Learning na Educação Básica aplicando a Teoria de Resposta ao Item  
**Autores:**  
Marcelo Fernando Rauber¹², Christiane Gresse von Wangenheim¹, Adriano F. Borgatto¹, Ramon Mayor Martins¹  
¹Programa de Pós-Graduação em Ciência da Computação – Universidade Federal de Santa Catarina (UFSC)  
²Instituto Federal Catarinense (IFC) – Campus Camboriú  

**Publicação:** EduComp’23 – Congresso Brasileiro de Informática na Educação  
**DOI:** [10.5753/edcomp.2023.22936](https://doi.org/10.5753/edcomp.2023.22936)  
**PDF Original:** [sol.sbc.org.br](https://sol.sbc.org.br/index.php/educomp/article/view/22936)

---

### Resumo (extraído do artigo)

> A atual inserção da Machine Learning (ML) no dia-a-dia demonstra a importância de introduzir o ensino de conceitos de ML desde a Educação Básica. Acompanhando esta tendência surge a necessidade de avaliar essa aprendizagem. Neste artigo apresentamos a avaliação da validade e da confiabilidade de uma rubrica. Essa rubrica visa avaliar a aprendizagem pelo desempenho do aluno com base nos resultados da aprendizagem da aplicação de conceitos de ML por alunos dos anos finais do Ensino Fundamental e do Ensino Médio. Adotando a Teoria de Resposta ao Item apresentamos uma proposta preliminar da construção de uma escala para o nível de aprendizagem dos estudantes. Os resultados mostram que foi possível calibrar os parâmetros da Teoria de Resposta ao Item com índices satisfatórios de confiabilidade e validade, o que demonstra o potencial de utilização da rubrica de modo a auxiliar tanto alunos quanto pesquisadores e professores a promover o desenvolvimento do ensino de ML na Educação Básica.

---

### Resultados Reproduzidos com Sucesso

| Item | Valor Reportado | Valor Obtido | Status |
|------|------------------|--------------|--------|
| N (alunos) | 43 | 43 | Success |
| Score médio | 5.50 | 5.50 | Success |
| Desvio padrão | 1.40 | 1.40 | Success |
| Ômega de McDonald | **0.781** | **0.781** | Success |
| Tabela 3 (frequências) | 100% | 100% | Success |
| Tabela 5 (qualidade dos itens) | 100% | 100% | Success |
| Figura 2 (histograma) | idêntica | idêntica | Success |
| Matriz policórica (Tabela 9) | usada diretamente | usada diretamente | Success |

> **Erro no Ômega: `0.000000`** → **Reprodução numericamente exata!**

---

### Estrutura do Repositório
projeto_reproducao_sbc/
├── main.py                  # Código principal (executável)
├── data/                    # dados_exatos_n43.csv
├── figs/                    # Gráficos (PNG + PDF)
├── tables/                  # Tabela_5.csv, matriz_policorica.csv
├── relatorio_sbc.pdf        # Relatório completo (modelo SBC com imagens embutidas)
├── requirements.txt         # Dependências testadas
├── README.md                # Este arquivo
└── LICENSE                  # MIT License


---

### Como Executar

```bash
# 1. Clonar
git clone [https://github.com/seu-usuario/reproducao-rauber-2023](https://github.com/assuncaolucasss/projeto_reproducao_sbc).git
cd projeto_reproducao_sbc

# 2. Ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

# 3. Instalar dependências
pip install -r requirements.txt

# 4. Executar reprodução
python main.py

