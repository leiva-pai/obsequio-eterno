# 🗡️ La Leyenda de Hyrule — Carta de Cumpleaños Interactiva

Una experiencia web interactiva, inmersiva y moderna diseñada como regalo especial de cumpleaños. Construida con HTML5, Tailwind CSS, sintetizador Web Audio ("Arpa de Hyrule"), efectos de partículas y sistema de descarga de ilustración.

---

## 📁 Estructura del Repositorio

```text
Mocosa/
├── index.html         # Web interactiva (HTML, CSS y JS integrados)
├── assets/
│   └── dibujo.png     # Ilustración / dibujo especial para descargar
└── README.md          # Instrucciones de despliegue y documentación
```

---

## 🎨 Personalización del Dibujo

Para cambiar la imagen o colocar tu dibujo original:
1. Reemplaza el archivo dentro de `assets/dibujo.png` por tu imagen (formato PNG o JPG recomendado).
2. El botón de descarga automáticamente permitirá guardar la imagen bajo el nombre **`Zelda_Link_Especial.png`**.

---

## 🚀 Instrucciones de Despliegue en GitHub Pages

Puedes desplegar esta carta en minutos usando cualquiera de los dos métodos descritos a continuación:

### Opción A: Desde la interfaz de GitHub (Sin consola)

1. **Crear un nuevo repositorio en GitHub**:
   - Ingresa a [GitHub.com](https://github.com) e inicia sesión.
   - Haz clic en el botón **`+`** (arriba a la derecha) -> **New repository**.
   - Nombre del repositorio: `carta-mocosa` (o el nombre de tu preferencia).
   - Mantén la visibilidad como **Public**.
   - Haz clic en **Create repository**.

2. **Subir los archivos**:
   - En la pantalla de tu repositorio recién creado, haz clic en el enlace **"uploading an existing file"**.
   - Arrastra la carpeta `assets` (con `dibujo.png` adentro), el archivo `index.html` y `README.md`.
   - Haz clic en **Commit changes**.

3. **Activar GitHub Pages**:
   - En tu repositorio de GitHub, dirígete a **Settings** (Pestaña superior).
   - En el menú lateral izquierdo, haz clic en **Pages**.
   - En la sección **Build and deployment**:
     - **Source**: Selecciona `Deploy from a branch`.
     - **Branch**: Selecciona `main` (o `master`) y carpeta `/ (root)`.
   - Haz clic en **Save**.
   - En 1 o 2 minutos, GitHub te dará un enlace público con tu web lista para compartir (Ejemplo: `https://tu-usuario.github.io/carta-mocosa/`).

---

### Opción B: Utilizando Git desde la terminal

```bash
# 1. Inicializar el repositorio Git local
git init

# 2. Agregar todos los archivos
git add .

# 3. Crear el commit inicial
git commit -m "Initial commit: Carta interactiva de cumpleaños"

# 4. Renombrar la rama principal a main
git branch -M main

# 5. Vincular a tu repositorio remoto de GitHub (reemplaza con tu URL)
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git

# 6. Subir los archivos
git push -u origin main
```

Posteriormente activa **GitHub Pages** en `Settings` -> `Pages` -> `Source: Deploy from a branch` (`main` / `/root`).

---

## ✨ Características Incluidas
- **Scroll Fluido y Nativo**: Sin interrupciones ni bloqueos de la rueda del ratón/trackpad.
- **Tipografía Unificada**: Inter / Sans-Serif sobrio al estilo Google / Android.
- **Arpa de Hyrule**: Generador de melodías pentatónicas con Web Audio API.
- **Medidor de Insomnio**: Animación gráfica interactiva al scroll.
- **Templo del Tiempo**: Emblema SVG interactivo con efectos de luz y sonido.
- **Descargar Ilustración**: Botón integrado para previsualizar y descargar la ilustración.
