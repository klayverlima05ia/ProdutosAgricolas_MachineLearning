# 🌾 Fase 3 – Capítulo 10 – Produtos Agrícolas (FIAP)

Klayver Lima  
Inteligência Artificial  

---

## 🎯 Objetivo

Analisar uma base de dados com informações de solo e clima e, a partir dela:

1. Fazer uma **análise exploratória e descritiva** dos dados.  
2. Encontrar o **perfil ideal** de solo/clima para plantações.  
3. Comparar diferentes culturas (ex: arroz, milho e café).  
4. Desenvolver **5 modelos preditivos** que indiquem qual cultura é mais adequada às condições apresentadas.  
5. Avaliar e comparar a performance de cada modelo.

---

## 🧠 Tecnologias utilizadas

- Python 3 (Google Colab)
- Bibliotecas:
  - `pandas`, `numpy`, `matplotlib`
  - `scikit-learn` (`LogisticRegression`, `KNN`, `DecisionTree`, `RandomForest`, `SVC`)

---

## 📊 Principais gráficos gerados

- Distribuição de culturas (bar plot)  
- Histogramas das variáveis numéricas  
- Matriz de correlação  
- Boxplots de temperatura e precipitação por cultura  
- Scatter de precipitação x umidade  

---

## 🌱 Perfil Ideal Global

| Variável | Média |
|-----------|--------|
| Nitrogênio (N) | 50.6 |
| Fósforo (P) | 53.4 |
| Potássio (K) | 48.1 |
| Temperatura (°C) | 25.6 |
| Umidade (%) | 71.5 |
| pH | 6.47 |
| Precipitação (mm) | 103.5 |

---

## 🌾 Comparativo entre culturas

| Cultura | Características predominantes |
|----------|------------------------------|
| **Rice (arroz)** | Alta umidade e muita chuva |
| **Maize (milho)** | Temperatura amena e chuva moderada |
| **Coffee (café)** | Alto nitrogênio e boa precipitação |

---

## 🤖 Modelos preditivos testados

| Modelo | Acurácia |
|--------|-----------|
| Random Forest | **99,4%** |
| SVC (SVM) | 98,9% |
| KNN | 97,8% |
| Decision Tree | 97,8% |
| Logistic Regression | 97,3% |

✅ **Random Forest** obteve o melhor desempenho.

---

## 🏁 Conclusão

O trabalho cumpre todos os requisitos:
- Análise exploratória e descritiva com gráficos;
- Perfil ideal de solo/clima;
- Comparação entre culturas;
- 5 modelos preditivos e avaliação de performance;
- Conclusão interpretativa dos resultados.

Este notebook demonstra uma aplicação completa de **Machine Learning em Agricultura Inteligente**.
