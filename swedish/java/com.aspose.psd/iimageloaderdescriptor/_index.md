---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD för Java API-referens"
description: "Bildläsardeskriptorn som specificerar läsarens egenskaper."
type: docs
weight: 124
url: /sv/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Bildläsarens beskrivning som specificerar laddarens egenskaper. Laddarens beskrivning används för att övervinna behovet av att hålla varje bildläsarinstans i minnet samt problem med multitrådning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med hjälp av  loadOptions . |
| [createInstance()](#createInstance--) | Skapar en ny laddarinstans. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bestämmer om bildläsaren kan läsa en ny bild från den angivna strömmen och eventuellt med hjälp av  loadOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Filformatdetaljerna som specificeras av  loadOptions .  loadOptions  kan vara null. |

**Returns:**
boolean -  true  om bildläsaren som skapats av denna beskrivning kan läsa bild från strömmen; annars,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Skapar en ny laddarinstans.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
