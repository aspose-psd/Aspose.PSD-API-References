---
title: "IImageLoaderDescriptor‑klass"
type: docs
weight: 1820
url: /sv/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar det stödjade formatet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med hjälp av <paramref name=\"loadOptions\" />. |
| [create_instance()](#create_instance__2) | Skapar en ny laddarinstans. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med hjälp av <paramref name=\"loadOptions\" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Filformatdetaljerna som anges av <paramref name=\"loadOptions\" />. <paramref name=\"loadOptions\" /> kan vara null. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bildläsaren som skapats av denna beskrivare kan läsa bild från strömmen; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny laddarinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | En ny laddarinstans. |


