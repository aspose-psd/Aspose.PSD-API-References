---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De afbeeldingsmakerdescriptor die de maker-eigenschappen specificeert."
type: docs
weight: 119
url: /nl/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

De image creator descriptor die de creator properties specificeert. De creator descriptor wordt gebruikt om de noodzaak te omzeilen elk image creator instance in het geheugen te bevatten en multithreading-problemen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Bepaalt of de image creator een nieuw beeld kan maken met behulp van de  imageOptions . |
| [createInstance()](#createInstance--) | Maakt een nieuwe creator‑instance. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Bepaalt of de image creator een nieuw beeld kan maken met behulp van de  imageOptions .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De afbeeldingsopties. |

**Returns:**
boolean -  true  als de image creator die door deze descriptor is gemaakt beeldgegevens kan maken met de opgegeven  imageOptions ; anders,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Maakt een nieuwe creator‑instance.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
