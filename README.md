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

### 2. Tipos de Destinação dos Resíduos

### 3. Destinação por Região

### 4. Planos Municipais de Gestão

### 5. Tipos de Resíduos Mais Declarados

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
