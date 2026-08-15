---
title: "Clase Metered"
type: docs
weight: 3030
url: /es/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Metered()](#Metered__1) | Inicializa una nueva instancia de la clase Metered |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Obtiene el crédito de consumo |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Obtiene el tamaño del archivo de consumo |
| [get_product_name()](#get_product_name__3) | Obtiene el nombre del producto. |
| [is_metered_licensed()](#is_metered_licensed__4) | Comprueba si Metered está licenciado |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Establece la clave pública y privada de Metered.<br/>            Si compras una licencia Metered, al iniciar la aplicación, se debe llamar a esta API; normalmente, eso es suficiente. <br/>            Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, <br/>            para evitar este caso, deberías comprobar regularmente el estado de la licencia; si está en estado de evaluación, llama a esta API nuevamente. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Inicializa una nueva instancia de la clase Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Obtiene el crédito de consumo

**Returns**

| Tipo | Descripción |
| :- | :- |
| decimal | cantidad de consumo |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Obtiene el tamaño del archivo de consumo

**Returns**

| Tipo | Descripción |
| :- | :- |
| decimal | cantidad de consumo |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Obtiene el nombre del producto.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Nombre del producto licenciado |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Comprueba si Metered está licenciado

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero o falso |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Establece la clave pública y privada de Metered.<br/>            Si compras una licencia Metered, al iniciar la aplicación, se debe llamar a esta API; normalmente, eso es suficiente. <br/>            Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, <br/>            para evitar este caso, deberías comprobar regularmente el estado de la licencia; si está en estado de evaluación, llama a esta API nuevamente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| public_key | string | clave pública |
| private_key | string | clave privada |

