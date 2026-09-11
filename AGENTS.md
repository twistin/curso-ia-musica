# AGENTS.md — Curso IA + Música

Instrucciones operativas para agentes (Codex) que trabajen en este repositorio.
Léelas al inicio de cada tarea y respétalas.

## Qué es este repo
Repositorio personal de formación en IA aplicada a la música: base de ML generalista
reorientada hacia el audio, SuperCollider, el live coding y la docencia. Organizado en
fases (0 a 4). Ver `README.md` para el arco completo.

## Idioma
Todo el contenido —READMEs, notas, comentarios de código, mensajes de commit— en **español**.

## Dónde va cada cosa
- Código Python de una fase → `fase-N.../notebooks/`.
- Código SuperCollider (`.scd`) → `fase-N.../sc/`.
- Apuntes de una fase → `fase-N.../notas/`.
- El resultado que cierra una fase → `fase-N.../entregable/`.
- Diario transversal de aprendizaje → `notas/diario.md` (una entrada por sesión).
- Nunca crear material fuera de la fase que corresponde.

## Convenciones
- Respeta `.gitignore`: NO añadas audio (`*.wav`, etc.) ni modelos (`*.pt`, `*.ts`, ...)
  al control de versiones. Son pesados y van fuera del repo.
- Usa como fuentes los enlaces de `recursos/enlaces.md`. No inventes recursos, cursos
  ni URLs; si falta algo, indícalo en la nota en vez de fabricarlo.
- Los notebooks deben ser ejecutables y comentados, pensados también como material docente.
- Al completar un entregable, marca su checkbox en el `README.md` de la fase y en la
  tabla de progreso del `README.md` raíz.
- Prosa técnica directa, sin relleno.

## Commits
- Mensajes claros en español, en imperativo, acotados a un cambio: p. ej.
  `Añade notebook de features de audio (Fase 1)`.
- Un commit = una unidad de trabajo coherente. Nada de commits gigantes que mezclan fases.

## Alcance
- Céntrate en la tarea pedida. Si detectas trabajo adicional útil, propónlo en la
  respuesta o en `notas/diario.md`, no lo ejecutes por tu cuenta.
