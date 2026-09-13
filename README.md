# MLI-Knot-Cursos Showcase

> **Status:** vitrine pública sanitizada de um protótipo funcional privado/local.
> **Projeto fonte:** `MLI-Knot-Cursos`, mantido privado/local.  
> **Regra de publicação:** somente documentação, exemplos e imagens revisados e seguros entram nesta superfície.

<div align="center">

<img src="assets/matrix-inspired-banner.gif" width="100%" alt="Cyber banner" />

</div>

> Public sanitized showcase of the current functional prototype flow of **MLI-Knot-Cursos**.
> Vitrine pública sanitizada do fluxo atualmente implementado no protótipo **MLI-Knot-Cursos**.

![Status](https://img.shields.io/badge/status-public%20showcase-blue)
![Scope](https://img.shields.io/badge/scope-sanitized%20documentation-darkgreen)
![Current functional baseline](https://img.shields.io/badge/current%20functional%20baseline-100%25-brightgreen)
![Source](https://img.shields.io/badge/source%20project-private-orange)
![GitHub stars](https://img.shields.io/github/stars/proftectiagocosta-hash/MLI-Knot-Cursos-Showcase?style=flat&label=stars)
![README views](https://hits.sh/github.com/proftectiagocosta-hash/MLI-Knot-Cursos-Showcase.svg?label=README%20views)
![Language](https://img.shields.io/badge/language-PT--BR%20%7C%20EN-informational)

---

## Português

### O que é

**MLI-Knot-Cursos Showcase** é a vitrine pública e sanitizada do projeto privado **MLI-Knot-Cursos**.

A fonte atual é um **protótipo funcional em evolução** de uma experiência educacional baseada em catálogo, inscrição local, aulas sequenciais, progresso, retomada de estudo e fluxo de certificado.

Esta vitrine descreve comportamentos verificáveis do protótipo sem publicar seu código-fonte, dados internos, conteúdo privado de cursos ou material de desenvolvimento não revisado.

### Fluxo atualmente representado no protótipo

```text
catálogo
-> inscrição local
-> aulas
-> progresso
-> continuar estudo
-> conclusão em 100%
-> fluxo de certificado
```

O protótipo atual já representa:

1. catálogo e detalhe de cursos;
2. inscrição armazenada localmente no navegador;
3. aulas organizadas em sequência;
4. controle progressivo de acesso às aulas;
5. marcação de aulas concluídas;
6. cálculo de percentual de progresso;
7. ação para continuar a partir da próxima aula útil;
8. liberação do fluxo de certificado após 100% de conclusão;
9. prévia de certificado;
10. geração de certificado em PDF;
11. versão apropriada para impressão.

Determinadas configurações do protótipo também representam, de forma **local e simulada**, a necessidade de aquisição do certificado antes de sua liberação.

Isso não corresponde a pagamento real nem a integração financeira.

### Marcador de progresso

O README do projeto fonte enumera **11 funcionalidades já trabalhadas** no protótipo atual. Todas as 11 pertencem à baseline funcional atualmente declarada.

**Marcador público da baseline funcional documentada atual: 11/11 = 100%.**

Esse percentual significa somente **100% da baseline funcional atualmente enumerada no README fonte**. Não significa produto completo, esforço de engenharia concluído, prontidão para produção ou conclusão dos próximos passos. Backend real, autenticação, pagamento, emissão oficial de certificado e outras limitações continuam fora dessa baseline.

### Persistência do protótipo

Inscrição, progresso e estados relacionados ao certificado são representados localmente no navegador durante esta fase.

Essa persistência é adequada à prototipação e não deve ser interpretada como conta de usuário, banco de dados centralizado ou backend de produção.

### Limites atuais

O projeto fonte ainda é um protótipo privado/local e não deve ser tratado como plataforma pronta para produção.

Não existem nesta fase:

- backend real de produção;
- banco de dados centralizado;
- autenticação real de usuários;
- pagamento real;
- validação financeira;
- emissão oficial de certificados;
- registro externo de certificados;
- painel administrativo completo.

Os certificados representados pelo protótipo são artefatos de demonstração e não possuem status oficial.

### Escopo público

Esta vitrine pode conter:

- descrição sanitizada do fluxo funcional;
- documentação de progresso;
- documentação do fluxo de certificado;
- diagramas conceituais;
- exemplos fictícios;
- roadmap público;
- screenshots públicos seguros, quando explicitamente revisados.

Ela não contém:

- código-fonte privado;
- dados reais de alunos;
- contas reais;
- conteúdo privado de cursos;
- credenciais ou chaves;
- dados de pagamento;
- configurações internas desnecessárias à compreensão pública;
- registros oficiais de certificados.

### Documentação

- [`docs/overview.md`](docs/overview.md)
- [`docs/public-boundary.md`](docs/public-boundary.md)
- [`docs/course-flow.md`](docs/course-flow.md)
- [`docs/student-progress.md`](docs/student-progress.md)
- [`docs/certificate-flow.md`](docs/certificate-flow.md)
- [`docs/roadmap.md`](docs/roadmap.md)
- [`docs/screenshots/README.md`](docs/screenshots/README.md)

### Licença e aviso

- [LICENSE.md](LICENSE.md)
- [NOTICE.md](NOTICE.md)

### Relação com o projeto principal

O **MLI-Knot-Cursos** permanece privado/local.

Esta vitrine apresenta apenas uma camada pública sanitizada do que já pode ser explicado com segurança.

---

## English

### What it is

**MLI-Knot-Cursos Showcase** is the public sanitized surface of the private **MLI-Knot-Cursos** project.

The current source is an evolving **functional prototype** of an educational experience built around a course catalog, local enrollment, sequential lessons, progress tracking, study resumption, and a certificate flow.

This repository documents verifiable prototype behavior without publishing private source code, internal data, private course material, or unrevised development content.

### Currently represented prototype flow

```text
catalog
-> local enrollment
-> lessons
-> progress
-> continue studying
-> 100% completion
-> certificate flow
```

The prototype currently represents:

- course catalog and course-detail views;
- local enrollment state;
- sequential lesson access;
- completed-lesson tracking;
- progress percentage;
- continuation from the next useful lesson;
- certificate gating after 100% completion;
- certificate preview;
- PDF generation;
- printable certificate view.

Some prototype configurations also model a **local simulated certificate-acquisition state** before certificate release.

This is not a real payment integration.

### Progress marker

The source-project README enumerates **11 functionalities already worked on** in the current prototype, and all 11 belong to the currently declared functional baseline.

**Current documented functional-baseline marker: 11/11 = 100%.**

This percentage means only 100% of the functional baseline currently enumerated by the source README. It is not product completion, engineering-effort completion, production readiness, or completion of future steps.

### Current boundaries

The source project remains a private/local prototype and is not a production platform.

It currently has no:

- production backend;
- centralized database;
- real user authentication;
- real payment processing;
- financial validation;
- official certificate issuance;
- external certificate registry.

Prototype certificates are demonstration artifacts and have no official status.

### Documentation

- [`docs/overview.md`](docs/overview.md)
- [`docs/public-boundary.md`](docs/public-boundary.md)
- [`docs/course-flow.md`](docs/course-flow.md)
- [`docs/student-progress.md`](docs/student-progress.md)
- [`docs/certificate-flow.md`](docs/certificate-flow.md)
- [`docs/roadmap.md`](docs/roadmap.md)
- [`docs/screenshots/README.md`](docs/screenshots/README.md)

### Public boundary

This repository contains sanitized documentation only.

Private source code, real student data, private course content, credentials, payment data, and unrevised internal material remain outside the public surface.

---

## Public status

```text
Repository type: public sanitized showcase
Source project: MLI-Knot-Cursos
Source project state: functional private/local prototype
Source project visibility: private/local
Current documented functional baseline items: 11
Baseline items currently declared as worked: 11
Current functional-baseline marker: 100%
Product completion claimed: no
Engineering effort completion claimed: no
Production readiness claimed: no
Code included here: no
Sensitive material included here: no
Production system represented here: no
```

---

## Related public resources

- [Tiago Costa / Tendoshk profile](https://github.com/proftectiagocosta-hash)
- [Project Map](https://github.com/proftectiagocosta-hash/proftectiagocosta-hash/blob/main/PROJECT_MAP.md)
- [MLI-Knot Mind Showcase](https://github.com/proftectiagocosta-hash/MLI-Knot-Mind-Showcase)
