# Random Forest - Breast Cancer Wisconsin Dataset

Projeto desenvolvido para a disciplina de Inteligencia Artificial, com foco em classificação supervisionada utilizando o algoritmo Random Forest em Python.

---

# Objetivo

O projeto realiza a classificação de tumores mamários como:

- Benigno
- Maligno

utilizando o dataset Breast Cancer Wisconsin.

O código executa:

- carregamento da base
- pré-processamento
- separação treino/teste
- treinamento do modelo
- ajuste de hiperparâmetros
- avaliação das métricas
- geração de gráficos
- análise da importância das variáveis

---

# Estrutura Esperada

Todos os arquivos devem estar na mesma pasta:

```text
projeto/
│
├── data.csv
├── random_forest.py
├── README.md
```

---

# Requisitos

- Python 3.10+
- pip
- ambiente virtual (recomendado)

---

# Criação do Ambiente Virtual

## Linux / macOS

```bash
python -m venv venv
```

ou

```bash
python3 -m venv venv
```

---

## Windows

```powershell
python -m venv venv
```

---

# Ativação do Ambiente Virtual

## Linux / macOS

```bash
source venv/bin/activate
```

---

## Windows CMD

```cmd
venv\Scripts\activate
```

---

## Windows PowerShell

```powershell
.\venv\Scripts\Activate.ps1
```

---

# Instalação das Dependências

Instale as bibliotecas necessárias:

```bash
pip install pandas scikit-learn matplotlib numpy
```

---

# Dataset

O arquivo do dataset deve se chamar:

```text
data.csv
```

e deve permanecer na mesma pasta do código.

---

# Execução

Execute o projeto com:

```bash
python random_forest.py
```

ou:

```bash
py random_forest.py
```

---

# Funcionalidades do Código

O sistema realiza automaticamente:

- leitura da base de dados
- remoção de colunas desnecessárias
- conversão da variável alvo
- balanceamento estratificado
- geração de seed aleatória
- treinamento do modelo Random Forest
- ajuste automático de hiperparâmetros
- cálculo das métricas
- geração da matriz de confusão
- análise de importância das variáveis

---

# Métricas Geradas

O código calcula:

- Acurácia
- Precisão
- Revocação (Recall)
- F1-Score
- Matriz de Confusão

---

# Bibliotecas Utilizadas

| Biblioteca | Finalidade |
|---|---|
| pandas | Manipulação da base |
| scikit-learn | Machine Learning |
| matplotlib | Visualização gráfica |
| numpy | Operações numéricas |

---

# Hiperparâmetros Testados

O GridSearchCV realiza busca automática utilizando:

- número de árvores
- profundidade máxima
- divisão mínima de nós
- quantidade mínima de amostras por folha

---

# Reprodutibilidade

O código gera e exibe uma seed aleatória utilizada na execução.

Isso permite reproduzir os resultados posteriormente.

---

# Saídas Geradas

Durante a execução serão exibidos:

- melhores hiperparâmetros
- métricas completas
- matriz de confusão
- relatório de classificação
- gráfico da matriz de confusão
- gráfico das variáveis mais importantes

---

# Observações

- O dataset utilizado é o Breast Cancer Wisconsin Dataset.
- O projeto utiliza classificação supervisionada binária.
- O algoritmo utilizado é Random Forest.

---

# Autor
Filipe Silva da Fonseca e Grupo
---
Projeto acadêmico desenvolvido para fins educacionais.
