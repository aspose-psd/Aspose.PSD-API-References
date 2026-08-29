---
title: "IImageLoaderDescriptor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Yükleyici özelliklerini belirten görüntü yükleyici tanımlayıcısı."
type: docs
weight: 124
url: /tr/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Yükleyici özelliklerini belirten görüntü yükleyici tanımlayıcısı. Yükleyici tanımlayıcısı, her görüntü yükleyici örneğinin bellekte tutulması gerekliliğini ve çok iş parçacıklı sorunları aşmak için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak loadOptions kullanıp kullanmayacağını belirler. |
| [createInstance()](#createInstance--) | Yeni bir yükleyici örneği oluşturur. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak loadOptions kullanıp kullanmayacağını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | loadOptions tarafından belirtilen dosya formatı ayrıntıları. loadOptions null olabilir. |

**Returns:**
boolean - bu tanımlayıcı tarafından oluşturulan görüntü yükleyicisi akıştan görüntü okuyabiliyorsa true; aksi takdirde false.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Yeni bir yükleyici örneği oluşturur.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
