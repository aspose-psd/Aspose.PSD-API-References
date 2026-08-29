---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar bildexportörsdeskriptorn."
type: docs
weight: 122
url: /sv/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Representerar bildexportörens beskrivning. Exportörbeskrivningen används för att övervinna behovet av att hålla varje exportörinstans i minnet och problem med flertrådad körning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen. |
| [createInstance()](#createInstance--) | Skapar en ny exportörinstans. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden som ska exporteras. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativbasen. |

**Returns:**
boolean - true om exportören som skapats av denna beskrivning kan exportera den angivna bilden till det angivna filformatet; annars false.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Skapar en ny exportörinstans.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
