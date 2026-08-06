---
title: "PatternFillSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres d'effet de remplissage de motif"
type: docs
weight: 20
url: /fr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Paramètres d'effet de remplissage de motif
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Initialise une nouvelle instance de la classe [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Champs

| Champ | Description |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Génère les nœuds de ressources LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtient ou définit une valeur indiquant si [link with layer]. |
| [getAngle()](#getAngle--) | Obtient ou définit l’angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient ou définit la couleur. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Le type de remplissage |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal. |
| [getLinked()](#getLinked--) | Obtient ou définit une valeur indiquant si ce [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) est lié. |
| [getPatternData()](#getPatternData--) | Obtient ou définit les données du motif. |
| [getPatternHeight()](#getPatternHeight--) | Obtient ou définit la hauteur du motif. |
| [getPatternId()](#getPatternId--) | Obtient ou définit l’identifiant du motif. |
| [getPatternName()](#getPatternName--) | Obtient ou définit le nom du motif. |
| [getPatternWidth()](#getPatternWidth--) | Obtient ou définit la largeur du motif. |
| [getPhase_internalized()](#getPhase-internalized--) | Obtient ou définit la phase. |
| [getPointType()](#getPointType--) | Obtient ou définit le type du point. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Déclenche la modification de la valeur. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l’angle. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtient ou définit la couleur. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Obtient ou définit le décalage horizontal. |
| [setLinked(boolean value)](#setLinked-boolean-) | Obtient ou définit une valeur indiquant si ce [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) est lié. |
| [setPatternData(int[] value)](#setPatternData-int---) | Obtient ou définit les données du motif. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Définit le tampon de pixels du pattern\u2019s et le mode de compression à utiliser lors de l’enregistrement. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Obtient ou définit la hauteur du motif. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Obtient ou définit l’identifiant du motif. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Obtient ou définit le nom du motif. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Obtient ou définit la largeur du motif. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Obtient ou définit la phase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Obtient ou définit le type du point. |
| [setScale(double value)](#setScale-double-) | Obtient ou définit l'échelle. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Obtient ou définit le décalage vertical. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Configure les données par défaut du motif dans l’instance [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Met à jour les propriétés du motif à partir de l’instance [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Initialise une nouvelle instance de la classe [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Génère les nœuds de ressources LFX2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pointType | java.lang.String | Type du point. |
| color | [Color](../../com.aspose.psd/color) | La couleur. |
| patternName | java.lang.String | Nom du motif. |
| identifier | java.lang.String | L'identifiant. |
| échelle | double | L'échelle. |
| lié | booléen | si défini sur  true  [lié]. |
| offset | [PointF](../../com.aspose.psd/pointf) | Le décalage. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Liste de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtient ou définit une valeur indiquant si [link with layer].

Valeur:  true  si [lien avec le calque]; sinon,  false .

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtient ou définit l’angle.

Valeur : l'angle.

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


Obtient ou définit la couleur.

Valeur: la couleur.

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


Le type de remplissage

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Obtient ou définit le décalage horizontal.

Valeur: Le décalage horizontal.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Obtient ou définit une valeur indiquant si ce [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) est lié.

Valeur:  true  si lié; sinon,  false .

**Returns:**
booléen
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Obtient ou définit les données du motif.

Valeur: Les données du motif.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Obtient ou définit la hauteur du motif.

Valeur: La hauteur du motif.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Obtient ou définit l’identifiant du motif.

Valeur: L'identifiant du motif.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Obtient ou définit le nom du motif.

Valeur: Le nom du motif.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Obtient ou définit la largeur du motif.

Valeur: La largeur du motif.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Obtient ou définit la phase.

Valeur: La phase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Obtient ou définit le type du point.

Valeur: Le type du point.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Obtient ou définit l'échelle.

Valeur : l'échelle.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Obtient ou définit le décalage vertical.

Valeur: Le décalage vertical.

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


Déclenche la modification de la valeur.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Obtient ou définit une valeur indiquant si [link with layer].

Valeur:  true  si [lien avec le calque]; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtient ou définit l’angle.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur.

Valeur: la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Obtient ou définit le décalage horizontal.

Valeur: Le décalage horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Obtient ou définit une valeur indiquant si ce [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) est lié.

Valeur:  true  si lié; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Obtient ou définit les données du motif.

Valeur: Les données du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Définit le tampon de pixels du pattern\u2019s et le mode de compression à utiliser lors de l’enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| patternData | int[] | Pixels 32 bits dans  0xAARRGGBB . |
| compressionModeOnSave | byte | Le mode de compression utilisé pour définir la compression des données du motif lors de l'enregistrement du fichier psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Obtient ou définit la hauteur du motif.

Valeur: La hauteur du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Obtient ou définit l’identifiant du motif.

Valeur: L'identifiant du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Obtient ou définit le nom du motif.

Valeur: Le nom du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Obtient ou définit la largeur du motif.

Valeur: La largeur du motif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Obtient ou définit la phase.

Valeur: La phase.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Obtient ou définit le type du point.

Valeur: Le type du point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Obtient ou définit l'échelle.

Valeur : l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Obtient ou définit le décalage vertical.

Valeur: Le décalage vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Configure les données par défaut du motif dans l’instance [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Les paramètres de remplissage de motif. |

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


Met à jour les propriétés du motif à partir de l’instance [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | L'instance [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) avec les données du motif. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

