---
title: "FileStreamContainer"
second_title: "Aspose.PSD för Java API-referens"
description: "Hjälpmedel för filströmshantering."
type: docs
weight: 44
url: /sv/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Hjälpmedel för filströmshantering.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Anger antalet läs- och skrivbyte vid sekventiell läsning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canRead()](#canRead--) | Hämtar ett värde som indikerar om strömmen stöder läsning. |
| [canSeek()](#canSeek--) | Hämtar ett värde som indikerar om strömmen stöder sökning. |
| [canWrite()](#canWrite--) | Hämtar ett värde som indikerar om strömmen stöder skrivning. |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Skapar en ny filström. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFilePath()](#getFilePath--) | Hämtar filsökvägen. |
| [getLength()](#getLength--) | Hämtar eller anger strömmens längd i byte. |
| [getPosition()](#getPosition--) | Hämtar eller anger den aktuella positionen i strömmen. |
| [getStream()](#getStream--) | Hämtar datastreamen. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | Hämtar ett värde som indikerar om strömmen skapades explicit. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| [isTemporal()](#isTemporal--) | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Öppnar en befintlig filström. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | Öppnar en befintlig filström. |
| [read(byte[] bytes)](#read-byte---) | Läser byte för att fylla den angivna bytebufferten. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte. |
| [readByte()](#readByte--) | Läser ett byte från strömmen och flyttar positionen i strömmen framåt med ett byte, eller returnerar -1 om slutet av strömmen har nåtts. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Sparar (kopierar) all strömmens data till den angivna strömmen. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [seek(long offset, int origin)](#seek-long-int-) | Anger positionen i den aktuella strömmen. |
| [seekBegin()](#seekBegin--) | Anger strömmens position till början av strömmen. |
| [setLength(long value)](#setLength-long-) | Hämtar eller anger strömmens längd i byte. |
| [setPosition(long value)](#setPosition-long-) | Hämtar eller anger den aktuella positionen i strömmen. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Konverterar strömmens data till  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Konverterar strömmens data till  byte  array. |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | Utför en explicit konvertering från [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) till FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | Utför en explicit konvertering från [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) till java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Utför en explicit konvertering från  com.aspose.imaging.StreamContainer  till  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Skriver alla angivna byte till strömmen. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte. |
| [writeByte(byte value)](#writeByte-byte-) | Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Kopierar den innehållande datan till en annan  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Kopierar den innehållande datan till en annan  StreamContainer . |
### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Anger antalet läs- och skrivbyte vid sekventiell läsning.

### canRead() {#canRead--}
```
public boolean canRead()
```


Hämtar ett värde som indikerar om strömmen stöder läsning.

Värde:  true  om strömmen stöder läsning; annars,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Hämtar ett värde som indikerar om strömmen stöder sökning.

Värde:  true  om strömmen stöder sökning; annars,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Hämtar ett värde som indikerar om strömmen stöder skrivning.

Värde:  true  om strömmen stöder skrivning; annars,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Skapar en ny filström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileLocation | java.lang.String | Filens plats. |
| isTemporal | boolean | Om den är satt till  true  är filströmcontainern temporär. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Frigör den aktuella instansen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten.

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


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Hämtar filsökvägen.

Värde: Filens sökväg.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public long getLength()
```


Hämtar eller anger strömlängden i byte. Detta värde är mindre än  System.IO.Stream.Length  med startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Strömlängden.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Den aktuella strömpositionen.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Hämtar datastreamen.

Värde: Datastreamen.

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
public Object getSyncRoot()
```


Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

Värde: Objektet som kan användas för att synkronisera åtkomst till den synkroniserade resursen.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


Hämtar ett värde som indikerar om strömmen skapades explicit.

Värde:  true  om strömmen skapades explicit; annars  false .

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Hämtar ett värde som indikerar om denna ström avyttras vid stängning.

Värde:  true  om strömmen disponeras vid stängning; annars,  false .

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


Hämtar eller anger ett värde som indikerar om strömmen är temporär.

Värde:  true  om strömmen är temporär; annars  false .

--------------------

En temporär ström tar bort sig själv när den avyttras. Om strömmen är minnesbaserad har denna egenskap ingen effekt. Strömmen kan markeras som temporär eller beständig om den skapades explicit, annars kastas lämpligt undantag.

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileLocation | java.lang.String | Filens plats. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileLocation | java.lang.String | Filens plats. |
| disposeDuplicatedStreams | boolean | Om den är satt till  true  avyttras de duplicerade strömmarna. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Läser byte för att fylla den angivna bytebufferten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | byte[] | Byte att fylla. |

**Returns:**
int - Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert | byte[] | En array av byte. När den här metoden returnerar innehåller bufferten den angivna byte‑arrayen med värdena mellan  offset  och ( offset  +  count  - 1) ersatta av de byte som lästs från den aktuella källan. |
| offset | int | Det nollbaserade byte‑offsetet i  buffer  där lagringen av data som lästs från den aktuella strömmen ska börja. |
| count | int | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

**Returns:**
int - Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än antalet begärda byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet på strömmen har nåtts.
### readByte() {#readByte--}
```
public int readByte()
```


Läser ett byte från strömmen och flyttar positionen i strömmen framåt med ett byte, eller returnerar -1 om slutet av strömmen har nåtts.

**Returns:**
int - Den osignerade byte som kastas till en Int32, eller -1 om slutet på strömmen har nåtts.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek  ReadWriteBytesCount  och ström‑värdet  Length .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Sparar (kopierar) all strömmens data till den angivna strömmen. Använder ström‑värdet  Length .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |
| bufferSize | int | Bufferten. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Strömmen att spara data till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet  ReadWriteBytesCount . |
| längd | long | Strömdataens längd att kopiera. Som standard är längden satt till värdet  Length . |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek  ReadWriteBytesCount  och ström‑värdet  Length .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömdata till. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream  Length  värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömdata till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet  ReadWriteBytesCount . |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara strömdata till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet  ReadWriteBytesCount . |
| längd | long | Strömdataens längd att kopiera. Som standard är längden satt till värdet  Length . |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Anger positionen i den aktuella strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | long | En byteoffset relativt parametern  origin . Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer-konstruktorn. |
| origin | int | Ett värde av typen System.IO.SeekOrigin som anger referenspunkten som används för att erhålla den nya positionen. |

**Returns:**
long - Den nya positionen inom den aktuella strömmen.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Sätter strömmens position till början av strömmen. Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer-konstruktorn.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Hämtar eller anger strömlängden i byte. Detta värde är mindre än  System.IO.Stream.Length  med startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Strömlängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn.

Värde: Den aktuella strömpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


Hämtar eller anger ett värde som indikerar om strömmen är temporär.

Värde:  true  om strömmen är temporär; annars  false .

--------------------

En temporär ström tar bort sig själv när den avyttras. Om strömmen är minnesbaserad har denna egenskap ingen effekt. Strömmen kan markeras som temporär eller beständig om den skapades explicit, annars kastas lämpligt undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Konverterar strömmens data till  byte  array.

**Returns:**
byte[] - Strömdata konverterad till  byte  arrayen.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Konverterar strömmens data till  byte  array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att börja läsa byte från. |
| bytesCount | long | Antalet byte att läsa. |

**Returns:**
byte[] - Strömdata konverterad till  byte  arrayen.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Utför en explicit konvertering från [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) till FileInputStream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Filströmcontainern. |

**Returns:**
java.io.FileInputStream - Resultatet av konverteringen.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


Utför en explicit konvertering från [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) till java.io.InputStream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Filströmcontainern. |

**Returns:**
java.io.InputStream - Resultatet av konverteringen.
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Utför en explicit konvertering från  com.aspose.imaging.StreamContainer  till  System.IO.Stream .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |

**Returns:**
com.aspose.ms.System.IO.Stream - Resultatet av konverteringen.
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Skriver alla angivna byte till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | byte[] | Byte att skriva. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert | byte[] | En array av byte. Denna metod kopierar  count  byte från  buffer  till den aktuella strömmen. |
| offset | int | Den nollbaserade byteoffseten i  buffer  där kopieringen av byte till den aktuella strömmen ska börja. |
| count | int | Antalet byte som ska skrivas till den aktuella strömmen. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Byte att skriva till strömmen. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Kopierar den innehållande datan till en annan  StreamContainer .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att kopiera till. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Kopierar den innehållande datan till en annan  StreamContainer .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att kopiera till. |
| längd | long | Antalet byte att skriva. |

