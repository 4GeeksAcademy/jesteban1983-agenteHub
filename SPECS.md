# TAREA: Componete gestión de Agentes - AgentHub

## Contexto

. Panel Admin en entorno React/Tailwind. 

## Especificaciones

### Tarea

. modifica index.html

### Requisitos

**[Especificaciones Bisuales]**

. Estilo: Inspirado en Material 3/Stich (minimalista, tarjetas blancas/negras).

. Modo: Dark/Light nativo de Tailwind.

. Layout: Responsive, asumiendo Sidebar existente.

**[Funcionalidad Requerida]**

1. **Tabla/Lista**: Columna [ Nombre, Propietario, Estado (Badges Color)].

2. **Skill Togle**: Acordeón con transición 'duration-300'.

3. **Dropdown**: Menú con "configurar", "Eliminar".

**[REQUERIMIENTOS DE INTERFAZ]**

Implementa las siguientes secciones con datos hardcodeados para visualización:

1. Dashboard & Global

Interacciones: Toggle de modo claro/oscuro funcional (clases dark: de Tailwind) que persista en la navegación.

Métricas: 4 tarjetas (Ingresos, Descuentos, Agentes Activos, Agentes Fallando) con iconos y valores fijos.

Gráfico: Marcador de posición de ancho completo para actividad semanal.

2. Gestión de Usuarios y Contratos

Usuarios: Tabla de 5 filas (nombre, email, plan, badge de estado). Acciones: "Ver detalle" (abre modal con registro completo) y "Eliminar".

Contrataciones: Tabla de 4 contratos con desglose de skills y precios en un modal de "Ver detalle".

3. Gestión de Agentes y Skills

Agentes: Lista de 4 agentes con badges de estado y lista de skills colapsada (transición suave al expandir).

Configuración: El dropdown de acción "Configurar" debe abrir un modal con un <textarea> editable para el prompt del sistema.

Skills: Catálogo de 4 capacidades con descripción y contador de agentes habilitados.

4. Log de Errores

Registros: Al menos 6 entradas con timestamp y badges de gravedad por código de color.

Detalle: Modal con traza completa del error y opción "Marcar como resuelto".



### Restricciones

. Formato: Código listo para insertar en index.html.

. Estilos: Solo clases Tailwind integradas. No CSS externo.

. Sin explicaciones ni saludos.