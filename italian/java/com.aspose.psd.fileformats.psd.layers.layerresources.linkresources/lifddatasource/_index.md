---
title: "LiFdDataSource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce la classe di origine dati liFD nel file PSD che contiene informazioni su un file incorporato."
type: docs
weight: 10
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

Definisce la classe di origine dati liFD nel file PSD che contiene informazioni su un file incorporato. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop®.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | Inizializza una nuova istanza della classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | La versione del descrittore. |
| [LatestVersion_internalized](#LatestVersion-internalized) | L'ultima versione disponibile della sorgente dati collegata |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Il valore di tipo della sorgente dati collegata inatteso |
| [ZeroChar_internalized](#ZeroChar-internalized) | Il carattere zero |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Ottiene o imposta un valore che indica se l'asset PSD è bloccato. |
| [getAssetModTime()](#getAssetModTime--) | Ottiene o imposta la data di modifica dell'asset, per gli asset delle librerie Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Ottiene o imposta l'identificatore del documento figlio nella sorgente dati liFE o liFD della risorsa Lnk2 / LnkE Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Ottiene o imposta l'ID della classe della risorsa. |
| [getClassName_internalized()](#getClassName-internalized--) | Ottiene o imposta il nome della classe di risorsa. |
| [getCompId()](#getCompId--) | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Ottiene o imposta la proprietà ContentID. |
| [getData()](#getData--) | Ottiene o imposta i dati dell'oggetto intelligente incorporato nel file PSD. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Ottiene la lunghezza dei dati incorporati. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Ottiene la lunghezza dei dati della sorgente del collegamento. |
| [getFileCreator()](#getFileCreator--) | Ottiene o imposta il creatore del file nella risorsa PSD formato LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Ottiene o imposta il tipo di file incorporato o esterno che la risorsa Adobe® Photoshop® Lnk2 / LnkE contiene o collega. |
| [getItems_internalized()](#getItems-internalized--) | Ottiene o imposta l'array OSTypeStructure che definisce le proprietà della risorsa. |
| [getLength()](#getLength--) | Ottiene la lunghezza della sorgente dati del collegamento in byte. |
| [getOriginalCompId()](#getOriginalCompId--) | Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [getOriginalFileName()](#getOriginalFileName--) | Ottiene il nome file originale della sorgente dati nella risorsa di collegamento globale Adobe® Photoshop®. |
| [getType()](#getType--) | Ottiene il tipo di sorgente dati del collegamento globale di Adobe® Photoshop® che può essere uno dei seguenti o nessuno: Il file collegato incorporato liFD che corrisponde alla risorsa PSD Lnk2Resource Il file collegato esterno liFE che corrisponde alla risorsa PSD LnkeResource L'alias del file collegato liFA |
| [getUniqueId()](#getUniqueId--) | Ottiene l'identificatore unico globale della sorgente dati nella risorsa di collegamento PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Ottiene o imposta i dati sconosciuti che precedono le proprietà Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Ottiene la versione della sorgente dati nella risorsa PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Ottiene o imposta un valore che indica se questa sorgente dati del collegamento ha il descrittore di file aperto: CompId e OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Ottiene un valore che indica se questa sorgente dati del collegamento PSD collega all'elemento della libreria Adobe® Photoshop® \\u0421\\u0421. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Salva i dati del blocco della sorgente dati del collegamento. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Ottiene o imposta un valore che indica se l'asset PSD è bloccato. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Ottiene o imposta la data di modifica dell'asset, per gli asset delle librerie Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Ottiene o imposta l'identificatore del documento figlio nella sorgente dati liFE o liFD della risorsa Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta l'ID della classe della risorsa. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Ottiene o imposta il nome della classe di risorsa. |
| [setCompId(int value)](#setCompId-int-) | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Ottiene o imposta la proprietà ContentID. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta i dati dell'oggetto intelligente incorporato nel file PSD. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Ottiene o imposta il creatore del file nella risorsa PSD formato LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Ottiene o imposta un valore che indica se questa sorgente dati del collegamento ha il descrittore di file aperto: CompId e OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Ottiene o imposta il tipo di file incorporato o esterno che la risorsa Adobe® Photoshop® Lnk2 / LnkE contiene o collega. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ottiene o imposta l'array OSTypeStructure che definisce le proprietà della risorsa. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Ottiene un valore che indica se questa sorgente dati del collegamento PSD collega all'elemento della libreria Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Ottiene il nome file originale della sorgente dati nella risorsa di collegamento globale Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Imposta il valore della proprietà per struttura di tipo. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Ottiene l'identificatore unico globale della sorgente dati nella risorsa di collegamento PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Ottiene o imposta i dati sconosciuti che precedono le proprietà Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


Inizializza una nuova istanza della classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Inizializza una nuova istanza della classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| version | int | La versione. |
| uniqueId | java.util.UUID | L'identificatore unico. |
| originalFileName | java.lang.String | Nome del file originale. |
| fileType | java.lang.String | Tipo del file. |
| fileCreator | java.lang.String | Il creatore del file. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


La versione del descrittore.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


L'ultima versione disponibile della sorgente dati collegata

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Il valore di tipo della sorgente dati collegata inatteso

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Il carattere zero

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| version | int |  |
| guid | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Ottiene o imposta un valore che indica se l'asset PSD è bloccato. Lo stato di blocco dell'asset, per gli asset delle Librerie Adobe® Photoshop® \u0421\u0421.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Ottiene o imposta la data di modifica dell'asset, per gli asset delle librerie Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Ottiene o imposta l'identificatore del documento figlio nella sorgente dati liFE o liFD della risorsa Lnk2 / LnkE Adobe® Photoshop®.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Ottiene o imposta l'ID della classe della risorsa.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Ottiene o imposta il nome della classe di risorsa.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comps, è possibile creare, gestire e visualizzare più versioni di un layout in un unico file Adobe® Photoshop®. Un layer comp è un'istantanea di uno stato del pannello Layers. I layer comps salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione del Layer Comp per Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Ottiene o imposta la proprietà ContentID. Il valore di questa proprietà viene letto e salvato solo quando Version è >= 8.

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


Ottiene o imposta i dati dell'oggetto intelligente incorporato nel file PSD.

Valore: I dati dell'oggetto intelligente incorporato.

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Ottiene la lunghezza dei dati incorporati.

Valore: La lunghezza dei dati incorporati.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Ottiene la lunghezza dei dati della sorgente del collegamento.

**Returns:**
long - La lunghezza dei dati di origine.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Ottiene o imposta il creatore del file nella risorsa PSD formato LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Ottiene o imposta il tipo di file incorporato o esterno che la risorsa Adobe® Photoshop® Lnk2 / LnkE contiene o collega.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Ottiene o imposta l'array OSTypeStructure che definisce le proprietà della risorsa.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Ottiene la lunghezza della sorgente dati del collegamento in byte.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. Questa proprietà ottiene l'identificatore di selezione originale del layer Comp per Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Ottiene il nome file originale della sorgente dati nella risorsa di collegamento globale Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Ottiene il tipo di sorgente dati del collegamento globale di Adobe® Photoshop® che può essere uno dei seguenti o nessuno: Il file collegato incorporato liFD che corrisponde alla risorsa PSD Lnk2Resource Il file collegato esterno liFE che corrisponde alla risorsa PSD LnkeResource L'alias del file collegato liFA

Valore: Il tipo di origine dati del collegamento PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Ottiene l'identificatore unico globale della sorgente dati nella risorsa di collegamento PSD.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Ottiene o imposta i dati sconosciuti che precedono le proprietà Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene la versione della sorgente dati nella risorsa PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Ottiene o imposta un valore che indica se questa sorgente dati del collegamento ha il descrittore di file aperto: CompId e OriginalCompId.

Valore:  true  se questa istanza ha un descrittore di file aperto; altrimenti,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Ottiene un valore che indica se questa sorgente dati del collegamento PSD collega all'elemento della libreria Adobe® Photoshop® \\u0421\\u0421.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Salva i dati del blocco della sorgente dati del collegamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Ottiene o imposta un valore che indica se l'asset PSD è bloccato. Lo stato di blocco dell'asset, per gli asset delle Librerie Adobe® Photoshop® \u0421\u0421.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Ottiene o imposta la data di modifica dell'asset, per gli asset delle librerie Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Ottiene o imposta l'identificatore del documento figlio nella sorgente dati liFE o liFD della risorsa Lnk2 / LnkE Adobe® Photoshop®.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Ottiene o imposta l'ID della classe della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Ottiene o imposta il nome della classe di risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comps, è possibile creare, gestire e visualizzare più versioni di un layout in un unico file Adobe® Photoshop®. Un layer comp è un'istantanea di uno stato del pannello Layers. I layer comps salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione del Layer Comp per Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Ottiene o imposta la proprietà ContentID. Il valore di questa proprietà viene letto e salvato solo quando Version è >= 8.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Ottiene o imposta i dati dell'oggetto intelligente incorporato nel file PSD.

Valore: I dati dell'oggetto intelligente incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Ottiene o imposta il creatore del file nella risorsa PSD formato LnkE / Lnk2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Ottiene o imposta un valore che indica se questa sorgente dati del collegamento ha il descrittore di file aperto: CompId e OriginalCompId.

Valore:  true  se questa istanza ha un descrittore di file aperto; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Ottiene o imposta il tipo di file incorporato o esterno che la risorsa Adobe® Photoshop® Lnk2 / LnkE contiene o collega.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Ottiene o imposta l'array OSTypeStructure che definisce le proprietà della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Ottiene un valore che indica se questa sorgente dati del collegamento PSD collega all'elemento della libreria Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. Questa proprietà ottiene l'identificatore di selezione originale del layer Comp per Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Ottiene il nome file originale della sorgente dati nella risorsa di collegamento globale Adobe® Photoshop®.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Imposta il valore della proprietà per struttura di tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La struttura. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Ottiene l'identificatore unico globale della sorgente dati nella risorsa di collegamento PSD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Ottiene o imposta i dati sconosciuti che precedono le proprietà Items OSTypeStructures.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

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

