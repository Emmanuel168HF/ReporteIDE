# Actividad 3 — Configuración de un Entorno de Desarrollo Integrado (IDE)

**Alumno:** Gomez Almaraz Armando Emmanuel  
**Grupo:** 2DSM-G3  
**Fecha:** 15 de enero de 2026  
**Unidad:** UNIDAD 1

---

## 1. IDE seleccionado
- **IDE:** Visual Studio Code  
- **Versión:** 1.86.x  
- **Sistema operativo:** Windows 11 (64 bits)

---

## 2. Justificación

Elegí **Visual Studio Code** como entorno de desarrollo para **Java y Python** porque equilibra potencia, ligereza y personalización total. Es un IDE que crece contigo: hoy estudiante, mañana desarrollador profesional.

- **Criterio 1: Soporte sólido para Java y Python**  
  Permite desarrollo completo con depuración, ejecución y gestión de proyectos en ambos lenguajes mediante extensiones oficiales.

- **Criterio 2: Ecosistema de extensiones**  
  Facilita integrar herramientas modernas como Jupyter, GitHub Copilot y depuradores avanzados sin saturar el sistema.

- **Criterio 3: Flujo profesional con Git y GitHub**  
  Integra control de versiones directamente en el editor, favoreciendo buenas prácticas desde etapas tempranas.

---

## 3. Requisitos previos

- **Sistema operativo:** Windows 11  
- **Conexión a internet:** Para descargas y sincronización de extensiones  
- **Dependencias:**
  - Git
  - Java Development Kit (JDK 17 o superior)
  - Python 3.10 o superior
- **Permisos:** Acceso de administrador para instalación

---

## 4. Instalación (paso a paso)

1. Acceder al sitio oficial de Visual Studio Code.
2. Descargar la versión para Windows 64 bits.
3. Ejecutar el instalador `.exe`.
4. Aceptar términos y condiciones.
5. Activar opciones recomendadas (agregar al PATH).
6. Finalizar la instalación.

---

### 4.1 Verificación

- **¿Cómo comprobé que funciona?**  
  El IDE se ejecutó correctamente y permitió crear, ejecutar y depurar programas en Java y Python.

- **Evidencia:**  
  Ejecución correcta de un archivo `.java` y un `.py` desde el editor.

---

## 5. Configuración inicial

### 5.1 Ajustes básicos

- Activación de **Auto Save**.
- Tema visual personalizado.
- Configuración de fuente monoespaciada para código.
- Activación del panel de control de versiones.

---

### 5.2 Extensiones / plugins

| Extensión | Función | Por qué |
|---|---|---|
| Extension Pack for Java | Soporte completo para Java | Incluye compilador, depuración y autocompletado |
| Language Support for Java | Lenguaje Java | Base para desarrollo Java |
| Debugger for Java | Depuración | Permite ejecución paso a paso |
| Python | Soporte Python | Ejecución, linting y depuración |
| Jupyter | Notebooks interactivos | Ideal para análisis y prácticas en Python |
| Code Runner | Ejecutar código rápido | Ejecuta Java y Python sin configurar manualmente |
| GitHub Copilot | IA para programación | Apoyo inteligente en escritura de código |
| GitHub Copilot App Module | Integración avanzada | Mejora el flujo con Copilot |
| GitLens | Control de versiones | Visualiza historial de cambios |
| Error Lens | Errores visibles | Resalta errores directamente en el código |
| Console Ninja | Consola mejorada | Depuración más clara |
| Image Preview | Vista previa de imágenes | Útil en proyectos con recursos gráficos |
| Material Icon Theme | Íconos visuales | Mejora la organización visual |
| Rainbow Brackets | Colores en paréntesis | Facilita lectura de estructuras |
| Spanish Language Pack for VS Code | Interfaz en español | Mayor comprensión del entorno |
| GlassIt-VSC | Transparencia del editor | Mejora estética y concentración |
| Doki Theme | Tema visual | Personalización estética del entorno |

---

### 5.3 Herramientas adicionales

- **Java:**  
  - Compilador: JDK 17  
  - Prueba: Ejecución correcta de `HelloWorld.java`

- **Python:**  
  - Intérprete: Python 3.11  
  - Prueba: Ejecución correcta de script `.py` y notebook Jupyter

---

## 6. Prueba final (mini-ejercicio)

```txt
# 1. Navegación al directorio de trabajo
d:
cd \repositorios\ReporteIDE

# 2. Inicialización del repositorio local
git init

# 3. Configuración del origen remoto (vínculo con GitHub)
git remote add origin https://github.com/Emmanuel168HF/ReporteIDE.git

# 4. Creación del archivo de reporte (Markdown)
echo "# Reporte IDE - Emmanuel" > A3_ReporteIDE_GomezAlmarazArmandoEmmanuel.md

# 5. Preparación de archivos (Staging)
git add A3_ReporteIDE_GomezAlmarazArmandoEmmanuel.md

# 6. Registro de cambios localmente (Commit)
git commit -m "Primer commit: Mi reporte técnico"

# 7. Renombrar rama principal a main
git branch -M main

# 8. Carga de archivos a la nube (Push)
git push -u origin main
---
```
## 7. Conclusiones

- La configuración de **Visual Studio Code** como IDE para **Java y Python** permitió establecer un entorno de desarrollo funcional, flexible y alineado a prácticas profesionales actuales.
- La correcta instalación del **JDK**, **Python** y las extensiones oficiales garantizó la ejecución, depuración y gestión adecuada de proyectos en ambos lenguajes.
- El uso de extensiones adicionales como **GitHub Copilot**, **Jupyter**, **Error Lens** y **Code Runner** optimizó la productividad y facilitó la detección de errores durante el desarrollo.
- La integración de **Git y GitHub** permitió aplicar control de versiones, asegurando trazabilidad de cambios y una estructura ordenada del proyecto.
- Documentar paso a paso la instalación y configuración hace que el entorno sea **reproducible**, comprensible y listo para futuros proyectos académicos y profesionales.

En conclusión, el IDE configurado no solo cumple con los requisitos técnicos de la actividad, sino que establece una base sólida para el desarrollo de software moderno, eficiente y orientado al futuro.
