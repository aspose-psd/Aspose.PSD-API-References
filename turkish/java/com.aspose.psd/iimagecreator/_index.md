---
title: "IImageCreator"
second_title: "Java için Aspose.PSD API Referansı"
description: "Görüntü oluşturucu."
type: docs
weight: 118
url: /tr/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

Görüntü oluşturucu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | Yeni bir görüntü örneği, imageOptions ile oluşturur. |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


Yeni bir görüntü örneği, imageOptions ile oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Görüntü verisinin oluşturulacağı akış konteyneri. |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |
| width | int | yeni görüntünün genişliği |
| height | int | yeni görüntünün yüksekliği |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
