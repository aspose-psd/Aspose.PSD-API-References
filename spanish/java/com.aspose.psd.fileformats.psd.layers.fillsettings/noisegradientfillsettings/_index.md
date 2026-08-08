---
title: "NoiseGradientFillSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase de definición de degradado de ruido."
type: docs
weight: 18
url: /es/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Clase de definición de degradado de ruido.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Inicializa una nueva instancia de la clase [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
## Campos

| Campo | Descripción |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtiene o establece un valor que indica si [align with layer]. |
| [getAngle()](#getAngle--) | Obtiene o establece el ángulo. |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Obtiene o establece el modelo de color - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither. |
| [getExpansionCount()](#getExpansionCount--) | Obtiene o establece el recuento de expansión ( = 2 para Photoshop 6.0). |
| [getFillType()](#getFillType--) | El tipo de relleno. |
| [getGradientMode()](#getGradientMode--) | Obtiene el modo de este gradiente. |
| [getGradientName()](#getGradientName--) | Obtiene o establece el nombre del gradiente. |
| [getGradientType()](#getGradientType--) | Obtiene o establece el tipo de degradado. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [getMaximumColor()](#getMaximumColor--) | Obtiene o establece el color máximo de PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Obtiene o establece el color mínimo de PixelDataFormat. |
| [getReverse()](#getReverse--) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Obtiene o establece la semilla del número aleatorio utilizada para generar colores para el gradiente de ruido. |
| [getRoughness()](#getRoughness--) | Obtiene o establece el factor de rugosidad. |
| [getScale()](#getScale--) | Obtiene o establece la escala. |
| [getShowTransparency()](#getShowTransparency--) | Obtiene o establece la bandera para mostrar la transparencia. |
| [getUseVectorColor()](#getUseVectorColor--) | Obtiene o establece la bandera para usar color vectorial. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera el cambio de valor. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtiene o establece un valor que indica si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo. |
| [setColorModel(short value)](#setColorModel-short-) | Obtiene o establece el modelo de color - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Obtiene o establece el recuento de expansión ( = 2 para Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Obtiene el modo de este gradiente. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtiene o establece el nombre del gradiente. |
| [setGradientType(int value)](#setGradientType-int-) | Obtiene o establece el tipo de degradado. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtiene o establece el color máximo de PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtiene o establece el color mínimo de PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Obtiene o establece la semilla del número aleatorio utilizada para generar colores para el gradiente de ruido. |
| [setRoughness(int value)](#setRoughness-int-) | Obtiene o establece el factor de rugosidad. |
| [setScale(int value)](#setScale-int-) | Obtiene o establece la escala. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Obtiene o establece la bandera para mostrar la transparencia. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Obtiene o establece la bandera para usar color vectorial. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Inicializa una nueva instancia de la clase [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtiene o establece el ángulo.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Obtiene o establece el modelo de color - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither.

Valor:  true  si dithering; de lo contrario,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Obtiene o establece el recuento de expansión ( = 2 para Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


El tipo de relleno.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Obtiene el modo de este gradiente. Determina 'Tipo de gradiente' = 'Sólido/Ruido' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Obtiene o establece el nombre del gradiente.

Valor: El nombre del gradiente.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Obtiene o establece el desplazamiento horizontal en porcentaje.

Valor: El desplazamiento horizontal.

**Returns:**
double
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Obtiene o establece el color máximo de PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Obtiene o establece el color mínimo de PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Obtiene o establece la semilla del número aleatorio utilizada para generar colores para el gradiente de ruido.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Obtiene o establece el factor de rugosidad.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Obtiene o establece la escala.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Obtiene o establece la bandera para mostrar la transparencia.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Obtiene o establece la bandera para usar color vectorial.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Obtiene o establece el desplazamiento vertical en porcentaje.

Valor: El desplazamiento vertical.

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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Genera el cambio de valor.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtiene o establece el ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Obtiene o establece el modelo de color - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither.

Valor:  true  si dithering; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Obtiene o establece el recuento de expansión ( = 2 para Photoshop 6.0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Obtiene el modo de este gradiente. Determina 'Tipo de gradiente' = 'Sólido/Ruido' (0/1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Obtiene o establece el nombre del gradiente.

Valor: El nombre del gradiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Obtiene o establece el desplazamiento horizontal en porcentaje.

Valor: El desplazamiento horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Obtiene o establece el color máximo de PixelDataFormat.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Obtiene o establece el color mínimo de PixelDataFormat.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Obtiene o establece la semilla del número aleatorio utilizada para generar colores para el gradiente de ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Obtiene o establece el factor de rugosidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtiene o establece la escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Obtiene o establece la bandera para mostrar la transparencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Obtiene o establece la bandera para usar color vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Obtiene o establece el desplazamiento vertical en porcentaje.

Valor: El desplazamiento vertical.

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

