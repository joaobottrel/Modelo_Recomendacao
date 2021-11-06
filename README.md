# Modelo_Recomendacao
Modelo de Recomendação para uma plataforma de e-commerce

O objetivo desse trabalho é a implementação de um modelo de recomendação para facilitar a busca de produtos para usuários que forem acessar uma plataforma de e-commerce, baseado em histórico e a relação entre compras realizadas e usuários da plataforma.
Esse repositório possui o arquivo Modelo_Recomendacao.ipynb escrito no Google Colab e foi implementado o método de similaridade de cossenos como modelo de recomendação.


O modelo funciona bem e sua aplicação pode ser usada na seguinte situação:
* Quando um usuário entra numa seção da loja e pesquisa um item, aparecendo assim itens da mesma categoria como sugestão para facilitar a pesquisa do usuário.

Porém tem alguns pontos de melhoria que podem ser aplicados
* Os reviews são baseadas no pedido de compra, ou seja, se o usuário fez uma compra de 5 itens, a nota vai para os 5 itens, indiferente se um produto foi mais ou menos satisfatório que o outro
* A média de reviews pode ser uma métrica que engana pois uma venda de um produto com 1 review de 5 pontos tem média maior que 200 vendas de um produto com média de 4.9, porém o último item seria mais popular.
* Algumas categorias da loja possui poucos itens como "cds_dvds_musicais" que possui 1 item, seria interessante para a empresa ter uma distribuição categorica um pouco mais abrangente para evitar possíveis erros na recomendação
