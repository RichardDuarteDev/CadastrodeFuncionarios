Descrição do Projeto (Fluxo da Arquitetura Híbrida)

1 - A aplicação principal é uma aplicação monolítica MVC com seu próprio banco de dados.

2 - Ela se conecta ao Back-End de um sistema externo (camada de negócios) por meio de uma API interna, consumindo dados e serviços da aplicação de integração.

3 - Simultaneamente, também consome uma API pública externa, integrando dados adicionais ao sistema.

4 - A lógica de apresentação e orquestração das integrações acontece no MVC, que unifica os dados consumidos das APIs com os seus próprios dados locais.

Com isso, a aplicação centraliza as interfaces e expõe funcionalidades unificadas ao usuário final, mesmo com os dados vindo de diferentes fontes.

