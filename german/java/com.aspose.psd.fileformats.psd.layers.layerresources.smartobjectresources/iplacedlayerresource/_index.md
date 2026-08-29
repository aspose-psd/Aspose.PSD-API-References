---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert das Interface IPlacedLayerResource, das Informationen über eine platzierte Ebene in der PSD-Datei enthält."
type: docs
weight: 17
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Definiert das Interface IPlacedLayerResource, das Informationen über eine platzierte Ebene in der PSD‑Datei enthält. Es ist ein Markup‑Interface, das verwendet wird, um PlLd-, Sold- und Sole‑Ressourcen in Adobe\ufffd Photoshop\ufffd‑Bildern zu kennzeichnen. Es wird verwendet, um Smart‑Object‑Ebenen in Adobe\ufffd Photoshop\ufffd‑Bildern zu unterstützen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild. |
| [getBottom()](#getBottom--) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [getBounds()](#getBounds--) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [getItems()](#getItems--) | Liest oder setzt die Verzerrungsobjekte. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei. |
| [getPerspective()](#getPerspective--) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei. |
| [getRight()](#getRight--) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [getTop()](#getTop--) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [getTotalPages()](#getTotalPages--) | Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei. |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei. |
| [getUOrder()](#getUOrder--) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getUniqueId()](#getUniqueId--) | Liest oder setzt den global eindeutigen Bezeichner der platzierten oder Smart‑Object‑Ebene im PSD‑Bild. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getValue()](#getValue--) | Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild. |
| [getVersion()](#getVersion--) | Liest die Version der platzierten Ebene in der PSD‑Datei, normalerweise 3‑5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [isCustom()](#isCustom--) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild. |
| [setBottom(double value)](#setBottom-double-) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [setCustom(boolean value)](#setCustom-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Liest oder setzt die Verzerrungsobjekte. |
| [setLeft(double value)](#setLeft-double-) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [setPageNumber(int value)](#setPageNumber-int-) | Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei. |
| [setPerspective(double value)](#setPerspective-double-) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei. |
| [setRight(double value)](#setRight-double-) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [setTop(double value)](#setTop-double-) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [setTotalPages(int value)](#setTotalPages-int-) | Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei. |
| [setUOrder(int value)](#setUOrder-int-) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Liest oder setzt den global eindeutigen Bezeichner der platzierten oder Smart‑Object‑Ebene im PSD‑Bild. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [setValue(double value)](#setValue-double-) | Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild.

Wert: Die Antialias-Richtlinie der platzierten Ebene.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild.

Wert: Die untere Position der platzierten Ebene.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei.

Wert: Die Begrenzungen der platzierten Ebene.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Liest oder setzt die Maßeinheit der horizontalen Netzpunkte.

Wert: Die Maßeinheit der horizontalen Netzpunkte.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Liest oder setzt die Verzerrungsobjekte.

Wert: Die Warp-Elemente.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei.

Wert: Die linke Position der platzierten Ebene.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei.

Wert: Die Seitenzahl der platzierten Ebene.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der Perspektivwert der platzierten Ebene.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der weitere Perspektivwert der platzierten Ebene.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei.

Wert: Der Typ der platzierten Ebene.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei.

Wert: Die rechte Position der platzierten Ebene.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild.

Wert: Die obere Position der platzierten Ebene.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei.

Wert: Die Gesamtseiten der platzierten Ebene.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei.

Wert: Die Transformationsmatrix der platzierten Ebene.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der U-Ordnungswert der platzierten Ebene.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Liest oder setzt den global eindeutigen Bezeichner der platzierten oder Smart‑Object‑Ebene im PSD‑Bild.

Wert: Der eindeutige Bezeichner der platzierten Ebene.

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


Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der V-Ordnungswert der platzierten Ebene.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild.

Wert: Der Verzerrungswert der platzierten Ebene.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Liest die Version der platzierten Ebene in der PSD‑Datei, normalerweise 3‑5.

Wert: Die Version der platzierten oder Smart‑Object‑Ebene.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Liest oder setzt die Maßeinheit der vertikalen Netzpunkte.

Wert: Die Maßeinheit der vertikalen Netzpunkte.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Liest oder setzt einen Wert, der angibt, ob der Verzerrungsstil dieser Instanz benutzerdefiniert ist. Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte.

Wert:  true  wenn die platzierte oder Smart‑Object‑Ebene‑Ressource einen benutzerdefinierten Stil hat; andernfalls  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild.

Wert: Die Antialias-Richtlinie der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild.

Wert: Die untere Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei.

Wert: Die Begrenzungen der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob der Verzerrungsstil dieser Instanz benutzerdefiniert ist. Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte.

Wert:  true  wenn die platzierte oder Smart‑Object‑Ebene‑Ressource einen benutzerdefinierten Stil hat; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Liest oder setzt die Maßeinheit der horizontalen Netzpunkte.

Wert: Die Maßeinheit der horizontalen Netzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Liest oder setzt die Verzerrungsobjekte.

Wert: Die Warp-Elemente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei.

Wert: Die linke Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei.

Wert: Die Seitenzahl der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der Perspektivwert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der weitere Perspektivwert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei.

Wert: Der Typ der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei.

Wert: Die rechte Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild.

Wert: Die obere Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei.

Wert: Die Gesamtseiten der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei.

Wert: Die Transformationsmatrix der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der U-Ordnungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Liest oder setzt den global eindeutigen Bezeichner der platzierten oder Smart‑Object‑Ebene im PSD‑Bild.

Wert: Der eindeutige Bezeichner der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der V-Ordnungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild.

Wert: Der Verzerrungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Liest oder setzt die Maßeinheit der vertikalen Netzpunkte.

Wert: Die Maßeinheit der vertikalen Netzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

