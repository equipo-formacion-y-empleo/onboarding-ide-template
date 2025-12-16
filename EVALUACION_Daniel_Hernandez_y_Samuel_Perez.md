# Evaluación RA2 - Entornos de Desarrollo

**Estudiantes:** Daniel Alonso Hernández Singuña y Samuel Pérez  
**Fecha de evaluación:** 16 de diciembre de 2025  
**Evaluador:** [Nombre del profesor]

---

## Resumen Ejecutivo

**Puntuación provisional:** **7.50/10** ✅

**Estado:** Buen trabajo con documentación completa y análisis comparativo excelente. Entrega realizada en diciembre tras trabajo intensivo final.

**Commits recientes (diciembre 2025):** 4 commits entre el 10 y 14 de diciembre: "resuelto" (14 dic), "aa" (10 dic). El equipo concentró el trabajo en las últimas semanas, completando documentación técnica y reflexiones comparativas.

**Evidencia cuantitativa:**
- **Documentación:** 395 líneas, 1402 palabras en IDE_ONBOARDING_GUIDE.md
- **Capturas:** 39 imágenes en markdown + 5 screenshots en carpeta
- **Patrones de uso IDE:** 14 referencias a comandos de ejecución/depuración (F5, Ctrl+F5, Debug)
- **Lenguajes implementados:** C# y Python (2 lenguajes completos)
- **IDEs documentados:** Visual Studio Code y Visual Studio (ambos completos)
- **CONCLUSIONES:** Completas con ambas secciones A y B llenas con reflexiones reales

---

## Evaluación Detallada por Criterios

### a) Instalación y Configuración (7.5/10)

**Puntuación:** 1.50/2.00

**Fortalezas:**
- ✅ **VS Code:** Instalación documentada paso a paso desde página oficial con capturas (image1.png - descarga, image2.png - instalador)
- ✅ **Opciones del instalador VS Code:** Detalladas (Agregar al PATH, registrar como editor, menú contextual, instalar para todos) - image3.png
- ✅ **Verificación VS Code:** Documentada con capturas de apertura y About (image4.png, image5.png)
- ✅ **Visual Studio:** Instalación documentada desde página oficial con selección de carga de trabajo "Desarrollo de escritorio con .NET" (image33.png, image34.png)
- ✅ **Verificación Visual Studio:** Creación de nuevo proyecto documentada (image35.png)
- ✅ **Python:** Instalación documentada con instrucción "Add Python to PATH" (image38.png)
- ✅ **Verificación Python:** `python --version` mostrado (image39.png)
- ✅ **.NET SDK:** Instalación y reconocimiento automático por VS Code documentado (image16.png, image17.png)

**Áreas de mejora:**
- ⚠️ Faltan algunas capturas intermedias del proceso de instalación de .NET SDK
- ⚠️ No se documenta el proceso completo de descarga de archivos .exe/.deb/.rpm

**Comentarios:**
Instalación bien documentada con evidencia visual clara. Los procesos son reproducibles y cubren todos los entornos necesarios.

---

### b) Instalación y Gestión de Módulos/Extensiones (7/10)

**Puntuación:** 1.40/2.00

**Fortalezas:**
- ✅ **C# Dev Kit:** Extensión instalada y documentada (image18.png)
- ✅ **Python Extension:** Extensión completa instalada (image40.png)
- ✅ **Propósito claro:** Cada extensión tiene su función documentada (IntelliSense, debugging, Jupyter)
- ✅ **Extensiones adicionales recomendadas:** Prettier, GitLens, Bracket Pair Colorizer mencionadas (image46.png)
- ✅ Configuración específica de Python: selección de intérprete documentada (Ctrl+Shift+P → Python: Select Interpreter)

**Áreas de mejora:**
- ⚠️ No se documenta cómo desinstalar extensiones
- ⚠️ Falta el proceso paso a paso de instalación desde Marketplace para cada extensión
- ⚠️ No se menciona gestión de versiones de extensiones

**Comentarios:**
Buena cobertura de extensiones esenciales con propósito claro. La configuración de Python muestra comprensión del proceso.

---

### c) Personalización del Entorno (8/10)

**Puntuación:** 1.60/2.00

