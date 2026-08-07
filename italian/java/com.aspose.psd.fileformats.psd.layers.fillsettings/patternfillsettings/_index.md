---
title: "PatternFillSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Impostazioni dell'effetto di riempimento pattern"
type: docs
weight: 20
url: /it/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Impostazioni dell'effetto di riempimento pattern
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Inizializza una nuova istanza della classe [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Genera i nodi risorsa LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Ottiene o imposta un valore che indica se [link with layer]. |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ottiene o imposta il colore. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Il tipo di riempimento |
| [getHorizontalOffset()](#getHorizontalOffset--) | Ottiene o imposta lo spostamento orizzontale. |
| [getLinked()](#getLinked--) | Ottiene o imposta un valore che indica se questo [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) è collegato. |
| [getPatternData()](#getPatternData--) | Ottiene o imposta i dati del pattern. |
| [getPatternHeight()](#getPatternHeight--) | Ottiene o imposta l'altezza del pattern. |
| [getPatternId()](#getPatternId--) | Ottiene o imposta l'identificatore del pattern. |
| [getPatternName()](#getPatternName--) | Ottiene o imposta il nome del pattern. |
| [getPatternWidth()](#getPatternWidth--) | Ottiene o imposta la larghezza del pattern. |
| [getPhase_internalized()](#getPhase-internalized--) | Ottiene o imposta la fase. |
| [getPointType()](#getPointType--) | Ottiene o imposta il tipo del punto. |
| [getScale()](#getScale--) | Ottiene o imposta la scala. |
| [getVerticalOffset()](#getVerticalOffset--) | Ottiene o imposta lo spostamento verticale. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera la modifica del valore. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Ottiene o imposta un valore che indica se [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Ottiene o imposta il colore. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Ottiene o imposta lo spostamento orizzontale. |
| [setLinked(boolean value)](#setLinked-boolean-) | Ottiene o imposta un valore che indica se questo [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) è collegato. |
| [setPatternData(int[] value)](#setPatternData-int---) | Ottiene o imposta i dati del pattern. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Imposta il buffer dei pixel del pattern e la modalità di compressione da utilizzare durante il salvataggio. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Ottiene o imposta l'altezza del pattern. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Ottiene o imposta l'identificatore del pattern. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Ottiene o imposta il nome del pattern. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Ottiene o imposta la larghezza del pattern. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Ottiene o imposta la fase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Ottiene o imposta il tipo del punto. |
| [setScale(double value)](#setScale-double-) | Ottiene o imposta la scala. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Ottiene o imposta lo spostamento verticale. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Imposta i dati predefiniti del pattern nell'istanza [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Aggiorna le proprietà del pattern dall'istanza [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Inizializza una nuova istanza della classe [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Genera i nodi risorsa LFX2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pointType | java.lang.String | Tipo del punto. |
| color | [Color](../../com.aspose.psd/color) | Il colore. |
| patternName | java.lang.String | Nome del modello. |
| identifier | java.lang.String | L'identificatore. |
| scale | double | La scala. |
| collegato | boolean | se impostato su  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | L'offset. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Elenco di [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Ottiene o imposta un valore che indica se [link with layer].

Valore:  true  se [link with layer]; altrimenti,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Ottiene o imposta l'angolo.

Valore: L'angolo.

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


Ottiene o imposta il colore.

Valore: Il colore.

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


Il tipo di riempimento

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Ottiene o imposta lo spostamento orizzontale.

Valore: Lo spostamento orizzontale.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Ottiene o imposta un valore che indica se questo [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) è collegato.

Valore:  true  se collegato; altrimenti,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Ottiene o imposta i dati del pattern.

Valore: I dati del modello.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Ottiene o imposta l'altezza del pattern.

Valore: L'altezza del modello.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Ottiene o imposta l'identificatore del pattern.

Valore: L'identificatore del modello.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Ottiene o imposta il nome del pattern.

Valore: Il nome del modello.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Ottiene o imposta la larghezza del pattern.

Valore: La larghezza del modello.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Ottiene o imposta la fase.

Valore: La fase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Ottiene o imposta il tipo del punto.

Valore: Il tipo del punto.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Ottiene o imposta la scala.

Valore: La scala.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Ottiene o imposta lo spostamento verticale.

Valore: Lo spostamento verticale.

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


Genera la modifica del valore.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Ottiene o imposta un valore che indica se [link with layer].

Valore:  true  se [link with layer]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Ottiene o imposta l'angolo.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore.

Valore: Il colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Ottiene o imposta lo spostamento orizzontale.

Valore: Lo spostamento orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Ottiene o imposta un valore che indica se questo [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) è collegato.

Valore:  true  se collegato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Ottiene o imposta i dati del pattern.

Valore: I dati del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Imposta il buffer dei pixel del pattern e la modalità di compressione da utilizzare durante il salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| patternData | int[] | Pixel a 32 bit in  0xAARRGGBB . |
| compressionModeOnSave | byte | La modalità di compressione utilizzata per definire la compressione dei dati del modello al salvataggio del file psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Ottiene o imposta l'altezza del pattern.

Valore: L'altezza del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Ottiene o imposta l'identificatore del pattern.

Valore: L'identificatore del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Ottiene o imposta il nome del pattern.

Valore: Il nome del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Ottiene o imposta la larghezza del pattern.

Valore: La larghezza del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Ottiene o imposta la fase.

Valore: La fase.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Ottiene o imposta il tipo del punto.

Valore: Il tipo del punto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Ottiene o imposta la scala.

Valore: La scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Ottiene o imposta lo spostamento verticale.

Valore: Lo spostamento verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Imposta i dati predefiniti del pattern nell'istanza [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Le impostazioni di riempimento pattern. |

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


Aggiorna le proprietà del pattern dall'istanza [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | L'istanza di [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) con i dati del modello. |

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

