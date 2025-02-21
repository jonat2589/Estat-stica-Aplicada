# 📊 Teste Z: Comparação de Estratégias de Ensino  

Este projeto aplica um **teste estatístico Z** para verificar se há uma diferença significativa entre as médias de notas de alunos submetidos a duas estratégias de ensino diferentes.  

## 📌 Objetivo  
Analisar se a Estratégia B resulta em notas **significativamente maiores** do que a Estratégia A.  

## 🛠 Tecnologias Utilizadas  
- Python  
- NumPy  
- SciPy  
- Matplotlib  

## 📈 Metodologia  
1. Geramos amostras aleatórias de notas para as duas estratégias de ensino.  
2. Calculamos as **médias e variâncias** das amostras.  
3. Realizamos um **teste Z** para verificar a significância estatística.  
4. Plotamos a **distribuição normal padrão** destacando a região crítica do teste.  

## 🔍 Resultados  
- Estatística Z: `1.50`  
- p-valor: `0.06`  
- Como `p > 0.05`, **não rejeitamos H0**. Isso indica que **não há uma diferença estatisticamente significativa** entre as médias das Estratégias A e B.  

## 📊 Gráfico da Distribuição Z  
O gráfico gerado mostra a distribuição normal padrão, a região crítica (vermelha) e a posição do valor de **Z calculado**.  

![Gráfico Z](https://github.com/jonat2589/Estat-stica-Aplicada/blob/main/download.png)

## 🚀 Como Executar  
Clone o repositório e rode o código:  

```bash
python teste_z.py
