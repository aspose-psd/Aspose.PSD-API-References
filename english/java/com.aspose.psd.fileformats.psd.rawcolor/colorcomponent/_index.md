---
title: ColorComponent
second_title: Aspose.PSD for Java API Reference
description: Color component is an abstraction over Channel Value and Channel Value.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Color component is an abstraction over Channel Value and Channel Value. Any color is composed from an array of ColorComponent
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Initializes a new instance of the [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Gets the bit depth of Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description of Color Component |
| [getFullName()](#getFullName--) | Gets the full name of color component with name and space-separated description |
| [getName()](#getName--) | Gets the name of color component. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Gets the permitted full names. |
| [getValue()](#getValue--) | Gets or sets the value. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Gets or sets the value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Initializes a new instance of the [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) class. Please check

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitDepth | byte | The bit depth. |
| fullName | java.lang.String | The full name. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Gets the bit depth of Color Component/Channel

Value: The bit depth.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description of Color Component

Value: The description.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Gets the full name of color component with name and space-separated description

Value: The full name.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Gets the name of color component.

Value: The name.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Gets the permitted full names.

Value: The permitted full names.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Gets or sets the value. Please note, if you try to set value that is more than possible stored in current bit depth, you'll get an exception

Value: The value.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Gets or sets the value. Please note, if you try to set value that is more than possible stored in current bit depth, you'll get an exception

Value: The value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

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

