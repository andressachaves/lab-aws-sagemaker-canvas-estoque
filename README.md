# 📊 Previsão de Estoque Inteligente com AWS SageMaker Canvas

Projeto de Machine Learning desenvolvido na plataforma AWS SageMaker Canvas para previsão inteligente de estoque, utilizando modelos de ML sem necessidade de código.

## 🎯 Objetivo

Criar um modelo preditivo de estoque utilizando o SageMaker Canvas da AWS, demonstrando como aplicar Machine Learning de forma acessível (no-code/low-code) para resolver problemas reais de gestão de inventário.

## 🛠️ Tecnologias

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker_Canvas-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-No--Code-blue?style=for-the-badge)

## 📋 Pré-requisitos

- Conta ativa na AWS
- Acesso ao SageMaker Canvas
- Dataset de estoque (disponível na pasta `/datasets`)

> 💡 Não tem conta AWS? Crie gratuitamente em [aws.amazon.com](https://aws.amazon.com/free)

## 🚀 Passo a Passo

### 1. Configurar o SageMaker Canvas
```
AWS Console → SageMaker → Canvas → Abrir SageMaker Canvas
```

### 2. Importar os Dados
- Acesse a aba **Datasets**
- Faça upload do arquivo da pasta `/datasets`
- Aguarde o processamento

### 3. Criar o Modelo
- Clique em **New Model**
- Selecione o dataset importado
- Escolha a coluna alvo (quantidade em estoque)
- Clique em **Quick Build**

### 4. Analisar as Previsões
- Avalie as métricas do modelo (RMSE, MAPE)
- Gere previsões para períodos futuros
- Exporte os resultados

## 📁 Estrutura do Projeto

```
lab-aws-sagemaker-canvas-estoque/
├── datasets/         # Dados para treinamento do modelo
└── README.md
```

## 📈 Resultados

O modelo de ML treinado no SageMaker Canvas permite:
- Prever demanda futura de produtos
- Identificar padrões sazonais de consumo
- Otimizar níveis de estoque e reduzir desperdícios

## 🔗 Referências

- [Documentação SageMaker Canvas](https://docs.aws.amazon.com/sagemaker/latest/dg/canvas.html)
- [AWS Free Tier](https://aws.amazon.com/free)

## 👩‍💻 Autora

**Andressa Chaves**  
[![GitHub](https://img.shields.io/badge/GitHub-andressachaves-181717?style=flat&logo=github)](https://github.com/andressachaves)
