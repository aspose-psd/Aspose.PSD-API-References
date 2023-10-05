---
title: Font
second_title: Aspose.PSD for Java API Reference
description: Defines a particular format for text including font face size and style attributes.
type: docs
weight: 46
url: /java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Initializes a new  com.aspose.psd.Font  that uses the specified existing  com.aspose.psd.Font  and  com.aspose.psd.FontStyle  enumeration. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initializes a new  com.aspose.psd.Font  using a specified size. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initializes a new  com.aspose.psd.Font  using a specified size and style. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initializes a new  com.aspose.psd.Font  using a specified size, style, unit, and character set. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initializes a new  com.aspose.psd.Font  using a specified size, style, and unit. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates an exact deep copy of this  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether the specified object is a  com.aspose.psd.Font  and has the same property values as this  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Gets a value indicating whether this  Font  is bold. |
| [getCharacterSet()](#getCharacterSet--) | Gets a byte value that specifies the character set that this  Font  uses. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Gets a value indicating whether this  Font  is italic. |
| [getName()](#getName--) | Gets the face name of this  Font . |
| [getSize()](#getSize--) | Gets the em-size of this  Font  measured in the units specified by the  P:Aspose.Imaging.Font.Unit  property. |
| [getStrikeout()](#getStrikeout--) | Gets a value indicating whether this  Font  specifies a horizontal line through the font. |
| [getStyle()](#getStyle--) | Gets style information for this  Font . |
| [getUnderline()](#getUnderline--) | Gets a value indicating whether this  Font  is underlined. |
| [getUnit()](#getUnit--) | Gets the unit of measure for this  Font . |
| [hashCode()](#hashCode--) | Gets the hash code for this  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initializes a new  com.aspose.psd.Font  using a specified size and unit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a human-readable string representation of this  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initializes a new  com.aspose.psd.Font  that uses the specified existing  com.aspose.psd.Font  and  com.aspose.psd.FontStyle  enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | The existing  com.aspose.psd.Font  from which to create the new  com.aspose.psd.Font . |
| newStyle | int | The  com.aspose.psd.FontStyle  to apply to the new  com.aspose.psd.Font . Multiple values of the  com.aspose.psd.FontStyle  enumeration can be combined with the OR operator. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initializes a new  com.aspose.psd.Font  using a specified size. The character set is set to  F:Aspose.Imaging.CharacterSet.Default , the graphics unit to  F:Aspose.Imaging.GraphicsUnit.Point , the font style to  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the  com.aspose.psd.Font  name. |
| emSize | float | The em-size, in points, of the new font. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initializes a new  com.aspose.psd.Font  using a specified size and style. The character set is set to  F:Aspose.Imaging.CharacterSet.Default , the graphics unit to  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the  com.aspose.psd.Font  name. |
| emSize | float | The em-size, in points, of the new font. |
| style | int | The  com.aspose.psd.FontStyle  of the new font. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initializes a new  com.aspose.psd.Font  using a specified size, style, unit, and character set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the  com.aspose.psd.Font  name. |
| emSize | float | The em-size of the new font in the units specified by the  unit  parameter. |
| style | int | The  com.aspose.psd.FontStyle  of the new font. |
| unit | int | The  com.aspose.psd.GraphicsUnit  of the new font. |
| characterSet | int | A character set to use for this font. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initializes a new  com.aspose.psd.Font  using a specified size, style, and unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the  com.aspose.psd.Font  name. |
| emSize | float | The em-size of the new font in the units specified by the  unit  parameter. |
| style | int | The  com.aspose.psd.FontStyle  of the new font. |
| unit | int | The  com.aspose.psd.GraphicsUnit  of the new font. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Creates an exact deep copy of this  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether the specified object is a  com.aspose.psd.Font  and has the same property values as this  com.aspose.psd.Font .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to test. |

**Returns:**
boolean - True if the  obj  parameter is a  com.aspose.psd.Font  and has the same property values as this  com.aspose.psd.Font ; otherwise, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Gets a value indicating whether this  Font  is bold.

**Returns:**
boolean - True if this  Font  is bold; otherwise, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Gets a byte value that specifies the character set that this  Font  uses.

**Returns:**
int - A character set that this  Font  uses.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gets a value indicating whether this  Font  is italic.

**Returns:**
boolean - True if this  Font  is italic; otherwise, false.
### getName() {#getName--}
```
public String getName()
```


Gets the face name of this  Font .

**Returns:**
java.lang.String - A string representation of the face name of this  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Gets the em-size of this  Font  measured in the units specified by the  P:Aspose.Imaging.Font.Unit  property.

**Returns:**
float - The em-size of this  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Gets a value indicating whether this  Font  specifies a horizontal line through the font.

**Returns:**
boolean - True if this  Font  has a horizontal line through it; otherwise, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets style information for this  Font .

**Returns:**
int - A  FontStyle  enumeration that contains style information for this  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Gets a value indicating whether this  Font  is underlined.

**Returns:**
boolean - True if this  Font  is underlined; otherwise, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Gets the unit of measure for this  Font .

**Returns:**
int - A  GraphicsUnit  that represents the unit of measure for this  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this  com.aspose.psd.Font .

**Returns:**
int - The hash code for this  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initializes a new  com.aspose.psd.Font  using a specified size and unit. The character set is set to  F:Aspose.Imaging.CharacterSet.Default , the style is set to  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | A string representation of the  com.aspose.psd.Font  name. |
| emSize | float | The em-size of the new font in the units specified by the  unit  parameter. |
| unit | int | The  com.aspose.psd.GraphicsUnit  of the new font. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  com.aspose.psd.Font .

**Returns:**
java.lang.String - A string that represents this  com.aspose.psd.Font .
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

