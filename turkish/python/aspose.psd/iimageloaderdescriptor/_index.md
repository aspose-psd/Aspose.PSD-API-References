---
title: "IImageLoaderDescriptor Sınıfı"
type: docs
weight: 1820
url: /tr/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Desteklenen formatı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak <paramref name="loadOptions" /> kullanıp kullanmayacağını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir yükleyici örneği oluşturur. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak <paramref name="loadOptions" /> kullanıp kullanmayacağını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | <paramref name="loadOptions" /> tarafından belirtilen dosya biçimi ayrıntıları. <paramref name="loadOptions" /> null olabilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu tanımlayıcı tarafından oluşturulan görüntü yükleyicisi akıştan görüntü okuyabiliyorsa <c>true</c>; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir yükleyici örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Yeni bir yükleyici örneği. |


