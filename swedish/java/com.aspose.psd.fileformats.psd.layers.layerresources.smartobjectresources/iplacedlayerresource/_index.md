---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar gränssnittet IPlacedLayerResource som innehåller information om ett placerat lager i PSD-filen."
type: docs
weight: 17
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Definierar gränssnittet **IPlacedLayerResource** som innehåller information om ett placerat lager i en PSD-fil. Det är ett markup‑gränssnitt som används för att beteckna PlLd-, Sold- och Sole‑resurser i Adobe\ufffd Photoshop\ufffd‑bilder. Det används för att stödja smarta objektlager i Adobe\ufffd Photoshop\ufffd‑bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden. |
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [getBounds()](#getBounds--) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [getItems()](#getItems--) | Hämtar eller anger warp‑objekten. |
| [getLeft()](#getLeft--) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen. |
| [getPerspective()](#getPerspective--) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Hämtar eller anger typen av det placerade lagret i PSD‑filen. |
| [getRight()](#getRight--) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [getTop()](#getTop--) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [getTotalPages()](#getTotalPages--) | Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen. |
| [getUOrder()](#getUOrder--) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getUniqueId()](#getUniqueId--) | Hämtar eller anger det globala unika identifieraren för det placerade smartobjektlagret i PSD‑bilden. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getValue()](#getValue--) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [getVersion()](#getVersion--) | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3‑5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [isCustom()](#isCustom--) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden. |
| [setBottom(double value)](#setBottom-double-) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [setCustom(boolean value)](#setCustom-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger warp‑objekten. |
| [setLeft(double value)](#setLeft-double-) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [setPageNumber(int value)](#setPageNumber-int-) | Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen. |
| [setPerspective(double value)](#setPerspective-double-) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Hämtar eller anger typen av det placerade lagret i PSD‑filen. |
| [setRight(double value)](#setRight-double-) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [setTop(double value)](#setTop-double-) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [setTotalPages(int value)](#setTotalPages-int-) | Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen. |
| [setUOrder(int value)](#setUOrder-int-) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Hämtar eller anger det globala unika identifieraren för det placerade smartobjektlagret i PSD‑bilden. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setValue(double value)](#setValue-double-) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden.

Värde: Anti‑alias‑policyn för det placerade lagret.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen.

Värde: Sidnumret för det placerade lagret.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Hämtar eller anger typen av det placerade lagret i PSD‑filen.

Värde: Typen av det placerade lagret.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen.

Värde: Totalt antal sidor i det placerade lagret.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen.

Värde: Transformationsmatrisen för det placerade lagret.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Hämtar eller anger det globala unika identifieraren för det placerade smartobjektlagret i PSD‑bilden.

Värde: Det unika identifieraren för det placerade lagret.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3‑5.

Värde: Den placerade eller smarta objektlagrets version.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om den placerade eller smarta objektlagrets resurs har anpassad stil; annars  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden.

Värde: Anti‑alias‑policyn för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om den placerade eller smarta objektlagrets resurs har anpassad stil; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen.

Värde: Sidnumret för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Hämtar eller anger typen av det placerade lagret i PSD‑filen.

Värde: Typen av det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen.

Värde: Totalt antal sidor i det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen.

Värde: Transformationsmatrisen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Hämtar eller anger det globala unika identifieraren för det placerade smartobjektlagret i PSD‑bilden.

Värde: Det unika identifieraren för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

