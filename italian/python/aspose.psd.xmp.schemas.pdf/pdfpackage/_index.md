---
title: "Classe PdfPackage"
type: docs
weight: 10
url: /it/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Inizializza una nuova istanza della classe PdfPackage |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | Imposta le parole chiave. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Imposta la versione PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Imposta il nome dello strumento che ha creato il Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Imposta il trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Imposta il valore del tipo XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Inizializza una nuova istanza della classe PdfPackage

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Imposta le parole chiave.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| keywords | string | Le parole chiave. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Imposta la versione PDF.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| version | string | Versione Pdf, ad esempio: 1.0, 1.3 ecc. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Imposta il nome dello strumento che ha creato il Pdf.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| producer | string | Il nome del produttore. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Imposta il trapped.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_trapped | bool | se impostato a <c>true</c> il documento è stato trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Il valore da impostare. |

