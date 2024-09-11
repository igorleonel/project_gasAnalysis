# Análise de Preços de Combustíveis no Brasil com Dash e Plotly

## Visão Geral:

Este projeto utiliza o framework Dash com Python para criar uma aplicação interativa de análise de dados sobre o preço da gasolina em diferentes regiões e estados do Brasil.
A aplicação permite visualizar e comparar informações sobre preços de gasolina ao longo do tempo, analisando variações regionais e comparações diretas entre estados.
O deploy da aplicação é realizado na plataforma Render, que facilita a publicação e a escalabilidade do aplicativo. O processo de ETL (Extração, Transformação e Carga) foi 
realizado utilizando Python para garantir que os dados fossem manipulados e preparados adequadamente para análise. 

## Base de Dados
A base de dados utilizada é um arquivo CSV contendo informações sobre o preço da gasolina. O dataset inclui colunas como Região, Estado, Produto, Preço de revenda por litro, etc.
Os dados foram extraídos a partir do [Kaggle](https://www.kaggle.com/datasets/matheusfreitag/gas-prices-in-brazil/data)

## O deploy
O deploy da aplicação foi realizado na plataforma Render. O Render é uma plataforma de deploy em nuvem que oferece uma solução simples e eficiente para hospedar aplicações web.

## Principais Funcionalidades:

1. **Interatividade com Filtros:** A aplicação possibilita a seleção de ano e região de análise, filtrando os dados de acordo com as escolhas do usuário para uma análise mais focada.

2. **Comparação de Máximos e Mínimos:** Utiliza gráficos de linhas para exibir as máximas e mínimas dos preços de revenda ao longo dos anos, facilitando a identificação de tendências.

3. **Análise Regional e Estadual:** Gráficos de barras horizontais destacam os preços médios por região e estado, permitindo uma comparação direta entre diferentes locais do Brasil.

4. **Comparação Temporal entre Estados:** Gráficos de linha animados mostram a evolução dos preços de revenda ao longo do tempo para múltiplos estados, com a possibilidade de selecionar estados específicos para comparação.

5. **Comparação Direta de Preços entre Estados:** Gráficos de dispersão indicam qual estado possui o menor preço de revenda em um dado período, com anotações que auxiliam na interpretação visual dos dados.

6. **Indicadores:** Dois indicadores numéricos mostram a variação de preços ao longo do tempo para estados específicos, destacando as mudanças percentuais e valores absolutos em um formato claro e direto.

## Ferramentas Utilizadas:

* **Dash:** Framework para a criação de dashboards interativos.
* **Plotly:** Biblioteca para a criação de gráficos interativos.
* **Pandas:** Utilizado para manipulação e limpeza dos dados.
* **Dash Bootstrap Components:** Fornece estilos e layouts responsivos com temas alternativos.
* **Render:** Para realizar o deploy do projeto.

## Código e Layout:

O código é organizado para incluir callbacks que atualizam os gráficos dinamicamente com base nas interações do usuário, e utiliza componentes do Dash Bootstrap para uma apresentação mais sofisticada e acessível.
A interface é dividida em diferentes seções (cards), cada uma responsável por uma análise específica.

## Conclusão:

Este projeto é uma poderosa ferramenta de visualização de dados que pode ser utilizada por analistas e gestores para tomar decisões informadas sobre a dinâmica dos preços de combustíveis no Brasil.
Ao disponibilizar visualizações interativas, a aplicação facilita a identificação de padrões e tendências que poderiam passar despercebidos em análises tradicionais.

Confira o projeto completo em meu portfólio: [Link para o Portfólio](https://project-gasprice.onrender.com/)
