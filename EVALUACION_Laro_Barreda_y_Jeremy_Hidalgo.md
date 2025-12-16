# Evaluación RA2 - Entornos de Desarrollo

**Estudiantes:** Laro Barreda y Jeremy Hidalgo  
**Fecha de evaluación:** 16 de diciembre de 2025  
**Evaluador:** [Nombre del profesor]

---

## Resumen Ejecutivo

**Puntuación provisional:** **9.00/10** ✅

**Estado:** Excelente trabajo integral con documentación extensa y múltiples lenguajes implementados.

**Commits recientes (diciembre 2025):** 7 commits entre el 10 de diciembre mostrando trabajo final intensivo ("imagenes arregladas", "Fix image syntax", "cambios nuevos", "segundo cambio", "onboard hecho"). El equipo realizó la mayoría del trabajo en las últimas semanas, cumpliendo con todos los requisitos de manera exhaustiva.

**Evidencia cuantitativa:**
- **Documentación:** 1158 líneas, 5310 palabras en IDE_ONBOARDING_GUIDE.md
- **Capturas:** 27 imágenes en markdown + 34 screenshots en carpeta
- **Patrones de uso IDE:** 51 referencias a comandos de ejecución/depuración (F5, Ctrl+F5, dotnet run, Debug)
- **Lenguajes implementados:** C#, Java, Python, F# (4 lenguajes completos)
- **IDEs documentados:** Visual Studio Code y Visual Studio (ambos completos)

---

## Evaluación Detallada por Criterios

### a) Instalación y Configuración (9/10)

**Puntuación:** 1.80/2.00

**Fortalezas:**
- ✅ **VS Code:** Instalación documentada paso a paso con 8 pasos detallados desde descarga hasta verificación, incluyendo capturas de pantalla de cada fase (screenshot1-3)
- ✅ **Visual Studio:** Proceso completo documentado con selección de cargas de trabajo, componentes opcionales, y verificación desde el instalador (screenshot62, 64, 65, 69)
- ✅ **.NET SDK:** Instalación documentada desde la página oficial con verificación mediante `dotnet --version` y `dotnet --info` (screenshots 24-28)
- ✅ **34 screenshots** que validan todos los procesos de instalación y configuración
- ✅ Verificaciones sistemáticas después de cada instalación

**Áreas de mejora:**
- ⚠️ Podrían incluir troubleshooting específico para problemas comunes durante la instalación
- ⚠️ Las fechas V0 y V1 en el encabezado no están completadas

**Comentarios:**
La documentación de instalación es excepcionalmente detallada, con pasos numerados claramente y capturas que validan cada fase. El proceso está diseñado para que cualquier nuevo desarrollador pueda replicarlo sin dificultad.

---

### b) Instalación y Gestión de Módulos/Extensiones (8.5/10)

**Puntuación:** 1.70/2.00

**Fortalezas:**
- ✅ **C# Dev Kit:** Instalación documentada con pasos específicos (Ctrl+Shift+X, búsqueda, instalación) - screenshots 30-31
- ✅ **Extensiones documentadas:** Palenight Theme, Better Comments, Prettier, indent-rainbow
- ✅ **Ionide para F#:** Proceso completo de instalación y verificación
- ✅ **Java Extension Pack:** Mencionado en configuraciones recomendadas
- ✅ Capturas de pantalla mostrando el proceso de instalación desde el Marketplace

**Áreas de mejora:**
- ⚠️ Falta documentar explícitamente cómo desinstalar o deshabilitar extensiones
- ⚠️ No se menciona la gestión de versiones de extensiones o actualizaciones

**Comentarios:**
Excelente cobertura de extensiones para múltiples lenguajes. Cada extensión tiene su propósito claramente definido y el proceso de instalación está bien documentado visualmente.

---

### c) Personalización del Entorno (9.5/10)

**Puntuación:** 1.90/2.00

**Fortalezas:**
- ✅ **Temas:** Palenight Theme instalado y documentado con captura (screenshot8)
- ✅ **Better Comments:** Extensión para mejorar visualización de comentarios (screenshot9)
- ✅ **Atajos de teclado:** Lista completa documentada (Ctrl+F5, Ctrl+Shift+P, Ctrl+,, Alt+↑/↓, F12, Shift+Alt+F)
- ✅ **Editor settings:** 
  - `editor.formatOnSave: true` documentado con captura (screenshot22)
  - `editor.wordWrap: "on"` para evitar scroll horizontal (screenshot22)
- ✅ **Terminal integrada:** PowerShell configurado como predeterminado con perfil personalizado completo
- ✅ **Configuración de perfil PowerShell Dev:** Ejemplo avanzado con variables de entorno (DOTNET_ENVIRONMENT), PATH personalizado, icono y color
- ✅ Código de configuración JSON completo y funcional

**Áreas de mejora:**
- ⚠️ No se menciona si probaron fuentes personalizadas (Fira Code, JetBrains Mono)
- ⚠️ No hay capturas mostrando temas de iconos

