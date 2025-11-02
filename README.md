<<<<<<< HEAD
# simbia-data-analysis
=======
Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** sobre o **Diagnóstico da Gestão de Resíduos Sólidos Urbanos** nos municípios brasileiros, com o objetivo de compreender padrões, disparidades regionais e gargalos relacionados à Coleta Seletiva, Destinação dos Resíduos e Planos Municipais de Gestão.

---

## Funcionalidades

- Carregar e explorar dados municipais de resíduos sólidos (fonte: SNIS / MMA);
- Analisar distribuição de coleta seletiva por Unidade Federativa (UF);
- Identificar tipos de destinação de resíduos e proporções por região;
- Avaliar correlação entre planos de gestão e práticas sustentáveis;
- Gerar visualizações interativas e relatórios interpretativos;
- Identificar oportunidades para políticas públicas e soluções tecnológicas.

---

## Análises Principais

A seguir, são apresentadas as principais análises realizadas no projeto.

### 1. Distribuição de Municípios com Coleta Seletiva Implantada por UF
- **Visualização:** Gráfico de barras empilhadas (`Sim` × `Não`) por estado.
- **Insight:** Sudeste e Sul concentram maior adoção da coleta seletiva. Norte e Nordeste apresentam baixa cobertura.

### 2. Tipos de Destinação dos Resíduos
- **Visualização:** Gráfico de pizza com as principais destinações.
- **Insight:** Aterros Sanitários ainda predominam, mas há avanço na compostagem e reciclagem.

### 3. Destinação por Região
- **Visualização:** Gráfico de barras empilhadas normalizadas.
- **Insight:** Sul e Sudeste possuem maior proporção de destinações sustentáveis.

### 4. Planos Municipais de Gestão
- **Visualização:** Barras empilhadas por UF.
- **Insight:** Falta de planejamento estratégico é um gargalo relevante, especialmente no Norte e Nordeste.

### 5. Tipos de Resíduos Mais Declarados
- **Visualização:** Barras horizontais com frequência dos tipos de resíduos.
- **Insight:** Resíduos Domiciliares e Comerciais predominam amplamente.

---

## Conjunto de Dados

A seguir, estão as principais colunas e fontes de dados utilizadas na análise:

- `UF`: Unidade Federativa (estado).
- `Coleta Seletiva`: Indica se há coleta seletiva implantada (`Sim` / `Não`).
- `Destinacao`: Tipo de destinação adotada (e.g., Aterro Sanitário, Reciclagem, Lixão).
- `Plano de Gestao`: Indica se o município possui plano de gestão de resíduos (`Sim` / `Não`).
- `Tipo Resíduo`: Classificação do resíduo declarado (Domiciliar, Comercial, Saúde, etc).

📊 **Fonte:** Diagnóstico do Manejo de Resíduos Sólidos Urbanos – SNIS / Ministério do Meio Ambiente  
📅 **Ano de Referência:** 2023

---

## Estrutura do Repositório

| Arquivo | Descrição |
| :-- | :-- |
| `data-analysis-simbia.ipynb` | Notebook principal contendo a análise exploratória completa. |
| `Municipal-Diagnostico.csv` | Base de dados utilizada (fonte: SNIS / MMA / SINIR). |
| `README.md` | Este arquivo, com a descrição geral do projeto. |

---

## Dependências

Para executar este projeto, você precisará instalar as seguintes bibliotecas e ferramentas:

### Python
- Python 3.11+
- pandas
- matplotlib
- seaborn
- numpy

Instalação:
```bash
pip install pandas matplotlib seaborn numpy
```

### Dados
- Arquivo CSV `Municipal-Diagnostico.csv` (disponibilizado no repositório).

#### Preparar Ambiente
1. Clone o repositório.
2. Certifique-se de que o arquivo `Municipal-Diagnostico.csv` está na mesma pasta do notebook.
3. Abra o notebook `data-analysis-simbia.ipynb` no Jupyter Notebook ou VS Code e execute as células em sequência.

---

## Outras Ferramentas

- Jupyter Notebook
- VS Code
- Git (para versionamento)

---

## Autores

- [@MatheusMakita](https://github.com/MatheusMakita)
>>>>>>> f433e6d (feat: add full data analysis Simbia)
