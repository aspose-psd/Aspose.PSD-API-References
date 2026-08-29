---
title: "FileStreamContainer klass"
type: docs
weight: 1270
url: /sv/python-net/aspose.psd/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Anger antal läs- och skrivbyte vid sekventiell läsning. |
| can_read | bool | r | Hämtar ett värde som indikerar om strömmen stöder läsning. |
| can_seek | bool | r | Hämtar ett värde som indikerar om strömmen stöder sökning. |
| can_write | bool | r | Hämtar ett värde som indikerar om strömmen stöder skrivning. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| file_path | string | r | Hämtar filsökvägen. |
| is_created | bool | r | Hämtar ett värde som indikerar om strömmen skapades explicit. |
| is_stream_disposed_on_close | bool | r | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| is_temporal | bool | r/w | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| längd | long | r/w | Hämtar eller anger strömmens längd i byte. Detta värde är mindre än  av startpositionen för strömmen som skickas till StreamContainer-konstruktorn. |
| position | long | r/w | Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till StreamContainer-konstruktorn. |
| stream | _io.BufferedRandom | r | Hämtar datastreamen. |
| sync_root | object | r | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Skapar en ny filström. |
| flush() | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte. |
| [read(bytes)](#read_bytes_4) | Läser byte för att fylla den angivna bytebufferten. |
| [read_byte()](#read_byte__5) | Läser ett byte från strömmen och flyttar positionen i strömmen framåt med ett byte, eller returnerar -1 om slutet av strömmen har nåtts. |
| [save(destination_stream)](#save_destination_stream_6) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) och strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(file_path)](#save_file_path_9) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) och strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [seek(offset, origin)](#seek_offset_origin_12) | Ställer in positionen inom den aktuella strömmen. |
| seek_begin() | Ställer in strömmens position till början av strömmen. Detta värde representerar förskjutning från startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn. |
| [to_bytes()](#to_bytes__13) | Konverterar strömmens data till en int‑array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_14) | Konverterar strömmens data till en int‑array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_15) | Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i strömmen framåt med antalet skrivna byte. |
| [write(bytes)](#write_bytes_16) | Skriver alla angivna byte till strömmen. |
| [write_byte(value)](#write_byte_value_17) | Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte. |
| [write_to(stream_container)](#write_to_stream_container_18) | Kopierar det innehållande datat till en annan [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_19) | Kopierar det innehållande datat till en annan [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Skapar en ny filström.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_location | string | Filplatsen. |
| is_temporal | bool | Om den är inställd på <c>true</c> är filströmbehållaren temporär. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | Filströmbehållaren. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_location | string | Filplatsen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | Filströmbehållaren. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| buffer | byte | En array av byte. När denna metod returnerar innehåller bufferten den angivna byte‑arrayen med värdena mellan <paramref name="offset" /> och (<paramref name="offset" /> + <paramref name="count" /> - 1) ersatta av de byte som lästs från den aktuella källan. |
| offset | int | Det nollbaserade byte‑offsetet i <paramref name="buffer" /> där lagringen av data som lästs från den aktuella strömmen ska börja. |
| count | int | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet av strömmen har nåtts. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

Läser byte för att fylla den angivna bytebufferten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte att fylla. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Läser ett byte från strömmen och flyttar positionen i strömmen framåt med ett byte, eller returnerar -1 om slutet av strömmen har nåtts.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den osignerade byten kastad till en Int32, eller -1 om slutet av strömmen har nåtts. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) och strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara datan till. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara datan till. |
| buffer_size | int | Bufferten. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara datan till. |
| buffer_size | int | Buffertstorleken. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | Strömdatans längd att kopiera. Som standard är längden satt till värdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) och strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatana till. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatana till. |
| buffer_size | int | Buffertstorleken. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatana till. |
| buffer_size | int | Buffertstorleken. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | Strömdatans längd att kopiera. Som standard är längden satt till värdet [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_12}


```
 seek(offset, origin) 
```

Ställer in positionen inom den aktuella strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| offset | long | En byteoffset relativt parametern <paramref name\="origin\" />. Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Ett värde av typen SeekOrigin som indikerar referenspunkten som används för att erhålla den nya positionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Den nya positionen inom den aktuella strömmen. |


### Method: to_bytes() {#to_bytes__13}


```
 to_bytes() 
```

Konverterar strömmens data till en int‑array.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Strömdatana konverterade till int‑arrayen. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_14}


```
 to_bytes(position, bytes_count) 
```

Konverterar strömmens data till en int‑array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att börja läsa byte från. |
| bytes_count | long | Antalet byte att läsa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Strömdatana konverterade till int‑arrayen. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_15}


```
 write(buffer, offset, count) 
```

Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i strömmen framåt med antalet skrivna byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| buffer | byte | En bytearray. Denna metod kopierar <paramref name\="count\" /> byte från <paramref name\="buffer\" /> till den aktuella strömmen. |
| offset | int | Den nollbaserade byteoffseten i <paramref name\="buffer\" /> där kopieringen av byte till den aktuella strömmen ska börja. |
| count | int | Antalet byte som ska skrivas till den aktuella strömmen. |

### Method: write(bytes) {#write_bytes_16}


```
 write(bytes) 
```

Skriver alla angivna byte till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte att skriva. |

### Method: write_byte(value) {#write_byte_value_17}


```
 write_byte(value) 
```

Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | byte | Byte att skriva till strömmen. |

### Method: write_to(stream_container) {#write_to_stream_container_18}


```
 write_to(stream_container) 
```

Kopierar det innehållande datat till en annan [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att kopiera till. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_19}


```
 write_to(stream_container, length) 
```

Kopierar det innehållande datat till en annan [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att kopiera till. |
| längd | long | Antalet byte att skriva. |

