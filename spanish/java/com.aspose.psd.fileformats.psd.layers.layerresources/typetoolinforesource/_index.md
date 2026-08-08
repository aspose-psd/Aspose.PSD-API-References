---
title: "TypeToolInfoResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La información de la herramienta de texto."
type: docs
weight: 79
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

La información de la herramienta de tipo. Para versiones de PSD inferiores a 6.0.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Inicializa una nueva instancia de la clase [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versión del encabezado PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma de recurso específica de PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versión del encabezado PSD |
| [ResourceSignature](#ResourceSignature) | La firma de recurso común. |
| [TypeToolKey](#TypeToolKey) | La clave de información de la herramienta de tipo. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licencia venture. |
## Métodos

| Método | Descripción |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAComponent()](#getAComponent--) | Obtiene o establece un componente. |
| [getBComponent()](#getBComponent--) | Obtiene o establece el componente b. |
| [getCharacterCount()](#getCharacterCount--) | Obtiene o establece el recuento de caracteres. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Obtiene o establece el valor del espacio de color. |
| [getFontVersion()](#getFontVersion--) | Obtiene o establece la versión de la fuente. |
| [getFonts()](#getFonts--) | Obtiene o establece las fuentes. |
| [getFontsCount()](#getFontsCount--) | Obtiene el recuento de fuentes. |
| [getGComponent()](#getGComponent--) | Obtiene o establece el componente g. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Obtiene o establece la posición horizontal. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getLineCount()](#getLineCount--) | Obtiene el recuento de líneas. |
| [getLines()](#getLines--) | Obtiene o establece las líneas. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getRComponent()](#getRComponent--) | Obtiene o establece el componente r. |
| [getScaleFactor()](#getScaleFactor--) | Obtiene o establece el factor de escala. |
| [getSelectionEnd()](#getSelectionEnd--) | Obtiene o establece el final de la selección. |
| [getSelectionStart()](#getSelectionStart--) | Obtiene o establece el inicio de la selección. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getStyles()](#getStyles--) | Obtiene o establece los estilos de fuente. |
| [getStylesCount()](#getStylesCount--) | Obtiene el recuento de estilos. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece la matriz de transformación. |
| [getTypeValue()](#getTypeValue--) | Obtiene o establece el valor de tipo. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Obtiene o establece la ubicación vertical. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setAComponent(short value)](#setAComponent-short-) | Obtiene o establece un componente. |
| [setBComponent(short value)](#setBComponent-short-) | Obtiene o establece el componente b. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Obtiene o establece el recuento de caracteres. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Obtiene o establece los datos de color sin procesar. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Obtiene o establece el valor del espacio de color. |
| [setFontVersion(short value)](#setFontVersion-short-) | Obtiene o establece la versión de la fuente. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Obtiene o establece las fuentes. |
| [setGComponent(short value)](#setGComponent-short-) | Obtiene o establece el componente g. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Obtiene o establece la posición horizontal. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Obtiene o establece las líneas. |
| [setRComponent(short value)](#setRComponent-short-) | Obtiene o establece el componente r. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Obtiene o establece el factor de escala. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Obtiene o establece el final de la selección. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Obtiene o establece el inicio de la selección. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Obtiene o establece los estilos de fuente. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtiene o establece la matriz de transformación. |
| [setTypeValue(short value)](#setTypeValue-short-) | Obtiene o establece el valor de tipo. |
| [setVersion(short value)](#setVersion-short-) | Obtiene o establece la versión. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Obtiene o establece la ubicación vertical. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Inicializa una nueva instancia de la clase [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La versión del encabezado PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La firma de recurso específica de PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La versión del encabezado PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La firma de recurso común.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La clave de información de la herramienta de tipo.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licencia venture.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Comprueba y establece si el recurso es específico de PSB. Algunos recursos no se reconocen por ahora, pero tenemos una lista completa de recursos específicos de PSB que cambian su comportamiento al guardar. Por lo tanto, debemos comprobar esto al menos en UnknownResource.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave. |

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Obtiene o establece un componente.

Valor: un componente.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Obtiene o establece el componente b.

Valor: el componente b.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Obtiene o establece el recuento de caracteres.

Valor: el recuento de caracteres.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


Obtiene o establece el valor del espacio de color.

Valor: el valor del espacio de color.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Obtiene o establece la versión de la fuente.

Valor: la versión de la fuente.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Obtiene o establece las fuentes.

Valor: las fuentes.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Obtiene el recuento de fuentes.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Obtiene o establece el componente g.

Valor: el componente g.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Obtiene o establece la posición horizontal.

Valor: la ubicación horizontal.

**Returns:**
int
### getKey() {#getKey--}
```
public final int getKey()
```


Obtiene la clave del recurso de capa.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Obtiene la longitud del recurso de capa en bytes.

**Returns:**
int
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Obtiene el recuento de líneas.

Valor: el recuento de líneas.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Obtiene o establece las líneas.

Valor: las líneas.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Obtiene la longitud del prefijo. El valor predeterminado es 12 para recursos 8BIM y 16 para 8B64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdVersion | int | La versión PSD. |

**Returns:**
int - La longitud del prefijo.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones.

**Returns:**
int
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Obtiene o establece el componente r.

Valor: el componente r.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Obtiene o establece el factor de escala.

Valor: el factor de escala.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Obtiene o establece el final de la selección.

Valor: el final de la selección.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Obtiene o establece el inicio de la selección.

Valor: el inicio de la selección.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene la firma del recurso de capa.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Obtiene o establece los estilos de fuente.

Valor: los estilos de fuente.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Obtiene el recuento de estilos.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Obtiene o establece el valor de tipo.

Valor: El valor del tipo.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Obtiene o establece la versión.

Valor: La versión.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Obtiene o establece la ubicación vertical.

Valor: La posición vertical.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determina si el recurso es específico de PSB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave del recurso. |

**Returns:**
boolean -  true  si el recurso es específico de PSB; de lo contrario,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Obtiene un valor que indica si esta instancia es un recurso específico de PSB.

Valor:  true  si esta instancia es un recurso específico de PSB; de lo contrario,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Guarda el contenedor de flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| psdVersion | int | La versión PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Guarda el encabezado del recurso personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Guarda la firma del encabezado, el identificador y la longitud.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |
| isLengthLong | boolean | si se establece en  true  la longitud es larga. |

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Obtiene o establece un componente.

Valor: un componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Obtiene o establece el componente b.

Valor: el componente b.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Obtiene o establece el recuento de caracteres.

Valor: el recuento de caracteres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Obtiene o establece los datos de color sin procesar.

Valor: Los datos de color sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Obtiene o establece el valor del espacio de color.

Valor: el valor del espacio de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Obtiene o establece la versión de la fuente.

Valor: la versión de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Obtiene o establece las fuentes.

Valor: las fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Obtiene o establece el componente g.

Valor: el componente g.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Obtiene o establece la posición horizontal.

Valor: la ubicación horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Obtiene o establece las líneas.

Valor: las líneas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Obtiene o establece el componente r.

Valor: el componente r.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Obtiene o establece el factor de escala.

Valor: el factor de escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Obtiene o establece el final de la selección.

Valor: el final de la selección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Obtiene o establece el inicio de la selección.

Valor: el inicio de la selección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Obtiene o establece los estilos de fuente.

Valor: los estilos de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Obtiene o establece la matriz de transformación.

Valor: La matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Obtiene o establece el valor de tipo.

Valor: El valor del tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Obtiene o establece la versión.

Valor: La versión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Obtiene o establece la ubicación vertical.

Valor: La posición vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una String que representa esta instancia.
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

