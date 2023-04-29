# En esta carpeta se verán el diagrama de caso de uso
## Índice:
- [Introducción](#introduccion)
- [Diagrama de caso de uso](#diagrama)
- [Especificaciones del diagrama](#especificaciones)
    - [Especificación de los actores](#actores)
    - [Especificación de los casos de uso](#uso)
### Introducción <a name="introduccion">.
Una reconocida página web quiere ofrecer a sus clientes la posibilidad de comprar productos. A partir de esto, el cliente puede buscar el producto y elegir todos los productos que quiera pero para ello debe de autenticarse. Antes de comprar, el administrador de la base de datos se serciora de que existan productos suficientes. En el caso de que no sea así, el dueño de la página envía un aviso y repone productos. Una vez que haya suficiente stock, el administrador comprueba de que el pago se realizó correctamentey, a raíz de esto, aprueba o deniega la operación. 

El cliente también puede cancelar el pago del producto seleccionado. 

Por otro lado, el dueño puede cambiar el precio de los productos. 

### Diagrama <a name="diagrama"> de caso de uso.

<img src="https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/img/vending_diagrama_caso_uso.png">

### Especificaciones <a name="especificaciones"> del diagrama.

#### Especificación de los actores. <a name="actores">

##### ACTOR 1

|**ACTOR 1**        | ADMINISTRADOR                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Comprueba el pago y el stock               |
| **CARACTERÍSTICAS** | El administrador debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **FECHA** | 29/04/2023  |


##### ACTOR 2

|**ACTOR 2**        | DUEÑO                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Cambia el precio de los productos y repone el stock |               
| **CARACTERÍSTICAS** | El dueño debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **FECHA** | 29/04/2023  |


##### ACTOR 3


|**ACTOR 3**        | CLIENTE                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Puede buscar, seleccionar y comprar productos |              
| **CARACTERÍSTICAS** | El cliente debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **FECHA** | 29/04/2023  |

#### Especificación de los casos de uso. <a name="uso">

##### CASO DE USO 1

|**CASO DE USO 1**        | COMPROBAR PAGO                         | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Administrador |
| **DESCRIPCIÓN** | El administrador puede comprobar los pagos de los clientes |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 2

|**CASO DE USO 1**        |COMPROBAR STOCK                       | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Administrador y dueño |
| **DESCRIPCIÓN** | Los actores pueden comprobar el stock |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticados |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticados |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 3

|**CASO DE USO 3**        | APROBAR OPERACIÓN                       | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Administrador |
| **DESCRIPCIÓN** | El administrador puede aprobar operaciones de pago |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado y comprobar pago|
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 4

|**CASO DE USO 4**        | DENEGAR OPERACIÓN                       | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Administrador |
| **DESCRIPCIÓN** | El administrador puede denegar operaciones de pago |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado y comprobar pago|
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 5

|**CASO DE USO 5**        | REPONER STOCK                       | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Dueño |
| **DESCRIPCIÓN** | El dueño puede reponer el stock |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado y comprobar si hay stock suficiente |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado y comprobar stock|
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 6

|**CASO DE USO 6**        | Cambiar precio                    | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Duueño |
| **DESCRIPCIÓN** | El dueño puede cambair el precio de los productos |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 7

|**CASO DE USO 7**        | BUSCAR PRODUCTOS                     | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Cliente |
| **DESCRIPCIÓN** | El cliente puede buscar productos |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 8

|**CASO DE USO 8**        | SELECCIONAR PRODUCTOS                     | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Cliente |
| **DESCRIPCIÓN** | El cliente puede seleccionar los productos |
| **FLUJO BÁSICO** | Atenticarse --> Comprobar stock --> Seleccionar productos  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado y comprobar stock|
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 9

|**CASO DE USO 9**        |  COMPRAR PRODUCTOS                    | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Cliente |
| **DESCRIPCIÓN** | El cliente puede comprar productos |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** |   |
| **REQUISITOS** | Estar autenticado |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |

##### CASO DE USO 10

|**CASO DE USO 10**        | MANDAR AVISO                       | 
|------------------ |:-------------------------------------------|
|**FUENTE**    | El caso de uso se encuentra en este [documento](https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/Anteproyecto.md)  |              
| **ACTOR** | Administrador |
| **DESCRIPCIÓN** | El administrador manda un aviso en caso de que no hay stock suficiente |
| **FLUJO BÁSICO** |  |
| **CONDICIONES PREVIAS** | Estar autenticado |
| **CONDICIONES POSTERIORES** | Reponer stock  |
| **REQUISITOS** | Estar autenticado |
| **NOTAS** |   |
| **AUTOR** | Yamila Ramos  |
| **FECHA** | 29/04/2023  |