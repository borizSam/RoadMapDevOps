# 🚀 Mi RoadMap DevOps - Workflow de GitHub Actions para Quarto  

¡Hola! 👋 Soy **Boris** y este es mi **RoadMap DevOps**, donde comparto mi aprendizaje y experiencia en herramientas como **GitHub Actions, GitHub Pages y Quarto**.  

En este repositorio, he creado un **workflow automatizado** que se encarga de **renderizar y desplegar** el contenido generado con **Quarto** en **GitHub Pages**. Así, cada vez que actualizo mi roadmap, los cambios se reflejan automáticamente en la página web. 🚀  

---

## 🌍 ¿Cómo funciona este Workflow?

Este workflow está diseñado para:  

1️⃣ **Renderizar mis archivos `.qmd`** con **Quarto**.  
2️⃣ **Publicar automáticamente el contenido** en la rama `gh-pages`.  
3️⃣ **Actualizar mi RoadMap en GitHub Pages** sin intervención manual.  

Esto me permite concentrarme en **mejorar el contenido**, mientras GitHub Actions se encarga del despliegue.  

---

## ⚡ ¿Cuándo se activa el workflow?

💡 **El workflow se ejecuta en dos casos:**  

🖱️ **`workflow_dispatch`**  
🔹 Permite ejecutarlo manualmente desde GitHub Actions.  
🔹 Útil para forzar una actualización sin hacer cambios en el código.  

🔄 **`push` a `main`**  
🔹 Cada vez que subo un commit a `main`, el workflow se ejecuta automáticamente.  
🔹 Asegura que mi página web siempre esté actualizada con los últimos cambios.  

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

Cada vez que hago un commit en mi RoadMap, ¡todo se actualiza solo! 🚀

# 🌍 🚀 ¡Explora mi RoadMap DevOps!
Si te interesa el mundo de DevOps y quieres ver cómo va evolucionando mi roadmap, puedes visitar mi página en el siguiente enlace:

➡️ [RoadMap DevOps](https://borizsam.github.io/RoadMapDevOps/)