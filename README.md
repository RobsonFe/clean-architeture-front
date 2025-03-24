# Clean Architecture - Front-End

Este projeto foi gerado usando o [Angular CLI](https://github.com/angular/angular-cli) versão 19.2.4.

## Descrição:

O objetivo desse projeto é o estudo da arquitetra limpa no Front-End, onde aplicaremos os conceitos e fundamentos da arquietura limpa, de uma forma onde seja um sistema com o máximo de desaclopamento para melhor manutenção e escalabilidade da aplicação, onde esses conceitos e fundamentos, embora nesse projeto seja feito em Angular, possa ser utilizado em outros frameworks, ou até mesmo esse projeto possa ser atualizado para outro framework, sem alterar as bases e fundamentos do négocio.

A inspiração e base desse projeto foi feita após leitura do artigo do `The Pragmatic Engineer` e `Daily Dev`.

Segue o link em questão para maiores detalhes da implementação.

- [Artigo 1]("https://thepragmaticengineer.hashnode.dev/clean-architecture-em-aplicacoes-frontend-utilizando-angular")

- [Artigo 2]("https://dev.to/bespoyasov/clean-architecture-on-frontend-4311?ref=dailydev")

## **Etapas Iniciais**

- Essa etapa inicial é para configuração e instalação do projeto.

## Servidor de desenvolvimento

Para iniciar um servidor de desenvolvimento local, execute:

```bash
ng serve
```

Após iniciar o servidor, abra seu navegador e navegue até `http://localhost:4200/`. A aplicação será recarregada automaticamente sempre que você modificar qualquer um dos arquivos-fonte.

## Geração de código

O Angular CLI inclui ferramentas poderosas para geração de código. Para gerar um novo componente, execute:

```bash
ng generate component nome-do-componente
```

Para obter uma lista completa dos esquemas disponíveis (como `components`, `directives` ou `pipes`), execute:

```bash
ng generate --help
```

## Construção

Para compilar o projeto, execute:

```bash
ng build
```

Isso compilará seu projeto e armazenará os artefatos de build no diretório `dist/`. Por padrão, a compilação para produção otimiza sua aplicação para desempenho e velocidade.

## Executando testes unitários

Para executar testes unitários com o [Karma](https://karma-runner.github.io), use o seguinte comando:

```bash
ng test
```

## Executando testes de ponta a ponta (end-to-end)

Para executar testes de ponta a ponta (e2e), execute:

```bash
ng e2e
```

O Angular CLI não inclui um framework de testes de ponta a ponta por padrão. Você pode escolher um que melhor atenda às suas necessidades.

## Recursos adicionais

Para mais informações sobre o uso do Angular CLI, incluindo uma referência detalhada de comandos, visite a página [Visão geral e referência de comandos do Angular CLI](https://angular.dev/tools/cli).
