Instrucciones para ejecutar la aplicación


Requisitos previos
Node.js y npm: Asegúrate de tener Node.js y npm instalados.
Git: Si deseas clonar el repositorio, instala Git.


Clonar el repositorio
<<<<<<< HEAD
git clone https://github.com/ManuelNajeraa/Actt4.git
=======
git clone https://github.com/GeraEsc/Act-4
>>>>>>> 19d40bf9f13b00c1032db7252715a85174e711ef
cd Act-4


Instalar dependencias
npm install


Variables de entorno
Crea un archivo .env en la raíz del proyecto con las siguientes variables
PORT=3000
MONGODB_URI=mongodb://localhost:27017/mi-base-de-datos
JWT_SECRET=tu-secreto


Ejecutar la aplicación
npm start
La aplicación se ejecutará en http://localhost:3000.


Ejecutar pruebas
npm test


Despliegue en Vercel
Instala Vercel si no lo tienes:
npm install -g vercel


Despliega la aplicación:
npx vercel --prod --token=tu-token-de-vercel
