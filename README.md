# Salas UFCG - Termo de abertura

> "Oh não, tá tendo aula na minha sala? Apresentação de PIBIC?" -
> algo que  todo professor passa algum dia, UFCG 

## Contexto
Atualmente não existe fácil acesso à informação sobre as salas da UFCG. Todo semestre é necessário que a coordenação e os professores juntem esforços para alocar o uso das salas de maneira ótima e, mesmo após as matrículas, o corpo docente tem dificuldades em reservar salas com os recursos necessários, como projetos funcionais, e em horários apropriados. Os alunos, por sua vez, tem ainda menos informação sobre o funcionamento dos prédios e salas da universidade.
Além disso, com o início da implementação de um Smart Campus na UFCG, surgiram várias ideias de interação do corpo docente e discente com prédios e salas do campus. É fundamental que exista uma plataforma que unifique o acesso de toda essa informação gerada sobre esses recintos da UFCG, para padronizar e permitir escalabilidade do Smart Campus como um todo.

## Proposta

Como um meio de solucionar esse problema, o Salas oferece a curto prazo uma ferramenta de organização e planejamento para corpo docente e a longo prazo uma API valiosa para o Smart Campus.\
O Salas UFCG é uma plataforma de monitoramento do uso de salas da UFCG que pode ser dividido em duas principais funcionalidades: a Aplicação Web e a API.\

### Aplicação web
A Aplicação Web diz respeito aos recursos que serão acessíveis ao corpo docente e discente através de um navegador web. Nela teremos recursos como:
-   Visualização de disponibilidade de salas;
-   Visualização e cadastro de recursos disponíveis nas salas, o que inclui número de cadeiras, situação de projetores, ar-condicionado, lâmpadas, entre outros;
-   Professores podem reservar horários de uso, até mesmo com eventos que repetem semanalmente;
-   A administração dos prédios pode entender melhor como estão sendo usadas as salas e otimizar a manutenção das mesmas;
-   Professores e alunos podem registrar queixas sobre algum recurso da sala;
-   Visualização geral em um mapa com informações sucintas e úteis, como disponibilidade e acessibilidade, das salas do Campus.

### API
A API do Salas, por outro lado, oferece aos desenvolvedores do Smart Campus um sistema único de informação sobre os recintos da universidade. Assim, aplicativos poderão visualizar e contribuir com algumas informações nas categorias a seguir:

-   Recursos da sala: Uma sala é composta por vários recursos. Inicialmente pensamos em: quantidade de cadeiras (para canhotos e destros), se possui e qual estado do projetor, estado do ar-condicionado, situação das lâmpadas e qualidade da acessibilidade. Será permitido que novos recursos sejam acrescentados conforme aplicações sejam criadas e coletem novas informações para alimentar o Salas.

-   Horários e disponibilidade: Assim como na aplicação web, a API permitirá consulta e reservas de horários nas salas do campus.

## Funcionamento
Para que todas essas funcionalidades sejam disponibilizadas pelo Salas, é necessário que ocorra um mapeamento virtual de todo o Campus. Para tal, juntaremos esforços com a coordenação da universidade, que possui plantas dos prédios do campus, e coletaremos manualmente informações sobre a geografia da universidade. Uma vez coletada essa informação, será possível agrupar conjuntos de salas nos seus respectivos blocos e prédios, para então fazer outra coleta de dados, agora sobre os recursos de cada sala. Depois de todo esse trabalho manual, teríamos a base para o funcionamento do Salas, para que os próximos dados sejam coletados não manualmente por desenvolvedores e funcionários, mas sim por aplicações que utilizam a API.

## Impacto
Através dessa plataforma, todos os aplicativos do crescente Smart Campus da UFCG poderão ter uma base única de dados sobre as salas da universidade. Ainda mais, os professores poderão imediatamente aproveitar de mais organização e planejamento de suas aulas. Nada de chegar em uma sala para ter a surpresa de ver 
um apresentação de PIBIC no seu horário de aula! O Salas é uma solução de curto, médio e longo prazo que ajudará a coordenação, o corpo docente e os desenvolvedores de soluções para o campus.

## Tecnologias
A aplicação será desenvolvida utilizando ReactJS para o desenvolvimento do FrontEnd e Node.js para o BackEnd. Além disso, usaremos o PostGreSQL e, claro, a plataforma GitHub para a integração do desenvolvimento.
