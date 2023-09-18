---
title: ResolutionSetting
second_title: Aspose.PSD for Java API Reference
description: The resolution setting for image save options.
type: docs
weight: 93
url: /java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

The resolution setting for image save options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Initializes a new instance of the  ResolutionSetting  class. |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Initializes a new instance of the  ResolutionSetting  class. |
## Methods

| Method | Description |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Defines PDF page size in dependency of DPI resolution taken from PdfOptions.ResolutionSettings or if it has default values; from the image itself |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets or sets the horizontal resolution. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets or sets the vertical resolution. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Gets or sets the horizontal resolution. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Gets or sets the vertical resolution. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Initializes a new instance of the  ResolutionSetting  class.

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Initializes a new instance of the  ResolutionSetting  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| horizontalResolution | double | The horizontal resolution. |
| verticalResolution | double | The vertical resolution. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Defines PDF page size in dependency of DPI resolution taken from PdfOptions.ResolutionSettings or if it has default values; from the image itself

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | The image size. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | The original resolution. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | The new resolution. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Gets or sets the horizontal resolution.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets or sets the vertical resolution.

**Returns:**
double
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




### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Gets or sets the horizontal resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Gets or sets the vertical resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

