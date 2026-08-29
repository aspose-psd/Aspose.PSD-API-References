---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt de afbeeldingsexporteurdescriptor voor."
type: docs
weight: 122
url: /nl/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Stelt de descriptor van de afbeeldingsexporter voor. De descriptor van de exporter wordt gebruikt om de noodzaak te omzeilen elke exporter‑instantie in het geheugen te bevatten en problemen met multithreading.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Bepaalt of de afbeeldingsexporter de opgegeven afbeelding kan exporteren naar het opgegeven afbeeldingsformaat dat is gespecificeerd door de opslagopties. |
| [createInstance()](#createInstance--) | Maakt een nieuwe exporter‑instantie aan. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Bepaalt of de afbeeldingsexporter de opgegeven afbeelding kan exporteren naar het opgegeven afbeeldingsformaat dat is gespecificeerd door de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te exporteren. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De basis van de opties. |

**Returns:**
boolean -  true  als de door deze descriptor gemaakte exporter de opgegeven afbeelding kan exporteren naar het opgegeven bestandsformaat; anders,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Maakt een nieuwe exporter‑instantie aan.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
