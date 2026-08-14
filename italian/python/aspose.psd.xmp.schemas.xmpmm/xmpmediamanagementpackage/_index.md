---
title: "Classe XmpMediaManagementPackage"
type: docs
weight: 10
url: /it/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Inizializza una nuova istanza della classe XmpMediaManagementPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Ottiene l'URI dello spazio dei nomi. |
| prefisso | string | r | Ottiene il prefisso. |
| xml_namespace | string | r | Ottiene lo spazio dei nomi XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge la proprietà stringa. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_2) | Determina se la chiave specificata contiene la chiave. |
| [get_xml_value()](#get_xml_value__3) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_4) | Rimuove il valore con la chiave specificata. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Imposta il derived from. |
| [set_document_id(guid)](#set_document_id_guid_6) | Imposta l'identificatore del documento. |
| [set_document_id(guid)](#set_document_id_guid_7) | Imposta l'identificatore del documento. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Imposta l'ID dell'istanza. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Imposta l'ID dell'istanza. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Imposta l'ID del documento originale. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Imposta l'ID del documento originale. |
| [set_value(key, value)](#set_value_key_value_12) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Imposta il valore del tipo XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Inizializza una nuova istanza della classe XmpMediaManagementPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Aggiunge la proprietà stringa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | string | Il valore stringa. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Determina se la chiave specificata contiene la chiave.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave da verificare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se la chiave specificata contiene la chiave. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converte il valore XMP nella rappresentazione XML.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito nella rappresentazione XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Rimuove il valore con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore rimosso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se il valore con la chiave specificata è stato rimosso. |


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Imposta il derived from.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Il riferimento della risorsa. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Imposta l'identificatore del documento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | Guid | L'identificatore unico. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Imposta l'identificatore del documento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | string | L'identificatore unico. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Imposta l'ID dell'istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | Guid | L'identificatore unico. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Imposta l'ID dell'istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | string | L'identificatore unico. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Imposta l'ID del documento originale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | Guid | L'identificatore unico. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Imposta l'ID del documento originale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | string | L'identificatore unico. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Il valore da impostare. |

