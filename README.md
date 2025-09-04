# 📊 Análise de Consumo de Energia Residencial

Este projeto consiste em uma análise exploratória de dados sobre **consumo de energia elétrica em residências**, utilizando a base `individual_household_electric_power_consumption`.  
O objetivo é compreender padrões de consumo, explorar correlações entre variáveis e gerar visualizações que auxiliem na interpretação dos dados.

---

## 🚀 Como executar o projeto

Este projeto foi desenvolvido no **Google Colab**, não sendo necessário configurar ambiente local.  

### Passos:
1. Acesse o Google Colab: [Google Colab](https://colab.research.google.com/).  
2. Faça upload do notebook `individual_household_electric_power_consumption.ipynb`.  
3. O próprio notebook já contém instruções para:  
   - Capturar e carregar o **DataFrame**.  
   - Realizar o pré-processamento dos dados.  
   - Executar a análise exploratória com gráficos e métricas.  

> ⚠️ É necessário importar as bibliotecas listadas no início do notebook (como `pandas`, `matplotlib`, `seaborn`, entre outras). O Colab permite instalação rápida com `!pip install`.

---

## 📂 Estrutura do Projeto

- `individual_household_electric_power_consumption.ipynb` → Notebook principal com toda a análise de dados.  
- Dataset utilizado: disponível para importação direto no notebook.  

---

## 📈 Resultados Esperados

A análise traz:  
- Estatísticas descritivas do consumo.  
- Visualizações de séries temporais.  
- Identificação de picos e padrões de uso de energia.  
- Insights sobre variáveis correlacionadas.

---

## 👩‍💻 Colaboradores

- **Adonay Rodrigues da Rocha** – RM558782  
- **Thamires Ribeiro** – RM558128  
- **Pedro Henrique Martins dos Reis** – RM555306  

---

## 📝 Licença

Este projeto é de caráter **acadêmico**, voltado para estudo e prática de análise de dados.

---

## ❓ Perguntas e Respostas - Orange Data Mining

### 36. Importação e visualização inicial
- **Quantas variáveis e registros aparecem?**  
  9 variáveis, 2.075.259 linhas.

### 37. Amostragem de dados (1%)
- **Foi criada uma amostra de pouco mais de 1% dos registros (20.753 linhas). A distribuição de Global_active_power na amostra manteve o mesmo padrão da base completa, confirmando que uma pequena amostragem aleatória é representativa do conjunto total.**

### 38. Distribuição do consumo
- **A distribuição da variável Global_active_power está claramente concentrada em valores baixos.  
  A maior parte dos registros tem consumo próximo de zero a 2 kW. O gráfico mostra que a frequência cai rapidamente conforme os valores aumentam, indicando que há poucos registros de alto consumo.**

### 39. Relação entre variáveis elétricas
- **O gráfico de dispersão entre Voltage e Global_intensity mostra que existe uma tendência negativa:  
  À medida que a intensidade global (Global_intensity) aumenta, o valor da voltagem tende a diminuir.  
  Ou seja, há uma correlação inversa entre essas variáveis — os pontos se concentram formando um “declive”, mostrando que valores altos de intensidade estão associados a valores mais baixos de voltagem.  
  No entanto, a dispersão dos pontos indica que não é uma relação perfeitamente linear, mas a tendência geral é visível.**
