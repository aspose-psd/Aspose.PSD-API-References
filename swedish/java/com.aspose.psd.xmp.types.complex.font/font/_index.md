---
title: "Typsnitt"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar XMP Font."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Representerar XMP Font.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Font()](#Font--) | Initierar en ny instans av klassen  Font  . |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initierar en ny instans av klassen  Font  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Lägger till den angivna nyckeln. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Hämtar eller anger arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Hämtar eller anger typsnittets stil. |
| [getFontFamily()](#getFontFamily--) | Hämtar eller anger typsnittsfamiljen. |
| [getFontFileName()](#getFontFileName--) | Hämtar eller anger typsnittsfilens namn utan fullständig sökväg. |
| [getFontName()](#getFontName--) | Hämtar eller anger PostScript-typsnittets namn. |
| [getFontType()](#getFontType--) | Hämtar eller anger typsnittstypen. |
| [getNamespaceUri()](#getNamespaceUri--) | Hämtar standardnamnutrymmets URI. |
| [getPrefix()](#getPrefix--) | Hämtar prefixet. |
| [getVersion()](#getVersion--) | Hämtar eller anger typsnittsversionen. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Hämtar eller anger ett värde som indikerar om detta typsnitt är sammansatt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Hämtar eller anger arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt. |
| [setComposite(boolean value)](#setComposite-boolean-) | Hämtar eller anger ett värde som indikerar om detta typsnitt är sammansatt. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Hämtar eller anger typsnittets stil. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Hämtar eller anger typsnittsfamiljen. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Hämtar eller anger typsnittsfilens namn utan fullständig sökväg. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Hämtar eller anger PostScript-typsnittets namn. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Hämtar eller anger typsnittstypen. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Hämtar eller anger typsnittsversionen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Initierar en ny instans av klassen  Font  .

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initierar en ny instans av klassen  Font  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamily | java.lang.String | Typsnittsfamilj. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Lägger till den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.Object | Värdet att lägga till i. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Hämtar eller anger arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt.

Värde: Arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt.

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


Hämtar eller anger typsnittets stil.

Värde: Typsnittets stil.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Hämtar eller anger typsnittsfamiljen.

Värde: Typsnittsfamiljen.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Hämtar eller anger typsnittsfilens namn utan fullständig sökväg.

Värde: Typsnittsfilens namn utan fullständig sökväg.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Hämtar eller anger PostScript-typsnittets namn.

Värde: Namnet på PostScript-typsnittet.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Hämtar eller anger typsnittstypen.

TrueType, Type 1, Open Type och så vidare. Värde: Typsnittstypen.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Hämtar standardnamnutrymmets URI.

**Returns:**
java.lang.String - Standardnamnutrymmes URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar prefixet.

**Returns:**
java.lang.String - Prefixet.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Hämtar eller anger typsnittsversionen.

/version för Type1-teckensnitt nameId 5 för Apple True Type och OpenType /CIDFontVersion för CID-teckensnitt Den tomma strängen för bitmap-teckensnitt Värde: Teckensnittsversionen.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
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


Hämtar eller anger ett värde som indikerar om detta typsnitt är sammansatt.

Värde:  true  om detta teckensnitt är sammansatt; annars,  false .

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


Hämtar eller anger arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt.

Värde: Arrayen med filnamn för de typsnitt som utgör ett sammansatt typsnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta typsnitt är sammansatt.

Värde:  true  om detta teckensnitt är sammansatt; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Hämtar eller anger typsnittets stil.

Värde: Typsnittets stil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Hämtar eller anger typsnittsfamiljen.

Värde: Typsnittsfamiljen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Hämtar eller anger typsnittsfilens namn utan fullständig sökväg.

Värde: Typsnittsfilens namn utan fullständig sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Hämtar eller anger PostScript-typsnittets namn.

Värde: Namnet på PostScript-typsnittet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Hämtar eller anger typsnittstypen.

TrueType, Type 1, Open Type och så vidare. Värde: Typsnittstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Hämtar eller anger typsnittsversionen.

/version för Type1-teckensnitt nameId 5 för Apple True Type och OpenType /CIDFontVersion för CID-teckensnitt Den tomma strängen för bitmap-teckensnitt Värde: Teckensnittsversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

