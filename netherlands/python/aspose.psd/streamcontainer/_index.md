---
title: "StreamContainer Klasse"
type: docs
weight: 4230
url: /nl/python-net/aspose.psd/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StreamContainer

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | Initialiseert een nieuw exemplaar van de [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) klasse. |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | Initialiseert een nieuw exemplaar van de [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [statisch] | int | r | Specificeert het aantal lees- en schrijfbytes bij sequentieel lezen. |
| can_read | bool | r | Haalt een waarde op die aangeeft of de stream lezen ondersteunt. |
| can_seek | bool | r | Haalt een waarde op die aangeeft of de stream zoeken ondersteunt. |
| can_write | bool | r | Haalt een waarde op die aangeeft of de stream schrijven ondersteunt. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| is_stream_disposed_on_close | bool | r | Haalt een waarde op die aangeeft of deze stream bij sluiten wordt vrijgegeven. |
| lengte | long | r/w | Haalt de streamlengte in bytes op of stelt deze in. Deze waarde is kleiner dan de  door de startstreampositie die is doorgegeven in de StreamContainer‑constructor. |
| position | long | r/w | Haalt de huidige positie binnen de stream op of stelt deze in. Deze waarde vertegenwoordigt de offset ten opzichte van de startstreampositie die is doorgegeven in de StreamContainer‑constructor. |
| stroom | _io.BufferedRandom | r | Haalt de datastream op. |
| sync_root | object | r | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| flush() | Leegt alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | Leest een reeks bytes van de huidige stream en verschuift de positie binnen de stream met het aantal gelezen bytes. |
| [read(bytes)](#read_bytes_2) | Leest bytes om de opgegeven bytebuffer te vullen. |
| [read_byte()](#read_byte__3) | Leest een byte van de stream en verschuift de positie binnen de stream met één byte, of retourneert -1 als het einde van de stream is bereikt. |
| [save(destination_stream)](#save_destination_stream_4) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaardbuffergrootte [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) en de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | Slaat (kopieert) alle gegevens van de stream op naar de opgegeven stream. Gebruikt de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [save(file_path)](#save_file_path_7) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaardbuffergrootte [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) en de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) waarde. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. |
| [seek(offset, origin)](#seek_offset_origin_10) | Stelt de positie binnen de huidige stream in. |
| seek_begin() | Stelt de streampositie in op het begin van de stream. Deze waarde vertegenwoordigt de offset ten opzichte van de startpositie van de stream die is doorgegeven in de StreamContainer‑constructor. |
| [to_bytes()](#to_bytes__11) | Converteert de streamgegevens naar een int‑array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_12) | Converteert de streamgegevens naar een int‑array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_13) | Schrijft een reeks bytes naar de huidige stream en verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes. |
| [write(bytes)](#write_bytes_14) | Schrijft alle opgegeven bytes naar de stream. |
| [write_byte(value)](#write_byte_value_15) | Schrijft een byte naar de huidige positie in de stream en verplaatst de positie binnen de stream met één byte. |
| [write_to(stream_container)](#write_to_stream_container_16) | Kopieert de ingesloten gegevens naar een andere [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_17) | Kopieert de ingesloten gegevens naar een andere [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

Initialiseert een nieuw exemplaar van de [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

Initialiseert een nieuw exemplaar van de [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De gegevensstroom. |
| dispose_stream | bool | indien ingesteld op <c>true</c> wordt de stream verwijderd wanneer de container wordt verwijderd. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

Leest een reeks bytes van de huidige stream en verschuift de positie binnen de stream met het aantal gelezen bytes.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| buffer | byte | Een array van bytes. Wanneer deze methode terugkeert, bevat de buffer de opgegeven byte‑array met de waarden tussen <paramref name="offset" /> en (<paramref name="offset" /> + <paramref name="count" /> - 1) vervangen door de bytes die zijn gelezen van de huidige bron. |
| offset | int | De nulgebaseerde byte‑offset in <paramref name="buffer" /> waarop de gegevens die van de huidige stream worden gelezen, moeten worden opgeslagen. |
| count | int | Het maximale aantal bytes dat uit de huidige stream moet worden gelezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het totale aantal bytes dat in de buffer is gelezen. Dit kan minder zijn dan het aangevraagde aantal bytes als dat aantal momenteel niet beschikbaar is, of nul (0) als het einde van de stream is bereikt. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Leest bytes om de opgegeven bytebuffer te vullen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De te vullen bytes. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het aantal gelezen bytes. Deze waarde kan minder zijn dan het aantal bytes in de buffer als er niet genoeg bytes in de stream aanwezig zijn. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

Leest een byte van de stream en verschuift de positie binnen de stream met één byte, of retourneert -1 als het einde van de stream is bereikt.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De ongetekende byte gecast naar een Int32, of -1 als het einde van de stream is bereikt. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaardbuffergrootte [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) en de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | De stream waarin de gegevens moeten worden opgeslagen. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

Slaat (kopieert) alle gegevens van de stream op naar de opgegeven stream. Gebruikt de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | De stream waarin de gegevens moeten worden opgeslagen. |
| buffer_size | int | De buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | De stream waarin de gegevens moeten worden opgeslagen. |
| buffer_size | int | De buffergrootte. Standaard wordt de waarde van [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) gebruikt. |
| length | long | De lengte van de streamgegevens om te kopiëren. Standaard is de lengte ingesteld op de waarde van [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de standaardbuffergrootte [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) en de waarde van stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de streamgegevens op te slaan. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream. Gebruikt de stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de streamgegevens op te slaan. |
| buffer_size | int | De buffergrootte. Standaard wordt de waarde van [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) gebruikt. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

Slaat (kopieert) de gegevens van de stream op naar de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de streamgegevens op te slaan. |
| buffer_size | int | De buffergrootte. Standaard wordt de waarde van [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) gebruikt. |
| length | long | De lengte van de streamgegevens om te kopiëren. Standaard is de lengte ingesteld op de waarde van [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_10}


```
 seek(offset, origin) 
```

Stelt de positie binnen de huidige stream in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| offset | long | Een byte‑offset relatief ten opzichte van de parameter <paramref name="origin" />. Deze waarde vertegenwoordigt de offset vanaf de beginnende streampositie die is doorgegeven in de StreamContainer‑constructor. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Een waarde van het type SeekOrigin die het referentiepunt aangeeft dat wordt gebruikt om de nieuwe positie te verkrijgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De nieuwe positie binnen de huidige stream. |


### Method: to_bytes() {#to_bytes__11}


```
 to_bytes() 
```

Converteert de streamgegevens naar een int‑array.

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De streamgegevens geconverteerd naar de int‑array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_12}


```
 to_bytes(position, bytes_count) 
```

Converteert de streamgegevens naar een int‑array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om bytes vanaf te lezen. |
| bytes_count | long | Het aantal bytes om te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De streamgegevens geconverteerd naar de int‑array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_13}


```
 write(buffer, offset, count) 
```

Schrijft een reeks bytes naar de huidige stream en verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| buffer | byte | Een array van bytes. Deze methode kopieert <paramref name="count" /> bytes van <paramref name="buffer" /> naar de huidige stream. |
| offset | int | De nulgebaseerde byte‑offset in <paramref name="buffer" /> waarop bytes naar de huidige stream worden gekopieerd. |
| count | int | Het aantal bytes dat naar de huidige stream moet worden geschreven. |

### Method: write(bytes) {#write_bytes_14}


```
 write(bytes) 
```

Schrijft alle opgegeven bytes naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De te schrijven bytes. |

### Method: write_byte(value) {#write_byte_value_15}


```
 write_byte(value) 
```

Schrijft een byte naar de huidige positie in de stream en verplaatst de positie binnen de stream met één byte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | byte | De byte om naar de stream te schrijven. |

### Method: write_to(stream_container) {#write_to_stream_container_16}


```
 write_to(stream_container) 
```

Kopieert de ingesloten gegevens naar een andere [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om naar te kopiëren. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_17}


```
 write_to(stream_container, length) 
```

Kopieert de ingesloten gegevens naar een andere [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om naar te kopiëren. |
| lengte | long | Het aantal bytes om te schrijven. |

