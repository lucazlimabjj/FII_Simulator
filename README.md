# FII_Simulator
# 📈 Simulador de Independência Financeira (Excel Avançado)

> Este repositório contém um **Dashboard de Planejamento Financeiro** desenvolvido no Microsoft Excel. O projeto foi construído com foco na matemática financeira precisa, indo além de simulações básicas para incorporar o impacto da inflação, projeções de renda passiva e metas claras de acumulação.

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Logo">
  <img src="https://img.shields.io/badge/Financial%20Modeling-Advanced-blue?style=for-the-badge" alt="Finance Badge">
</p>

---

## 🎓 Contexto do Projeto

Este projeto foi desenvolvido como aplicação prática dos conhecimentos adquiridos no curso **Santander - Excel com Inteligência Artificial - 2º Semestre**. O objetivo foi criar uma ferramenta funcional que auxiliasse na tomada de decisão de investimentos de longo prazo, focada em Fundos Imobiliários (FIIs) e geração de renda.

## 🚀 Funcionalidades Principais

A planilha foi estruturada para responder às três principais perguntas de um investidor: "Onde vou chegar?", "O que eu ganho com isso?" e "Quanto tempo falta?".

### 1. Projeção de Poder de Compra (Real vs. Nominal)
Diferente de simuladores comuns que mostram apenas o saldo bruto, este projeto implementa a lógica da **Equação de Fisher** para descontar a inflação (IPCA estimado) dos rendimentos.
* **Saldo Acumulado (Nominal):** O valor numérico que aparecerá na corretora.
* **Poder de Compra (Real):** O valor ajustado a preços de hoje, mostrando a verdadeira riqueza acumulada.

### 2. Visualização "Boca de Jacaré" 🐊
Um gráfico comparativo que ilustra visualmente o impacto corrosivo da inflação no longo prazo. Ele demonstra como as curvas de patrimônio Nominal (Azul) e Real (Vermelha) se afastam drasticamente com o passar das décadas.

### 3. Calculadora do Efeito Bola de Neve (Magic Number) ❄️
Uma funcionalidade crucial para investidores de dividendos. Baseado no preço médio de uma cota (ex: Base 10 ou Base 100) e na taxa de rendimento, a planilha calcula:
* O patrimônio exato necessário para que os rendimentos comprem uma nova cota sozinhos.
* O **"Número Mágico"** de cotas a serem acumuladas para atingir esse ponto de inflexão exponencial.

### 4. Estimador de Tempo para Liberdade Financeira ⏳
Utilização de funções financeiras avançadas (`NPER`) para inverter o cálculo: o usuário define uma **Meta de Renda Mensal** (ex: R$ 3.000,00) e o dashboard calcula exatamente quantos anos e meses são necessários para atingir essa meta, considerando os aportes mensais e a taxa de retorno atual.

---

## 📸 Screenshots do Projeto

*(Aqui você vai colocar os prints da sua planilha. Veja o tutorial abaixo de como fazer isso)*

### Visão Geral do Dashboard
![Visão Geral do Dashboard](visao_geral.png)

### Detalhe: Bola de Neve e Calculadora de Tempo
![Detalhe das Calculadoras](detalhe.png)

---

## 🛠️ Tecnologias e Conceitos Utilizados
* **Microsoft Excel:** Fórmulas Avançadas, Formatação Condicional, Gráficos Personalizados.
* **Matemática Financeira:** Valor Futuro (VF), Número de Períodos (NPER), Juros Compostos, Taxa Real vs. Nominal.
* **Data Visualization:** Gráficos limpos para facilitar a leitura de dados complexos.
