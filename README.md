# *Markdown*
Este repositorio esta dedicado a la escritura de Mardown's, ideas en la organización de proyectos, mensajes alerta y tipología en general.

## *Estructuras De Proyectos:*

### *Estructura Por Tipos:*
Organización en proyectos pequeños, la escabilidad del proyecto es reducida a cierto punto.
```Estructura Por Tipos
└──src/
    ├───assets/
    ├───api/
    ├───configs/
    ├───components/
    |   ├───SingUpForm.tsx
    |   ├───Employees.tsx
    |   ├───PaymentForm.tsx
    |   └──Button.tsx
    ├───hooks/
    |   ├───usePayment.tsx
    |   ├───useUpdateEmployees.tsx
    |   ├───useEmployees.tsx
    |   └──useAuth.tsx
    ├───lib/
    ├───services/
    ├───states/
    └───utils/
```

### *Estructura Por Features:* 
Organización por tipo y por feature, refleja el producto dentro de la carpeta de cada tipo, Carpeta-->Componentes.
```Estructura Por Features
└──src/
    ├───assets/
    ├───api/
    ├───configs/
    ├───components/
    |   ├───auth/
    |   |   └──SingUpForm.tsx
    |   ├───payment/
    |   |   └──Payment.tsx
    |   |   └──SingUpForm.tsx
    |   ├───common/
    |   |   └──Button.tsx
    |   |   └──SingUpForm.tsx
    |   ├───employees/
    |   |   ├──EmployeeSummary.tsx
    |   |   └──EmployeeSummary.tsx
    ├───hooks/
    |   ├───auth/
    |   |   └──useAuth.ts
    |   ├───payment/
    |   |   └──Payment.ts
    |   └──employees/
    |      ├──useEmployees.ts
    |      └──useUpdateEmployees.ts
    ├───lib/
    ├───services/
    ├───states/
    └───utils/
```

## *Screaming Arquitecture:*
Indicar en la carpeta que es lo que hacemos, dividir las responsabilidades Actor-->Carpeta-->Componentes.
```Screaming Arquitecture
└──src/
    ├───assets/
    ├───modules/
    |   ├───core/
    |   |   ├───components/

    ├───hooks/
    |   ├───usePayment.tsx
    |   ├───useUpdateEmployees.tsx
    |   ├───useEmployees.tsx
    |   └──useAuth.tsx
    ├───lib/
    ├───services/
    ├───states/
    └───utils/
```


## *Nota Inicial en Markdown: Código Fuente*
    > **Note:**
    > Esto es una nota

## *Nota Inicial en Markdown: Visualización*
> **Note:**
> This is a note

## *Alertas en Markdown: Código fuente*

    > [!NOTE]
    > Esto es información adicional que puede ayudar al usuario.

    > [!TIP]
    > Un consejo o una sugerencia.

    > [!IMPORTANT]
    > Información crucial.

    > [!WARNING]
    > Necesita atención del usuario.

    > [!CAUTION]
    > consecuencias negativas si no haces caso.


## *Alertas en Markdown: Visualización*

> [!NOTE]
> Esto es información adicional que puede ayudar al usuario.

> [!TIP]
> Un consejo o una sugerencia.

> [!IMPORTANT]
> Información crucial.

> [!WARNING]
> Necesita atención del usuario.

> [!CAUTION]
> consecuencias egativas si no haces caso.

## *Encabezados: Código Fuente*
Existeb seis (6) niveles de títulos de Markdown:
 
    # Este es el primer nivel de encabezado (H1)
    ## Este es el segundo nivel de encabezado (H2)
    ...
    ###### Este es el sexto nivel de encabezado (H6)

> [!NOTE]
> Esto es un ejemplo de la asignacion de niveles haciendo uso de los elementos anteriormente mencionados.


## *Texto en negrita y cursiva: Código Fuente*
Para formatear el texto en negrita , enciérrelo entre dos asteriscos:

    This text is **bold**.

Para formatear el texto en cursiva , enciérrelo entre un solo asterisco:

    This text is *italic*.

Para formatear el texto en negrita y cursiva , enciérrelo entre tres asteriscos:
    
    This text is both ***bold and italic***.


## *Tablas en Mardown: Código Fuente*
Para crear una tabla con markdown es necesario utilizar la barra vertical "|" para indicar la division de las columnas:
        
    | User: | dg2c4 |

Para marcar la división del encabezado de las columnas y centrar el texto, se utiliza la barra vertical y guiones "-":

    |------|--------|

Para continuar solo utilizar la barra verticar "|" y el texto dentro de cada una, teniendo en cuenta que el numero de barras divide la cantidad de columnas:

    # Tabla 2x2
    | User: | dg2c4 |
    |-------|-------|
    | User: | dg2c4 |

    # Tabla 4x4
    | User: | dg2c4 | Security | Alpha |
    |-------|-------|----------|-------|
    | User: | dg2c4 | Security | Alpha |
    | User: | dg2c4 | Security | Alpha |

> [!NOTE]
> Esto es un ejemplo de la división entre columnas haciendo uso de los elementos anteriormente mencionados.

## *Tablas en Mardown: Visualización*

| User: | dg2c4 | Security | Alpha |
|-------|-------|----------|-------|
| User: | dg2c4 | Security | Alpha |
| User: | dg2c4 | Security | Alpha |

> [!NOTE]
> Esto es un ejemplo de la la visualización de tablas haciendo uso de los elementos anteriormente mencionados.


## Created By:
    https://github.com/dg2c4
