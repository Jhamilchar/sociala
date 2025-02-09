# Sociala - Social Network App

Bienvenido a **Sociala**, una plantilla de aplicación de red social construida con **React**.

## 🚀 Requisitos

### 📌 Node.js
Este proyecto requiere **Node.js v18**. Puedes verificar tu versión de Node con:
```sh
node -v
```

Si necesitas cambiar la versión de Node, puedes usar **nvm (Node Version Manager)**:
```sh
# Para sistemas Unix (Linux/macOS)
nvm use 18

# Para Windows con nvm-windows
nvm use 18
```

Si no tienes **nvm** instalado, sigue la guía oficial:
- [nvm para macOS/Linux](https://github.com/nvm-sh/nvm)
- [nvm para Windows](https://github.com/coreybutler/nvm-windows)

## 📦 Instalación

Clona el repositorio y accede al directorio del proyecto:
```sh
git clone https://github.com/usuario/sociala.git
cd sociala
```

Luego, instala las dependencias con:
```sh
npm install
```
Si encuentras problemas con dependencias, usa:
```sh
npm install --legacy-peer-deps
```

## ▶️ Ejecución del Proyecto
Para iniciar el servidor de desarrollo, ejecuta:
```sh
npm start
```
El proyecto se ejecutará en **http://localhost:3000/**

## 📁 Estructura del Proyecto
```
/sociala
│── src/               # Código fuente
│── public/            # Archivos estáticos
│── package.json       # Dependencias y scripts
│── .gitignore         # Archivos a ignorar por Git
│── README.md          # Documentación del proyecto
```

## 🛠 Tecnologías Usadas
- **React** - Librería principal
- **Styled-Components** - Estilos dinámicos
- **ApexCharts** - Gráficos interactivos
- **React-Router** - Navegación en la aplicación

## 📌 Notas Adicionales
- Si experimentas errores con dependencias, prueba:
  ```sh
  rm -rf node_modules package-lock.json
  npm install
  ```
- Puedes construir el proyecto para producción con:
  ```sh
  npm run build
  ```

---

📌 **¡Listo! Ahora puedes empezar a trabajar en Sociala 🚀**

