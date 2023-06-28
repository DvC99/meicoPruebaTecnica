# Prueba Técnica para Desarrollador de Software

## MEICO S.A - Gerencia Administrativa y Financiera - Dirección de Sistemas - Centro de Valoración Desarrollador de Software

¡Bienvenido a la prueba técnica para el puesto de Desarrollador de Software en MEICO S.A! A continuación encontrarás una serie de casos que deberás resolver. Asegúrate de revisar y completar todos los casos antes de finalizar.

## CASO 1: Desarrollo de un nuevo proyecto para soportar el proceso de toma de pedidos

Le han encargado el desarrollo de un nuevo proyecto para soportar el proceso de toma de pedidos de una compañía comercial. Esta compañía distribuye y entrega productos a clientes mayoristas y tiendas. Los vendedores visitan a los clientes para tomar los pedidos durante estas visitas. La solución que se desarrolle debe tener en cuenta la información contenida en los sistemas de información existentes en la empresa y ser capaz de integrarse con ellos.

**Tareas a realizar:**

- ¿A qué cargos dentro de la compañía escogería como líderes, por qué?

  Teniendo en cuenta el origen que tiene el proyecto y la finalidad de este, escogería a dos cargos de la empresa, que, posiblemente, podrían liderar el proyecto gracias al conocimiento en los requerimientos que tienen de este. Estos son los siguientes cargos:

  - Gerente de Operaciones: Es el encargado de supervisar y coordinar las decisiones relacionadas con los pedidos realizados y la distribución o entrega de estos, por lo que él conoce el funcionamiento al pie de la letra del proceso de ventas. Además, él ha liderado otros tipos de proyectos, por lo que podría desempeñarse bien con la gestión de este.

  - Gerente de Ventas: Es el principal actor en la acción de venta con el cliente. Él es el encargado de tomar los pedidos durante las visitas a los clientes, por lo que el gerente de Ventas será fundamental para proporcionar información sobre los requisitos y necesidades del equipo de ventas, que es el usuario final del aplicativo.

- ¿A quiénes involucraría en el levantamiento de requerimientos? ¿Por qué?

  Para realizar el levantamiento de requerimientos, es importante involucrar a las siguientes partes que intervienen con el cliente directamente o en el proceso de ventas:

  - Departamento de Ventas: Principalmente, son los usuarios finales de la aplicación, por lo que los hace poseedores de un conocimiento sobre los procesos de toma de pedidos. El levantamiento de requerimientos, de su parte, garantiza que el sistema, cumpla los requerimientos exigidos.

  - Departamento de Logística: Está encargado de la distribución y entrega de los productos, por lo que participan en la otra parte del proceso de ventas. Su participación durante el levantamiento de los requerimientos, garantiza que se va a tener en cuenta en la solución los procesos de logística.

- ¿Cuál es la metodología de proyecto que implementaría? Mencione hitos y documentos de control del proyecto.

  Para el proyecto, optaría por una metodología ágil como Scrum, que se adapta bien a los proyectos de desarrollo de software. Ya que permite un desarrollo del proyecto, donde ambas partes trabajan de manera cercana (equipo de desarrollo y los usuarios finales), y también, permite la entrega incremental y continua del aplicativo.

  Algunos hitos y documentos de control del proyecto que incluye la metodología Scrum podrían incluir:

  - Reuniones de planificación de sprint: Al inicio de cada sprint, se deben establecer objetivos y prioridades de los requerimientos, determinar cuáles funcionalidades se van a desarrollar y asignar las tareas al equipo.

  - Backlog del producto: Documentación de los requerimientos y funcionalidades del sistema, teniendo en cuenta su valor y relevancia para el negocio.

  - Sprint backlog: El desglose de la documentación en una lista de tareas específicas que se abordarán durante cada sprint.

  - Reuniones diarias de seguimiento: Reuniones al inicio del día para revisar el progreso, identificar obstáculos y ajustar el plan del sprint si es necesario.

  - Revisiones de sprint: Al finalizar el sprint, se hace una reunión para mirar el avance logrado. También sirve para obtener retroalimentación de los usuarios y realizar ajustes según sea necesario.

  - Retrospectivas de sprint: Evaluación del sprint por parte del equipo de desarrollo, donde se identifican áreas a mejorar y se establecen acciones correctivas de ser necesario.

