---
title: "XmpDate"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente la Date dans le paquet XMP."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Représente la Date dans le paquet XMP.

Une valeur date-heure est représentée en utilisant un sous-ensemble des formats définis dans Formats de date et d'heure: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initialise une nouvelle instance de la classe XmpDate. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initialise une nouvelle instance de la classe XmpDate. |
## Champs

| Champ | Description |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | La chaîne de format ISO 8601 (aller-retour). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Obtient la chaîne de format pour la valeur actuelle. |
| [getValue()](#getValue--) | Obtient ou définit la valeur de la date. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Renvoie la valeur de chaîne contenue au format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Obtient ou définit la valeur de la date. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initialise une nouvelle instance de la classe XmpDate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | Une valeur date-heure qui est représentée en utilisant un sous-ensemble du formatage ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initialise une nouvelle instance de la classe XmpDate.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateString | java.lang.String | La représentation sous forme de chaîne de la date. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


La chaîne de format ISO 8601 (aller-retour).

Voir plus: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFormat() {#getFormat--}
```
public String getFormat()
```


Obtient la chaîne de format pour la valeur actuelle.

Valeur: la chaîne de format pour la valeur actuelle.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Obtient ou définit la valeur de la date.

Valeur: la valeur de date.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Renvoie la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Renvoie la valeur de chaîne contenue au format XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Obtient ou définit la valeur de la date.

Valeur: la valeur de date.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

