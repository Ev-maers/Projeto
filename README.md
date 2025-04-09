# Projeto_Residencia
Origens -  Um marketplace para artesão

# 📌 Equipe:
- Crocheteiros

# 📌 Integrantes: 
- Deyvison: dmc2@cesar.school
- Joyce: jcs3@cesar.school
- Albean: ascb@cesar.school
- Evellin: maers@cesar.school



# 📌 Sobre o Projeto

Origens é um marketplace voltado para a venda de produtos artesanais brasileiros, conectando artesãos de diversas regiões de todo o Brasil a compradores que valorizam peças únicas e culturais.

# ✨ Funcionalidades Principais

- Catálogo de produtos artesanais organizado por região.
- Sistema de busca e filtros avançados.
- Perfil personalizado para compradores e artesãos.
- Carrinho de compras e favoritos.
- Dashboard de vendas para artesãos.

# 📋 Histórias de Usuário

1. Exploração de Produtos
Como visitante,
quero explorar produtos artesanais por regiões do Brasil,
para que eu possa conhecer a diversidade cultural e artesanal de cada localidade.

2. Cadastro de Usuário
Como novo usuário,
quero me cadastrar na plataforma,
para que eu possa salvar favoritos, fazer compras e personalizar minhas preferências.

3. Personalização de Gostos
Como usuário cadastrado,
quero personalizar meus gostos,
para que a plataforma me recomende produtos de acordo com meu estilo e preferências.

4. Busca por Produto
Como usuário,
quero utilizar a barra de busca,
para que eu possa encontrar rapidamente produtos específicos ou categorias que me interessam.

5. Filtragem por Região
Como comprador curioso,
quero filtrar os produtos por região do Brasil,
para que eu possa conhecer o artesanato típico de determinada localidade.

6. Favoritar Produtos
Como usuário logado,
quero favoritar produtos,
para que eu possa acessá-los facilmente mais tarde e comparar antes de comprar.

7. Perfil de Vendedor
Como artesão,
quero acessar meu perfil de vendedor,
para que eu possa editar minhas informações e gerenciar minha vitrine de produtos.

8. Análise de Vendas
Como vendedor,
quero acompanhar a análise de minhas vendas,
para que eu possa entender meu desempenho e tomar decisões estratégicas.

9. Gerenciamento de Pedidos
Como vendedor,
quero gerenciar meus pedidos,
para que eu possa manter o controle de entregas e satisfação dos clientes.

10. Acesso ao SAC
Como usuário (cliente ou vendedor),
quero acessar o SAC (Serviço de Atendimento ao Cliente),
para que eu possa resolver dúvidas ou problemas rapidamente.

11. Explorar Mapa Interativo
Como usuário visitante,
quero interagir com o mapa do Brasil na home,
para que eu possa descobrir produtos típicos de cada estado de forma visual e intuitiva.

12. Listagem de Categorias
Como usuário,
quero acessar uma listagem organizada de categorias,
para que eu possa encontrar mais facilmente o tipo de produto artesanal que estou procurando.

13. Gerenciar Estoque
Como vendedor,
quero gerenciar meu estoque de produtos,
para que eu possa manter minhas ofertas atualizadas e evitar vendas de itens indisponíveis.

14. Avaliar Compras
Como comprador,
quero avaliar os produtos que comprei,
para que eu possa ajudar outros usuários e dar feedback aos artesãos.

15. Configurações de Conta
Como usuário cadastrado,
quero acessar e alterar minhas configurações de conta,
para que eu possa atualizar meus dados pessoais, preferências e segurança.


# 📊 Diagrama de Atividades do Sistema

stateDiagram-v2
    [*] --> Home
    Home --> Busca: Pesquisar produtos
    Home --> Explorar: Navegar por regiões
    Home --> Login: Acessar conta
    
    Login --> Cadastro: Novo usuário
    Login --> Perfil: Login bem-sucedido
    
    Perfil --> Favoritos: Ver favoritos
    Perfil --> Compras: Histórico
    Perfil --> Produtos: (Artesão)
    
    Busca --> Produto: Selecionar item
    Explorar --> Produto: Selecionar item
    
    Produto --> Carrinho: Adicionar
    Produto --> Favoritos: Favoritar
    
    Carrinho --> Checkout: Finalizar compra
    Checkout --> Pagamento
    Pagamento --> Confirmação


# 📌 Trello

![trello](https://github.com/user-attachments/assets/28534d06-afa1-4dff-959a-9424d902e199)

# 📌 Home Page

![figma](https://github.com/user-attachments/assets/e7817765-44d5-4476-94b1-6d280b1fc36f)


# 🛠️ Tecnologias que serão Utilizadas

- Prototipagem: Figma
- Frontend: React.js
- Backend: Node.js
- Banco de Dados: Django
- Pagamentos: Mercado Pago

# 📄 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.


