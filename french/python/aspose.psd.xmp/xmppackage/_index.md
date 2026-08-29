---
title: "XmpPackage Classe"
type: docs
weight: 430
url: /fr/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | chaîne | r | Obtient l'URI de l'espace de noms. |
| préfixe | chaîne | r | Obtient le préfixe. |
| xml_namespace | chaîne | r | Obtient l'espace de noms XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Ajoute la valeur. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_2) | Détermine si la clé spécifiée contient la clé. |
| [get_xml_value()](#get_xml_value__3) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_4) | Supprime la valeur avec la clé spécifiée. |
| [set_value(key, value)](#set_value_key_value_5) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Définit la valeur du type XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Ajoute la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| valeur | chaîne | La valeur à ajouter à. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | La valeur à définir. |

