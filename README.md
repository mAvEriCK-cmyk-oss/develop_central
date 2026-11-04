# SENATI — Prácticas Ágiles con GitHub (Semana 12)

Aplicación web sobre **Scrum, Kanban y Extreme Programming (XP)** para el laboratorio de Gestión de Proyectos y Prácticas Ágiles del instructor Gino Nibin.

## Aplicación
- `index.html`: navegación, fundamentos ágiles, guía y tablero Kanban interactivo.
- `script.js`: agregar tareas, moverlas entre cuatro columnas, validar títulos, confirmar eliminación y guardar cambios localmente.
- `styles.css`: presentación visual y diseño adaptable.

**Cómo abrir:** descarga los tres archivos en una misma carpeta y abre `index.html` con un navegador moderno. Bootstrap se carga desde CDN; se necesita conexión para sus estilos y el modal.

## Repositorio y flujo
- Repositorio central: https://github.com/mAvEriCK-cmyk-oss/develop_central
- Rama de integración: `develop`
- Milestone: [Sprint 1 – Mejoras a la App Ágil](https://github.com/mAvEriCK-cmyk-oss/develop_central/milestone/1)
- Historias de usuario: [Issues #1 a #6](https://github.com/mAvEriCK-cmyk-oss/develop_central/issues)
- Revisión de documentación: [PR #7](https://github.com/mAvEriCK-cmyk-oss/develop_central/pull/7)
- Mejora del tablero: [PR #8](https://github.com/mAvEriCK-cmyk-oss/develop_central/pull/8)

## Proceso recomendado para el equipo
1. Cada integrante hace fork de `develop_central` y, si corresponde, lo renombra `develop_personaN`.
2. Se crea o sincroniza una rama `develop` en el fork.
3. Se realiza el cambio en `feature/US-XX-descripcion`, partiendo de `develop`.
4. Se abre un Pull Request hacia `develop_central/develop`, con enlace a la Issue.
5. Otro integrante revisa los cambios, ejecuta pruebas y aprueba.
6. Se hace merge y se mueve el ítem a Done en GitHub Projects.

## Definition of Done
- Historia de usuario documentada y asociada a Sprint 1.
- Cambio real en los archivos del proyecto.
- Aplicación funcionando en navegador.
- Pull Request revisado y aprobado por otra persona.
- Merge efectuado hacia `develop`.
- URL y captura de pantalla real como evidencia.

## Nota de verificación
Las Issues, Milestone y PRs se publicaron en GitHub. **Los PRs no se consideran aprobados ni mergeados hasta que aparezca ese estado real.** Las capturas y forks deben corresponder a las cuentas del equipo.
