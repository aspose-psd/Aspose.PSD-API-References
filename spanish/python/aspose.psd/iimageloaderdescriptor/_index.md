---
title: "Clase IImageLoaderDescriptor"
type: docs
weight: 1820
url: /es/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene el formato compatible. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando el <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del cargador. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando el <paramref name="loadOptions" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Los detalles del formato de archivo especificados por <paramref name="loadOptions" />. El <paramref name="loadOptions" /> puede ser nulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el cargador de imágenes creado por este descriptor puede leer la imagen del flujo; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del cargador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Una nueva instancia del cargador. |


