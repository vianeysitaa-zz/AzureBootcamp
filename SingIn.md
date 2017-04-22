# Paso a paso para habilitar el Sign On en una Web App a través de Azure AD #
> En este documento podremos habilitar el login de una aplicación web a través del servicio de Active Directory en Azure. 

1. Ingresar a tu cuenta de Azure
![Ingresar a Azure](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-1.png)
2. Generar una aplicación web en Azure: Dar click en el botón de "+", seleccionar la opción "Web + Mobile" y escoger "Web App".
![Generar web app](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-2.png)
3. Configurar los parámetros de la web app para generarla
![Configurar web app](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-3.png)
4. Una vez que la web app se haya creado, navegamos a ella para poder administrarla. En esta página podemos ver la URL de nuestra web app, dirección ftp, en qué subscripción se encuentra, etc.
![Navegar web app](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-4.png)
5. En el menú derecho navegamos a la opción "Authentication/Authorization"
![Authorization web app](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-5.png)
6. Activamos la opción de autenticación de app service a encendido ("ON")
![Authentication ON](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-6.png)
7. En este paso configuramos qué debe hacer la aplicación, en caso de que una petición a la página no se encuentre autenticado. Existen varias opciones:
* Permitir peticiones anónimas (Sin acción)
* Acceso a través de Azure AD
* Acceso a través de Facebook
* Acceso a través de Google
* Acceso a través de cuentas Microsoft (outlook, live, hotmail)
* Acceso a través de Twitter
![Accesos](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-7.png)
8. Para esta DEMO seleccionaremos el acceso a través de Azure AD
![Configuración AD](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-11.png)
9. Configuramos el modo de administración exprés, el que nos permite crear y registrar una aplicación en nuestro directorio Activo, o seleccionar alguna existente. Damos clic en "Ok"
![configuración AD](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-12.png)
13. Notamos que nuestro proveedor de autenticación aparece como configurado, y damos click en guardar ("Save")
![Accesos](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-13.png)
14. Hasta este paso ya configuramos la autenticación, ahora solo tenemos que probarla. Navegamos a nuestra web app, y nos debe pedir autenticación para el sitio.
![Accesos](https://github.com/vianeysitaa/AzureBootcamp/blob/master/imgs/signon-8.png)

# Referencias adicionales #
> [Habilitar Single Sign On con O365](https://apps.dev.microsoft.com/Landing)

> [Autenticación OAuth 2.0](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-v2-protocols-oauth-code)

> [Active Directory Authentication Libraries](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-libraries)
