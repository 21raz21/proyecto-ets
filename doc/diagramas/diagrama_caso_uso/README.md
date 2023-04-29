# En esta carpeta se verán el diagrama de caso de uso
## Índice:
- [Introducción](#introduccion)
- [Diagrama de caso de uso](#diagrama)
- [Especificaciones del diagrama](#especificaciones)
    - [Especificación de los actores](#actores)

### Introducción <a name="introduccion">.
Una reconocida página web quiere ofrecer a sus clientes la posibilidad de comprar productos. A partir de esto, el cliente puede buscar el producto y elegir todos los productos que quiera pero para ello debe de autenticarse. Antes de comprar, el administrador de la base de datos se serciora de que existan productos suficientes. En el caso de que no sea así, el dueño de la página envía un aviso y repone productos. Una vez que haya suficiente stock, el administrador comprueba de que el pago se realizó correctamentey, a raíz de esto, aprueba o deniega la operación. 

El cliente también puede cancelar el pago del producto seleccionado. 

Por otro lado, el dueño puede cambiar el precio de los productos. 

### Diagrama <a name="diagrama"> de caso de uso.

<img src="https://github.com/21raz21/proyecto-ets/blob/feature_9/doc/img/vending_diagrama_caso_uso.png">

### Especificaciones <a name="especificaciones"> del diagrama.

#### Especificación de los actores <a name="actores">.

##### ACTOR 1

|**ACTOR 1**        | ADMINISTRADOR                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Comprueba el pago y el stock               |
| **CARACTERÍSTICAS** | El administrador debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **fecha** | 29/04/2023  |


##### ACTOR 2

|**ACTOR 2**        | DUEÑO                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Cambia el precio de los productos y repone el stock |               |
| **CARACTERÍSTICAS** | El dueño debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **fecha** | 29/04/2023  |


##### ACTOR 3


|**ACTOR 3**        | CLIENTE                              | 
|------------------ |:-------------------------------------------|
|**DESCRIPCIÓN**    | Puede uscar, seleccionar y comprar productos |              |
| **CARACTERÍSTICAS** | El cliente debe de estar autenticado |
| **RELACIOONES** |  |
| **REFERENCIAS** |  |
| **NOTAS** |  |
| **AUTOR** | Yamila Ramos |
| **fecha** | 29/04/2023  |