### **Estructura de Carpetas**

```
src/
  assets/                 # Imágenes, íconos y recursos estáticos
  components/             # Componentes reutilizables
    Header.jsx            # Barra de navegación
    Footer.jsx            # Pie de página
    WeatherCard.jsx       # Tarjeta para mostrar datos del clima
    ComparisonCard.jsx    # Tarjeta para comparar dos ciudades
    Map.jsx               # Componente para el mapa interactivo
  context/                # Contextos globales
    ThemeContext.jsx      # Modo claro/oscuro
    WeatherContext.jsx    # Manejo global del clima
  hooks/                  # Hooks personalizados
    useWeatherFetch.js    # Hook para manejar peticiones a la API del clima
    useLocation.js        # Hook para obtener la ubicación del usuario
  pages/                  # Vistas principales
    Home.jsx              # Vista principal con la búsqueda y datos actuales
    Details.jsx           # Vista con información detallada del clima
    Comparison.jsx        # Vista para comparar dos ciudades
  utils/                  # Funciones auxiliares
    api.js                # Configuración para consumir la API
    formatters.js         # Funciones para formatear datos (ej.: temperatura, fechas)
  styles/                 # Archivos de estilo (CSS/SASS)
    main.css              # Estilos globales
    components/           # Estilos específicos de componentes
  App.jsx                 # Configuración de rutas principales
  main.jsx                # Punto de entrada del proyecto
```
