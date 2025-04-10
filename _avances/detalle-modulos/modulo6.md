# Control de entrega - José Pfuño

## Sobre el módulo

Considere como título el nombre del módulo y coloque el nombre del integrante para asociarlo con facilidad. Luego responda a las siguientes preguntas:
- 1. ¿Cual es el objetivo de su módulo?

    Garantizar que los productos avícolas (pollo, huevos, etc.) sean entregados al cliente final en las condiciones pactadas (tiempo, cantidad, calidad y documentación), validando el cumplimiento del proceso y cerrando el ciclo logístico con trazabilidad y transparencia.

2. ¿A quién beneficia el funcionamiento de su módulo (área interna, cliente - persona o empresa)?
    
    En el area interna reduce los reclamos por errores de entrega, facilita la logistica inversa para las devoluciones, proporciona tambien evidencia digital para posibles disputas en la entrega.

    Para los clientes, el beneficio es la operacion sin interrupción de los restaurantes, la facilidad de documentación como facturas para los procesos de ellos, y un menor riesgo de recepción de productos en mal estado en pro de la calidad.

3. ¿Qué resultado genera su módulo? ¿Es un producto o un servicio? ¿Qué características tiene?

    El módulo de Control y Confirmación de Entrega se comporta más como un servicio que como un producto tangible, diferenciándose de otros módulos de la cadena de suministro por su enfoque en validación, comunicación y cierre de ciclo.

    a. Enfoque en interacción y validación

        No mueve físicamente la mercancía (como Gestión de Carga), sino que certifica que el proceso se completó correctamente.

    b. Generación de datos para mejora continua

        -Transforma eventos físicos (entregas exitosas/fallidas) en datos analizables (ej.: % de incidencias por conductor).

        -Módulos como Recepción de Órdenes son más transaccionales (registran, pero no analizan).

4. ¿Qué recursos se emplean para obtener dicho resultado?

    a. Recursos tecnológicos
        Impresoras portatiles, app movil personalizada, plataforma central (backend), APIs de terceros.
    b. Recursos humanos
        Personal logístico como conductores y supervisores.

5. ¿Cómo se planifican el uso de estos recursos?

    2. Ejecución del Módulo de Control y Confirmación de Entrega

        Paso 3: Proceso de entrega física (despues de finalizar el modulo de monitoreo de rutas)

        Conductor entrega el pedido y el receptor (cliente) verifica:

        -Cantidad: Escaneo de QR o código de barras en los paquetes.

        -Calidad: Inspección visual (ej.: pollo sin decoloración, empaques sellados).

        Evidencias digitales:

        -Firma electrónica o huella del receptor.

        -Foto del producto entregado (opcional, para altares valor).

        Paso 4: Confirmación digital y cierre

        App móvil envía datos en tiempo real al ERP de San Fernando:

        -Actualiza inventario.

        -Marca el pedido como "Entregado" o "Incidente Registrado".

        Cliente recibe comprobante por email/SMS (factura, guía).

    3. Transición a Gestión de Reclamos y Devoluciones

        Paso 5: Detección de incidencias post-entrega

        Caso 1: Entrega exitosa → El proceso termina aquí.

        Caso 2: Reclamo inmediato (ej.: faltante o producto en mal estado):

6. ¿Cómo se reserva el uso / la propiedad del producto o servicio generado?


