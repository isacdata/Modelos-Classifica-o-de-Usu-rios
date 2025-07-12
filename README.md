# 🤖 Modelos de Classificação de Usuários

Este projeto compara diferentes algoritmos de classificação supervisionada para prever a categoria de usuários com base em variáveis comportamentais e demográficas. A modelagem foi feita com foco em avaliação estatística, explicabilidade e otimização por GridSearchCV.

---

## 📁 Dados

- Arquivo: `ml_datasource.csv`
- Variáveis incluem características numéricas e categóricas de usuários
- Dados tratados via encoding ordinal e separação em treino/teste

---

## 🎯 Objetivo

Prever corretamente a **categoria de um usuário** com base em um conjunto de atributos, e comparar a performance de diferentes modelos supervisionados.

---

## 📊 Modelos Avaliados

- Regressão Logística
- Random Forest Classifier
- XGBoost Classifier

---

## 🧪 Técnicas Utilizadas

- Visualização com seaborn (`sns.pairplot`, histogramas, matriz de correlação)
- `train_test_split` para validação
- `OrdinalEncoder` para variáveis categóricas
- `Variance Inflation Factor (VIF)` para avaliar multicolinearidade
- Avaliação com Acurácia, ROC AUC e Matriz de Confusão
- `GridSearchCV` para tuning dos modelos

---

## 📈 Métricas de Avaliação

- Acurácia
- Matriz de Confusão
- AUC Score

---

## 📂 Estrutura do Repositório

```
modelos-classificacao-usuarios/
├── Machine Learning Project.ipynb
├── ml_datasource.csv  (ou instrução de acesso)
├── requirements.txt
└── README.md
```

---

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/modelos-classificacao-usuarios.git
cd modelos-classificacao-usuarios
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o notebook em seu ambiente Jupyter

---

## 👤 Autor

Projeto desenvolvido por **Isac Vieira**, com foco em aprendizado supervisionado e análise interpretável de classificadores.

---

## 📄 Licença

Código disponível para fins educacionais e demonstração técnica.
