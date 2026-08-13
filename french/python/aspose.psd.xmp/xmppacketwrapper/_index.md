---
title: "Classe XmpPacketWrapper"
type: docs
weight: 450
url: /fr/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initialise une nouvelle instance de la classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initialise une nouvelle instance de la classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Obtient l'instruction de traitement de l'en-tête. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Obtient les métadonnées XMP. Facultatif. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Obtient le tableau de [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dans le XMP. |
| packages_count | int | r | Obtient le nombre de packages dans la structure XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Obtient l'instruction de traitement du trailer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Ajoute le package. |
| clear_packages() | Supprime tous les [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dans le XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Détermine si le package existe dans le wrapper XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Obtient le package par URI d'espace de noms. |
| [remove_package(package)](#remove_package_package_4) | Supprime le package XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initialise une nouvelle instance de la classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initialise une nouvelle instance de la classe [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | L'en-tête XMP de l'instruction de traitement. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Le trailer XMP de l'instruction de traitement. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Les métadonnées XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Ajoute le package.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Le package. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Détermine si le package existe dans le wrapper XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| namespace_uri | chaîne | URI du schéma du package. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie vrai si le package avec l'URI d'espace de noms spécifié existe dans le wrapper XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Obtient le package par URI d'espace de noms.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| namespace_uri | chaîne | L'URI du schéma du package. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Renvoie le package XMP pour l'URI d'espace de noms spécifié. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Supprime le package XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Le package. |

