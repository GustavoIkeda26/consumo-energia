# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-black?logo=github)
![Energia](https://img.shields.io/badge/Energia-Consumo%20Elétrico-yellow)

## 🎯 Objetivo

A **Calculadora de Consumo de Energia** é um programa desenvolvido em Python que permite estimar o consumo mensal de energia elétrica de um aparelho.

O usuário informa o nome do aparelho, a potência em watts e o tempo médio de uso diário. O sistema calcula o consumo estimado em kWh por mês e também apresenta uma estimativa de custo.

## 🔄 Linguagem utilizada

- Python

## 📐 Fórmula utilizada

O consumo mensal é calculado através da seguinte fórmula:

    consumoMensal = (potencia × horasDia × 30) / 1000

### Onde:

- **potencia** = potência do aparelho em watts (W)
- **horasDia** = tempo médio de uso diário em horas
- **30** = quantidade estimada de dias no mês
- **1000** = conversão de Wh para kWh

## 💰 Cálculo do custo

O programa também realiza uma estimativa do custo mensal considerando o valor fixo de **R$ 0,75 por kWh**.

    custoEstimado = consumoMensal × 0,75

## ▶️ Como executar

1. Certifique-se de ter o Python instalado.
2. Abra o terminal na pasta do projeto.
3. Execute:

    python app.py

Caso o comando acima não funcione, tente:

    py app.py

## 💡 Exemplo de utilização

Para um aparelho com:

- Potência: **100 W**
- Uso diário: **15 horas**

O consumo mensal será:

    (100 × 15 × 30) / 1000 = 45 kWh/mês

E o custo estimado será:

    45 × 0,75 = R$ 33,75/mês

## 📁 Estrutura do projeto

    consumo-energia/
    ├── app.py
    └── README.md

## 📚 Sobre o projeto

Projeto desenvolvido como atividade prática para aplicação dos conceitos de **Python, Git e GitHub**.