- ¿Qué módulos del sistema central de la compañía estarían integrados en esta solución? ¿Por qué?

  Los principales módulos del sistema de la compañía, que estarían integrados en la solución, serían los siguientes:

  - Sistema de Información de Clientes: Principalmente, para acceder a la información relevante de los clientes, datos de contacto, historial de pedidos y estado de la cuenta.

  - Sistema de Gestión de Inventarios: Para obtener información sobre los productos disponibles y mantener actualizado el stock del aplicativo.

- Explique el flujo del proceso de negocio que usted le propondría a la compañía.

  1. Los vendedores visitan a los clientes o los clientes hacen el pedido por el aplicativo, esto depende de la información que se le solicite o el trato que se tenga con los clientes.

  2. Los pedidos se validan automáticamente, disponibilidad y sé verificar la cartera de los clientes y su historial de pagos.

  3. Una vez validados, los pedidos se envían al departamento de logística para su procesamiento y preparación para la entrega.

  4. El sistema de gestión de inventarios se actualiza con la información de los pedidos.

  5. Los productos se entregan a los clientes mayoristas y tiendas según los procesos establecidos por el departamento de logística.  

- Explique la arquitectura técnica de la solución que usted le propondría a la compañía.

  La arquitectura técnica de la solución propuesta, podría ser cliente-servidor, donde la aplicación de toma de pedidos se ejecuta en los dispositivos móviles de los vendedores (clientes) y se comunica con un servidor central para almacenar y procesar los datos. Se podrían implementar una API para la integración con los sistemas existentes (inventario y logística de entrega), y bases de datos para el almacenamiento de la información. Además, se implementaría tecnologías móviles y web para garantizar la accesibilidad y usabilidad del sistema en diferentes dispositivos y plataformas.

## CASO 2: Diferencia entre un servicio Web basado en SOAP y otro basado en REST

¿Cuál es la diferencia principal entre un servicio Web basado en SOAP y otro basado en REST?
  
  SOAP es un protocolo de comunicación en XML para intercambiar información entre sistemas, se centra en la interoperatividad y permite una comunicación más compleja. REST es un estilo de arquitectura que utiliza métodos HTTP/HTTPS, basado en principios y estándares webs y enfocado en la simplicidad, escalabilidad y rendimiento.

## CASO 3: Análisis de query's SQL y rendimiento

**Numeral 3.1** La siguiente tabla (PEDIDOS), contiene el detalle de líneas de pedidos facturados, así:

| Orden_no |     Tipo    | Fechapedido | articulo | Vlrtotal | cliente |
|----------|-------------|-------------|----------|----------|---------|
|  633436  | MAYORISTA   |  20/2/2022  |  93710   | 1785589  | 109191  |
|  633436  | MAYORISTA   |  20/2/2022  |  93714   | 2584832  | 109191  |
|  634091  |     TAT     |  24/2/2021  |  93712   |  243000  | 109188  |
|  634091  |     TAT     |  24/3/2019  |  93716   |  203399  | 109188  |
|  634091  |     TAT     |  24/2/2014  |  93717   |  156600  | 109188  |
|  634132  | MAYORISTA   |  24/2/2014  |  93712   |  891000  | 109186  |
|  634132  | MAYORISTA   |  24/2/2014  |  93715   |  444401  | 109186  |
|  634132  | MAYORISTA   |  24/2/2014  |  93716   |  745798  | 109186  |
|  634132  | MAYORISTA   |  24/1/2022  |  93719   |  313501  | 109186  |
|  634132  | MAYORISTA   |  24/5/2019  |  94030   |     1    | 109186  |

