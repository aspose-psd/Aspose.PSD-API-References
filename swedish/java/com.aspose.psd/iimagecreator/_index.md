---
title: "IImageCreator"
second_title: "Aspose.PSD för Java API-referens"
description: "Bildskaparen."
type: docs
weight: 118
url: /sv/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

Bildskaparen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | Skapar en ny bildinstans med  imageOptions . |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


Skapar en ny bildinstans med  imageOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren för att skapa bilddata i. |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |
| bredd | int | bredd på ny bild |
| höjd | int | höjd på ny bild |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
