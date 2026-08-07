---
title: "IPlacedLayerResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce l'interfaccia IPlacedLayerResource che contiene informazioni su un livello posizionato nel file PSD."
type: docs
weight: 17
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Definisce l'interfaccia IPlacedLayerResource che contiene informazioni su un livello posizionato nel file PSD. È un'interfaccia di markup utilizzata per designare le risorse PlLd, Sold e Sole nelle immagini Adobe\\ufffd Photoshop\\ufffd. È utilizzata per supportare i livelli oggetto intelligente nelle immagini Adobe\\ufffd Photoshop\\ufffd.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Ottiene o imposta la politica anti alias del livello posizionato nell'immagine PSD. |
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Ottiene o imposta l'unità di misura dei punti della griglia orizzontale. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [getItems()](#getItems--) | Ottiene o imposta gli elementi del warp. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD. |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il numero di pagina del livello posizionato nel file PSD. |
| [getPerspective()](#getPerspective--) | Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Ottiene o imposta il tipo del livello posizionato nel file PSD. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra del livello posizionato nel file PSD. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD. |
| [getTotalPages()](#getTotalPages--) | Ottiene o imposta il numero totale di pagine del livello posizionato nel file PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta la matrice di trasformazione del livello posizionato nel file PSD. |
| [getUOrder()](#getUOrder--) | Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD. |
| [getUniqueId()](#getUniqueId--) | Ottiene o imposta l'identificatore unico globale del livello oggetto intelligente posizionato nell'immagine PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD. |
| [getValue()](#getValue--) | Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD. |
| [getVersion()](#getVersion--) | Ottiene la versione del livello posizionato nel file PSD, di solito 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Ottiene o imposta l'unità di misura dei punti della griglia verticale. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [isCustom()](#isCustom--) | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Ottiene o imposta la politica anti alias del livello posizionato nell'immagine PSD. |
| [setBottom(double value)](#setBottom-double-) | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Ottiene o imposta l'unità di misura dei punti della griglia orizzontale. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ottiene o imposta gli elementi del warp. |
| [setLeft(double value)](#setLeft-double-) | Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Ottiene o imposta il numero di pagina del livello posizionato nel file PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Ottiene o imposta il tipo del livello posizionato nel file PSD. |
| [setRight(double value)](#setRight-double-) | Ottiene o imposta la posizione destra del livello posizionato nel file PSD. |
| [setTop(double value)](#setTop-double-) | Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Ottiene o imposta il numero totale di pagine del livello posizionato nel file PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Ottiene o imposta la matrice di trasformazione del livello posizionato nel file PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Ottiene o imposta l'identificatore unico globale del livello oggetto intelligente posizionato nell'immagine PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD. |
| [setValue(double value)](#setValue-double-) | Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Ottiene o imposta l'unità di misura dei punti della griglia verticale. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Ottiene o imposta la politica anti alias del livello posizionato nell'immagine PSD.

Valore: La politica di anti-alias del livello posizionato.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD.

Valore: La posizione inferiore del livello posizionato.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Ottiene o imposta i limiti del livello posizionato nel file PSD.

Valore: I limiti del livello posizionato.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Ottiene o imposta l'unità di misura dei punti della griglia orizzontale.

Valore: L'unità di misura dei punti della griglia orizzontale.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Ottiene o imposta gli elementi del warp.

Valore: Gli elementi di deformazione.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD.

Valore: La posizione sinistra del livello posizionato.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Ottiene o imposta il numero di pagina del livello posizionato nel file PSD.

Valore: Il numero di pagina del livello posizionato.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD.

Valore: Il valore di prospettiva del livello posizionato.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD.

Valore: L'altro valore di prospettiva del livello posizionato.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Ottiene o imposta il tipo del livello posizionato nel file PSD.

Valore: Il tipo del livello posizionato.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Ottiene o imposta la posizione destra del livello posizionato nel file PSD.

Valore: La posizione destra del livello posizionato.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD.

Valore: La posizione superiore del livello posizionato.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Ottiene o imposta il numero totale di pagine del livello posizionato nel file PSD.

Valore: Il totale delle pagine del livello posizionato.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Ottiene o imposta la matrice di trasformazione del livello posizionato nel file PSD.

Valore: La matrice di trasformazione del livello posizionato.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD.

Valore: Il valore dell'ordine U del livello posizionato.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Ottiene o imposta l'identificatore unico globale del livello oggetto intelligente posizionato nell'immagine PSD.

Valore: L'identificatore unico del livello posizionato.

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


Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD.

Valore: Il valore dell'ordine V del livello posizionato.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD.

Valore: Il valore di deformazione del livello posizionato.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Ottiene la versione del livello posizionato nel file PSD, di solito 3-5.

Valore: la versione del livello posizionato o smart object.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Ottiene o imposta l'unità di misura dei punti della griglia verticale.

Valore: L'unità di misura dei punti della griglia verticale.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. Se true contiene punti della mesh. Se impostato a false elimina i punti della mesh.

Valore:  true  se la risorsa del livello posizionato o smart object ha uno stile personalizzato; altrimenti,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Ottiene o imposta la politica anti alias del livello posizionato nell'immagine PSD.

Valore: La politica di anti-alias del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD.

Valore: La posizione inferiore del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Ottiene o imposta i limiti del livello posizionato nel file PSD.

Valore: I limiti del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. Se true contiene punti della mesh. Se impostato a false elimina i punti della mesh.

Valore:  true  se la risorsa del livello posizionato o smart object ha uno stile personalizzato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Ottiene o imposta l'unità di misura dei punti della griglia orizzontale.

Valore: L'unità di misura dei punti della griglia orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Ottiene o imposta gli elementi del warp.

Valore: Gli elementi di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD.

Valore: La posizione sinistra del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Ottiene o imposta il numero di pagina del livello posizionato nel file PSD.

Valore: Il numero di pagina del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD.

Valore: Il valore di prospettiva del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD.

Valore: L'altro valore di prospettiva del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Ottiene o imposta il tipo del livello posizionato nel file PSD.

Valore: Il tipo del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Ottiene o imposta la posizione destra del livello posizionato nel file PSD.

Valore: La posizione destra del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD.

Valore: La posizione superiore del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Ottiene o imposta il numero totale di pagine del livello posizionato nel file PSD.

Valore: Il totale delle pagine del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Ottiene o imposta la matrice di trasformazione del livello posizionato nel file PSD.

Valore: La matrice di trasformazione del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD.

Valore: Il valore dell'ordine U del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Ottiene o imposta l'identificatore unico globale del livello oggetto intelligente posizionato nell'immagine PSD.

Valore: L'identificatore unico del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD.

Valore: Il valore dell'ordine V del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD.

Valore: Il valore di deformazione del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Ottiene o imposta l'unità di misura dei punti della griglia verticale.

Valore: L'unità di misura dei punti della griglia verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

