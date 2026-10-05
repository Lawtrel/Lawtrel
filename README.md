# Leandro Alves dos Santos

**Graduando em Engenharia de Software na UNEB | Técnico em Automação pelo SENAI**

Desenvolvo APIs, aplicações web e projetos que conectam software e hardware. Busco **estágio ou vaga júnior em desenvolvimento**, com foco em backend e integração de sistemas. Disponível para oportunidades remotas no Brasil e presenciais ou híbridas em Alagoinhas e Salvador.

Atuo na **Tecno System EJ** com desenvolvimento fullstack e colaboração em equipe. Na **iniciação científica da UNEB**, investigo agentes baseados em LLMs para refatoração de testes de software.

[LinkedIn](https://www.linkedin.com/in/leandro-goncalvess/) · [ORCID](https://orcid.org/0009-0005-0819-0878)

## Backend e aplicações web

### [TecnoManager](https://github.com/Lawtrel/tecnomanager)

API REST de projetos, tarefas e membros de uma empresa júnior. Impede concluir projetos com tarefas pendentes e valida o vínculo entre tarefa e projeto nas atualizações.

**Java 21 · Spring Boot · JPA · PostgreSQL · Flyway · OpenAPI · JUnit · MockMvc**

Na [revisão com integração PostgreSQL](https://github.com/Lawtrel/tecnomanager/pull/2), **37 testes passaram em H2 e os mesmos 37 em PostgreSQL 16**, com migrações e empacotamento. Inclui teste de atualização de dados legados e restrições de status no banco. Consulte o PR para acompanhar a integração e o README para os limites de autenticação e concorrência.

### [BitFrost](https://github.com/Lawtrel/bitfrost)

Sistema de gestão de vales, clientes e transportadoras, desenvolvido em colaboração. API com autenticação JWT e permissões por cargo; interface com criação, processamento e exportação de vales em PDF.

**TypeScript · Node.js · Express · React · Prisma · PostgreSQL · Jest · Supertest · Vitest**

A [revisão dos fluxos e do PDF](https://github.com/Lawtrel/bitfrost/pull/15) passou com **302 testes de frontend, 57 de autenticação com banco simulado e 11 de integração com PostgreSQL**, além dos builds no CI. Fluxos principais e PDF também foram conferidos localmente. O histórico registra as contribuições de Lawtrel e Gui-ASA.

### [Frame-24](https://github.com/Lawtrel/frame-24)

Projeto acadêmico em equipe para gestão de cinemas, com API, interfaces web e persistência em uma estrutura de monorepo.

**TypeScript · NestJS · Next.js · Prisma · PostgreSQL · Turborepo**

## Automação e sistemas embarcados

| Projeto | Implementação no repositório | Tecnologias |
| --- | --- | --- |
| [BeatTime](https://github.com/Lawtrel/BeatTime) | Relógio com display OLED, LEDs e integração com um backend para Spotify. | C, Raspberry Pi Pico W, Node.js, HTTP |
| [Robotmotion](https://github.com/Lawtrel/robotMotion) | Pet eletrônico com estados, display OLED, persistência e interface web, desenvolvido em equipe. | C++, ESP8266, I2C, EEPROM |

Esses projetos mostram integração entre firmware, interfaces e comunicação. A revisão atual dos repositórios não inclui uma nova validação física em hardware.

## Fundamentos de computação

[Chip-8 Emulator](https://github.com/Lawtrel/Chip8-Emu): núcleo de emulação em TypeScript compartilhado entre navegador e terminal, com operações de CPU, memória e manipulação de bits. Tecnologias: Node.js, Vite e Canvas.

## Formação e conhecimentos

- **Engenharia de Software - UNEB:** em andamento, conclusão prevista para dezembro de 2027.
- **Técnico em Automação - SENAI:** concluído em 2022.
- **Backend e dados:** JavaScript, TypeScript, Node.js, Express, NestJS, Java, Spring Boot, APIs REST, MySQL, PostgreSQL, MongoDB e Prisma.
- **Interfaces:** React, Next.js, React Native, HTML e CSS.
- **Ferramentas e qualidade:** Git, GitHub, Docker, Linux, testes automatizados e pesquisa em testes de software.
- **Sistemas embarcados:** projetos com C/C++, ESP8266, Raspberry Pi Pico W, GPIO e I2C.

Os projetos incluem trabalhos acadêmicos, colaboração e experimentos. Os READMEs explicam execução, escopo e limitações; resultados de testes descrevem a versão verificada e não equivalem a uso em produção.
