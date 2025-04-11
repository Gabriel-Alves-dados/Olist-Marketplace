# Olist Marketplace – Análise de Dados com Power BI  
Análise exploratória e estratégica com foco em comportamento de compra, atrasos logísticos e performance de vendas.

Este projeto tem como objetivo transformar dados reais da Olist — um marketplace brasileiro — em insights estratégicos por meio da criação de um dashboard interativo no Power BI.

A base de dados foi obtida via Kaggle e representa transações reais entre 2016 e 2018. Através de técnicas de Business Intelligence, ETL, modelagem relacional e criação de medidas com DAX, o projeto busca responder questões chave do negócio como:

- Quais categorias mais vendem?
- Como é o comportamento de pagamento?
- Há gargalos logísticos?
- Qual o tempo médio de entrega?

O resultado é um painel dinâmico que permite ao usuário explorar os dados e gerar insights para decisões baseadas em evidências.

##  Estrutura do Repositório

Olist-Marketplace/  
├── README.md  
├── powerbi/  
│   └── Olist_Dashboard.pbix  
├── documentos/ 
│   └── relatorio_olist.pdf  
├── imagens/  
│   ├── dashboard.png  
│   ├── modelo_dados.png  
│   └── print_metricas.png  

##Principais Insights

-  **Categorias com maior volume de vendas**: Artigos de cama, mesa e banho lideram o volume de pedidos, sugerindo alta demanda por itens domésticos.
- **Atrasos logísticos**: Pedidos com atrasos de entrega estão concentrados em algumas categorias, como esportes e utilidades domésticas.
- **Formas de pagamento**: A maioria dos pedidos foi paga em cartão de crédito, com destaque para parcelamentos entre 2 e 4 vezes.
- **Evolução de vendas**: A análise sazonal mostra aumento significativo de pedidos entre outubro e dezembro, indicando potencial de campanhas sazonais no fim de ano.

Esses insights foram gerados a partir de filtros dinâmicos, medidas DAX e visuais interativos criados no Power BI.

## Tecnologias e Técnicas Utilizadas

- **Power BI**: criação do dashboard e visualizações interativas
- **DAX (Data Analysis Expressions)**: desenvolvimento de medidas como receita total, ticket médio, tempo de entrega e análise sazonal
- **Modelagem de Dados**: construção de um modelo relacional com tabelas de fato e dimensões
- **ETL**: limpeza, transformação e relacionamento dos dados diretamente no Power BI
- **Visual Storytelling**: estruturação de visualizações que conduzem o olhar do usuário à descoberta de insights

Este projeto simula um pipeline real de Business Intelligence, combinando análise exploratória com visão estratégica.

##  Como visualizar o projeto

- Acesse o arquivo `.pbix` em `/powerbi` para visualizar no Power BI Desktop

---

##  Sobre

Este projeto foi desenvolvido como parte do meu portfólio em **Análise de Dados**, aplicando técnicas reais de BI para transformar dados em decisões.

Sinta-se à vontade para explorar, comentar ou contribuir!

---

##  Contato

Gabriel Alves — [LinkedIn](https://www.linkedin.com/in/gabriel-alves-dados/)  
🌐 Artigo completo no Medium: [Leia aqui]([https://lnkd.in/dvM7dgU8](https://medium.com/@gabrielhanszmann/análise-de-dados-reais-da-olist-com-power-bi-c16cafe2a35d))
