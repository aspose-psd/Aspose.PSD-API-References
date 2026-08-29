---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de IPlacedLayerResource‑interface die informatie bevat over een geplaatste laag in het PSD‑bestand."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Definieert de IPlacedLayerResource‑interface die informatie bevat over een geplaatste laag in het PSD‑bestand. Het is een markup‑interface die wordt gebruikt om PlLd-, Sold- en Sole‑resources aan te duiden in de Adobe\ufffd Photoshop\ufffd‑afbeeldingen. Het wordt gebruikt om slimme‑objectlagen te ondersteunen in de Adobe\ufffd Photoshop\ufffd‑afbeeldingen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in. |
| [getBottom()](#getBottom--) | Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in. |
| [getBounds()](#getBounds--) | Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [getItems()](#getItems--) | Haalt of stelt de warp-items in. |
| [getLeft()](#getLeft--) | Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in. |
| [getPageNumber()](#getPageNumber--) | Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in. |
| [getPerspective()](#getPerspective--) | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Haalt of stelt het type van de geplaatste laag in het PSD-bestand in. |
| [getRight()](#getRight--) | Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in. |
| [getTop()](#getTop--) | Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in. |
| [getTotalPages()](#getTotalPages--) | Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in. |
| [getTransformMatrix()](#getTransformMatrix--) | Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in. |
| [getUOrder()](#getUOrder--) | Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [getUniqueId()](#getUniqueId--) | Haalt op of stelt de globale unieke identifier van de slimme‑object geplaatste laag in de PSD‑afbeelding in. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [getValue()](#getValue--) | Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| [getVersion()](#getVersion--) | Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3‑5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Haalt op of stelt de meeteenheid van de verticale mesh‑punten in. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [isCustom()](#isCustom--) | Haalt op of stelt een waarde in die aangeeft of de warp‑stijl van deze instantie aangepast is. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in. |
| [setBottom(double value)](#setBottom-double-) | Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in. |
| [setCustom(boolean value)](#setCustom-boolean-) | Haalt op of stelt een waarde in die aangeeft of de warp‑stijl van deze instantie aangepast is. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Haalt of stelt de warp-items in. |
| [setLeft(double value)](#setLeft-double-) | Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in. |
| [setPageNumber(int value)](#setPageNumber-int-) | Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in. |
| [setPerspective(double value)](#setPerspective-double-) | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Haalt of stelt het type van de geplaatste laag in het PSD-bestand in. |
| [setRight(double value)](#setRight-double-) | Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in. |
| [setTop(double value)](#setTop-double-) | Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in. |
| [setTotalPages(int value)](#setTotalPages-int-) | Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in. |
| [setUOrder(int value)](#setUOrder-int-) | Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Haalt op of stelt de globale unieke identifier van de slimme‑object geplaatste laag in de PSD‑afbeelding in. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [setValue(double value)](#setValue-double-) | Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Haalt op of stelt de meeteenheid van de verticale mesh‑punten in. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in.

Waarde: Het anti‑aliasbeleid van de geplaatste laag.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De onderste locatie van de geplaatste laag.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in.

Waarde: De grenzen van de geplaatste laag.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Haalt of stelt de meeteenheid van de horizontale rasterpunten in.

Waarde: De maateenheid van de horizontale rasterpunten.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De linkse locatie van de geplaatste laag.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in.

Waarde: Het paginanummer van de geplaatste laag.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De perspectiefwaarde van de geplaatste laag.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De andere perspectiefwaarde van de geplaatste laag.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Haalt of stelt het type van de geplaatste laag in het PSD-bestand in.

Waarde: Het type van de geplaatste laag.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De rechtse locatie van de geplaatste laag.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De bovenste locatie van de geplaatste laag.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in.

Waarde: Het totale aantal pagina's van de geplaatste laag.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in.

Waarde: De transformatiematrix van de geplaatste laag.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De U-ordewaarde van de geplaatste laag.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Haalt op of stelt de globale unieke identifier van de slimme‑object geplaatste laag in de PSD‑afbeelding in.

Waarde: De unieke identifier van de geplaatste laag.

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


Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De V-ordewaarde van de geplaatste laag.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De warp-waarde van de geplaatste laag.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3‑5.

Waarde: De versie van de geplaatste of slimme objectlaag.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Haalt op of stelt de meeteenheid van de verticale mesh‑punten in.

Waarde: De maateenheid van de verticale rasterpunten.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Haalt een waarde op of stelt deze in die aangeeft of de warp-stijl van deze instantie aangepast is. Als true bevat het mesh-punten. Als false worden de mesh-punten gewist.

Waarde:  true  als de geplaatste of slimme objectlaag‑resource een aangepaste stijl heeft; anders,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in.

Waarde: Het anti‑aliasbeleid van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De onderste locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in.

Waarde: De grenzen van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de warp-stijl van deze instantie aangepast is. Als true bevat het mesh-punten. Als false worden de mesh-punten gewist.

Waarde:  true  als de geplaatste of slimme objectlaag‑resource een aangepaste stijl heeft; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Haalt of stelt de meeteenheid van de horizontale rasterpunten in.

Waarde: De maateenheid van de horizontale rasterpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De linkse locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in.

Waarde: Het paginanummer van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De perspectiefwaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De andere perspectiefwaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Haalt of stelt het type van de geplaatste laag in het PSD-bestand in.

Waarde: Het type van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De rechtse locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De bovenste locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in.

Waarde: Het totale aantal pagina's van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in.

Waarde: De transformatiematrix van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De U-ordewaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Haalt op of stelt de globale unieke identifier van de slimme‑object geplaatste laag in de PSD‑afbeelding in.

Waarde: De unieke identifier van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De V-ordewaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De warp-waarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Haalt op of stelt de meeteenheid van de verticale mesh‑punten in.

Waarde: De maateenheid van de verticale rasterpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

