---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De afbeeldingsladerscriptor die de lader-eigenschappen specificeert."
type: docs
weight: 124
url: /nl/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

De image loader descriptor die de loader-eigenschappen specificeert. De loader descriptor wordt gebruikt om de noodzaak te omzeilen om elke image loader‑instantie in het geheugen te houden en problemen met multithreading.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Bepaalt of de image loader een nieuw beeld kan lezen van de opgegeven stream en optioneel met de  loadOptions . |
| [createInstance()](#createInstance--) | Maakt een nieuwe loader‑instantie. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bepaalt of de image loader een nieuw beeld kan lezen van de opgegeven stream en optioneel met de  loadOptions .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De bestandsformaatdetails gespecificeerd door  loadOptions . De  loadOptions  kan null zijn. |

**Returns:**
boolean -  true  als de door deze descriptor gemaakte image loader een afbeelding kan lezen van de stream; anders,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Maakt een nieuwe loader‑instantie.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
