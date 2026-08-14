---
title: "Classe XmpPacketWrapper"
type: docs
weight: 450
url: /it/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Inizializza una nuova istanza della classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Inizializza una nuova istanza della classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Ottiene l'istruzione di elaborazione dell'intestazione. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Ottiene i metadati XMP. Facoltativo. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Ottiene l'array di [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) all'interno di XMP. |
| packages_count | int | r | Ottiene la quantità di pacchetti all'interno della struttura XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Ottiene l'istruzione di elaborazione del trailer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Aggiunge il pacchetto. |
| clear_packages() | Rimuove tutti i [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) all'interno di XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determina se il pacchetto esiste nel wrapper XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Ottiene il pacchetto per URI dello spazio dei nomi. |
| [remove_package(package)](#remove_package_package_4) | Rimuove il pacchetto XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Inizializza una nuova istanza della classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Inizializza una nuova istanza della classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | L'intestazione XMP dell'istruzione di elaborazione. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Il trailer XMP dell'istruzione di elaborazione. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | I metadati XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Aggiunge il pacchetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Il pacchetto. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determina se il pacchetto esiste nel wrapper XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| namespace_uri | string | URI dello schema del pacchetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se il pacchetto con l'URI dello spazio dei nomi specificato esiste nel wrapper XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Ottiene il pacchetto per URI dello spazio dei nomi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| namespace_uri | string | L'URI dello schema del pacchetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Restituisce il pacchetto XMP per l'URI dello spazio dei nomi specificato. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Rimuove il pacchetto XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Il pacchetto. |

