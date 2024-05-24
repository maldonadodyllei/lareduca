Clone en el repositori 'https://github.com/maldonadodyllei/lareduca.git'

Habria que cambiar el archivo .env, ademas de cambiar el DB_DATABASE para elegir la base de datos que quieres

Instalar composer con el comando 
-> composer install

A continuación hay que ejecutar los siguientes dos comandos:
-> npm i
-> npm run dev

Ahora, para poder ejecutar las migraciones hay que ejecutar el siguiente comando
-> php artisan migrate

Seguramente aparezca un mensaje conforme la apliación está en producción, lo que hay que responder que 'si' y continuar

A partir de aquí ya está todo operativo. Registrarse con un usuario 'Teacher'

Primero de todo hay que crear un departamento en 'admin' para poder crear cursos y seguidamente asignar los alumnos