La siguiente tabla muestra el maestro de ARTICULO con sus columnas correspondientes.

| articulo |   Nombre Artículo  | PrecioUnitario |  Estado  |
|----------|-------------------|----------------|----------|
|  93710   |    Agua Clara     |     15000      |  ACTIVO  |
|  93714   |     Old Parr      |     20000      |  ACTIVO  |
|   93712   | Aceite Selecto  |     5400       | INACTIVO |
|  93716   |    Harina Pan     |     15400      |  ACTIVO  |
|  93717   | Bombilla Ahorradora |    4747     | INACTIVO |

**Se le pide diseñar una consulta SQL** de control que nos muestre los artículos facturados, cumpliendo con las siguientes consideraciones:

- Pedidos con fecha entre el 01/01/2021 y el 31/05/2022.

- Debe mostrar todos los pedidos sin importar si el artículo existe o no en el maestro de artículos.

- Columnas del informe: No. Orden, Fecha Pedido, Articulo, Nombre artículo, Precio unitario, VlrTotal, Estado.

- Para los casos en que el artículo facturado no exista en el maestro de artículos debe mostrar, en las columnas correspondientes de nombre y precio unitario, la siguiente información:

  - **Nombre:** ‘INEXISTENTE’
  - **Precio Unitario:** ‘-1’

- La columna ESTADO se debe desplegar de la siguiente forma:

  - Para los casos en que el ESTADO del artículo sea INACTIVO o el artículo no exista en el maestro de artículos, debe devolver la frase **‘FUERA DE STOCK’**, en caso contrario mostrar la frase **‘EN STOCK’**.

```SQL
    SELECT
        p.Orden_no,
        p.Fechapedido,
        p.articulo,
        COALESCE(a."Nombre Artículo", 'INEXISTENTE') AS "Nombre artículo",
        COALESCE(a.PrecioUnitario, -1) AS "Precio unitario",
        p.Vlrtotal,
        CASE
            WHEN a.Estado = 'INACTIVO' OR a.articulo IS NULL THEN 'FUERA DE STOCK'
            ELSE 'EN STOCK'
        END AS Estado
    FROM PEDIDOS p
    LEFT JOIN ARTICULO a ON p.articulo = a.articulo
    WHERE p.Fechapedido BETWEEN '2021-01-01' AND '2022-05-31';
```

**Numeral 3.2** usted encuentra en el monitoreo a la base de datos, que la siguiente consulta está afectando el rendimiento del servidor:

```SQL
    SELECT 
        cliente, 
        fechapedido, 
        artículo, 
        vlrtotal
    FROM pedidos
    WHERE fechapedido >= '2018-05-01'
    AND artículo NOT IN (
        SELECT art_codigo
        FROM articulo
        WHERE estado = 'INACTIVO'
    );
```

describa un query optimizado para esta consulta, ¿Qué índice sugeriría?

```SQL
    SELECT 
        p.cliente, 
        p.fechapedido, 
        p.articulo, 
        p.vlrtotal
    FROM pedidos p
    LEFT JOIN articulo a ON p.articulo = a.articulo AND a.estado = 'INACTIVO'
    WHERE p.fechapedido >= '2018-05-01' AND a.articulo IS NULL;
```

**Numeral 3.3** Teniendo como base la tabla SALARIES:

```SQL
    SALARIES (
        Professor_Name (TEXT),
        Department (TEXT),
        Salary (INT)
    )
```

Marque el Query que devuelva el departamento con el salario promedio más alto junto con ese salario promedio. Por cada una de las opciones descartadas, explique ¿por qué las descartaría?

