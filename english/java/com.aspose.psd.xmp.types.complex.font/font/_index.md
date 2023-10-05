---
title: Font
second_title: Aspose.PSD for Java API Reference
description: Represents XMP Font.
type: docs
weight: 10
url: /java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Represents XMP Font.
## Constructors

| Constructor | Description |
| --- | --- |
| [Font()](#Font--) | Initializes a new instance of the  Font  class. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initializes a new instance of the  Font  class. |
## Methods

| Method | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Adds the specified key. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Gets or sets the array of file names for the fonts that make up a composite font. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Gets or sets the font face. |
| [getFontFamily()](#getFontFamily--) | Gets or sets the font family. |
| [getFontFileName()](#getFontFileName--) | Gets or sets the font file name without full path. |
| [getFontName()](#getFontName--) | Gets or sets the PostScript font name. |
| [getFontType()](#getFontType--) | Gets or sets the font type. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the default namespace URI. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getVersion()](#getVersion--) | Gets or sets the font version. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Gets or sets a value indicating whether this font is composite. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Gets or sets the array of file names for the fonts that make up a composite font. |
| [setComposite(boolean value)](#setComposite-boolean-) | Gets or sets a value indicating whether this font is composite. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Gets or sets the font face. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Gets or sets the font family. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Gets or sets the font file name without full path. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Gets or sets the PostScript font name. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Gets or sets the font type. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Gets or sets the font version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Initializes a new instance of the  Font  class.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initializes a new instance of the  Font  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Adds the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.Object | The value to add to. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Gets or sets the array of file names for the fonts that make up a composite font.

Value: The array of file names for the fonts that make up a composite font.

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


Gets or sets the font face.

Value: The font face.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Gets or sets the font family.

Value: The font family.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Gets or sets the font file name without full path.

Value: The font file name without full path.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets or sets the PostScript font name.

Value: The name of PostScript font name.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Gets or sets the font type.

TrueType, Type 1, Open Type, and so on. Value: The font type.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the default namespace URI.

**Returns:**
java.lang.String - The default namespace URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

**Returns:**
java.lang.String - The prefix.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets or sets the font version.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts Value: The font version.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
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


Gets or sets a value indicating whether this font is composite.

Value:  true  if this font is composite; otherwise,  false .

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


Gets or sets the array of file names for the fonts that make up a composite font.

Value: The array of file names for the fonts that make up a composite font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Gets or sets a value indicating whether this font is composite.

Value:  true  if this font is composite; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Gets or sets the font face.

Value: The font face.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Gets or sets the font family.

Value: The font family.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Gets or sets the font file name without full path.

Value: The font file name without full path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Gets or sets the PostScript font name.

Value: The name of PostScript font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Gets or sets the font type.

TrueType, Type 1, Open Type, and so on. Value: The font type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Gets or sets the font version.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts Value: The font version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

