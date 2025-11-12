# BetterWidgets

BetterWidgets es una aplicación moderna enfocada en ofrecer **componentes visuales dinámicos y personalizables**, diseñados para integrarse fácilmente en interfaces web o de escritorio.  

El objetivo del proyecto es crear un conjunto de widgets más **eficientes, atractivos y adaptables** que mejoren la experiencia del usuario y faciliten el trabajo del desarrollador.

## Características principales

- **Interfaz limpia y modular:** cada widget está diseñado para reutilización y personalización.  
- **Código optimizado** en JavaScript / HTML / CSS.  
- **Arquitectura flexible:** pensada para escalar o integrarse con frameworks.  
- **Configuración automatizada** mediante `forge.config.js`.  
- **Enfoque educativo y experimental:** sirve como sandbox para probar nuevas ideas UI.

## Estructura del proyecto
BetterWidgets/
├── src/
│ ├── assets/ # Recursos estáticos (imágenes, íconos, fuentes)
│ ├── components/ # Widgets y módulos reutilizables
│ ├── main.js # Punto de entrada principal
│ ├── preload.js # Inicialización previa y comunicación segura
│ └── styles/ # Hojas de estilo globales
├── forge.config.js # Configuración de build y empaquetado
├── package.json # Dependencias y scripts
├── .gitignore # Archivos ignorados por Git
└── README.md # Este archivo

## Instalación y ejecución
1. Clona el repositorio: git clone https://github.com/trblnjon/BetterWidgets.git
   cd BetterWidgets
2. Instala las dependencias: npm install
3. Ejecuta el entorno de desarrollo: npm start
4. Compila para producción: npm run build

## Scripts disponibles
| Comando       | Descripción                                        |
| ------------- | -------------------------------------------------- |
| npm start     | Inicia la aplicación en modo desarrollo            |
| npm run build | Genera una versión optimizada de la app            |
| npm run lint  | Analiza el código con ESLint (si está configurado) |

## Tecnologías utilizadas
- HTML5 / CSS3 / JavaScript (ES6+)
- Electron Forge (para empaquetado y distribución)
- Node.js / NPM
- Prettier / ESLint (opcional, para formateo y calidad)

## Próximas mejoras
- Agregar pruebas unitarias con Jest.
- Implementar un sistema de temas (light/dark).
- Añadir soporte para widgets personalizados.
- Documentación detallada de la API interna.
- Integración con servicios externos (REST o WebSocket).

## Licencia
Este proyecto está bajo la licencia MIT.
Puedes usar, modificar y compartir el código libremente, siempre con la debida atribución.