**Comentarios:**
Personalización muy completa y profesional. La configuración del perfil de terminal PowerShell muestra comprensión avanzada del sistema. El formateo automático y word wrap son configuraciones esenciales bien documentadas.

---

### d) Uso del Depurador (No evaluado en este criterio)

*Criterio integrado en criterios e) y f)*

---

### e) Uso de Ejecutables de Diferentes Lenguajes (9/10)

**Puntuación:** 1.80/2.00

**Fortalezas:**
- ✅ **C#:** 
  - Proyecto HolaMundo completo con namespace, clase Program, método Main
  - Código con función `MostrarMensaje()` (implícito en flujo de trabajo documentado)
  - Ejecución mediante `dotnet run`
  - Debugging completo documentado: breakpoints (F9), Step Over (F10), Step Into (F11), Step Out (Shift+F11), Variables/Watch
- ✅ **Java:** 
  - Clase `HolaMundo` completa con método `mensaje(String mensaje)`
  - Compilación documentada: `javac HolaMundo.java`
  - Ejecución documentada: `java HolaMundo`
  - Salida esperada mostrada: "hello Laro" / "hello harold"
- ✅ **Python:** Mencionado con configuraciones específicas (Pylint, Black formatter, venv)
- ✅ **F#:** 
  - Proyecto completo con `dotnet new console -lang "F#"`
  - Código funcional: `printfn "¡F# funcionando correctamente en VS Code!"`
  - Ejecución mediante `dotnet run`
  - Debugging configurado con launch.json
- ✅ **Ejecución desde IDE:** 51 referencias a comandos IDE (F5, Ctrl+F5, Debug) - no usan CLI externa
- ✅ Documentación exhaustiva de debugging: breakpoints, step over/into/out, console REPL, múltiples objetivos

**Áreas de mejora:**
- ⚠️ Python: solo aparece en configuraciones, no hay código de ejemplo ejecutado
- ⚠️ No hay capturas mostrando la ejecución real de cada lenguaje

**Comentarios:**
Implementación sobresaliente de 4 lenguajes (C#, Java, Python configurado, F#). El código Java es funcional y didáctico. La documentación de debugging es de nivel profesional, cubriendo conceptos avanzados como REPL, múltiples targets, y configuración de launch.json.

---

### f) Uso de Ejecutables en Diferentes IDEs (9/10)

**Puntuación:** 1.80/2.00

**Fortalezas:**
- ✅ **Visual Studio Code:**
  - Navegación documentada: barra de actividades, barra lateral, grupo de edición, panel, barra de estado
  - Paleta de comandos (Ctrl+Shift+P) con ejemplos prácticos
  - Gestión de archivos y carpetas
  - Terminal integrada con PowerShell personalizado
  - Debugging completo: launch.json, configuración con Copilot, REPL
- ✅ **Visual Studio:**
  - Instalación completa con selección de cargas de trabajo
  - Creación de proyecto C# documentada paso a paso
  - Debugging avanzado: breakpoints (incluso condicionales), inspección de variables, visualizadores
  - Ventanas de depuración: Automático (Ctrl+Alt+V, A), Variables locales (Alt+4)
  - Compilación: Ctrl+Shift+B y ejecución F5
  - Flujo completo: creación, compilación, debugging
- ✅ Comparación implícita en CONCLUSIONES: VS Code preferido (10/10) vs Visual Studio (7/10)
- ✅ Ambos IDEs tienen secciones extensas y bien estructuradas

**Áreas de mejora:**
- ⚠️ No hay ejemplos de ejecutar el mismo código en ambos IDEs para comparar workflow
- ⚠️ Visual Studio no tiene capturas de pantalla de ejecución/debugging

**Comentarios:**
Documentación profesional de ambos IDEs. Visual Studio Code tiene cobertura completa desde navegación básica hasta debugging avanzado. Visual Studio está documentado con profundidad técnica, especialmente en debugging (breakpoints condicionales, visualizadores, ventanas de inspección). La comparación en CONCLUSIONES es honesta y basada en experiencia real.

---

### g) Análisis Comparativo entre IDEs (8/10)

**Puntuación:** 1.60/2.00

**Fortalezas:**
- ✅ **CONCLUSIONES_EVALUACION.md completo** con ambas secciones A y B
- ✅ **Sección A - Evaluación Inicial:**
  - Tabla comparativa: instalación, primera impresión, configuración básica, soporte C#
  - Preferencia inicial clara: VS Code
  - Razones justificadas: "más usada", "diferentes extensiones en marketplace", "más intuitivo"
- ✅ **Sección B - Evaluación Final:**
  - Tabla de evaluación práctica: productividad, facilidad, herramientas utilizadas, valoración final
  - Preferencia mantenida: VS Code (10/10) vs Visual Studio (7/10)
  - Justificación honesta: "se utilizó más VS Code por popularidad mientras que VS no se utilizó más que un 10% del tiempo por costumbre"
- ✅ **Aprendizajes documentados:**
  - Lo inesperado: "Ya teníamos experiencia con VS Code... Visual Studio nunca lo utilizamos"
  - Características valiosas: Prettier, PowerShell, Live Server
  - Características menos útiles: Better Comments, GitHub Copilot (no probado)
- ✅ **Reflexiones sobre proceso:**
  - Aspectos destacados de cada IDE
  - Dificultades: bucles, if-else
  - Conocimientos adquiridos: atajos, instalación .NET/JDK, manejo de consola
- ✅ **Recomendaciones:**
  - Para C#: VS Code recomendado (reconociendo que "VS es mejor para C# por su depurador")
  - Consejos: práctica, paciencia, revisión de código
  - Errores a evitar: versiones de .NET, sintaxis e indentación

**Áreas de mejora:**
- ⚠️ La comparativa es desequilibrada: reconocen que usaron VS Code 90% del tiempo vs Visual Studio 10%
- ⚠️ Faltan algunos detalles en reflexiones (problemas durante instalación/configuración no están descritos)
- ⚠️ Sección "Trabajo en Equipo" incompleta: "cada 2 ejercicios cambiamos de persona" sin más detalles
- ⚠️ No completan la pregunta sobre metodología de evaluación en dos fases

**Comentarios:**
Análisis honesto y autocrítico. Reconocen que su preferencia por VS Code está sesgada por experiencia previa, pero aun así documentaron VS con profundidad técnica. Las CONCLUSIONES muestran reflexión genuina sobre el proceso de aprendizaje. La honestidad sobre no haber probado GitHub Copilot y usar VS Code por "costumbre" demuestra madurez profesional.

---

## Puntuación Final

| Criterio | Peso | Puntuación | Ponderado |
|----------|------|------------|-----------|
| a) Instalación y configuración IDE + SDK | 20% | 9.0/10 | 1.80/2.00 |
| b) Instalación y gestión módulos/extensiones | 20% | 8.5/10 | 1.70/2.00 |
| c) Personalización del entorno | 20% | 9.5/10 | 1.90/2.00 |
| e) Ejecutables de diferentes lenguajes | 20% | 9.0/10 | 1.80/2.00 |
| f) Ejecutables en diferentes IDEs | 10% | 9.0/10 | 0.90/1.00 |
| g) Análisis comparativo entre IDEs | 10% | 8.0/10 | 0.80/1.00 |
| **TOTAL** | **100%** | | **8.90/10** ≈ **9.00/10** |

