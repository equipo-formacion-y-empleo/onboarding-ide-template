# Evaluación RA2 - Entornos de Desarrollo

**Estudiantes:** Diana Lucía Aragon Fernandez y Gustavo Daniel Quintero Paba  
**Fecha de evaluación:** 16 de diciembre de 2025  
**Evaluador:** [Nombre del profesor]

---

## Resumen Ejecutivo

**Puntuación provisional:** **8.00/10** ✅

**Estado:** Buen trabajo con documentación completa y múltiples capturas de pantalla. Entrega realizada en diciembre tras trabajo intensivo final.

**Commits recientes (diciembre 2025):** 3 commits el 10 de diciembre: "Complete onboarding guide with screenshots and examples" como commit principal. El equipo concentró todo el trabajo en las últimas semanas, completando los requisitos fundamentales.

**Evidencia cuantitativa:**
- **Documentación:** 434 líneas, 1796 palabras en IDE_ONBOARDING_GUIDE.md
- **Capturas:** 36 imágenes en markdown + 40 screenshots en carpeta
- **Patrones de uso IDE:** 20 referencias a comandos de ejecución/depuración (F5, Ctrl+F5, dotnet run, Debug)
- **Lenguajes implementados:** C# y Python (2 lenguajes completos)
- **IDEs documentados:** Visual Studio Code y Visual Studio (ambos completos)

---

## Evaluación Detallada por Criterios

### a) Instalación y Configuración (8/10)

**Puntuación:** 1.60/2.00

**Fortalezas:**
- ✅ **VS Code:** Instalación documentada con proceso claro: descarga, instalación, verificación con capturas (descarga.png, Instalador.png, Verificacion.png)
- ✅ **Visual Studio:** Proceso completo documentado con selección de carga de trabajo "Desarrollo de escritorio con .NET" (desarrollo.png, prueba.PNG)
- ✅ **.NET SDK:** Instalación desde página oficial con verificación mediante `dotnet --version` (instalacion.png, powershell.PNG)
- ✅ **Python:** Instalación documentada con instrucción de "Add Python to PATH" y verificación con `python --version` (python.png)
- ✅ **40 screenshots** validando los procesos de instalación
- ✅ **Opciones del instalador VS Code:** Documentadas (aceptar licencia, carpeta, PATH, editor predeterminado, accesos directos)

**Áreas de mejora:**
- ⚠️ Algunos pasos podrían tener más detalles técnicos
- ⚠️ Falta la fecha V1 en el encabezado del documento

**Comentarios:**
Instalación bien documentada con evidencia visual clara. Los procesos son reproducibles y cubren tanto IDEs como runtimes/SDKs necesarios. 

---

### b) Instalación y Gestión de Módulos/Extensiones (7.5/10)

**Puntuación:** 1.50/2.00

**Fortalezas:**
- ✅ **C# Extension:** Soporte oficial documentado (ms-dotnettools.csharp) con captura (extension.PNG)
- ✅ **Python Extension:** Extensión oficial mencionada con soporte completo
- ✅ **Java Extension Pack:** Mencionado para soporte completo de Java
- ✅ **Temas:** Material Theme, One Dark Pro, Dracula, Solarized Dark, Night Owl documentados (temas.jpg)
- ✅ **File Icon Theme:** Mencionado para mejor identificación de archivos
- ✅ **Material Theme Ocean High Contrast + DeepForest icons:** Configurados en el proyecto Python
- ✅ Propósito claro de cada extensión: IntelliSense, debugging, compilación

**Áreas de mejora:**
- ⚠️ No se documenta el proceso de instalación paso a paso desde Marketplace
- ⚠️ Falta información sobre cómo desinstalar o deshabilitar extensiones
- ⚠️ No se menciona gestión de versiones de extensiones

**Comentarios:**
Buena cobertura de extensiones esenciales para múltiples lenguajes. Cada extensión tiene un propósito claro documentado. 

---

### c) Personalización del Entorno (8.5/10)

**Puntuación:** 1.70/2.00

