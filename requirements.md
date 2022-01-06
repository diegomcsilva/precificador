# Precificação - Facilitador de calculo de preço no ramo alimentício

  ## Team
    Diego
    Camila
    Michel
    Jaque

  ## General Referencies
    <!-- Ref de Mercado -->
    https://www.calcularte.com.br/

    <!-- Ref de estudo -->
    - requirements (https://www.usability.gov/how-to-and-tools/methods/requirements.html)
    - https://www.youtube.com/watch?v=nDN4JRbFEns&t=845s&ab_channel=Rocketseat

  ## Problem
    - Dificuldade que pessoa do ramo alimentício encontram ao utilizar, ou não, planilhas para calculo de preço de produto.

  ## Objctive
    - Faciliar e modernizar o calculo de preço de produtos.
    <!-- TO DO Evoluir o objetivo pra tornar ele único! -->
    - Fazer com que profissionais do ramo alimentício consigam precificar de forma correta.
    - Tornar a atualização de preço de ingrediente mais simples e continua.

  ## Persona
    Leigo virtualmente
    Pequena e Microempreendedor 
    Referência (Facebook, Whatsapp) - Aderência

  ## Possibilities
    - Trabalhar com gerenciamento de estoque.
    - Trabalhar com pedidos dinamicos a mercados.
    - Gestão de estoque pro mercado saber que a pessoa precisa do produto.
    - Localização ajudaria no atendimento de mercado
    - Pode ter divulgação de workshops e cursos.
    - Adicionar Publicidade na divugação de promoções de mercado, Workshops, Cursos etc.
    - Pode deixar receitas publicas e virar um site de receitas.
    - Pode conseguir parcerias com empresas de produtos (Ex. Leite condensado) e fazer sugestão no cadastro.
    - Pode ter uma comunicação com o mercado e a pessoa solicita o produto pelo app.
    - Atender pequenos e micronegócios no final da pandemia.

  ## Variables
    ### Usuário:Main
    - Produto
    - Ingredientes
    - Receitas
    - Informaçoes de contato
      - Nome
      - Profissão
      - Idade
      - Endereço

    ### Ingrediente
      - Nome
      - Preço
      - Data do cadastro
      - Data de alteração
      - Quantidade (g, ml)

    ### Receita
      - Nome
      - Ingredientes
      - Tempo de preparo
      - Rendimento
      - Lucro esperado
      - Valor do produto
      - Imposto (ISS, Notas etc)
      - Publica
      - Categoria 
        - tipo (doce, salgado)
        - tag (peixe, carne, picante, caseiro)

  ## List Relations
    Ingrediente > Produto
    Ingrediente > Usuário
    Produto > Usuário


  ## Business Requirements
    ### (define the objectives and what problems the stakeholder intends to solve with the product.)
    [ ] Os ingredientes ficam disnponíveis para qualquer receita cadastrado pelo usuário.
    [ ] Para o usuário estar ativo é necessário pagamento de mensalidade.
    [ ] Usuário só pode visualizar receitas cadastradas em sua conta.
    [ ] Fazer com que os preços sejam alterados caso algum preço de um ingrediente mude significativamente.
    [ ] Caso o preço de algum ingrediente seja alterado o preço final da receita muda.

  ## User Requirements 
    ### (describe how user expectations and how they will interact with the product.  Use the features, functions, and content described in your scenarios to develop your requirements. Your user scenarios should outline the tasks your users want to complete on your site.)
    [ ] - O usuário precisa se logar com e-mail e senha para acessar conta.
    [ ] - O usuário precisa conseguir cadastrar ingredientes
    [ ] - O usuário precisa conseguir cadastrar produto
    [ ] - O usuário precisa poder visualizar o resultado do calculo do produto
    [ ] - O usuário precisa conseguir editar informações do ingrediente
    [ ] - O usuário precisa conseguir editar informações do produto
    [ ] - O usuário precisa conseguir deletar um ingrediente
    [ ] - O usuário precisa conseguir deletar um produto
    [ ] - O usuário precisa poder consultar/utilizar o ingrediente de outra receita
    [ ] - O usuário precisa poder copiar um receita inteira
    [ ] - O usuário precisa poder buscar por um receita

  ## Functional Requirements 
    ### (provide details of how a product should behave and specify what is needed for development.)
    [ ] - O usuário precisa ser autenticado pela aplicação
    [ ] - O sistema precisa verificar se o usuário esta ativo
    [ ] - Receitas devem poder ser editadas
    [ ] - Ingredientes devem poder ser editadas
    [ ] - Receitas devem poder ser apagadas
    [ ] - Ingredientes devem poder ser apagadas
    [ ] - Qualquer pessoa pode visualizar receitas públicas
    [ ] - Receitas publicas podem ser buscadas/filtradas
    [ ] - Notificar o usuário depois de uma tempo de uma receita cadastrada(Atualização de preço).

  ## Quality-of-Service Requirements 
    ### (detail what characteristics a product must maintain in order to maintain its effectiveness and any constraints.)
    [ ] - Segurança dos dados do usuário (Receita não compartilhada, caso ñ seja opcão do usuário) 
    [ ] - Preocupação com UX e UI
    [ ] - Interface amigável
    [ ] - Fácil e Intuitivo de ser utilizado
    [ ] - Responsividade em todas as telas

  ## Implementation Requirements 
    ### (are used to detail changes in process, team roles, migration from one system to another, etc.)
    - Web Site
    - Responsivo
    - Mobile First
    - Domínio - Definir
    - Hospedagem Node (Versel, Netlify)

  ## Tecnologic Architecture
    -- BACK
      - Nest.js
      - GraphQL
      - TypeORM
      - Test
    -- FRONT
      - Next.js
      - React.js
      - Test