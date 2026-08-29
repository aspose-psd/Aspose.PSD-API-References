---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD för Java API-referens"
description: "Bildskapardeskriptorn som specificerar skaparegenskaperna."
type: docs
weight: 119
url: /sv/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Image creator descriptor som specificerar skaparegenskaperna. Creator descriptor används för att övervinna behovet av att innehålla varje image creator-instans i minnet och problem med flertrådad körning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Bestämmer om image creator kan skapa en ny bild med hjälp av  imageOptions . |
| [createInstance()](#createInstance--) | Skapar en ny skapareinstans. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Bestämmer om image creator kan skapa en ny bild med hjälp av  imageOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |

**Returns:**
boolean -  true  om image creator som skapats av detta deskriptör kan skapa bilddata med den angivna  imageOptions ; annars,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Skapar en ny skapareinstans.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
