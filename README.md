# SPRINT 1 Definición del proyecto - Proyecto ARSW - Easy Parking 

# Logo:

<p align="center">
    <img  src="img/logo.png">
</p>

# Resumen

Easy Parking - Sistema de gestión de Estacionamiento para Establecimientos

Esta es una aplicación web diseñada para darle un soporte de gestión totalmente tecnológico integrando los sistemas IoT (Internet of Things) del establecimiento consiguiendo el máximo beneficio, productividad y control.

# Descripción

contará con dos tipos de usuarios y vistas:

- **Interfaz/vista Administrador:**

    - contara con un sistema para gestionar las posiciones y pisos del estacionamiento
    - también mostrará como un mapa con cada piso y lugares de estacionamiento donde cada lugar tendrá una opción para bloquear/abrir cada espacio del estacionamiento, 
    - opción para traer la información de los dispositivos IoT (dispositivos que bloquean o permiten el espacio a un lugar en el estacionamiento) y se sincronice con el mapa del estacionamiento para que este actualice o alimente cuando un lugar ha sido ocupado o está libre.
    - Notificaciones y alertas constantes con el estado en tiempo real del estacionamiento

    - **usuarios que interactúan:**

        - usuario administrador.

- **Interfaz/vista usuario que usa el estacionamiento:** 

    - será un tablero donde se mostrarán los pisos en color ROJO/VERDE si están libres o no.
    - si están libres selecciona el piso y se le mostraran los lugares libres donde el usuario escoge ese lugar y se le confirmara el lugar exacto de este.
    - esta vista se alimentará también de la información de los dispositivos IoT para tener actualizado en tiempo real los lugares disponibles.

    - **usuarios que interactúan:**

        - usuario normal.

- **conectar con dispositivos IoT:** 

    - dispositivos IoT (sensores, mecanismos de bloqueo) que sirvan para identificar y bloquear/permitir el paso en el espacio asignado del estacionamiento. y a su vez envía información al sistema para sincronizar su información.


## Necesidades que cubre nuestro proyecto

- poder tener un sistema tecnológico funcionando las 24h donde gestione y controle un estacionamiento.

## Problemas que se resuelven

- Evita bloqueo y largas filas en los estacionamientos.
- llevar un mejor control y orden en el estacionamiento.
- Actuar eficazmente cuando el estacionamiento colapse (fines de semana, festivos o fechas especiales):
    - gracias a las alertas se da tiempo a crear un plan estratégico poniendo nuevos lugares o boqueando las entradas ya que el sistema notificara cuando ya se esté excediendo el límite.

## Nicho de Mercado

- Establecimientos grandes como:
    - Centros Comerciales.
    - edificios corporativos.
    - conjuntos residenciales.

## Principales Competidores

- [4PARK_PRO](https://imasdetres.com/sistema-control-accesos-gestion-parking/) : sistema de gestión de parking 
    - no conecta sus sistemas de control.

## Valor añadido

- Poder conectar todo gracias a IoT, ofreciendo estadísticas y una gestión y administración practica cómodamente desde una oficina.

- Como es un sistema dinámico, se puede implementar fácilmente a las necesidades del cliente convirtiéndolo en un sistema para gestión de otras cosas como por ejemplo (sistema para abrir y cerrar las puertas del establecimiento).


# Historias de usuario

las historias de usuario están hechas en [trello](https://trello.com/), puede verlas desde el siguiente link:

- [Historias de Usuario Easy Parking](https://trello.com/b/rBTDUsPz/historias-de-usuario-easyparking)


# Autor

* **ANDRES DAVID VASQUEZ IBAÑEZ** - *Initial work* - [VASHIGO](https://github.com/vashigo)


# Licencia

This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details