# 🔍 Es Posta

**Herramienta de verificación de noticias impulsada por IA**

Es Posta es una aplicación web que ayuda a los usuarios a verificar la credibilidad de las noticias analizando las fuentes y proporcionando puntuaciones de confiabilidad con feedback visual intuitivo.

-----

## 🌟 Características

- **Análisis de Credibilidad**: Evalúa la confiabilidad de las fuentes de noticias mediante IA
- **Puntuación Visual**: Sistema de colores para identificar rápidamente la confiabilidad
  - 🟢 Verde: Fuente confiable
  - 🟡 Amarillo: Verificación adicional recomendada
  - 🔴 Rojo: Fuente poco confiable
- **Interfaz Intuitiva**: Diseño limpio y fácil de usar
- **Respuestas Rápidas**: Análisis en tiempo real de las noticias ingresadas

-----

## 🚀 Tecnologías

- **Frontend**: React.js
- **Backend**: Node.js
- **IA**: Integración con API de análisis de contenido
- **Gestión de Estado**: React Hooks
- **Estilos**: CSS3

-----

## 📋 Requisitos Previos

- Node.js (v14 o superior)
- npm o yarn
- Clave API para el servicio de análisis (configurar en variables de entorno)

-----

## 🔧 Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/es-posta.git
cd es-posta
```

2. **Instalar dependencias del backend**
```bash
cd backend
npm install
```

3. **Instalar dependencias del frontend**
```bash
cd ../frontend
npm install
```

4. **Configurar variables de entorno**

Crear un archivo `.env` en la carpeta `backend`:
```env
API_KEY=tu_clave_api_aqui
PORT=5000
```

5. **Iniciar el servidor backend**
```bash
cd backend
npm start
```

6. **Iniciar la aplicación frontend**
```bash
cd frontend
npm start
```

La aplicación estará disponible en `http://localhost:3000`

-----

## 📁 Estructura del Proyecto

```
es-posta/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── backend/
│   ├── server.js
│   ├── routes/
│   └── package.json
├── .gitignore
└── README.md
```

-----

## 💡 Uso

1. Ingresa el texto de la noticia o la URL de la fuente en el campo de entrada
2. Haz clic en "Verificar"
3. Espera el análisis de la IA
4. Revisa la puntuación de confiabilidad y el feedback codificado por colores
5. Lee las recomendaciones y fuentes sugeridas para contrastar

-----

## 🔒 Seguridad

- Las claves API están protegidas mediante variables de entorno
- No se almacenan datos de usuario
- Todas las consultas son anónimas

-----

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

-----

## 📝 Roadmap

- [ ] Integración con múltiples APIs de verificación
- [ ] Sistema de historial de búsquedas
- [ ] Extensión para navegador
- [ ] App móvil (iOS/Android)
- [ ] Base de datos de fuentes verificadas
- [ ] Sistema de reportes comunitarios

-----
