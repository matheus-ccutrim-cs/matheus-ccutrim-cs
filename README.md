<h1 align="center"> Hi👋, I'm Matheus Cutrim </h1>

<p align="center">
  <b>Computer Science Student at FIAP</b><br>
  Dados · Machine Learning · Python · Java · SQL
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matheus-cutrim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:matheusccutrim2@gmail.com"><img src="https://img.shields.io/badge/matheusccutrim2@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://github.com/matheus-ccutrim-cs"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## 🧑‍💻 Sobre mim

Sou estudante de **Ciência da Computação na FIAP** e gosto de transformar dados em respostas para problemas reais. Meus projetos se dão pela minha evolução em estudos acadêmicos e possoais. E dentro deles, atualmente destaco projetos reais utilizando **Machine Learning** (classificação, regressão e seleção de atributos), **análise de dados com Python e SQL**, automação de relatórios e **programação orientada a objetos em Java**.

- 🔭 Foco atual: Ciência de Dados, Machine Learning e Desenvolvimento de Software
- 🌱 Aprendendo: modelos mais robustos, validação de modelos e boas práticas de engenharia de software
- 🎯 Buscando: oportunidades de **estágio** em Dados, Desenvolvimento e com foco em IA Generativa
- 📫 Pode me contatar pelo LinkedIn ou e-mail acima

---

## 🛠️ Tecnologias e ferramentas

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Dados e Machine Learning**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)

---

## 🚀 Projetos em destaque

### 🧪 [Alura Care — Classificação de Exames com ML](https://github.com/matheus-ccutrim-cs/Alura-care)
Classificação de diagnósticos a partir de dados de exames, investigando quais variáveis realmente importam para o modelo.
- **Random Forest** comparado a um baseline (`DummyClassifier`), com ~**92,4%** de acurácia
- Seleção de atributos com **SelectKBest (chi²)**, **RFE** e **RFECV** (validação cruzada 5-fold, ~**93%** de acurácia)
- Análise de correlação, padronização e redução de dimensionalidade com **PCA** e **t-SNE**

`Python` `Pandas` `scikit-learn` `Seaborn` `Jupyter`

### ⚡ [Previsão do Consumo Energético de uma Nave Espacial](https://github.com/matheus-ccutrim-cs/previsao-consumo-energetico)
Modelo de **regressão supervisionada** para prever o consumo de energia (kWh) de uma nave em missão fictícia — *Global Solution, Modelagem Linear para Aprendizado de Máquina*.
- Fluxo completo: geração de dados → EDA → pré-processamento → treino → avaliação → previsão
- **Regressão Linear** com R² de **0,93** (MAE 12,40 kWh · RMSE 15,68 kWh)
- Interpretação dos coeficientes como apoio à decisão operacional

`Python` `NumPy` `Pandas` `scikit-learn` `Matplotlib`

### 🛰️ [Orion-X — Sistema de Monitoramento de Missão Espacial](https://github.com/matheus-ccutrim-cs/orion-X)
Sistema em Python que processa dados de sensores (temperatura, energia, oxigênio, radiação, comunicação) e gera um relatório automático — *Global Solution, Python*.
- Classificação automática de risco (**Normal / Atenção / Crítico**) e geração de alertas
- Cálculo de **índice de estabilidade** ponderado por registro
- Consumo da **API Open-Meteo** com tratamento de erros e exportação para **Excel**

`Python` `Pandas` `Requests` `OpenPyXL` `JSON`

### 📉 [Papel & Ponto — Análise de Risco de Churn com SQL](https://github.com/matheus-ccutrim-cs/Papel-Ponto)
Análise de uma base de **10.000 vendas** para identificar clientes inativos e apoiar ações de reativação do CRM.
- Identificou **225 de 800 clientes (28,13%)** em risco de churn
- VIEW por cliente, agregações, segmentação com `CASE WHEN` e tratamento de datas
- Recomendações de negócio e documentação clara de premissas e limitações

`SQL` `SQLite` `CSV`

### 🚗 [FiapRide — Programação Orientada a Objetos em Java](https://github.com/matheus-ccutrim-cs/poo-fiapride-matheus-cutrim)
Sistema de mobilidade com passageiros, saldo, viagens e diferentes veículos, além de um módulo de biblioteca com empréstimos e devoluções.
- Encapsulamento, herança, **polimorfismo**, classes abstratas e **interfaces** (ex.: `Recarregavel` para carros elétricos)
- Diagramas de classes e reflexões sobre as decisões de modelagem

`Java` `POO` `UML`

### 🎲 [Jogo do Número Secreto](https://github.com/matheus-ccutrim-cs/numero-secreto-)
Jogo web interativo com sorteio sem repetição, dicas de maior/menor e narração por voz.

`JavaScript` `HTML` `CSS`

---

## 📊 Estatísticas
<p align="center"> <img height="165" src="./profile/stats.svg" alt="Estatísticas do GitHub"> <img height="165" src="./profile/top-langs.svg" alt="Linguagens mais usadas"> </p>
<p align="center"> <i>"Dados não falam sozinhos — é preciso fazer as perguntas certas."</i><br> ⭐ Obrigado pela visita! </p>


