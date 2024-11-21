# Servidor para generar un Bearer Token de Firebase

[Documentación oficial de Firebase](https://firebase.google.com/docs/cloud-messaging/auth-server)

## Pasos

1. Instalar las dependencias
```
npm install
```

2. Obtener el archivo de configuración de Firebase (firebase-admin.json)
    - Crear un proyecto en Firebase (Si no tienes una)
    - Ir a cuentas de servicio
    - Descargar el archivo de configuración de Firebase (Generar una nueva clave privada)
    - Copiar el archivo los datos de Firebase en el archivo firebase-admin.json
3. Levantar el servidor
```
node app
```





