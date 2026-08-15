---
title: "Clase StreamSource"
type: docs
weight: 40
url: /es/python-net/aspose.psd.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.psd.sources](/psd/python-net/aspose.psd.sources/)

**Full Name:** aspose.psd.sources.StreamSource

**Inheritance:** Source

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StreamSource(stream)](#StreamSource_stream_1) | Inicializa una nueva instancia de la clase [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Inicializa una nueva instancia de la clase [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Obtiene un valor que indica si el flujo debe ser eliminado cuando el contenedor se elimina. |
| flujo | _io.BufferedRandom | r | Obtiene el flujo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtiene el contenedor del flujo. |


### Constructor: StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Inicializa una nueva instancia de la clase [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo a abrir. |

### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Inicializa una nueva instancia de la clase [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo a abrir. |
| dispose_stream | bool | si se establece en <c>true</c> el flujo será eliminado. |

### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtiene el contenedor del flujo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | el contenedor del flujo. |


