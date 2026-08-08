---
title: "SplitStreamContainer"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en delad strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner."
type: docs
weight: 102
url: /sv/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Representerar en delad strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
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
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getLength()](#getLength--) | Hämtar eller anger strömmens längd i byte. |
| [getPosition()](#getPosition--) | Hämtar eller anger den aktuella positionen i strömmen. |
| [getStream()](#getStream--) | Hämtar datastreamen. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Infogar strömbehållaren på angiven position. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Läser byte för att fylla den angivna bytebufferten. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte. |
| [readByte()](#readByte--) | Läser ett byte från strömmen och flyttar positionen i strömmen framåt med ett byte, eller returnerar -1 om slutet av strömmen har nåtts. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Sparar (kopierar) all strömmens data till den angivna strömmen. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Anger positionen i den aktuella strömmen. |
| [seekBegin()](#seekBegin--) | Anger strömmens position till början av strömmen. |
| [setLength(long value)](#setLength-long-) | Hämtar eller anger strömmens längd i byte. |
| [setPosition(long value)](#setPosition-long-) | Hämtar eller anger den aktuella positionen i strömmen. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Konverterar strömmens data till  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Konverterar strömmens data till  byte  array. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Utför en explicit konvertering från  com.aspose.imaging.StreamContainer  till  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Skriver alla angivna byte till strömmen. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte. |
| [writeByte(byte value)](#writeByte-byte-) | Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Kopierar den innehållande datan till en annan  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Kopierar den innehållande datan till en annan  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Datastreamen. |
| disposeStream | boolean | om den är inställd på  true  kommer strömmen att disponeras när behållaren disponeras. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initierar en ny instans av klassen [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| disposeStream | boolean | om den är inställd på  true  disponeras strömmen. |

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
public final Object getSyncRoot()
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
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Infogar strömbehållaren på angiven position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Positionen att infoga i. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att infoga. |
| disposeStream | boolean | om den är inställd på  true  disponeras strömmen. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Hämtar ett värde som indikerar om denna ström avyttras vid stängning.

Värde:  true  om strömmen disponeras vid stängning; annars,  false .

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

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Strömmen att spara data till. |
| bufferSize | int | Buffertstorleken. Som standard används värdet [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT). |
| length | long | Strömdataens längd att kopiera. Som standard är längden satt till värdet Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

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

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| längd | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Anger positionen i den aktuella strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | long | En byteoffset relativt parametern  origin . Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer-konstruktorn. |
| origin | int | Ett värde av typen [SeekOrigin](../../com.aspose.psd/seekorigin) som indikerar referenspunkten som används för att erhålla den nya positionen. |

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

