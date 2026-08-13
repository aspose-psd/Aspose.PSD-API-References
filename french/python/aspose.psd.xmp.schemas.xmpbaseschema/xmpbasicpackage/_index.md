---
title: "Classe XmpBasicPackage"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initialise une nouvelle instance de la classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initialise une nouvelle instance de la classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Valeur maximale de la note. |
| RATING_MIN [static] | int | r | Valeur minimale de la note. |
| RATING_REJECTED [static] | int | r | Valeur de note rejetée. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Ajoute la date de création de la ressource. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Ajoute la date de création de la ressource. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Définit l'outil du créateur. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Définit l'identifiant. |
| [set_label(label)](#set_label_label_9) | Définit l'étiquette. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Ajoute la date de dernière modification des métadonnées. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Ajoute la date de dernière modification des métadonnées. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Ajoute la date de dernière modification de la ressource. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Ajoute la date de dernière modification de la ressource. |
| [set_rating(choise)](#set_rating_choise_14) | Définit la note. |
| [set_value(key, value)](#set_value_key_value_15) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Définit la valeur du type XMP. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initialise une nouvelle instance de la classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initialise une nouvelle instance de la classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| préfixe | chaîne | Le préfixe. |
| namespace_uri | chaîne | L'URI de l'espace de noms. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Ajoute la date de création de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| created_date | datetime | Date de création. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Ajoute la date de création de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| created_date | chaîne | Date de création. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Définit l'outil du créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_tool | chaîne | Nom de l'outil. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Définit l'identifiant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| idenfifier | chaîne | L'idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Définit l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| label | chaîne | L'étiquette. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Ajoute la date de dernière modification des métadonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_date | datetime | Date des métadonnées. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Ajoute la date de dernière modification des métadonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_date | chaîne | Date des métadonnées. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Ajoute la date de dernière modification de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| modified_date | datetime | Date de dernière modification. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Ajoute la date de dernière modification de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| modified_date | chaîne | Date de dernière modification. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Définit la note.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| choise | int | De -1 à 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | La valeur à définir. |

