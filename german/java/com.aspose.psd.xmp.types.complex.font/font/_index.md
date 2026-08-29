---
title: "Schriftart"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt XMP-Schriftart dar."
type: docs
weight: 10
url: /de/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Stellt XMP-Schriftart dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Font()](#Font--) | Initialisiert eine neue Instanz der  Font  Klasse. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initialisiert eine neue Instanz der  Font  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Fügt den angegebenen Schlüssel hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Liest oder setzt das Array von Dateinamen für die Schriftarten, aus denen eine zusammengesetzte Schriftart besteht. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Liest oder setzt die Schriftart. |
| [getFontFamily()](#getFontFamily--) | Liest oder setzt die Schriftfamilie. |
| [getFontFileName()](#getFontFileName--) | Liest oder setzt den Schriftdateinamen ohne vollständigen Pfad. |
| [getFontName()](#getFontName--) | Liest oder setzt den PostScript-Schriftartnamen. |
| [getFontType()](#getFontType--) | Liest oder setzt den Schrifttyp. |
| [getNamespaceUri()](#getNamespaceUri--) | Liest den Standard-Namespace-URI. |
| [getPrefix()](#getPrefix--) | Liest das Präfix. |
| [getVersion()](#getVersion--) | Liest oder setzt die Schriftversion. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Liest oder setzt einen Wert, der angibt, ob diese Schrift zusammengesetzt ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Liest oder setzt das Array von Dateinamen für die Schriftarten, aus denen eine zusammengesetzte Schriftart besteht. |
| [setComposite(boolean value)](#setComposite-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Schrift zusammengesetzt ist. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Liest oder setzt die Schriftart. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Liest oder setzt die Schriftfamilie. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Liest oder setzt den Schriftdateinamen ohne vollständigen Pfad. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Liest oder setzt den PostScript-Schriftartnamen. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Liest oder setzt den Schrifttyp. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Liest oder setzt die Schriftversion. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Initialisiert eine neue Instanz der  Font  Klasse.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initialisiert eine neue Instanz der  Font  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamily | java.lang.String | Schriftfamilie. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Fügt den angegebenen Schlüssel hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.Object | Der Wert, zu dem hinzugefügt werden soll. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Liest oder setzt das Array von Dateinamen für die Schriftarten, aus denen eine zusammengesetzte Schriftart besteht.

Wert: Das Array von Dateinamen für die Schriften, die eine zusammengesetzte Schrift bilden.

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


Liest oder setzt die Schriftart.

Wert: Der Schriftschnitt.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Liest oder setzt die Schriftfamilie.

Wert: Die Schriftfamilie.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Liest oder setzt den Schriftdateinamen ohne vollständigen Pfad.

Wert: Der Schriftdateiname ohne vollständigen Pfad.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Liest oder setzt den PostScript-Schriftartnamen.

Wert: Der Name des PostScript-Schriftnamens.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Liest oder setzt den Schrifttyp.

TrueType, Type 1, Open Type und so weiter. Wert: Der Schrifttyp.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Liest den Standard-Namespace-URI.

**Returns:**
java.lang.String - Der Standard-Namespace-URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest das Präfix.

**Returns:**
java.lang.String - Das Präfix.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Liest oder setzt die Schriftversion.

/version für Type1 fonts nameId 5 für Apple True Type und OpenType /CIDFontVersion für CID fonts Die leere Zeichenkette für bitmap fonts Wert: Die Schriftart-Version.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenkettenwert im XMP-Format.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
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


Liest oder setzt einen Wert, der angibt, ob diese Schrift zusammengesetzt ist.

Wert:  true  wenn diese Schriftart zusammengesetzt ist; andernfalls,  false .

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


Liest oder setzt das Array von Dateinamen für die Schriftarten, aus denen eine zusammengesetzte Schriftart besteht.

Wert: Das Array von Dateinamen für die Schriften, die eine zusammengesetzte Schrift bilden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Schrift zusammengesetzt ist.

Wert:  true  wenn diese Schriftart zusammengesetzt ist; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Liest oder setzt die Schriftart.

Wert: Der Schriftschnitt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Liest oder setzt die Schriftfamilie.

Wert: Die Schriftfamilie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Liest oder setzt den Schriftdateinamen ohne vollständigen Pfad.

Wert: Der Schriftdateiname ohne vollständigen Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Liest oder setzt den PostScript-Schriftartnamen.

Wert: Der Name des PostScript-Schriftnamens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Liest oder setzt den Schrifttyp.

TrueType, Type 1, Open Type und so weiter. Wert: Der Schrifttyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Liest oder setzt die Schriftversion.

/version für Type1 fonts nameId 5 für Apple True Type und OpenType /CIDFontVersion für CID fonts Die leere Zeichenkette für bitmap fonts Wert: Die Schriftart-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

