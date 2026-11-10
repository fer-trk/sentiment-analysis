# Guía de contribución

## Preparar un cambio

- Define el resultado esperado y cómo verificarlo.
- Crea una rama desde `dev` con un nombre descriptivo, por ejemplo `fix/api-startup`.
- Usa OpenSpec cuando cambien un contrato de API, el flujo de revisión, los datos o la evaluación del modelo. Mantén los escenarios y criterios verificables.

## Abrir el pull request

- Abre un PR hacia `dev` por cada corrección. Puedes usar un borrador para acordar el alcance.
- Incluye el cambio, el motivo, los criterios de aceptación y los resultados de las pruebas. Enlaza la especificación si existe.
- Comprueba el resultado de GitHub Actions antes de integrar. Ejecuta localmente las pruebas del área modificada y `git diff --check`.
- Usa títulos y commits descriptivos. Los cambios listos se integran por squash merge. `main` se reserva para versiones estables.

## Datos y secretos

Mantén fuera de Git las credenciales, los archivos `.env` locales, los datos personales y los comentarios reales que no estén autorizados para redistribución.
