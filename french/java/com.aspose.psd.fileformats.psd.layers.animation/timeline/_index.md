---
title: "Chronologie"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le modèle d'options de la chronologie."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

Le modèle d'options de la chronologie.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Timeline()](#Timeline--) | Initialise une nouvelle instance de la classe [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Appliquer les valeurs actuelles de la chronologie à l'image d'entrée PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Obtient ou définit la valeur AFSt. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Obtient ou définit l'index de la trame active. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Obtient la trame par identifiant. |
| [getFrames()](#getFrames--) | Obtient la liste des trames. |
| [getFramesList()](#getFramesList--) | Obtient la liste des trames. |
| [getFsID()](#getFsID--) | Obtient ou définit la valeur FsID. |
| [getLoopesCount()](#getLoopesCount--) | Obtient ou définit le nombre de boucles. |
| [getPsdImage()](#getPsdImage--) | Obtient ou définit le PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) de cette [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Enregistre les données du PsdImage et de la Timeline dans le flux spécifié au format spécifié selon les options d'enregistrement. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Enregistre les données du PsdImage et de la Timeline à l'emplacement de fichier spécifié au format spécifié selon les options d'enregistrement. |
| [setAFSt(int value)](#setAFSt-int-) | Obtient ou définit la valeur AFSt. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Obtient ou définit l'index de la trame active. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Obtient la liste des trames. |
| [setFsID(int value)](#setFsID-int-) | Obtient ou définit la valeur FsID. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Obtient ou définit le nombre de boucles. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Obtient ou définit le PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) de cette [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Bascule la trame active vers la trame ciblée. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Appliquer les valeurs actuelles de la chronologie à l'image d'entrée PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Initialise une nouvelle instance de la classe [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Appliquer les valeurs actuelles de la chronologie à l'image d'entrée PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | L'image psd. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Obtient ou définit la valeur AFSt.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Obtient ou définit l'index de la trame active.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


Obtient la trame par identifiant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frameId | int | L'identifiant de la trame. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Obtient la liste des trames.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Obtient la liste des trames.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Obtient ou définit la valeur FsID.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Obtient ou définit le nombre de boucles.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Obtient ou définit le PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) de cette [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


Enregistre les données du PsdImage et de la Timeline dans le flux spécifié au format spécifié selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | Le flux de sortie. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Enregistre les données du PsdImage et de la Timeline à l'emplacement de fichier spécifié au format spécifié selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Obtient ou définit la valeur AFSt.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Obtient ou définit l'index de la trame active.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Obtient la liste des trames.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Obtient ou définit la valeur FsID.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Obtient ou définit le nombre de boucles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Obtient ou définit le PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) de cette [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Bascule la trame active vers la trame ciblée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetActiveFrameIndex | int | L'index de trame cible. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


Appliquer les valeurs actuelles de la chronologie à l'image d'entrée PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frameIndex | int | L'index de trame pour mettre à jour les états des calques. |

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

