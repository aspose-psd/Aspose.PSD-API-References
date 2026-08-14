---
title: "Classe XmpRightsManagementPackage"
type: docs
weight: 10
url: /it/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Inizializza una nuova istanza della classe XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Imposta il certificato. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Contrassegna come contenuto a gestione dei diritti |
| [set_owners(owners)](#set_owners_owners_7) | Imposta i proprietari. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Imposta i termini di utilizzo. |
| [set_value(key, value)](#set_value_key_value_9) | Imposta il valore. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Imposta la dichiarazione web. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Imposta il valore del tipo XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Inizializza una nuova istanza della classe XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Imposta il certificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificato | string | Il certificato. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Contrassegna come contenuto a gestione dei diritti

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | bool | se impostato su <c>true</c> indica che questa è una risorsa a gestione dei diritti. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Imposta i proprietari.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| proprietari | string | I proprietari. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Imposta i termini di utilizzo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | I termini di utilizzo. |

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

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Imposta la dichiarazione web.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| web_statement_url | string | L'URL della dichiarazione web. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Il valore da impostare. |

