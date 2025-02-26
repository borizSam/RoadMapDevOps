# 🚀 Road Map DevOps 
# GitHub Actions: Quarto Publish

Este archivo describe el flujo de trabajo de **GitHub Actions** utilizado en este proyecto para **automatizar la renderización y despliegue** del contenido generado con **Quarto** en **GitHub Pages**.  

---

## 🌍 Descripción General del Workflow

El objetivo del workflow es:  

1️⃣ **Compilar los archivos `.qmd`** con Quarto.  
2️⃣ **Publicar el contenido generado** en la rama `gh-pages`.  
3️⃣ **Actualizar automáticamente la página en GitHub Pages**.  

Esto garantiza que **cada cambio en el código fuente se refleje automáticamente en la página web**.  

---

## ⚡ Activadores del Workflow

💡 **El workflow se activa en dos casos:**  

🖱️ **`workflow_dispatch`**  
🔹 Permite ejecutar el workflow manualmente desde GitHub Actions.  
🔹 Útil para forzar una actualización sin realizar cambios en el código.  

🔄 **`push` a `main`**  
🔹 Cada vez que se sube un commit a `main`, el workflow se ejecuta automáticamente.  
🔹 Asegura que los cambios se reflejen en la página sin intervención manual.  

---

# 🎯 Conclusión

💡 Este workflow proporciona una solución automatizada, eficiente y confiable para mantener la página web siempre actualizada con los últimos cambios en los archivos Quarto.

    🔹 Eliminación de tareas manuales en el despliegue.
    🔹 Actualización continua sin intervención del usuario.
    🔹 Integración fluida entre Quarto, GitHub Actions y GitHub Pages.
# Flujo del Workflow
📌 Se realiza un push a la rama "main"  
      ⬇  
🔄 GitHub Actions detecta el cambio  
      ⬇  
📥 Clona el repositorio en un entorno virtual  
      ⬇  
⚙️ Instala y configura Quarto  
      ⬇  
🛠️ Renderiza los archivos `.qmd` a HTML  
      ⬇  
🚀 Publica el contenido en la rama `gh-pages`  
      ⬇  
🌐 GitHub Pages actualiza la página automáticamente  

# 🌍 🚀 Accede a mi Road Map DevOps
🔗 Puedes ver el resultado finalen el siguiente enlace:

➡️ [RoadMap DevOps](https://borizsam.github.io/RoadMapDevOps/)