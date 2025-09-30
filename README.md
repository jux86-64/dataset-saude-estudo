# Análise de Casos de Dengue - Projeto de Estudo

## 📋 Sobre o Projeto
Este é um projeto de análise de dados desenvolvido para fins educacionais, simulando casos de dengue nos estados do Sudeste brasileiro. **Importante**: Os dados utilizados são uma simulação criada para aula e não representam números reais.

## 🎯 Objetivo do Estudo
Desenvolver habilidades em análise de dados e visualização através de um cenário simulado de saúde pública, explorando:
- Análise temporal de dados epidemiológicos
- Comparação entre regiões
- Identificação de padrões e tendências
- Criação de visualizações eficazes

## 📊 Sobre os Dados
- **Natureza**: Dados simulados para exercício acadêmico
- **Período**: 2015-2024 (fictício)
- **Região**: Sudeste do Brasil (ES, MG, RJ, SP)
- **Variáveis**: Ano, Estado, Casos Confirmados

## 🛠️ Ferramentas e Tecnologias
- **Python** para análise de dados
- **Pandas** para manipulação de dados
- **Matplotlib** e **Seaborn** para visualizações
- **Jupyter Notebook** para desenvolvimento

## 📈 Análises Realizadas

### 1. Agrupamento e Consolidação
```python
# Agrupamento por ano e estado
agrupar = df.groupby(['Ano', 'Estado']).sum()
```

### 2. Visualizações Criadas
- Gráfico comparativo de casos por ano e estado
- Identificação de picos e tendências temporais
- Análise de distribuição entre estados

### 3. Principais Descobertas (Baseadas na Simulação)
- Padrões de sazonalidade identificados nos dados simulados
- Variações entre estados na simulação
- Anos com maior incidência na base simulada

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências:
   ```
   pip install pandas matplotlib seaborn numpy jupyter
   ```
3. Execute o notebook:
  ```
  jupyter notebook ProjetoSaude.ipynb
  ```

## 📁 Estrutura do Projeto
```
ProjetoSaude.ipynb          
datasets/
└── Simulacao_Dengue_Sudeste_2015_2024.xlsx  
README.md                   
```

## 🎓 Aprendizados Desenvolvidos
      - Manipulação de dados com Pandas
      - Criação de visualizações com Matplotlib/Seaborn
      - Análise exploratória de dados
      - Trabalho com dados temporais
      - Documentação de projetos de análise

## 🔮 Possíveis Expansões
      - Adicionar mais variáveis à simulação (clima, população)
      - Implementar modelos de previsão
      - Criar dashboard interativo
      - Adicionar análise de correlações

## ⚠️ Aviso Importante

ESTE É UM PROJETO EDUCACIONAL
Os dados utilizados são totalmente simulados e não refletem a realidade epidemiológica. Desenvolvido para praticar técnicas de análise de dados e visualização.

*Projeto desenvolvido como exercício acadêmico*
