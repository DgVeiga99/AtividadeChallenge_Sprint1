# Enterprise Challenge - Sprint 1 - Ingredion

## Descrição do Projeto
Este projeto tem como objetivo analisar a **produção de laranja no Brasil**, utilizando imagens de satélite e dados históricos para correlacionar **índices espectrais (NDVI)** com **produtividade agrícola**. A partir dessas informações, buscamos identificar padrões ideais para o plantio e prever a produtividade futura utilizando técnicas de **Machine Learning**.

## Região de Estudo
A análise foi realizada na **região de Bebedouro - SP**, um dos principais polos citrícolas do Brasil. Essa região possui **clima favorável, solo adequado e infraestrutura avançada**, sendo um dos grandes centros de exportação de suco de laranja.

## Metodologia

### 1. Sensoriamento Remoto e Análise de NDVI
Utilizamos o **SATVeg**, uma plataforma da **EMBRAPA**, para obtenção e análise de imagens de satélite da área agrícola. O **NDVI (Normalized Difference Vegetation Index)** foi aplicado para monitoramento da vegetação, permitindo:
- Identificação de **padrões sazonais** da cultura da laranja;
- Análise da **densidade vegetativa** em diferentes períodos;
- Detecção de **possíveis problemas na produtividade**.

### 2. Coleta de Dados Temporais
Para validar a correlação entre NDVI e produtividade, utilizamos **bases públicas do IBGE**, obtendo dados históricos de produção agrícola. Os principais arquivos analisados incluem:
- **Tabela 3.25 - São Paulo**: Valores cultivados de culturas permanentes, incluindo a laranja.
- **Tabela 6.25 - São Paulo**: Dados de produção de culturas sazonais.
- **Satveg_planilha**: Registro dos valores de NDVI ao longo do tempo para a área estudada.
- **laranja-valor-da-producao-2023**: Dados sobre o valor de produção de laranja por estado no Brasil.

## Ferramentas Utilizadas
- **SATVeg (EMBRAPA)**: Análise de imagens de satélite e índices de vegetação.
- **IBGE - Produção Agrícola Municipal (PAM)**: Dados históricos de produtividade.
- **Linguagem Python**: Para modelagem preditiva futura baseada nos padrões identificados.

## Conclusão e Próximos Passos
Os dados coletados confirmam que é possível correlacionar **informações de sensoriamento remoto (NDVI) com produtividade da laranja**. O próximo passo do projeto será desenvolver um **modelo de Machine Learning** que permita prever:
- **Melhores épocas para plantio e colheita**;
- **Impacto das condições climáticas na produção**;
- **Ajustes de manejo para otimizar a produtividade**.

Esse modelo pode trazer benefícios diretos para a **tomada de decisão no agronegócio**, tornando o cultivo da laranja **mais eficiente e sustentável**.
