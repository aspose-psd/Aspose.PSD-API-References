---
title: "Classe PdfPackage"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initialise une nouvelle instance de la classe PdfPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | chaîne | r | Obtient l'URI de l'espace de noms. |
| préfixe | chaîne | r | Obtient le préfixe. |
| xml_namespace | chaîne | r | Obtient l'espace de noms XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Ajoute une propriété de chaîne. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_2) | Détermine si la clé spécifiée contient la clé. |
| [get_xml_value()](#get_xml_value__3) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_4) | Supprime la valeur avec la clé spécifiée. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Définit les keywords. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Définit la version PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Définit le nom de l'outil qui a créé le Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Définit le trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Définit la valeur du type XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initialise une nouvelle instance de la classe PdfPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Ajoute une propriété de chaîne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| valeur | chaîne | La valeur de chaîne. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Détermine si la clé spécifiée contient la clé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La clé à vérifier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie vrai si la clé spécifiée contient la clé. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Convertit la valeur XMP en représentation XML.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Renvoie la valeur XMP convertie en représentation XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Supprime la valeur avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur supprimée. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie vrai si la valeur avec la clé spécifiée a été supprimée. |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Définit les keywords.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| keywords | chaîne | Les keywords. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Définit la version PDF.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| version | chaîne | Version Pdf, par exemple : 1.0, 1.3 etc. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Définit le nom de l'outil qui a créé le Pdf.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| producer | chaîne | Le nom du producer. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Définit le trapped.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| is_trapped | bool | si défini sur <c>true</c> le document a été trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | La valeur à définir. |

