# Health Monitor - Monitoramento de Batimentos Cardíacos
Este repositório é dedicado à documentação do projeto Health Monitor - Monitoramento de Batimentos Cardíacos. O sistema proposto visa oferecer uma solução IoT integrada a um aplicativo móvel para o monitoramento de batimentos cardíacos e níveis de oxigênio no sangue, focado principalmente em pessoas com problemas cardiovasculares. A documentação inclui detalhes técnicos, arquitetura e guias de uso, permitindo uma visão abrangente do projeto.

Para obter mais detalhes sobre o desenvolvimento de funcionalidades e o código-fonte do sistema, consulte os links úteis abaixo.

## Funcionalidades Principais
* **Monitoramento em Tempo Real:** O dispositivo coleta continuamente os dados de frequência cardíaca e níveis de oxigênio no sangue, garantindo uma vigilância constante da saúde do usuário.
* **Alertas Automáticos:** Em caso de detecção de irregularidades críticas, o sistema alerta automaticamente os monitores do paciente, permitindo uma intervenção rápida.
* **Acompanhamento Remoto:** Permita que médicos e familiares monitorem sua saúde à distância, oferecendo segurança adicional.

## Licença
Este projeto está licenciado sob a [Licença MIT](LICENSE).

## Stack utilizada
O projeto como um todo faz uso das seguintes tecnologias:

![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white)&nbsp;
![Jasmine](https://img.shields.io/badge/jasmine-%238A4182?style=for-the-badge&logo=jasmine)
![Karma](https://img.shields.io/badge/Karma-%23027E6F?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)&nbsp;
![Spring Boot](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)&nbsp;
![JUnit](https://img.shields.io/badge/junit5-%2325A162?style=for-the-badge&logo=junit5&logoColor=%23FFFFFF)
![Mockito](https://img.shields.io/badge/mockito-%23800000?style=for-the-badge&logo=mockito&logoColor=%23FFFFFF)
![Arduino](https://img.shields.io/badge/arduino-%2300878F?style=for-the-badge&logo=arduino&logoColor=%23FFFFFF)
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)&nbsp;
![AWS](https://img.shields.io/badge/amazonwebservices-%23232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=%23FFFFFF)


* **Front-end Ionic:** framework open-source para desenvolver aplicativos móveis, web e desktop com base no Angular e tecnologias web como HTML, CSS e JavaScript.
* **Front-end Jasmine:** framework de teste para JavaScript que permite escrever testes de unidade de forma simples e eficiente, garantindo a qualidade do código frontend.
* **Front-end Karma:** ferramenta de execução de testes JavaScript. Geralmente usada com Jasmine, roda os testes em navegadores reais.
* **Back-end Java:** linguagem de programação amplamente utilizada, conhecida por sua robustez e portabilidade, orientada a objetos.
* **Back-end Spring Boot:** framework para construir aplicações Java de forma rápida.
* **Back-end JUnit:** framework para escrever testes unitários em Java. Ele ajuda a verificar a funcionalidade do backend e garantir que o código funcione como esperado.
* **Back-end Mockito:** framework de simulação (mocking) para testes em Java. É usado para criar objetos simulados para testar interações entre diferentes partes do sistema.
* **IOT Arduino:** plataforma de prototipagem open-source baseada em hardware e software. No projeto, é utilizado para IoT com Esp32, para controle e coleta de dados do sensor MAX30100.
* **Banco de dados PostgreSQL:** sistema de banco de dados relacional avançado e open-source, utilizado no projeto para armazenamento e gerenciamento de dados.
* **Virtualização Docker:** plataforma para criar, gerenciar e executar containers. Ajuda a garantir que o ambiente de desenvolvimento e produção sejam consistentes.
* **Cloud AWS:** plataforma de serviços de computação em nuvem que oferece infraestrutura e ferramentas como EC2, utilizada no desenvolvimento. No projeto, é usada para deploy e hospedagem.

## Ferramentas de Desenvolvimento
![Githubactions](https://img.shields.io/badge/githubactions-%232088FF?style=for-the-badge&logo=githubactions&logoColor=%23FFFFFF)
![SonarCloud](https://img.shields.io/badge/sonarcloud-%234E9BCD?style=for-the-badge&logo=sonarcloud)
![Grafana](https://img.shields.io/badge/grafana-%23F46800?style=for-the-badge&logo=grafana&logoColor=%23FFFFFF)
![Prometheus](https://img.shields.io/badge/prometheus-%23E6522C?style=for-the-badge&logo=prometheus&logoColor=%23FFFFFF)

- **SonarCloud Code Review:** plataforma de análise estática de código que identifica vulnerabilidades, problemas de segurança e má qualidade de código. É usada para realizar code review automatizado e manter a qualidade do código no projeto.
- **Github Actions (CD/CD):** ferramenta de automação que permite criar pipelines de integração contínua (CI) e entrega contínua (CD).
- **Grafana:** plataforma de visualização e monitoramento de dados. No projeto, é usada para criar dashboards que exibem métricas de desempenho e outras informações relevantes para o monitoramento.
- **Prometheus:** ferramenta de monitoramento e alerta para sistemas distribuídos. Ele coleta métricas em tempo real e fornece os dados necessários para o Grafana gerar gráficos e dashboards.

## Links
Aqui estão os links para os outros repositórios, ferramentas relacionadas ao projeto e a apk do aplicativo:

### APK
- [APK](https://drive.google.com/drive/u/1/folders/18BauIdDIypA8bfIgAjnFnEx9DDYZj5NU) - Aplicativo para Android

### Documentação
- [Wiki](https://github.com/Gabriel7fs/health-monitor/wiki) - Informações detalhadas e guias do projeto.
- [Documentação da API (Swagger)](http://18.191.189.164/api/swagger-ui/index.html#/) - Documentação da API.

### Repositórios
- [Backend](https://github.com/Gabriel7fs/back-health-monitor) - Repositório do back-end
- [Frontend](https://github.com/Gabriel7fs/frontend-health-monitor) - Repositório do front-end
- [IOT](https://github.com/Gabriel7fs/health-monitor-iot) - Repositório do código de IoT

### Monitoramento
- [Grafana](http://18.191.189.164:3000/d/OS7-NUiGz/spring-boot-statistics-and-endpoint-metrics?orgId=1&refresh=5s) - Painel de estatísticas do Spring Boot e métricas de Endpoint. (usuário: admin, senha: admin)
- [SonarCloud - BackEnd](https://sonarcloud.io/summary/new_code?id=Gabriel7fs_back-health-monitor) - SonarCloud do Back-end.
- [SonarCloud - FrontEnd](https://sonarcloud.io/summary/overall?id=Gabriel7fs_frontend-health-monitor&branch=main) - SonarCloud do Front-end.

### Ferramentas de Colaboração

- [Jira](https://wordswap.atlassian.net/jira/software/projects/SCRUM/boards/1) - Board do Jira para acompanhamento das tarefas do projeto.
- [Figma](https://www.figma.com/proto/SRugCUC42ZkaDxU8i3bWDz/Health-Monitor?node-id=0-1&t=SfVAw0eg87TpCmve-1) - Mockups do sistema no Figma.
