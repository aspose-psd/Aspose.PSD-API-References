---
title: "HatchBrush"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar en rektangulär brush med ett hatch‑mönster, en förgrundsfärg och en bakgrundsfärg."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

Definierar en rektangulär brush med ett hatch‑mönster, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella  Brush . |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar färgen på utrymmena mellan hatch‑linjerna. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getForegroundColor()](#getForegroundColor--) | Hämtar färgen på hatch‑linjerna. |
| [getHatchStyle()](#getHatchStyle--) | Hämtar hatch‑stilen för denna brush. |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Ställer in färgen på utrymmena mellan hatch‑linjerna. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | Ställer in färgen på hatch‑linjerna. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Ställer in hatch‑stilen för denna brush. |
| [setOpacity(float value)](#setOpacity-float-) | Anger penselns opacitet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Skapar en ny djupklon av den aktuella  Brush .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar färgen på utrymmena mellan hatch‑linjerna.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Hämtar färgen på hatch‑linjerna.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Hämtar hatch‑stilen för denna brush.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Returns:**
float - Penselns opacitetsvärde.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Ställer in färgen på utrymmena mellan hatch‑linjerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Färgen på utrymmena mellan hatch‑linjerna. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


Ställer in färgen på hatch‑linjerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Färgen på skrafferlina. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Ställer in hatch‑stilen för denna brush.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Penselns opacitetsvärde. |

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

