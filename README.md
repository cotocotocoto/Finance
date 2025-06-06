# PlanFinanciero - Aplicación de Planificación Financiera Personal

Esta aplicación web permite a los usuarios crear planes financieros personalizados, incluyendo presupuesto, fondo de emergencia y plan de retiro.

## Características

- **Dashboard financiero**: Visualización de ingresos, gastos y ahorros
- **Calculadora de fondo de emergencia**: Determina cuánto necesitas ahorrar para imprevistos
- **Calculadora de plan de retiro**: Proyecta tus ahorros para la jubilación
- **Recomendaciones personalizadas**: Consejos financieros basados en tu situación
- **Diseño responsivo**: Funciona en dispositivos móviles y de escritorio

## Requisitos previos

- Node.js 16.0 o superior
- npm 7.0 o superior

## Instalación

1. Clona este repositorio:
```bash
git clone <url-del-repositorio>
cd plan-financiero
```

2. Instala las dependencias:
```bash
npm install
```

## Ejecución en modo desarrollo

Para ejecutar la aplicación en modo desarrollo:

```bash
npm run dev
```

La aplicación estará disponible en `http://localhost:5173`

## Construcción para producción

Para construir la aplicación para producción:

```bash
npm run build
```

Los archivos generados estarán en el directorio `dist`.

## Despliegue

Puedes desplegar los archivos del directorio `dist` en cualquier servicio de hosting estático como:

- Netlify
- Vercel
- GitHub Pages
- Firebase Hosting
- Amazon S3

## Estructura del proyecto

```
plan-financiero/
├── public/              # Archivos estáticos
├── src/                 # Código fuente
│   ├── components/      # Componentes React
│   │   ├── ui/          # Componentes de interfaz de usuario
│   │   └── ...          # Componentes específicos de la aplicación
│   ├── lib/             # Bibliotecas y utilidades
│   ├── App.jsx          # Componente principal
│   ├── App.css          # Estilos principales
│   └── main.jsx         # Punto de entrada
├── index.html           # Plantilla HTML
└── package.json         # Dependencias y scripts
```

## Tecnologías utilizadas

- React
- Vite
- Tailwind CSS
- Lucide Icons
- LocalStorage para persistencia de datos

## Personalización

### Fórmulas financieras

Las fórmulas financieras se encuentran en `src/lib/calculosFinancieros.js` y pueden ser modificadas según necesidades específicas.

### Estilos

Los estilos utilizan Tailwind CSS y pueden ser personalizados en los archivos de componentes o en el archivo `tailwind.config.js`.

## Licencia

MIT

