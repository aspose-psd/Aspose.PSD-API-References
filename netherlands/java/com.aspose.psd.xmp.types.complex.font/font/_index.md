---
title: "Lettertype"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vertegenwoordigt XMP Font."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Vertegenwoordigt XMP Font.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Font()](#Font--) | Initialiseert een nieuw exemplaar van de  Font  klasse. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initialiseert een nieuw exemplaar van de  Font  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Voegt de opgegeven sleutel toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Haalt op of stelt de array met bestandsnamen voor de lettertypen die een samengesteld lettertype vormen, in. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Haalt op of stelt de lettertype‑weergave in. |
| [getFontFamily()](#getFontFamily--) | Haalt op of stelt de lettertypefamilie in. |
| [getFontFileName()](#getFontFileName--) | Haalt op of stelt de bestandsnaam van het lettertype zonder volledig pad in. |
| [getFontName()](#getFontName--) | Haalt op of stelt de PostScript-lettertype‑naam in. |
| [getFontType()](#getFontType--) | Haalt op of stelt het lettertype‑type in. |
| [getNamespaceUri()](#getNamespaceUri--) | Haalt de standaard namespace‑URI op. |
| [getPrefix()](#getPrefix--) | Haalt het voorvoegsel op. |
| [getVersion()](#getVersion--) | Haalt op of stelt de lettertype‑versie in. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Haalt de tekenreeksinhoud op in XMP-indeling. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Haalt op of stelt een waarde in die aangeeft of dit lettertype samengesteld is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Haalt op of stelt de array met bestandsnamen voor de lettertypen die een samengesteld lettertype vormen, in. |
| [setComposite(boolean value)](#setComposite-boolean-) | Haalt op of stelt een waarde in die aangeeft of dit lettertype samengesteld is. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Haalt op of stelt de lettertype‑weergave in. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Haalt op of stelt de lettertypefamilie in. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Haalt op of stelt de bestandsnaam van het lettertype zonder volledig pad in. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Haalt op of stelt de PostScript-lettertype‑naam in. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Haalt op of stelt het lettertype‑type in. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Haalt op of stelt de lettertype‑versie in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Initialiseert een nieuw exemplaar van de  Font  klasse.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initialiseert een nieuw exemplaar van de  Font  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFamily | java.lang.String | Lettertypefamilie. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Voegt de opgegeven sleutel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| waarde | java.lang.Object | De waarde om aan toe te voegen. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Haalt op of stelt de array met bestandsnamen voor de lettertypen die een samengesteld lettertype vormen, in.

Waarde: De array van bestandsnamen voor de lettertypen die een samengesteld lettertype vormen.

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


Haalt op of stelt de lettertype‑weergave in.

Waarde: De lettertype‑weergave.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Haalt op of stelt de lettertypefamilie in.

Waarde: De lettertypefamilie.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Haalt op of stelt de bestandsnaam van het lettertype zonder volledig pad in.

Waarde: De bestandsnaam van het lettertype zonder volledig pad.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Haalt op of stelt de PostScript-lettertype‑naam in.

Waarde: De naam van het PostScript-lettertype.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Haalt op of stelt het lettertype‑type in.

TrueType, Type 1, Open Type, enzovoort. Waarde: Het lettertype‑type.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Haalt de standaard namespace‑URI op.

**Returns:**
java.lang.String - De standaard namespace-URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Haalt het voorvoegsel op.

**Returns:**
java.lang.String - De prefix.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Haalt op of stelt de lettertype‑versie in.

/version voor Type1 fonts nameId 5 voor Apple True Type en OpenType /CIDFontVersion voor CID fonts De lege tekenreeks voor bitmap fonts Waarde: De fontversie.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Haalt de tekenreeksinhoud op in XMP-indeling.

**Returns:**
java.lang.String - Retourneert de tekenreeksinhoud in XMP-indeling.
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


Haalt op of stelt een waarde in die aangeeft of dit lettertype samengesteld is.

Waarde:  true  als dit font samengesteld is; anders,  false .

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


Haalt op of stelt de array met bestandsnamen voor de lettertypen die een samengesteld lettertype vormen, in.

Waarde: De array van bestandsnamen voor de lettertypen die een samengesteld lettertype vormen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of dit lettertype samengesteld is.

Waarde:  true  als dit font samengesteld is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Haalt op of stelt de lettertype‑weergave in.

Waarde: De lettertype‑weergave.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Haalt op of stelt de lettertypefamilie in.

Waarde: De lettertypefamilie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Haalt op of stelt de bestandsnaam van het lettertype zonder volledig pad in.

Waarde: De bestandsnaam van het lettertype zonder volledig pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Haalt op of stelt de PostScript-lettertype‑naam in.

Waarde: De naam van het PostScript-lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Haalt op of stelt het lettertype‑type in.

TrueType, Type 1, Open Type, enzovoort. Waarde: Het lettertype‑type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Haalt op of stelt de lettertype‑versie in.

/version voor Type1 fonts nameId 5 voor Apple True Type en OpenType /CIDFontVersion voor CID fonts De lege tekenreeks voor bitmap fonts Waarde: De fontversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

