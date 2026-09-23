# modulo-autenticacion-equipo1
Base de datos: Veterinaria 
modulo-autenticacion-equipo1
Base de datos: Veterinaria

# 1.registro de usuario
-criterios: 
*CA1:Registro exitoso: 
Dado que me encuentro en el formulario de un registro, 
cuándo hago el ingreso de un nombre, un correo valido y una contraseña segura, y hago un clic en registrarme, 
entonces se crea la cuenta y se muestra un mensaje de confirmación. 

*CA2:Correo duplicado: 
Dado que ingreso un correo electrónico que ya se encuentra registrado en la base de datos,
cuando intenta enviar el formulario, 
entonces el sistema muestra el mensaje de error indicando que el correo electrónico ya se encuentra registrado. 

*CA3:Validación del formulario: 
Dado que dejo campos obligatorios sin llenar o el correo electrónico no cumple con el formato estandar, 
cuando presiono registrarse, 
entonces el sistema resalta los campos con errores y impide realizar el envio.

# 2.Loging de usuario
-Crioterios: 
*CA1:Autenticación exitosa: 
Dado que me encuentro en la pantalla de loging, 
cuando ingreso el correo y la contraseña correctos y presiono "iniciar sesión", 
entonces el sistema valida las contraseñas y me redirige al dashboard. 

*CA2:Credenciales incorrectas: 
Dado que ingreso un correo o contraseña invalido, 
cuando presiono "iniciar sesión", 
entonces se muestra el mensaje de error "credenciales incorrectas" sin detallar cual fallo. 

*CA3:Ocultar/mostrar contraseña: 
Dado que digito mi contraseña, 
cuando interactuó con el campo, 
entonces los caracteres están por defecto pero cuento con la opción de visualizar la clave.

# 3.Visualización del dashboard
-Criterios: 
*CA1:Carga de bienvenida: Dado que inicio sesión comrrectamente, 
cunado el sistema me redirige al dashboard, 
entonces visualizo un mensaje con mi nombre y los módulos principales activos. 

*CA2:Protección de la ruta: Dado que no estoy autenticando a la URL expiro, 
cuando intento acceder directamente a la URL del dashboard, 
entonces el sistema me redirige automáticamente al loging.

*CA3:Cierre de sesión: 
Dado que estoy dentro del dashboard, 
cuando hago clic en "cerrar sesión", 
entonces el sistema destruye el token/sesión y me redirige al loging.

# 4.Objetivo del modulo
implementar el modulo integral de gestión de acceso e identidad de usuario que automatice los procesos de registro, autenticación y despliegue del panel de control(Dashboard).El módulo tiene como propósito garantizar el control de acceso a la plataforma mediante la validación segura de credenciales, la protección de rutas privadas y la personificación de la interfaz principal, asegurando así la confidencialidad y la integridad de la información del sistema.
# 5.Integrantes del equipo
-Deimar Alejandro Manrique Arismendi 
-Jaider sabino triana
-Javier mauricio barón cardona 

