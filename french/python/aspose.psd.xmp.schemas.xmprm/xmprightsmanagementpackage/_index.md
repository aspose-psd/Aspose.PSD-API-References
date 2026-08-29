---
title: "Classe XmpRightsManagementPackage"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initialise une nouvelle instance de la classe XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Définit le certificat. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Marque comme contenu de gestion des droits |
| [set_owners(owners)](#set_owners_owners_7) | Définit les propriétaires. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Définit les conditions d'utilisation. |
| [set_value(key, value)](#set_value_key_value_9) | Définit la valeur. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Définit la déclaration web. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Définit la valeur du type XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initialise une nouvelle instance de la classe XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Définit le certificat.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| certificat | chaîne | Le certificat. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Marque comme contenu de gestion des droits

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | bool | si défini sur <c>true</c> que ceci est une ressource gérée par des droits. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Définit les propriétaires.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| propriétaires | chaîne | Les propriétaires. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Définit les conditions d'utilisation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Les conditions d'utilisation. |

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

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Définit la déclaration web.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| web_statement_url | chaîne | L'URL de la déclaration Web. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | chaîne | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | La valeur à définir. |

