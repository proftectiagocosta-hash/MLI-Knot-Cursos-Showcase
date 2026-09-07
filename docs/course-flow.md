# Course flow / Fluxo de cursos

This document describes the public sanitized educational flow currently represented by the private/local **MLI-Knot-Cursos** prototype.

Este documento descreve o fluxo educacional público e sanitizado atualmente representado pelo protótipo privado/local **MLI-Knot-Cursos**.

---

## Main flow / Fluxo principal

```text
catalog -> enrollment -> lessons -> progress -> continue studying -> certificate
```

```text
catálogo -> inscrição -> aulas -> progresso -> continuar estudo -> certificado
```

---

## 1. Catalog / Catálogo

The prototype presents a course catalog and allows navigation to a course-detail view.

O protótipo apresenta um catálogo de cursos e permite navegar para o detalhe de cada curso.

The public showcase describes this behavior without publishing the private course dataset or internal implementation.

A vitrine descreve esse comportamento sem publicar o conjunto privado de dados dos cursos ou sua implementação interna.

---

## 2. Enrollment / Inscrição

Enrollment is currently represented as local prototype state in the browser.

A inscrição é atualmente representada como estado local de protótipo no navegador.

It is not backed by a real account, authentication system, or production backend.

Ela não utiliza conta real, sistema real de autenticação ou backend de produção.

---

## 3. Lessons / Aulas

Lessons are organized in sequence.

As aulas são organizadas em sequência.

The prototype controls lesson access progressively: the first lesson can be started after enrollment, and later lessons depend on progress through the sequence.

O protótipo controla o acesso às aulas de forma progressiva: a primeira aula pode ser iniciada após a inscrição, e as aulas seguintes dependem do progresso na sequência.

---

## 4. Progress / Progresso

Completed lessons are recorded locally.

As aulas concluídas são registradas localmente.

The prototype calculates course completion as a percentage based on completed lessons.

O protótipo calcula a conclusão do curso em percentual com base nas aulas concluídas.

---

## 5. Continue studying / Continuar estudo

The continue action determines the next useful lesson from the current local progress state.

A ação de continuar estudo determina a próxima aula útil a partir do estado local de progresso.

This allows the prototype to resume the learner at the next incomplete point.

Isso permite que o protótipo retome o estudante no próximo ponto ainda não concluído.

---

## 6. Certificate flow / Fluxo de certificado

Certificate access is gated by course completion.

O acesso ao certificado depende da conclusão do curso.

```text
course progress = 100% -> certificate flow becomes eligible
```

```text
progresso do curso = 100% -> fluxo de certificado torna-se elegível
```

The prototype includes certificate preview, PDF generation, and a printable view.

O protótipo inclui prévia de certificado, geração em PDF e uma visualização para impressão.

Some prototype configurations also model a local simulated acquisition state for certificate access.

Algumas configurações do protótipo também representam um estado local e simulado de aquisição para acesso ao certificado.

This does not represent real payment processing or official certificate issuance.

Isso não representa processamento real de pagamento nem emissão oficial de certificado.
