---
title: "ResolutionSetting"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Auflösungseinstellung für Bildspeicheroptionen."
type: docs
weight: 92
url: /de/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

Die Auflösungseinstellung für Bildspeicheroptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Initialisiert eine neue Instanz der ResolutionSetting-Klasse. |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Initialisiert eine neue Instanz der ResolutionSetting-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Definiert die PDF-Seitengröße abhängig von der DPI-Auflösung, die aus PdfOptions.ResolutionSettings entnommen wird oder, falls Standardwerte vorhanden sind, aus dem Bild selbst. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Liest oder setzt die horizontale Auflösung. |
| [getVerticalResolution()](#getVerticalResolution--) | Liest oder setzt die vertikale Auflösung. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Liest oder setzt die horizontale Auflösung. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Liest oder setzt die vertikale Auflösung. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Initialisiert eine neue Instanz der ResolutionSetting-Klasse.

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Initialisiert eine neue Instanz der ResolutionSetting-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| horizontalResolution | double | Die horizontale Auflösung. |
| verticalResolution | double | Die vertikale Auflösung. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Definiert die PDF-Seitengröße abhängig von der DPI-Auflösung, die aus PdfOptions.ResolutionSettings entnommen wird oder, falls Standardwerte vorhanden sind, aus dem Bild selbst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Die Bildgröße. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Die ursprüngliche Auflösung. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Die neue Auflösung. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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


Liest oder setzt die horizontale Auflösung.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Liest oder setzt die vertikale Auflösung.

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


Liest oder setzt die horizontale Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Liest oder setzt die vertikale Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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

