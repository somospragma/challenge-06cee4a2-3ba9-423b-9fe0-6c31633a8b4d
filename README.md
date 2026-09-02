# Implementación y gestión de versionamiento de código en un proyecto frontend

El equipo de desarrollo de un proyecto frontend con React necesita implementar y gestionar eficazmente el versionamiento de su código utilizando GIT. El objetivo es asegurar que el flujo de trabajo de desarrollo sea eficiente, que los cambios se manejen de manera ordenada y que las integraciones sean estables. El sistema debe permitir a los desarrolladores utilizar comandos básicos y avanzados de GIT para versionar sus piezas de código de manera adecuada.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Fundamentos de versionamiento de código |
| **Nivel** | senior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 4-6 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración inicial del repositorio

**Objetivo:** Configurar un repositorio de GIT y establecer la estrategia de branching para el proyecto.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Define una estrategia de branching adecuada para el proyecto.
- Configura un repositorio de GIT y aplica la estrategia de branching definida.

**Entregable:** Repositorio de GIT configurado con la estrategia de branching aplicada.

<details>
<summary>Pistas de conocimiento</summary>

- Identifica las ramas necesarias para el flujo de trabajo del proyecto.
- Considera las ventajas y desventajas de diferentes estrategias de branching.

</details>

### Fase 2: Uso de comandos básicos de GIT

**Objetivo:** Realizar operaciones básicas de GIT como commit, pull request, clone y merge.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Crea un commit con cambios significativos en tu proyecto.
- Realiza un pull request y describe los cambios realizados.
- Clona el repositorio en una nueva ubicación y realiza un merge de una rama secundaria.

**Entregable:** Commit realizado, pull request creado y merge completado.

<details>
<summary>Pistas de conocimiento</summary>

- Revisa la documentación de GIT para asegurarte de que estás utilizando los comandos correctamente.
- Considera cómo describir eficazmente tus cambios en el pull request.

</details>

### Fase 3: Uso de comandos avanzados de GIT

**Objetivo:** Utilizar comandos avanzados de GIT como stash, rebase, rm, reset y checkout.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Guarda temporalmente tus cambios utilizando stash.
- Realiza un rebase de una rama secundaria sobre la rama principal.
- Elimina un archivo del repositorio utilizando rm y reset.
- Crea una nueva rama y cambia a ella utilizando checkout.

**Entregable:** Operaciones avanzadas de GIT realizadas y documentadas.

<details>
<summary>Pistas de conocimiento</summary>

- Investiga los usos comunes de cada comando avanzado.
- Considera los posibles problemas que podrían surgir al utilizar estos comandos y cómo resolverlos.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un commit en GIT y por qué es importante?
- **paraQueSirve**: ¿Para qué sirve un pull request y cómo debe ser descrito?
- **comoSeUsa**: ¿Cómo se utiliza el comando rebase en GIT y en qué situaciones es útil?
- **erroresComunes**: ¿Cuáles son los errores comunes al utilizar el comando reset y cómo se pueden evitar?
- **queDecisionesImplica**: ¿Qué decisiones debes tomar al elegir una estrategia de branching para tu proyecto?

## Criterios de Evaluacion

- Configuración inicial del repositorio de GIT con estrategia de branching aplicada.
- Realización de operaciones básicas de GIT (commit, pull request, clone, merge).
- Uso de comandos avanzados de GIT (stash, rebase, rm, reset, checkout).
- Documentación clara y concisa de las operaciones realizadas.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
