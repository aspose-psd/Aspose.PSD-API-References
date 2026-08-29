---
title: "Font"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il font XMP."
type: docs
weight: 10
url: /it/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Rappresenta il font XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Font()](#Font--) | Inizializza una nuova istanza della classe  Font  . |
| [Font(String fontFamily)](#Font-java.lang.String-) | Inizializza una nuova istanza della classe  Font  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Aggiunge la chiave specificata. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Ottiene o imposta l'array di nomi file per i caratteri che compongono un font composito. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Ottiene o imposta lo stile del font. |
| [getFontFamily()](#getFontFamily--) | Ottiene o imposta la famiglia del font. |
| [getFontFileName()](#getFontFileName--) | Ottiene o imposta il nome file del font senza percorso completo. |
| [getFontName()](#getFontName--) | Ottiene o imposta il nome del font PostScript. |
| [getFontType()](#getFontType--) | Ottiene o imposta il tipo di font. |
| [getNamespaceUri()](#getNamespaceUri--) | Ottiene l'URI dello spazio dei nomi predefinito. |
| [getPrefix()](#getPrefix--) | Ottiene il prefisso. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione del font. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore stringa contenuto in formato XMP. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Ottiene o imposta un valore che indica se questo font è composito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Ottiene o imposta l'array di nomi file per i caratteri che compongono un font composito. |
| [setComposite(boolean value)](#setComposite-boolean-) | Ottiene o imposta un valore che indica se questo font è composito. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Ottiene o imposta lo stile del font. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Ottiene o imposta la famiglia del font. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Ottiene o imposta il nome file del font senza percorso completo. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Ottiene o imposta il nome del font PostScript. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Ottiene o imposta il tipo di font. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Ottiene o imposta la versione del font. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Inizializza una nuova istanza della classe  Font  .

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Inizializza una nuova istanza della classe  Font  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamily | java.lang.String | Famiglia del font. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Aggiunge la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.Object | Il valore a cui aggiungere. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Ottiene o imposta l'array di nomi file per i caratteri che compongono un font composito.

Valore: L'array di nomi file per i caratteri che compongono un font composito.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Ottiene o imposta lo stile del font.

Valore: Lo stile del font.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Ottiene o imposta la famiglia del font.

Valore: La famiglia del font.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Ottiene o imposta il nome file del font senza percorso completo.

Valore: Il nome file del font senza percorso completo.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Ottiene o imposta il nome del font PostScript.

Valore: Il nome del font PostScript.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Ottiene o imposta il tipo di font.

TrueType, Type 1, Open Type e così via. Valore: Il tipo di font.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ottiene l'URI dello spazio dei nomi predefinito.

**Returns:**
java.lang.String - L'URI di spazio dei nomi predefinito.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ottiene il prefisso.

**Returns:**
java.lang.String - Il prefisso.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Ottiene o imposta la versione del font.

/version per i font Type1 nameId 5 per Apple True Type e OpenType /CIDFontVersion per i font CID La stringa vuota per i font bitmap Valore: La versione del font.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore stringa contenuto in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore stringa contenuto in formato XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Ottiene o imposta un valore che indica se questo font è composito.

Valore:  true  se questo font è composito; altrimenti,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Ottiene o imposta l'array di nomi file per i caratteri che compongono un font composito.

Valore: L'array di nomi file per i caratteri che compongono un font composito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Ottiene o imposta un valore che indica se questo font è composito.

Valore:  true  se questo font è composito; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Ottiene o imposta lo stile del font.

Valore: Lo stile del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Ottiene o imposta la famiglia del font.

Valore: La famiglia del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Ottiene o imposta il nome file del font senza percorso completo.

Valore: Il nome file del font senza percorso completo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Ottiene o imposta il nome del font PostScript.

Valore: Il nome del font PostScript.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Ottiene o imposta il tipo di font.

TrueType, Type 1, Open Type e così via. Valore: Il tipo di font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Ottiene o imposta la versione del font.

/version per i font Type1 nameId 5 per Apple True Type e OpenType /CIDFontVersion per i font CID La stringa vuota per i font bitmap Valore: La versione del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

