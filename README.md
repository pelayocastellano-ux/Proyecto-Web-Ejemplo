# Proyecto-Web-Ejemplo

Proyecto web de ejemplo con HTML y CSS para practicar Git y GitHub: ramas, commits, pull requests y resolucion de conflictos.

---

## Descripcion

Este proyecto es una pagina web estatica creada como actividad practica del curso de GitHub en Edutin Academy. Incluye un archivo HTML con estructura semantica y una hoja de estilos CSS con diseno visual moderno.

---

## Como clonar este proyecto

Sigue estos pasos para obtener una copia local del repositorio:

### Requisitos previos

- Tener [Git](https://git-scm.com/) instalado en tu sistema.
- Un navegador web moderno (Chrome, Firefox, Edge, etc.).

### Pasos

1. Abre una terminal (o Git Bash en Windows).

2. Clona el repositorio:

```bash
git clone https://github.com/pelayocastellano-ux/Proyecto-Web-Ejemplo.git
```

3. Entra en la carpeta del proyecto:

```bash
cd Proyecto-Web-Ejemplo
```

4. Abre el archivo `index.html` en tu navegador:

   - **En Linux/macOS:**
     ```bash
     xdg-open index.html   # Linux
     open index.html        # macOS
     ```
   - **En Windows:**
     ```bash
     start index.html
     ```
   - O simplemente haz doble clic sobre `index.html` desde el explorador de archivos.

---

## Estructura del proyecto

```
Proyecto-Web-Ejemplo/
├── index.html      # Estructura HTML de la pagina
├── style.css       # Hoja de estilos CSS
└── README.md       # Documentacion del proyecto
```

---

## Ramas del proyecto

| Rama | Descripcion |
|------|-------------|
| `main` | Rama principal con la version estable e integrada del proyecto. Contiene el codigo HTML y CSS con los estilos finales tras resolver el merge. |
| `feature-mejora-estilo` | Rama de desarrollo donde se implementaron mejoras visuales: nueva paleta de colores (azul oscuro + rojo acento), tipografia 'Segoe UI', header con gradiente, secciones con efecto hover y footer renovado. Los cambios fueron integrados en `main` mediante Pull Request #1. |

---

## Historial de trabajo

1. Se creo el repositorio en GitHub con README inicial.
2. Se anadieron `index.html` y `style.css` con la estructura base.
3. Se creo la rama `feature-mejora-estilo` con mejoras de estilo.
4. Se simulo un conflicto de merge: un "colaborador" actualizo `style.css` en `main` con otra paleta de colores.
5. El conflicto se resolvio manteniendo los estilos mejorados de la rama `feature-mejora-estilo`.
6. Se completo el Pull Request #1 integrando los cambios en `main`.

---

## Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox, gradientes, transiciones)
- Git / GitHub

---

*Desarrollado como actividad practica del Curso de GitHub - Edutin Academy, 2026.*
