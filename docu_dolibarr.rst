DOCUMENTACIÓN INSTALACIÓN DOLIBARR
=========================================

.. sectnum::

.. contents:: Table of contents

Introduccion
~~~~~~~~~~~~~~~~~~~~~~~~~

En esta documentación os ensenyaremos como instalar un ERP como es el caso de Dolibarr en la
plataforma Windows.

Que es Dolibarr?
~~~~~~~~~~~~~~~~~~~~~~~~~

Dolibarr ERP/CRM es un software de Planificación de Recursos Empresariales (PRE, ERP en inglés) y 
Gestión de Relaciones con los Clientes (GRC, CRM en inglés) open source para la Pequeña y mediana empresa,
autónomos o asociaciones.

Funcionalidades
~~~~~~~~~~~~~~~~~~~~~~~~~

Dolibarr incluye las funcionalidades más importantes de un PRE/GRC (En inglés ERP/CRM) exceptuando la gestión contable.
Está basado en diferentes módulos más o menos dependientes unos de otros. Se caracteriza principalmente por su 
facilidad de instalación y su simplicidad de uso a pesar del gran número de funcionalidades que se activan a través
de módulos

+----------------------+----------------------+----------------------+-----------------------------+
| Módulos principales  | Otros módulos        |       Diversos       | Funcionalidades que faltan  |
+======================+======================+======================+=============================+
| Catálogo de clientes | Generación de        | Multi-usuario,       | Sin módulo de gestión de    |
| y/o clientes         | PDF (facturas,       | permisos por         | recursos humanos            |
| potenciales          | pedidos,             | funcionalidades      |                             |
| y/o proveedores      | presupuestos...)     |                      |                             |
+----------------------+----------------------+----------------------+-----------------------------+
| Anuario de clientes, | Gestión de miembros  | Varios gestores      | Adopción de las NIIF        |
| clientes potenciales,| de una asociación    | de menú              |                             |
| proveedores          |                      |                      |                             |
|                      |                      |                      |                             |
+----------------------+----------------------+----------------------+-----------------------------+
| Gestión de cuentas   | Conectividad LDAP    | Muy simple de        |                             |
| bancarias/Cajas      |                      | instalar y de usar   |                             |
|                      |                      |                      |                             |
|                      |                      |                      |                             |
+----------------------+----------------------+----------------------+-----------------------------+
| Control de pagos     | Gestión de           | Funciona con MySQL   |                             |
|                      | subvenciones         | 3.1 o superior       |                             |
|                      |                      |                      |                             |
|                      |                      |                      |                             |
+----------------------+----------------------+----------------------+-----------------------------+

Procedimiento de Instalacion
~~~~~~~~~~~~~~~~~~~~~~~~~

Para los menos experimentados, que trabajan bajo windows, existe una distribución de Dolibarr llamada DoliWamp
que permite realizar una instalación Dolibarr bajo Windows con todos sus prerequisitos (Apache, MySql, PHP)
sin conocimientos informáticos. Como instalarla:

Consiga la versión de `Dolibarr <http://www.dolibarr.es/>`_ para Windows. 

Una vez dentro de la Web de Dolibarr, le daremos a Descargar. Y seguidamente, en versiones estables le daremos a
Descargar

.. note::
    Para guiarse utiliza las imágenes que vamos a poner en el transcurso de la documentación

.. image:: ./Recursos/1.PNG
    :align: center

.. image:: ./Recursos/2.PNG
    :align: center


En el siguiente paso tendremos que selecciona el instalador apropiado para nuestra plataforma. En nuestro caso
seleccionaremos "Dolibarr installer for Windows" o directamente pulsaremos el botón de Download Latest Version


.. image:: ./Recursos/3.PNG
    :align: center

Entonces, nos podremos dirigir a la carpeta de Descargas y buscar el ejecutable siguiente:

.. image:: ./Recursos/4.PNG
    :align: center

Una vez encontrado el ejecutable, hacemos doble click y empezamos la instalación.

.. note:: 
    En estos pasos, todo será darle a siguiente

.. image:: ./Recursos/5.PNG
    :align: center

.. image:: ./Recursos/6.PNG
    :align: center

.. image:: ./Recursos/7.PNG
    :align: center

