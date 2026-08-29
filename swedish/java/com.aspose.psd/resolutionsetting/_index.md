---
title: "ResolutionSetting"
second_title: "Aspose.PSD för Java API-referens"
description: "Upplösningsinställningen för bildsparalternativ."
type: docs
weight: 92
url: /sv/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

Upplösningsinställningen för bildsparalternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Initierar en ny instans av klassen ResolutionSetting. |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Initierar en ny instans av klassen ResolutionSetting. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Definierar PDF-sidstorlek beroende av DPI-upplösning hämtad från PdfOptions.ResolutionSettings eller, om den har standardvärden, från själva bilden. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar eller anger den horisontella upplösningen. |
| [getVerticalResolution()](#getVerticalResolution--) | Hämtar eller anger den vertikala upplösningen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Hämtar eller anger den horisontella upplösningen. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Hämtar eller anger den vertikala upplösningen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Initierar en ny instans av klassen ResolutionSetting.

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Initierar en ny instans av klassen ResolutionSetting.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| horizontalResolution | double | Den horisontella upplösningen. |
| verticalResolution | double | Den vertikala upplösningen. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Definierar PDF-sidstorlek beroende av DPI-upplösning hämtad från PdfOptions.ResolutionSettings eller, om den har standardvärden, från själva bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Bildens storlek. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Den ursprungliga upplösningen. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Den nya upplösningen. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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


Hämtar eller anger den horisontella upplösningen.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar eller anger den vertikala upplösningen.

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


Hämtar eller anger den horisontella upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Hämtar eller anger den vertikala upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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

