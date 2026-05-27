# Análise de Logística e Impacto Financeiro - E-commerce (Olist)

Este projeto analisa como a eficiência logística (prazos de entrega) e fatores financeiros (preço do produto e valor do frete) impactam a satisfação do cliente (review score) utilizando a base de dados pública da Olist.

## Tecnologias Utilizadas
* Python 3
* Pandas
* Matplotlib
* Seaborn

## Principais Insights

* **Impacto do Atraso:** Quando ocorre atraso na entrega, a nota média de satisfação cai de **4.1 para 2.2 estrelas**, consolidando o prazo como fator crítico para a experiência do usuário.
* **Paradoxo do Frete:** Pedidos com atraso registraram um frete médio **64% mais caro** (R$ 32,27 vs R$ 19,64). O cliente investe mais e recebe uma experiência inferior.
* **Segmentação Premium:** Produtos de maior valor (Premium) demoram em média **2 dias a mais** para serem entregues devido à complexidade logística. Apesar disso, sustentam a maior nota de satisfação (4.13 estrelas), mostrando resiliência desde que o prazo estimado seja cumprido.

##  Como Executar
1. Baixe os dados originais diretamente do [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
2. Crie uma pasta chamada `data/` na raiz do projeto e insira os arquivos CSV baixados lá dentro.
3. Instale as dependências: `pip install -r requirements.txt`
4. Execute o notebook contido na pasta `notebooks/`.
