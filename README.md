# Dark-Kitchens
monolito en base php para plataforma donde el dueño sube su menú, el cliente hace el pedido y el cocinero ve una lista de tareas pendientes.


## Descripción del proyecto
**Dark Kitchens** es una plataforma web pensada para emprendimientos de comida que trabajan únicamente por domicilios o delivery. La idea nace de la necesidad de organizar mejor los pedidos, el menú y las tareas de cocina, evitando depender solamente de WhatsApp para todo el proceso.

La plataforma permite que el dueño del negocio publique su menú, que los clientes realicen pedidos de forma más ordenada y que el cocinero visualice una lista de tareas pendientes según los pedidos recibidos.

## Problemática
Hoy en día muchos negocios de comida pequeños o medianos manejan sus pedidos por chats, llamadas o mensajes informales. Esto puede generar desorden, pérdida de información, demora en la atención y dificultad para llevar el control de los pedidos en tiempo real.

## Solución propuesta
Este proyecto busca ofrecer una solución sencilla y funcional para centralizar la operación básica de una dark kitchen mediante una plataforma web desarrollada en PHP.

## Objetivo general
Desarrollar una aplicación web en PHP que permita gestionar el menú, registrar pedidos y organizar las tareas de cocina en un emprendimiento de tipo dark kitchen.

## Objetivos específicos
- Permitir al administrador o dueño registrar, editar y eliminar productos del menú.
- Facilitar al cliente la visualización del menú y la realización de pedidos.
- Mostrar al cocinero una lista de pedidos pendientes para mejorar la organización en cocina.
- Centralizar la información del negocio en una sola plataforma.

## Usuarios del sistema
### Dueño o administrador
- Gestiona el menú.
- Revisa pedidos realizados.
- Controla el estado general del negocio.

### Cliente
- Consulta el menú disponible.
- Realiza pedidos.
- Puede visualizar información básica de su pedido.

### Cocinero
- Consulta los pedidos pendientes.
- Organiza la preparación según el orden de llegada o prioridad.

## Funcionalidades principales
- Registro e inicio de sesión de usuarios.
- Gestión del menú de productos.
- Visualización del menú por parte del cliente.
- Registro de pedidos.
- Listado de pedidos pendientes para cocina.
- Cambio de estado de pedidos.
- Panel básico de administración.

## Uso de Artisan
Como el proyecto corre en Docker, no necesitas tener PHP instalado. Usa el comando `exec` para hablar con el contenedor:

```bash
docker compose up -d
docker compose exec app php artisan [comando]
```
