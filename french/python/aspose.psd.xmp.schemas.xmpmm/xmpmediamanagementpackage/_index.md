---
title: "XmpMediaManagementPackage Classe"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initialise une nouvelle instance de la classe XmpMediaManagementPackage |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Définit le dérivé de. |
| [set_document_id(guid)](#set_document_id_guid_6) | Définit l'identifiant du document. |
| [set_document_id(guid)](#set_document_id_guid_7) | Définit l'identifiant du document. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Définit l'ID d'instance. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Définit l'ID d'instance. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Définit l'ID du document original. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Définit l'ID du document original. |
| [set_value(key, value)](#set_value_key_value_12) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Définit la valeur du type XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initialise une nouvelle instance de la classe XmpMediaManagementPackage

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Définit le dérivé de.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | La référence de la ressource. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Définit l'identifiant du document.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | Guid | L'identifiant unique. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Définit l'identifiant du document.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | chaîne | L'identifiant unique. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Définit l'ID d'instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | Guid | L'identifiant unique. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Définit l'ID d'instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | chaîne | L'identifiant unique. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Définit l'ID du document original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | Guid | L'identifiant unique. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Définit l'ID du document original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | chaîne | L'identifiant unique. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | La valeur à définir. |

