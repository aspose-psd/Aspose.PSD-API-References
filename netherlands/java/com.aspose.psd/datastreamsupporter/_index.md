---
title: "DataStreamSupporter"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De gegevensstroomcontainer."
type: docs
weight: 38
url: /nl/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

De gegevensstroomcontainer.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Treedt op wanneer afbeelding werd geladen of opgeslagen |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Treedt op wanneer krediet werd gebruikt |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [cacheData()](#cacheData--) | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer. |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Haalt de gegevensstroom van het object op. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Haalt het bestandspad van de bronafbeelding op als deze bestaat. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Slaat de gegevens van het object op in de huidige DataStreamSupporter. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(String filePath)](#save-java.lang.String-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Stelt de gegevensstroom van het object in. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Treedt op wanneer afbeelding werd geladen of opgeslagen

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Treedt op wanneer krediet werd gebruikt

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer.

### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Haalt de gegevensstroom van het object op.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Haalt het bestandspad van de bronafbeelding op als deze bestaat. Retourneert een lege string als het bronpad niet kan worden gevonden.

**Returns:**
java.lang.String - Het bestandspad van de bronafbeelding.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt

Waarde:  true  als het object een geheugenoptimalisatiestrategie gebruikt; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt
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


Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.

**Returns:**
boolean - een waarde die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.
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


Slaat de gegevens van het object op in de huidige DataStreamSupporter.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van het object op te slaan. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | De stream om de gegevens van het object op te slaan. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |
| overWrite | boolean | indien ingesteld op  true  wordt de bestandsinhoud overschreven, anders wordt toegevoegd. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Stelt de gegevensstroom van het object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | De gegevensstroom van het object. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Stelt een waarde in die aangeeft of [ignore after save].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als [ignore after save]; anders false. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