| Opción | Query | Justificación |
|:------:|-------|---------------|
|        | SELECT Department, AVG(Salary) FROM SALARIES GROUP BY DEPARTMENT ORDER BY AVG(Salary); | Esta consulta calcula el salario promedio por departamento y los ordena de forma ascendente, pero no muestra solo el departamento con mayor promedio. |
|        | SELECT Department, AVG(Salary) FROM SALARIES ORDER BY AVG(Salary) DESC LIMIT 1; | Esta consulta realiza lo pedido pero calcula dos veces el promedio del salario por departamento. |
|        | SELECT Department, AVG(Salary) FROM SALARIES GROUP BY AVG(Salary) DESC LIMIT 1; | El uso de GROUP BY AVG(Salary) no sirve, ya que la agrupación se debe hacer por el campo "Department".|
|        | SELECT Department, AVG(Salary) FROM SALARIES GROUP BY DEPARTMENT ORDER BY AVG(Salary) DESC LIMIT 1; | Está seria la mejor opción solo que en el GROUP BY no se coloca bien el nombre de la columna.|

**Numeral 3.4** Con la misma tabla salaries diseñe un query que devuelva los departamentos que se encuentran repetidos, cuantas veces se repite y ordénelos del que más se repite al que menos se repite.

```SQL
    SELECT 
        Department, 
        COUNT(*) AS Repetitions
    FROM SALARIES
    GROUP BY Department
    HAVING Repetitions > 1
    ORDER BY Repetitions DESC;
```

**Numeral 3.5** Con la misma tabla salaries Diseñe un query que regrese todos los departamentos contenidos en la tabla SALARIES (sin duplicados).

```SQL
    SELECT DISTINCT 
        Department
    FROM SALARIES;
```

## CASO 4: Envío de datos de un formulario

Cree un formulario que solicite la carga de dos valores enteros y muestre en otra página el resultado de la suma de los dos valores capturados por teclado.

- **Formulario de entrada:**

    ![Formulario en primera pagina](https://github.com/DvC99/meicoPruebaTecnica/blob/6ea4f9218e321a6a33e3e9e4fc37d7768b835288/Caso4/pagina1.png)

- **Resultado de la suma:**

    ![Resultado en segunda pagina](https://github.com/DvC99/meicoPruebaTecnica/blob/6ea4f9218e321a6a33e3e9e4fc37d7768b835288/Caso4/pagina2.png)

- **Muestra error número negativo:**

    ![Formulario error negativos](https://github.com/DvC99/meicoPruebaTecnica/blob/6ea4f9218e321a6a33e3e9e4fc37d7768b835288/Caso4/muestraErrorPagina1.png)

## CASO 5: Revisión de CSS

Revise el código CSS proporcionado y determine el color de fondo del elemento con una clase de .box.

```CSS
    .box {
    background-color: blue;
    background: url(images/star.png?raw=png) no-repeat left top;
    }
```

  1. black
  2. ~~blue~~
  3. transparent
  4. white

## CASO 6: Re-escritura de función

¿Cómo puedes reescribir esta función usando la sintaxis de la función de flecha?.

  1. let product => (x,y) { <´br /> x * y; <´br />}

  2. let product = (x,y) => x*y;
  
  3. let product => x*y;
  
  4. let product = (x,y) -> x*y;

## CASO 7: Creación de mensaje JSON

Arme un mensaje JSON con los datos proporcionados:
  
- Nombre
- Edad
- Telefonos
  - Tipo de teléfono
  - Número de teléfono
- Email.

```JSON
    {
        "Nombre": "Juan",
        "Edad": 12,
        "Telefonos": [
            {
                "Tipo": "Celular",
                "Numero": "3020010210"
            },
            {
                "Tipo": "Celular",
                "Numero": "3020010210"
            }
        ],
        "Email": "dadad@hooms.com"
    }
```

## CASO 8: Extracción de datos de un archivo JSON

Genere un programa para extraer los datos del archivo JSON generado en el caso anterior y mostrarlos en formato de lista en una página web.

¡Mucho éxito en la resolución de los casos!
