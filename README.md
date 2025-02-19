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

# Reporte de Vulnerabilidades

Este documento detalla las vulnerabilidades detectadas en el proyecto mediante `npm audit`.

## 🔴 Vulnerabilidades Altas (6)
1. **nth-check (<2.0.1)** → Problema de complejidad en expresiones regulares [(Advisory)](https://github.com/advisories/GHSA-rp65-9cf3-cjxr)
2. **nth-check (<2.0.1)** → Afecta a `css-select`
3. **nth-check (<2.0.1)** → Afecta a `svgo`
4. **nth-check (<2.0.1)** → Afecta a `@svgr/plugin-svgo`
5. **nth-check (<2.0.1)** → Afecta a `@svgr/webpack`
6. **nth-check (<2.0.1)** → Afecta a `react-scripts`

## 🟠 Vulnerabilidades Moderadas (6)
7. **postcss (<8.4.31)** → Error de análisis en retorno de línea [(Advisory)](https://github.com/advisories/GHSA-7fh5-64p2-3v2j)
8. **postcss (<8.4.31)** → Afecta a `resolve-url-loader`
9. **serialize-javascript (<6.0.2)** → Riesgo de Cross-Site Scripting (XSS) [(Advisory)](https://github.com/advisories/GHSA-76p7-773f-r4q5)
10. **serialize-javascript (<6.0.2)** → Afecta a `rollup-plugin-terser`
11. **serialize-javascript (<6.0.2)** → Afecta a `workbox-build`
12. **serialize-javascript (<6.0.2)** → Afecta a `workbox-webpack-plugin`

## 🔧 Solución recomendada
Ejecuta el siguiente comando para corregir las vulnerabilidades:
```sh
npm audit fix
```
Si el problema persiste, intenta con:
```sh
npm audit fix --force
```
⚠️ **Advertencia:** El uso de `--force` puede provocar cambios significativos en las dependencias. Se recomienda probar la aplicación después de ejecutar este comando.



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

