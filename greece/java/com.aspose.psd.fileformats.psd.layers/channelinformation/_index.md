---
title: "ChannelInformation"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι πληροφορίες καναλιού."
type: docs
weight: 13
url: /el/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Οι πληροφορίες καναλιού.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Το Id του καναλιού μάσκας χρήστη (raster). |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Το Id του σύντομου καναλιού μάσκας (raster ή vector). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Το Id του καναλιού άλφα |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Συμπιέζει τα δεδομένα του καναλιού |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Κλωνοποιεί τις καθορισμένες πληροφορίες καναλιού. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Λαμβάνει το βάθος bit του καναλιού. |
| [getChannelID()](#getChannelID--) | Λαμβάνει ή ορίζει το ID του καναλιού. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης. |
| [getData_internalized()](#getData-internalized--) | Λαμβάνει ή ορίζει τα δεδομένα του καναλιού. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του καναλιού σε byte. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Λαμβάνει την έκδοση του PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Λαμβάνει τα μη συμπιεσμένα δεδομένα. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Λαμβάνει αν το κανάλι είναι ShortMask ή όχι |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Αποθηκεύει τα δεδομένα του καναλιού. |
| [setChannelID(short value)](#setChannelID-short-) | Λαμβάνει ή ορίζει το ID του καναλιού. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Ορίζει τα συμπιεσμένα δεδομένα. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Ορίζει τα συμπιεσμένα δεδομένα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Το Id του καναλιού μάσκας χρήστη (raster). (εάν ένα στρώμα έχει και διανυσματική και raster μάσκα).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Το Id του σύντομου (raster ή διανυσματικού) καναλιού μάσκας. (εάν ένα στρώμα έχει μόνο μία διανυσματική ή raster μάσκα, αλλά όχι και τις δύο).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Το Id του καναλιού άλφα

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Συμπιέζει τα δεδομένα του καναλιού

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawData | byte[] | Τα ακατέργαστα δεδομένα για συμπίεση |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια του στρώματος |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια της μάσκας στρώματος |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| πλάτος | int |  |
| ύψος | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Κλωνοποιεί τις καθορισμένες πληροφορίες καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Οι πληροφορίες. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Η κλωνοποιημένη μάσκα στρώματος.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Λαμβάνει το βάθος bit του καναλιού.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Λαμβάνει ή ορίζει το ID του καναλιού.

Τιμή: Το ID του καναλιού.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης.

Τιμή: Η μέθοδος συμπίεσης.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Λαμβάνει ή ορίζει τα δεδομένα του καναλιού.

Τιμή: Τα δεδομένα του καναλιού.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Λαμβάνει το μήκος του καναλιού σε byte.

Τιμή: Το μήκος.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Λαμβάνει την έκδοση του PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Λαμβάνει τα μη συμπιεσμένα δεδομένα.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Λαμβάνει αν το κανάλι είναι ShortMask ή όχι

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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Αποθηκεύει τα δεδομένα του καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| is32BitColor | boolean | αληθές εάν το χρώμα είναι σε λειτουργία 32-bit |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Λαμβάνει ή ορίζει το ID του καναλιού.

Τιμή: Το ID του καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Ορίζει τα συμπιεσμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| compressedData | byte[] | Τα συμπιεσμένα δεδομένα. |
| channelWidth | int | Πλάτος του καναλιού. |
| channelHeight | int | Ύψος του καναλιού. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης.

Τιμή: Η μέθοδος συμπίεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Ορίζει τα συμπιεσμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawData | byte[] | Τα ακατέργαστα δεδομένα. |
| imageSize | [Size](../../com.aspose.psd/size) | Το μέγεθος της εικόνας |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια των τρέχοντων δεδομένων καναλιού. Εάν η εικόνα είναι μεγάλη, θα χωριστεί κατά τη διαδικασία και currentBounds != imageBounds |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

