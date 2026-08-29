---
title: "ResolutionSetting"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La configuración de resolución para las opciones de guardado de imagen."
type: docs
weight: 92
url: /es/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

La configuración de resolución para las opciones de guardado de imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Inicializa una nueva instancia de la clase  ResolutionSetting . |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Inicializa una nueva instancia de la clase  ResolutionSetting . |
## Métodos

| Método | Descripción |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Define el tamaño de página PDF en función de la resolución DPI tomada de PdfOptions.ResolutionSettings o, si tiene valores predeterminados, de la propia imagen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene o establece la resolución horizontal. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtiene o establece la resolución vertical. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtiene o establece la resolución horizontal. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtiene o establece la resolución vertical. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Inicializa una nueva instancia de la clase  ResolutionSetting .

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Inicializa una nueva instancia de la clase  ResolutionSetting .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| horizontalResolution | double | La resolución horizontal. |
| verticalResolution | double | La resolución vertical. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Define el tamaño de página PDF en función de la resolución DPI tomada de PdfOptions.ResolutionSettings o, si tiene valores predeterminados, de la propia imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | El tamaño de la imagen. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | La resolución original. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | La nueva resolución. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene o establece la resolución horizontal.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtiene o establece la resolución vertical.

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


Obtiene o establece la resolución horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtiene o establece la resolución vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

