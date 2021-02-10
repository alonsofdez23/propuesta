% CrossPerformance
% Alonso Fernández Vidal
% Curso 2020/21

# Descripción general del proyecto

Plataforma para gestión de reserva de clases y gestión interna de centros deportivos.

## Funcionalidad principal de la aplicación

La aplicación permitirá a los usuarios registrase y loguearse. Estos usuarios podrán reservar clase en tramos horarios establecidos previamente por el administrador. Los usuarios tendrán sus perfiles donde pondrán tener sus datos personales, marcas personales y objetivos.

## Objetivos generales

Como administrador establecer franjas horarias para reservar clases, control total de los usuarios, gestión interna de los pagos, etc.

Como usuario poder rellenar y actualizar sus datos personales, reservar horas de clase, etc.

* Objetivo: "gestionar las reservas de clase de los usuarios".
* Casos de uso: 
	- Invitados: "registrarse".
	- Usuarios: "iniciar sesión", "cerrar sesión", "reservar clase", "eliminar reserva de clase", "mirar entreno del día", "editar perfil personal", "borrar perfil personal", "buscar otros usuarios", "ver a otro usuario".
	- Administrador: "iniciar sesión", "cerrar sesión", "registar entreno del día", "eliminar entreno del día", "modificar entreno del día", "ver detalles del entreno del día", "editar un perfil", "borrar una cuenta", "buscar otros usuarios", "ver a otro usuario", "ver pagos facturados".

# Elemento de innovación

* Uso de Amazon S3 como servicio de almacenamiento y protección de datos.