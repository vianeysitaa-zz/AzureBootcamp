# AzureBootcamp
Repositorio con los pasos para el laboratorio de Identity with Azure AD y O365

# Habilitar Autenticación Multi-Factor (MFA) #
>La autenticación Multi-Factor proporciona una capa adicional de seguridad para confirmar la identidad de un usuario. Las metodologías utilizadas pueden incluir PIN, llamadas telefónicas, tarjetas inteligentes, biometría, etc.
>La integración de MFA para proteger una implementación de directorio activo, especialmente si está sincronizada o federada con Azure Active Directory, puede extender los límites de seguridad de nuestra infraestructura.

## Pasos para integrar MFA ##

1. Ingrese al portal de Azure
2. Navegar al Directorio Activo
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa1.jpg "Navegar al directorio activo")
3. Navegar al directorio activo correspondiente e ir a los usuarios
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa2.jpg "Navegar al directorio activo")
4. Selecciona el usuario y da click en el ícono del candado "manage multi-factor auth"
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa3.jpg "Seleccionar usuario")
5. Selecciona el usuario o los usuarios que deseas habilitar con MAF y da clic en la opción "Enable"
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa5.jpg "Habilitar MFA")
6. Da click en "Enable multi-factor auth" en el mensaje pop up que aparecerá
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa6.jpg "Habilitar MFA")
7. Inicia sesión con el usuario al que se acaba de habilitar MFA
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa8.jpg "Inicia Sesión")
8. Ahora configuraremos MFA. En esta página podrás ver las tres opciones disponibles:
* Autenticación por teléfono: Esto enviará un mensaje SMS o hará una llamada telefónica al número de teléfono especificado. Si utilizamos esta opción, los SMS y las llamadas serán cobradas.
* Teléfono de oficina: Esta opción es para solicitar el contacto utilizando el teléfono de oficina especificado por el administrador.
* Aplicación móvil: Con esta opción, se puede instalar la aplicación móvil (Azure Authenticator) en su teléfono y se puede configurar para enviar notificaciones mediante la aplicación cuando intente iniciar sesión o utilizar un código de verificación.
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa10.jpg "Configuración de MFA")
9. Selecciona la opción deseada y da click en "Setup"
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa11.jpg "Setup")
10. Para esta DEMO, seleccionamos el método de aplicación móvil. Intenta hacer de nuevo login con la cuenta para que puedas probar la configuración MFA
![alt text](http://www.rebeladmin.com/wp-content/uploads/2016/01/mfa12.jpg "Login con MFA")









