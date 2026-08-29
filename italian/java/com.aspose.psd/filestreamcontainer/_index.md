---
title: "FileStreamContainer"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Helper per l'elaborazione del flusso di file."
type: docs
weight: 44
url: /it/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Helper per l'elaborazione del flusso di file.
## Campi

| Campo | Descrizione |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Specifica il conteggio dei byte letti e scritti durante la lettura sequenziale. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canRead()](#canRead--) | Restituisce un valore che indica se il flusso supporta la lettura. |
| [canSeek()](#canSeek--) | Restituisce un valore che indica se il flusso supporta la ricerca. |
| [canWrite()](#canWrite--) | Restituisce un valore che indica se il flusso supporta la scrittura. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crea un nuovo flusso di file. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Pulisce tutti i buffer per questo flusso e fa sì che tutti i dati memorizzati vengano scritti sul dispositivo sottostante. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFilePath()](#getFilePath--) | Ottiene il percorso del file. |
| [getLength()](#getLength--) | Restituisce o imposta la lunghezza del flusso in byte. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione corrente all'interno del flusso. |
| [getStream()](#getStream--) | Restituisce il flusso di dati. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | Ottiene un valore che indica se il flusso è stato creato esplicitamente. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Restituisce un valore che indica se questo flusso viene eliminato alla chiusura. |
| [isTemporal()](#isTemporal--) | Ottiene o imposta un valore che indica se il flusso è temporale. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Apre un flusso di file esistente. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | Apre un flusso di file esistente. |
| [read(byte[] bytes)](#read-byte---) | Legge i byte per riempire il buffer di byte specificato. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Legge una sequenza di byte dal flusso corrente e avanza la posizione all'interno del flusso del numero di byte letti. |
| [readByte()](#readByte--) | Legge un byte dal flusso e avanza la posizione all'interno del flusso di un byte, oppure restituisce -1 se si è alla fine del flusso. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Salva (copia) tutti i dati del flusso nello stream specificato. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath)](#save-java.lang.String-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Salva (copia) i dati del flusso nello stream specificato. |
| [seek(long offset, int origin)](#seek-long-int-) | Imposta la posizione all'interno del flusso corrente. |
| [seekBegin()](#seekBegin--) | Imposta la posizione del flusso all'inizio del flusso. |
| [setLength(long value)](#setLength-long-) | Restituisce o imposta la lunghezza del flusso in byte. |
| [setPosition(long value)](#setPosition-long-) | Restituisce o imposta la posizione corrente all'interno del flusso. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Ottiene o imposta un valore che indica se il flusso è temporale. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Converte i dati del flusso in un array di byte. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converte i dati del flusso in un array di byte. |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | Esegue una conversione esplicita da [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | Esegue una conversione esplicita da [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Esegue una conversione esplicita da  com.aspose.imaging.StreamContainer  a  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Scrive tutti i byte specificati nello stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Scrive una sequenza di byte nello stream corrente e avanza la posizione corrente all'interno di questo stream del numero di byte scritti. |
| [writeByte(byte value)](#writeByte-byte-) | Scrive un byte nella posizione corrente del flusso e avanza la posizione all'interno del flusso di un byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Copia i dati contenuti in un altro  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Copia i dati contenuti in un altro  StreamContainer . |
### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Specifica il conteggio dei byte letti e scritti durante la lettura sequenziale.

### canRead() {#canRead--}
```
public boolean canRead()
```


Restituisce un valore che indica se il flusso supporta la lettura.

Valore:  true  se lo stream supporta la lettura; altrimenti,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Restituisce un valore che indica se il flusso supporta la ricerca.

Valore:  true  se lo stream supporta lo spostamento; altrimenti,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Restituisce un valore che indica se il flusso supporta la scrittura.

Valore:  true  se lo stream supporta la scrittura; altrimenti,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crea un nuovo flusso di file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileLocation | java.lang.String | La posizione del file. |
| isTemporal | boolean | Se impostato su  true  il contenitore del flusso di file è temporale. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Rilascia l'istanza corrente.

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
### flush() {#flush--}
```
public void flush()
```


Pulisce tutti i buffer per questo flusso e fa sì che tutti i dati memorizzati vengano scritti sul dispositivo sottostante.

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


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Ottiene il percorso del file.

Valore: Il percorso del file.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public long getLength()
```


Ottiene o imposta la lunghezza dello stream in byte. Questo valore è inferiore a  System.IO.Stream.Length  della posizione iniziale dello stream passata nel costruttore di StreamContainer.

Valore: La lunghezza dello stream.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Ottiene o imposta la posizione corrente all'interno dello stream. Questo valore rappresenta lo spostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer.

Valore: La posizione corrente dello stream.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Restituisce il flusso di dati.

Valore: Lo stream di dati.

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


Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

Valore: L'oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

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


Ottiene un valore che indica se il flusso è stato creato esplicitamente.

Valore:  true  se il flusso è stato creato esplicitamente; altrimenti,  false .

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Restituisce un valore che indica se questo flusso viene eliminato alla chiusura.

Valore:  true  se lo stream viene eliminato alla chiusura; altrimenti,  false .

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


Ottiene o imposta un valore che indica se il flusso è temporale.

Valore:  true  se il flusso è temporale; altrimenti,  false .

--------------------

Un flusso temporale si rimuoverà da sé quando viene eliminato. Se il flusso è basato sulla memoria, questa proprietà non ha effetto. Il flusso può essere contrassegnato come temporale o persistente nel caso sia stato creato esplicitamente; altrimenti viene sollevata l'eccezione appropriata.

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


Apre un flusso di file esistente. Se il flusso di file non esiste, viene sollevata l'eccezione appropriata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileLocation | java.lang.String | La posizione del file. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


Apre un flusso di file esistente. Se il flusso di file non esiste, viene sollevata l'eccezione appropriata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileLocation | java.lang.String | La posizione del file. |
| disposeDuplicatedStreams | boolean | se impostato su  true  elimina i flussi duplicati. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Legge i byte per riempire il buffer di byte specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte da riempire. |

**Returns:**
int - Il numero di byte letti. Questo valore può essere inferiore al numero di byte nel buffer se non ci sono abbastanza byte nello stream.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Legge una sequenza di byte dal flusso corrente e avanza la posizione all'interno del flusso del numero di byte letti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori tra  offset  e ( offset  +  count  - 1) sostituiti dai byte letti dalla sorgente corrente. |
| offset | int | L'offset di byte basato su zero in  buffer  al quale iniziare a memorizzare i dati letti dallo stream corrente. |
| count | int | Il numero massimo di byte da leggere dallo stream corrente. |

**Returns:**
int - Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tali byte non sono attualmente disponibili, o zero (0) se è stato raggiunto la fine dello stream.
### readByte() {#readByte--}
```
public int readByte()
```


Legge un byte dal flusso e avanza la posizione all'interno del flusso di un byte, oppure restituisce -1 se si è alla fine del flusso.

**Returns:**
int - Il byte senza segno convertito in un Int32, o -1 se è alla fine dello stream.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Salva (copia) i dati dello stream nello stream specificato. Usa la dimensione predefinita del buffer  ReadWriteBytesCount  e il valore di  Length  dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Salva (copia) tutti i dati dello stream nello stream specificato. Usa il valore di  Length  dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |
| bufferSize | int | Il buffer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Lo stream in cui salvare i dati. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene utilizzato il valore ReadWriteBytesCount. |
| lunghezza | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita la lunghezza è impostata al valore Length. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Salva (copia) i dati dello stream nello stream specificato. Usa la dimensione predefinita del buffer  ReadWriteBytesCount  e il valore di  Length  dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Salva (copia) i dati dello stream nello stream specificato. Utilizza il valore Length dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene utilizzato il valore ReadWriteBytesCount. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dello stream. |
| bufferSize | int | La dimensione del buffer. Per impostazione predefinita viene utilizzato il valore ReadWriteBytesCount. |
| lunghezza | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita la lunghezza è impostata al valore Length. |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Imposta la posizione all'interno del flusso corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset | long | Un offset di byte relativo al parametro origin. Questo valore rappresenta lo scostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| origin | int | Un valore di tipo  System.IO.SeekOrigin  che indica il punto di riferimento utilizzato per ottenere la nuova posizione. |

**Returns:**
long - La nuova posizione all'interno dello stream corrente.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Imposta la posizione dello stream all'inizio dello stream. Questo valore rappresenta lo scostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Ottiene o imposta la lunghezza dello stream in byte. Questo valore è inferiore a  System.IO.Stream.Length  della posizione iniziale dello stream passata nel costruttore di StreamContainer.

Valore: La lunghezza dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Ottiene o imposta la posizione corrente all'interno dello stream. Questo valore rappresenta lo spostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer.

Valore: La posizione corrente dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


Ottiene o imposta un valore che indica se il flusso è temporale.

Valore:  true  se il flusso è temporale; altrimenti,  false .

--------------------

Un flusso temporale si rimuoverà da sé quando viene eliminato. Se il flusso è basato sulla memoria, questa proprietà non ha effetto. Il flusso può essere contrassegnato come temporale o persistente nel caso sia stato creato esplicitamente; altrimenti viene sollevata l'eccezione appropriata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Converte i dati del flusso in un array di byte.

**Returns:**
byte[] - I dati dello stream convertiti nell'array byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Converte i dati del flusso in un array di byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui iniziare a leggere i byte. |
| bytesCount | long | Il conteggio dei byte da leggere. |

**Returns:**
byte[] - I dati dello stream convertiti nell'array byte.
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


Esegue una conversione esplicita da [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a FileInputStream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Il contenitore del flusso di file. |

**Returns:**
java.io.FileInputStream - Il risultato della conversione.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


Esegue una conversione esplicita da [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a java.io.InputStream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Il contenitore del flusso di file. |

**Returns:**
java.io.InputStream - Il risultato della conversione.
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Esegue una conversione esplicita da  com.aspose.imaging.StreamContainer  a  System.IO.Stream .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

**Returns:**
com.aspose.ms.System.IO.Stream - Il risultato della conversione.
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Scrive tutti i byte specificati nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte da scrivere. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Scrive una sequenza di byte nello stream corrente e avanza la posizione corrente all'interno di questo stream del numero di byte scritti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Un array di byte. Questo metodo copia count byte da buffer allo stream corrente. |
| offset | int | L'offset di byte basato su zero in buffer a partire dal quale iniziare a copiare i byte nello stream corrente. |
| count | int | Il numero di byte da scrivere nello stream corrente. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Scrive un byte nella posizione corrente del flusso e avanza la posizione all'interno del flusso di un byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | Il byte da scrivere nello stream. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copia i dati contenuti in un altro  StreamContainer .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream in cui copiare. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copia i dati contenuti in un altro  StreamContainer .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream in cui copiare. |
| lunghezza | long | Il conteggio dei byte da scrivere. |

