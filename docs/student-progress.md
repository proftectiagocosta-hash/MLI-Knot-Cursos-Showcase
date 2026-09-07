# Student progress / Progresso do aluno

This document describes the public sanitized progress model currently implemented in the private/local **MLI-Knot-Cursos** prototype.

Este documento descreve o modelo público e sanitizado de progresso atualmente implementado no protótipo privado/local **MLI-Knot-Cursos**.

---

## Purpose / Propósito

The progress layer shows what has been completed, what remains pending, and where study should continue.

A camada de progresso mostra o que já foi concluído, o que permanece pendente e de onde o estudo deve continuar.

---

## Prototype state / Estado de protótipo

Enrollment and course progress are stored locally in the browser during this prototype phase.

A inscrição e o progresso do curso são armazenados localmente no navegador nesta fase de protótipo.

There is no production account system or centralized student database behind this behavior.

Não existe sistema de contas em produção nem banco de dados centralizado de alunos por trás desse comportamento.

---

## Current progress behavior / Comportamento atual de progresso

The prototype currently represents:

- enrollment state;
- completed lessons;
- percentage completed;
- course status;
- next incomplete lesson;
- sequential access to lessons;
- continuation from the next useful point;
- certificate eligibility after full completion.

O protótipo atualmente representa:

- estado de inscrição;
- aulas concluídas;
- percentual concluído;
- status do curso;
- próxima aula não concluída;
- acesso sequencial às aulas;
- retomada a partir do próximo ponto útil;
- elegibilidade para certificado após conclusão total.

---

## Continue studying / Continuar estudo

If no lesson has been completed, the prototype directs the learner to the first available lesson.

Se nenhuma aula foi concluída, o protótipo direciona o estudante para a primeira aula disponível.

After progress begins, the continue action selects the next incomplete lesson.

Depois que o progresso começa, a ação de continuar seleciona a próxima aula não concluída.

At 100% completion, the learning flow reaches the certificate stage.

Ao atingir 100% de conclusão, o fluxo de estudo chega à etapa de certificado.

---

## Current boundaries / Limites atuais

This showcase contains no real student records.

Esta vitrine não contém registros reais de alunos.

All described progress behavior belongs to a local functional prototype and must not be interpreted as production student tracking.

Todo o comportamento de progresso descrito pertence a um protótipo funcional local e não deve ser interpretado como rastreamento de alunos em produção.