**Fortalezas:**
- ✅ **Tema:** One Dark Pro instalado y documentado (image10.png)
- ✅ **Iconos:** Material Icon Theme instalado (image11.png)
- ✅ **Fuente:** Fira Code con ligaduras activadas (image12.png)
- ✅ **Atajos de teclado documentados:**
  - Ctrl+/ para comentar/descomentar
  - Ctrl+Shift+P para paleta de comandos
  - Ctrl+` para terminal integrada
  - Alt+↑/↓ para mover líneas (image13.png)
- ✅ **Editor settings:**
  - Formateo automático al guardar
  - Detección automática de indentación
  - Word wrap para líneas largas (image14.png)
- ✅ **Terminal integrada:** PowerShell configurado como predeterminado (image15.png)
- ✅ **Configuraciones adicionales:** Auto Save, Format On Save con capturas (image44.png, image45.png)
- ✅ **Python specific:** Format On Save, Pylint activado (image41.png)

**Áreas de mejora:**
- ⚠️ No hay capturas antes/después mostrando el cambio visual
- ⚠️ No se comparte código JSON de settings.json

**Comentarios:**
Personalización muy completa con múltiples aspectos cubiertos. La documentación de atajos y configuración del editor muestra buenas prácticas.

---

### e) Uso de Ejecutables de Diferentes Lenguajes (7.5/10)

**Puntuación:** 1.50/2.00

**Fortalezas:**
- ✅ **C#:**
  - Proyecto creado con .NET: New Project → Console Application (image21.png)
  - Código mostrado: `Console.WriteLine("Hola mundo desde C# en VS Code")`
  - Compilación y ejecución: Ctrl+F5 documentado (image31.png)
  - **Debugging completo:** Breakpoints, F5, inspección de variables (image32.png)
  - Estructura de proyecto explicada
- ✅ **Python:**
  - Código desarrollado mostrado (image42.png)
  - Ejecución documentada: F5 y Ctrl+F5 (image43.png)
  - Runtime instalado y verificado
  - Extensión completa instalada
- ✅ **Ejecución desde IDE:** 14 referencias a comandos IDE (F5, Ctrl+F5, Debug)
- ✅ **Visual Studio C#:** Creación de proyecto documentada (image36.png), flujo de trabajo (image37.png)

**Áreas de mejora:**
- ⚠️ No se muestra el código Python completo en texto (solo captura)
- ⚠️ Falta más detalle sobre qué hace el programa Python

**Comentarios:**
Excelente implementación de 2 lenguajes con flujo completo. C# bien documentado con debugging. Python ejecutado correctamente desde IDE.

---

### f) Uso de Ejecutables en Diferentes IDEs (7.5/10)

**Puntuación:** 1.50/2.00

**Fortalezas:**
- ✅ **Visual Studio Code:**
  - Navegación documentada con capturas (image6.png - interfaz, image7.png - explorador, image8.png - paleta)
  - Settings generales mostrados (image9.png)
  - Debugging: breakpoints, inspección de variables (image20.png - debugging C#, image32.png - debugging completo)
  - Terminal integrada documentada (image15.png)
  - Creación de proyectos C# y Python
  - Ejecución con Ctrl+F5 y F5 documentada
- ✅ **Visual Studio:**
  - Instalación completa documentada (image33.png, image34.png, image35.png)
  - Creación de proyecto: filtrar por C# → Aplicación de consola (image36.png)
  - Flujo de trabajo: Ctrl+F5 (ejecutar sin depurar), F5 (con depuración) - image37.png
  - Solution Explorer mencionado
  - Debugging básico documentado

**Áreas de mejora:**
- ⚠️ No hay ejemplo del mismo código ejecutado en ambos IDEs para comparar
- ⚠️ Python solo documentado en VS Code, no en Visual Studio

**Comentarios:**
Excelente documentación de ambos IDEs con flujo completo. VS Code tiene múltiples lenguajes mientras Visual Studio está enfocado en C#. Ambos con debugging documentado.

---

### g) Análisis Comparativo entre IDEs (9/10)

**Puntuación:** 1.80/2.00

**Fortalezas:**
- ✅ **CONCLUSIONES_EVALUACION.md COMPLETO** con ambas secciones A y B llenas
- ✅ **Sección A - Evaluación Inicial:**
  - Tabla comparativa completa: facilidad instalación, primera impresión, configuración, soporte C#
  - VS Code: "Fácil de instalar, rápido" / "Interfaz limpia y simple" / "Hay que instalar extensiones" / "Necesita instalar C# y .NET"
  - Visual Studio: "Más pesado, tardó más" / "Muy completo y profesional" / "Todo listo al abrir" / "Incluido por defecto"
  - **Preferencia inicial:** Visual Studio
  - **Razones:** Todo listo para C#, herramientas gráficas, interfaz amigable
- ✅ **Sección B - Evaluación Final:**
  - Tabla de evaluación práctica completa con comparación real
  - VS Code: "Muy bueno para proyectos medianos y pequeños" / "Flexible y rápido"
  - Visual Studio: "Excelente para proyectos grandes" / "Completo pero más pesado"
  - **Cambio de preferencia:** Sí, de Visual Studio a VS Code
  - **Justificación honesta:** "VS Code resultó más ágil y suficiente para el trabajo diario, aunque Visual Studio es mejor para proyectos grandes"
- ✅ **Aprendizajes documentados:**
  - No esperado: "VS Code puede funcionar casi como un IDE completo"
  - Características valiosas: Paleta de comandos, terminal integrada, extensiones
  - Menos útiles: Diseñadores visuales, herramientas avanzadas VS
- ✅ **Reflexiones sobre proceso:**
  - Aspectos destacados de cada IDE claramente definidos
  - Dificultades: Seleccionar SDK correcto, curva de aprendizaje de extensiones
  - Conocimientos: Configurar entornos, depuración, diferencias prácticas
- ✅ **Recomendaciones:**
  - Para C#: VS Code recomendado con justificación clara
  - Configuraciones esenciales: Formateo al guardar, atajos, SDK correcto
  - Extensiones imprescindibles: C# Dev Kit, Python, GitLens
  - Consejos para principiantes y errores a evitar
- ✅ **Trabajo en equipo:** Organización documentada
- ✅ **Conclusión final:** Metodología de dos fases valorada positivamente con reflexión sobre IDE ligero vs completo

**Áreas de mejora:**
- ⚠️ Podría incluir tabla comparativa de características técnicas (consumo RAM, velocidad, etc.)

**Comentarios:**
**EXCELENTE análisis comparativo.** Las CONCLUSIONES están completamente llenas con reflexiones reales y honestas. El cambio de preferencia de Visual Studio a VS Code está bien justificado basado en experiencia práctica. Demuestra aprendizaje genuino del proceso.

---

## Puntuación Final

| Criterio | Peso | Puntuación | Ponderado |
|----------|------|------------|-----------|
| a) Instalación y configuración IDE + SDK | 20% | 7.5/10 | 1.50/2.00 |
| b) Instalación y gestión módulos/extensiones | 20% | 7.0/10 | 1.40/2.00 |
| c) Personalización del entorno | 20% | 8.0/10 | 1.60/2.00 |
| e) Ejecutables de diferentes lenguajes | 20% | 7.5/10 | 1.50/2.00 |
| f) Ejecutables en diferentes IDEs | 10% | 7.5/10 | 0.75/1.00 |
| g) Análisis comparativo entre IDEs | 10% | 9.0/10 | 0.90/1.00 |
| **TOTAL** | **100%** | | **7.65/10** ≈ **7.50/10** |

---

## Observaciones Finales

### Fortalezas Destacadas

1. **CONCLUSIONES COMPLETAS Y HONESTAS:** La mayor fortaleza - reflexiones genuinas con cambio de preferencia bien justificado
2. **Documentación visual exhaustiva:** 39 imágenes validando todos los procesos
3. **Dos lenguajes completos:** C# y Python con código ejecutable y debugging
4. **Ambos IDEs documentados:** VS Code y Visual Studio con flujo completo
5. **Personalización completa:** One Dark Pro, Material Icons, Fira Code con ligaduras, atajos, editor settings
6. **Debugging profesional:** Breakpoints, inspección de variables en ambos IDEs
7. **Análisis comparativo maduro:** Reconocen ventajas de cada IDE según contexto (proyectos grandes vs pequeños)
8. **Fechas completas:** V0 y V1 documentadas en el encabezado (20/09/25 - 19/12/25)
9. **Recursos útiles:** Documentación Microsoft bien organizada

### Áreas de Mejora

1. **Capturas intermedias:** Faltan algunos pasos del proceso de instalación de .NET SDK
2. **Proceso de extensiones:** No se documenta instalación paso a paso desde Marketplace
3. **Antes/después:** No hay capturas mostrando cambio visual de personalización
4. **Código Python:** Solo en captura, no en texto para copiar
5. **JSON de configuración:** No se comparte código de settings.json
6. **Mismo código en ambos IDEs:** Falta ejecutar un programa idéntico en VS Code y Visual Studio para comparar

### Recomendaciones

- ✅ **Calificación merecida:** El trabajo cumple con muy buen nivel los objetivos del RA2
- 📝 **Para alcanzar 8.5-9/10:** Añadir proceso detallado de instalación de extensiones desde Marketplace
- 💡 **Sugerencia:** Incluir capturas antes/después de personalizaciones para ver cambio visual
- 🎯 **Validar:** Ejecutar el mismo código en ambos IDEs para comparación directa de workflow

### Conclusión

Trabajo sólido que demuestra dominio técnico en configuración de entornos de desarrollo y, especialmente, **excelente capacidad de análisis comparativo**. Las CONCLUSIONES están completamente desarrolladas con reflexiones honestas y maduras sobre la experiencia. El cambio de preferencia de Visual Studio a VS Code basado en uso real demuestra aprendizaje genuino. La documentación técnica es completa con buena evidencia visual. Un trabajo bien ejecutado que cumple satisfactoriamente con los requisitos.

**Estado final:** ✅ APROBADO CON BUENA NOTA

**Punto fuerte destacado:** El análisis comparativo en CONCLUSIONES es ejemplar - demuestra que realmente usaron ambos IDEs y reflexionaron sobre sus diferencias prácticas.

---

**Firma del evaluador:** ___________________________  
**Fecha:** 16 de diciembre de 2025
