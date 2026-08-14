---
title: "Classe XmpBasicPackage"
type: docs
weight: 10
url: /it/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Inizializza una nuova istanza della classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Inizializza una nuova istanza della classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Valore massimo della valutazione. |
| RATING_MIN [static] | int | r | Valore minimo della valutazione. |
| RATING_REJECTED [static] | int | r | Valore di valutazione rifiutata. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Aggiunge la data di creazione della risorsa. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Aggiunge la data di creazione della risorsa. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Imposta lo strumento creatore. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Imposta l'identificatore. |
| [set_label(label)](#set_label_label_9) | Imposta l'etichetta. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Aggiunge la data dell'ultima modifica dei metadati. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Aggiunge la data dell'ultima modifica dei metadati. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Aggiunge la data dell'ultima modifica della risorsa. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Aggiunge la data dell'ultima modifica della risorsa. |
| [set_rating(choise)](#set_rating_choise_14) | Imposta la valutazione. |
| [set_value(key, value)](#set_value_key_value_15) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Imposta il valore del tipo XMP. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Inizializza una nuova istanza della classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Inizializza una nuova istanza della classe [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prefisso | string | Il prefisso. |
| namespace_uri | string | L'URI del namespace. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Aggiunge la data di creazione della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| created_date | datetime | Data di creazione. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Aggiunge la data di creazione della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| created_date | string | Data di creazione. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Imposta lo strumento creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_tool | string | Nome dello strumento. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Imposta l'identificatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| identificatore | string | L'identificatore. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Imposta l'etichetta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | string | L'etichetta. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_date | datetime | Data dei metadati. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_date | string | Data dei metadati. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modified_date | datetime | Data dell'ultima modifica. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modified_date | string | Data dell'ultima modifica. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Imposta la valutazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scelta | int | Da -1 a 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Il valore da impostare. |

