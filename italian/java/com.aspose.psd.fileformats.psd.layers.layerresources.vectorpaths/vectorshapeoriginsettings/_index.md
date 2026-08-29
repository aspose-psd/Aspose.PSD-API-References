---
title: "VectorShapeOriginSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Impostazioni di origine della forma vettoriale."
type: docs
weight: 24
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Impostazioni di origine della forma vettoriale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Inizializza una nuova istanza della classe [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | La chiave del descrittore per salvare l'indice di origine della forma. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | La chiave del descrittore dei raggi del rettangolo di origine. |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | La chiave del descrittore della risoluzione di origine. |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | La chiave del descrittore del riquadro di delimitazione della forma di origine. |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | La chiave del descrittore del tipo di origine. |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | La chiave del descrittore per salvare il valore invalidato della forma. |
| [KnownKeys_internalized](#KnownKeys-internalized) | Le chiavi delle proprietà note |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Ottiene l'identificatore univoco. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Ottiene o imposta gli angoli del riquadro di origine. |
| [getOriginIndex()](#getOriginIndex--) | Ottiene o imposta l'indice della forma di origine. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Ottiene o imposta il rettangolo dei raggi di origine. |
| [getOriginResolution()](#getOriginResolution--) | Ottiene o imposta la risoluzione di origine. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Ottiene o imposta il riquadro di delimitazione della forma di origine. |
| [getOriginType()](#getOriginType--) | Ottiene o imposta il tipo di origine. |
| [getTransform()](#getTransform--) | Ottiene o imposta la matrice di trasformazione. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Ottiene o imposta un valore che indica se questa istanza ha proprietà sconosciute. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Ottiene o imposta un valore che indica se questa istanza è modificata. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Ottiene un valore che indica se questa istanza ha la proprietà degli angoli della scatola di origine. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Ottiene un valore che indica se questa istanza ha la proprietà dell'indice di origine. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Ottiene un valore che indica se il rettangolo dei raggi di origine è presente per questa istanza. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Ottiene un valore che indica se questa istanza ha la proprietà della risoluzione di origine. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Ottiene un valore che indica se questa istanza ha la proprietà del rettangolo. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Ottiene un valore che indica se questa istanza ha la proprietà del tipo di origine. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Determina se la proprietà con la chiave specificata è presente. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Ottiene o imposta un valore che indica se la forma è invalidata. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Ottiene un valore che indica se questa istanza ha impostato la proprietà di forma invalidata. |
| [isTransformPresent()](#isTransformPresent--) | Ottiene un valore che indica se questa istanza ha la proprietà di trasformazione. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Ottiene o imposta un valore che indica se questa istanza è modificata. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Ottiene o imposta gli angoli del riquadro di origine. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Ottiene o imposta l'indice della forma di origine. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Ottiene o imposta il rettangolo dei raggi di origine. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Ottiene o imposta la risoluzione di origine. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Ottiene o imposta il riquadro di delimitazione della forma di origine. |
| [setOriginType(int value)](#setOriginType-int-) | Ottiene o imposta il tipo di origine. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Ottiene o imposta un valore che indica se la forma è invalidata. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Ottiene o imposta la matrice di trasformazione. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Ottiene o imposta un valore che indica se questa istanza ha proprietà sconosciute. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Inizializza una nuova istanza della classe [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isShapeInvalidated | boolean | Il valore della forma invalidata. |
| originIndex | int | L'indice di origine della forma. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


La chiave del descrittore per salvare l'indice di origine della forma.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


La chiave del descrittore dei raggi del rettangolo di origine.

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


La chiave del descrittore della risoluzione di origine.

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


La chiave del descrittore del riquadro di delimitazione della forma di origine.

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


La chiave del descrittore del tipo di origine.

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


La chiave del descrittore per salvare il valore invalidato della forma.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


Le chiavi delle proprietà note

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


Ottiene l'identificatore univoco.

Valore: L'identificatore univoco.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Ottiene o imposta gli angoli del riquadro di origine.

Valore: Gli angoli della scatola di origine.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Ottiene o imposta l'indice della forma di origine.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Ottiene o imposta il rettangolo dei raggi di origine.

Valore: Il rettangolo dei raggi di origine.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Ottiene o imposta la risoluzione di origine.

Valore: La risoluzione di origine.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Ottiene o imposta il riquadro di delimitazione della forma di origine.

Valore: La scatola della forma di origine.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Ottiene o imposta il tipo di origine.

Valore: Il tipo di origine.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Ottiene o imposta la matrice di trasformazione.

Valore: La matrice di trasformazione.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Ottiene o imposta un valore che indica se questa istanza ha proprietà sconosciute.

Valore:  true  se questa istanza ha proprietà sconosciute; altrimenti,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Ottiene o imposta un valore che indica se questa istanza è modificata.

Valore:  true  se questa istanza è modificata; altrimenti,  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà degli angoli della scatola di origine.

Valore:  true  se questa istanza ha la proprietà dei vertici della scatola di origine; altrimenti,  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà dell'indice di origine.

Valore:  true  se questa istanza ha la proprietà indice di origine; altrimenti,  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Ottiene un valore che indica se il rettangolo dei raggi di origine è presente per questa istanza.

Valore:  true  se questa istanza ha la proprietà del rettangolo dei raggi di origine; altrimenti,  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà della risoluzione di origine.

Valore:  true  se questa istanza ha la proprietà di risoluzione di origine; altrimenti,  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà del rettangolo.

Valore:  true  se questa istanza ha la proprietà del rettangolo della forma di origine; altrimenti,  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà del tipo di origine.

Valore:  true  se questa istanza ha la proprietà tipo di origine; altrimenti,  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Determina se la proprietà con la chiave specificata è presente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La chiave della proprietà. |

**Returns:**
boolean -  true  se la proprietà con la chiave specificata è presente; altrimenti,  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Ottiene o imposta un valore che indica se la forma è invalidata.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Ottiene un valore che indica se questa istanza ha impostato la proprietà di forma invalidata.

Valore:  true  se questa istanza ha impostato la proprietà di forma invalidata; altrimenti,  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Ottiene un valore che indica se questa istanza ha la proprietà di trasformazione.

Valore:  true  se questa istanza ha la proprietà di trasformazione; altrimenti,  false .

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




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è modificata.

Valore:  true  se questa istanza è modificata; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Ottiene o imposta gli angoli del riquadro di origine.

Valore: Gli angoli della scatola di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Ottiene o imposta l'indice della forma di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Ottiene o imposta il rettangolo dei raggi di origine.

Valore: Il rettangolo dei raggi di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Ottiene o imposta la risoluzione di origine.

Valore: La risoluzione di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Ottiene o imposta il riquadro di delimitazione della forma di origine.

Valore: La scatola della forma di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Ottiene o imposta il tipo di origine.

Valore: Il tipo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Ottiene o imposta un valore che indica se la forma è invalidata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Ottiene o imposta la matrice di trasformazione.

Valore: La matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza ha proprietà sconosciute.

Valore:  true  se questa istanza ha proprietà sconosciute; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

