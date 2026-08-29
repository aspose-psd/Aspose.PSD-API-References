---
title: "IImageCreatorDescriptor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Oluşturucu özelliklerini belirten görüntü oluşturucu tanımlayıcısı."
type: docs
weight: 119
url: /tr/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Görüntü oluşturucu özelliklerini belirten görüntü oluşturucu tanımlayıcısı. Oluşturucu tanımlayıcısı, her görüntü oluşturucu örneğinin bellekte tutulması ve çok iş parçacıklı sorunların gerekliliğini aşmak için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | imageOptions kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler. |
| [createInstance()](#createInstance--) | Yeni bir oluşturucu örneği oluşturur. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


imageOptions kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |

**Returns:**
boolean -  true  eğer bu tanımlayıcı tarafından oluşturulan görüntü oluşturucu belirtilen imageOptions kullanarak görüntü verisi oluşturabiliyorsa; aksi takdirde,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Yeni bir oluşturucu örneği oluşturur.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