**Fortalezas:**
- ✅ **Temas:** Múltiples opciones documentadas: Material Theme, One Dark Pro, Dracula, Solarized Dark, Night Owl (temas.jpg)
- ✅ **Fuentes:** Fira Code y JetBrains Mono con ligaduras mencionadas (fuente.png)
- ✅ **Configuración de fuente actual:** Consolas tamaño 14 documentada
- ✅ **File Icon Theme:** Para mejor identificación de archivos
- ✅ **Atajos de teclado:** Lista completa documentada con captura (atajos.jpg):
  - Ctrl+/ para comentar/descomentar
  - Ctrl+Shift+P para paleta de comandos
  - Ctrl+` para terminal integrada
  - Alt+↑/↓ para mover líneas
- ✅ **Editor settings:**
  - Formateo automático al guardar (configuraciones.png)
  - Autoguardado activado (editor.png)
  - Detección automática de indentación
  - Word wrap para líneas largas
- ✅ **Terminal integrada:** PowerShell como predeterminado con perfil personalizado (terminal.png)
- ✅ **Barra lateral:** Organizada con explorador y control de versiones
- ✅ **Python:** Black configurado como formateador con autoformato al guardar, escribir y pegar (Setting1.png)
- ✅ **Entorno virtual Python:** .venv creado y activado con intérprete configurado

**Áreas de mejora:**
- ⚠️ No hay capturas mostrando el antes/después de la personalización
- ⚠️ No se documenta código JSON de configuración en settings.json

**Comentarios:**
Personalización muy completa con múltiples aspectos cubiertos. La configuración de Black con autoformato y el entorno virtual Python muestran comprensión avanzada. 

---

### e) Uso de Ejecutables de Diferentes Lenguajes (8/10)

**Puntuación:** 1.60/2.00

**Fortalezas:**
- ✅ **C#:**
  - Proyecto completo creado con `dotnet new console -o MiProyecto` (proyecto.PNG)
  - Estructura documentada: bin/, obj/, .csproj, Program.cs, .sln (estructura.PNG)
  - Código por defecto mostrado (ejemplo.PNG)
  - Comentarios sobre decisiones: Program.cs como punto de entrada, Console.WriteLine, gestión de configuración
  - Compilación y ejecución: `cd MiProyecto`, `dotnet run` (compilacion.PNG)
  - Salida verificada: "Hello, World!"
  - **Debugging completo:** breakpoints, Run and Debug, inspección de variables y flujo (debug.PNG, finalizacion.PNG)
- ✅ **Python:**
  - Código desarrollado completo mostrado (ejercicio.PNG)
  - Ejecución documentada: `python <nombre_del_archivo>.py` (ejecucion.PNG)
  - Entorno virtual .venv configurado
  - Black configurado como formateador
  - Intérprete configurado al entorno virtual
- ✅ **Ejecución desde IDE:** 20 referencias a comandos IDE (F5, Ctrl+F5, dotnet run, Debug)
- ✅ **Debugging en ambos lenguajes:** VS Code debugging documentado para C# con breakpoints, variables, flujo de ejecución

**Áreas de mejora:**
- ⚠️ El código Python mostrado no tiene descripción de su funcionalidad
- ⚠️ No se muestra la salida real del programa Python ejecutado
- ⚠️ Falta más detalle sobre el debugging de Python

**Comentarios:**
Excelente implementación de 2 lenguajes con flujo completo de trabajo. C# está muy bien documentado desde creación hasta debugging. Python tiene código real ejecutado con configuración profesional (venv, Black). 

---

### f) Uso de Ejecutables en Diferentes IDEs (8/10)

**Puntuación:** 1.60/2.00

**Fortalezas:**
- ✅ **Visual Studio Code:**
  - Navegación documentada: navegación por interfaz, edición, paleta de comandos (Ctrl+Shift+P), gestión de archivos
  - Terminal integrada con PowerShell
  - Personalización completa documentada (tema, fuentes, atajos, editor, terminal)
  - Debugging: breakpoints, F5, inspección de variables (puntos.png, depuracion.png, variables.png)
  - Flujo C#: creación con dotnet, compilación, ejecución, debugging
  - Flujo Python: código ejecutado desde IDE
- ✅ **Visual Studio:**
  - Instalación con selección de carga de trabajo "Desarrollo de escritorio con .NET" (desarrollo.png)
  - Creación de proyecto: "Crear un nuevo proyecto" → "Aplicación de consola (.NET)" → nombre y carpeta (crear.PNG, consola.PNG, creacion.PNG, miproyecto.PNG)
  - Estructura generada automáticamente con Program.cs (principal.PNG)
  - **Compilación y ejecución:** Ctrl+F5 documentado (ejecutar.PNG)
  - **Verificación de salida:** "Hello, World!" confirmado
  - **Solution Explorer:** Navegación por archivos y carpetas documentada (solucion.PNG)
  - **Debugging:** Breakpoints, F5, panel de depuración con variables y flujo (depuracion2.PNG)
  - Verificación completa: abrir .sln, ejecutar con Ctrl+F5, verificar salida

**Áreas de mejora:**
- ⚠️ No hay ejemplo del mismo código ejecutado en ambos IDEs para comparar workflow
- ⚠️ Python solo se ejecuta en VS Code, no en Visual Studio

**Comentarios:**
Excelente documentación de ambos IDEs con flujo completo. VS Code tiene múltiples lenguajes mientras que Visual Studio está enfocado en C#. Ambos tienen debugging documentado con capturas claras. 

---

### g) Análisis Comparativo entre IDEs (6.5/10)

**Puntuación:** 1.30/2.00

**Fortalezas:**
- ✅ **CONCLUSIONES_EVALUACION.md existe** con estructura completa de secciones A y B
- ✅ **Sección A - Evaluación Inicial:** Tabla comparativa preparada (instalación, primera impresión, configuración, soporte C#)
- ✅ **Sección B - Evaluación Final:** Tabla de evaluación práctica preparada (productividad, facilidad, herramientas, valoración)
- ✅ **Estructura completa:** Primeras impresiones, preferencia inicial, evolución, aprendizajes, reflexiones, recomendaciones
- ✅ **Secciones organizadas:** Aspectos destacados, dificultades, conocimientos adquiridos, conclusiones, trabajo en equipo

**Áreas de mejora:**
- ❌ **Sección A completamente vacía:** Todas las tablas tienen placeholders sin completar
- ❌ **Sección B completamente vacía:** No hay evaluación tras uso prolongado
- ❌ **Sin preferencia documentada:** No se indica qué IDE prefieren ni inicial ni final
- ❌ **Sin aprendizajes documentados:** Todas las reflexiones están sin completar
- ❌ **Sin recomendaciones:** No hay conclusiones finales escritas
- ❌ **Trabajo en equipo sin detalles:** Sección vacía

**Comentarios:**
La estructura del archivo CONCLUSIONES es excelente y completa, pero todo el contenido está sin llenar. Tienen las tablas comparativas preparadas pero no las completaron con sus experiencias reales. Esta es la principal área pendiente del trabajo. 

---

## Puntuación Final

| Criterio | Peso | Puntuación | Ponderado |
|----------|------|------------|-----------||
| a) Instalación y configuración IDE + SDK | 20% | 8.0/10 | 1.60/2.00 |
| b) Instalación y gestión módulos/extensiones | 20% | 7.5/10 | 1.50/2.00 |
| c) Personalización del entorno | 20% | 8.5/10 | 1.70/2.00 |
| e) Ejecutables de diferentes lenguajes | 20% | 8.0/10 | 1.60/2.00 |
| f) Ejecutables en diferentes IDEs | 10% | 8.0/10 | 0.80/1.00 |
| g) Análisis comparativo entre IDEs | 10% | 6.5/10 | 0.65/1.00 |
| **TOTAL** | **100%** | | **7.85/10** ≈ **8.00/10** |

---

## Observaciones Finales

### Fortalezas Destacadas

1. **Documentación visual exhaustiva:** 36 imágenes markdown + 40 screenshots validan todos los procesos
2. **Dos lenguajes completos:** C# y Python totalmente implementados con código ejecutable
3. **Ambos IDEs documentados:** VS Code y Visual Studio con flujo completo desde creación hasta debugging
4. **Personalización completa:** Temas, fuentes, atajos, editor settings, terminal, entorno virtual Python
5. **Debugging profesional:** Breakpoints, inspección de variables, flujo de ejecución en ambos IDEs
6. **Python con buenas prácticas:** Entorno virtual .venv, Black configurado, intérprete específico
7. **Verificaciones sistemáticas:** Cada instalación tiene su verificación documentada (dotnet --version, python --version)
8. **Recursos útiles completos:** Enlaces y documentación para VS Code, Python, .NET, Git

### Áreas de Mejora

1. **CONCLUSIONES sin completar:** La mayor debilidad - archivo preparado pero vacío
2. **Sin análisis comparativo real:** No hay reflexión sobre preferencias entre IDEs
3. **Sin aprendizajes documentados:** Faltan las experiencias personales del proceso
4. **Fecha V1 incompleta:** En el encabezado del documento principal
5. **Código Python sin descripción:** No se explica qué hace el programa
6. **Sin capturas antes/después:** En personalización no se ve el cambio visual
7. **Sin JSON de configuración:** No se comparte el código de settings.json

### Recomendaciones

- ✅ **Calificación merecida:** El trabajo técnico cumple con muy buen nivel los objetivos del RA2
- 📝 **Para alcanzar 9-10/10:** Completar CONCLUSIONES_EVALUACION.md con experiencias reales
- 💡 **Sugerencia:** Añadir reflexión sobre qué IDE prefieren y por qué basado en uso real
- 🎯 **Prioridad:** Documentar aprendizajes, dificultades encontradas y soluciones aplicadas

### Conclusión

Trabajo sólido que demuestra dominio técnico en configuración de entornos de desarrollo, uso de múltiples lenguajes y herramientas profesionales. La documentación técnica es completa con evidencia visual clara. El único aspecto pendiente significativo es el análisis comparativo y reflexiones personales en CONCLUSIONES. A pesar de esto, el trabajo técnico es de muy buena calidad y cumple satisfactoriamente con los requisitos principales.

**Estado final:** ✅ APROBADO CON BUENA NOTA

**Camino a la excelencia:** Completar CONCLUSIONES_EVALUACION.md con sus experiencias reales comparando ambos IDEs, aprendizajes del proceso, y recomendaciones basadas en práctica.

---

**Firma del evaluador:** ___________________________  
**Fecha:** 16 de diciembre de 2025
