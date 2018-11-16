# PIMVI
Código do projeto para PIM VI da faculdade UNIP, curso Analise e Desenvolvimento de Software

Objetivos desse PIM:
- Fazer o levantamento e a análise de requisitos de um sistema para uma determinada empresa, utilizando as técnicas aprendidas.

Contexto do trabalho:
- Uma livraria resolveu contratar uma empresa para construir um sistema para realizar a venda de livros pela Internet. Em linhas gerais, o usuário deverá acessar o site, escolher o(s) livro(s) que deseja comprar e efetuar a compra.

Alguns aspectos devem ser levados em consideração:
- O acesso ao sitedeverá ser feito por meio de logine senha. Caso seja a primeira vez que o usuário esteja acessando o site, este deve se cadastrar. Os dados para cadastro do usuário no sitesão: nome, endereço, telefone, data de nascimento, logine senha Caso o usuário já possua cadastro apenas deve digitar seu logine senha.

- Após a validação do logine senha o usuário poderá escolher os livros de seu interesse consultando os dados no sistema de controle de estoque (já existente). Este irá retornar a informação da disponibilidade ou indisponibilidade do livro(s) para compra. Após a escolha do(s) livro(s), o usuário deverá efetuar a compra com pagamento somente por meio de cartão de crédito que deve ser validado pelo sistema externo da operadora de cartão de crédito. Caso o(s) livro(s) escolhido(s) pelo usuário esteja(m) indisponível(is) para compra no momento, o usuário poderá realizar a reserva.

- Para resolver esses problemas, o proprietário resolveu contratar uma empresa para desenvolver um sistema para a livraria.

Atividades a serem realizadas:
1.Identificar os casos de uso.
2.Elaborar o modelo de casos de uso.
3.Identificar relacionamentos de include, extende generalização.
4.Cada caso de uso deve ter uma descrição sucinta do seu comportamento, do fluxo principal, fluxos alternativos e de exceção, pré e pós-condições.
5.Descrever os requisitos não funcionais (requisitos de usabilidade).
6.Identificar e descrever o contexto de uso (usuários, tarefas e ambiente).
7.Descrever as regras de negócio.
8.Elaborar o diagrama de classes de análise (Boundary, Control, Entity).
9.Construir o modelo de dados (MER).

Dicas para a elaboração do PIM VI:
Para o modelo de casos de uso:
1.identifique os principais atores envolvidos no sistema;
2.identifique os principais objetivos do sistema;
3.faça a relação entre atores e casos de uso;
4.verifique se há cenários do tipo <<extends>> ou de <<include>>.

Para o protótipo de telas:
1.Embora não seja parte do trabalho, é interessante que, antes da especificação dos casos de uso, você elabore um esboço da tela para cada caso de uso.
2.Isso facilitará na hora de você especificar os casos de uso.

Para a especificação de casos de uso:
Para cada caso de uso:
1.descreva brevemente o que ele faz;
2.identifique o que o sistema precisa para iniciar o caso de uso (pré-condição);
3.descreva o passo a passo do caminho de sucesso, ou seja, o caminho onde tudo dá certo;
4.repasse o fluxo principal e identifique possíveis caminhos alternativos e exceções;
5.descreva os fluxos alternativos;
6.identifique as regras de negócio.

Para o diagrama de classes:
1.identifique os substantivos do texto e do diagrama de casos de uso;
2.selecione aqueles que fazem parte do sistema;
3.faça o relacionamento entre eles e coloque o nome em cada relação;
4.identifique as multiplicidades entre as classes;
5.localize atributos e métodos de cada classe;
6.verifique a existência de agregações e heranças.

Para o MER:
1.A partir do diagrama de classes, identifique as classes que precisam ser persistidas e crie uma tabela respectiva;
2.Verifique a criação das chaves primárias de cada tabela;
3.Identifique as relação do tipo 1..n e propague a chave estrangeira para o lado n;
4.Verifique relações do tipo n..ne crie tabelas de relacionamento, contendo ao menos as chaves primárias das tabelas envolvidas na relação.
5.Revise o modelo.

