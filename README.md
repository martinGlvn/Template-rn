# React Native + Expo Template con TypeScript

Un template completo para aplicaciones React Native con Expo y TypeScript, que incluye configuraciones para navegación, estado global, estilizado, testing y más.

## Tecnologías incluidas

- **Base**: React Native, Expo, TypeScript
- **Navegación**: React Navigation (Stack y Tab)
- **Estado global**: Zustand con persistencia
- **Estilizado**: Styled Components
- **Formularios**: React Hook Form
- **Testing**: Jest y React Native Testing Library
- **Linting**: ESLint y Prettier
- **Gestión de assets**: Expo Font, Expo Image
- **Entornos**: react-native-dotenv
- **Persistencia**: AsyncStorage
- **Administración**: Tanstack Query
- **Zod**: validaciones

## Estructura de carpetas
src/
  ├── api/           # Llamadas API y servicios
  ├── assets/        # Imágenes, fuentes, etc
  ├── components/    # Componentes reutilizables
  ├── constants/     # Valores constantes
  ├── features/      # Módulos específicos
  ├── hooks/         # Custom hooks
  ├── navigation/    # Configuración de navegación
  ├── stores/        # Estados globales (Zustand)
  ├── theme/         # Estilos, configuración de NativeWind
  ├── types/         # TypeScript interfaces/types
  └── utils/         # Funciones utilitarias

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/martinGlvn/Template-rn.git mi-app
cd mi-app

# Instalar dependencias
npm install

# Iniciar la aplicación
npm start