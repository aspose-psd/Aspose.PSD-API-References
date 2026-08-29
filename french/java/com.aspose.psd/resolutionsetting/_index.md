---
title: "ResolutionSetting"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le paramètre de résolution pour les options d'enregistrement d'image."
type: docs
weight: 92
url: /fr/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

Le paramètre de résolution pour les options d'enregistrement d'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Initialise une nouvelle instance de la classe  ResolutionSetting  . |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Initialise une nouvelle instance de la classe  ResolutionSetting  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Définit la taille de la page PDF en fonction de la résolution DPI prise à partir de PdfOptions.ResolutionSettings ou, si elle possède des valeurs par défaut, à partir de l'image elle-même. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtient ou définit la résolution horizontale. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtient ou définit la résolution verticale. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtient ou définit la résolution horizontale. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtient ou définit la résolution verticale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Initialise une nouvelle instance de la classe  ResolutionSetting  .

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Initialise une nouvelle instance de la classe  ResolutionSetting  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| horizontalResolution | double | La résolution horizontale. |
| verticalResolution | double | La résolution verticale. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Définit la taille de la page PDF en fonction de la résolution DPI prise à partir de PdfOptions.ResolutionSettings ou, si elle possède des valeurs par défaut, à partir de l'image elle-même.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La taille de l'image. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | La résolution d'origine. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | La nouvelle résolution. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient ou définit la résolution horizontale.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient ou définit la résolution verticale.

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


Obtient ou définit la résolution horizontale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtient ou définit la résolution verticale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

