---
title: "GrdmResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase GrdmResource."
type: docs
weight: 35
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Clase GrdmResource. Contiene información sobre la capa Gradient-Map.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Inicializa una nueva instancia de la clase [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | La escala predeterminada. |
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
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Modelo de color. |
| [getColorPoints()](#getColorPoints--) | Obtiene o establece los puntos de color. |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [getDither()](#getDither--) | El degradado está tramado. |
| [getExpansionCount()](#getExpansionCount--) | Cuenta de expansión ( = 2 para Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Longitud(= 32 para Photoshop 6.0) No hay información sobre a qué sirve. |
| [getGradientMode()](#getGradientMode--) | Modo para este degradado Determina 'Tipo de degradado' = 'Sólido/Ruido' (0/1). |
| [getGradientName()](#getGradientName--) | Nombre del degradado: cadena Unicode, con relleno. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getInterpolation()](#getInterpolation--) | Interpolación. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtiene o establece el método de interpolación para el degradado. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de capa en bytes. |
| [getMaximumColor()](#getMaximumColor--) | Color máximo del formato PixelDataFormat.Rgba64Bpp. |
| [getMinimumColor()](#getMinimumColor--) | Color mínimo del formato PixelDataFormat.Rgba64Bpp. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para este recurso. |
| [getReverse()](#getReverse--) | El degradado está invertido. |
| [getRndNumberSeed()](#getRndNumberSeed--) | La semilla de número aleatorio utilizada para generar colores para el degradado de ruido. |
| [getRoughness()](#getRoughness--) | Factor de aspereza Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Aspereza' (0 - 2048). |
| [getShowTransparency()](#getShowTransparency--) | Indicador para mostrar transparencia Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Agregar transparencia' a verdadero. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Obtiene o establece los puntos de transparencia. |
| [getUseVectorColor()](#getUseVectorColor--) | Indicador para usar color vectorial. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Inicializa la longitud del degradado. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda los datos del recurso en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setColorModel(short value)](#setColorModel-short-) | Modelo de color. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Obtiene o establece los puntos de color. |
| [setDither(boolean value)](#setDither-boolean-) | El degradado está tramado. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Cuenta de expansión ( = 2 para Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Modo para este degradado Determina 'Tipo de degradado' = 'Sólido/Ruido' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Nombre del degradado: cadena Unicode, con relleno. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolación. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtiene o establece el método de interpolación para el degradado. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Color máximo del formato PixelDataFormat.Rgba64Bpp. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Color mínimo del formato PixelDataFormat.Rgba64Bpp. |
| [setReverse(boolean value)](#setReverse-boolean-) | El degradado está invertido. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | La semilla de número aleatorio utilizada para generar colores para el degradado de ruido. |
| [setRoughness(int value)](#setRoughness-int-) | Factor de aspereza Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Aspereza' (0 - 2048). |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Indicador para mostrar transparencia Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Agregar transparencia' a verdadero. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Obtiene o establece los puntos de transparencia. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Indicador para usar color vectorial. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Inicializa una nueva instancia de la clase [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdVersion | int | La versión PSD del recurso. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


La escala predeterminada.

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


Modelo de color. Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Modelo de color' a RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Obtiene o establece los puntos de color.

Valor: Los puntos de color.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Obtiene o establece los datos.

Valor: Los datos.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


El degradado está tramado.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Cuenta de expansión ( = 2 para Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Longitud(= 32 para Photoshop 6.0) No hay información sobre a qué sirve.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Modo para este degradado Determina 'Tipo de degradado' = 'Sólido/Ruido' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Nombre del degradado: cadena Unicode, con relleno.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolación. Determina la suavidad, cuando 'Tipo de degradado' = 'Sólido' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Obtiene o establece el método de interpolación para el degradado.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Color máximo del formato PixelDataFormat.Rgba64Bpp. El color tiene canales ARGB, cada canal es de 16 bits.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Color mínimo del formato PixelDataFormat.Rgba64Bpp. El color tiene canales ARGB, cada canal es de 16 bits.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


Obtiene la versión mínima de PSD requerida para este recurso. Se necesita la versión 3 cuando el método de interpolación se almacena explícitamente.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


El degradado está invertido.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


La semilla de número aleatorio utilizada para generar colores para el degradado de ruido.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Factor de aspereza Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Aspereza' (0 - 2048).

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Indicador para mostrar transparencia Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Agregar transparencia' a verdadero.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene la firma del recurso de capa.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Obtiene o establece los puntos de transparencia.

Valor: Los puntos de transparencia.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Indicador para usar color vectorial.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Inicializa la longitud del degradado. GradientLength es de solo lectura, por lo que solo puede asignarse una vez.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | El valor. |

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


Guarda los datos del recurso en el contenedor de flujo especificado.

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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Modelo de color. Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Modelo de color' a RGB/SHB/LAB (3/4/6).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Obtiene o establece los puntos de color.

Valor: Los puntos de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


El degradado está tramado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Cuenta de expansión ( = 2 para Photoshop 6.0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Modo para este degradado Determina 'Tipo de degradado' = 'Sólido/Ruido' (0/1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Nombre del degradado: cadena Unicode, con relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolación. Determina la suavidad, cuando 'Tipo de degradado' = 'Sólido' (GradientMode = 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Obtiene o establece el método de interpolación para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Color máximo del formato PixelDataFormat.Rgba64Bpp. El color tiene canales ARGB, cada canal es de 16 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Color mínimo del formato PixelDataFormat.Rgba64Bpp. El color tiene canales ARGB, cada canal es de 16 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


El degradado está invertido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


La semilla de número aleatorio utilizada para generar colores para el degradado de ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Factor de aspereza Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Aspereza' (0 - 2048).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Indicador para mostrar transparencia Cuando 'Tipo de degradado' = 'Ruido', podemos asignar 'Agregar transparencia' a verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Obtiene o establece los puntos de transparencia.

Valor: Los puntos de transparencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Indicador para usar color vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

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

