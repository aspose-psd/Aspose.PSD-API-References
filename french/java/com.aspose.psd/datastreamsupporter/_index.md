---
title: "DataStreamSupporter"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le conteneur de flux de données."
type: docs
weight: 38
url: /fr/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Le conteneur de flux de données.
## Champs

| Champ | Description |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Se produit lorsque l'image a été chargée ou enregistrée |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Se produit lorsque le crédit a été utilisé |
## Méthodes

| Méthode | Description |
| --- | --- |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtient le flux de données de l'objet. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtient le chemin du fichier de l'image source si elle existe. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Enregistre les données de l'objet dans le  DataStreamSupporter  actuel. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Définit le flux de données de l'objet. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Définit une valeur indiquant si [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Se produit lorsque l'image a été chargée ou enregistrée

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Se produit lorsque le crédit a été utilisé

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent.

### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtient le flux de données de l'objet.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtient le chemin du fichier de l'image source si elle existe. Retourne une chaîne vide si le chemin source est introuvable.

**Returns:**
java.lang.String - Le chemin du fichier de l'image source.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire

Valeur :  true  si l'objet utilise la stratégie d'optimisation de mémoire ; sinon,  false .

**Returns:**
boolean - une valeur indiquant si l'objet utilise la stratégie d'optimisation de mémoire
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.

**Returns:**
boolean - une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Enregistre les données de l'objet dans le  DataStreamSupporter  actuel.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'objet. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le flux où enregistrer les données de l'objet. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |
| overWrite | booléen | si défini sur true, écrase le contenu du fichier, sinon une addition sera effectuée. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Définit le flux de données de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux de données de l'objet. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Définit une valeur indiquant si [ignore after save].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si [ignore after save] ; sinon, false. |

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

