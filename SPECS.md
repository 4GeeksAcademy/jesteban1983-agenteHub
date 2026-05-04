# CREAR AGENTE IA "AgentHub"

## Contexto

. Estoy construyendo "AgentHub", un panel administrativo. Necesito el componente de Gestión de Agentes.

## Especificaciones

### Tarea

. modifica index.html

### Requisitos

. Modificar pagina index.html
. Pagina de conversacion con un Agente de Ia.
. porpuesta visual similar a https://stitch.withgoogle.com/
. Estructura responsive.
. Navar (tipo 3 puntos)
    . Preguntas Frecuentes
    . Foro
    . Guia de instrucciones
    . Enviar comentarios

.**Navegación**: Lateral persistente (no la desarrolles ahora, asume que existe).
. **Interfaz**: Soporte para modo claro/oscuro usando clases dark: de Tailwind.

.**Componente Principal**: Una lista de tarjetas o tabla que incluya:

    .Nombre, Propietario y Estado (Badge con colores: Activo=verde, Inactivo=gris, Fallando=rojo).

    .Skill Toggle: Sección colapsada que se expande con transición suave al hacer clic.

    .Acciones (Dropdown ⋮): Opciones "Configurar" (abre Modal con el system prompt) y "Eliminar".

### Restricciones
. sin css