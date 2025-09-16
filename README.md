# challenge-amigo-secreto
Este es un proyecto de  Lógica de programación de el Cuso de Alura
# 🎁 Amigo Secreto

Una aplicación web interactiva para organizar sorteos de amigo secreto de manera fácil y divertida.

## 📋 Descripción

**Amigo Secreto** es una aplicación web que desarrollada con HTML, CSS y JavaScript, lo que permite a los usuarios crear listas de participantes y realizar sorteos aleatorios para hacer intercambios de regalos. La aplicación cuenta con una interfaz intuitiva y funcionalidades completas para gestionar participantes.

### Características principales

- ✅ **Agregar participantes**: Interfaz simple para añadir nombres a la lista
- ✅ **Validación de datos**: Previene nombres duplicados y campos vacíos
- ✅ **Lista interactiva**: Visualización clara de todos los participantes
- ✅ **Eliminar participantes**: Botones individuales para remover personas específicas
- ✅ **Sorteo aleatorio**: Algoritmo que selecciona un ganador de forma aleatoria
- ✅ **Interfaz responsiva**: Adaptada para dispositivos móviles y desktop
- ✅ **Confirmaciones**: Diálogos de confirmación para acciones importantes
- ✅ **Soporte de teclado**: Tecla Enter para agregar participantes rápidamente

## Demo

<img width="1895" height="911" alt="image" src="https://github.com/user-attachments/assets/edfbcc91-b524-413a-a9c3-1ef68cc19c03" />


## 🛠️ Tecnologías utilizadas

- **HTML**: Estructura semántica de la aplicación
- **CSS3**: Estilos modernos con variables CSS y diseño responsivo
- **JavaScript**: Lógica de la aplicación y manipulación del DOM
- **Google Fonts**: Tipografías

## 📁 Estructura del proyecto

```
amigo-secreto/
│
├── index.html          # Página principal
├── style.css           # Estilos de la aplicación
├── app.js              # Lógica JavaScript
├── README.md           # Documentación del proyecto
│
└── assets/             # Recursos multimedia
    ├── amigo-secreto.png
    └── play_circle_outline.png
```

## 🔧 Instalación y uso

### Prerrequisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación de dependencias adicionales

### Instalación

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/amigo-secreto.git
   ```

2. **Navega al directorio del proyecto**:
   ```bash
   cd amigo-secreto
   ```

3. **Abre el archivo `index.html`**:
   - Opción 1: Doble clic en el archivo `index.html`
   - Opción 2: Usa un servidor local:
     ```bash
     # Con Python 3
     python -m http.server 8000
     
     # Con Node.js (si tienes http-server instalado)
     npx http-server
     ```

4. **Accede a la aplicación**:
   - Navegador: `http://localhost:8000` (si usas servidor local)
   - O simplemente abre el archivo directamente en tu navegador

## 📖 Cómo usar la aplicación

### 1. Agregar participantes
- Escribe un nombre en el campo de texto
- Presiona "Añadir" o la tecla Enter
- El nombre aparecerá en la lista con un botón de eliminar

### 2. Gestionar la lista
- **Eliminar individual**: Haz clic en ❌ junto al nombre
- **Limpiar todo**: Usa el botón "Limpiar toda la lista" (opcional)

### 3. Realizar el sorteo
- Haz clic en "Sortear amigo"
- El resultado aparecerá destacado en pantalla
- Se requieren mínimo 2 participantes para sortear

### 4. Validaciones incluidas
- No permite nombres vacíos
- Previene nombres duplicados
- Confirma antes de eliminar participantes

## 🎯 Funcionalidades técnicas

### Algoritmo de sorteo
```javascript
// Genera un índice aleatorio usando Math.random()
const indiceAleatorio = Math.floor(Math.random() * amigos.length);
const amigoSorteado = amigos[indiceAleatorio];
```

### Validaciones implementadas
- **Campos vacíos**: Verifica que se ingrese texto
- **Nombres duplicados**: Previene agregar el mismo nombre dos veces
- **Lista mínima**: Requiere al menos 2 participantes para sortear

### Gestión del DOM
- Manipulación dinámica de elementos HTML
- Actualización en tiempo real de la interfaz
- Event listeners para interacción del usuario

## 🎨 Personalización

### Colores principales (CSS Variables)
```css
:root {
    --color-primary: #4B69FD;      /* Azul principal */
    --color-secondary: #FFF9EB;    /* Crema de fondo */
    --color-button: #fe652b;       /* Naranja de botones */
    --color-text: #444444;         /* Gris del texto */
}
```

### Modificar estilos
1. Edita `style.css` para cambiar la apariencia
2. Las clases CSS están organizadas por componentes
3. Diseño responsivo incluido con media queries

## 🚨 Resolución de problemas

### Problema: "agregarAmigo is not defined"
**Solución**: Verifica que el archivo `app.js` esté en la misma carpeta y correctamente enlazado

### Problema: Los estilos no se cargan
**Solución**: Confirma que `style.css` esté en el directorio correcto

### Problema: Las imágenes no aparecen
**Solución**: Verifica que la carpeta `assets/` contenga las imágenes necesarias

## 🧪 Funciones de debug

Abre la consola del navegador (F12) y prueba:

```javascript
// Ver estado actual
mostrarEstadoActual()

// Cargar datos de prueba
llenarDatosPrueba()

// Limpiar toda la lista
eliminarTodosLosAmigos()
```

## 👨‍💻 Autor

**Jostyn Yesid Reyes Gonzalez**
- Email: jsotynreyes,jr@gmail.com
- LinkedIn: [Tu Perfil](www.linkedin.com/in/yesid-reyes-348844324)

## 🙏 Agradecimientos

- Inspirado en challenges de el Curso de ALura latam

---

⭐ **¿Te gusta el proyecto? ¡Dale una estrella!** ⭐
