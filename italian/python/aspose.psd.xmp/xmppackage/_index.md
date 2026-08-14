---
title: "Classe XmpPackage"
type: docs
weight: 430
url: /it/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Ottiene l'URI dello spazio dei nomi. |
| prefisso | string | r | Ottiene il prefisso. |
| xml_namespace | string | r | Ottiene lo spazio dei nomi XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge il valore. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_2) | Determina se la chiave specificata contiene la chiave. |
| [get_xml_value()](#get_xml_value__3) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_4) | Rimuove il valore con la chiave specificata. |
| [set_value(key, value)](#set_value_key_value_5) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Imposta il valore del tipo XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Aggiunge il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | string | Il valore a cui aggiungere. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Il valore da impostare. |

