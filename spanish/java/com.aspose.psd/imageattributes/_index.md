---
title: "ImageAttributes"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Un objeto com.aspose.psd.ImageAttributes contiene información sobre cómo se manipulan los colores de mapas de bits y metarchivos durante la renderización."
type: docs
weight: 55
url: /es/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Un objeto com.aspose.psd.ImageAttributes contiene información sobre cómo se manipulan los colores de mapas de bits y metarchivos durante la renderización. Un objeto com.aspose.psd.ImageAttributes mantiene varios ajustes de color, incluyendo matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapa de colores y valores de umbral de color. Durante la renderización, los colores pueden corregirse, oscurecerse, aclararse y eliminarse. Para aplicar dichas manipulaciones, inicialice un objeto com.aspose.psd.ImageAttributes y pase la ruta de ese objeto com.aspose.psd.ImageAttributes (junto con la ruta de una [Image](../../com.aspose.psd/image)) al método drawImage.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Inicializa una nueva instancia de la clase com.aspose.psd.ImageAttributes. |
## Campos

| Campo | Descripción |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Los atributos de imagen GDI. |
## Métodos

| Método | Descripción |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Borra la tabla de remapeo de color del pincel de este objeto com.aspose.psd.ImageAttributes. |
| [clearColorKey()](#clearColorKey--) | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [clearColorKey(int type)](#clearColorKey-int-) | Borra la clave de color (rango de transparencia) para una categoría especificada. |
| [clearColorMatrix()](#clearColorMatrix--) | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Borra la matriz de ajuste de color para una categoría especificada. |
| [clearGamma()](#clearGamma--) | Desactiva la corrección gamma para la categoría predeterminada. |
| [clearGamma(int type)](#clearGamma-int-) | Desactiva la corrección gamma para una categoría especificada. |
| [clearNoOp()](#clearNoOp--) | Borra la configuración NoOp para la categoría predeterminada. |
| [clearNoOp(int type)](#clearNoOp-int-) | Borra la configuración NoOp para una categoría especificada. |
| [clearOutputChannel()](#clearOutputChannel--) | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Borra la configuración del perfil de color del canal de salida para una categoría especificada. |
| [clearRemapTable()](#clearRemapTable--) | Borra la tabla de remapeo de color para la categoría predeterminada. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Borra la tabla de remapeo de color para una categoría especificada. |
| [clearThreshold()](#clearThreshold--) | Borra el valor de umbral para la categoría predeterminada. |
| [clearThreshold(int type)](#clearThreshold-int-) | Borra el valor de umbral para una categoría especificada. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Establece la tabla de remapeo de color para la categoría de pincel. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Establece la clave de color para la categoría predeterminada. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Establece la clave de color (rango de transparencia) para una categoría especificada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Establece la matriz de ajuste de color para una categoría especificada. |
| [setGamma(float gamma)](#setGamma-float-) | Establece el valor gamma para la categoría predeterminada. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Establece el valor gamma para una categoría especificada. |
| [setNoOp()](#setNoOp--) | Desactiva el ajuste de color para la categoría predeterminada. |
| [setNoOp(int type)](#setNoOp-int-) | Desactiva el ajuste de color para una categoría especificada. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Establece el archivo de perfil de color del canal de salida para una categoría especificada. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Establece la tabla de remapeo de color para la categoría predeterminada. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Establece la tabla de remapeo de color para una categoría especificada. |
| [setThreshold(float threshold)](#setThreshold-float-) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Establece el umbral (rango de transparencia) para una categoría especificada. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Establece el modo de ajuste que se usa para decidir cómo mosaicar una textura a través de una forma, o en los bordes de la forma. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a través de una forma, o en los bordes de la forma. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a través de una forma, o en los bordes de la forma. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Inicializa una nueva instancia de la clase com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Los atributos de imagen GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Borra la tabla de remapeo de color del pincel de este objeto com.aspose.psd.ImageAttributes.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Borra la clave de color (rango de transparencia) para la categoría predeterminada.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Borra la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la clave de color. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Borra la matriz de ajuste de color para la categoría predeterminada.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Borra la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la matriz de ajuste de color. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Desactiva la corrección gamma para la categoría predeterminada.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Desactiva la corrección gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual la corrección gamma está deshabilitada. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Borra la configuración NoOp para la categoría predeterminada.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Borra la configuración NoOp para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la configuración NoOp. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la configuración del canal de salida. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Borra la configuración del perfil de color del canal de salida para la categoría predeterminada.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Borra la configuración del perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la configuración del perfil del canal de salida. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Borra la tabla de remapeo de color para la categoría predeterminada.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Borra la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra la tabla de remapeo. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Borra el valor de umbral para la categoría predeterminada.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Borra el valor de umbral para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se borra el umbral. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría de pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Una matriz de  com.aspose.psd.ColorMap  objetos. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Establece la clave de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.psd/color) | El valor alto de la clave de color. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Establece la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.psd/color) | El valor alto de la clave de color. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece la clave de color. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de escala de grises. |
| banderas | int | Un elemento de  Aspose.Imaging.ColorMatrixFlag  que especifica el tipo de imagen y color que se verá afectado por las matrices de ajuste de color y ajuste de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de escala de grises. |
| mode | int | Un elemento de  Aspose.Imaging.ColorMatrixFlag  que especifica el tipo de imagen y color que se verá afectado por las matrices de ajuste de color y ajuste de escala de grises. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establecen las matrices de ajuste de color y ajuste de escala de grises. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |
| banderas | int | Un elemento de  Aspose.Imaging.ColorMatrixFlag  que especifica el tipo de imagen y color que se verá afectado por la matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Establece la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matriz de ajuste de color. |
| mode | int | Un elemento de  Aspose.Imaging.ColorMatrixFlag  que especifica el tipo de imagen y color que se verá afectado por la matriz de ajuste de color. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece la matriz de ajuste de color. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Establece el valor gamma para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Establece el valor gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |
| type | int | Un elemento de la enumeración  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece el valor gamma. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Desactiva el ajuste de color para la categoría predeterminada.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Desactiva el ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se desactiva la corrección de color. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| banderas | int | Un elemento de  Aspose.Imaging.ColorChannelFlag  que especifica el canal de salida. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| banderas | int | Un elemento de  Aspose.Imaging.ColorChannelFlag  que especifica el canal de salida. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece el canal de salida. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Establece el archivo de perfil de color del canal de salida para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | El nombre de ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser el nombre de ruta totalmente calificado. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Establece el archivo de perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | El nombre de ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser el nombre de ruta totalmente calificado. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece el archivo de perfil de color del canal de salida. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Una matriz de pares de colores del tipo  com.aspose.psd.ColorMap . Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Establece la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Una matriz de pares de colores del tipo  com.aspose.psd.ColorMap . Cada par de colores contiene un color existente (el primer valor) y el color al que se mapeará (el segundo valor). |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece la tabla de remapeo de colores. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Establece el umbral (rango de transparencia) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Un número real que especifica el valor del umbral. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Establece el umbral (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Un valor de umbral de 0.0 a 1.0 que se usa como punto de ruptura para ordenar colores que se mapearán a un valor máximo o mínimo. |
| type | int | Un elemento de  Aspose.Imaging.ColorAdjustType  que especifica la categoría para la cual se establece el umbral de color. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Establece el modo de ajuste que se usa para decidir cómo mosaicar una textura a lo largo de una forma, o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de  Aspose.Imaging.WrapMode  que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a lo largo de una forma, o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de  Aspose.Imaging.WrapMode  que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | [Color](../../com.aspose.psd/color) | Un objeto  com.aspose.psd.ImageAttributes  que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece en  WrapMode.Clamp  y el rectángulo fuente pasado a DrawImage es más grande que la propia imagen. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a lo largo de una forma, o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Un elemento de  Aspose.Imaging.WrapMode  que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | [Color](../../com.aspose.psd/color) | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece en  WrapMode.Clamp  y el rectángulo fuente pasado a DrawImage es más grande que la propia imagen. |
| clamp | boolean | Este parámetro no tiene efecto. Establézcalo en false. |

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

