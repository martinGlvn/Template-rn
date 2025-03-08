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

## Estructura de carpetas
src/
├── assets/ # Imágenes, fuentes y otros recursos
├── components/ # Componentes reutilizables
├── hooks/ # Custom hooks
├── navigation/ # Configuración de navegación
├── screens/ # Pantallas de la aplicación
├── services/ # Servicios API y externos
├── store/ # Estado global con Zustand
├── styles/ # Estilos globales
├── types/ # Definiciones de tipos
└── utils/ # Funciones utilitarias

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/martinGlvn/Template-rn.git mi-app
cd mi-app

# Instalar dependencias
npm install

# Iniciar la aplicación
npm start