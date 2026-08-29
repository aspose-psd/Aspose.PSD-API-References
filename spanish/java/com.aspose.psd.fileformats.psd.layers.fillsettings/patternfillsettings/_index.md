---
title: "PatternFillSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Configuración del efecto de relleno de patrón"
type: docs
weight: 20
url: /es/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Configuración del efecto de relleno de patrón
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Inicializa una nueva instancia de la clase [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Campos

| Campo | Descripción |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Genera los nodos de recurso LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtiene o establece un valor que indica si [link with layer]. |
| [getAngle()](#getAngle--) | Obtiene o establece el ángulo. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene o establece el color. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | El tipo de relleno |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtiene o establece el desplazamiento horizontal. |
| [getLinked()](#getLinked--) | Obtiene o establece un valor que indica si este [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) está vinculado. |
| [getPatternData()](#getPatternData--) | Obtiene o establece los datos del patrón. |
| [getPatternHeight()](#getPatternHeight--) | Obtiene o establece la altura del patrón. |
| [getPatternId()](#getPatternId--) | Obtiene o establece el identificador del patrón. |
| [getPatternName()](#getPatternName--) | Obtiene o establece el nombre del patrón. |
| [getPatternWidth()](#getPatternWidth--) | Obtiene o establece el ancho del patrón. |
| [getPhase_internalized()](#getPhase-internalized--) | Obtiene o establece la fase. |
| [getPointType()](#getPointType--) | Obtiene o establece el tipo del punto. |
| [getScale()](#getScale--) | Obtiene o establece la escala. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtiene o establece el desplazamiento vertical. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera el cambio de valor. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtiene o establece un valor que indica si [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtiene o establece el color. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Obtiene o establece el desplazamiento horizontal. |
| [setLinked(boolean value)](#setLinked-boolean-) | Obtiene o establece un valor que indica si este [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) está vinculado. |
| [setPatternData(int[] value)](#setPatternData-int---) | Obtiene o establece los datos del patrón. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Establece el búfer de píxeles del patrón\u2019s y el modo de compresión a usar al guardar. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Obtiene o establece la altura del patrón. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Obtiene o establece el identificador del patrón. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Obtiene o establece el nombre del patrón. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Obtiene o establece el ancho del patrón. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Obtiene o establece la fase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Obtiene o establece el tipo del punto. |
| [setScale(double value)](#setScale-double-) | Obtiene o establece la escala. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Obtiene o establece el desplazamiento vertical. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Configura los datos predeterminados del patrón a la instancia de [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Actualiza las propiedades del patrón desde la instancia de [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Inicializa una nueva instancia de la clase [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Genera los nodos de recurso LFX2.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pointType | java.lang.String | Tipo del punto. |
| color | [Color](../../com.aspose.psd/color) | El color. |
| patternName | java.lang.String | Nombre del patrón. |
| identificador | java.lang.String | El identificador. |
| escala | double | La escala. |
| vinculado | boolean | si se establece a  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | El desplazamiento. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Lista de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtiene o establece un valor que indica si [link with layer].

Valor:  true  si [link with layer]; de lo contrario,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtiene o establece el ángulo.

Valor: El ángulo.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color.

Valor: El color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


El tipo de relleno

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Obtiene o establece el desplazamiento horizontal.

Valor: El desplazamiento horizontal.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Obtiene o establece un valor que indica si este [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) está vinculado.

Valor:  true  si vinculado; de lo contrario,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Obtiene o establece los datos del patrón.

Valor: Los datos del patrón.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Obtiene o establece la altura del patrón.

Valor: La altura del patrón.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Obtiene o establece el identificador del patrón.

Valor: El identificador del patrón.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Obtiene o establece el nombre del patrón.

Valor: El nombre del patrón.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Obtiene o establece el ancho del patrón.

Valor: El ancho del patrón.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Obtiene o establece la fase.

Valor: La fase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Obtiene o establece el tipo del punto.

Valor: El tipo del punto.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Obtiene o establece la escala.

Valor: La escala.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Obtiene o establece el desplazamiento vertical.

Valor: El desplazamiento vertical.

**Returns:**
int
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


Obtiene o establece un valor que indica si [link with layer].

Valor:  true  si [link with layer]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtiene o establece el ángulo.

Valor: El ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color.

Valor: El color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Obtiene o establece el desplazamiento horizontal.

Valor: El desplazamiento horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Obtiene o establece un valor que indica si este [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) está vinculado.

Valor:  true  si vinculado; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Obtiene o establece los datos del patrón.

Valor: Los datos del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Establece el búfer de píxeles del patrón\u2019s y el modo de compresión a usar al guardar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| patternData | int[] | píxeles de 32 bits en  0xAARRGGBB . |
| compressionModeOnSave | byte | El modo de compresión utilizado para definir la compresión de los datos del patrón al guardar el archivo psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Obtiene o establece la altura del patrón.

Valor: La altura del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Obtiene o establece el identificador del patrón.

Valor: El identificador del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Obtiene o establece el nombre del patrón.

Valor: El nombre del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Obtiene o establece el ancho del patrón.

Valor: El ancho del patrón.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Obtiene o establece la fase.

Valor: La fase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Obtiene o establece el tipo del punto.

Valor: El tipo del punto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Obtiene o establece la escala.

Valor: La escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Obtiene o establece el desplazamiento vertical.

Valor: El desplazamiento vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Configura los datos predeterminados del patrón a la instancia de [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | La configuración de relleno de patrón. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


Actualiza las propiedades del patrón desde la instancia de [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | La instancia de [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) con datos del patrón. |

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

