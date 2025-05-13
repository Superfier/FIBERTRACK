# FIBERTRACK

## 📦 Instalación

Sigue estos pasos para configurar FiberTrack en tu entorno:

1. **Instala Node.js:**  
   [Descargar Node.js](https://nodejs.org/es)
   
2. **Instala npm (si aún no lo tienes):**  
   ```sh
   npm install -g npm

3. Clona el repositorio:
   git clone <URL_DEL_REPOSITORIO>

🚀 Inicialización
- Instala las dependencias:
   npm install

- Crea los archivos .env:

  a- Ruta: FIBERTRAC1/otifiber
    VITE_API_BASE=http://localhost:3000/api
    VITE_GOOGLE_MAP=AIzaSyAC2fSELr6Sd0xL1A2BN_y8wInwOe59gLo
    VITE_MAP_ID=92b1a70fec4902b3

  b- Ruta: FIBERTRAC1/otifiberAPI
      MONGO_URI=mongodb+srv://adrianma:123456adrian@cluster0.wrgxm.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
      PORT=3000
      HOST=http://localhost
      JWT_SECRET=12345678
      RECOVERY_EMAIL=superraikage@gmail.com
      APPLICATION_PASSWORD=srxd vinf mwbw xwhr


Por ultimo debes de inicar el servidor:
  - Antes de ejecutar el servidor, abre una terminal separada para cada proyecto:
  - 📁 Carpeta optifiber
    cd optifiber
    npm run dev
  - 📁 Carpeta optifiberAPI
    cd optifiberAPI
    npm run dev



📌 Notas adicionales:
- Asegúrate de que MongoDB está correctamente configurado y ejecutándose(igualmente dentro de mongo copas hacer un usuario).
- Verifica que las variables de entorno sean correctas antes de iniciar el proyecto.


