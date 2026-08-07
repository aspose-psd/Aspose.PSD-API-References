---
title: "StringStructure"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La struttura stringa."
type: docs
weight: 26
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
```
public final class StringStructure extends OSTypeStructure
```

La struttura stringa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StringStructure(ClassID keyName)](#StringStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Inizializza una nuova istanza della classe [StringStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [StructureKey](#StructureKey) | Identifica la chiave della struttura. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Trova la struttura per valore del nome della chiave. |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Trova la struttura per valore del nome della chiave. |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Organizza le strutture in un unico dizionario per nome della chiave. |
| [createColorDescriptor_internalized(Color value)](#createColorDescriptor-internalized-com.aspose.psd.Color-) |  |
| [createColorDescriptor_internalized(Color value, String keyName)](#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-) | Crea il [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) con valore di colore con il nome della chiave specificato. |
| [create_internalized(ClassID keyName, String value)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore booleano dall'elenco delle strutture per nome della chiave. |
| [getClass()](#getClass--) |  |
| [getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore di colore dall'elenco delle strutture per nome della chiave. |
| [getColorValue_internalized(List<OSTypeStructure> itemsList)](#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [getCopy_internalized()](#getCopy-internalized--) | Crea una copia completa di questa struttura. |
| [getHeaderLength()](#getHeaderLength--) | Ottiene la lunghezza dell'intestazione. |
| [getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore int32 dall'elenco delle strutture per nome della chiave. |
| [getKey()](#getKey--) | Ottiene la chiave. |
| [getKeyName()](#getKeyName--) | Ottiene o imposta il nome della chiave. |
| [getLength()](#getLength--) | Ottiene la lunghezza in byte del [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene l'elenco dei valori delle strutture da un altro elenco di strutture per nome della chiave. |
| [getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore PointF dall'elenco delle strutture per nome della chiave. |
| [getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore RectangleF dall'elenco delle strutture per nome della chiave. |
| [getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ottiene il valore stringa dall'elenco delle strutture per nome della chiave. |
| [getValue()](#getValue--) | Ottiene o imposta il valore. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Trova e rimuove la struttura dall'elenco degli elementi di input. |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Salva la struttura nel contenitore di stream specificato. |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | Salva la struttura nel contenitore di stream specificato. |
| [setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore booleano nell'elenco delle strutture per nome della chiave. |
| [setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore di colore in un elenco di strutture per nome della chiave. |
| [setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)](#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore int32 nell'elenco delle strutture per nome della chiave. |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta il nome della chiave. |
| [setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta l'elenco dei valori delle strutture in un altro elenco di strutture per nome della chiave. |
| [setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore PointF nell'elenco delle strutture per nome della chiave. |
| [setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore RectangleF nell'elenco delle strutture per nome della chiave. |
| [setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Imposta il valore stringa nella lista di strutture per nome chiave. |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Aggiungi o aggiorna la struttura all'elenco di elementi di input. |
| [setValue(String value)](#setValue-java.lang.String-) | Ottiene o imposta il valore. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringStructure(ClassID keyName) {#StringStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public StringStructure(ClassID keyName)
```


Inizializza una nuova istanza della classe [StringStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Il nome della chiave. |

### StructureKey {#StructureKey}
```
public static final int StructureKey
```


Identifica la chiave della struttura.

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


Trova la struttura per valore del nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | java.lang.String | Il nome della chiave. |
|  | container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Il contenitore di elementi in cui cercare. |

T : Il tipo dell'oggetto risultato. |

**Returns:**
T - La struttura per valore del nome chiave.
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


Trova la struttura per valore del nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | java.lang.String | Il nome della chiave. |
|  | elementi | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Gli elementi in cui cercare. |

T : Il tipo dell'oggetto risultato. |

**Returns:**
T - La struttura per valore del nome chiave.
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


Organizza le strutture in un unico dizionario per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Le strutture |
| dizionario | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Il dizionario da organizzare |
| prefisso | java.lang.String | Il prefisso per i nomi delle chiavi. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Strutture organizzate come dizionario per nome chiave.
### createColorDescriptor_internalized(Color value) {#createColorDescriptor-internalized-com.aspose.psd.Color-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### createColorDescriptor_internalized(Color value, String keyName) {#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value, String keyName)
```


Crea il [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) con valore di colore con il nome della chiave specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Il valore del colore. |
| keyName | java.lang.String | Il nome della chiave. |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### create_internalized(ClassID keyName, String value) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-java.lang.String-}
```
public static StringStructure create_internalized(ClassID keyName, String value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |
| valore | java.lang.String |  |

**Returns:**
[StringStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure)
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
### getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static boolean getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore booleano dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
boolean - Il valore booleano dall'elenco di strutture se esiste, altrimenti il valore predefinito.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static Color getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore di colore dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color value from the structures list if it exists, otherwise the default value.
### getColorValue_internalized(List<OSTypeStructure> itemsList) {#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static Color getColorValue_internalized(List<OSTypeStructure> itemsList)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

**Returns:**
[Color](../../com.aspose.psd/color)
### getCopy_internalized() {#getCopy-internalized--}
```
public final OSTypeStructure getCopy_internalized()
```


Crea una copia completa di questa struttura.

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - Returns the full copy of this structure.
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


Ottiene la lunghezza dell'intestazione.

**Returns:**
int - La lunghezza dell'intestazione
### getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static int getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore int32 dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
int - Il valore int32 dall'elenco di strutture se esiste, altrimenti il valore predefinito.
### getKey() {#getKey--}
```
public int getKey()
```


Ottiene la chiave.

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


Ottiene o imposta il nome della chiave.

Valore: Il nome della chiave.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene la lunghezza in byte del [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Returns:**
int
### getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.List<OSTypeStructure> getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene l'elenco dei valori delle strutture da un altro elenco di strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - L'elenco dei valori delle strutture dalla lista di altre strutture se esiste, altrimenti il valore predefinito.
### getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static PointF getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore PointF dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The PointF value from the structures list if it exists, otherwise the default value.
### getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static RectangleF getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore RectangleF dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The RectangleF value from the structures list if it exists, otherwise the default value.
### getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static String getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ottiene il valore stringa dall'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | L'elenco di strutture in cui cercare. |
| keyName | java.lang.String | Il nome della chiave da utilizzare per la ricerca. |

**Returns:**
java.lang.String - Il valore stringa dalla lista delle strutture se esiste, altrimenti il valore predefinito.
### getValue() {#getValue--}
```
public final String getValue()
```


Ottiene o imposta il valore.

Valore: Il valore.

**Returns:**
java.lang.String
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




### removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items) {#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)
```


Trova e rimuove la struttura dall'elenco degli elementi di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | java.lang.String | Il nome della chiave. |
| elementi | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Gli elementi. |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Salva la struttura nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


Salva la struttura nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

### setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore booleano nell'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore di colore in un elenco di strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setColorValue_internalized(Color value, List<OSTypeStructure> itemsList) {#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore int32 nell'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


Ottiene o imposta il nome della chiave.

Valore: Il nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta l'elenco dei valori delle strutture in un altro elenco di strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore PointF nell'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore RectangleF nell'elenco delle strutture per nome della chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Imposta il valore stringa nella lista di strutture per nome chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il valore da impostare. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | La lista delle strutture. |
| keyName | java.lang.String | Il nome della chiave. |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


Aggiungi o aggiorna la struttura all'elenco di elementi di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La struttura da aggiungere o aggiornare. |
| elementi | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Gli elementi. |

### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Ottiene o imposta il valore.

Valore: Il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

