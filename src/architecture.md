### • Como a arquitetura está sendo exibida?

A arquitetura está sendo expressa por meio deste documento através da abordagem de diagramação de arquitetura de software C4 Model. A documentação deste projeto está sendo dividida em 2 tópicos conforme a estrutura hierárquica a seguir:

```
\ Arquitetura de Software (Esta página)
  \-> C1. Visão Geral
    \-> C2. Sistema

```

| Nome da seção   | Propósito e breve descrição                                                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| C1. Visão Geral | Nesta seção você verá o primeiro nível do C4 Model, sendo uma perspectiva de contexto da arquitetura do sistema.                                                                                                     |
| C2. Sistema     | Nesta seção você verá o sistema como um todo do ponto de vista de contâineres, os quais se relacionam. Nessa visão são expostos os relacionamentos entre esses contâineres para garantir que a arquitetura funcione. |

### • O que é o C4 Model?

O modelo C4 é uma abordagem fácil de aprender e amigável ao desenvolvedor para diagramação de arquitetura de software. Bons diagramas de arquitetura de software auxiliam na comunicação dentro/fora das equipes de desenvolvimento/produto de software, integração eficiente de novos funcionários, revisões/avaliações de arquitetura, identificação de riscos (por exemplo, tempestade de riscos), modelagem de ameaças (por exemplo, STRIDE/LINDDUN), etc. Ele foi criado por Simon Brown e é baseado no na abordagem 4+1 de Philippe Kruchten e também no UML.

### • Como ler a documentação da forma correta?

Entenda que o C4 Model é uma abordagem minimalista para se expressar uma arquitetura de software com um conjunto rico de diagramas e recursos intertextuais. Dessa forma, você precisa imaginar a documentação como um mapa arquitetural. Neste mapa arquitetural você poderá dar um zoom e a cada nível descido aumentar o nível de granularidade das informações, sendo possível visualizar cada vez mais detalhes.<br>
No nível C1 você verá o sistema, do ponto de vista de contexto do sistema e da perspectiva de um usuário, não técnico ou técnico que seja de dentro ou de fora da equipe de desenvolvimento. No nível C2 você poderá ver o sistema do ponto de vista de containers e seus relacionamentos, da perspectiva de um usuário técnico de dentro ou fora da equipe de desenvolvimento, com capacidade de entender as informações expressas.

### • Principais tecnologias envolvidas

1. [JavaScript](https://www.javascript.com/)<br>
   JavaScript é uma linguagem de programação baseada em texto usada tanto no lado do cliente quanto no lado do servidor que permite que você torne as páginas da web interativas. Enquanto HTML e CSS são linguagens que dão estrutura e estilo às páginas da web, o JavaScript fornece às páginas da web elementos interativos que envolvem o usuário. Exemplos comuns de JavaScript que você pode usar todos os dias incluem a caixa de pesquisa na Amazon, um vídeo de recapitulação de notícias incorporado no The New York Times ou atualizar seu feed do Twitter.

2. [TypeScript](https://www.typescriptlang.org/)<br>
   TypeScript é uma linguagem de programação fortemente tipada que se baseia em JavaScript, oferecendo melhores ferramentas em qualquer escala. O TypeScript adiciona sintaxe adicional ao JavaScript para oferecer suporte a uma integração mais estreita com seu editor. Detecte erros no início do seu editor. O código TypeScript é convertido em JavaScript, que é executado em qualquer lugar que o JavaScript seja executado: em um navegador, em Node.js ou Deno e em seus aplicativos. O TypeScript entende JavaScript e usa inferência de tipos para fornecer ótimas ferramentas sem código adicional.

3. [NextJS](https://nextjs.org/)<br>
   Next.js é uma estrutura da web de desenvolvimento front-end React de código aberto criada por Vercel que permite funcionalidades como renderização do lado do servidor e geração de sites estáticos para aplicativos da web baseados em React.

4. [NestJS](https://nestjs.com/)<br>
   Nest (NestJS) é um framework para criar aplicativos Node.js eficientes e escaláveis ​​do lado do servidor. Ele usa JavaScript progressivo, é construído com e suporta totalmente TypeScript (ainda permite que os desenvolvedores codifiquem em JavaScript puro) e combina elementos de POO (Programação Orientada a Objetos), PF (Programação Funcional) e PRF (Programação Reativa Funcional).<br>
   Sob o capô, o Nest faz uso de frameworks robustos de servidor HTTP como o Express (o padrão) e, opcionalmente, pode ser configurado para usar o Fastify também!
   No entanto, embora existam muitas bibliotecas, auxiliares e ferramentas excelentes para Node (e JavaScript do lado do servidor), nenhuma delas resolve efetivamente o principal problema de - Arquitetura.<br>
   A Nest fornece uma arquitetura de aplicativo pronta para uso que permite que desenvolvedores e equipes criem aplicativos altamente testáveis, escaláveis, pouco acoplados e de fácil manutenção. A arquitetura é fortemente inspirada no Angular.

5. [TypeORM](https://typeorm.io/)<br>
   TypeORM é um ORM que pode ser executado em plataformas NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo e Electron e pode ser usado com TypeScript e JavaScript (ES5, ES6, ES7, ES8). Seu objetivo é sempre oferecer suporte aos recursos JavaScript mais recentes e fornecer recursos adicionais que o ajudem a desenvolver qualquer tipo de aplicativo que use bancos de dados - desde pequenos aplicativos com algumas tabelas até aplicativos corporativos de grande escala com vários bancos de dados. O TypeORM é altamente influenciado por outros ORMs, como Hibernate, Doctrine e Entity Framework.

6. [HTTP/S](https://datatracker.ietf.org/doc/html/rfc2616)<br>
   O HTTP é um protocolo para buscar recursos como documentos HTML. É a base de qualquer troca de dados na Web e é um protocolo cliente-servidor, o que significa que as solicitações são iniciadas pelo destinatário, geralmente o navegador da Web. Um documento completo é reconstruído a partir dos diferentes subdocumentos obtidos, por exemplo, texto, descrição do layout, imagens, vídeos, scripts e muito mais.

7. [REST API](https://standards.rest/)<br>
   API REST, também chamada de API RESTful, é uma interface de programação de aplicações (API ou API web) que está em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTful. REST é a sigla em inglês para "Representational State Transfer", que em português significa tansferência de estado representacional. Essa arquitetura foi criada pelo cientista da computação Roy Fielding.

8. [AWS - Cognito](https://aws.amazon.com/pt/cognito/)<br>
   O Amazon Cognito é uma plataforma de identidade para aplicações web e aplicativos móveis. É um diretório de usuários, um servidor de autenticação e um serviço de autorização para credenciais da AWS e tokens de acesso do OAuth 2.0. Com o Amazon Cognito, você pode autenticar e autorizar usuários do diretório de usuários integrado, de seu diretório corporativo e de provedores de identidades de consumidores, como Google e Facebook.
