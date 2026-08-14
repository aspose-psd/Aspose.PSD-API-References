---
title: "Classe SplitStreamContainer"
type: docs
weight: 4220
url: /it/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Specifica il conteggio dei byte di lettura e scrittura durante la lettura sequenziale. |
| can_read | bool | r | Restituisce un valore che indica se lo stream supporta la lettura. |
| can_seek | bool | r | Restituisce un valore che indica se lo stream supporta lo spostamento. |
| can_write | bool | r | Restituisce un valore che indica se lo stream supporta la scrittura. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| is_stream_disposed_on_close | bool | r | Restituisce un valore che indica se questo stream viene eliminato alla chiusura. |
| lunghezza | long | r/w | Ottiene o imposta la lunghezza dello stream in byte. Questo valore è inferiore al  dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| position | long | r/w | Ottiene o imposta la posizione corrente all'interno dello stream. Questo valore rappresenta lo spostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| flusso | _io.BufferedRandom | r | Restituisce lo stream di dati. |
| sync_root | object | r | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| flush() | Svuota tutti i buffer per questo stream e provoca la scrittura di tutti i dati memorizzati nel dispositivo sottostante. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Inserisce il contenitore di stream nella posizione specificata. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream del numero di byte letti. |
| [read(bytes)](#read_bytes_3) | Legge byte per riempire il buffer di byte specificato. |
| [read_byte()](#read_byte__4) | Legge un byte dallo stream e avanza la posizione all'interno dello stream di un byte, oppure restituisce -1 se è alla fine dello stream. |
| [save(destination_stream)](#save_destination_stream_5) | Salva (copia) i dati dello stream nello stream specificato. Utilizza la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) e il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Salva (copia) tutti i dati dello stream nello stream specificato. Utilizza il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Salva (copia) i dati dello stream nello stream specificato. |
| [save(file_path)](#save_file_path_8) | Salva (copia) i dati dello stream nello stream specificato. Utilizza la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) e il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Salva (copia) i dati del flusso nello stream specificato. Utilizza il valore del flusso [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Salva (copia) i dati dello stream nello stream specificato. |
| [seek(offset, origin)](#seek_offset_origin_11) | Imposta la posizione all'interno del flusso corrente. |
| seek_begin() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta lo spostamento dalla posizione iniziale del flusso passata nel costruttore di StreamContainer. |
| [to_bytes()](#to_bytes__12) | Converte i dati del flusso in un array di interi. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Converte i dati del flusso in un array di interi. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente all'interno di questo flusso del numero di byte scritti. |
| [write(bytes)](#write_bytes_15) | Scrive tutti i byte specificati nello stream. |
| [write_byte(value)](#write_byte_value_16) | Scrive un byte nella posizione corrente del flusso e avanza la posizione all'interno del flusso di un byte. |
| [write_to(stream_container)](#write_to_stream_container_17) | Copia i dati contenuti in un altro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | Copia i dati contenuti in un altro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso di dati. |
| dispose_stream | bool | se impostato su <c>true</c> il flusso verrà eliminato quando il contenitore verrà eliminato. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il flusso di dati. |
| dispose_stream | bool | se impostato su <c>true</c> il flusso verrà eliminato quando il contenitore verrà eliminato. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Inserisce il contenitore di stream nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione in cui inserire. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso da inserire. |
| dispose_stream | bool | se impostato su <c>true</c> elimina il flusso. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream del numero di byte letti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| buffer | byte | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori compresi tra <paramref name="offset" /> e (<paramref name="offset" /> + <paramref name="count" /> - 1) sostituiti dai byte letti dalla sorgente corrente. |
| offset | int | L'offset di byte basato su zero in <paramref name="buffer" /> a partire dal quale iniziare a memorizzare i dati letti dal flusso corrente. |
| conteggio | int | Il numero massimo di byte da leggere dal flusso corrente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tali byte non sono attualmente disponibili, o zero (0) se è stato raggiunto la fine del flusso. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Legge byte per riempire il buffer di byte specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte da riempire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il numero di byte letti. Questo valore può essere inferiore al numero di byte nel buffer se non ci sono abbastanza byte nel flusso. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Legge un byte dallo stream e avanza la posizione all'interno dello stream di un byte, oppure restituisce -1 se è alla fine dello stream.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il byte senza segno convertito in Int32, o -1 se si è alla fine del flusso. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Salva (copia) i dati dello stream nello stream specificato. Utilizza la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) e il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Salva (copia) tutti i dati dello stream nello stream specificato. Utilizza il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | Il buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Salva (copia) i dati dello stream nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene utilizzato il valore ReadWriteBytesCount. |
| length | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita la lunghezza è impostata al valore [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Salva (copia) i dati dello stream nello stream specificato. Utilizza la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) e il valore dello stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dello stream. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Salva (copia) i dati del flusso nello stream specificato. Utilizza il valore del flusso [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dello stream. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Salva (copia) i dati dello stream nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dello stream. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | La lunghezza dei dati dello stream da copiare. Per impostazione predefinita la lunghezza è impostata al valore [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Imposta la posizione all'interno del flusso corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| offset | long | Un offset di byte relativo al parametro <paramref name=\"origin\" />. Questo valore rappresenta l'offset dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Un valore di tipo SeekOrigin che indica il punto di riferimento usato per ottenere la nuova posizione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | La nuova posizione all'interno dello stream corrente. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Converte i dati del flusso in un array di interi.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | I dati dello stream convertiti in un array di interi. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Converte i dati del flusso in un array di interi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui iniziare a leggere i byte. |
| bytes_count | long | Il conteggio dei byte da leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | I dati dello stream convertiti in un array di interi. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente all'interno di questo flusso del numero di byte scritti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| buffer | byte | Un array di byte. Questo metodo copia <paramref name=\"count\" /> byte da <paramref name=\"buffer\" /> allo stream corrente. |
| offset | int | L'offset di byte basato su zero in <paramref name=\"buffer\" /> al quale iniziare a copiare i byte nello stream corrente. |
| conteggio | int | Il numero di byte da scrivere nello stream corrente. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Scrive tutti i byte specificati nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte da scrivere. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Scrive un byte nella posizione corrente del flusso e avanza la posizione all'interno del flusso di un byte.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | byte | Il byte da scrivere nello stream. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

Copia i dati contenuti in un altro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream in cui copiare. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

Copia i dati contenuti in un altro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream in cui copiare. |
| lunghezza | long | Il conteggio dei byte da scrivere. |

