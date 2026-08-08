---
title: "SplitStreamContainer"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een gesplitste streamcontainer voor die de stream bevat en streamverwerkingsroutines biedt."
type: docs
weight: 102
url: /nl/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Stelt een gesplitste streamcontainer voor die de stream bevat en streamverwerkingsroutines biedt.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Specificeert het aantal lees- en schrijfbytes bij sequentieel lezen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canRead()](#canRead--) | Haalt een waarde op die aangeeft of de stream lezen ondersteunt. |
| [canSeek()](#canSeek--) | Haalt een waarde op die aangeeft of de stream zoeken ondersteunt. |
| [canWrite()](#canWrite--) | Haalt een waarde op die aangeeft of de stream schrijven ondersteunt. |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Leegt alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getLength()](#getLength--) | Haalt de lengte van de stream op of stelt deze in bytes in. |
| [getPosition()](#getPosition--) | Haalt de huidige positie binnen de stream op of stelt deze in. |
| [getStream()](#getStream--) | Haalt de datastream op. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Voegt de streamcontainer in op de opgegeven positie. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Haalt een waarde op die aangeeft of deze stream bij sluiten wordt vrijgegeven. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Leest bytes om de opgegeven bytebuffer te vullen. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Leest een reeks bytes van de huidige stream en verplaatst de positie binnen de stream met het aantal gelezen bytes. |
| [readByte()](#readByte--) | Leest een byte van de stream en verplaatst de positie binnen de stream met één byte, of retourneert -1 als het einde van de stream is bereikt. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Slaat (kopieert) alle gegevens van de stream op naar de opgegeven stream. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save(String filePath)](#save-java.lang.String-) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Stelt de positie binnen de huidige stream in. |
| [seekBegin()](#seekBegin--) | Stelt de streampositie in op het begin van de stream. |
| [setLength(long value)](#setLength-long-) | Haalt de lengte van de stream op of stelt deze in bytes in. |
| [setPosition(long value)](#setPosition-long-) | Haalt de huidige positie binnen de stream op of stelt deze in. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Converteert de streamgegevens naar de  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converteert de streamgegevens naar de  byte  array. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Voert een expliciete conversie uit van  com.aspose.imaging.StreamContainer  naar  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Schrijft alle opgegeven bytes naar de stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Schrijft een reeks bytes naar de huidige stream en verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes. |
| [writeByte(byte value)](#writeByte-byte-) | Schrijft een byte naar de huidige positie in de stream en verplaatst de positie binnen de stream met één byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Kopieert de ingesloten gegevens naar een andere  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Kopieert de ingesloten gegevens naar een andere  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De datastream. |
| disposeStream | boolean | als ingesteld op  true  wordt de stream vrijgegeven wanneer de container wordt vrijgegeven. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initialiseert een nieuw exemplaar van de [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| disposeStream | boolean | indien ingesteld op  true  wordt de stream vrijgegeven. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Specificeert het aantal lees- en schrijfbytes bij sequentieel lezen.

### canRead() {#canRead--}
```
public boolean canRead()
```


Haalt een waarde op die aangeeft of de stream lezen ondersteunt.

Waarde:  true  als de stream lezen ondersteunt; anders,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Haalt een waarde op die aangeeft of de stream zoeken ondersteunt.

Waarde:  true  als de stream zoeken ondersteunt; anders,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Haalt een waarde op die aangeeft of de stream schrijven ondersteunt.

Waarde:  true  als de stream schrijven ondersteunt; anders,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

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
### flush() {#flush--}
```
public void flush()
```


Leegt alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Haalt of stelt de streamlengte in bytes in. Deze waarde is kleiner dan de  System.IO.Stream.Length  met de startpositie van de stream die is doorgegeven in de StreamContainer‑constructor.

Waarde: De streamlengte.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Haalt op of stelt de huidige positie binnen de stream in. Deze waarde geeft de offset weer vanaf de startpositie van de stream die is doorgegeven in de StreamContainer‑constructor.

Waarde: De huidige streampositie.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Haalt de datastream op.

Waarde: De datastream.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren.

Waarde: Het object dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Voegt de streamcontainer in op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | De positie om in te voegen. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om in te voegen. |
| disposeStream | boolean | indien ingesteld op  true  wordt de stream vrijgegeven. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Haalt een waarde op die aangeeft of deze stream bij sluiten wordt vrijgegeven.

Waarde:  true  als de stream wordt vrijgegeven bij sluiten; anders,  false .

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




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Leest bytes om de opgegeven bytebuffer te vullen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | byte[] | De bytes om te vullen. |

**Returns:**
int - Het aantal gelezen bytes. Deze waarde kan kleiner zijn dan het aantal bytes in de buffer als er niet genoeg bytes in de stream aanwezig zijn.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Leest een reeks bytes van de huidige stream en verplaatst de positie binnen de stream met het aantal gelezen bytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | byte[] | Een array van bytes. Wanneer deze methode terugkeert, bevat de buffer de opgegeven byte‑array met de waarden tussen  offset  en ( offset  +  count  - 1) vervangen door de bytes die zijn gelezen van de huidige bron. |
| offset | int | De nulgebaseerde byte‑offset in  buffer  waarop de gegevens die van de huidige stream zijn gelezen, moeten worden opgeslagen. |
| count | int | Het maximale aantal bytes dat uit de huidige stream moet worden gelezen. |

**Returns:**
int - Het totale aantal bytes dat in de buffer is gelezen. Dit kan minder zijn dan het aangevraagde aantal bytes als dat aantal momenteel niet beschikbaar is, of nul (0) als het einde van de stream is bereikt.
### readByte() {#readByte--}
```
public int readByte()
```


Leest een byte van de stream en verplaatst de positie binnen de stream met één byte, of retourneert -1 als het einde van de stream is bereikt.

**Returns:**
int - De ongetekende byte omgezet naar een Int32, of -1 als het einde van de stream is bereikt.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaard buffergrootte  ReadWriteBytesCount  en de stream  Length  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | De stream om de gegevens in op te slaan. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Slaat (kopieert) alle gegevens van de stream op naar de opgegeven stream. Gebruikt de stream  Length  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | De stream om de gegevens in op te slaan. |
| bufferSize | int | De buffer. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstStream | java.io.OutputStream | De stream om de gegevens in op te slaan. |
| bufferSize | int | De buffergrootte. Standaard wordt de waarde van [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT) gebruikt. |
| length | long | De lengte van de streamgegevens die gekopieerd moeten worden. Standaard wordt de lengte ingesteld op de waarde van Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaard buffergrootte  ReadWriteBytesCount  en de stream  Length  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de streamgegevens op te slaan. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de waarde van stream Length.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de streamgegevens op te slaan. |
| bufferSize | int | De buffergrootte. Standaard wordt de waarde van ReadWriteBytesCount gebruikt. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de streamgegevens op te slaan. |
| bufferSize | int | De buffergrootte. Standaard wordt de waarde van ReadWriteBytesCount gebruikt. |
| lengte | long | De lengte van de streamgegevens die gekopieerd moeten worden. Standaard wordt de lengte ingesteld op de waarde van Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| lengte | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Stelt de positie binnen de huidige stream in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offset | long | Een byte-offset ten opzichte van de origin-parameter. Deze waarde geeft de offset weer vanaf de beginnende streampositie die is doorgegeven in de StreamContainer‑constructor. |
| origin | int | Een waarde van het type [SeekOrigin](../../com.aspose.psd/seekorigin) die het referentiepunt aangeeft dat wordt gebruikt om de nieuwe positie te verkrijgen. |

**Returns:**
long - De nieuwe positie binnen de huidige stream.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Stelt de streampositie in op het begin van de stream. Deze waarde geeft de offset weer vanaf de beginnende streampositie die is doorgegeven in de StreamContainer‑constructor.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Haalt of stelt de streamlengte in bytes in. Deze waarde is kleiner dan de  System.IO.Stream.Length  met de startpositie van de stream die is doorgegeven in de StreamContainer‑constructor.

Waarde: De streamlengte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Haalt op of stelt de huidige positie binnen de stream in. Deze waarde geeft de offset weer vanaf de startpositie van de stream die is doorgegeven in de StreamContainer‑constructor.

Waarde: De huidige streampositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Converteert de streamgegevens naar de  byte  array.

**Returns:**
byte[] - De streamgegevens geconverteerd naar de byte‑array.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Converteert de streamgegevens naar de  byte  array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie vanaf waar bytes gelezen moeten worden. |
| bytesCount | long | Het aantal te lezen bytes. |

**Returns:**
byte[] - De streamgegevens geconverteerd naar de byte‑array.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Voert een expliciete conversie uit van  com.aspose.imaging.StreamContainer  naar  System.IO.Stream .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |

**Returns:**
com.aspose.ms.System.IO.Stream - Het resultaat van de conversie.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Schrijft alle opgegeven bytes naar de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | byte[] | De te schrijven bytes. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Schrijft een reeks bytes naar de huidige stream en verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | byte[] | Een array van bytes. Deze methode kopieert count bytes van buffer naar de huidige stream. |
| offset | int | De nulgebaseerde byte-offset in buffer waarop begonnen wordt met het kopiëren van bytes naar de huidige stream. |
| count | int | Het aantal bytes dat naar de huidige stream moet worden geschreven. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Schrijft een byte naar de huidige positie in de stream en verplaatst de positie binnen de stream met één byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte | De byte die naar de stream moet worden geschreven. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Kopieert de ingesloten gegevens naar een andere  StreamContainer .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer waarnaar gekopieerd moet worden. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Kopieert de ingesloten gegevens naar een andere  StreamContainer .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer waarnaar gekopieerd moet worden. |
| lengte | long | Het aantal te schrijven bytes. |

