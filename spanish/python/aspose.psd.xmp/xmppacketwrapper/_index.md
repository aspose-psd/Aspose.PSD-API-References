---
title: "Clase XmpPacketWrapper"
type: docs
weight: 450
url: /es/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Inicializa una nueva instancia de la clase [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Inicializa una nueva instancia de la clase [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Obtiene la instrucción de procesamiento del encabezado. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Obtiene los metadatos XMP. Opcional. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Obtiene una matriz de [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dentro de XMP. |
| packages_count | int | r | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Obtiene la instrucción de procesamiento del tráiler. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Agrega el paquete. |
| clear_packages() | Elimina todos los [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dentro de XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determina si el paquete existe en el envoltorio XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Obtiene el paquete por URI de espacio de nombres. |
| [remove_package(package)](#remove_package_package_4) | Elimina el paquete XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Inicializa una nueva instancia de la clase [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Inicializa una nueva instancia de la clase [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | El encabezado XMP de la instrucción de procesamiento. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | El tráiler XMP de la instrucción de procesamiento. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Los metadatos XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Agrega el paquete.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | El paquete. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determina si el paquete existe en el envoltorio XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| namespace_uri | string | URI del esquema del paquete. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve true si el paquete con el URI de espacio de nombres especificado existe en el envoltorio XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Obtiene el paquete por URI de espacio de nombres.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| namespace_uri | string | El URI del esquema del paquete. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Devuelve el paquete XMP para el URI del espacio de nombres especificado. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Elimina el paquete XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | El paquete. |

