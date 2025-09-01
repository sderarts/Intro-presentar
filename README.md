# 👾 Presentaciones - Club Informático Chile

¡Bienvenido al **Club Informático Chile**!  
Este repositorio está diseñado para que **cada miembro pueda presentarse** y aparecer en nuestra página web estática.

---

## ✅ ¿Cómo funciona?
- Tenemos un archivo `index.html` que muestra todas las presentaciones.
- Cada miembro agrega su **nombre**, una **breve reseña** y sus **enlaces de LinkedIn y GitHub**.
- Luego, subes tus cambios a través de un **Pull Request**.

---

## 🛠 ¿Cómo me agrego?
### 1. Haz un **fork** del repositorio
En la esquina superior derecha de esta página, haz clic en **Fork** para copiar el proyecto a tu cuenta.

### 2. Clona tu fork en tu PC
```bash
git clone https://github.com/TU-USUARIO/club-informatico-presentaciones.git
```

### 3. Edita el archivo `index.html`
Busca la sección
```html
<div class="presentaciones">
    <!-- Aquí los miembros agregan sus presentaciones -->
</div>
```

Agrega tu bloque de presentación **siguiendo este formato**:
```html
<div class="card">
    <h3>Tu Nombre</h3>
    <p>Escribe una breve reseña sobre ti: ¿qué te apasiona? ¿en qué trabajas o estudias?</p>
    <div class="links">
        <a href="https://linkedin.com/in/TU-USUARIO" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/TU-USUARIO" target="_blank"><i class="fab fa-github"></i></a>
    </div>
</div>
```

📌 Ejemplo real:
```html
<div class="card">
    <h3>Carlos Carrasco</h3>
    <p>Desarrollador backend apasionado por Python y la tecnología open source. Aprendiendo DevOps y ciberseguridad.</p>
    <div class="links">
        <a href="https://linkedin.com/in/mg-carlos-carrasco/" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/KrlitosForever" target="_blank"><i class="fab fa-github"></i></a>
    </div>
</div>
```

### 4. Guarda los cambios y súbelos a tu fork
```bash
git add .
git commit -m "Agregando mi presentación"
git push origin main
```

### 5. Crea un Pull Request
Vuelve a este repositorio original y crea un Pull Request para que revisemos y unamos tu cambio.

## ✅ ¿Qué debes considerar?
✔ Respeta el formato propuesto.   
✔ Usa íconos de LinkedIn y GitHub (ya están en la plantilla con Font Awesome).   
✔ No elimines ni modifiques otras presentaciones.   
✔ Sé breve, máximo 2-3 líneas en tu reseña.   

## ❓ ¿Tienes dudas?
Ve a la sección de Discussions ahí encontraras los siguientes foros:   
✔️ General   
✔️ Ideas   
✔️ Preguntas y Respuestas   

## 🎯 ¿Quieres contribuir más?

¡Perfecto! Puedes:
* Mejorar el diseño con CSS.
* Agregar soporte para fotos de perfil.
* Crear un formulario dinámico para generar el bloque HTML automáticamente.

## 🎉Ya eres parte del club 🎉
Puedes revisarte en el siguiente [Link](https://club-informatico.github.io/Intro-presentar/)