---

## Observaciones Finales

### Fortalezas Destacadas

1. **Documentación exhaustiva:** 1158 líneas y 5310 palabras demuestran compromiso con la calidad
2. **Múltiples lenguajes:** C#, Java, F# completamente implementados y documentados; Python configurado
3. **Evidencia visual:** 27 imágenes markdown + 34 screenshots validan todos los procesos
4. **Debugging profesional:** Conceptos avanzados como REPL, breakpoints condicionales, visualizadores, múltiples targets
5. **Personalización avanzada:** Perfil PowerShell personalizado con variables de entorno muestra comprensión técnica profunda
6. **Honestidad académica:** Reconocen sesgos y limitaciones en su evaluación comparativa
7. **Configuraciones reproducibles:** Código JSON completo y funcional para settings.json y launch.json

### Áreas de Mejora

1. **Desequilibrio en uso de IDEs:** Solo 10% del tiempo en Visual Studio limita la validez de la comparación
2. **Python sin ejemplo ejecutado:** Falta código real a pesar de configuraciones detalladas
3. **Fechas incompletas:** V0 y V1 en el encabezado principal sin completar
4. **Sección Trabajo en Equipo:** Muy breve, falta detalles sobre colaboración
5. **Capturas de ejecución:** No hay screenshots mostrando salida de programas ejecutados
6. **Troubleshooting:** Falta documentación de problemas encontrados y soluciones aplicadas

### Recomendaciones

- ✅ **Calificación merecida:** El trabajo cumple con excelencia los objetivos del RA2
- 📝 **Para próximos trabajos:** Equilibrar tiempo de uso entre herramientas a comparar
- 💡 **Sugerencia:** Incluir una sección de "lecciones aprendidas" con problemas reales encontrados
- 🎯 **Validar:** Ejecutar código Python documentado para completar la cobertura de lenguajes

### Conclusión

Trabajo sobresaliente que demuestra dominio técnico en configuración de entornos de desarrollo, uso de múltiples lenguajes y herramientas profesionales. La documentación es de calidad profesional y puede servir como guía de referencia para otros estudiantes. A pesar del desequilibrio en uso de IDEs, la profundidad técnica y honestidad en el análisis justifican una calificación excelente.

**Estado final:** ✅ APROBADO CON DISTINCIÓN

---

**Firma del evaluador:** ___________________________  
**Fecha:** 16 de diciembre de 2025