.. seealso::
     Si usted desea tener un icono en el escritorio o inicio ràpido solo tendra que aceptarlo en el checkbox


:✔: Crear un icono de Inicio ràpido
:✔: Crear un icono en el escritorio

Seguidamente podremos darle al boton de instalar. Esperaremos unos segundos y en los parametros técnicos le daremos 
siguiente, y finalmente al btn:[Finalizar] boton.

.. image:: ./Recursos/8.PNG
    :align: center

.. image:: ./Recursos/9.PNG
    :align: center

.. image:: ./Recursos/10.PNG
    :align: center

.. image:: ./Recursos/13.PNG
    :align: center

Procedimiento de actualización 
~~~~~~~~~~~~~~~~~~~~~~~~~

Déjese guuiar en todos los pasos sin cambiar ningún valor de los propuestos por defecto. Esto actualizará todos
los ficheros 

Al final de la ejecución, se mostrará su explorador con una página que le preguntará por la actualización de su
base de datos. Escoja la opción acorde a su caso. 

Si su instalación es muy antigua, deberá ejecutar todos los pasos de actualización uno a uno hasta llegar a la versión más reciente. 

.. image:: ./Recursos/14.PNG
    :align: center

.. image:: ./Recursos/15.PNG
    :align: center

.. image:: ./Recursos/16.PNG
    :align: center

.. image:: ./Recursos/17.PNG
    :align: center

.. image:: ./Recursos/18.PNG
    :align: center

.. image:: ./Recursos/19.PNG
    :align: center

.. image:: ./Recursos/20.PNG
    :align: center

.. image:: ./Recursos/21.PNG
    :align: center

.. warning::  
    En el siguiente paso, debe ingresar la contrasenya que va utilizar para el usuario administrador. Tal y como le
    mostramos en la imagen de abajo

.. image:: ./Recursos/22.PNG
    :align: center

.. image:: ./Recursos/23.PNG
    :align: center

Primeras configuraciones
~~~~~~~~~~~~~~~~~~~~~~~~~

Después de la instalación de Dolibarr, debe establecer los parámetros para adaptar Dolibarr a
sus necesidades antes de su puesta en funcionamiento. 

Primero debe iniciar sesión con el usuario admin y la contraseña establecida anteriormente.

.. image:: ./Recursos/24.PNG
    :align: center

Una vez hecho el login estaremos en la area de configuración.

.. image:: ./Recursos/25.PNG
    :align: center

Empresa/Institución
-------------------------------- 

* **Nombre**: Nombre de la empresa o asociación
* **Logo**: Añada aquí su logo (.PNG, .jpg or .gif). No hay recomendación de tamaño, pero es mejor un formato.PNG SIN fondo transparente (Dolibarr usa FPDF que no gestiona ese tipo de fichero). En caso de duda, utilice un logotipo en formato jpg con un fondo blanco.
* **País**: No olvide indicar su país, ya que algunas opciones dependen de ello.
* **IVA**: Indique si usted se encuentra sometido o no a IVA. 

.. image:: ./Recursos/26.PNG
    :align: center

.. image:: ./Recursos/27.PNG
    :align: center

.. image:: ./Recursos/28.PNG
    :align: center

.. image:: ./Recursos/29.PNG
    :align: center

Módulos 
~~~~~~~~~~~~~~~~~~~~~~~~~

La activación de los módulos es muy importante. Depende de lo que planee hacer con Dolibarr. Es muy poco probable que usted necesite todos los módulos. Debe activar los módulos que probablemente necesite. Por ejemplo: Empresas, Facturas, Contabilidad.

Para activar los módulos que necesite, vaya a la página menu:Configuración[Módulos] y haga click en el link "Activar" en cada módulo que necesite.

El listado de módulos estándar está disponible en la página Listado de Módulos.

Si no está seguro de que módulos activar, vaya uno tras otro y vea las características que ofrecen en Dolibarr (compruebe los derechos, ver más adelante). Por supuesto, es posible deshabilitar los módulos después.

Una vez activados, algunos módulos requieren configuración adicional (haga clic en el icono que aparece en la misma línea). Véase Listado de Módulos para más información. 

.. image:: ./Recursos/30.PNG
    :align: center
