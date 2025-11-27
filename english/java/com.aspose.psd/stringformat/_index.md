---
title: StringFormat
second_title: Aspose.PSD for Java API Reference
description: Encapsulates text layout information such as alignment orientation and tab stops display manipulations such as ellipsis insertion and national digit substitution and OpenType features.
type: docs
weight: 106
url: /java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initializes a new  com.aspose.psd.StringFormat  object. |
| [StringFormat(int options)](#StringFormat-int-) | Initializes a new  com.aspose.psd.StringFormat  object with the specified  com.aspose.psd.StringFormatFlags  enumeration and language. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Initializes a new  com.aspose.psd.StringFormat  object from the specified existing  com.aspose.psd.StringFormat  object. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a deep clone of this  com.aspose.psd.StringFormat  object. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets text alignment information on the vertical plane. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Gets the language that is used when local digits are substituted for western digits. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Gets the method to be used for digit substitution. |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| [getFormatFlags()](#getFormatFlags--) | Gets a  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information. |
| [getGenericDefault()](#getGenericDefault--) | Gets a generic default  com.aspose.psd.StringFormat  object. |
| [getGenericTypographic()](#getGenericTypographic--) | Gets a generic typographic  com.aspose.psd.StringFormat  object. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Gets the  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object. |
| [getLineAlignment()](#getLineAlignment--) | Gets the line alignment on the horizontal plane. |
| [getTabStops()](#getTabStops--) | Gets an array of distances between tab stops in the units specified by the  P:Aspose.Imaging.getGraphics().PageUnit  property. |
| [getTrimming()](#getTrimming--) | Gets the  com.aspose.psd.StringTrimming  enumeration for this  com.aspose.psd.StringFormat  object. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Sets text alignment information on the vertical plane. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Sets the language that is used when local digits are substituted for western digits. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Sets the method to be used for digit substitution. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Sets a  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Sets the  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Sets the line alignment on the horizontal plane. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Sets tab stops for this  com.aspose.psd.StringFormat  object. |
| [setTrimming(int value)](#setTrimming-int-) | Sets the  com.aspose.psd.StringTrimming  enumeration for this  com.aspose.psd.StringFormat  object. |
| [toString()](#toString--) | Converts this  com.aspose.psd.StringFormat  object to a human-readable string. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initializes a new  com.aspose.psd.StringFormat  object.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initializes a new  com.aspose.psd.StringFormat  object with the specified  com.aspose.psd.StringFormatFlags  enumeration and language.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | int | The  com.aspose.psd.StringFormatFlags  enumeration for the new  com.aspose.psd.StringFormat  object. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initializes a new  com.aspose.psd.StringFormat  object from the specified existing  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | The  com.aspose.psd.StringFormat  object from which to initialize the new  com.aspose.psd.StringFormat  object. |

### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Creates a deep clone of this  com.aspose.psd.StringFormat  object.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets text alignment information on the vertical plane.

**Returns:**
int - A  com.aspose.psd.StringAlignment  enumeration that specifies text alignment information.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Gets the language that is used when local digits are substituted for western digits.

**Returns:**
int - A National Language Support (NLS) language identifier that identifies the language that will be used when local digits are substituted for western digits. You can pass the  P:System.Globalization.CultureInfo.LCID  property of a  System.Globalization.CultureInfo  object as the NLS language identifier. For example, suppose you create a  System.Globalization.CultureInfo  object by passing the string "ar-EG" to a  System.Globalization.CultureInfo  constructor. If you pass the  P:System.Globalization.CultureInfo.LCID  property of that  System.Globalization.CultureInfo  object along with.  com.aspose.psd.StringDigitSubstitute.Traditional  to the  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  method, then Arabic-Indic digits will be substituted for western digits at display time.

The setter is introduced for the obsolete method setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Gets the method to be used for digit substitution.

**Returns:**
int - A  com.aspose.psd.StringDigitSubstitute  enumeration value that specifies how to substitute characters in a string that cannot be displayed because they are not supported by the current font.

The setter is introduced for the obsolete method SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Gets the number of spaces between the beginning of a line of text and the first tab stop.

**Returns:**
float - The first tab offset.

The property is introduced for removed method GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Gets a  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information.

**Returns:**
int - A  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Gets a generic default  com.aspose.psd.StringFormat  object.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Gets a generic typographic  com.aspose.psd.StringFormat  object.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Gets the  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object.

**Returns:**
int - The  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object, the default is  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Gets the line alignment on the horizontal plane.

**Returns:**
int - A  com.aspose.psd.StringAlignment  enumeration that represents the line alignment.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Gets an array of distances between tab stops in the units specified by the  P:Aspose.Imaging.getGraphics().PageUnit  property.

**Returns:**
float[] - The tab stops.

The property is introduced for removed method GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Gets the  com.aspose.psd.StringTrimming  enumeration for this  com.aspose.psd.StringFormat  object.

**Returns:**
int - A  com.aspose.psd.StringTrimming  enumeration that indicates how text drawn with this  com.aspose.psd.StringFormat  object is trimmed when it exceeds the edges of the layout rectangle.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets text alignment information on the vertical plane.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  com.aspose.psd.StringAlignment  enumeration that specifies text alignment information. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Sets the language that is used when local digits are substituted for western digits.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A National Language Support (NLS) language identifier that identifies the language that will be used when local digits are substituted for western digits. You can pass the  P:System.Globalization.CultureInfo.LCID  property of a  System.Globalization.CultureInfo  object as the NLS language identifier. For example, suppose you create a  System.Globalization.CultureInfo  object by passing the string "ar-EG" to a  System.Globalization.CultureInfo  constructor. If you pass the  P:System.Globalization.CultureInfo.LCID  property of that  System.Globalization.CultureInfo  object along with.  com.aspose.psd.StringDigitSubstitute.Traditional  to the  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  method, then Arabic-Indic digits will be substituted for western digits at display time.

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Sets the method to be used for digit substitution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  com.aspose.psd.StringDigitSubstitute  enumeration value that specifies how to substitute characters in a string that cannot be displayed because they are not supported by the current font.

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Sets a  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  com.aspose.psd.StringFormatFlags  enumeration that contains formatting information. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Sets the  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The  com.aspose.psd.HotkeyPrefix  object for this  com.aspose.psd.StringFormat  object, the default is  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Sets the line alignment on the horizontal plane.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  com.aspose.psd.StringAlignment  enumeration that represents the line alignment. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Sets tab stops for this  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstTabOffset | float | The number of spaces between the beginning of a line of text and the first tab stop. |
| tabStops | float[] | An array of distances between tab stops in the units specified by the  com.aspose.psd.Graphics.PageUnit  property. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Sets the  com.aspose.psd.StringTrimming  enumeration for this  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  com.aspose.psd.StringTrimming  enumeration that indicates how text drawn with this  com.aspose.psd.StringFormat  object is trimmed when it exceeds the edges of the layout rectangle. |

### toString() {#toString--}
```
public String toString()
```


Converts this  com.aspose.psd.StringFormat  object to a human-readable string.

**Returns:**
java.lang.String - A string representation of this  com.aspose.psd.StringFormat  object.
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

